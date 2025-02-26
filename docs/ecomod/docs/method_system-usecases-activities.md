# ECOMOD Method: Specify Use Case Activities

#### ---ORIGINAL---begin---
Model the behavior of the System Use Cases.
#### ---ORIGINAL---end---

![Activity Model](images/en-sysmod-method-usecaseactivities.png)


## Purpose

#### ---ORIGINAL---begin---
The Use Case Activities specify the functional decomposition of the System Use Cases including the order of execution and object flow between the system functions.
#### ---ORIGINAL---end---


## Description

#### ---ORIGINAL---begin---
A System Use Case specifies for example a name, a trigger, and a result. The behavior of a System Use Case is specified by the Use Case Activity. The specification could be a rough description or a very clear and detailed specification of the use case functions. The level of detail depends on the needs of your project.

Each step of a Use Case Activity is again specified with a Use Case Activity. The Use Case Activities that need no further refinements have no included steps.

A Use Case Activity includes the description of the input and output objects of the functions. The relationship of an output object of a function to an input of another function is called object flow.

The Use Case Activity could specify pre- and postconditions. The preconditions must be true to trigger the System Use Case. The postcondition is true after the execution of the System Use Case.

The essentials steps of a System Use Case are the top level steps in the root Use Case Activity.

It is a good practice to separate the use case functions that are responsible for the input and output of objects from and to the system actors from all other functions. Those input/output functions depend on the interface technology that is typically more unstable than the core functions and are less dependent on the specific domain.
#### ---ORIGINAL---end---


## Inputs

+ [System Use Cases](product_system-usecases.md)
+ System Context: [simple](product_system-context-simple.md) or [complex](product_system-context.md)
+ [System Requirements](product_system-requirements.md)


## Outputs

+ [System Use Case Activities](product_system-usecaseactivities.md)
+ [Domain Data Model](product_domain-data-model.md) (_updated_)


## Tasks

+ -TODO- [Model Use Case Activities](task_usecase-activities.md)
+ -TODO- [Model Object Flow](task_usecase-objectflow.md)


## Further Information

### Recommendations & Tips

_None._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
