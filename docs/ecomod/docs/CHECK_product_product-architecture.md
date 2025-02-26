# ECOMOD Product: Product Architecture

The **_Product Architecture_** specifies the concrete architecture of the system.


## Purpose

The **_Product Architecture_** makes the architectural and technical concepts of the Logical Architecture concrete.


## Description

In the system model the **_Product Architecture_** is the most detailed specification of the system, and the lowest level of abstraction of a architectural description. Typically, it is not reusable for similar systems like product families or generations.

A **_Product Architecture_** is a spezialization of the Logical Architecture, the next level of details below the **_Product Architecture_** is part of specific engineering models, for example, a software or CAD model, and out of scope of the system model.

The **_Product Architecture_** should be loosely coupled with a Base Architecture by linking the buildings blocks of the **_Product Architecture_** to the proper elements of the Logical Architecture by using SysML's _structure allocation_ concept.

The **_Product Architecture_** provides answers to the following primary questions about the system model:

+ What concrete parts is the system composed of?
+ Which concrete system interfaces does the system offer/support?
+ Which information flows from/to system interfaces?

The **_Product Architecture_** can also provide answers to other questions:

+ How are the parts of the system connected?
+ Which parts are responsible for which interfaces of the system?


## Representation

The mapping from the logical building blocks to concrete products is depicted in a **SysML Block Definition Diagram** and the concrete products are pictured either as **SysML Block** or **discipline-specific ECOMOD stereotypes**. The linking between them is pictured with the **SysML Allocation** relationship.

The composition of the system by its building blocks is depicted in a **SysML Block Definition Diagram** and the concrete products are pictured either as **SysML Block** or **discipline-specific ECOMOD stereotypes**. The linking is pictured with the **SysML Composition** relationship.

The internal connectivity of the system is depicted in a **SysML Internal Block Diagram**, the linking is pictured with the **SysML Connector** relationship and the object flow is pictured with the **SysML InformationFlow** relationship.


## Further Information

+ This product is produced by the methods:
  - [Specialize Product Architecture](methods_product-architecture.md)

+ This product is used as input by the methods:
  - [Define System States](methods_system-states.md)
  - [Verify Architecture with Scenarios](methods_architecture-scenarios.md)


## Examples

#### Product Architecture

![Example for Product Architecture](images/en-ecomod-example-productarchitecture-modelview.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
