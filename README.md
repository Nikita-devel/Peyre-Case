<sub>[← All projects](https://github.com/Nikita-devel)</sub>

# Peyre S.A. — custom production apps for a sheet-metal manufacturer

> Two in-house apps built during my July 2026 internship at Peyre S.A. (sheet-metal fabrication, 42 staff, Toulouse) and **used daily** by the methods office and the shop floor.

**📄 Case study (FR):** https://nikita-devel.github.io/Peyre-Case/

This repository hosts the public case study page only. The application source code is proprietary and kept private.

## Problem

- Shop-floor planning lived on a whiteboard, rewritten every week, with no history.
- Bar cutting was decided by hand: no optimisation, avoidable metal offcuts.
- Decisions made in the methods office reached the shop floor late.

## Solution

| App | What it does |
|---|---|
| **Cutting optimiser** | Extracts part data from PDF job files and computes the bar cutting plan (1D bin packing, Best Fit Decreasing). Every plan is reviewed on a check screen before it goes to the shop floor. |
| **Production planner** | Replaces 3 spreadsheets and the whiteboard: the office sets deadlines, operators allocate hours day by day, with a visual overload alert. |

## Results

| Metric | Value |
|---|---|
| Time to prepare a job file | 30 min → 3 min |
| Offcut sorting time saved | ≈ 30 h / year (estimate) |
| Material offcuts avoided | 10–20 % (estimate) |

## Stack

Python · Pandas · Streamlit · SQLite · PDF parsing

## My role

Full cycle, alone: requirements with operators, SQLite data model, build, deployment, documentation and user training.

---

Nikita Chumak · [LinkedIn](https://linkedin.com/in/chumak-nikita) · nikita.chumak@insa-lyon.fr
