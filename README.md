# Racing Challenge & AI Pricing Platform — Engineering Case Study

> **OSYSTIC ENGINEERING CASE STUDY · PUBLIC SHOWCASE · SANITIZED · PORTFOLIO-SAFE**

## Problem & constraints

A racing challenge platform needed to coordinate scheduled race-data processing, participant/result management, challenge scoring and an operational browser experience while keeping calculated pricing and data integrity consistent across recurring updates.

Key constraints evidenced by the private source include:

- separate frontend and backend services
- recurring external-data ingestion/update jobs
- persistent meeting, race, participant and result state
- jockey/driver challenge workflows
- calculated Monte Carlo pricing
- operational database backup/recovery requirements
- dependency on external racing-data sources

## Architecture & decisions

The private delivery uses:

- Next.js 14 / React frontend
- FastAPI backend
- SQLAlchemy-backed persistence with SQLite in the delivered implementation
- data-ingestion/scraper modules
- scheduler jobs for result updates, price refresh, meeting state, missed-result recovery and integrity checks
- Monte Carlo pricing logic

## Contribution & delivery

OSYSTIC's retained engineering source includes meeting/live/result views, jockey and driver challenge surfaces, bet/settings interfaces, backend schemas/routing, scheduled processing, result-integrity utilities and operational handover documentation.

## Evidence & outcomes

Repository CI validates the maintained frontend build and backend Python baseline. The source also directly evidences scheduled processing, result-integrity controls and Monte Carlo pricing code.

No revenue, win-rate, prediction-accuracy or client-result percentage is asserted because the reviewed evidence does not support such a public claim.

## Confidentiality

The public artifact excludes client identity, production IP/hostnames, credentials, live database contents, private endpoints and protected logs/screenshots.


## Public vs. private repository boundary

This repository contains **sanitized public proof only**. The confidential delivery/source repository remains private. Implementation source, client identity, credentials, private infrastructure, payment/contract details, private conversations, and protected raw evidence are intentionally excluded.

Public claims here are limited to the evidence-backed engineering information documented in this repository.
