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
addons:
- slidev-addon-citations

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

- Researchers are evaluating what role artificial intelligence will have in multiple software engineering domains over the next several years.

---
layout: image-right
image: /serc-roadmap.png
backgroundSize: 30em 50%
---
# What Will Software Engineering Look Like

- Artificial intelligence will be used by
  - Engineers
  - Architects
  - Technical leads
  - Managers

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
  - Specific to domain or industry the software operates in

---

# How will AI help?

- Parse Functional, Non-Functional and Domain Requirements
  - "focus on specific tasks such as design pattern identification,...requirement classification, extraction, traceability, validation, generation and completeness enhancement" (M. Pezze et al p10)

- Recommend design decisions based on requirements
  - "method based on [AI] models was presented to classify software requirements automatically...results showed they can successfully classify the requirements" (Khayashi pp7-8)
  - "suggest requirements prioritization by analyzing technical dependencies, project goals, and historical data...have domain experts validate the results" (Arora p8)

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

- Frameworks manage:
  - Ideation
  - Development
  - Testing
  - Security
  - Delivery

---
layout: image-right
image: /School-Robot-GIF-by-BrainPOP.gif
backgroundSize: 30em 50%
---
# How Will AI Help?

- Create the content for
  - Ideation
  - Stories for developer work
  - Testing

- “AI4SE solutions can transfer information and insights from one micro-task to
others” (Lo p11) 
  - Create a project roadmap with verification by project managers and technical leads
  - Accelerate project management
  - Allow software development teams to think holistically about projects

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

- Create functionality boundaries in your system
- Requirements gathered translated into
  - System structure
  - Components
  - Integrations

---
layout: image-right
image: /Sketch-Ux-GIF-by-Perrine-Land.gif
backgroundSize: 30em 50%
---
# What Will Design and Architecture Look Like?

- AI translates requirements into blueprints of system and project design
  - "hybrid AI systems that excel in tasks requiring [logic] reasoning and pattern recognition" (Burgueno et al p10)
  - "Feature Maps (FMs)...computed via Feature-Role normalization (FRN) and used for design pattern detection" (Thaller p8)
  - "[Architecturally Significant Requirements]...refined via human-bot dialog...synthesized into an architectural specification" (Ahmad p282)

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
# What Does Programming Look Like?

- Writing instructions that a computer can understand and execute
- Software developer as creator

---
layout: image-right
image: /curators-at-the-national-gallery.jpg
backgroundSize: 30em 50%
---
# Software Developer As Creator and Curator

- Increasing impact of work
  - collaborator/pair programming or automatic programming with validation
  - "trustworthy integration of automatically generated code" (Pezze et al p26)

- Collaboration in repairing code
  - "effective, particularly when guided by detailed feedback" (Liu et al p20)

---
layout: cover
background: https://cover.sli.dev
---
# Software Testing

---
layout: image-right
image: /software-testing.jpg
backgroundSize: 30em 50%
---
# How Do We Test Now?

- Ensure software functions correctly
  - Write the code then write the test code
- Finding and documenting bugs and other issues before the product is released

---
layout: image-right
image: /time-writes-GIF.gif
backgroundSize: 30em 50%
---
# What Can AI Do For Testing?

- Draft the test code while drafting the system code 
  - Unit tests (Roziere et al)
  - Integration tests (of system components)
  - End-to-end (e2e) tests

- Draft test cases and test suites
  - "use of large language models to generate test cases, showing promising results" (Pezze et al p10)

---
layout: cover
background: https://cover.sli.dev
---
# IT Operations

---
layout: image-right
image: /ITOM-Processes_480x480.webp
backgroundSize: 30em 50%
---
# What Are IT Operations?

- The management and maintenance of IT infrastructure
- Ensuring systems run reliably and securely after the software is built

---
layout: image-right
image: /highlight-ferrari-GIF.gif
backgroundSize: 30em 50%
---
# Pairing for Patching

- "Artifical intelligence powered tools to protect software ecosystems in production under human control" (Pezze et al p31)
  - Vulnerability detection
  - Fix Localization & Patching
  - Patch Ranking

