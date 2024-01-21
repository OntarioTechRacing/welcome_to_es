# welcome_to_es

![OTR Logo.png](OTR%20Logo.png)

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
- [5 Workflow](#5-workflow)
- [6 Technical Onboarding](#6-technical-onboarding)
    - [6.1 Bare Metal Programming](#61-bare-metal-programming)

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
    - [GitHub Org ES Project](https://github.com/orgs/OntarioTechRacing/projects/1)
      for all our technical project management.
4. [Slack](https://slack.com/).
    - Our primary text based communication platform for all of OTR
        - For virtual meetings we occasionally use Slack huddles, but mostly
          use [Google Meets](https://meet.google.com/).
5. [Monday.com](https://monday.com/).
    - Our high level project management solution for all of OTR
      with [ES department board](https://ontario-tech-racing.monday.com/boards/3165097442).

- **_It is highly recommended bookmark the pages above._**

### 3.2 General Responsibilities & Policy

The following are the general responsibilities and policy for our department /
OTR team.

> Please take note of these!

1. Weekly department meeting.
2. 2 hour in-person minimum.
    - All ES members must commit at least 2 hours of in-person work each week,
      this includes:
        - Working on your OTR project(s).
        - Contributing time to someone else's OTR project.
        - Cleaning up / organizing team facilities.
        - etc.
    - Meetings including weekly department meetings do not count towards the 2
      hours unless the meeting is specifically for working on a project or team
      responsibility.
3. Active communications via Slack.
4. Attending and supporting wider team meetings, work sessions, etc.
    - ~1-2 sessions per month.

---

## 4 General Department Documentation

All technical documentation about our department can be found on
the [embedded repository](https://github.com/OntarioTechRacing/embedded).

For new members there will be too much information to take in at once. We don't
expect you to know it all from the get go, but the department repository should
be a point of reference going forwards.

> Please review the embedded repository
> [`README.md`](https://github.com/OntarioTechRacing/embedded/blob/main/README.md)
> for an overview of the technical conventions and workflow of our department.

---

## 5 Workflow

From a high-level view of our department, each member manages various projects.
The projects are assigned by member interest, skill-set and urgency.

Different projects follow different development cycles, you will be introduced
to them towards the start of your first project contribution.

You can view a list of our current ongoing and completed projects on
monday.com and technical progress is on our GitHub project board (see department
project board links above).

> Look at the scrum board to see if any projects labeled (upcoming) interest
> you. You might have a chance to contribute to a project as a project manager (
> PM) or task manager (TM).

---

## 6 Technical Onboarding

### 6.1 Bare Metal Programming

Whether you are looking to focus on low-level hardware programming, high-level
scripts or anything in between, all ES members should ideally contribute to
development of OTR FSAE EV.

- Our primary goal is to support engineering on the FSAE EV.
- High level programming (automation, CI/CD devops, ML, etc) are typically not
  priority as of the current state of OTR.

Our module level hardware runs on most commonly on STM32 microcontrollers. A
STM32 beginner guide has been created on the embedded
repository: [stm32/getting_started](https://github.com/OntarioTechRacing/embedded/blob/main/resources/stm32/getting_started.md).

> Complete the STM32 getting started training.
