---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

I'm a fourth-year Ph.D. student in Software Engineering at Institute for Software Research at Carnegie Mellon University. I work with Dr. Eunsuk Kang and Dr. David Garlan. My research mainly focuses on **software architecture**, **software quality**, and **formal methods**. My goal is to develop methodologies and tools to help developers to systematically design and build software systems that are **safe** and **robust**.

[[CV](/statics/Changjian-Zhang-CV.pdf)][[Google Scholar](https://scholar.google.com/citations?hl=en&user=ZCz6P_QAAAAJ)][[GitHub](https://github.com/SteveZhangBit)]

***I'm actively looking for a summer internship opportunity!!!***

## Projects

- Software Robustness: Engineers and developers always want to make their software systems robust. However, what we really mean about "robustness" is often vague. IEEE defines robustness as the ability of a software system to function correctly under uncertainties in the inputs, while it is unclear what the uncertainties are and how we define the correctness of the function. In this project, we aim at developing a general formal framework for defining and reasoning software robustness. Under this framework, we have developed a [tool](https://doi.org/10.1145/3368089.3409753) for computing software robustness for transition systems, and a tool for automatically robustifying a (transition) system (under review). Currently, we are also working on reasoing robustness for systems with ML components.

- [AlloyMax](https://doi.org/10.1145/3468264.3468587): [Alloy](http://alloytools.org/) is a first-order modeling language developed by MIT with SAT as its back-end solver. It is widely used in design verification and model generation. Because of the nature of SAT, using Alloy for model generation generates an arbitrary model that satisfies the constraints, while which may not be useful. AlloyMax extends Alloy with MaxSAT solving that enables it to synthesize optimal models, which not only satisfy the constraints but also optimize for certain requirements. It brings optimization capability to Alloy and allows Alloy to solver a wider range of problems.

## Selected Publications

- Robustification of Behavioral Designs against Environmental Deviations. \
  **Changjian Zhang**, Tarang Saluja, Romulo Meira Goes, Matthew Bolton, David Garlan, and Eunsuk Kang. (ICSE 2023).

- [**AlloyMax: bringing maximum satisfaction to relational specifications. (Distinguished Paper Award)**](https://doi.org/10.1145/3468264.3468587) \
  **Changjian Zhang**, Ryan Wagner, Pedro Orvalho, David Garlan, Vasco Manquinho, Ruben Martins, and Eunsuk Kang. 2021. In Proceedings of the 29th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2021). Association for Computing Machinery, New York, NY, USA, 155–167.

- [**A behavioral notion of robustness for software systems.**](https://doi.org/10.1145/3368089.3409753) \
  **Changjian Zhang**, David Garlan, and Eunsuk Kang. 2020. In Proceedings of the 28th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2020). Association for Computing Machinery, New York, NY, USA, 1–12.

## Other Work

- [**Safe Run-time Reconfiguration for Event-driven Systems with Pub/Sub in ROS.**](http://acme.able.cs.cmu.edu/pubs/uploads/pdf/ROSReconfig-submitted.pdf) \
  **Changjian Zhang**, Eunsuk Kang, David Garlan. 2018.

## Bio

I received my Bachelor degree in Computer Science at Beijing Institute of Technology. Then, I received a Master degree in Software Engineering at Carnegie Mellon University. Now, I'm a fourth-year Ph.D. student at CMU, working with [Dr. Eunsuk Kang](https://eskang.github.io/) and [Dr. David Garlan](https://www.cs.cmu.edu/~garlan/).

