# IoT-PML Guidance: How to Build an initial Package Structure

This guidance is not directly related to an [IoT-PML Method](methods.md). It describes how to create a proper package structure for an IoT-PML System Model.

1. Inside the root package for you projects create a package with the name of your system of interest (this package is hereinafter referred to as the *Project Root*). Optional: Assign the UML stereotype «systemModel» to this package.

1. Inside the Project Root package create the top-level packages named as "System Context", "Functional Requirements", "System Decomposition", "Software Stack", and "Threat Model".

1. Create inside the package [System Context] a package named "External Entities" (to manage the System Actors).

1. Create inside the package [System Context] a package named "External Information" (to manage the information items flowing between the system and its environment).

1. Create inside the package [System Decomposition] a package named "Internal Information" (to manage the information items flowing between the building block of the system).

1. Create inside the package [System Decomposition] a package named "Behavior Analysis" (to manage the system's behavior).

1. Create inside the package [Threat Model] a package named "Threats" (to manage the security requirements).


## Example Model Content

![Example Model Structure of System Model](images/en-iotpml-example-systemmodelstructure-initial.png)
