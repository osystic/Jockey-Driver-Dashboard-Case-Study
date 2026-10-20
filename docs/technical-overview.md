# Technical overview

The private delivery uses:

- Next.js 14 / React frontend
- FastAPI backend
- SQLAlchemy-backed persistence with SQLite in the delivered implementation
- data-ingestion/scraper modules
- scheduler jobs for result updates, price refresh, meeting state, missed-result recovery and integrity checks
- Monte Carlo pricing logic

## Public engineering boundary

This overview describes sanitized architecture and engineering decisions only. Confidential implementation source and protected delivery material remain private.
