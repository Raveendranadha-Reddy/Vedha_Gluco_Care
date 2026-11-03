# Database Notes

Historical PostgreSQL notes mention database `vedhaglucocare` and role `vgc_app`. Do not commit credentials; use environment variables or a secret manager.

A previous schema-only export reportedly had 47 tables, 47 primary keys, 24 unique constraints, 48 check constraints, 71 foreign keys, and 43 standalone indexes. A separate audit mentioned 385 columns, 190 constraints, and indexes changing from 119 to 114. These may be different snapshots/counting methods and are not current verified metrics.

Generate a fresh schema-only dump, review migrations/schema drift, and never commit patient records.