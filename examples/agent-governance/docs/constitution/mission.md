# Mission

## Purpose

Deliver a small service that transforms validated input into a documented,
observable result for internal engineering users.

## Users

- **Service client:** sends requests and consumes the documented response.
- **Operator:** deploys, monitors, and recovers the service.
- **Maintainer:** changes behavior while preserving the service contract.

## In Scope

- The service API, validation rules, observability, and deployment scripts.
- Documentation needed to operate and maintain the service.

## Out of Scope

- Customer identity systems, billing, raw data ingestion, and unrelated
  infrastructure.
- Silent changes to public behavior without an acceptance-criteria update.
