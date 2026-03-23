# SCHEDULO_SIH

https://edu-sched-ai-11b53d25.base44.app

# SCHEDULO — AI-Based Timetable Generation System (Prototype)

## Overview

SCHEDULO is an AI-driven timetable generation system designed to address the increasing complexity of academic scheduling in institutions adopting multidisciplinary education models under NEP 2020.

The project focuses on developing an intelligent scheduling framework capable of generating optimized, conflict-free timetables while accommodating student preferences, faculty constraints, and institutional policies.

---

## Project Status

Technology Readiness Level: TRL 4 — Prototype Stage

* User interface prototype designed and validated
* System architecture and workflow defined
* Core optimization approach (Genetic Algorithm and Constraint Satisfaction Problem) conceptualized
* Initial model experimentation in progress

The backend system, full algorithmic implementation, and deployment pipeline are currently under development.

---

## Problem Statement

Timetable generation in academic institutions is traditionally a manual and iterative process that suffers from several limitations:

* High time and effort requirements
* Frequent scheduling conflicts across courses and departments
* Inability to scale with multidisciplinary course structures
* Lack of adaptability to real-time changes in availability or policy

With the implementation of NEP 2020, increased flexibility in course selection has further intensified scheduling complexity, especially in managing cross-department electives and resource allocation.

---

## Proposed Solution

SCHEDULO proposes a hybrid AI-based scheduling system that integrates optimization and constraint-solving techniques to automate timetable generation.

The system is designed around the following components:

* Genetic Algorithms for global optimization of scheduling combinations
* Constraint Satisfaction Problem (CSP) techniques for enforcing hard constraints such as faculty availability, room allocation, and course conflicts
* Data-driven models to support adaptive scheduling and future extensibility

### Key Capabilities

* Automated generation of conflict-free timetables
* Balanced distribution of faculty workload
* Support for dynamic rescheduling
* Scalable design suitable for multidisciplinary academic structures

---

## System Architecture

The system is structured into three primary layers:

1. Input Layer
   Collects and processes student course selections, faculty availability, and institutional constraints

2. AI Engine
   Combines Genetic Algorithms and CSP techniques to generate optimized scheduling solutions

3. Output Layer
   Produces structured timetables along with dashboards for monitoring and analysis

Refer to the architecture diagram in the `/design` directory for a detailed representation.

---

## Prototype Interface

The current prototype demonstrates the user interaction layer of the system, including:

* Student interface for course and elective selection
* Administrative dashboard for monitoring scheduling metrics
* Visualization of timetable outputs and analytics

Screenshots of the prototype are available in the `/prototype-ui` directory.

---

## System Workflow

The scheduling process follows a structured workflow:

1. Collection of student preferences and course selections
2. Integration of faculty availability and infrastructure constraints
3. Processing through the AI-based optimization engine
4. Generation of a structured timetable
5. Provision for iterative refinement and future dynamic rescheduling

---

## Technology Stack (Planned)

| Layer      | Technology             |
| ---------- | ---------------------- |
| Backend    | FastAPI (Python)       |
| Frontend   | React.js               |
| Database   | Supabase               |
| Deployment | AWS Cloud Services     |
| AI Engine  | Genetic Algorithm, CSP |

---

## Expected Outcomes

* Generation of conflict-free timetables with high reliability (target ≥95%)
* Reduced timetable generation time (target under 2 minutes per cycle)
* Improved utilization of institutional resources
* Reduction in administrative workload associated with manual scheduling

---

## Future Work

* Implementation of backend services and API endpoints
* Development of the optimization engine (GA + CSP integration)
* Integration with real institutional datasets
* Deployment on a scalable cloud infrastructure
* Extension to include reinforcement learning for adaptive scheduling
* Integration with existing ERP systems

---

## Research Foundation

The project is informed by prior research in:

* AI-based scheduling and optimization systems
* Genetic algorithm-based timetable generation
* Constraint satisfaction approaches for resource allocation
* Policy frameworks introduced under NEP 2020

Detailed references are provided in the accompanying project documentation.

---

## Team

CTRL + ALT + Z

---

## Note

This repository represents a design and prototype-stage implementation intended to demonstrate system architecture, problem understanding, and solution approach. Full system development is in progress.
