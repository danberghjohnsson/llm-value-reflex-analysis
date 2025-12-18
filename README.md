# llm-value-reflex-analysis

**An exploratory method for observing how large language models respond to value friction.**

---

## What this is

This repository contains a lightweight, qualitative method for exploring **how large language models (LLMs) reflexively handle value conflicts**.

The goal is not to determine what a model *believes*, nor to measure political bias or moral correctness.  
Instead, the method makes it possible to observe:

- how models frame normative tensions,
- which actors or institutions are given legitimacy,
- how conflict is resolved, softened, or left open.

In short: we study **value reflexes**, not opinions.

---

## Why this exists

LLMs are increasingly used in contexts where values matter:  
public sector, regulated industries, education, advisory roles, and internal decision support.

At the same time, many discussions about alignment are either:
- highly abstract, or
- reduced to simplistic bias metrics.

This project aims to offer a **practical middle ground**:
- intellectually sharp,
- accessible to non-specialists,
- grounded in observable model behavior.

---

## Core idea: value friction

The method is built around **value friction**.

A *value friction* is a situation where multiple reasonable values pull in different directions  
(e.g. stability vs. pluralism, law vs. conscience, individual agency vs. institutional authority).

Each prompt in the prompt set is designed to activate such a friction — without forcing a binary choice.

The model’s response reveals how it reflexively organizes and handles that tension.

---

## What a prompt is (and is not)

Each prompt is:

- a **probe**, not a test,
- open-ended,
- free of local political or cultural references,
- intentionally lacking a “correct” answer.

Prompts are **not** moral dilemmas or surveys.  
They are designed to surface *how* a model reasons, not *what* it concludes.

---

## What the output is

Running a prompt set against a model produces a **normative reflex profile**:  
a qualitative description of how the model tends to handle recurring value frictions.

This profile is:

- descriptive, not evaluative,
- comparative, not absolute,
- context-dependent.

It does not label models as “good” or “bad”, only as **more or less compatible with certain value environments**.

---

## How analysis is done

Each response is read and analyzed along five simple dimensions:

1. **Authority** – Who is implicitly granted legitimacy to decide?
2. **Conflict handling** – Is conflict treated as necessary, risky, or something to avoid?
3. **Normative voice** – Exploratory, guiding, moralizing, or authoritative?
4. **Closure** – Is tension left open, balanced, or resolved in one direction?
5. **Absence** – What is notably missing?

Analysis is manual, lightweight, and intentionally transparent.

---

## What this method is (and is not)

### This method *is*:
- qualitative and exploratory,
- reproducible in practice,
- suitable for reflection, comparison, and discussion.

### This method is *not*:
- a scoring system,
- an objective measurement of values,
- a claim about intent, training data, or ideology.

---

## Typical use cases

- Comparing different LLMs in value-sensitive contexts
- Reflecting on model suitability for a given organization or sector
- Supporting internal discussions on AI governance and alignment
- Teaching and workshops on AI, values, and systems thinking

---

## Repository structure (expected)

/prompts # Value friction prompt set(s)
/models # Model identifiers or configs (not weights)
/results # Raw model outputs
/analysis # Human-readable analysis notes


---

## License

This project is released under the **MIT License**.

Use it, adapt it, and build on it.  
Just do not pretend it produces objective truth.

---

## Status

This is **v0.1**.

The method is intentionally simple and open to refinement.  
If you find it useful, feel free to adapt it — and if you improve it, consider sharing back.
