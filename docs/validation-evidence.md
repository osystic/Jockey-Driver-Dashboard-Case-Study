# Validation Evidence

The canonical private repository contains:

- a Next.js 14 application;
- a FastAPI backend and explicit Python dependencies;
- scheduled processing modules;
- result-integrity/recovery utilities;
- Monte Carlo pricing logic;
- database persistence models;
- private deployment/backup documentation.

During modernization, CI exposed and helped correct two repository issues before acceptance: a missing lockfile assumption in the initial workflow and a missing theme-context module required by the frontend source. The final modernization PR passed both frontend and backend CI.

The public case study does not disclose production infrastructure or claim commercial/performance outcomes not supported by evidence.
