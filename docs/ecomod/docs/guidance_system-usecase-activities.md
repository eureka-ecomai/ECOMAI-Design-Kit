# ECOMOD Guidance: How to Model the Use Case Activities




The ECOMOD product **_Use Case Activities_** consists of the following parts:

+ a model element catalog containing one _Use Case Activity_ for each System Use Case
+ for each _Use Case Activity_ a _Use Case Activity View_ depicting
  - the essential steps to be performed in a System Use Case
  - the input/output objects of the activity (_optional_)
  - the object flow between the essential steps (_optional_)
+ for each System Use Case an _Activity Tree View_ (_optional_) depicting
  - the composition of the activity by its essential steps (system functions)


## Representation

+ The _Use Case Activity View_ is depicted in a `SysML Activity Diagram`.
+ The _Use Case Activity_ of a System Use Case is pictured as `ECOMOD stereotype «essentialActivity»`.
+ The _Use Case Activity_ of a continuous System Use Case is pictured as `ECOMOD stereotype «continuousActivity»`.
+ The relation between an _Use Case Activity_ and a _System Use Case_ is pictured with the `SysML Realization`.
+ A decomposable essential step of an _Use Case Activity_ is pictured as `ECOMOD stereotype «essentialActivity»`.
+ The _Activity Tree View_ is depicted in a `SysML Block Diagram`.
+ The composition of an _Use Case Activity_ by its essential steps is pictured with the `SysML Composition`.








1. Open the diagram [Functional Requirements].

1. Repeat the steps below for each modeled use case.

1. Select a use use in the diagram.

1. Open the _context menu_ of the selected use case.

1. Select [**New Child Diagram | Activity | with Activity Diagram**] and, if asked for a name, enter the same name as the selected use case.

1. After the activity diagram has opened, start modeling the detailed workflow of this use case.

1. Switch back to the [Functional Requirements] diagram and select this use use again.

1. Open the _context menu_ of the selected use case.

1. Select [**New Child Diagram | Select Composite Diagram**] and select the activity diagram created before.


## Example Model Content

![Example Model Structure of Functional Requirements](images/en-iotpml-example-usecaseactivities-modelstructure.png)


## Example View

![Example of Use Case Object Flows](images/en-iotpml-example-usecaseactivities-modelview.png)
