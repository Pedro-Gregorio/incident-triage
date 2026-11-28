# Incident Triage (WIP)

The goal of this project is to create a full, scalable system that mimics a production-like environment, where user reported incidents are found, reported and analyzed.

## What it does

Users can report an incident through an API, which is then categorised and stored. Events go through Kafka, and traces and metrics show what happened.

## Technologies Used (and planned)

- Java 21
- Spring Boot 4
- PostgreSQL 17
- Docker
- Flyway
- Testcontainers
- Kafka
- OpenTelemetry
- AWS
- GitHub Actions

## To Do

- [ ] PostgreSQL and Flyway Migrations for incidents table
- [ ] Create Incident (POST /incidents) Endpoint
- [ ] Get Incident Details (GET /incidents/{id}) Endpoint
- [ ] Basic Incident Categorisation
- [ ] Kafka Event on Incident Creation
- [ ] Testcontainers for Happy Path Tests
- [ ] Open Telemetry Traces and Metrics
