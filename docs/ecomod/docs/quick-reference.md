# The ECOMOD Profile Quick Reference


## Profile Elements


### Activities

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «continuousAction» | Represents a continuous executed Action. | ![Notation](images/en-ecomod-notation-action-continuous.png) | ![Example](images/en-ecomod-sample-action-continuous.png) |
| «continuousActivity» | Represents a continuous running Activity. | ![Notation](images/en-ecomod-notation-activity-continuous.png) |![Example](images/en-ecomod-sample-activity-continuous.png) |
| «continuousEssentialStep» | Represents an essential atomic step in a _Use Case_ workflow that is executed continuous. | ![Notation](images/en-ecomod-notation-action-essential-step-continuous.png) | ![Example](images/en-ecomod-sample-action-essential-step-continuous.png) |
| «continuousUseCaseActivity» | Represents the workflow executed in a _Continuous Use Case_. | ![Notation](images/en-ecomod-notation-activity-usecase-continuous.png) |![Example](images/en-ecomod-sample-activity-usecase-continuous.png) |
| «EssentialStep» | Represents an essential atomic step in a _Use Case_ workflow. | ![Notation](images/en-ecomod-notation-action-essential-step.png) | ![Example](images/en-ecomod-sample-action-essential-step.png) |
| «EssentialUCStep» | Represents an essential complex step in a _Use Case_. | ![Notation](images/en-ecomod-notation-activity-usecase-essential-step.png) |![Example](images/en-ecomod-sample-activity-usecase-essential-step.png) |
| «SendIndicationAction» | Represents the sending of an indication. | ![Notation](images/en-ecomod-notation-action-send-indication.png) | ![Example](images/en-ecomod-sample-action-send-indication.png) |
| «SendIndicationMessage» | Represents the sending of a message. | ![Notation](images/en-ecomod-notation-action-send-message.png) | ![Example](images/en-ecomod-sample-action-send-message.png) |
| «SendIndicationSignal» | Represents the sending of a signal. | ![Notation](images/en-ecomod-notation-action-send-signal.png) | ![Example](images/en-ecomod-sample-action-send-signal.png) |
| «UseCaseActivity» | Represents the workflow executed in a _Use Case_. | ![Notation](images/en-ecomod-notation-activity-usecase.png) |![Example](images/en-ecomod-sample-activity-usecase.png) |


### Actors

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «Actuator» | Represents a foreign device that has an effect on the environment and is controlled by the system to be specified. | ![Notation](images/en-ecomod-notation-actor-actuator.png) | ![Example](images/en-ecomod-sample-actor-actuator.png) |
| «BoundarySystem» | Represents a foreign system that acts as an interface between another system and the system to be specified. | ![Notation](images/en-ecomod-notation-actor-boundarysystem.png) | ![Example](images/en-ecomod-sample-actor-boundarysystem.png) |
| «ControlUnit» | Represents a foreign device that provides data from the environment to the system to be specified. | ![Notation](images/en-ecomod-notation-actor-controlunit.png) | ![Example](images/en-ecomod-sample-actor-controlunit.png) |
| «EnvironmentalEffect» | Represents a relevant effect (e.g. humidity or temperature) from the system's environment that influences the system to be specified. | ![Notation](images/en-ecomod-notation-actor-environmentaleffect.png) | ![Example](images/en-ecomod-sample-actor-environmentaleffect.png) |
| «ForeignSystem» | Represents a foreign system that receives data from the system to be specified. | ![Notation](images/en-ecomod-notation-actor-foreignsystem.png) | ![Example](images/en-ecomod-sample-actor-foreignsystem.png) |
| «Sensor | Represents a foreign device that provides data from the environment to the system to be specified. | ![Notation](images/en-ecomod-notation-actor-sensor.png) | ![Example](images/en-ecomod-sample-actor-sensor.png) |
| «Service» | Represents a foreign system that provides data to the system to be specified. | ![Notation](images/en-ecomod-notation-actor-service.png) | ![Example](images/en-ecomod-sample-actor-service.png) |
| «StatusIndicator» | Represents a foreign device that displays status information about the system to be specified. | ![Notation](images/en-ecomod-notation-actor-statusindicator.png) | ![Example](images/en-ecomod-sample-actor-statusindicator.png) |
| «User» | Represents a human actor. It's defined to distinct an user from a _Stakeholder_. | ![Notation](images/en-ecomod-notation-actor-user.png) | ![Example](images/en-ecomod-sample-actor-user.png) |
| «UserSystem» | Represents a foreign system that acts as an interface between a human and the system to be specified. | ![Notation](images/en-ecomod-notation-actor-usersystem.png) | ![Example](images/en-ecomod-sample-actor-usersystem.png) |


