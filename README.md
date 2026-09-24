# Booking

Booking is a planned backend for a coworking space. It will help members browse meeting rooms, reserve rooms for specific time intervals, view their reservations, and cancel upcoming reservations.

> **Portfolio project under development.** This repository currently contains project documentation only. The capabilities and technology choices below are planned and are not presented as completed features.

## Planned Capabilities

- Allow members to browse available meeting rooms.
- Allow members to reserve a room for a time interval.
- Allow members to view their reservations.
- Allow members to cancel upcoming reservations.
- Allow administrators to manage meeting rooms.
- Prevent overlapping active reservations, including overlapping simultaneous requests.

## Planned Stack

- Plain JavaScript, with no TypeScript.
- Node.js and Express for the backend.
- PostgreSQL for persistence.
- Plain SQL for database queries.
- Automated tests for the application behavior.

## Roadmap

1. Define the room, member, and reservation domain model.
2. Set up the Node.js and Express backend structure.
3. Add PostgreSQL persistence and plain SQL queries.
4. Implement member reservations, cancellations, and administrator room management.
5. Enforce overlap prevention for active and simultaneous reservations.
6. Add automated tests and refine the project documentation.

## Product Brief

See the [product brief](docs/product-brief.md) for the project direction and requirements.
