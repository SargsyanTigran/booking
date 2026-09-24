# Product Brief

## Product

Booking is a backend for a coworking space's meeting-room reservations.

## Users and Capabilities

Members will be able to:

- Browse active meeting rooms.
- Create bookings for a room and time interval.
- View and manage their own bookings.
- Cancel only their own upcoming reservations.

Administrators will be able to:

- Create rooms.
- Update rooms.
- Deactivate rooms.

## Business Rules

- A booking's end time must be later than its start time.
- New bookings cannot start in the past.
- Booking timestamps must include a timezone offset and be stored consistently in UTC.
- Active reservations for the same room cannot overlap, including simultaneous booking requests.
- Back-to-back bookings are allowed when one booking ends at the exact time another begins.
- Canceled reservations do not block room availability.
- Members can cancel only their own upcoming reservations.
- Deactivating a room prevents new bookings while preserving its existing reservations.

## Initial Scope

The following are outside the initial scope:

- Payments.
- Recurring reservations.
- Frontend development.

## Planned Stack

- Plain JavaScript only; TypeScript will not be used.
- Node.js.
- Express.
- PostgreSQL.
- Plain SQL.
- Automated tests.

## Scope

This repository setup covers project documentation only. The application will be implemented in a later phase, and application dependencies will not be installed as part of this setup.