### Behavior

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «ProcessBehavior» | Represents the behavior of a process. | ![Notation](images/en-ecomod-notation-behavior-process.png) | ![Example](images/en-ecomod-sample-behavior-process.png) |


### Blocks

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «Context» | Represent a context in which communication links between the context objects are specified. | ![Notation](images/en-ecomod-notation-context.png) | ![Example](images/en-ecomod-sample-context-system.png) |
| «System» | Represents the system to be specified. | ![Notation](images/en-ecomod-notation-system.png) | ![Example](images/en-ecomod-sample-system.png) |
| «HardwareBlock» | Represents a hardware building block. | ![Notation](images/en-ecomod-notation-block-hardware.png) | ![Example](images/en-ecomod-sample-block-hardware.png) |
| «HwSubsystem» | Represents a logical hardware building block. | ![Notation](images/en-ecomod-notation-block-subsystem-hardware.png) | ![Example](images/en-ecomod-sample-block-subsystem-hardware.png) |
| «SoftwareBlock» | Represents a software building block. | ![Notation](images/en-ecomod-notation-block-software.png) | ![Example](images/en-ecomod-sample-block-software.png) |
| «SwSubsystem» | Represents a logical software building block. | ![Notation](images/en-ecomod-notation-block-subsystem-software.png) | ![Example](images/en-ecomod-sample-block-subsystem-software.png) |
| «Subsystem» | Represents a logical building block. | ![Notation](images/en-ecomod-notation-block-subsystem.png) | ![Example](images/en-ecomod-sample-block-subsystem.png) |
| «SwApplication» | Represents a software building block on application layer. | ![Notation](images/en-ecomod-notation-software-application.png) | ![Example](images/en-ecomod-sample-software-application.png) |
| «SwComponent» | Represents a software building block on component layer. | ![Notation](images/en-ecomod-notation-software-component.png) | ![Example](images/en-ecomod-sample-software-component.png) |
| «SwDriver» | Represents a software building block on driver layer. | ![Notation](images/en-ecomod-notation-software-driver.png) | ![Example](images/en-ecomod-sample-software-driver.png) |


### Interactions

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «continuousInteractionOccurence» | Represents a continuous executed interaction. | ![Notation](images/en-ecomod-notation-interaction-continuous-occurrence.png) |![Example](images/en-ecomod-sample-interaction-continuous-occurrence.png) |
| «Lifeline[Hardware]» | Represents the lifeline of a _Hardware Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-block-hardware.png) |![Example](images/en-ecomod-sample-lifeline-block-hardware.png) |
| «Lifeline[HwSubsystem]» | Represents the lifeline of a _Hardware Subsystem Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-block-subsystem-hardware.png) |![Example](images/en-ecomod-sample-lifeline-block-subsystem-hardware.png) |
| «Lifeline[Software]» | Represents the lifeline of a _Software Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-block-software.png) |![Example](images/en-ecomod-sample-lifeline-block-software.png) |
| «Lifeline[Subsystem]» | Represents the lifeline of a _Subsystem Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-block-subsystem.png) |![Example](images/en-ecomod-sample-lifeline-block-subsystem.png) |
| «Lifeline[SwApplication]» | Represents the lifeline of a _Software Application Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-software-application.png) |![Example](images/en-ecomod-sample-lifeline-software-application.png) |
| «Lifeline[SwComponent]» | Represents the lifeline of a _Software Component Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-software-component.png) |![Example](images/en-ecomod-sample-lifeline-software-component.png) |
| «Lifeline[SwDriver]» | Represents the lifeline of a _Software Driver Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-software-driver.png) |![Example](images/en-ecomod-sample-lifeline-software-driver.png) |
| «Lifeline[SwSubsystem]» | Represents the lifeline of a _Software Subsystem Block_ in an interaction. | ![Notation](images/en-ecomod-notation-lifeline-block-subsystem-software.png) |![Example](images/en-ecomod-sample-lifeline-block-subsystem-software.png) |
| «ScenarioInteraction» | Represents the interaction of an architecture scenario. | ![Notation](images/en-ecomod-notation-interaction-scenario.png) |![Example](images/en-ecomod-sample-interaction-scenario.png) |


