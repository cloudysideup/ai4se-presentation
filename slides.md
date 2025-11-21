---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Artificial Intelligence for Software Engineering
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

# Artificial Intelligence for Software Engineering
## A More Collaborative Toolset

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

---

# Intro

- Creating business logic written in a programming language along with the
  tests to verify that code and the process of how these items are written have proven to be a
  more difficult task.
- As AI models have become more specialised and geared towards code
  creation, practitioners have embraced using it in limited purposes and researchers are
  evaluating what role artificial intelligence will have in multiple software engineering domains
  over the next several years.

---

# Thesis Statement

- Based on their research and how practitioners are currently using
  it, artificial intelligence will be used by engineers, leads and managers for augmentation and
  coaching within the domains and common processes of software engineering.

---
layout: cover
---

# Gathering Software Requirements

---

# What Do We Require?

- Functional Requirements
  - What the software needs to do

- Non-Functional Requirements
  - How the software performs a task

- Domain Requirements
  - Rules or standards
  - specific to domain or industry the software operates in

---

# How will AI help?

- Parse Functional, Non-Functional and Domain Requirements
- Recommend design decisions based on requirements
- Sources
  1. Pezze, p10, 2.1.3
  2. Pezze ref 92
  3. Stutz ref 20

---
layout: cover
image: cover.sli.dev
---
# Project Planning and oversight

---

# Understanding The Work

- frameworks manage:
  - ideation
  - development
  - testing
  - security
  - delivery

---

# How will AI help?

- create the content for
  - ideation
  - stories for developer work
  - testing. 
  - “AI4SE solutions can transfer information and insights from one micro-task to
others” (Lo, p11). 
  - insights integrated to create a roadmap for a project. 
  While project managers and technical leads would need to verify what is
created, 
  would augment and accelerate project management and 
  allow software development teams to think holistically about their projects

- Sources
  1. Lo ref 151
  2. Lo ref 150?

---
layout: cover
image: https://cover.sli.dev
---
# Software Design and Architecture

---

# Organizing Code and Development

- create functionality boundaries in your system
- requirements gathered translated into
  - system structure
  - components
  - integrations

---

# What will Software design and Architecture look like?


- validating the system design pattern artificial intelligence identifies in the requirements.
- “deep learning techniques” identified by research...[focused] on...design pattern identification, user
interface detection, traceability, validation” (M. Pezze et al, p10).
- Once requirements are
translated into blueprint of system and project design, code can be created.

- Sources
  1. Pezze p10, 2.1.3
  2. Pezze ref 25 (models), 190
  3. Lo ref 97

---
layout: cover
image: https://cover.sli.dev
---
# Source Code Generation (Programming)

---

# What does Programming look like?

- writing instructions that a computer can understand and execute
- software developer as creator

---

# Software Developer as Curator

- Increasing impact of work
- collaborator/pair programming
- Automatic programming 
- Completion of code
- Refactoring
- Sources
  1. Pezze p10 2.1.3
  2. Pezze p15
  3. Pezze p26

---
layout: cover
image: https://cover.sli.dev
---
# Software Testing

---

# How do we test now?

1. ensure software functions correctly
  - write the code then write the test code
2. finding and documenting bugs and other issues before the product is released

---

# What can AI do for Testing?

- draft the test code while drafting the system code 
  - unit tests
  - integration tests
  - e2e tests
- vulnerability detection
- draft test cases and test suites

- Sources
  1. Pezze p10-11 2.1.3
  2. Lo ref 98?
  3. Lo ref 111

---
layout: cover
image: https://cover.sli.dev
---
# IT Operations

---

# What are IT Operations?

- Background
  1. the management and maintenance of IT infrastructure
  2. ensuring systems run reliably and securely after the software is built

---

# Pairing for Patching

- Partner in maintenance of systems that support systems
  1. security

- Sources
  1. Pezze p11 2.1.3
  2. Pezze p31
  3. Lo ref 101, 118-120

---
layout: cover
image: https://cover.sli.dev
---
# Program Analysis

---

# What is Program Analysis?

- Static Code Analysis
- Static Application Security Testing
- Dynamic Application Security Testing

---

# Integration of Analysis into Process

- Agentic AI invocation of tools
- Sources
  1. Pezze, p27
  1. Lo ref 47,107-111,121

---
layout: cover
image: https://cover.sli.dev
---
# References
---

Ahmad, Aakash, et al. "Towards human-bot collaborative software architecting with chatgpt." Proceedings of the 27th international conference on evaluation and assessment in software engineering. 2023.

Arora, Chetan, John Grundy, and Mohamed Abdelrazek. "Advancing requirements engineering through generative ai: Assessing the role of llms." Generative AI for Effective Software Development. Cham: Springer Nature Switzerland, 2024. 129-148.

Burgueño, Lola, et al. "Automation in Model-Driven Engineering: A look back, and ahead." ACM Transactions on Software Engineering and Methodology 34.5 (2025): 1-25.

Khayashi, Fatemeh, et al. "Deep learning methods for software requirement classification: A performance study on the pure dataset." arXiv preprint arXiv:2211.05286 (2022).

---
Liu, Yue, et al. "Refining chatgpt-generated code: Characterizing and mitigating code quality issues." ACM Transactions on Software Engineering and Methodology 33.5 (2024): 1-26.

Lo, David. "Trustworthy and Synergistic Artificial Intelligence for Software Engineering: Vision
and Roadmaps. CoRR abs/2309.04142 (2023)." arXiv preprint arXiv:2309.04142 10 (2023).

Niu, Changan, et al. "Crosscodebench: Benchmarking cross-task generalization of source code models." 2023 IEEE/ACM 45th International Conference on Software Engineering (ICSE). IEEE, 2023.

Peng, Yun, et al. "Generative type inference for python." 2023 38th IEEE/ACM International Conference on Automated Software Engineering (ASE). IEEE, 2023.

---

Pezzè, Mauro, et al. "A 2030 Roadmap for Software Engineering." ACM Transactions on
Software Engineering and Methodology 34.5 (2025): 1-55.

Roziere, Baptiste, et al. "Leveraging automated unit tests for unsupervised code translation." arXiv preprint arXiv:2110.06773 (2021).

Stutz, Kevin, Kurt Sandkuhl, and Michael Möhring. "Empirical Insights into the Usage of
Generative AI in Software Engineering." International Conference on Business Informatics
Research. Cham: Springer Nature Switzerland, 2025.

Thaller, Hannes, Lukas Linsbauer, and Alexander Egyed. "Feature maps: A comprehensible software representation for design pattern detection." 2019 IEEE 26th international conference on software analysis, evolution and reengineering (SANER). IEEE, 2019.

