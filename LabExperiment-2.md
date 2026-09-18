# Experiment 2: Problem Identification and Feasibility

**Course:** Software Engineering and Design Principles
**Experiment:** 2 – Problem Identification and Feasibility
**Project Title:** Student Placement Management System
**Domain:** Education and Campus Recruitment

## Aim

To identify the problem addressed by the Student Placement Management System and prepare its problem statement, objectives, scope, and technical and operational feasibility analysis.

## Objectives

* Identify the real-world problem addressed by the software project.
* Prepare a clear and concise problem statement.
* Define the objectives and scope of the proposed system.
* Perform technical and operational feasibility analysis.
* Evaluate the viability of the proposed solution.

## Introduction

Problem identification is the first step in software engineering. A clearly defined problem statement helps in understanding the actual requirements of stakeholders and provides a foundation for designing an effective software solution.

In many educational institutions, placement activities involve students, placement officers, faculty members, and recruiters. Managing student profiles, eligibility criteria, placement drives, applications, interview schedules, and offers manually can result in data duplication, delays, and difficulty in tracking placement activities.

The **Student Placement Management System** provides a centralized platform to manage the complete campus placement process efficiently.

## Selected Project

**Project Title:** Student Placement Management System
**Domain:** Education and Campus Recruitment

## Problem Statement

Traditional placement management often relies on spreadsheets, emails, forms, and manual communication between students, placement officers, and recruiters. This makes it difficult to maintain accurate student records, verify eligibility, manage placement drives, track applications, schedule interviews, and monitor final placement status.

A **Student Placement Management System** provides a centralized and secure platform where students can manage their profiles and applications, placement officers can manage drives and eligibility criteria, and recruiters can view and shortlist eligible candidates. The system helps reduce manual effort, improve data accuracy, and provide better visibility into the placement process.

## Project Objectives

* Provide secure authentication and role-based access for students, placement officers, and recruiters.
* Maintain centralized student academic, skill, and resume information.
* Allow placement officers to create and manage placement drives.
* Automatically identify students who satisfy specified eligibility criteria.
* Enable students to apply for eligible placement opportunities.
* Allow recruiters to view and shortlist candidates.
* Manage interview schedules and application status.
* Maintain placement and offer records.
* Generate placement statistics and reports.
* Reduce manual effort and improve the efficiency of campus recruitment activities.

## Project Scope

The Student Placement Management System covers the management of student profiles, companies, placement drives, eligibility criteria, applications, shortlisting, interviews, and placement offers.

The system supports different roles such as students, placement officers, and recruiters. Students can maintain their profiles, upload resumes, view eligible opportunities, and track applications. Placement officers can manage companies, placement drives, eligibility criteria, and placement statistics. Recruiters can create job requirements and shortlist suitable candidates.

Future enhancements may include AI-based resume screening, skill-based candidate matching, automated notifications, analytics dashboards, and cloud deployment.

Activities such as actual salary processing, company payroll management, employee onboarding, and external recruitment operations are outside the scope of the project.

## Technical Feasibility Analysis

| Factor            | Assessment | Remarks                                                                                              |
| ----------------- | ---------- | ---------------------------------------------------------------------------------------------------- |
| Technology        | Feasible   | Java and Spring Boot can be used for backend development.                                            |
| Database          | Feasible   | PostgreSQL can store student, company, drive, application, and placement data.                       |
| Frontend          | Feasible   | Next.js/React can provide a responsive user interface.                                               |
| Development Tools | Feasible   | IntelliJ IDEA/VS Code, Git and GitHub support development and version control.                       |
| Authentication    | Feasible   | Spring Security and JWT can provide secure authentication and role-based authorization.              |
| AI Integration    | Feasible   | Spring AI can be used for resume analysis and candidate-job matching.                                |
| Caching           | Feasible   | Redis can improve performance for frequently accessed data.                                          |
| Messaging         | Feasible   | Apache Kafka can handle asynchronous events such as notifications and application updates.           |
| Deployment        | Feasible   | Docker and AWS can be used for containerized cloud deployment.                                       |
| Scalability       | Feasible   | Modular architecture allows additional features and services to be added in the future.              |
| Security          | Feasible   | Password hashing, JWT authentication, authorization, input validation, and HTTPS can be implemented. |

## Operational Feasibility Analysis

| Factor               | Assessment | Remarks                                                                                    |
| -------------------- | ---------- | ------------------------------------------------------------------------------------------ |
| User Acceptance      | High       | The system provides a simple centralized interface for placement activities.               |
| Ease of Use          | High       | Students, recruiters, and placement officers can access features according to their roles. |
| Training Requirement | Low        | Basic training is sufficient because the workflow is simple and familiar.                  |
| Availability         | High       | A cloud-deployed system can be accessed whenever required.                                 |
| Maintainability      | High       | Modular and layered architecture makes maintenance easier.                                 |
| Data Management      | High       | Centralized storage reduces duplication and improves data consistency.                     |
| Business Benefit     | High       | Reduces manual work and improves placement process visibility and efficiency.              |
| Future Expansion     | High       | AI matching, analytics, notifications, and cloud-based services can be added later.        |

## Analysis

The feasibility study indicates that the **Student Placement Management System is technically and operationally viable**.

The required technologies such as Java, Spring Boot, PostgreSQL, React/Next.js, Docker, and AWS are widely available and suitable for implementing the proposed system. Security mechanisms such as authentication and role-based authorization can be implemented using standard frameworks.

Operationally, the system can reduce the dependency on spreadsheets and manual communication. A centralized platform can improve accessibility, data consistency, application tracking, and placement administration.

The proposed system can initially be implemented as a modular application and can later be extended with AI-based candidate matching, event-driven processing, analytics, and cloud infrastructure.

## Observation

Clearly defining the problem, objectives, scope, and feasibility helps determine whether the proposed software solution is practical and achievable. The feasibility analysis shows that the Student Placement Management System can be developed using available technologies and can provide significant benefits to students, placement officers, and recruiters.

## Result

The problem statement, objectives, project scope, and technical and operational feasibility of the **Student Placement Management System** were successfully identified and analyzed. The study concludes that the proposed system is feasible and provides a suitable foundation for subsequent software design and development activities.