### Use Cases

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «continuous» | Represents a _Use Case_ having continuous behavior. | ![Notation](images/en-ecomod-notation-systemusecase-continuous.png) | ![Example](images/en-ecomod-sample-systemusecase-continuous.png) |
| «primary» | Represents a _Use Case_ which is equivalent to a mandatory system function. | ![Notation](images/en-ecomod-notation-systemusecase-primary.png) | ![Example](images/en-ecomod-sample-systemusecase-primary.png) |
| «supporting» | Represents a _Use Case_ which provides a (reuseable) supporting function. | ![Notation](images/en-ecomod-notation-systemusecase-supporting.png) | ![Example](images/en-ecomod-sample-systemusecase-supporting.png) |
| «SystemProcess» | Represents a behavior of the system that brings the use case activities in a logical execution sequence. | ![Notation](images/en-ecomod-notation-systemprocess.png) | ![Example](images/en-ecomod-sample-systemprocess.png) |


### Requirements

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «Objective» | Represents a goal that should be achieved through system development. | ![Notation](images/en-ecomod-notation-objective.png) | ![Example](images/en-ecomod-sample-objective.png) |
| «Stakeholder» | Represents a person in a specific role or any kind of organization (e.g. a company department or government agency) that has interests, needs, concerns or doubt about the system, or is effected by the system. | ![Notation](images/en-ecomod-notation-stakeholder.png) | ![Example](images/en-ecomod-sample-stakeholder.png) |
| **_Functional:_** |  |  |  |
| «IndependentSysActivityReqt» | Represents a functional requirement that describes an independent system activity. | ![Notation](images/en-ecomod-notation-sysreqt-functional-independent-system-activity.png) | ![Example](images/en-ecomod-sample-sysreqt-functional-independent-system-activity.png) |
| «InterfaceInteractionReqt» | Represents a functional requirement that describes an interface interaction. | ![Notation](images/en-ecomod-notation-sysreqt-functional-interface-interaction.png) | ![Example](images/en-ecomod-sample-sysreqt-functional-interface-interaction.png) |
| «UserInteractionReqt» | Represents a functional requirement that describes an user interaction. | ![Notation](images/en-ecomod-notation-sysreqt-functional-user-interaction.png) | ![Example](images/en-ecomod-sample-sysreqt-functional-user-interaction.png) |
| **_Qualities (FURPS+):_** |  |  |  |
| «FunctionalityReqt» | [FURPS+] Represents a quality criteria regarding to _Functionality_ aspects like capability, reusability, compatibility, interoperability, or portability. | ![Notation](images/en-ecomod-notation-quality-furps-functionality.png) | ![Example](images/en-ecomod-sample-quality-furps-functionality.png) |
| «UsabilityReqt» | [FURPS+] Represents a quality criteria regarding to _Usability_ aspects like human factors, aesthetics, consistency, documentation, or responsiveness. | ![Notation](images/en-ecomod-notation-quality-furps-usability.png) | ![Example](images/en-ecomod-sample-quality-furps-usability.png) |
| «ReliabilityReqt» | [FURPS+] Represents a quality criteria regarding to _Reliability_ aspects like availability, recoverability, survivability, stability, or accuracy. | ![Notation](images/en-ecomod-notation-quality-furps-reliability.png) | ![Example](images/en-ecomod-sample-quality-furps-reliability.png) |
| «PerformanceReqt» | [FURPS+] Represents a quality criteria regarding to the _Performance_ aspects like speed, efficiency, resource consumption, throughput, or capacity. | ![Notation](images/en-ecomod-notation-quality-furps-performance.png) | ![Example](images/en-ecomod-sample-quality-furps-performance.png) |
| «SupportabilityReqt» | [FURPS+] Represents a quality criteria regarding to _Supportability_ aspects like maintainability, sustainability, testability, flexibility, installability, or localizability. | ![Notation](images/en-ecomod-notation-quality-furps-supportability.png) | ![Example](images/en-ecomod-sample-quality-furps-supportability.png) |
| «SecurityReqt» | [FURPS+] Represents a quality criteria regarding to _Security_ aspects like safety, or exploitability. | ![Notation](images/en-ecomod-notation-quality-furps-security.png) | ![Example](images/en-ecomod-sample-quality-furps-security.png) |
| **_Qualities (ISO 9126):_** |  |  |  |
| «EfficiencyReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to the _Efficiency_ aspects like speed, efficiency, resource consumption, throughput, or capacity. | ![Notation](images/en-ecomod-notation-quality-iso9126-efficiency.png) | ![Example](images/en-ecomod-sample-quality-iso9126-efficiency.png) |
| «FunctionalityReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to _Functionality_ aspects like capability, reusability, compatibility, interoperability, or portability. | ![Notation](images/en-ecomod-notation-quality-iso9126-functionality.png) | ![Example](images/en-ecomod-sample-quality-iso9126-functionality.png) |
| «MaintainabilityReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to _Maintainability_ aspects like maintainability, sustainability, testability, flexibility, installability, or localizability. | ![Notation](images/en-ecomod-notation-quality-iso9126-maintainability.png) | ![Example](images/en-ecomod-sample-quality-iso9126-maintainability.png) |
| «PortabilityReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to _Portability_ aspects like safety, or exploitability. | ![Notation](images/en-ecomod-notation-quality-iso9126-portability.png) | ![Example](images/en-ecomod-sample-quality-iso9126-portability.png) |
| «ReliabilityReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to _Reliability_ aspects like availability, recoverability, survivability, stability, or accuracy. | ![Notation](images/en-ecomod-notation-quality-iso9126-reliability.png) | ![Example](images/en-ecomod-sample-quality-iso9126-reliability.png) |
| «UsabilityReqt_ISO9126» | [ISO 9126] Represents a quality criteria regarding to _Usability_ aspects like human factors, aesthetics, consistency, documentation, or responsiveness. | ![Notation](images/en-ecomod-notation-quality-iso9126-usability.png) | ![Example](images/en-ecomod-sample-quality-iso9126-usability.png) |
| **_Qualities (ISO 25010):_** |  |  |  |
| «QiU_ContextCoverage_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Context Coverage_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qiu-context-coverage.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qiu-context-coverage.png) |
| «QiU_FreedomFromRisk_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Freedom from Risks_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qiu-freedom-from-risk.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qiu-freedom-from-risk.png) |
| «QiU_Satisfaction_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Satisfaction_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qiu-satisfaction.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qiu-satisfaction.png) |
| «QoP_Compability_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Compability_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-compability.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-compability.png) |
| «QoP_FunctionalSuitability_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Functional Suitability_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-functional-suitability.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-functional-suitability.png) |
| «QoP_Maintainablility_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Maintainablility_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-maintainablility.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-maintainablility.png) |
| «QoP_PerformanceEfficiency_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Performance Efficiency_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-performance-efficiency.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-performance-efficiency.png) |
| «QoP_Portability_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Portability_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-portability.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-portability.png) |
| «QoP_Reliability_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Reliability_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-reliability.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-reliability.png) |
| «QoP_Security_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Security_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-security.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-security.png) |
| «QoP_Usability_ISO25010_» | [ISO 25010] Represents a quality-in-use criteria regarding to _Usability_ aspects. | ![Notation](images/en-ecomod-notation-quality-iso25010-qop-usability.png) | ![Example](images/en-ecomod-sample-quality-iso25010-qop-usability.png) |
| **_Constraints:_** |  |  |  |
| «DeliveryComponentsReqt» | Represents a constraint on other delivery components. | ![Notation](images/en-ecomod-notation-constraint-regulatory.png) | ![Example](images/en-ecomod-sample-constraint-regulatory.png) |
| «OrganizationalReqt» | Represents a constraint on the system development process. | ![Notation](images/en-ecomod-notation-constraint-organizational.png) | ![Example](images/en-ecomod-sample-constraint-organizational.png) |
| «PhysicalReqt» | Represents a physical constraint that restricts the system design. | ![Notation](images/en-ecomod-notation-constraint-physical.png) | ![Example](images/en-ecomod-sample-constraint-physical.png) |
| «RegulatoryReqt» | Represents a regulatory constraint on the system development. | ![Notation](images/en-ecomod-notation-constraint-regulatory.png) | ![Example](images/en-ecomod-sample-constraint-regulatory.png) |
| «TechnologicalReqt» | Represents a technological constraint that restricts the system design. | ![Notation](images/en-ecomod-notation-constraint-technological.png) | ![Example](images/en-ecomod-sample-constraint-technological.png) |
| «UserInterfaceReqt» | Represents a user interface constraint that restricts the system design. | ![Notation](images/en-ecomod-notation-constraint-user-interface.png) | ![Example](images/en-ecomod-sample-constraint-user-interface.png) |


