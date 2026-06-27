# Laboratory Guidelines

> Repository: **ex288-4.18-training**
>
> Version: **1.0**
>
> Status: **Living Document**

---

# Purpose

This document defines the design principles used for every laboratory contained in this repository.

The objective is to provide a consistent, realistic and high-quality learning experience focused on practical OpenShift development.

These guidelines ensure that every laboratory follows the same educational philosophy regardless of the technology involved.

---

# Project Philosophy

This project is built around one simple idea:

> **People learn OpenShift by solving problems, not by memorizing commands.**

Every laboratory must therefore simulate situations that an OpenShift Developer could realistically encounter in production or during the EX288 certification exam.

---

# Technical Credits

## Project Author

**Fernando Loitey**

Red Hat Engineer

Infrastructure & OpenShift Specialist

Project creator and maintainer.

---

## Technical Collaboration

The laboratory framework, instructional methodology and technical architecture have been developed with the assistance of **ChatGPT (OpenAI)**.

Rather than replacing practical engineering experience, ChatGPT serves as a technical design partner, helping transform certification objectives into structured, practical and reusable learning experiences.

Final technical decisions and validations always remain the responsibility of the project maintainer.

---

# General Principles

Every laboratory must follow these principles.

## 1. One competency at a time

Each laboratory should primarily teach a single competency.

Additional concepts may appear naturally, but they must never distract from the primary learning objective.

---

## 2. Realistic scenarios

Laboratories should simulate situations commonly found in production environments.

Artificial or unrealistic exercises should be avoided whenever possible.

---

## 3. Troubleshooting first

Students are expected to investigate, diagnose and validate before modifying resources.

The goal is to build troubleshooting skills rather than command memorization.

---

## 4. CRC compatibility

Every laboratory must run successfully using:

* OpenShift Local (CRC)
* Git repositories
* oc CLI

No enterprise infrastructure should be required.

---

## 5. Reproducibility

Every exercise must be reproducible from scratch.

A clean CRC installation should be able to execute every laboratory following the provided instructions.

---

## 6. Validation

Every laboratory must define an objective validation.

Examples include:

* Successful Build
* Pod Running
* Route responding correctly
* Expected application output
* Helm release deployed successfully

A laboratory is considered complete only after objective validation.

---

## 7. Progressive difficulty

Laboratories are designed to increase in complexity.

Difficulty levels are:

🟢 Beginner

🟡 Intermediate

🟠 Advanced

🔴 Exam Mode

---

## 8. Pattern recognition

Every laboratory must reinforce a troubleshooting pattern.

Examples:

Build fails

↓

Inspect BuildConfig

↓

Read Build Logs

↓

Validate Build Strategy

↓

Review Source Configuration

or

Route returns 503

↓

Verify Service

↓

Check Endpoints

↓

Validate Labels and Selectors

Students should gradually recognize these patterns without relying on memorized commands.

---

## 9. Reusable learning

Every laboratory should be suitable for reuse as:

* GitHub documentation
* TikTok short
* YouTube video
* Live demonstration
* MateOps practical exercise

Educational value extends beyond certification preparation.

---

## 10. Continuous evolution

OpenShift evolves continuously.

Laboratories should evolve with the platform.

Outdated technologies may remain for historical reference, but new laboratories should prioritize current OpenShift best practices.

---

# Laboratory Structure

Every laboratory should contain the following elements.

```
labXX/

README.md

starter/

assets/

validation/
```

---

## README.md

Contains the student instructions.

Should include:

* Objective
* Scenario
* Initial State
* Deliverables
* Validation Criteria

Solutions should never appear here.

---

## starter/

Contains the intentionally incomplete or broken application.

Students perform all work inside this directory.

---

## assets/

Optional resources required by the laboratory.

Examples:

* YAML manifests
* Helm Charts
* Templates
* Supporting files

---

## validation/

Contains scripts or documentation used to validate the final result.

---

# Laboratory Lifecycle

Each laboratory follows the same workflow.

```
Study Guide

↓

Competency

↓

Scenario Design

↓

Implementation

↓

Troubleshooting

↓

Validation

↓

Debrief

↓

Content Reuse
```

---

# Definition of Done

A laboratory is considered complete only when:

* The learning objective has been achieved.
* The application behaves as expected.
* Validation succeeds.
* The troubleshooting process is understood.
* The scenario can be reproduced from scratch.
* The laboratory is ready for educational reuse.

---

# Long-Term Vision

This repository is intended to become more than an EX288 study resource.

Its long-term objective is to provide a practical, community-driven OpenShift Developer training framework that evolves alongside future OpenShift releases.

The certification is a milestone.

The framework is the project.

