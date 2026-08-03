# Deploy Summary & Runbook — CNO Policyholder-Account Portal (Sitecore XP / .NET 8)

> **System:** CNO policyholder self-service portal (`cno-mini-svc-hook`)
> **Source platform:** Liferay 6.2 EE
> **Target platform:** Sitecore XP / XM 10.x · .NET 8.0 · MVC/SXA C#
> **Artifact:** `Cno.Web` + `Cno.Domain` — 154 files · build PASSED · SHA-256 manifested
> **Date:** 2026-07-13 · **Prepared by:** aiDAP Technical Discovery · **Version:** 1.0

---

## Table of Contents

1. [Deploy Outcome](#1-deploy-outcome)
2. [Deploy Pipeline](#2-deploy-pipeline)
3. [Deploy Steps (Runbook)](#3-deploy-steps-runbook)
4. [Verification & Smoke Checks](#4-verification--smoke-checks)
5. [Rollback](#5-rollback)
6. [Post-Deploy — Confidence-Driven UAT Scope](#6-post-deploy--confidence-driven-uat-scope)

---

## 1. Deploy Outcome

The gate-passed package (154 files, 0 build errors, SHA-256 manifested) is deployed as a **.NET application publish** onto a Sitecore XP 10.x delivery host.