### Ports

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «InteractionPoint» | Represents a specific point over that the system and its environment interacts with its environment. | ![Notation](images/en-ecomod-notation-port-interaction-point.png) | ![Example](images/en-ecomod-sample-port-interaction-point.png) |
| «ProvidingPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-providing.png) | ![Example](images/en-ecomod-sample-port-providing.png) |
| «ReceiverPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-receiver.png) | ![Example](images/en-ecomod-sample-port-receiver.png) |
| «RequiringPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-requiring.png) | ![Example](images/en-ecomod-sample-port-requiring.png) |
| «SenderPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-sender.png) | ![Example](images/en-ecomod-sample-port-sender.png) |
| «SwProvidedIntfPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-provided-interface.png) | ![Example](images/en-ecomod-sample-port-provided-interface.png) |
| «SwRequiredIntfPort» | Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-required-interface.png) | ![Example](images/en-ecomod-sample-port-required-interface.png) |
| «TypedInteractionPoint» | [electrical] Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-interaction-point-typed-electrical.png) | ![Example](images/en-ecomod-sample-port-interaction-point-typed-electrical.png) |
| «TypedInteractionPoint» | [logical] Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-interaction-point-typed-logical.png) | ![Example](images/en-ecomod-sample-port-interaction-point-typed-logical.png) |
| «TypedInteractionPoint» | [mechanical] Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-interaction-point-typed-mechanical.png) | ![Example](images/en-ecomod-sample-port-interaction-point-typed-mechanical.png) |
| «TypedInteractionPoint» | [service] Represents ...TODO... | ![Notation](images/en-ecomod-notation-port-interaction-point-typed-service.png) | ![Example](images/en-ecomod-sample-port-interaction-point-typed-service.png) |


