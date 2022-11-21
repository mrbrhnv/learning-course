Class:

@startuml
!pragma layout smetana

class Duck extends Animal {
+String beakColor
+swim()
+quack()
}
class Fish extends Animal {
-int sizeInFeettt
-canEat()
}
@enduml