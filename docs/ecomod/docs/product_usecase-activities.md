# ECOMOD Product: Use Case Activities


_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |

---


The **_Use Case Activities_** describes the details of the behavior of a system functions on execution.


## Purpose

The **_Use Case Activities_** are the functional decomposition of the _System Use Cases_ and specify the system functionality from the _Requirements_ perspective.


## Description

A use case is defines the summary of an identified system behavior and represents its purpose, not its behavior. This is specified by an _Use Case Activity_, which defines the single functions of a use case, their order of execution and the flow of objects between the functions.


The **_Use Case Activities_** provides answers to the following primary questions about the system model:

+ Which essential steps must be carried out in which order in an use case?
+ Which system functions are performed by an an use case?
+ How does the system behave in certain situations, how does it react to external influences?

The **_Use Case Activities_** can also provide answers to other questions:

+ What scenarios of an use case exist?
+ What alternative paths through an use case exist?
+ What error cases must be handled by an use case?
+ Which information is required by an use case?
+ Which information is provided by an use case?

The ECOMOD product **_Use Case Activities_** is part of the ECOMOD product [_System Use Cases_](product_system-usecases.md) and should provide for each use case defined in the system model at least a specification of its base-path scenario.


## Representation

An _Use Case Activity_ is pictured as **ECOMOD stereotype «UCActivity»** or as **ECOMOD stereotype «ContinousUCActivity»** for a continuous use case. The workflow of an _Use Case Activity_ is depicted in a **SysML Activity Diagram** and the essential steps are pictured as **ECOMOD stereotype «EssentialStep»**, including the call of another use case (calling a continuous use cases is pictured as **ECOMOD stereotype «ContinuousEssentStep»**).


## Further Information

+ This product is produced by the methods:
  - [Identify System Use Cases](method_system-usecases.md)

+ This product is used as input by the methods:
  - [Verify Architecture with Scenarios](method_verify-architecture.md)


## Examples

#### System Use Case Activity

![Example for Use Case Activity](images/en-ecomod-example-usecaseactivities-modelview.png)

#### System Use Case Activity with Object Flows

![Example for Use Case Activity with Object Flows](images/en-ecomod-example-usecaseobjectflows-modelview.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
