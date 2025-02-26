# The ECOMOD Profile Quick Reference


## Profile Elements


### Activities

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «continuousActivity» | Represents the activities executed in a _Continuous System Use Case_. | ![Notation of Continuous Activity](images/en-ecomod-notation-activity-continuous.png) |![Example of Continuous Activity](images/en-ecomod-sample-activity-continuous.png) |
| «continuousAction» | Represents the Call Behavior Action needed to integrate a _Continuous Activity_ into a workflow. | ![Notation of Continuous Action](images/en-ecomod-notation-action-continuous.png) | ![Example of Continuous Action](images/en-ecomod-sample-action-continuous.png) |


### Actors

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «User» | Represents a human actor. It's defined to distinct an user from a _Stakeholder_. | ![Notation of User](images/en-ecomod-notation-actor-user.png) | ![Example of User](images/en-ecomod-sample-actor-user.png) |
| «EnvironmentalEffect» | Represents a relevant effect (e.g. humidity or temperature) from the system's environment that influences the system to be specified. | ![Notation of Environmental Effect](images/en-ecomod-notation-actor-environmentaleffect.png) | ![Example of Environmental Effect](images/en-ecomod-sample-actor-environmentaleffect.png) |
| **_External Devices:_** |  |  |  |
| «Sensor | Represents a foreign device that provides data from the environment to the system to be specified. | ![Notation of Sensor](images/en-ecomod-notation-actor-sensor.png) | ![Example of Sensor](images/en-ecomod-sample-actor-sensor.png) |
| «Actuator» | Represents a foreign device that has an effect on the environment and is controlled by the system to be specified. | ![Notation of Actuator](images/en-ecomod-notation-actor-actuator.png) | ![Example of Actuator](images/en-ecomod-sample-actor-actuator.png) |
| «ControlUnit» | Represents a foreign device that provides data from the environment to the system to be specified. | ![Notation of Control Unit](images/en-ecomod-notation-actor-controlunit.png) | ![Example of Control Unit](images/en-ecomod-sample-actor-controlunit.png) |
| «StatusIndicator» | Represents a foreign device that displays status information about the system to be specified. | ![Notation of Status Indicator](images/en-ecomod-notation-actor-statusindicator.png) | ![Example of Status Indicator](images/en-ecomod-sample-actor-statusindicator.png) |
| **_External Systems:_** |  |  |  |
| «ForeignSystem» | Represents a foreign system that receives data from the system to be specified. | ![Notation of Foreign System](images/en-ecomod-notation-actor-foreignsystem.png) | ![Example of Foreign System](images/en-ecomod-sample-actor-foreignsystem.png) |
| «BoundarySystem» | Represents a foreign system that acts as an interface between another system and the system to be specified. | ![Notation of Boundary System](images/en-ecomod-notation-actor-boundarysystem.png) | ![Example of Boundary System](images/en-ecomod-sample-actor-boundarysystem.png) |
| «UserSystem» | Represents a foreign system that acts as an interface between a human and the system to be specified. | ![Notation of User System](images/en-ecomod-notation-actor-usersystem.png) | ![Example of User System](images/en-ecomod-sample-actor-usersystem.png) |
| «Service» | Represents a foreign system that provides data to the system to be specified. | ![Notation of Service](images/en-ecomod-notation-actor-service.png) | ![Example of Service](images/en-ecomod-sample-actor-service.png) |


### Blocks

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «System» | Represents the system to be specified. | ![Notation of System](images/en-ecomod-notation-system.png) | ![Example of System](images/en-ecomod-sample-system.png) |
| «Context» | Represent a context in which communication links between the context objects are specified. | ![Example of Context](images/en-ecomod-notation-context.png) | ![Notation of Context](images/en-ecomod-sample-context-system.png) |


