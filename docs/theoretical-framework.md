# Theoretical Framework & Architectural Principles

The **Academic Rubric Optimizer (ARO)** bridges natural language processing with higher education pedagogy. Rather than operating as an open-ended conversational agent, ARO acts as an algorithmic cognitive scaffold designed to enforce academic rigor and human intellectual ownership.

---

## 1. Webb's Depth of Knowledge (DoK) as a Boundary Firewall

A primary failure mode of contemporary LLM usage in academic settings is cognitive bypass—where students outsource high-order analytical tasks to the AI model. 

ARO formalizes task boundaries using **Norman Webb’s Depth of Knowledge (DoK)** taxonomy:

```
┌──────────────────────────────────────────────────────────────┐
│ Level 4: Extended Thinking (Synthesis, Critique, Stakes)     │ ◄── [HUMAN ONLY]
├──────────────────────────────────────────────────────────────┤
│ Level 3: Strategic Thinking (Rebuttal, Case Logic, Anomaly)  │ ◄── [HUMAN ONLY]
├──────────────────────────────────────────────────────────────┤
│ Level 2: Skill / Concept (Source Context, Outline Structure) │ ◄── [COLLABORATIVE]
├──────────────────────────────────────────────────────────────┤
│ Level 1: Recall & Reproduction (Citations, Terminology)      │ ◄── [AI ASSISTED]
└──────────────────────────────────────────────────────────────┘