---
layout: cover
background: https://cover.sli.dev
---
# Program Analysis

---
layout: image-right
image: /tn-images-7-1057734412.png
backgroundSize: 30em 50%
---
# What is Program Analysis?

- Static Code Analysis
- Static Application Security Testing
- Dynamic Application Security Testing

---
layout: image-right
image: /Infographic-CT360-Secure-Code-process.jpg
backgroundSize: 30em 50%
---
# Integration of Analysis Into Process

- Agentic AI using tools
  - "large language models can invoke...program analysis tools, to autonomously complete programming tasks" (Pezze et al p27)

---

# References

Ahmad, Aakash, et al. "Towards human-bot collaborative software architecting<br>
&nbsp;&nbsp;&nbsp;&nbsp;with chatgpt." Proceedings of the 27th international conference on<br>
&nbsp;&nbsp;&nbsp;&nbsp;evaluation and assessment in software engineering. 2023.

Arora, Chetan, John Grundy, and Mohamed Abdelrazek. "Advancing requirements<br>
&nbsp;&nbsp;&nbsp;&nbsp;engineering through generative ai: Assessing the role of llms." Generative<br>
&nbsp;&nbsp;&nbsp;&nbsp;AI for Effective Software Development. Cham: Springer Nature Switzerland,<br>
&nbsp;&nbsp;&nbsp;&nbsp;2024 129-148.

Burgueño, Lola, et al. "Automation in Model-Driven Engineering: A look back,<br>
&nbsp;&nbsp;&nbsp;&nbsp;and ahead." ACM Transactions on Software Engineering and Methodology<br>
&nbsp;&nbsp;&nbsp;&nbsp;34.5 (2025): 1-25.

Khayashi, Fatemeh, et al. "Deep learning methods for software requirement<br>
&nbsp;&nbsp;&nbsp;&nbsp;classification: A performance study on the pure dataset." arXiv preprint<br>
&nbsp;&nbsp;&nbsp;&nbsp;arXiv:2211.05286 (2022).

---

# References (continued)

Liu, Yue, et al. "Refining chatgpt-generated code: Characterizing and mitigating<br>
&nbsp;&nbsp;&nbsp;&nbsp;code quality issues." ACM Transactions on Software Engineering and<br>
&nbsp;&nbsp;&nbsp;&nbsp;Methodology 33.5 (2024): 1-26.

Lo, David. "Trustworthy and Synergistic Artificial Intelligence for Software<br>
&nbsp;&nbsp;&nbsp;&nbsp;Engineering: Vision and Roadmaps. CoRR abs/2309.04142 (2023)." arXiv<br>
&nbsp;&nbsp;&nbsp;&nbsp;preprint arXiv:2309.04142 10 (2023).

Pezzè, Mauro, et al. "A 2030 Roadmap for Software Engineering." ACM Transactions<br>
&nbsp;&nbsp;&nbsp;&nbsp;on Software Engineering and Methodology 34.5 (2025): 1-55.

---

# References (continued)

Roziere, Baptiste, et al. "Leveraging automated unit tests for unsupervised code<br>
&nbsp;&nbsp;&nbsp;&nbsp;translation." arXiv preprint arXiv:2110.06773 (2021).

Stutz, Kevin, Kurt Sandkuhl, and Michael Möhring. "Empirical Insights into the<br>
&nbsp;&nbsp;&nbsp;&nbsp;Usage of Generative AI in Software Engineering." International Conference on<br>
&nbsp;&nbsp;&nbsp;&nbsp;Business Informatics Research. Cham: Springer Nature Switzerland, 2025.

Thaller, Hannes, Lukas Linsbauer, and Alexander Egyed. "Feature maps: A comprehensible<br>
&nbsp;&nbsp;&nbsp;&nbsp;software representation for design pattern detection." 2019 IEEE 26th<br>
&nbsp;&nbsp;&nbsp;&nbsp;international conference on software analysis, evolution and reengineering<br>
&nbsp;&nbsp;&nbsp;&nbsp;(SANER). IEEE, 2019.

