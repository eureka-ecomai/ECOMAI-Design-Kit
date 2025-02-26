# ECOMOD Method: Describe Base Architecture

Describe the architectural and technical decisions that were made at the beginning of the development project and constraints the solution space.


## Motivation

The fundamental architecture of the system, which was determined before the start of the development project, sets the abstraction level of the Requirements, presets architecture and technical decisions, and influences the scope for innovations. 


## Description

### What's To Do

Document the architectural and technical decisions that are the obligatory constraints for the further system development. The _Requirements_ are based on it and it sets the limits within which new innovative solutions can be developed.

The requirements for a system should be solution-free, but the question arises as to what belongs to the requirements and what belongs to the solution. The _Base Architecture_ answers this question because the requirements are based on the _Base Architecture_. The technologies of the _Base Architecture_ may be used in the requirements because they are not part of the solution space, but rather limit it.

Please note, that the constraints, that are made at the beginning of the project, can only be reversed later with great effort, as many things - starting with the requirements - are based on them.


#### Guiding Questions

+ What is the desired level of innovation?
+ Which architectural decisions are given?
+ Which technical components are predetermined?

### How To Do

The _Base Architecture_ is depicted typically in a combination of a **SysML Block Definition Diagram** and a **SysML Internal Block Diagram** and pictured either with **SysML BLock** elements or **descipline-specific ECOMOD stereotypes**.

### Next Steps

The _Base Architecture_ contains cross-project patterns and components that can be reused for other system developments.


## Inputs

+ [System Idea](product_system-idea.md)
+ [System Objectives](product_system-objectives.md)


## Outputs

+ [Base Architecture](product_base-architecture.md)


## Modeling Guidances

+ [Model Base Architecture](guidance_base-architecture.md)


## Further Information

### Recommendations & Tips

_None._
