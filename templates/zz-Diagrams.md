## Pie Charts

```mermaid
pie title Users
"Mobile": 55.9
"Desktop": 40.1
"Tablet": 4
```

## Graphs

```mermaid
graph TD
A-->B
```

### Direction

1. Top to Bottom
	```mermaid
	graph TB
	A-->B
	```
2. Bottom to Top
	```mermaid
	graph BT
	A-->B
	```
3. Left to Right
	```mermaid
	graph LR
	A-->B
	```
4. Right to Left
	```mermaid
	graph RL
	A-->B
	```
	
### Shapes

1. Normal Box
```mermaid
graph TD
boxa[ Normal Box with Text]
```

2. Pill Shaped Box
```mermaid
graph TD
boxa([ Normal Box with Text])
```
3. Box with Rounded edges
```mermaid
graph TD
boxa(Normal Box with Text)
```
4. Subroutine shaped Box
```mermaid
graph TD
boxa[[Normal Box with Text]]
```
5. Cylindrical Shape
```mermaid
graph LR
boxa[(Normal Box with Text)] --> boxb[(Database B)]
```
6. Circle
```mermaid
graph LR
boxa((Normal Box with Text))
```
7. Asymmetric Shape
```mermaid
graph LR
boxa>Normal Box with Text]
``` 
8. Rhombus
```mermaid
graph LR
boxa{Normal Box with Text}
```
9. Hexagon
```mermaid
graph LR
boxa{{A}}
```
10. Parallelogram 
```mermaid
graph LR
boxa[/Normal Box with Text/]
```
11. Parallelogram Alternative
```mermaid
graph LR
boxa[\Normal Box with Text\]
```
12. Trapezoid
```mermaid
graph LR
boxa[/Normal Box with Text\]
```
13. Trapezoid Alternative
```mermaid
graph LR
boxa[\Normal Box with Text/]
```

### Links

1. Arrow head
```mermaid
graph LR
A --> B
```
2. Open Link
```mermaid
graph LR
A --- B
```
3. Text on Link
```mermaid
graph LR
A --Text--> B
```
4. Dotted Link
```mermaid
graph LR
A -.-> B
```
5. Dotted Link with Text
```mermaid
graph LR
A -.Text.-> B
```
6. Thick Link
```mermaid
graph LR
A ==> B
```

## Gantt Charts

```mermaid
gantt
title Productivity Guru Videos
dateFormat DD-MM-YYYY
section Obsidian Basics
Markdown: a1, 04-07-2020, 3d
Diagrams: after a1, 07-07-2020, 2d
section OtherVideos
example Video: 01-07-2020, 5d
video2: 07-07-2020, 12d
```

## Sequence Diagrams
```mermaid
sequenceDiagram
Alice ->>John: Hello John, How are you ?
John -->>Alice: Great !
```

## Class Diagram

```mermaid
classDiagram
class Animal
Vehicle <|-- Car
```

## State Diagram
```mermaid
stateDiagram-v2
Push --> Move
Move --> Stop
```

```mermaid
stateDiagram-v2
[*] --> s1
s1 --> [*]
```

## Entity Relationship Diagram
```mermaid
erDiagram
CUSTOMER ||--O{ ORDER : places
First entity relationship  second entity; relationship label
One to zero or more
ORDER ||--|{ LINE-ITEM : contains
One to one or more line 
CUSTOMER }|..|{ DELIVERY-ADDRESS :uses
One or more customers uses one or more delivery addresses
```



## User Journey

```mermaid
journey
title My working day
section Go to work
	Make tea: 5: Me
	Go upstairs: 3: Me
	Do work: 1: Me, Cat
section Go Home
	Go downstairs: 5 : Me
	Sit down: 5: Me
```
