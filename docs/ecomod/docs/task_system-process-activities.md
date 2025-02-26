# ECOMOD Task: Specify System Process Behavior

!! TODO !!


## Description

### Motivation

The process descriptions of the use cases are part of the core information of the requirements analysis. They specify the required behavior of the system in detail. 
Furthermore, care must be taken to describe the use cases without redundancies, because redundancies can lead to serious problems if their consistency is violated.

### What's To Do

Describe the processes of the use cases with all exceptions and variants in appropriate detail. Identify commonalities between use case flows and model these areas in isolation to avoid redundancies.

#### Guiding Questions

+ Which steps are necessary for the use case?
+ What exceptions and variants can occur during the process?
+ Is the use case described in sufficient detail and understandably?
+ Which use case steps are repeated in other use cases?
+ Which use cases are similar?

### How To Do

The use case flows are described with activities. Commonalities in use case processes are described in supporting (secondary) use cases and integrated into the primary use cases via the containing relationship (alternatively, subactivities can also be used for this).

#### Used Model Objects

+ Views: `UML Actvity Diagram`
+ Elements: `UML UseCase`, `UML Activity`, `UML ActionNodes`, `UML ControlNodes`, `UML InterruptableActivityRegion`
+ Relationships: `UML Realization`, `UML ControlFlow`, `UML InterruptFlow`

### Next Steps

The activities are the direct basis for the functional aspects of the system architecture. The clear representation in the activity diagram enables the client to be well integrated into the system development. And a redundancy-free use case structure provides good clues for a redundancy-free system architecture.


## Inputs

+ !!TODO!!


## Outputs

+ !!TODO!!


## Recommendations & Tips

_None._


## Modeling Guidance

How to model the _System Process Behavior_ in the Enterprise Architect tool:

1. !!TODO!!


## Examples

### System Process Behavior

![Example of System Process Behavior](images/en-ecomod-example-00-systemuprocess-behavior-modelview.png)

### Model Content

![Example of Model Content](images/en-ecomod-example-00-systemprocess-behavior-modelstructure.png)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
