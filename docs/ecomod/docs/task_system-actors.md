# ECOMOD Task: Identify System Actors

Identify the users and other external entities that interact with the system (or the system is acting with).


## Description

### Motivation

The system actors are the direct interaction partners for whom services and interfaces must be developed or whose influences on the system must be taken into account. They describe the limits of the system.

### What's To Do

All users and systems that interact with the system of interest are identified and their roles are modeled.

#### Guiding Questions

+ Who or what belongs to the system?
+ Who or what interacts with the system?
+ Which communication partners do you want to focus on?
+ What aspects do you want to emphasize with an actor category?

### How To Do

The system actors are primarily taken from the requirements and modeled in the system context diagram.

#### Used Model Objects

+ Views: `SysML Block Definition Diagram`, `SysML Internal Block Diagram`
+ Elements: `ECOMOD stereotype «Context»`, `ECOMOD stereotype «System»`, `ECOMOD stereotype «EnvironmentalEffect»`, `ECOMOD stereotype «User»`, `ECOMOD stereotype «ForeignSystem»`, `ECOMOD stereotype «BoundarySystem»`, `ECOMOD stereotype «UserSystem»`, `ECOMOD stereotype «Service»`, `ECOMOD stereotype «Sensor»`, `ECOMOD stereotype «Actuator»`, `ECOMOD stereotype «ControlUnit»`, `ECOMOD stereotype «StatusIndicator»`, `ECOMOD stereotype «SystemProperty»`, `ECOMOD stereotype «EnvironmentalEffectProperty»`, `ECOMOD stereotype «UserProperty»`, `ECOMOD stereotype «ForeignSystemProperty»`, `ECOMOD stereotype «BoundarySystemProperty»`, `ECOMOD stereotype «UserSystemProperty»`, `ECOMOD stereotype «ServiceProperty»`, `ECOMOD stereotype «SensorProperty»`, `ECOMOD stereotype «ActuatorProperty»`, `ECOMOD stereotype «ControlUnitProperty»`, `ECOMOD stereotype «StatusIndicatorProperty»`
+ Relationships: `SysML Part Association`


## Inputs

+ [System Requirements](product_system-requirements.md)


## Outputs

+ [System Context](product_system-context.md), _enriched with:_
  - System Context Definition
  - System Context View
  - System Actors


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the _System Context Definition_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the `System Context` package.

5. Open the `System Context Definition` diagram.

6. In the [Toolbox] view, ensure that content of the `ECOMOD System Context` toolbox (part of the `ECOMOD System-Level` toolbox set) is visible. 

7. Create a new `ECOMOD stereotype «Context»` element with a proper name within the `System Context` package by drag and drop the toolbox entry `System Context` onto the opened diagram; capture all relevant properties of this element.

8. Create a new `ECOMOD stereotype «System»` element with a proper name within the `System Context` package by drag and drop the toolbox entry `System` onto the opened diagram; capture all relevant properties of this element.

9. Model a `SysML Part Association` relationship from the `ECOMOD stereotype «System»` element to the `ECOMOD stereotype «Context»`; at the source end of this link capture the short name of the system as its role name.

10. Repeat the steps below for each identified _System Actor_, depending on the kind of actor:

    10.1-a _Environmental Effect_: Create a new `ECOMOD stereotype «EnvironmentalEffect»` element with a proper name within the `System Actors` subpackage by drag and drop the toolbox entry `Environmental Effect` onto the opened diagram.

    10.1-b _Human User_: Create a new `ECOMOD stereotype «User»` element with a proper name within the `System Actors` subpackage by drag and drop the toolbox entry `Human User` onto the opened diagram.

    10.1-c _External System_: Create a new `ECOMOD stereotype «ForeignSystem»`, `ECOMOD stereotype «BoundarySystem»`, `ECOMOD stereotype «UserSystem»`, or `ECOMOD stereotype «Service»` element with a proper name within the `System Actors` subpackage by drag and drop the toolbox entry `Foreign System`, `Boundary System`, `User System`, or `Service System` onto the opened diagram.

    10.1-d _External Device_: Create a new `ECOMOD stereotype «Sensor»`, `ECOMOD stereotype «Actuator»`, `ECOMOD stereotype «ControlUnit»`, or `ECOMOD stereotype «StatusIndicator»` element with a proper name within the `System Actors` subpackage by drag and drop the toolbox entry `Device: Sensor`, `Device: Actuator`, `Device: Control Unit`, or `Device: Status Indicator` onto the opened diagram.

    10.2 Capture all relevant properties of the created element.

    10.3 Model a `SysML Part Association` relationship from the created element to the `ECOMOD stereotype «Context»`; at the source end of this link capture a short name of this actor as its role name.


How to model the _System Context View_ in the Enterprise Architect tool:

1. If not active, enable the `ECOMOD System Modeling` perspective.

2. Switch to the [Project Browser] view.

3. Locate your system model root package.

4. Locate the element named `System Context` (the one having the `ECOMOD stereotype «Context»` set) within the `System Context` package.

5. Open the child diagram `System Context View` of this element.

6. In the [Toolbox] view, ensure that content of the `ECOMOD System Context` toolbox (part of the `ECOMOD System-Level` toolbox set) is visible. 

7. For all parts of the system context, that was modeled in the _System Context Definition_, corresponding `SysML Property` elements was generated automatically as child elements of the located `ECOMOD stereotype «Context»` element. Insert all of them into the opened diagram.

8. Capture all relevant properties of those inserted elements. Especially, set the actor element's "**ConnectionKind**" property to a value proper to the information defined in the _Functional System Requirements_ of kind _Interface Interaction_ or the _Technical System Constraints_.

9. Repeat the steps below for each inserted element representing a _System Actor_:

    9.1-a Model an interaction path as a `SysML Connector` relationship from the actor element to the `ECOMOD stereotype «System»` element if the system primary receives information from the actor (e.g. a sensor).

    9.1-b Model an interaction path as a `SysML Connector` relationship from the `ECOMOD stereotype «System»` element to the actor element if the system primary provides information to the actor (e.g. an actuator).

    9.2 If the _Functional System Requirements_ of kind _Interface Interaction_ or the _Technical System Constraints_ defines any kind of communication protocols (such as ModbusTCP) or connection technologies (such as CAN-Bus) capture that information as the name of the modeled relationship.

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
