# ECOMOD Method: Describe System Modes

#### ---ORIGINAL---begin---
Define the states, state transitions, and state-controlled functions of the system and parts of the system.
#### ---ORIGINAL---end---

![Activity Model](images/en-ecomod-method-system-modes.png)


## Purpose

#### ---ORIGINAL---begin---
The states of a system specify the conditions of the whole system or parts of the system that constrain the execution of function.
#### ---ORIGINAL---end---


## Description

#### ---ORIGINAL---begin---
A state describes a condition of the system or system part, for example, _active_ or _maintenance mode_. It further specifies which functions could be performed in a state. A transition specifies the trigger and guard condition to switch from one state to another. The state machine combines states ans transitions to a behavioral unit of a part of the architecture.

State machines could also be used to refine Requirements. In that case they are the description of a System Process.
#### ---ORIGINAL---end---


## Inputs

+ System Context: [simple](product_system-context-simple.md) or [complex](product_system-context.md)
+ [System Use Cases](product_system-usecases.md)
+ [System Processes](product_system-processes.md)
+ [System Use Case Activities](product_system-usecaseactivities.md)
+ [Domain Data Model](product_domain-data-model.md)


## Outputs

+ [System Modes](product_system-modes.md)


## Tasks

+ -TODO- [Model System Modes](task_system-modes.md)


## Further Information

### Recommendations & Tips

_None._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
