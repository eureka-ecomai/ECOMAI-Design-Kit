# The ECOMOD Process Model


The **_ECOMOD Process Model_** presented here is a description of only one of the possible and logically sensible execution sequences of the [ECOMOD Methods](methods.md). The order and selection of methods can be different in each project.

In particular, the logical order and the timely order should not mix up! The logical order does not imply a waterfall process. The _ECOMOD Process Model_ is independent of a waterfall or agile approach.


The _ECOMOD Process Model_ defines the two basic processes: **Preparation** and **Structuring**.

The goal of the _Preparation_ is to know and understand all relevant objectives, required functionality, qualities expected and constraints. 
Based on this knowledge, we decide on a suitable solution architecture and specify the requirements and architectural decisions more precisely in a formal specification, which is the goal of _Structuring_.


Regarding to the consideration on different levels the following concrete processes result:

+ [System Preparation](#system-preparation)

+ [System Structuring](#system-structuring)

+ [System Preparation](#system-analysis-process)

+ [System Structuring](#system-architecture-process)


At _System Level_, the processes [System Preparation](#system-preparation) and [System Structuring](#system-structuring) ensure that the requirements and architecture of the overall system have been sufficiently considered **before** the implementation of the software is started.

And at _Software Level_, the processes [Software Preparation](#software-preparation) and [Software Structuring](#software-structuring) ensure that  implementation of a supporting software solution is based on proper requirements and architecture decisions.


Please note, that the processes presented here are only a description of one useful logical order of execution of the [ECOMOD Methods](methods.md). The order and selection of the methods will be different in each project.


_Note: The figures shown in the sections below use the UML notation for activities._



## System Preparation

![ECOMOD System Preparation](images/en-ecomod-processes-system-preparation.png)

#### Necessary Inputs:

_-none-_

#### Produced Outcomes:

+ [System Idea](product_system-idea.md)
+ [System Objectives](product_system-objectives.md)
+ [Stakeholders](product_stakeholders.md)
+ [Base Architecture](product_base-architecture.md)
+ [Requirements](product_requirements.md)
+ [System Context](product_system-context.md)
+ [System Use Cases](product_system-usecases.md)
+ [System Processes](product_system-processes.md)
+ [Use Case Activities](product_usecase-activities.md)
+ [Domain Knowledge](product_domain-knowledge.md)

#### Applied Methods:

+ [Identify Stakeholders](method_stakeholders.md)
+ [Describe System Idea & Objectives](method_system-idea-objectives.md)
+ [Describe Base Architecture](method_base-architecture.md)
+ [Model Requirements](method_requirements.md)
+ [Identify System Context](method_system-context.md)
+ [Identify System Use Cases](method_system-usecases.md)
+ [Identify System Processes](method_system-processes.md)
+ [Model Use Cases Activities](method_usecase-activities.md)
+ [Model Domain Knowledge](method_domain-knowledge.md)



## System Structuring

![ECOMOD System Structuring Process](images/en-ecomod-processes-system-structuring.png)

#### Necessary Inputs:

+ [System Context](product_system-context.md)
+ [Requirements](product_requirements.md)
+ [System Use Cases](product_system-usecases.md)
+ [Base Architecture](product_base-architecture.md) (_optional_)
+ [Functional Architecture](product_functional-architecture.md) (_optional_)

#### Produced Outcomes:

+ [Logical Architecture](product_logical-architecture.md)
+ [Product Architecture](product_product-architecture.md)
+ [Scenarios](product_architecture-scenarios.md)
+ [System States](product_system-states.md)

#### Applied Methods:

+ [Model Logical Architecture](method_logical-architecture.md)
+ [Specialize Product Architecture](methods_product-architecture.md)
+ [Define System States](methods_system-states.md)
+ [Verify Architecture with Scenarios](methods_architecture-scenarios.md)



## Software Preparation

![ECOMOD Software Preparation](images/en-ecomod-processes-software-preparation.png)

#### Necessary Inputs:

_-none-_

#### Produced Outcomes:

+ [XXX](product_software-XXX.md)

#### Applied Methods:

+ [YYY](method_YYY.md)



## Software Structuring

![ECOMOD Software Structuring](images/en-ecomod-processes-software-structuring.png)

#### Necessary Inputs:

_-none-_

#### Produced Outcomes:

+ [XXX](product_software-XXX.md)

#### Applied Methods:

+ [YYY](method_YYY.md)

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
