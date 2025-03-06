# ECOMOD Task: Specify System Information Flows


_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |

---


Describe the relevant information flows between the actors and the system, along with the essential data and physical entities of the domain that are transported through them.


## Description

### Motivation

For a clear understanding of the system embedding, the information flow between the system and its environment is helpful. The information items defines the semantic and structure of the data and physical entities of the domain that are used by the system.

### What's To Do

Identify the information flows between the identified _System Actors_ and the system. Further, describe the information items that the system exchanges with its environment.

#### Guiding Questions

+ Which information items the system received from the actors?
+ Which information items the system provides to the actors?
+ Are the information items technically relevant to the system?

### How To Do

For each identified system actor, the relevant information items that they send to or receive from the system are modeled and noted along the _Connector_ links modeled in the task before.

#### Used Model Objects

+ Views: `SysML Internal Block Diagram`
+ Elements: `UML Signal`, `UML Class`
+ Relationships: `SysML Connector`, `UML InformationFlow`


## Inputs

+ [System Context (_simple variant_)](product_system-context-simple.md) or [System Context](product_system-context.md)


## Outputs

+ [System Context (_simple variant_)](product_system-context-simple.md) or [System Context](product_system-context.md), _enriched by:_
  - System Information Flows
  - Domain Information Items


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the _System Information Flows_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the element named `System Context` (the one having the `ECOMOD stereotype «Context»` set) within the `System Context` package.

5. Open the child diagram `System Context View` of this element.

6. Repeat the steps below for each `SysML Connector` relationship that is modeled in the Sytem Context View:

    6.1 If not already existing, create a new information item (`UML Signal` or `UML Class`) element with a proper name within the `External Information` subpackage.

    6.2 Model a new information flow using EA's `Information Flow Realized` feature by assigning one or more elements from the `External Information` subpackage as the information items conveyed.

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
