# ECOMOD Method: Define System Context (_simple variant_)

Identify the users and other external entities that interact with the system (or the system is acting with).

![Method Activities](images/en-ecomod-method-system-context-simple.png)


## Motivation

It's important to know those external entities with which the system interacts, together with the relevant information flows.


## Description

### What's To Do

The _System Context_ represents all elements from the system's environment that are involved as partners in the interactions with the system. These elements are called _System Actors_. The obvious ones are the users of the system and the external systems with explicite interfaces. Less obvious _System Actors_, but equally important are, for example, environmental effects like temperature or humidity.

Besides the list of system actors the _System Context_ describes relevant flows of information items between the _System Actors_ and the system.

Please note, that the human actors and the humans and organizations behind the non-human actors are also _Stakeholders_ of the system.

#### Guiding Questions

+ Who or what interacts with the system?
+ Which information flows from the environment to the system?
+ Which information flows from the system to its environment?
+ What information items are exchanged during an interaction?
+ Which communication protocols are used to exchange the information?
+ Which (interface) technologies are used to exchange the information?

### How To Do

The simple [System Context](product_system-context-simple.md) is depicted typically in a **SysML Block Definition Diagram**.

The system itself is pictured as **ECOMOD stereotype «System»** and the **System Actors** are pictured with specific **ECOMOD actor stereotypes** (e.g. a sensor actor as **ECOMOD stereotype «Sensor»**). 

The interaction between the system and an actor is expressed by a _Communication Path_ which is represented by the **SysML Association** relationship. The exchange of information item is represented by **SysML InformationFlow** relationships, which is a directed link that has the conveyed information items (either **UML Signal** or **UML Class** elements) assigned.

Any technical constraints (which can be found in the _Functional System Requirements_ of kind _Interface Interactions_ or the _Technological Constraints_) should be noted on the _Communication Paths_ (e.g. as the link's name).

### Next Steps

The information flows are used to identify and describe the _System Use Cases_. The _System Architecture_ must reflect the information flows inside the system. The noted communication protocols and interface technologies noted at the _Communication Paths_

 correspond to the _System Interfaces_ and are connected to the internal building blocks (_Subsystems_) of the system.


## Inputs

+ [System Objectives](product_system-objectives.md)
+ [System Requirements](product_system-requirements.md)


## Outputs

+ [System Context (_simple variant_)](product_system-context-simple.md), consisting of:
  - System Actors
  - System Information Flows
  - Domain Information Items
+ [Domain Data Model](product_domain-data-model.md) (_updated_)


## Tasks

+ [Identify System Actors](task_system-actors.md)
+ [Specify System Information Flows](task_system-informationflows.md)
+ [Add Technological Constraints](task_system-commtechnologies.md)


## Further Information

### Recommendations & Tips

+ For a more precise indication of the nature of an information item the following prefixes could be used:
  + "EI-" for _**E**lectrical **I**nformation_ (e.g. EI-Motor-Temperature)
  + "PI-" for _**P**hysical **I**nfluence_ (e.g. PI-Ambient-Temperature)
  + "MI-" for _**M**echanical **I**nformation_ (e.g. MI-Torque)
  + "SI-" for _**S**ervice **I**nformation_ (e.g. SI-Diagnostic-Data)
  
+ **Tip**: Use the '-' character instead of a '_' (underline) or ' ' (space) character in the information item's name.

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
