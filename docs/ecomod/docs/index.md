# The ECOMOD Methodology


_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |

---

![QR-Code](images/ecomod_qr_contact-request_250x250.png) Contact Request (e-Mail)


## Preface

_Please note, that currently the version 1 of the ECOMOD approach is available which only supports the modeling on System-Level._


This documentation uses some common terms with many different meanings. To clarify their meanings in this documentation, here is a list of definitions:

+ A **process** is a logical sequence of tasks performed to archive a particular objective; in other words, a process defines "what" is to be done, without specifying "how" each task is performed.

+ A **method** consists of techniques for performing a task; in other words, it defines the "how" of each task.

+ A **tool** facilitates the accomplishment of the methods.

+ A **methodology** is a consistent set of related processes, methods and tools.

+ A **product** is the outcome of a process and therfore a part of the methodology.


## Why ECOMOD?

ECOMOD is an abbreviation for _**ECO**MAI **Mod**eling Toolbox_ and was developed within the Eureka Penta project ECOMAI (_Ecological Motor Control and Predictive Maintenance with AI_).

ECOMOD is the result of the analysis of the different projects that were selected and researched as use cases by the partners within the ECOMAI project. Essentially, the systems behind these partner projects only differed from other embedded or IoT systems with a high software content through the use of AI-supported data processing.

The analysis also led to the realization that most embedded or IoT systems can basically be divided into the following categories:

+ Autonomous Data Collector System
+ Autonomous Control Loop System
+ Actor-controlled System

The typical characteristic of autonomously operating systems is that their services (or _system functions_) are not triggered by an actor or an event from the system environment (_"from outside"_). Rather, there is a continuously running system process that reacts to (internal or external) events and then triggers the system functions.

The main difference between the both autonomous system types is that in a _Autonomous Control Loop System_ the elements implementing the control loop are typically duplicated.

While accompanying the partner projects regarding model-based development, the impression was gained that the focus of analysis and design - probably due to the high proportion of software - was more on the description of the software solution and less on a holistic view at the system level without immediately sliding to the technology level.


## What is ECOMOD?

ECOMOD is neither a completely new system development process nor a new modeling language or simply a language extension. It's an approach trying to solve the problems on focusing in system development projects. 
It was inspired by the activities and tasks in the [Rational Unified Process](https://en.wikipedia.org/wiki/Rational_unified_process) (RUP) and the [System Modeling Toolbox](https://mbse4u.com/sysmod/) (SYSMOD) by Tim Weilkiens as well as by the ideas of the [SOPHISTs](https://www.sophist.de/).

The ECOMOD as a toolbox defines a methodology consisting of activities, methods and products, and provides appropriate model objects in the form of a language extension and model templates.

ECOMOD can also be used outside the ECOMAI context, it was designed to support the model-based development of any small or medium-sized embedded and IoT systems with a high software content. ECOMOD works together with the _OMG Systems Modeling Language_ (OMG SysML), which is a general-purpose modeling language for systems engineering and a world-wide standard. It is not mandatory to combine ECOMOD with the SysML. The combination with the _OMG Unified Modeling Language_ (OMG UML), which is also a world-wide standard, is possible too.


ECOMOD aims to support the model-based development of embedded or IoT systems with a high software content. The focus of the support is exclusively on the disciplines _Requirements Engineering_ and _Analysis and Design_, in which the system development is considered on two levels: the **System Level** and the **Software Level**. _[1]_

_Note: Consideration of system development at different levels also has the advantage that tailoring will be possible; for example, for very simple projects, the description at system level may be completely sufficient._


At each levels, a strict separation is made between "_the problem_" and "_the solution_". Therefore, the outcome of such a consideration consists of two models: a **Requirements Model** as a description of “_the problem_” and an **Architecture Model** as documentation of “_a appropriate solution_”. This ensures that all relevant information is available in the necessary completeness in order to provide a basis for a successful system implementation.

Therefore, the concrete results of the consideration on _System Level_ are the [System Requirements Model](products.md#system-requirements-model) and the [System Architecture Model](products.md#system-architecture-model), those on _Software Level_ the [Software Requirements Model](products.md#software-requirements-model) and the [Software Architecture Model](products.md#software-architecture-model).


These models consists of various **products**, which are produced by executing a set of several **methods**, which can be summarized in different (logical) **processes**. _[2]_


The [ECOMOD Products](products.md) are the crucial artifacts of the system development like functional and non-functional requirements, use cases or architectural subsystems. The [ECOMOD Methods](methods.md) are best practices how to create the _ECOMOD Products_.

Although ECOMOD is not a process, this documentation also provides some [Processes](processes.md) to demonstrate a typical logical order of execution of the described _ECOMOD Methods_. Probably, in practice, a project will typically use a custom set of methods in a different order, especially with lots of iterations and loops.

Since examples are always helpful for a better understanding, some [examples](examples.md) demonstrates the application of ECOMOD in practice. An overview about the [**ECOMOD Profile**](quick-reference.md) is also available as well as a [glossary](glossary.md).


---
#### _Notes:_

_[1] Considering only two levels when developing embedded and IoT systems is not the whole truth. Actually, the second level should be called the "technology level", which - analogous to software - also describes requirements and solutions for the hardware and any other technology involved in the project (such as mechanical, electrical or manual subsystems)._

_[2] In particular, the logical order and the chronological order must not be confused! The logical order does not imply a waterfall process. The application of ECOMOD is independent of a waterfall or agile approach._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
