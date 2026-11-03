# Deployment Notes

Historical Kubernetes notes mention namespace `veda-glucocare`, application pods, PostgreSQL StatefulSet pod `postgres-0`, a PostgreSQL Service, and a 10Gi gp3 PVC. These are not current cluster-state claims.

Validate live resources, probes, non-root containers, resource requests/limits, secret management, PostgreSQL network restrictions, backups/restores, and avoid public database exposure.