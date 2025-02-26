# ECOMOD Method: Describe Domain Data

#### ---ORIGINAL---begin---
Define the terms of the domain from the perspective of the system.
#### ---ORIGINAL---end---

![Activity Model](images/en-ecomod-methods-domaindatamodel.png)


## Purpose

#### ---ORIGINAL---begin---
The Domain Knowledge defines the semantic and structure of the domain objects that are used by the system.
#### ---ORIGINAL---end---


## Description

#### ---ORIGINAL---begin---
The system has knowledge about objects of the domain. Imagine your system is a person and you ask it about domain objects.

For example:

+ You: _"Do you know the concept of an operator?"_
+ System: _"Yes. An operator is one of my users and has a name, an ID and a list of active tasks."_

+ You: _"Do you know the concept of engine operating parameters?"_
+ System: _"Yes. An engine operating parameter has a torque, an speed and a temperature."_

The Domain Knowledge defines the knowledge of the system about the domain.

You can derive the domain objects from the object flow of the Use Case Activities. If an object is input or output of a system function, the system must know the concern of that object. Typically the modeled Use Case Activities and the included object flows are not complete. Therefore only parts of the Domain Knowledge could be directly be derived from them.

Especially if you separate the input/output functions of the Use Case Activities you get two kinds of domain objects:

1. The context objects are entities that are exchanged between the system and the system actors.
2. The system objects are domain objects that are used only inside the system.

The Domain Knowledge is also known as _Concept Model_.
#### ---ORIGINAL---end---


## Inputs

+ System Context: [simple](product_system-context-simple.md) or [complex](product_system-context.md)
[System Use Case Activities](product_system-usecaseactivities.md)


## Outputs

+ [Domain Data Model](product_domain-data-model.md)


## Tasks

+ -TODO- [Model Domain Information Items](task_domain-data-model.md)


## Further Information

### Recommendations & Tips

_None._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
