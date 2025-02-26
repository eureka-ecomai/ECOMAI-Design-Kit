# ECOMOD Task: Identify System Interaction Points

Identify the specific points at the system boundary through which the system interactions with the various system actors take place.


## Description

### Motivation

The system interaction points describe the interfaces to the system environment on a higher level and are responsible for successful system integration.


### What's To Do

Describe the points of the system through which interaction with the environment takes place.

#### Guiding Questions

+ How does the system exchange information with its environment?
+ Which interaction paths with the actors can be brought together?

### How To Do

For each identified _System Actor_ consider the associated _System Interaction Point_ and specify the services and information items that are offered or requested via that point.

#### Used Model Objects

+ Views: `SysML Internal Block Diagram`
+ Elements: `SysML Port`
+ Relationships: _-none-_


## Inputs

+ [System Context](products_system-context.md)


## Outputs

+ [System Context](product_system-context.md), _enriched by:_
  - System Interaction Points


## Recommendations & Tips

+ Use the connected actor's name as the name of a system's interaction point together with prefix "LP_" (for _**L**ogical interaction **P**oint_), e.g. LP_User, LP_Sensor, LP_Device.

+ For a more precise indication of the nature of the interaction point the following prefixes could be used:
  + "EP_" for _**E**lectrical interaction **P**oint_ (e.g. EP_Sensor)
  + "MP_" for _**M**echanical interaction **P**oint_ (e.g. MP_Fastening)
  + "SP_" for _**S**ervice interaction **P**oint_ (e.g. SP_TaxCalculator)


## Modeling Guidance

How to model the _System Interaction Points_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the element named `System Context` (the one having the `ECOMOD stereotype «Context»` set) within the `System Context` package.

5. Open the child diagram `System Context View` of this element.

6. Repeat the steps below for each modeled interaction path (the `SysML Connector` relationship that is modeled in the Sytem Context View):

    6.1-a An interaction path needs a new interaction point: Create a new `SysML Port` as child property of the element representing the system (the one having the `ECOMOD stereotype «System»` set) with a proper name.

    6.1-b An interaction path should use an existing interaction point: go on with next step.

    6.2 Take that end of the current `SysML Connector` which connects the system element, and move it to the interaction point identified in the step before (now, the `SysML Port` subelement is the new end of the link).

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
