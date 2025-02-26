# IoT-PML Guidance: How to Model the External Information Flows


1. Select the [External Information] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. For each identified external information, that is exchanged between the actors and the system, create - depending on the kind of information item - either a `IoT-PML InformationItem` or an `UML Signal` element with a suitable name in the [External Information] package.

1. Open the diagram [System Context].

1. For each external information, that is received by the system, model a directed `UML InformationFlow` relationship from the actor to the system element.

1. For each external information, that is sent by the system to its environment, model a directed `UML InformationFlow` relationship from the actor to the system element.


## Example Model Content

![Example Model Structure of External Information Flow](images/en-iotpml-example-externalinformationflows-modelstructure.png)


## Example View

![Example for External Information Flows](images/en-iotpml-example-systemcontext-modelview.png)