### Properties

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «Part[Hardware]» | Represents the role of a _Hardware Block_ in an internal block view. | ![Notation](images/en-ecomod-notation-property-block-hardware.png) | ![Example](images/en-ecomod-sample-property-block-hardware.png) |
| «Part[HwSubsystem]» | Represents the role of a _Hardware Subsystem Block_ in an internal block view. | ![Notation](images/en-ecomod-notation-property-block-subsystem-hardware.png) | ![Example](images/en-ecomod-sample-property-block-subsystem-hardware.png) |
| «Part[Software]» | Represents the role of a _Software Block_ in an internal block view. | ![Notation](images/en-ecomod-notation-property-block-software.png) | ![Example](images/en-ecomod-sample-property-block-software.png) |
| «Part[Subsystem]» | Represents the role of a _Subsystem Block_ in an internal block view. | ![Notation](images/en-ecomod-notation-property-block-subsystem.png) | ![Example](images/en-ecomod-sample-property-block-subsystem.png) |
| «Part[SwApplication]» | Represents the role of a _Software Application Block_ in a composite structure view. | ![Notation](images/en-ecomod-notation-property-software-application.png) | ![Example](images/en-ecomod-sample-property-software-application.png) |
| «Part[SwComponent]» | Represents the role of a _Software Component Block_ in a composite structure view. | ![Notation](images/en-ecomod-notation-property-software-component.png) | ![Example](images/en-ecomod-sample-property-software-component.png) |
| «Part[SwDriver]» | Represents the role of a _Software Driver Block_ in a composite structure view. | ![Notation](images/en-ecomod-notation-property-software-driver.png) | ![Example](images/en-ecomod-sample-property-software-driver.png) |
| «Part[SwSubsystem]» | Represents the role of a _Software Subsystem Block_ in an internal block view. | ![Notation](images/en-ecomod-notation-property-block-subsystem-software.png) | ![Example](images/en-ecomod-sample-property-block-subsystem-software.png) |


