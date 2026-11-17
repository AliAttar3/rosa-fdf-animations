# ROSA storage and IBM Fusion Backup & Restore: animations

Self-contained HTML animations (no build step, no external dependencies).

## ROSA storage across availability zones

What happens to persistent data in an AZ outage on Red Hat OpenShift Service on AWS (ROSA).

- `index.html`: all three scenes, with tabs
- `scene1-ebs-only.html`: EBS only
- `scene2-fdf-on-ebs.html`: FDF on EBS
- `scene3-mixed-cluster.html`: mixed cluster

## IBM Fusion Backup & Restore in action

- `fusion-backup-restore.html`: four tabs: software-defined backup & restore (any storage, spread across nodes), full / incremental / CBT backups, hub and spokes, and recipes

## Notes

Each page has auto-play and click-through modes. These are simplified teaching models,
not official guidance. Confirm ROSA and FDF specifics with the Red Hat documentation, and
Fusion Backup & Restore specifics with the IBM Fusion documentation.
