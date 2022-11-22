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

@startuml
!pragma layout smetana

class ГОСТ-34 extends ТЗ {
+String beakColor
+swim()
+quack()
}
class ГОСТ-19 extends ТЗ {
-int sizeInFeettt
-canEat()
}
class IEEE-STD830-1998 extends ТЗ {
-int sizeInFeettt
-canEat()
}
class IEEE-29148-2011 extends Г {
-int sizeInFeettt
-canEat()
}
@enduml