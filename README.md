# QA_Checklist_RuknuddinAsrari

## QA Checklist – Software Quality Verification

> **Task: QA Checklist Preparation**
> **Prepared by:** Ruknuddin Asrari
> **Email:** ruknuddin.asrari@thecareerinsights.com
> **Job Title:** Software Quality Engineer
> **Department:** IT Software Development
> **Organisation:** The Career Insights Hub LLC
> **Date:** 2026 | Version: 1.0

---

## 📋 Project Overview

This repository contains the complete **QA Checklist and Quality Verification** documentation for the **Student Registration System (SRS)**. The checklist verifies that the application meets defined quality standards across functionality, input validation, usability, security, and performance before release.

---

## 📁 Repository Structure

```
QA_Checklist_RuknuddinAsrari/
│
├── QA_Checklist.pdf              # 63-point pre-release checklist across 5 categories
├── Validation_Summary.pdf        # Consolidated validation findings, failed item detail, release recommendation
├── Defect_Issue_Notes.pdf        # Detailed defect notes, observations, and prioritised action matrix
└── README.md                     # This file
```

---

## 📊 Summary of Findings

| Category | Items | Pass | Fail | Warn | N/A |
|---|---|---|---|---|---|
| Functionality | 21 | 13 | 7 | 0 | 1 |
| Input Validation | 14 | 7 | 4 | 3 | 0 |
| Usability | 14 | 7 | 1 | 5 | 1 |
| Security | 5 | 3 | 1 | 1 | 0 |
| Performance | 4 | 3 | 0 | 1 | 0 |
| Documentation | 5 | 2 | 1 | 2 | 0 |
| **TOTAL** | **63** | **33** | **14** | **13** | **3** |

### Release Status: ❌ NOT READY FOR RELEASE
5 Critical and 5 High severity defects remain open. QA sign-off is blocked until all Critical/High FAIL items are resolved and verified.

---

## 🐛 Critical Defects Found

| Defect | Issue | Severity |
|---|---|---|
| DN-001 | Login accepts wrong password — authentication bypassed | Critical |
| DN-002 | Student role accesses Admin Dashboard via direct URL | Critical |
| DN-003 | Full course enrollment accepted — seat count goes negative | Critical |
| DN-003 | Duplicate course enrollment accepted | Critical |
| DN-004 | No account lockout after 5 failed login attempts | High |
| DN-004 | Session persists after logout via browser back button | High |
| DN-005 | No server-side validation — API bypasses all frontend checks | High |
| DN-006 | Oversized photo upload and empty required field accepted | Medium |

---

## 🎯 My Approach

### 1. Checklist Design
I structured the 63-point checklist across five categories — Functionality, Input Validation, Usability, Security, and Quality Standards — ensuring that every critical aspect of a pre-release review is covered. Each checkpoint maps to specific modules and references relevant test cases from Assignment 2.

### 2. Status Classification
Each checkpoint was evaluated and assigned one of four statuses: PASS, FAIL, WARN, or N/A. FAIL items are linked directly to defect references. WARN items are documented as risk observations requiring attention but not blocking release.

### 3. Validation Summary
The Validation Summary consolidates all findings into a category-level score table, details every FAIL and WARN item with a recommended action, and provides a clear release recommendation based on the results.

### 4. Defect / Issue Notes
The Defect Notes document groups related defects into 6 detailed notes (DN-001 to DN-006), each with observed behaviour, business impact, and a specific recommended fix. An 8-item observation log captures all WARN-level findings, and a prioritised action matrix maps every action to an owner, priority, and target timeline.
