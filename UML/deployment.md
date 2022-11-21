Deployment:
@startuml
!pragma layout smetana
package "Local Machine" {
[nodejs] as scrape
}
package "GCP" {
database "Cloud Datastore" as datastore {
[entity]
}
database "Cloud Storage" as gcs {
[bucket]
}
node "App Engine" {
frame "Standard" {
[indexer]
[web]
}
database "TaskQueue" as taskqueue {
[index-create-queue] as queue
}
}
}

actor User as user
scrape --> github : scraping
scrape -r-> bucket : put GitHub urls
bucket -d-> indexer : notification
indexer -l-> queue : put task
queue -r-> indexer : execute task
indexer -u-> entity : put
web -u-> entity : get
web -r-> user : show web page
@enduml