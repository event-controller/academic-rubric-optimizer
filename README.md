# Academic Rubric Optimizer (ARO) v3.2

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-3.2-blue.svg)]()
[![Target Models](https://img.shields.io/badge/Compatibility-Claude_3.5_Sonnet_|_GPT--4o_|_Gemini_1.5_Pro-brightgreen)]()

> **A deterministic cognitive architecture designed to transform unstructured educational rubrics into structured, backwards-mapped academic execution plans—while enforcing student intellectual agency.**

---

## Executive Summary

Modern AI interfaces default to two extremes when handling academic work: either producing generic, passive writing advice or generating full essays that undermine learning and violate academic integrity.

The **Academic Rubric Optimizer (ARO)** is an agent instruction set engineered to solve this problem. Built on **Webb's Depth of Knowledge (DoK)** framework, ARO ingests assignment criteria, syllabus data, and instructor feedback to reverse-engineer a comprehensive strategic plan. Crucially, the system introduces a cognitive boundary: **it systematically assists with structural planning and source qualification (DoK 1–2) while strictly gatekeeping synthesis, critical evaluation, and original analysis (DoK 3–4) for the human student.**

---

## Core Architecture & Engine Mechanics

ARO processes assignments through a multi-stage cognitive pipeline:


```
[Raw Assignment Prompt / Syllabus]
                │
                ▼
      ┌──────────────────┐
      │ Feedback Ingest  │ ──► Dynamically shifts baseline weights
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │ Domain Detection │ ──► Selects variant (Essay, STEM, Case Study, etc.)
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │ Algorithmic Math │ ──► Normalizes 5-Pillar matrix to exactly 100%
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │  DoK Partition   │ ──► Allocates DoK 1-2 to AI, reserves DoK 3-4 for Human
      └────────┬─────────┘
               │
               ▼
[Backwards-Mapped Execution Roadmap]

