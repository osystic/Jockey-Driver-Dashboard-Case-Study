# Racing Challenge & AI Pricing Platform

## P — Problem & constraints

Coordinate racing data, challenge standings and calculated pricing in a browser platform while coping with recurring external updates, persistent race/participant state, integrity checks and recovery requirements.

## A — Architecture & decisions

The private delivery separates a Next.js 14 / React frontend from a FastAPI backend. SQLAlchemy-backed persistence uses SQLite in the delivered implementation. Data-ingestion modules and scheduled jobs handle result updates, price refreshes, meeting state, missed-result recovery and integrity checks. Monte Carlo logic provides calculated pricing inside the backend workflow.

## C — Contribution & delivery

OSYSTIC implemented meeting/live/result views, jockey and driver challenge surfaces, settings interfaces, backend schemas/routing, ingestion/update processing, challenge calculations, result-integrity utilities and deployment/backup runbooks.

## Engineering highlights

- Separated browser presentation from backend domain and persistence logic.
- Added recurring jobs for result refresh, price refresh, meeting-state updates, missed-result recovery and integrity verification.
- Retained explicit result-integrity and recovery utilities for incomplete external feeds.
- Implemented Monte Carlo pricing as a defined backend calculation path.
- Preserved operational backup/recovery documentation alongside application source.

## Technology stack

- Next.js 14
- React
- FastAPI
- Python
- SQLAlchemy
- SQLite
- Scheduled background processing
- Data-ingestion modules
- Monte Carlo pricing logic

## E — Evidence & outcomes

Private source and CI verify the maintained frontend/backend layers, scheduled processing, integrity/recovery utilities and pricing implementation. Public claims are limited to evidence-backed engineering capability.

## Confidentiality

Production infrastructure, live database content, credentials, client identity, private endpoints and protected logs/screenshots remain private.
