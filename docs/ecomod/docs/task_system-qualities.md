# ECOMOD Task: Determine System Qualities


_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |

---


Capture the quality criterias of the system.


## Description

### Motivation

It's important to know the quality criterias that are expected and should be fullfilled by the solution.

### What's To Do

Describe the qualities that must be satisfied by the system and add them to the system model.

#### Guiding Questions

+ What system response times must be observed?
+ What are the expectations regarding the maintainability of the system?
+ What are the expectations regarding the system's reliability?
+ What are the expectations regarding the reliability of the system?
+ According to which quality criteria should the system be assessed - FURPS+ or ISO 25010?
+ Am I asking the right person and asking the right questions?
+ Are the answers official?
+ Is the stakeholder's concern a request or just a wish?
+ How can you check whether the requirement is met by the system?

### How To Do

To represent a _System Quality_ in the system model the ECOMOD profile provides various stereotypes, which are specializations of the **SysML Requirement** with extended properties.

Each identified _System Quality_ will be pictured in the `Quality Requirements` package using one of the following variants: **ECOMOD stereotype «FunctionalityReqt»**, **ECOMOD stereotype «UsabilityReqt»**, ***ECOMOD stereotype «ReliabilityReqt»***, **ECOMOD stereotype «PerformanceReqt»**, **ECOMOD stereotype «SupportablilityReqt»**, **ECOMOD stereotype «SecurityReqt»**. Additionally the created element can be depicted in the `Quality Requirements Catalog` diagram.

#### Used Model Objects

+ Views: `SysML Requirements Diagram`
+ Elements: `ECOMOD stereotype «FunctionalityReqt»`, `ECOMOD stereotype «UsabilityReqt»`, `ECOMOD stereotype «ReliabilityReqt»`, `ECOMOD stereotype «PerformanceReqt»`, `ECOMOD stereotype «SupportablilityReqt»`, `ECOMOD stereotype «SecurityReqt»`
+ Relationships: `SysML Trace`

## Inputs

+ _-none-_


## Outputs

+ [System Requirements](product_system-requirements.md), extended by:
  - System Qualities


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the _System Qualities_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the `Quality Requirements` subpackage within the `System Requirements` package.

5. Open the `Quality Requirements Catalog` diagram.

6. In the [Toolbox] view, ensure that content of the `ECOMOD System Requirements` toolbox (part of the `ECOMOD System-Level` toolbox set) is visible. 

8. Repeat the steps below for each identified _System Quality Requirements_:
    + Create a new _Quality Requirement_ element with a proper name within the `Quality Requirements` package by drag and drop one of the following toolbox entries onto the opened diagram: `Quality Reqt: Functionality`, `Quality Reqt: Usability`, `Quality Reqt: Reliability`, `Quality Reqt: Performance`, `Quality Reqt: Supportability`, `Quality Reqt: Security`.
    + Assign a _Stakeholder_ by using the "**Stakeholder**" property of this element.
    + Capture all other properties of this element.
    + If sensible, model a `SysML Trace` relationship from this element to each _System Objective_ supported by this requirement.


### Examples

#### System Quality Requirements

![Example of System Quality Requirements](images/en-ecomod-example-00-qualities-modelview.png)

#### Model Content

![Example of Model Content](images/en-ecomod-example-00-sysreqt-modelstructure.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
