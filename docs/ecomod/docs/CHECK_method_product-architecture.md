# SYSMOD Method: Specialize Product Architecture

#### ---ORIGINAL---begin---
Model a concrete specification of the Physical Architecture.
#### ---ORIGINAL---end---

![Activity Model](images/en-iotpml-method-product-architecture.png)


## Purpose

#### ---ORIGINAL---begin---
The Product Architecture is the most concrete specification of the architecture of the system in the system model.
#### ---ORIGINAL---end---


## Description

#### ---ORIGINAL---begin---
The Product Architecture specializes the technical concepts and principles of the Logical Architecture. For example, a electric motor in the Logical Architecture is specialized by a electric motor XYZ in the Product Architecture including a specification of the vendor, the size, the pwoer consumptation, the mechanical, electrical and software interfaces, and other features of interest.

The Product Architecture is a special Logical Architecture. If strongly coupled the Product Architecture is a specialization of the Logical Architecture. If loosely coupled there are only traceability relationships between both architectures.

In practice you often do not have strictly separated Logical Architectures and Product Architectures. It is one single Physical Architecture that is a mix of both kinds. Some parts cover technical concepts, other parts concrete specifications. The discriminator between the architecture kinds is the abstraction. You cannot measure abstraction and therefore you cannot clearly define the border between the Logical Architecture and the Product Architecture.
#### ---ORIGINAL---end---


## Inputs

+ [Logical Architecture](product_logical-architecture.md)


## Outputs

+ [Product Architecture](product_product-architecture.md)


## Tasks

+ [Model xxx](task_xxx.md)


## Further Information

### Examples

#### Example Product Architecture

![Example for Product Architecture](images/en-sysmod-example-productarchitecture-modelview.png)

### Recommendations & Tips

_None._

---
_Quick Navigation:_ | [Introduction](index.md) | [Processes](processes.md) | [Methods](methods.md) | [Products](products.md) | [Examples](examples.md) | [Reference](quick-reference.md) | [Glossary](glossary.md) |
