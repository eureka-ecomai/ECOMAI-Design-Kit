# IoT-PML Guidance: How to How to Model the System Component Interfaces


1. Select the [System Decomposition] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an `IoT-PML System Decomposition Diagram` named "System Interconnection".

1. Open the diagram [System Interconnection].

1. Place the element representing your system (from the [System Context] package) on the diagram.

1. Enable the display of the previousely modeled interaction points on the `IoT-PML «system»` element.

1. Place all system components (from the [System Decomposition] package) on the diagram, but inside the element representing your system and nested within each other to represent their hierarchical composition.

1. Repeat the steps below for each identified system building block:
    + Select the building block in the diagram.
    + For each identified interaction point create an `IoT-PML «InteractionPoint»` element with a suitable name which typically indicates its purpose.

1. Repeat the steps below for each identified component interaction point:
    + If this interaction point receives information items, model an `IoT-PML «Connector»` relationship to this interaction point.
    + If this interaction point sends information items, model an `IoT-PML «Connector»` relationship from this interaction point.


## Example Model Content

![Example Model Structure of System Component Interfaces](images/en-iotpml-example-componentinteractionpoints-modelstructure.png)


## Example View

![Example for System Component Interfaces](images/en-iotpml-example-componentinteractionpoints-modelview.png)

