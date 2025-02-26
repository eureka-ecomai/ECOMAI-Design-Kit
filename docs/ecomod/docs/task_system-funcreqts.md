# ECOMOD Task: Determine System Functionality

Capture the functional requirements of the system.


## Description

### Motivation

It's important to know the features of the system and what the system has to do.

### What's To Do

Describe the functionalities of the system and add them to the system model.

#### Guiding Questions

+ Which independent system activities should be executed by the system?
+ Which user interactions should be provided by the system?
+ Which interface interactions should be supported by the system?
+ Am I asking the right person and asking the right questions?
+ Are the answers official?
+ Is the stakeholder's concern a request or just a wish?
+ How can you check whether the requirement is met by the system?

### How To Do

To represent a _Functional System Requirement_ in the system model the ECOMOD profile provides the **ECOMOD stereotype «FunctionalReqt»**, which is a specialization of the **SysML Requirement** with extended properties.

Each identified _Functional System Requirement_ will be pictured by an **ECOMOD stereotype «FunctionalReqt»** in the `Functional Requirements` package. Additionally the created element can be depicted in the `Functional Requirements Catalog` diagram.

#### Used Model Objects

+ Views: `SysML Requirements Diagram`
+ Elements: `ECOMOD stereotype «FunctionalReqt»`
+ Relationships: `SysML Trace`

## Inputs

+ _-none-_


## Outputs

+ [System Requirements](product_system-requirements.md), extended by:
  - System Functionality


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the _Functional System Requirements_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the `Functional Requirements` subpackage within the `System Requirements` package.

5. Open the `Functional Requirements Catalog` diagram.

6. In the [Toolbox] view, ensure that content of the `ECOMOD System Requirements` toolbox (part of the `ECOMOD System-Level` toolbox set) is visible. 

8. Repeat the steps below for each identified _Functional System Requirements_:
    + Create a new `ECOMOD stereotype «FunctionalReqt»` element with a proper name within the `Functional Requirements` package by drag and drop the toolbox entry `Functional Requirement` onto the opened diagram.
    + Select the proper kind of functionality: _Independent System Activity_, _User Interaction_, or _Interface Interaction_.
    + Assign a _Stakeholder_ by using the "**Stakeholder**" property of this element.
    + Capture all other properties of this element.
    + If sensible, model a `SysML Trace` relationship from this element to each _System Objective_ supported by this requirement.


### Examples

#### Functional System Requirements

![Example of Functional System Requirements](images/en-ecomod-example-00-funcreqt-modelview.png)

#### Model Content

![Example of Model Content](images/en-ecomod-example-00-sysreqt-modelstructure.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
