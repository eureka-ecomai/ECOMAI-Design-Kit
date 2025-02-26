# ECOMOD Guidance: How to Model the Base Architecture


it's possible to couple the **_Base Architecture_** with the Logical Architecture either strongly by using the SysML Generalization relationship or loosely by using the SysML Allocate relationship.


A formal description of the ECOMOD product **_Base Architecture_** consists of the following parts:

+ a model element representing the _Base System Context_ 
+ a model element representing the _Base System_ (including the external interaction points)
+ a model element catalog containing the _Base System Actors_
+ a model element catalog containing the _Base System Parts_
+ a model element catalog containing the _Base System Interfaces_
+ a _Base Architecture Definition View_ depicting
  - the composition of the _Base System Context_ from the _Base System_ and the _Base System Actors_
  - the composition of the _Base System_ from the _Base System Parts_
+ a _Base Architecture View_ depicting
  - the connections between the _Base System Actors_ and the _Base System_ or _Base System Parts_
  - the connections between the _Base System Parts_
  - the information flows between the _Base System Actors_ and the _Base System_ or _Base System Parts_


## Representation

+ The _Base Architecture Definition View_ is depicted in a `SysML Block Definition Diagram`.
+ The _Base System Context_ is pictured as `ECOMOD stereotype «systemContext»`.
+ The _Base System Actors_ are pictured as `ECOMOD stereotype «user»`, `ECOMOD stereotype «environmentalEffect»`, or `ECOMOD stereotype «externalSystem»` (or one of its subkinds).
+ The _Base System_ is pictured as `ECOMOD stereotype «system»`.
+ The _Base System Parts_ are pictured as `SysML Block` (possibly marked with a discipline-specific stereotype).
+ The _Base System Interfaces_ are pictured as `SysML InterfaceBlock` (possibly marked with a discipline-specific stereotype).
+ The composition of the _Base System Context_ by its actors is pictured with the `SysML Composition`.
+ The composition of the _Base System_ by its parts is pictured with the `SysML Composition`.
+ The _Base Architecture View_ is depicted in a `SysML Internal Block Diagram`.
+ Each element of the _Base Architecture View_ is pictured as `SysML Property`.
+ The connection between those elements is pictured with the `SysML Connector`.
+ The information flow between those elements is pictured with the `SysML InformationFlow`.







!!TODO!!

1. Select the [Requirements] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an SysML `Requirements Diagram` named "Objectives".

1. Open the diagram [Objectives].

1. Repeat the steps below for each identified Stakeholder:
    + Create a new `ECOMOD stereotype «Objective»` element with a proper name within the [Objectives] package.
    + Place this element on the diagram.
    + Capture all relevant properties of this element.


## Example Model Content

![Example Model Structure of Base Architecture](images/en-ecomod-example-basearchitecture-modelstructure.png)


## Example View

![Example of Base Architecture](images/en-ecomod-example-basearchitecture-modelview.png)

