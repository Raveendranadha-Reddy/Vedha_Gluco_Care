# Backend Progress

Prior notes indicate appointment entity, repository, DTOs, service, and controller work.

Previously discussed routes:
- `POST /api/v1/patients/me/appointments`
- `GET /api/v1/patients/me/appointments`

Doctor verification and `BOOKED` status were discussed. Maven compile was reported successful at that time. A GET request reportedly timed out; root cause was not confirmed.

Glucose service notes: patient resolved from authenticated user; glucose value/unit/type/time/notes stored; up to 100 readings listed newest-first; latest-reading lookup discussed. Confirm exact implementation in current source.

Verification: run tests, check validation/errors, patient authorization, migrations/schema consistency, and reproduce the timeout.