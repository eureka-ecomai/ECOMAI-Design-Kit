# ECOMOD Task: Add Technological Constraints

Enrich the _System Context_ by the technological constraints.


## Description

### Motivation

It's important to figure out the technological constraints that influences the implementation of the communication between the system and its environment.

### What's To Do

Integrate the technical constraints, which can be found in the _Functional System Requirements_ of kind _Interface Interactions_ or the _Technological Constraints_, in the _System Context_ view.

#### Guiding Questions

+ Which communication protocols shall be used to exchange the information?
+ Which (interface) technologies shall be used to exchange the information?

### How To Do

For each identified _Communication Path_ check the _Technological Constraints_ or the _Functional System Requirements_ of kind _Interface Interactions_ if they define any technical specifications. Things like a communication protocol or interface technology are noted on the modeled _Communication Paths_ (e.g. as the link's name).

#### Used Model Objects

+ Views: `SysML Internal Block Diagram`
+ Elements: _-none-_
+ Relationships: `SysML Association` or `SysML Connector`


## Inputs

+ [System Context (_simple variant_)](product_system-context-simple.md) or [System Context](product_system-context.md)


## Outputs

+ [System Context (_simple variant_)](product_system-context-simple.md) or [System Context](product_system-context.md), _enriched by:_
  - Technical Constraints


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the notation of technological constraints in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. If you decide to model the simple variant of the _System Context_, open the diagram `System Context View` within the `System Context` package. Otherwise, locate the element named `System Context` (the one having the `ECOMOD stereotype «Context»` set) within the `System Context` package and open the child diagram `System Context View` of this element.

6. Repeat the steps below for each link representing a _Communication Path_ and that is subject to technological constraint or limitation:

    6.1 Select the link in the diagram and switch to its [Property] view.

    6.2 Capture the technological constraint or limitation as the link's name.

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
