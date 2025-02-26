# SYSMOD Method: Model Logical Architecture

#### ---ORIGINAL---begin---
Model a Physical Architecture on a high abstraction level that satisfies the given requirements.
#### ---ORIGINAL---end---

![Activity Model](images/en-iotpml-method-logical-architecture.png)


## Purpose

#### ---ORIGINAL---begin---
The Logical Architecture describes the technical concepts and principles of the system.
#### ---ORIGINAL---end---


## Description

#### ---ORIGINAL---begin---
The Logical Architecture is a abstract Physical Architecture. Thinking top-down in the development process the Logical Architecture is the first version of a Physical Architecture. It covers architectural and technical principles ans concepts. For example an electric motor is a technical concept. A concrete and detailed specification of the electric motor is part of the Product Architecture.

The Logical Architecture must follow the Base Architecture. If strongly coupled the Logical Architecture is aspecialization of the Base Architecture. If loosely coupled there are only traceability relationships between both architectures.
#### ---ORIGINAL---end---


## Inputs

+ [System Context](product_system-context.md)
+ [Requirements](product_requirements.md)
+ [System Use Cases](product_system-usecases.md)
+ [Base Architecture](product_base-architecture.md) (_optional_)
+ [Functional Architecture](product_functional-architecture.md) (_optional_)


## Outputs

+ [Logical Architecture](product_logical-architecture.md)


## Tasks

+ [Model System Interaction Points](task_system-interactionpoints.md)
+ [Model System Structures](task_system-components.md)
+ [Model Component Interfaces](task_component-interfaces.md)
+ [Model Internal Information Flows](task_component-informationflows.md)


## Further Information

### Examples

#### Example Interaction Points

![Example for Interaction Points](images/en-iotpml-example-systeminterfaces-modelview.png)

#### Example System Composition

![Example for System Composition](images/en-iotpml-example-systemcomposition-modelview.png)

#### Example Component Interconnection

![Example for Component Interconnection](images/en-iotpml-example-componentinterconnection-modelview.png)

### Recommendations & Tips

_None._
