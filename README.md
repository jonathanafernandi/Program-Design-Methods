# Program-Design-Methods

A group assignment for the **COMP6798001 – Program Design Methods** course (Bina Nusantara University, School of Computer Science), consisting of two parts: a **Case Study** on algorithm design using IPO Charts and pseudocode, and a **Project** on requirements gathering and UML-based system design for a student schedule reminder application.

## Table of Contents

- [Overview](#overview)
- [Group Members](#group-members)
- [Project Structure](#project-structure)
- [Part 1: Case Study](#part-1-case-study)
- [Part 2: Project](#part-2-project)
- [References](#references)

## Overview

This repository documents the design process for two related deliverables:

1. **Case Study**: Designing an algorithm (via IPO Chart and pseudocode) that counts campus visitors by body temperature category, based on a data file (`Todaysvisitors.dat`) recorded during BINUS University's COVID-19 health protocol screening.
2. **Project**: Conducting an observation with Binusian students to gather functional and non-functional requirements for a proposed application, then modeling the system using UML diagrams (use case, CRC card, class diagram, activity diagram, state diagram, and sequence diagram).

## Group Members

| Name | Student ID |
|---|---|
| Jonathan Alvindo Fernandi | 2602089143 |
| Medy Gunawan | 2602084741 |
| Muhammad Keinanthan Wahyuwardhana | 2602083291 |
| Richard Dave Teherag | 2602084905 |
| Richard Mazmur Columbus | 2602084312 |

**Class:** LC01  
**Lecturer:** Irma Irawati Ibrahim, S.S., M.Kom.  
**Semester/Academic Year:** 1/2022–2023

## Project Structure

```
Program-Design-Methods/
├── COMP6798001-PDM_AoL-AssessmentForm.pdf
├── AoL-CaseStudy-Project.pdf
└── README.md
```

## Part 1: Case Study

**Solution summary:**

- The IPO Chart defines inputs (`name`, `bodyTemperature`, `dataRecord`), the process (reading each record, comparing temperature against the 37.1°C threshold, and incrementing the appropriate counter), and outputs (`normalBodyTemperature`, `suspectedBodyTemperature`, `totalVisitors`).
- The pseudocode opens the data file, checks for its existence, loops through each record until end-of-file, classifies each visitor by temperature, and displays the final counts.

## Part 2: Project

**Proposed application:** A unified schedule and deadline reminder app for Binusian students.

### Functional Requirements

1. Collect all activity schedule notifications from BINUSMAYA, BINUS Mobile, Beelingua, and SoCS.
2. Store all collected notifications from these apps/websites into one integrated application.
3. Generate a calendar summarizing activities and deadlines that students need to complete.
4. Display detailed information about upcoming activities or deadlines.
5. Send periodic reminder notifications for scheduled activities and deadlines.

### Non-Functional Requirements

1. The application must run smoothly on both Android and iOS operating systems.
2. The application must support fast and up-to-date data processing.

### UML Diagrams

- **Use Case Diagram**: "User Reminder" use case, involving Students and Lecturers as actors, describing how the app collects course/assignment schedules and issues reminders.
- **CRC Card (Class-Responsibility-Collaboration)**: defines the responsibilities and collaborators of key system classes.
- **Class Diagram**: models the static structure of the reminder system.
- **Activity Diagram**: models the flow of activities from schedule collection to notification delivery.
- **State Diagram**: models the states of a scheduled activity/assignment (e.g., upcoming, due soon, overdue, completed).
- **Sequence Diagram**: models the interaction sequence between students, lecturers, and the system when a schedule is created, edited, or triggers a notification.

## References

- Gaddis, T. (2019). *Starting Out with Programming Logic and Design* (5th ed.). Chapter 2.2: Output, Input, and Variables.
- Dennis, A., Wixom, B. H., & Tegarden, D. (2015). *Systems Analysis and Design: An Object-Oriented Approach with UML* (5th ed.). Chapter 4: Business Process and Functional Modeling, pp. 126–127.