### Use Cases

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «SystemUC» | Represents a _System Use Case_ which is equivalent to a mandatory system function. It adds more properties to the SysML UseCase element. | ![Notation of System Use Case](images/en-ecomod-notation-systemusecase.png) | ![Example of System Use Case](images/en-ecomod-sample-systemusecase.png) |
| «continuousSUC» | Represents a specialized _System Use Case_ to model continuous behavior. | ![Notation of Continuous System Use Case](images/en-ecomod-notation-systemusecase-continuous.png) | ![Example of Continuous System Use Case](images/en-ecomod-sample-systemusecase-continuous.png) |
| «SystemProcess» | Represents a behavior of the system that brings the use case activities in a logical execution sequence. | ![Notation of System Process](images/en-ecomod-notation-systemprocess.png) | ![Example of System Process](images/en-ecomod-sample-systemprocess.png) |


### Requirements

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «Objective» | Represents a goal that should be achieved through system development. | ![Notation of Objective](images/en-ecomod-notation-objective.png) | ![Example of Objective](images/en-ecomod-sample-objective.png) |
| «Stakeholder» | Represents a person in a specific role or any kind of organization (e.g. a company department or government agency) that has interests, needs, concerns or doubt about the system, or is effected by the system. | ![Notation of System](images/en-ecomod-notation-stakeholder.png) | ![Example of System](images/en-ecomod-sample-stakeholder.png) |
| **_Functional:_** |  |  |  |
| «FunctionalReqt» | Represents a function of the system under consideration that must be provided by the system or by a system component. | ![Notation of Functional Requirement](images/en-ecomod-notation-sysreqt-functional.png) | ![Example of Functional Requirement](images/en-ecomod-sample-sysreqt-functional.png) |
| **_Qualities:_** |  |  |  |
| «FunctionalityReqt» | Represents a quality criteria regarding to functionality aspects like capability, reusability, compatibility, interoperability, or portability. | ![Notation of Functionality Requirement](images/en-ecomod-notation-quality-functionality.png) | ![Example of Functionality Requirement](images/en-ecomod-sample-quality-functionality.png) |
| «UsabilityReqt» | Represents a quality criteria regarding to usability aspects like human factors, aesthetics, consistency, documentation, or responsiveness. | ![Notation of Usability Requirement](images/en-ecomod-notation-quality-usability.png) | ![Example of Usability Requirement](images/en-ecomod-sample-quality-usability.png) |
| «ReliabilityReqt» | Represents a quality criteria regarding to reliability aspects like availability, recoverability, survivability, stability, or accuracy. | ![Notation of Reliability Requirement](images/en-ecomod-notation-quality-reliability.png) | ![Example of Reliability Requirement](images/en-ecomod-sample-quality-reliability.png) |
| «PerformanceReqt» | Represents a quality criteria regarding to the performance aspects like speed, efficiency, resource consumption, throughput, or capacity. | ![Notation of Performance Requirement](images/en-ecomod-notation-quality-performance.png) | ![Example of Performance Requirement](images/en-ecomod-sample-quality-performance.png) |
| «SupportabilityReqt» | Represents a quality criteria regarding to supportability aspects like maintainability, sustainability, testability, flexibility, installability, or localizability. | ![Notation of Supportability Requirement](images/en-ecomod-notation-quality-supportability.png) | ![Example of Supportability Requirement](images/en-ecomod-sample-quality-supportability.png) |
| «SecurityReqt» | Represents a quality criteria regarding to security aspects like safety, or exploitability. | ![Notation of Security Requirement](images/en-ecomod-notation-quality-security.png) | ![Example of Security Requirement](images/en-ecomod-sample-quality-security.png) |
| **_Constraints:_** |  |  |  |
| «TechnologicalReqt» | Represents a technological constraint on the design of system. | ![Notation of Technological Requirement](images/en-ecomod-notation-constraint-technological.png) | ![Example of Technological Requirement](images/en-ecomod-sample-constraint-technological.png) |
| «OrganizationallyReqt» | Represents a constraint on the system development process. | ![Notation of Organizationally Requirement](images/en-ecomod-notation-constraint-organizationally.png) | ![Example of Organizationally Requirement](images/en-ecomod-sample-constraint-organizationally.png) |
| «RegulatoryReqt» | Represents a regulatory constraint on the system development. | ![Notation of Regulatory Requirement](images/en-ecomod-notation-constraint-regulatory.png) | ![Example of Regulatory Requirement](images/en-ecomod-sample-constraint-regulatory.png) |



