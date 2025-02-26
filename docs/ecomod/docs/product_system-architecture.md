# ECOMOD Product: Logical Architecture

The **_Logical Architecture_** specifies the technical concepts and principles of the system.


## Purpose

The **_Logical Architecture_** covers the basic technical notation of the system and is reusable for similar systems like product families or generations.


## Description

The **_Logical Architecture_** describes the technical concepts and principles of the system on an abstract level.

The ISO/IEC/IEEE 42010:2011 standard defines the **_Logical Architecture_** as _"The logical view of the architecture of a system is composed of a set of related technical concepts and principles that support the logical operation of the system."_

The _System Engineering Book of Knowledge_ gives a slightly different definition: _"The logical architecture of a system is composed of a set of related technical concepts and principles that support the logical operation of the system. It includes a functional architecture, a behavioral architecture, and a temporal architecture."_

In our terminology the Functional Architecture is not part of the **_Logical Architecture_**.

The **_Logical Architecture_** should be loosely coupled with a _Base Architecture_ by linking the affected elements of the **_Logical Architecture_** to the proper elements of the _Base Architecture_ by using the _structure allocation_ concept of SysML.

The **_Logical Architecture_** provides answers to the following primary questions about the system model:

+ What building blocks is the system composed of?
+ Which system interfaces does the system offer/support?
+ Which object flows from/to system interfaces?

The **_Logical Architecture_** can also provide answers to other questions:

+ How are the building blocks of the system connected?
+ Which building blocks are responsible for which interfaces of the system?
+ Which interfaces does the building blocks offer/support?
+ Which object flows from/to the interfaces of the building blocks?


## Representation

The composition of the system by its building blocks is depicted in a **SysML Block Definition Diagram** and the building blocks on the highest level are pictured as **ECOMOD stereotype «Subsystem»**, those on lower detail level **ECOMOD stereotype «HardwareBlock»** or **ECOMOD stereotype «SoftwareBlock»**. The linking is pictured with the **SysML Composition** relationship.

The interfaces of the system are pictured as **ECOMOD stereotype «SystemPort»**, **ECOMOD stereotype «ActiveSystemPort»** or **ECOMOD stereotype «PassiveSystemPort»**; the interfaces of the building blocks are pictured as **ECOMOD stereotype «ProvidedPort»** or **ECOMOD stereotype «RequiredPort»**.

The internal connectivity of the system is depicted in a **SysML Internal Block Diagram**, the linking is pictured with the **SysML Connector** relationship and the object flow is pictured with the **SysML InformationFlow** relationship.


## Further Information

+ This product is produced by the methods:
  - [Model Logical Architecture](method_logical-architecture.md)


+ This product is used as input by the methods:
  - [Specialize Product Architecture](methods_product-architecture.md)
  - [Define System States](methods_system-states.md)
  - [Verify Architecture with Scenarios](methods_architecture-scenarios.md)


## Examples

#### Logical Architecture

![Example for Logical Architecture](images/en-ecomod-example-logicalarchitecture-modelview.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
