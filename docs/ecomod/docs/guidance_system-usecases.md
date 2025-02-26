# ECOMOD Guidance: How to Model the Use Cases




The ECOMOD product **_System Use Cases_** consists of the following parts:

+ a model element representing the system itself as a boundary (_System Boundary_)
+ a model element catalog containing the _System Use Cases_
+ a _System Use Case View_ depicting
  - the communication links between the _System Actors_ and the _System Use Cases_
  - the relations between the _System Use Cases_


## Representation

+ The _System Use Case View_ is depicted in a `SysML Use Case Diagram`.
+ The _System Boundary_ is pictured as `SysML Boundary`.
+ The _System Use Cases_ are basically pictured as `ECOMOD stereotype «systemUseCase»`, in special cases as `ECOMOD stereotype «continuousUseCase»`.
+ The communication link between a _System Use Case_ and a _System Actor_ is pictured with the `SysML Association`.
+ The relation between _System Use Cases_ is pictured either with the `SysML Inclusion` or the `SysML Extension`.







1. Select the [Functional Requirements] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an IoT-PML `Functional Requirements Diagram` named "Functional Requirements".

1. Open the diagram [Functional Requirements].

1. Place all the identified system actors (from the [External Entities] package) on the diagram.

1. Repeat the steps below for each identified system use case:
    + Create a new `UML UseCase` element with a proper name.
    + Place this element on the diagram.
    + Model an `UML Association` relationship from the use case to a system actor if there should be an interaction possible between them.


## Example Model Content

![Example Model Structure of Functional Requirements](images/en-iotpml-example-functionalrequirements-modelstructure.png)


## Example View

![Example of System Use Cases](images/en-iotpml-example-functionalrequirements-modelview.png)

