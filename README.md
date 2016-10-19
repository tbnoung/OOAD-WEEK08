# OOAD-WEEK08

## Use Case Diagram (ภาษาไทย)
###ส่งการบ้าน
#1

![](http://www.plantuml.com/plantuml/img/XO-z2iCm48DtFyMDyP1N25a3xP8tk3Y26EnSyPrR-lPre4kWFvkGFWaqgd6ncfCBLKqo2lKzTLeN3IKk81EQSOzug3yZKjQcc38uUVUvqS21kh29AEWYWLEqvs_ublWWJkij-Eg_nw_Owv-O9aFsRiI-jhyl)
#Code : 
@startuml

customer -- (subscribe to Reviews)

customer -- (order a meal)

(subscribe to Reviews) --> (choose Locality)

(subscribe to Reviews) --> (play)

(order a meal)-->(play)

(order a meal)-->(choose Menu)

(order a meal)-->(choose Menu Item)

@enduml

#2

![](http://www.plantuml.com/plantuml/img/XP112eD034NtEKLMHHTUO5P2Rz0RX1Ziu1ZB91QazEvEwwRO5hUVb_yVQSqf-pmcW2pif7qIV435L-41ezPGPJ79Tq6FF8YNu4pAXTfoyZYzg8lSfkpOqO96IQo69uJjvFGkQwAIMInxwW6R1Zys3i2zmG7-ooyGypIhH-tH5dCPD_PRE-HTz0-4LhGhdri1)

##Code
@startuml

rectangle {

(check in)

(reserve ticket)

(Cancle reservation)

(Report day sales)

}

:ticket&check-inassistant: -- (check in)

:ticket&check-inassistant: -- (reserve ticket)

:ticket&check-inassistant: -- (Cancle reservation)

:accounting system: -- (Report day sales)

:report day sales: -- (Report day sales)

@enduml

#3

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuGh9ICpCISnBISj9J5VGqjLLA4fDKR1II4jCBialmfHDoYbDnIDTdf5PWYJla9gN0hG40000)

#4

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKfFp4tDpKzALCZNrLLGoCZFGnL9oIz9D48Lyl7tGHNmBqijAayiISu02mS7kA69EgJcfG2j0W00)

#5

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEpoqeBKajKj3IrLLGo4wjJCelIh5AIqmkoIz2bSpDpyi42YfOAK1bYmkAClFI5NHrjM3w4799fIKb-NdOvHnIyrA0LWC0)



