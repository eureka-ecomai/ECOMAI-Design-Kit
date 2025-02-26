# ECOMOD Product: System Context (_simple variant_)


The **_System Context_** lists the external entities that interact with the system.


## Purpose

The **_System Context_** depicts how the system is embedded in its environment. It shows the external entities and the communication links between the system and those entities, together with the relevant item flows.

The **_System Context_** provides answers to the following primary questions about the system model:

+ What is the name of the system of interest?
+ What is part of the system environment (and therefore not part of the system itself)?
+ Which external entities play a role in the context of the system of interest?

The **_System Context_** can also provide answers to other questions:

+ Which external entity delivers which information to system of interest?
+ Which external entity receives which information from system of interest?
+ Which protocols are used to communicate with the external entities?
+ Which (interface) technologies are used to communicate with the external entities?


## Description

The system provides functions to and requests functions from the external entities, and handles events and effects from the outside. It is essential to know the complete context of the system. Therefore the **_System Context_** is a mandatory part of the systems model, representing a black-box view on the system that delimits the system itself from its environment.

The **_System Context_** is a list of the external entities and the relevant item flows between the system and those entities. The external entities are called _System Actors_ and can be categorized basically as human user, environmental effects and external devices or systems.


## Representation

The _System Context_ is depicted typically in a **SysML Block Definition Diagram**.

The system itself is pictured as **ECOMOD stereotype «System»** and the **System Actors** are pictured with specific **ECOMOD actor stereotypes** which represents the actor concept, but are specialized **SysML Blocks**.

Any kind of interaction between the system and an actor is expressed by a communication path which is represented by the **SysML Association** relationship. The exchange of information item is represented by **SysML InformationFlow** relationships, which is a directed link that has the conveyed information items (either **UML Signal** or **UML Class** elements) assigned.


## Further Information

+ This product is produced by the methods:
  - [Define System Context (_simple variant_)](method_system-context-simple.md)

+ This product is used as input by the methods:
  - [Specify System Use Cases](method_system-usecases.md)
  - [Specify System Processes](method_system-processes.md)
  - [Describe Domain Information Items](method_system-domainentities.md)
  - [Specify System/Actor Interactions](method_system-interactions.md)
  - [Decide System Interfaces](method_system-interfaces.md)
  - [Decide System Structure](method_system-decomposition.md)


## Examples

#### System Context (simple variant)

![Example System Context (simple)](images/en-ecomod-example-00-systemcontext-simple-modelview.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
