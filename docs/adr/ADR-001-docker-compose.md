# ADR-001

## Title

Use Docker Compose as Container Orchestrator

---

## Status

Accepted

---

## Context

The HomeLab requires an easy way to deploy multiple services while keeping configurations version-controlled.

---

## Decision

Docker Compose will be used for all application deployments.

---

## Consequences

### Positive

- Easy deployment
- Easy backup
- Git friendly
- Beginner friendly

### Negative

- Not suitable for large-scale orchestration
- Manual scaling

---

## Alternatives Considered

- Kubernetes
- Podman
- LXC