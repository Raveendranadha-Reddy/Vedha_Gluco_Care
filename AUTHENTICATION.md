# Authentication and Authorization

Earlier logs showed a Spring Security chain containing `JwtAuthenticationFilter`. This only confirms a JWT-related filter appeared in the observed configuration.

Not confirmed: claims, signing algorithm, key management, expiry, refresh flow, token storage/rotation, logout/revocation, or password hashing configuration.

Checklist: protect routes; resolve patient identity from authenticated principal; enforce roles/ownership; validate signature, issuer, audience, expiry; keep secrets out of source; test expired, malformed, revoked, and unauthorized tokens.