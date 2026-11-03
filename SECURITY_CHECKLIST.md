# Security Checklist

## Repository
- [ ] No credentials, API keys, JWTs, OTPs, private keys, or database passwords.
- [ ] No identifiable patient data or screenshots.
- [ ] Synthetic test fixtures only.
- [ ] Scan repository history for secrets.

## Application
- [ ] Authentication/authorization tests for all patient endpoints.
- [ ] Patient identity from authenticated context.
- [ ] Input validation and safe errors.
- [ ] Rate limiting considered.
- [ ] Logs exclude sensitive data.
- [ ] HTTPS enforced.

## Health data
- [ ] Retention/deletion policies defined.
- [ ] Staff access restricted by role and need.
- [ ] Encryption in transit/at rest where appropriate.
- [ ] Legal, privacy, and clinical review before production.
- [ ] No medical-device or clinical-decision claims without applicable validation/authorization.