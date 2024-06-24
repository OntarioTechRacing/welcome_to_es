# welcome_to_es

---

<details markdown="1">
  <summary>Table of Contents</summary>

- [1 Introduction](#1-introduction)
- [2 General Department Breakdown](#2-general-department-breakdown)
    - [2.1 Engineering Disciplines](#21-engineering-disciplines)
    - [2.2 Types of Projects](#22-types-of-projects)
    - [2.3 Department Cooperatives](#23-department-cooperatives)
- [3 Onboarding](#3-onboarding)
    - [3.1 General Administrative Tools](#31-general-administrative-tools)
    - [3.2 General Responsibilities & Policy](#32-general-responsibilities--policy)
- [4 General Department Documentation](#4-general-department-documentation)
- [5 Projects & Tasks](#5-projects--tasks)
- [6 Technical Onboarding](#6-technical-onboarding)
    - [6.1 Bare Metal Programming](#61-bare-metal-programming)
    - [6.2 PCB Design](#62-pcb-design)

</details>

---

## 1 Introduction

👋 **Welcome to the Embedded Software (ES) Department of Ontario Tech Racing!**

This markdown file documents how our department operates, the typical workflow
and beginning steps for all new members of ES.

> All TODO steps are block quoted like this.

---

## 2 General Department Breakdown

Embedded Software (ES) is the department in charge of regions covering embedded
systems, higher level programming and rapid systems prototyping.

### 2.1 Engineering Disciplines

Our department covers many aspects of engineering, primarily:

- 🤖 **Mechatronics Engineering.**
    - Bare metal programming, embedded systems, system design, control systems,
      etc.
- ⚡ **Electrical Engineering.**
    - Circuits, electronics, digital systems, semiconductors, etc.
- 💻 **Software Engineering.**
    - Version control, algorithms, data structures, networking, etc.
- ⚙️ **Mechanical Engineering.**
    - Enclosures, vibrations, control systems, electromechanical systems, etc.
- **And more!**

### 2.2 Types of Projects

Our primary projects fall within **6 main categories**:

1. 🔭 **Sensors.**
    - Collect and forward sensor data.
2. 📈 **Telemetry.**
    - Process, visualize and interpret data.
3. 🚀 **Controls.**
    - Control systems, command and manage control loops.
4. ⚡ **Hardware.**
    - Design, build, test and integrate PCBs.
5. 🎮 **Interfaces.**
    - Design interfaces primarily for driver(s).
6. 🕹️ **Equipment.**
    - Build equipment for testing, simulation, manufacturing, etc.

### 2.3 Department Cooperatives

Due to the nature of our department, we also work mostly with the following
departments:

- **Hardware and Electronics (HE).**
    - Designing and building our PCBs, completing the hardware for our projects.
- **Electric Drivetrain (EDT).**
    - Engineering all high voltage and drivetrain aspects of our team.

---

## 3 Onboarding

### 3.1 General Administrative Tools

Our department and wider OTR team uses a variety of tools to organize technical
work and run efficiently:

> Send your `@ontariotechu.net` email and GitHub account username / email to the
> department
> lead: [daniel.jeon@ontariotechu.net](mailto:daniel.jeon@ontariotechu.net).
> Accept and ensure you have access to the following once you receive the email
> invites.

1. [Google Drive: OTR Embedded Software Shared Drive](https://drive.google.com/drive/u/0/folders/0AHPA2ZoOBCtSUk9PVA).
    - Our administrative file storage solution for only ES.
        - Department budgeting.
        - Meeting Notes / Agendas.
        - Presentation slide decks.
        - Datasheets.
        - etc.
2. [Google Calendar](https://calendar.google.com/).
    - Our general calendar and scheduling solution.
3. [GitHub Org: Ontario Tech Racing](https://github.com/OntarioTechRacing).
    - Our version control / devops solution for all ES work.
    - Also stores the majority of internal technical documentation.
4. Google
   Sheets & [GitHub Org ES Project](https://github.com/orgs/OntarioTechRacing/projects/1)
    - Our current high level project management solution.
    - Some legacy tracking might require [Monday.com](https://monday.com/).
5. [TBD]()~~[Ontario Tech Racing Slack](https://ontariotechracing.slack.com/)~~.
    - Our primary text based communication platform for all of OTR.
    - Legacy communications can be found
      on [Ontario Tech Racing Slack](https://ontariotechracing.slack.com/).
6. [Google Meets](https://meet.google.com/)
    - Our virtual meeting solution.

- **_It is highly recommended bookmark the pages above._**

### 3.2 General Responsibilities & Policy

The following are the general responsibilities and policy for our department /
OTR team.

> Please take note of these!

1. Participate in weekly ~1-hour "All electrical & software" meeting.
    - In person in ACE 5030 / ACE conference room, with backup Google Meets.
2. Active contributions to assigned subsystem teams and engineering work.
    - All ES members must make progress and contributions tracked on GitHub.
    - This may entail more meetings and work sessions as applicable.
    - Work may be in-person, virtual or hybrid depending on the task.
3. Active communications.
4. Attend and support team-wide meetings, work sessions, etc.
    - ~2-4 meetings per month.

---

## 4 General Department Documentation

All technical documentation about our department can be found on
the [embedded repository](https://github.com/OntarioTechRacing/embedded) or
through the GitHub pages version
at [ontariotechracing.github.io/embedded/](https://ontariotechracing.github.io/embedded/).

For new members there will be too much information to take in at once. We don't
expect you to know it all from the get go, but the department repository should
be a point of reference going forwards.

---

## 5 Projects & Tasks

From a high-level view of our department, each member manages various projects.
The projects are assigned by member interest, skill-set and urgency.

Different projects follow different development cycles, you will be introduced
to them towards the start of your first project contribution.

---

## 6 Technical Onboarding

Whether you are looking to focus on low-level hardware programming, high-level
scripts, PCB design or anything in between, all ES members should ideally
contribute to development of OTR FSAE race car(s).

- Our primary goal is to support engineering on the FSAE vehicles.
- Currently, high level programming (automation, CI/CD devops, ML, etc) are not
  priority.

### 6.1 Bare Metal Programming

Our low-level hardware runs on most commonly on STM32 microcontrollers. A STM32
beginner guide can be found
here: [stm32/getting_started](https://github.com/OntarioTechRacing/embedded/blob/main/resources/stm32/getting_started.md).

> Complete the STM32 getting started training.

### 6.2 PCB Design

PCBs allow for finalized packaging and development of more advanced circuits.
Our current resources documentation can be found
here: [kicad](https://ontariotechracing.github.io/embedded/resources/kicad.html).

- Note: We are currently transitioning from Altium and the current KiCad
  workflow and devops processes will likely change / update in the near future.
