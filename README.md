# Wealth Batch

Spring Batch application for durable, restartable Wealth background processing.

## Responsibilities
- Scheduled and operator-triggered batch jobs.
- Reconciliation and bulk processing.
- Restartable steps, checkpoints and failure recovery.
- Idempotent writes and bounded concurrency.
- Persistent Spring Batch JobRepository metadata in PostgreSQL.

## Technology baseline
- Java 21
- Spring Boot 3.5.x
- Spring Batch 5.x (managed by Spring Boot)
- Maven Wrapper
- PostgreSQL-backed JobRepository
- Docker image targeting OCI Ampere `linux/arm64`

## Development
The `development` branch is the only branch intended for automatic Oracle Cloud development deployment. Production deployment from `main` is not configured.

Do not commit secrets, database URLs, private keys, tokens, or personal financial data.
