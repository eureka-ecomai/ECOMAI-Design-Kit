# IoT-PML Guidance: How to Model the System Interaction Points


1. Select the `IoT-PML «system»` element within the [System Context] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. For each identified interaction point create an `IoT-PML «InteractionPoint»` element as a child element with a suitable name which typically indicates the associated actor(s).

1. Select the [System Decomposition] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an `IoT-PML System Decomposition Diagram` named "System Interfaces".

1. Open the diagram [System Interfaces].

1. Place the element representing your system (from the [System Context] package) on the diagram.

1. Enable the display of the previousely modeled interaction points on the `IoT-PML «system»` element.

1. Place all system actors (from the [External Entities] package) on the diagram.

1. For each interaction point, that receives information items from a system actor, model an `IoT-PML «Connector»` relationship from the actor to this interaction point.

1. For each interaction point, that is used for sending information items to a system actor, model an `IoT-PML «Connector»` relationship from this interaction point to the actor.

1. If is is important to display which information items that are exchanged between the system and its environment, configure the information flow on the `IoT-PML «Connector»` links.


## Example Model Content

![Example Model Structure of System Interaction Points](images/en-iotpml-example-systeminterfaces-modelstructure.png)


## Example View

![Example for System Interaction Points](images/en-iotpml-example-systeminterfaces-modelview.png)

