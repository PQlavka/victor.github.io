IDEF0 "Написать реферат"  
![](https://github.com/PQlavka/victor.github.io/blob/main/lab2/01_A0.png)

Уровень 2  
![](https://github.com/PQlavka/victor.github.io/blob/main/lab2/02_A0.png)

DFD "Изучить источники"  
![](https://github.com/PQlavka/victor.github.io/blob/main/lab2/03_A1.png)

Текст 
`@startuml
skinparam actor {
	BackgroundColor White
	ArrowColor Black
	BorderColor Black
}
skinparam usecase {
	BackgroundColor White
	ArrowColor Black
	BorderColor Black
}
left to right direction
actor P0 as "человек"
actor M0 as "информационная система"
actor P as "студент"
actor M as "база данных"
usecase A as "изучение источников"
P -- (A)
(A) -- M
P0 <|-- P
M --|> M0
@enduml`

![](http://www.plantuml.com/plantuml/png/fP6_JiD03CRdtbDOcM2en0CWr9GvKZRcKtAqKTCSSYvYe4YqvS_0mAi4HDMga3o3_KOuN8EwCqJvyllipxOoAfr6LyrpLSwouaQZdeDEd4MuKuEnJcOJj5MHNjfSqDKqSqODGaHxwyaubn8fj9WQF4RtHtbLQH9TcdydvkRQWRE0sMJg8CtG92wpXVBxncUWImZuXJRqHIrzo7iV7Cp8cxIZXX-fvGVwffgVvRkbXXhHRy1Bsl6ILz8dPjyP-rJXlAPFyHfU_QNwq7UgQKirY5rtQVpAJu7ghmxxoLjU_oxNYDx0OLOhg0FxRkD0nJ0SmabugkJfPAJahFE5g5X50XONSeeQcIALN_O3)
