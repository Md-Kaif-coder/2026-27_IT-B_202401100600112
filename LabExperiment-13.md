# Experiment 13: Agile Workflow and Project Management

## 1. Aim

To understand Agile methodology, Scrum practices, sprint planning, backlog creation, and Scrum board management using the Student Placement Management System as a case study.

## 2. Objectives

- To understand the Agile software development methodology.
- To identify Scrum roles, events, and artifacts.
- To create a product backlog based on project requirements.
- To prepare a sprint plan with tasks, priorities, and acceptance criteria.
- To demonstrate a Scrum board using GitHub Projects or Trello.
- To understand how Agile practices are applied in industry workflows.

## 3. Tools and Technologies

- Project Management: GitHub Projects or Trello
- Version Control: Git and GitHub
- Backend: Java and Spring Boot
- Frontend: Next.js / React
- Database: PostgreSQL
- Documentation: Markdown

*Note: GitHub Projects or Trello can be used to implement the proposed Agile board. The board below is a design example; it does not claim that an external board has already been created.*

## 4. Introduction to Agile Methodology

Agile is an iterative and incremental approach to software development in which teams deliver software in small increments, incorporate feedback, and adapt to changing requirements.

Instead of completing the entire application before delivering anything, Agile teams divide work into manageable tasks and deliver useful functionality in repeated cycles.

### 4.1 Agile Principles

- Deliver working software frequently.
- Welcome changing requirements when they provide value.
- Encourage collaboration between stakeholders and developers.
- Maintain continuous communication within the team.
- Focus on working software as a measure of progress.
- Improve the development process through regular feedback.

### 4.2 Agile in the Student Placement Management System

The project can be developed incrementally:

- **Sprint 1:** Project setup, authentication, and user roles.
- **Sprint 2:** Student profiles and resume management.
- **Sprint 3:** Placement drive management and eligibility checking.
- **Sprint 4:** Application submission and status tracking.
- **Sprint 5:** Interview management, offers, and reporting.
- **Sprint 6:** Testing, bug fixing, and release preparation.

These are proposed sprint boundaries and can be adjusted according to team size, sprint duration, dependencies, and priorities.

## 5. Scrum Framework

Scrum is an Agile framework that helps teams organize complex work into short, time-boxed iterations called Sprints.

### 5.1 Scrum Roles

**1. Product Owner**

- Defines and communicates the product goal.
- Orders the product backlog according to value and priorities.
- Clarifies requirements and acceptance criteria.

**2. Scrum Master**

- Helps the team understand and apply Scrum.
- Facilitates Scrum events when needed.
- Helps address impediments and improve team effectiveness.

**3. Developers**

- Build, test, and integrate the product increment.
- Estimate and organize work during sprint planning.
- Collaborate to achieve the Sprint Goal.

*For a student project, one person may perform multiple responsibilities, but the responsibilities should remain clear.*

### 5.2 Scrum Events

| Event | Purpose | Typical Timing |
|---|---|---|
| Sprint | Time-boxed period for creating an increment | One to four weeks |
| Sprint Planning | Establishes the Sprint Goal and plans the work | At the start of the Sprint |
| Daily Scrum | Inspects progress toward the Sprint Goal and adapts the plan | 15 minutes for Developers |
| Sprint Review | Inspects the increment and discusses future adaptations | Near the end of the Sprint |
| Sprint Retrospective | Identifies improvements to the team's process | After the Sprint Review and before the next Sprint |

### 5.3 Scrum Artifacts

- **Product Backlog:** Ordered list of work needed to improve the product.
- **Sprint Backlog:** Sprint Goal, selected Product Backlog items, and the plan for delivering them.
- **Increment:** Usable product functionality that meets the Definition of Done.

## 6. Product Backlog Creation

### 6.1 Definition

A product backlog is an ordered and evolving list of product work. Items can represent features, enhancements, defects, or technical improvements.

### 6.2 Product Backlog for the Project

| ID | User Story | Priority | Acceptance Criteria |
|---|---|---|---|
| PB-01 | As a student, I want to register an account so that I can use the placement portal. | High | Valid unique details create an account; duplicate email is rejected. |
| PB-02 | As a user, I want
