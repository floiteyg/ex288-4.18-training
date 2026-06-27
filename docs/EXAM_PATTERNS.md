# EX288 Troubleshooting Patterns

> Repository: **ex288-4.18-training**

---

# Purpose

This document collects recurring troubleshooting patterns observed throughout the laboratories.

Its purpose is not to teach commands.

Its purpose is to teach **how to think**.

Successful OpenShift Developers recognize patterns before they search for commands.

---

# General Troubleshooting Workflow

Observe

↓

Hypothesis

↓

Collect Evidence

↓

Confirm

↓

Fix

↓

Validate

---

# Build Problems

## Build Failed

Typical investigation order

BuildConfig

↓

Build Logs

↓

Build Strategy

↓

Git Repository

↓

ContextDir

↓

Builder Image

---

# Deployment Problems

## Pod does not start

Deployment

↓

ReplicaSet

↓

Pod Events

↓

Container Logs

↓

Configuration

---

# Route Problems

## Route returns 503

Route

↓

Service

↓

Endpoints

↓

Selectors

↓

Pod Labels

---

# CrashLoopBackOff

Container Logs

↓

ConfigMap

↓

Secret

↓

Mounted Files

↓

Permissions

↓

Application

---

# Configuration Problems

## Application starts with incorrect configuration

ConfigMap

↓

Secret

↓

Environment Variables

↓

Mounted Volumes

↓

Application Logs

---

# Probe Problems

## Readiness Probe Failed

Probe Path

↓

Port

↓

Response Code

↓

Application Startup

---

## Liveness Probe Failed

Startup Time

↓

Application Logs

↓

Health Endpoint

↓

Restart Count

---

# Resource Problems

Pod Pending

↓

Requests

↓

Limits

↓

Node Resources

↓

Events

---

# Golden Rule

Never edit resources before understanding why they failed.

Diagnosis always comes before implementation.

---

# Repository Philosophy

The objective of this repository is not to memorize OpenShift commands.

The objective is to recognize recurring production patterns that also appear during the EX288 certification exam.

