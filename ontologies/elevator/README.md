
# Elevator ontology

It describes elevators inside or outside a building. Used classes and properties are very small in number to describe only neccessary facts.

The purpose of this ontology is to act as basement for further ontology developments, such as Saxonoy building regulation ontology.

## Illustration

The following diagram illustrates the structure of classes and related properties.

![](https://rawgit.com/AKSW/leds-asp-f-ontologies/master/ontologies/elevator/diagram.svg)

## Parts of the elevator structure

We based our ideas of the following overview, but current dataset does not justify to model elevators in such extend. Maybe later more detailed information are neccessary.

| Part | Features / Properties | Source |
|------|------------------------|--------|
| Control panel | max./min. height above floor | DIN 81-20, 5.12.1 and <br>DIN 81-70, 5.4.2.2 |
| Position display | lighted | DIN 81-70, 5.4.2.4 |
| Well (Elevator shaft) |  | DIN 81-20, 5.2 |
| . Walls | width, depth | DIN 81-20, 5.2.5.2 |
| . . Guide rails |  | DIN 81-20, 5.7 |
| . Ceiling (headroom) |  |  |
| . Floor (pit) |  |  |
| . Buffer |  | DIN 81-20, 5.8 |
| . Lighting, emergency lighting |  | DIN 81-20, 5.2.1.4 |
| . Doors | min. clear open width | DIN 81-20, 5.3 |
| . . Protection device | e.g. light barries  | DIN 81-20, 5.3.6 |
| . Car (cabine) | max. load control (DIN 81-20, 5.12.1.2) | DIN 81-20, 5.4 |
| . . Walls | width, depth, height |  |
| . . Ceiling |  |  |
| . . Doors | min. clear open width | DIN 81-20, 5.3 |
| . . . Protection device | e.g. light barries | DIN 81-20, 5.3.6 |
| . . Lighting, emergency lighting | min. luminosity | DIN 81-20, 5.4.10 |
| . . Control panel | max./min. height above floor  | DIN 81-20, 5.12.1 and <br>DIN 81-20, table 4 |
| . . . Buttons | each level, close/open door,  symbols, min. size, relief  | DIN 81-20, 5.12.1.1.2, and<br> DIN 81-70, 5.4 |
| . . . . Emergency call | bell symbol | DIN 81-20, 5.12.3 |
| . . Position display | lighted, max./min. height above floor | DIN 81-20, 5.12.1.1.3 |
| . . Ventilation |  | DIN 81-20, 5.4.9 |
