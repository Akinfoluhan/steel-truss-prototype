# Steel Truss Prototype — Capping the Interstate (CE2200 Statics)

This repository contains the written report and supporting materials for a CE2200 Statics final project focused on designing and testing a steel truss prototype for a community “cap” over an interstate to reconnect neighborhoods above Jefferson Street in Nashville.

## Project Overview

The project combines:

- Background research on how interstate highway construction impacted underrepresented communities and why “capping” projects are being used to reconnect neighborhoods.
- Structural analysis and truss design (method of joints + sections), with verification using a truss simulator.
- Physical construction of a steel truss prototype (welding/bolting) and load testing.

## Key Results (from testing + analysis)

- In testing, no members yielded; the first failure mode observed was buckling at a load of 667 lbs, with member CH failing first.
- The “community bridge” load-planning step used three scaled loads: landscaping (400 lb), community building (250 lb), and playground (170 lb).
- Load combinations 4 and 5 were recommended because they maintained structural integrity (no compression/tension failure), with combination 5 preferred for accessibility and layout.

## What’s in this repo

- `docs/project-prompt.pdf` — the original project description and rubric
- `docs/final-report.pdf` — the final written report (analysis, build process, results, recommendations)
- `media/` — project photos, figures, and diagrams
- `calculations/` — hand calculations, spreadsheets, or supporting math

## Tools / Methods Used

- Statics truss analysis (method of joints + method of sections)
- Buckling and yielding checks using standard stress/buckling relationships (as assigned)
- Truss simulator verification (Johns Hopkins Truss Calculator suggested by the assignment)
- Prototype fabrication using welded/bolted connections and load testing

## Future Improvements

- Improve joint configuration to better match the theoretical model and reduce unexpected weaknesses at connection points.
- Validate exact material properties used in the prototype to tighten agreement between analytical predictions and lab results.
- Expand the community-load study with additional load combinations and/or serviceability considerations.

## Report

- Final report: `docs/final-report.pdf`
- Project prompt: `docs/project-prompt.pdf`

## Collaborators
- [Parker Violand](https://www.linkedin.com/in/parker-violand/)
