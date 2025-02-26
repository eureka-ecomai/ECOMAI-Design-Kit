# ECOMOD Guidance: How to Model the Domain Knowledge




The ECOMOD product **_Domain Knowledge_** essentially consists of the following parts:

+ a catalog containing the Domain Objects
+ a catalog containing the domain-specific value types and units
+ a view depicting the Domain Objects and the relations between them


## Representation

+ The __Domain Object View_ is depicted in a `SysML Block Diagram`.
+ The _Domain Object_ is pictured as `ECOMOD stereotype «domainBlock»`.
+ The _Domain Value Type_ is pictured as `SysML ValueType`.
+ The _Domain Unit_ is pictured as `SysML Unit` and `SysML QuantityKind`.
+ The relation between _Domain Objects_ are pictured with a specific SysML block relationship.
+ The relation between a _Domain Object_ and a sysetm actor pictured with a specific SysML block relationship.






1. Select the [Requirements] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an SysML `Requirements Diagram` named "Stakeholders".

1. Open the diagram [Stakeholders].

1. Place all the identified System Objectives (from the [Objectives] package) on the diagram.

1. Repeat the steps below for each identified Stakeholder:
    + Create a new `ECOMOD stereotype «Stakeholder»` element with a proper name within the [Stakeholders] package.
    + Place this element on the diagram.
    + Model an `SysML Trace` relationship from the Stakeholder to a System Objective if this is a goal/concern of that Stakeholder.


## Example Model Content

![Example Model Structure of Stakeholders](images/en-ecomod-example-stakeholders-modelstructure.png)


## Example View

![Example of Stakeholders](images/en-ecomod-example-stakeholders-modelview.png)

