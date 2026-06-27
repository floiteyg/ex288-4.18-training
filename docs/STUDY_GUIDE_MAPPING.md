# EX288 4.18 Study Guide Mapping

> Repository: **ex288-4.18-training**
>
> Version: **1.0**
>
> Status: **Living Document**

---

# Purpose

This document maps the official EX288 / DO288 4.18 Study Guide to the practical training framework used in this repository.

It is **not** intended to replace the official documentation.

Instead, it defines:

* What competencies must be mastered.
* Which laboratories will cover each competency.
* The relationship between official objectives and practical exercises.
* The training progress throughout the project.

The **official Study Guide** remains the source of truth.

---

# Training Philosophy

This repository is based on four principles.

## Learn by troubleshooting

The objective is not to memorize commands.

The objective is to recognize problems and solve them using a structured troubleshooting methodology.

---

## Practice over theory

Every competency should be learned by completing practical laboratories.

Reading documentation alone is not considered sufficient.

---

## Real OpenShift environments

Whenever possible every exercise should run using:

* OpenShift Local (CRC)
* Git repositories
* oc CLI
* Red Hat supported technologies

---

## Reusable content

Every laboratory should also be reusable for:

* YouTube
* TikTok
* Live Streams
* MateOps
* Community learning

---

# Official Competencies

---

# Module 1 — Deploy Simple Applications

## 1.1 Deploy applications using the OpenShift Web Console

Topics

* Developer Perspective
* Import from Git
* Deploy from Container Image
* Application Topology

Mapped laboratories

* WEB-001
* WEB-002

Status

⬜ Not Started

---

## 1.2 Deploy applications using CLI tools

Topics

* oc new-app
* odo
* Devfiles
* Git repositories

Mapped laboratories

* CTX-001
* CTX-002
* CTX-003

Status

⬜ Not Started

---

# Module 2 — Container Images

## 2.1 Build UBI based container images

Topics

* Podman
* UBI Images
* Containerfiles
* Dockerfiles
* Image permissions

Mapped laboratories

* IMG-001
* IMG-002
* IMG-003

Status

⬜ Not Started

---

## 2.2 Consume private container registries

Topics

* Registry authentication
* Image Pull Secrets

Mapped laboratories

* REG-001
* REG-002

Status

⬜ Not Started

---

## 2.3 Image Streams

Topics

* ImageStreams
* ImageStreamTags
* External Registries

Mapped laboratories

* IS-001
* IS-002
* IS-003

Status

⬜ Not Started

---

# Module 3 — Builds

## 3.1 Build management

Topics

* BuildConfig
* Source Strategy (S2I)
* Docker Strategy
* Build troubleshooting

Mapped laboratories

* BLD-001
* BLD-002
* BLD-003

Status

⬜ Not Started

---

## 3.2 Build Triggers

Topics

* ImageChange Trigger
* ConfigChange Trigger

Mapped laboratories

* TRG-001
* TRG-002

Status

⬜ Not Started

---

## 3.3 S2I customization

Topics

* assemble
* run
* .s2i/bin

Mapped laboratories

* S2I-001
* S2I-002

Status

⬜ Not Started

---

# Module 4 — Deployments

## 4.1 Deployment Strategies

Topics

* Rolling
* Recreate

Mapped laboratories

* DEP-001
* DEP-002

Status

⬜ Not Started

---

## 4.2 Application configuration

Topics

* ConfigMaps
* Secrets
* Environment Variables
* Mounted Volumes

Mapped laboratories

ConfigMaps

* CFG-001
* CFG-002
* CFG-003

Secrets

* SEC-001
* SEC-002
* SEC-003

Status

⬜ Not Started

---

## 4.3 Stateful Applications

Topics

* PVC
* StatefulSets
* Storage

Mapped laboratories

* STS-001
* STS-002

Status

⬜ Not Started

---

## 4.4 Application Health

Topics

* Readiness Probe
* Liveness Probe
* Resource Requests
* Resource Limits

Mapped laboratories

* PRB-001
* PRB-002
* PRB-003

Status

⬜ Not Started

---

# Module 5 — Multi-container Applications

## 5.1 OpenShift Templates

Mapped laboratories

* TMP-001
* TMP-002
* TMP-003

Status

⬜ Not Started

---

## 5.2 Helm

Topics

* Chart creation
* Dependencies
* Values
* Installation
* Upgrade
* Packaging

Mapped laboratories

* HLM-001
* HLM-002
* HLM-003
* HLM-004
* HLM-005

Status

⬜ Not Started

---

## 5.3 Kustomize

Topics

* Base
* Overlays
* Environment customization

Mapped laboratories

* KUS-001
* KUS-002
* KUS-003

Status

⬜ Not Started

---

# Module 6 — OpenShift Pipelines

## 6.1 Tekton

Topics

* Tasks
* Pipelines
* PipelineRuns
* Workspaces
* tkn CLI

Mapped laboratories

To be defined after evaluating exam relevance.

Status

🟡 Research

---

# Naming Convention

Each laboratory has a permanent identifier.

Examples

CTX-001

CFG-002

SEC-003

PRB-001

TMP-002

HLM-004

Identifiers never change, even if the implementation evolves.

---

# Progress

| Module              | Status |
| ------------------- | ------ |
| Deploy Applications | ⬜      |
| Container Images    | ⬜      |
| Builds              | ⬜      |
| Deployments         | ⬜      |
| Multi-container     | ⬜      |
| Pipelines           | ⬜      |

---

# Notes

This document is intentionally concise.

Detailed laboratory descriptions are maintained separately in:

* docs/LAB_INDEX.md

The official Study Guide remains the authoritative reference for certification objectives.

