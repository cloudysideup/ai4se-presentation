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

# AI for Software Engineering
## A More Collaborative Toolset

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---

# Difficult Tasks In Uncertain Times

- Creating business logic written in a programming language along with the
  tests to verify that code and the process of how these items are written

- As large language models have become more specialised and geared towards code
  creation, practitioners have embraced using it in limited purposes

- researchers are evaluating what role artificial intelligence will have in multiple software engineering domains over the next several years.

---
layout: image-right
image: /serc-roadmap.png
backgroundSize: 30em 50%
---
# Thesis Statement

- Artificial intelligence will be used by
  - engineers
  - architects
  - technical leads
  - managers

- Augmentation and coaching within the domains and common processes

---
layout: cover
background: https://cover.sli.dev
---

# Gathering Software Requirements

---
layout: image-right
image: /software-requirements-types.jpg
backgroundSize: 30em 50%
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
  - "focus on specific tasks such as design pattern identification,...requirement classification, extraction, traceability, validation, generation and completeness enhancement" (M. Pezze et al, p10)

- Recommend design decisions based on requirements
  - "method based on [AI] models was presented to classify software requirements automatically...results showed they can successfully classify the requirements" (Khayashi, pp7-8)
  - "suggest requirements prioritization by analyzing technical dependencies, project goals, and historical data...have domain experts validate the results" (Arora, p8)

---
layout: cover
background: https://cover.sli.dev
---
# Project Planning and oversight

---
layout: image-right
image: /scrum.png
backgroundSize: 30em 50%
---
# Understanding The Work

- frameworks manage:
  - ideation
  - development
  - testing
  - security
  - delivery

---
layout: image-right
image: /School-Robot-GIF-by-BrainPOP.gif
backgroundSize: 30em 50%
---
# How will AI help?

- create the content for
  - ideation
  - stories for developer work
  - testing

- “AI4SE solutions can transfer information and insights from one micro-task to
others” (Lo, p11) 
  - create a project roadmap with verification by project managers and technical leads
  - accelerate project management
  - allow software development teams to think holistically about projects

---
layout: cover
background: https://cover.sli.dev
---
# Software Design and Architecture

---
layout: image-right
image: /sayonetech-software-architecture-patterns.jpg
backgroundSize: 30em 50%
---
# Organizing Code and Development

- create functionality boundaries in your system
- requirements gathered translated into
  - system structure
  - components
  - integrations

---
layout: image-right
image: /Sketch-Ux-GIF-by-Perrine-Land.gif
backgroundSize: 30em 50%
---
# What Will Design and Architecture Look Like?

- AI translates requirements into blueprints of system and project design
  - "hybrid AI systems that excel in tasks requiring [logic] reasoning and pattern recognition" (Burgueno et al, p10)
  - "Feature Maps (FMs)...computed via Feature-Role normalization (FRN) and used for design pattern detection" (Thaller, p8)
  - "[Architecturally Significant Requirements]...refined via human-bot dialog...synthesized into an architectural specification" (Ahmad, p282)

- Architects and project managers validate the design patterns/specifications


---
layout: cover
background: https://cover.sli.dev
---
# Source Code Generation (Programming)

---
layout: image-right
image: /Lone-programmer-workflow.png
backgroundSize: 30em 50%
---
# What does Programming look like?

- writing instructions that a computer can understand and execute
- software developer as creator

---
layout: image-right
image: /curators-at-the-national-gallery.jpg
backgroundSize: 30em 50%
---
# Software Developer as Curator

- Increasing impact of work
  - collaborator/pair programming or automatic programming with validation
  - "" (Liu, p23)
  - "" (Pezze, p15,26)

- Collaboration in repairing code
  - "" (Liu, p20)

---
layout: cover
background: https://cover.sli.dev
---
# Software Testing

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# How do we test now?

1. ensure software functions correctly
  - write the code then write the test code
2. finding and documenting bugs and other issues before the product is released

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# What can AI do for Testing?

- draft the test code while drafting the system code 
  - unit tests
  - integration tests
  - e2e tests

- vulnerability detection

- draft test cases and test suites
  - Pezze p10-11
  - Roziere, p14

---
layout: cover
background: https://cover.sli.dev
---
# IT Operations

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# What are IT Operations?

- Background
  - the management and maintenance of IT infrastructure
  - ensuring systems run reliably and securely after the software is built

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# Pairing for Patching

- Partner in maintenance of systems that support systems
  - Pezze p11, p31
  - Lo ref 101, 118-120

---
layout: cover
background: https://cover.sli.dev
---
# Program Analysis

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# What is Program Analysis?

- Static Code Analysis
- Static Application Security Testing
- Dynamic Application Security Testing

---
layout: image-right
image: /devops.png
backgroundSize: 30em 50%
---
# Integration of Analysis into Process

- Agentic AI invocation of tools
  - Pezze, p27
  - Roziere

---

# References

Ahmad, Aakash, et al. "Towards human-bot collaborative software architecting with chatgpt." Proceedings of the 27th international conference on evaluation and assessment in software engineering. 2023.

Arora, Chetan, John Grundy, and Mohamed Abdelrazek. "Advancing requirements engineering through generative ai: Assessing the role of llms." Generative AI for Effective Software Development. Cham: Springer Nature Switzerland, 2024. 129-148.

Burgueño, Lola, et al. "Automation in Model-Driven Engineering: A look back, and ahead." ACM Transactions on Software Engineering and Methodology 34.5 (2025): 1-25.

Khayashi, Fatemeh, et al. "Deep learning methods for software requirement classification: A performance study on the pure dataset." arXiv preprint arXiv:2211.05286 (2022).

---

# References (continued)

Liu, Yue, et al. "Refining chatgpt-generated code: Characterizing and mitigating code quality issues." ACM Transactions on Software Engineering and Methodology 33.5 (2024): 1-26.

Lo, David. "Trustworthy and Synergistic Artificial Intelligence for Software Engineering: Vision
and Roadmaps. CoRR abs/2309.04142 (2023)." arXiv preprint arXiv:2309.04142 10 (2023).

Pezzè, Mauro, et al. "A 2030 Roadmap for Software Engineering." ACM Transactions on
Software Engineering and Methodology 34.5 (2025): 1-55.

---

# References (continued)

Roziere, Baptiste, et al. "Leveraging automated unit tests for unsupervised code translation." arXiv preprint arXiv:2110.06773 (2021).

Stutz, Kevin, Kurt Sandkuhl, and Michael Möhring. "Empirical Insights into the Usage of
Generative AI in Software Engineering." International Conference on Business Informatics
Research. Cham: Springer Nature Switzerland, 2025.

Thaller, Hannes, Lukas Linsbauer, and Alexander Egyed. "Feature maps: A comprehensible software representation for design pattern detection." 2019 IEEE 26th international conference on software analysis, evolution and reengineering (SANER). IEEE, 2019.

