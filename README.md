<!-- omit in toc -->
# Curated list of learning resources for DS & MLE
(Working in progress)

a curated list of resources for aspiring data scientists and machine learning engineers

<!-- omit in toc -->
## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Python Version Management](#python-version-management)
  - [Dependency Management](#dependency-management)
  - [Project Templates](#project-templates)
- [Data Structures and Algorithms Resources](#data-structures-and-algorithms-resources)
  - [Books and Courses](#books-and-courses)
  - [Practice Platforms](#practice-platforms)
  - [Applications in DSML](#applications-in-dsml)
- [Software Engineering Resources](#software-engineering-resources)
- [Data Engineering Resources](#data-engineering-resources)
  - [Repositories](#repositories)
  - [Books](#books)
### Introduction 
**<u>What It Takes to Become a Data Scientist or Machine Learning Engineer</u>**

Becoming a Data Scientist or Machine Learning Engineer requires a <u>blend of technical skills, analytical thinking, and domain expertise</u>. While the two roles overlap in many ways, they serve distinct purposes within the data ecosystem.

Data Scientists focus on extracting actionable insights from data to drive business decisions. They apply statistical analysis, data visualization, and predictive modeling to uncover patterns in complex datasets. Proficiency in Python and other programming tools is essential, complemented by strong foundations in statistics, mathematics, and domain expertise. Today's Data Scientists increasingly leverage Large Language Models (LLMs) as analytical tools—using them for text analysis, automated reporting, and data exploration through natural language interfaces. Effective communication skills are crucial, as Data Scientists routinely translate technical findings into business recommendations for non-technical stakeholders. This communication ability is frequently assessed during interviews, where candidates may be asked to explain complex concepts in accessible terms.


On the other hand, Machine Learning Engineers specialize in designing and deploying scalable machine learning systems. They build robust pipelines that automate data processing and model training, ensuring models perform efficiently in production environments. This role demands strong software engineering skills, system architecture design, proficiency in frameworks like TensorFlow or PyTorch, and a deep understanding of algorithms and data structures. MLEs make critical architectural decisions that balance performance, scalability, cost, and maintainability across the entire ML system lifecycle. Increasingly, expertise with Large Language Models (LLMs) has become essential – including prompt engineering, fine-tuning techniques, RAG (Retrieval-Augmented Generation) implementation, and optimizing LLM deployment for cost and performance. MLEs must stay current with rapidly evolving LLM capabilities and best practices for their responsible integration into production systems.


A **T-shaped skillset** combining deep expertise in a core area with broad knowledge across related domains provides the optimal foundation for success in both data science and machine learning engineering. 

---

### Getting Started

#### Python Version Management
Pyenv is an useful Python version management tool that allows you to install and switch between multiple Python versions on the same system without conflicts. It is excellent for project specific environments and backward compatibility support

<br>

[https://github.com/pyenv/pyenv](https://github.com/pyenv/pyenv)

#### Dependency Management
Effective dependency management is critical in data science and ML projects to ensure <u>**reproducibility**</u>, prevent conflicts, and maintain consistent environments across development and production.

Both `poetry` and `uv` are good choices that attempt to address pip's limitations around dependency resolution, environment isolation and performance (`uv` is written in rust and is blazing fast)

<br>

[https://python-poetry.org/](https://python-poetry.org/)


[https://github.com/astral-sh/uv](https://github.com/astral-sh/uv)

#### Project Templates
Standardized project templates are essential for maintaining consistency and best practices across projects. Cookiecutter is the leading solution for project templates for Python-based data science and ML workflows. Initial investment in setting up appropriate templates may help to reduce technical debt over time.

Potential drawbacks:
- Potential overhead (structures that may be excessive for simple projects)
- Rigidity
- Maintenance requirements (templates need regular updates as best practices evolve over time)

[https://github.com/cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter)

A template that I personally like to use:
[https://github.com/py-pkgs/py-pkgs-cookiecutter](https://github.com/py-pkgs/py-pkgs-cookiecutter)

---

### Data Structures and Algorithms Resources

#### Books and Courses
- [Hello Algo](https://www.hello-algo.com/)
- [NeetCode Course](https://neetcode.io/courses)
- *Data Structures and Algorithms in Python* by Michael T. Goodrich, Roberto Tamassia, and Michael H. Goldwasser (Wiley, 2013) - [Amazon](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275)

#### Practice Platforms
- [https://leetcode.com/](https://leetcode.com/)
- [https://neetcode.io/practice](https://neetcode.io/practice)
- [https://www.hackerrank.com/](https://www.hackerrank.com/)
- [https://www.deep-ml.com/problems](https://www.deep-ml.com/problems) (The ML equivalent of LeetCode)
- [https://www.codewars.com](https://www.codewars.com/dashboard) (More suitable for beginners to pick up new languages)

#### Applications in DSML
- **Graph Structures:** LangGraph leverages Directed Acyclic Graphs (DAGs) to orchestrate complex agent workflows and reasoning paths
- **Network Algorithms:** Recommender systems employ graph-based collaborative filtering to model user-item interactions and social connections
- **Optimization Methods:** Feature selection often relies on greedy algorithms to efficiently identify the most predictive variables
- **Dynamic Programming:** Sequence analysis techniques like Dynamic Time Warping use DP to find optimal alignments between temporal sequences
- **Tree Data Structures:** Decision trees and ensemble methods (Random Forests, XGBoost) recursively partition data using binary tree structures
- **Hash Tables:** Vectorization and embedding lookups use efficient hashing for rapid data retrieval in high-dimensional spaces
- **Queue Processing:** Distributed ML systems implement priority queues for task scheduling and workload management

Remember: Those LeetCode grinding sessions weren't just for passing interviews—they're the algorithms secretly powering your ML models too! 😉

---

### Software Engineering Resources
- *Clean Code: A Handbook of Agile Software Craftsmanship* by Robert C. Martin (Prentice Hall, 2008) - [Amazon](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- *Software Engineering for Data Scientists* by Jacqueline Nolis & Emily Robinson (O'Reilly, 2022) - [Amazon](https://www.amazon.com/Software-Engineering-Data-Scientists-applications/dp/1492080799)
- *Fluent Python* by Luciano Ramalho (O'Reilly, 2022) - [Amazon](https://www.amazon.com/Fluent-Python-Concise-Effective-Programming/dp/1492056359)
- *Robust Python* by Patrick Viafore (O'Reilly, 2021) - [Amazon](https://www.amazon.com/Robust-Python-Patrick-Viafore/dp/1098100662)
- *Clean Code in Python* by Mariano Anaya (Packt, 2021) - [Amazon](https://www.amazon.com/Clean-Code-Python-maintainable-efficient/dp/1800560214)
- *Mastering Python Design Patterns* by Kamon Ayeva & Sakis Kasampalis (Packt, 2018) - [Amazon](https://www.amazon.com/Mastering-Python-Design-Patterns-problems/dp/1788837484)
- *Think Python* by Allen B. Downey (O'Reilly, 2015) - [Amazon](https://www.amazon.com/Think-Python-Allen-B-Downey/dp/1491939362)
- *The Pragmatic Programmer* by David Thomas & Andrew Hunt (Addison-Wesley, 2019) - [Amazon](https://www.amazon.com/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052)
- *Refactoring: Improving the Design of Existing Code* by Martin Fowler (Addison-Wesley, 2018) - [Amazon](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599)
- *Crafting Test-Driven Software with Python* by Alessandro Molina (Packt, 2021) - [Amazon](https://www.amazon.com/Crafting-Test-Driven-Software-Python-applications/dp/1838642625)
- [https://pytest-with-eric.com/](https://pytest-with-eric.com/)
- [https://refactoring.guru/](https://refactoring.guru/)

---

### Data Engineering Resources

#### Repositories
- [https://github.com/DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook)
- [https://github.com/DataTalksClub/data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp)

#### Books
- *Fundamentals of Data Engineering* by Joe Reis & Matt Housley (O'Reilly, 2022) - [Amazon](https://www.amazon.com/Fundamentals-Data-Engineering-Robust-Systems/dp/1098108302)
- *Data Engineering Design Patterns* by Joe Reis & Matt Housley (O'Reilly, 2023) - [Amazon](https://www.amazon.com/Data-Engineering-Design-Patterns-Grokking/dp/1633439216)
- *Streaming Systems* by Tyler Akidau, Slava Chernyak & Reuven Lax (O'Reilly, 2018) - [Amazon](https://www.amazon.com/Streaming-Systems-Where-Large-Scale-Processing/dp/1491983876)
- *Designing Data-Intensive Applications* by Martin Kleppmann (O'Reilly, 2017) - [Amazon](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
- *Financial Data Engineering* by Harvinder Atwal (Packt, 2023) - [Amazon](https://www.amazon.com/Financial-Data-Engineering-manipulate-transformation/dp/1803240997)

**Note:** Focus on mastering fundamental data engineering concepts and skills before specializing in cloud-specific implementations. This foundational knowledge provides the transferable expertise necessary to quickly adapt to any platform-specific requirements in professional settings.