### Artificial Neural Networks

| Stereotype | Definition | Notation | Example |
|:-----------|:-----------|:--------:|:-------:|
| «ANN Code Profiling» | Represents the profiling features for an static or dynamic analysis of the generated ANN source code. | ![Notation](images/en-ecomod-notation-ann-sourcecode-profiling.png) | ![Example](images/en-ecomod-sample-ann-sourcecode-profiling.png) |
| «ANN Source Code» | Represents the source code generated for the ANN by an AI compiler. | ![Notation](images/en-ecomod-notation-ann-sourcecode.png) | ![Example](images/en-ecomod-sample-ann-sourcecode.png) |
| **_Architecture:_** |  |  |  |
| «Asynchronous ANN» | Represents an _Asynchronous ANN_. | ![Notation](images/en-ecomod-notation-ann-type-asynchronous.png) | ![Example](images/en-ecomod-sample-ann-type-asynchronous.png) |
| «Convolutional ANN» | Represents an _Convolutional ANN_. | ![Notation](images/en-ecomod-notation-ann-type-convolutional.png) | ![Example](images/en-ecomod-sample-ann-type-convolutional.png) |
| «Cyclic ANN» | Represents an _Cyclic ANN_. | ![Notation](images/en-ecomod-notation-ann-type-cyclic.png) | ![Example](images/en-ecomod-sample-ann-type-cyclic.png) |
| «Feedforward ANN» | Represents an _Feedforward ANN_. | ![Notation](images/en-ecomod-notation-ann-type-feedforward.png) | ![Example](images/en-ecomod-sample-ann-type-feedforward.png) |
| «Recurrent ANN» | Represents an _Recurrent ANN_. | ![Notation](images/en-ecomod-notation-ann-type-recurrent.png) | ![Example](images/en-ecomod-sample-ann-type-recurrent.png) |
| «Self-Associative ANN» | Represents an _Self-Associative ANN_. | ![Notation](images/en-ecomod-notation-ann-type-selfassociative.png) | ![Example](images/en-ecomod-sample-ann-type-selfassociative.png) |
| «Single-Layer ANN» | Represents an _Single-Layer ANN_. | ![Notation](images/en-ecomod-notation-ann-type-singlelayer.png) | ![Example](images/en-ecomod-sample-ann-type-singlelayer.png) |
| «Symmetric ANN» | Represents an _Symmetric ANN_. | ![Notation](images/en-ecomod-notation-ann-type-symmetric.png) | ![Example](images/en-ecomod-sample-ann-type-symmetric.png) |
| «ActivationLayer» | Represents an _Activation Layer_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-layer-activation.png) | ![Example](images/en-ecomod-sample-ann-layer-activation.png) |
| «CombinationLayer» | Represents an _Combination Layer_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-layer-combination.png) | ![Example](images/en-ecomod-sample-ann-layer-combination.png) |
| «NormalizationLayer» | Represents an _Normalization Layer_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-layer-normalization.png) | ![Example](images/en-ecomod-sample-ann-layer-normalization.png) |
| «ActivationNeuron» | Represents an _Activation Neuron_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-neuron-activation.png) | ![Example](images/en-ecomod-sample-ann-neuron-activation.png) |
| «CombinationNeuron» | Represents an _Combination Neuron_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-neuron-combination.png) | ![Example](images/en-ecomod-sample-ann-neuron-combination.png) |
| «NormalizationNeuron» | Represents an _Normalization Neuron_ of an ANN. | ![Notation](images/en-ecomod-notation-ann-neuron-normalization.png) | ![Example](images/en-ecomod-sample-ann-neuron-normalization.png) |
| **_Machine Learning:_** |  |  |  |
| «ML Classification» | Represents the supervised machine learning (ML) method _Classification_. | ![Notation](images/en-ecomod-notation-ann-ml-classification.png) | ![Example](images/en-ecomod-sample-ann-ml-classification.png) |
| «ML Clustering» | Represents the unsupervised machine learning (ML) method _Clustering_. | ![Notation](images/en-ecomod-notation-ann-ml-clustering.png) | ![Example](images/en-ecomod-sample-ann-ml-clustering.png) |
| «ML Decision-Making» | Represents the reinforcement machine learning (ML) method _Decision-Making_. | ![Notation](images/en-ecomod-notation-ann-ml-decision-making.png) | ![Example](images/en-ecomod-sample-ann-ml-decision-making.png) |
| «ML Regression» | Represents the supervised machine learning (ML) method _Regression_. | ![Notation](images/en-ecomod-notation-ann-ml-regression.png) | ![Example](images/en-ecomod-sample-ann-ml-regression.png) |
| «ML Process» | Represents the workflow of the machine learning (ML) procedure. | ![Notation](images/en-ecomod-notation-ann-ml-process.png) | ![Example](images/en-ecomod-sample-ann-ml-process.png) |
| «ML Test Dataset» | Represents the structural description of a dataset used to test the ANN. | ![Notation](images/en-ecomod-notation-ann-ml-dataset-test.png) | ![Example](images/en-ecomod-sample-ann-ml-dataset-test.png) |
| «ML Training Dataset» | Represents the structural description of a dataset used to train the ANN. | ![Notation](images/en-ecomod-notation-ann-ml-dataset-training.png) | ![Example](images/en-ecomod-sample-ann-ml-dataset-training.png) |
| «ML Validation Dataset» | Represents the structural description of a dataset used to validate the ANN. | ![Notation](images/en-ecomod-notation-ann-ml-dataset-validation.png) | ![Example](images/en-ecomod-sample-ann-ml-dataset-validation.png) |
| «ML Test Database» | Represents the concrete database of the test data. | ![Notation](images/en-ecomod-notation-ann-ml-database-test.png) | ![Example](images/en-ecomod-sample-ann-ml-database-test.png) |
| «ML Training Database» | Represents the concrete database of the training data. | ![Notation](images/en-ecomod-notation-ann-ml-database-training.png) | ![Example](images/en-ecomod-sample-ann-ml-database-training.png) |
| «ML Validation Database» | Represents the concrete database of the validation data. | ![Notation](images/en-ecomod-notation-ann-ml-database-validation.png) | ![Example](images/en-ecomod-sample-ann-ml-database-validation.png) |


---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
