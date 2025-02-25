# Curated list of learning resources for DS & MLE
(Working in progress)

a curated list of resources for aspiring data scientists and machine learning engineers

## Table of Contents
- [Curated list of learning resources for DS \& MLE](#curated-list-of-learning-resources-for-ds--mle)
  - [Table of Contents](#table-of-contents)
    - [Introduction](#introduction)
    - [Getting Started](#getting-started)
      - [Python Version Management](#python-version-management)
      - [Dependency Management](#dependency-management)
      - [Project Templates](#project-templates)
    - [Data Structures and Algorithms Resources](#data-structures-and-algorithms-resources)
      - [Books and Courses](#books-and-courses)
      - [Practice Platforms](#practice-platforms)
      - [Applications in DSML](#applications-in-dsml)
### Introduction 
**What It Takes to Become a Data Scientist or Machine Learning Engineer**

Becoming a Data Scientist or Machine Learning Engineer requires a <u>blend of technical skills, analytical thinking, and domain expertise</u>. While the two roles overlap in many ways, they serve distinct purposes within the data ecosystem.

Data Scientists focus on extracting actionable insights from data to drive business decisions. They apply statistical analysis, data visualization, and predictive modeling to uncover patterns in complex datasets. Proficiency in Python and other programming tools is essential, complemented by strong foundations in statistics, mathematics, and domain expertise. Today's Data Scientists increasingly leverage Large Language Models (LLMs) as analytical tools—using them for text analysis, automated reporting, and data exploration through natural language interfaces. Effective communication skills are crucial, as Data Scientists routinely translate technical findings into business recommendations for non-technical stakeholders. This communication ability is frequently assessed during interviews, where candidates may be asked to explain complex concepts in accessible terms.


On the other hand, Machine Learning Engineers specialize in designing and deploying scalable machine learning systems. They build robust pipelines that automate data processing and model training, ensuring models perform efficiently in production environments. This role demands strong software engineering skills, system architecture design, proficiency in frameworks like TensorFlow or PyTorch, and a deep understanding of algorithms and data structures. MLEs make critical architectural decisions that balance performance, scalability, cost, and maintainability across the entire ML system lifecycle. Increasingly, expertise with Large Language Models (LLMs) has become essential – including prompt engineering, fine-tuning techniques, RAG (Retrieval-Augmented Generation) implementation, and optimizing LLM deployment for cost and performance. MLEs must stay current with rapidly evolving LLM capabilities and best practices for their responsible integration into production systems.


A **T-shaped skillset** combining deep expertise in a core area with broad knowledge across related domains provides the optimal foundation for success in both data science and machine learning engineering. 

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