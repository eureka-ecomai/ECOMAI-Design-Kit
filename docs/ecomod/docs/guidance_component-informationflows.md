# IoT-PML Guidance: How to How to Model the System Internal Information Flows


1. Open the diagram [System Interconnection] located within the [System Decomposition] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Repeat the steps below for each connection between the system building blocks:

1. For each identified internal information, that is exchanged between components, create - depending on the kind of information item - either a `IoT-PML InformationItem` or an `UML Signal` element with a suitable name within the [Internal Information] package.

1. For each external or internal information, that is received by the interaction point, model a directed `UML InformationFlow` relationship to the interaction point.

1. For each external or internal information, that is sent by the interaction point, model a directed `UML InformationFlow` relationship from the interaction point.


## Example Model Content

![Example Model Structure of System Internal Information Flows](images/en-iotpml-example-componentinterconnection-modelstructure.png)


## Example View

![Example for System Internal Information Flows](images/en-iotpml-example-componentinterconnection-modelview.png)

