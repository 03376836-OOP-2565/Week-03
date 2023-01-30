# Lab-02 ผลการทดลอง

### บันทึกผลการทดลองในไฟล์นี้


##  2.6.1  ให้คัดลอก code ไปเขียนใน plantUML เพื่อให้เกิดภาพ class diagram ดังรูปต่อไปนี้
![image](https://user-images.githubusercontent.com/115037574/215578419-19d97bf0-1033-4af1-95d8-dde471c1de64.png)


-------------

## 2.6.2 ให้เขียน code เพื่อให้เกิดภาพ class diagram ดังรูปต่อไปนี้
```puml
@startuml 
class Dog{}
class Cat{}

Cat <|.. whiteCat
Dog <|.. whiteDog
Cat <|.. blackCat
Dog <|.. blackDog
@enduml 
```
![image](https://user-images.githubusercontent.com/115037574/215578781-791ed399-2738-4d09-b42b-91df5f9211f3.png)

-------------


## 2.6.3 ให้นำ code ในรูปนี้ไปเขียนใน plantUML จะได้รูปคลาสไดอะแกรมแบบใดออกมา
![image](https://user-images.githubusercontent.com/115037574/215579121-3678917e-01d7-43be-8b9d-40e6cddecec4.png)


-------------

## 2.6.4 จงเขียน code ตามตัวอย่างในด้านขวาให้สมบูรณ์เพื่อให้แสดงภาพตามไดอะแกรมในด้านซ้าย
```puml
@startuml 
class classroom{}
class Whiteboard{}
class Table{}
class Chair{}
class Student{}
class Teacher{}

classroom o-- Whiteboard
classroom o-- Table
classroom o-- Chair
classroom o-- Student
classroom o-- Teacher
@enduml 
```
![image](https://user-images.githubusercontent.com/115037574/215579816-9e10b93a-5010-47a3-9401-cdbc4a8f0a5d.png)
-------------

## 2.6.5 จงเขียน code ตามตัวอย่างในด้านขวาให้สมบูรณ์เพื่อให้แสดงภาพตามไดอะแกรมในด้านซ้าย
```puml
@startuml 
class MotorBoat{}
class Car{}
class Helm{}
class Engine{}
class Door{}
class Wheel{}
class SteeringWheel{}

MotorBoat o-- Helm
MotorBoat o-- Engine

Car o-- Door
Car o-- Wheel
Car o-- SteeringWheel
Car o-- Engine
@enduml 
```
![image](https://user-images.githubusercontent.com/115037574/215580240-a8c7e430-4af0-413a-ae17-ee83351f21ec.png)
-------------

## 2.6.6 จงเขียน code ตามตัวอย่างในด้านขวาให้สมบูรณ์เพื่อให้แสดงภาพตามไดอะแกรมในด้านซ้าย
```puml
@startuml 
class Car{}
class Engine{}
class Door{}
class Wheel{}
class AirConditioner{}

Car <|-- "1..1" Engine
Car <|-- "2..4" Door
Car <|-- "4..4" Wheel
Car <|-- "0..1" AirConditioner
@enduml 
```
![image](https://user-images.githubusercontent.com/115037574/215581158-4f316b44-ed6c-4ccf-b858-a31d6c4a5459.png)
-------------
