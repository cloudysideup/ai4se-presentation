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

# Outline

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

- Tie to source
  1. Lo ref 150-151

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

- Tie to source
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

- Background – writing instructions that a computer can understand and execute

---

# From Creator to Curator

- Solution 2. collaborator/pair programming 3. Automatic programming (Pezze, p26) 4. Completion of code 5. Refactoring
- Tie to source
  1. Pezze p10 2.1.3
  2. Pezze p15

---
layout: cover
image: https://cover.sli.dev
---
# Software Testing

---

# How do we test now?

1. ensure software functions correctly
2. finding and documenting bugs and other issues before the product is released

---

# What can AI do for Testing?

1. QA
2. vuln detection
3. test case
4. e2e
5. unit

- Tie to source
  1. Pezze p10-11 2.1.3
  2. Lo ref 98

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

# What will IT Operations look like?

- Solution (Pezze, p31)
  1. patching, other security
  2. Lo ref 101, 118-120

- Tie to source
  1. Pezze p11 2.1.3

---
layout: cover
image: https://cover.sli.dev
---
# Program Analysis

---

# What is Program Analysis?

- Background
  1. SCA/DAST/SAST

---

# How will AI help?

- Solution
  1. Agentic AI invocation of tools (Pezze, p27)
- Tie to Source
  1. Lo ref 47,107-111,121

