# OOAD-WEEK08

## Use Case Diagram (ภาษาไทย)
###ส่งการบ้าน
#3

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

#4

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

#5

![](http://www.plantuml.com/plantuml/img/VLAx3eCm3Dpp5Hxfm0ymLA2Ygaj7r3abBbY4W19tglhlJH-KqA9CiNDdt-cItB6qVEsrO6ADSC8p5EEegPPCWn4QBmmyWAMcPL1aiNxTFqzf6Zzn4ydEecJSYAGQbUGMAeVMToLgP9owFHarrNgekwckJDXzLgNf5fAZDB9vpxkVvMjuABU6pmRMqDd4ghQ9udUH-U0SUVb2zMJ8iPKys0pI5Bxnn3YBv6B4HQWnOf1tZ1Q47_KNlb9sG3r2YQxxayhHAF-R7W00)
##Code

@startuml

title Web Application

left to right direction

rectangle {

(Create)

(Updath User)

(Delete User)

(Find User)

(lock User)

(Unlock User)

(Create)--> (Manage Users)

(Updath User)--> (Manage Users)

(Delete User)--> (Manage Users)

(Find User)--> (Manage Users)

(lock User)--> (Manage Users)

(Unlock User)--> (Manage Users)

}

:Website Administrator: -- (Create)

:Website Administrator: -- (Updath User)

:Website Administrator: -- (Delete User)

:Website Administrator: -- (Find User)

:Website Administrator: -- (lock User)

:Website Administrator: -- (Unlock User)

:Help Desk: -- (Find User)

@enduml




