# ECOMOD Method: Decide System Structure

Identify the specific points at the system boundary through which the system interacts with the system actors and decompose the system into smaller parts.

![Process Model of Determine System Architecture](images/en-iotpml-method-system-architecture.png)


## Purpose

The System Architecture defines the necessary interfaces of the system to the system environment and describes the building blocks that make up the system, along with their interfaces and the flow of information between them.


## Description

Consider the interaction points to which the system communicates with the system actors. This communication is done via so-called _system interfaces_. The users of the system and the external systems are connected via explicite system interfaces that provide and request functions; other system actors, such as sensors for example, provide information about environmental influences (like temperature or humidity) to the system so that the system is able to handle events and effects from the outside.

To better deal with the complexity of a system, the system is broken down into smaller parts. These parts are described along with their interfaces and the information exchange that occurs between them.


## Inputs

+ System Context: [simple](product_system-context-simple.md) or [complex](product_system-context.md)
+ [System Requirements](product_system-requirements.md)
+ [Domain Data Model](product_domain-data-model.md)
+ [System/Actor Interactions](product_system-interactions.md)


## Outputs

+ [System Structure](product_system-architecture.md)


## Tasks

+ -TODO- [Model System Architecture Context](task_system-architecture-context.md)
+ -TODO- [Model System Architecture Decomposition](task_system-internal-components.md)
+ -TODO- [Model Internal Interfaces](task_system-internal-interfaces.md)
+ -TODO- [Model Internal Information Flows](task_system-internal-informationflows.md)


## Further Information

### Recommendations & Tips

_None._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