---
# TODO ** TODO ** TODO ** TODO ** TODO ** TODO ** TODO


### Domain Data/Knowledge

| Stereotype | Definition | Notation |
|:-----------|:-----------|:--------:|
| «InformationItem» | Represents an information that is transported either from an actor to the system, or from the system to an actor. | ![Notation of InformationItem](images/en-iotpml-informationitem.png) |



### System Decomposition Elements

| Stereotype | Definition | Notation |
|:-----------|:-----------|:--------:|
| BehavSpecification | Represents the behavior of a building block, especially a software component. | ![Notation of BehavSpecification](images/en-iotpml-behavspecification.png) |
| ControlPoint | Represents an action in a workflow where the measurement of time can be started or stopped. | ![Notation of ControlPoint](images/en-iotpml-controlpoint.png) |
| HwComponent | Represents a hardware building block the system to be specified is composed of. | ![Notation of HwComponent](images/en-iotpml-hwcomponent.png) |
| InteractionPoint | Represents an external interface of the system to be specified where it interacts with specific actors. | ![Notation of InteractionPoint](images/en-iotpml-interactionpoint.png) |
| SwComponent | Represents a software building block the system to be specified is composed of. | ![Notation of SwComponent](images/en-iotpml-swcomponent.png) |



### Software Stack Elements

| Stereotype | Definition | Notation |
|:-----------|:-----------|:--------:|
| SystemLayer | Represents specific level of abstraction within the software architecture that describes the embedding of the system to be specified into its environment.. | ![Notation of SystemLayer](images/en-iotpml-systemlayer.png) |
| ApplicationLayer | Represents specific level of abstraction within the software architecture that describes the applications provided by the system to be specified. | ![Notation of ApplicationLayer](images/en-iotpml-applicationlayer.png) |
| DriverLayer| Represents specific level of abstraction within the software architecture that describes which protocols are supported by the system to be specified. | ![Notation of DriverLayer](images/en-iotpml-driverlayer.png) |
| HwAbstractionLayer | Represents specific level of abstraction within the software architecture that describes how the software components of the **_DriverLayer_** communicate whith the hardware components the system to be specified is composed of. | ![Notation of HwAbstractionLayer](images/en-iotpml-hwabstractionlayer.png) |
| HwPlatformLayer | Represents specific level of abstraction within the software architecture that describes which communication technologies are used in the system to be specified. | ![Notation of HwPlatformLayer](images/en-iotpml-hwplatformlayer.png) |
| InterfaceRepository | Represents, within an abstraction layer, a specific storage location for interface definitions provided or required by the building blocks (_the software components_) that compose the IoT software stack.. | ![Notation of InterfaceRepository](images/en-iotpml-interfacerepository.png) |
| ImplementationRepository | Represents, within an abstraction layer, a specific storage location for the functional specification of building blocks (_the software components_) used to compose the IoT software stacks. | ![Notation of ImplementationRepository](images/en-iotpml-implementationrepository.png) |
| DesignRepository | Represents, within an abstraction layer, a specific storage location for the functional application of the building blocks (_the software components_) that compose the IoT software stack. | ![Notation of DesignRepository](images/en-iotpml-designrepository.png) |
| ImplementationElement | Represents a software artifact needed for implementation. | ![Notation of ImplementationElement](images/en-iotpml-implementationelement.png) |
| Field | Represents an addressable storage place of a hardware component that is characterized as memory block. | ![Notation of Field]
(images/en-iotpml-field.png) |
| Register | Represents an addressable storage place of a hardware component that is characterized as processing or control unit (but not as memory block). | ![Notation of Register](images/en-iotpml-register.png) |
| Provided Interface | Represents an interface that is offered by a system-internal component. | ![Notation of Provided Interface Element](images/en-iotpml-providedinterface.png) |
| Required Interface | Represents an interface that is needed by a system-internal component. | ![Notation of Required Interface Element](images/en-iotpml-requiredinterface.png) |
| Behaviour | Represents an interface operation's behavior. | ![Notation of Behaviour](images/en-iotpml-behaviour.png) |


---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
