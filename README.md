# Shane Thomas

Platform-focused DevOps engineer — 10+ years automating infrastructure,
building CI/CD pipelines, and running hybrid cloud + air-gapped environments.
Certified Kubernetes Administrator (CKA). U.S. Army veteran (radar
maintenance on a $800M missile defense system).

**Core stack:** Kubernetes · Terraform · Ansible · Docker · ArgoCD ·
Azure / AWS · Linux (RHEL, Debian / Ubuntu, Proxmox)

## Projects worth a look

- **[gitops-helm-argocd-demo](https://github.com/shanecthomas/gitops-helm-argocd-demo)**
  — full CI/CD loop: lint → test → build → ephemeral dev deploy (Kind) →
  gated prod deploy (real AKS via Terraform + ArgoCD) → automatic teardown.
  Everything's visible in the Actions logs without running anything yourself.
- **[internal-dev-platform-demo](https://github.com/shanecthomas/internal-dev-platform-demo)**
  — self-service internal developer platform: a Backstage form request
  becomes a Crossplane claim, which provisions a real Azure resource.
- **[configsentry](https://github.com/shanecthomas/configsentry)**
  — config drift auditor for Linux hosts; baseline/check workflow, JSON
  output for CI (file integrity, SSH hardening, sysctl, etc.)
- **[apt-snapshot-revert](https://github.com/shanecthomas/apt-snapshot-revert)**
  — Atomic, tested apt package-version snapshot/rollback for Ubuntu —
  safety guards, held-package handling, cross-generation drift recovery

[LinkedIn](https://linkedin.com/in/shane-carther-thomas)
