# Racing Challenge & AI Pricing Platform

## P — Problem & constraints

Coordinate racing data, challenge standings and calculated pricing in a browser platform while coping with recurring external updates and integrity/recovery requirements.

## A — Architecture & decisions

Next.js frontend -> FastAPI service -> persistence/integration layer, with scheduled jobs for refresh/recovery and Monte Carlo logic for calculated prices.

## C — Contribution & delivery

Implemented operational UI surfaces, backend schemas/routing, ingestion/update logic, challenge calculations, result-integrity handling and deployment/backup runbooks.

## E — Evidence & outcomes

Private source and CI verify the maintained application layers and core engineering capability. Public claims are limited to what the code/build evidence supports.

## Confidentiality

Infrastructure details, live data, client identity and source implementation remain private.
