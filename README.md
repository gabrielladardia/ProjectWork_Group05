
# Telerehabilitation & Biofeedback Session Manager

## Project Overview
 
The goal of the project is to develop a Java desktop application that allows clinicians to design, customize, and execute personalized rehabilitation protocols.

The application will use the provided `edu.unisa.medsim` simulation engine to generate physiological telemetry data, including heart rate, oxygen saturation, and perceived fatigue or pain.

The project follows the Scrum framework and is developed incrementally across three sprints.

## Project Requirements

The project is organized into four User Epics, listed in order of priority.

### Epic 1 - Basic Exercise, Protocol Management & Simulated Execution
**Priority:** High

- Create, modify, delete, and display rehabilitation exercises.
- Create and manage therapy protocols.
- Start, pause, resume, skip, and stop exercise sessions.
- Display simulated physiological telemetry in real time.
- Integrate and extend the provided simulation engine.

### Epic 2 - Safety Thresholds, Undo/Redo & Execution Protocol
**Priority:** High/Medium

- Automatically pause sessions when safety thresholds are exceeded.
- Support Undo/Redo operations.
- Implement sequential, adaptive, and circuit execution modes.

### Epic 3 - Clinical Smart Filtering
**Priority:** Medium

- Generate protocols based on patient constraints.
- Filter exercises using clinical criteria.
- Display usage statistics on the dashboard.
- Associate clinical tags and contraindications with exercises.

### Epic 4 - Reusable Therapy Modules & Template Library
**Priority:** Low

- Create reusable Therapy Modules.
- Save and load protocols and modules.
- Import and export a Clinical Module Library.
- Reorder and manage exercises within protocols.
- Support advanced simulation configuration.

The implementation of these features depends on sprint priorities and available development time.

## Technologies and Tools

- **Programming Language:** Java
- **Build Tool:** Maven
- **Unit Testing:** JUnit
- **Version Control:** Git and GitHub
- **Project Management:** Trello
- **Development Methodology:** Scrum
- **Ide:** Apache NetBeans

## Scrum Organization

The project is divided into four phases:

1. **Pre-Game:** Requirements analysis, Product Backlog, software architecture, Definition of Done, and Sprint 1 planning.
2. **Sprint 1:** First development iteration.
3. **Sprint 2:** Second development iteration.
4. **Sprint 3:** Final development iteration and project presentation.

## Team

**Group 05 - Medical Software Engineering**

Anna Carbone, Gabriella D'Ardia, Alisia Romano, Francesco Spinelli.

