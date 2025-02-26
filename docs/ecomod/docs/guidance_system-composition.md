# IoT-PML Guidance: How to Model the System Composition


1. Select the [System Context] package (see [How to Build an Initial Package Structure](guidances_initial-package-structure.md)).

1. Create an `IoT-PML System Decomposition Diagram` named "System Decomposition".

1. Open the diagram [System Decomposition].

1. Place the element representing your system (from the [System Context] package) on the diagram.

1. For each system building block, that represents a kind of hardware:
    + Create an `IoT-PML «hwComponent»` element and add it to the diagram.
    + Model an `IoT-PML «Comprise»` relationship from this element to the element that is composed of it.

1. For each system building block, that represents a kind of software:
    + Create an `IoT-PML «swComponent»` element and add it to the diagram.
    + Model an `IoT-PML «Comprise»` relationship from this element to the element that is composed of it.


## Example Model Content

![Example Model Structure of System Composition](images/en-iotpml-example-systemcomposition-modelstructure.png)


## Example View

![Example for System Composition](images/en-iotpml-example-systemcomposition-modelview.png)

