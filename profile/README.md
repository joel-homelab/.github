<div align="center">

# HomeLab

**Kubernetes homelab for building production-style apps!**  
**Exploring cloud-native open source projects, and advancing toward Kubestronaut.**

[![Talos](https://img.shields.io/badge/Talos-FF7300?&style=plastic&logo=Talos&logoColor=white)](https://www.siderolabs.com/talos-linux)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://docker.com)
[![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)](https://helm.sh)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?&style=plastic&logo=Argo&logoColor=white)](https://argo-cd.readthedocs.io/)
[![Kargo](https://img.shields.io/badge/Kargo-E09050?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAACv0lEQVR42m2SS0hUYRxHf//v3rlzR0ebB0NUMyU+xsryjVlaZpFSFvRgxBAzKZWIiFa5iAyKlm1apRDRrglDXBVEIhE0vVAzDTMpncbHpOPodZzX/b4WtQjqLA+c3QH+hXk8kAAgx2be9qCt/OvVurwz3j/OAuRnqXD9pyMQY0BnJ/O27hjg3XXi1j5jGwBcrs649vZmbayrpdgn/Z1kZ8NYomPzrqigzPGBUnvpoRuPjEfFe6k4WiFGbBePFd5JMynS9+BygADAA0iP0Skq3Pf3RMqbn2qUsmb79ISbnXkOU90VItmO+vdNKHalYNQfTvT6Jg8SAOb1gBp6mM45x4G9u73n9md4iqwxJFYW4V9cw5xYp9e4zWJw8mfA+2ri0kNfoE8GwOsfAwDf2HEkp6U2Xz5iVeZ1njTRJucm5nIKMJ5EnJP8ctQ//NAX6OvvrJLJbcbW6uLNHTWFruNlmbZ1qlFBKMoRS+iwp6lI6hwAQTVIOue6dNvra7/bP9UlZTmUyWn/YtnsakI90dyaFGBMjoVhNhA4GBgBjICErsNiNiKpC/cj33S33NTYEAmFwsbKqgrZ6i6TkVuGxEIAocFnEAvTIIMREAKMGNOiSZHrtOWeKrBVSZU7s0TlnpLD1Qerk9pymMaGhwmqGY68csSC09BXQyBJBgHgQnBrqsKC4bVl6cW7MZ//88ctJoNUEtYilIjH4XJugEFRYbBuRNQ/BsF1AATOuVAVWYRXYymSEALNlzp6LXJyJM2cUmC1O2wRTRMOuwWkpgsR17i+MCUU1USpRpmlqjIbDyytl4lIvLt3z1Da3t6Tm5OZf/bC+euIJTgYEWQDKdlF+PFtCFPzS5gNaXNffoReDYzO3P99jgfS9vkqGovPFDWePtmXbrOkRrRIZHlldXYhGJyYHHo9NDzhf/P8a+QDgCAA/ALvJS2dDQq04wAAAABJRU5ErkJggg==&logoColor=white)](https://argo-cd.readthedocs.io/)
[![Istio](https://img.shields.io/badge/Istio-466BB0?&style=plastic&logo=Istio&logoColor=white)](https://istio.io/)
[![Kiali](https://img.shields.io/badge/Kiali-0090D0?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAB4UlEQVR42p2SO2iTcRTFz7n/75UmMVY6KDoUQUFFi0ptBbXoEC0KFaHQrU4uVqVjC/oZHdStQpdIFYIatIOT0KFCF4fqIjrUQQTxgQ98VZs0Jvn+t0MlxJQs3vFw7rkXzg9oNj09ToNC9PebBk2JSTUI1UE4U1vYnc26qa6+9jXdR9ez5g1lOUWVIPWfaALB1r3n6McOWuM7oArFQGDvFGan8rXLqmDixoe+4NbnkfjY3IC3fd99Gc5rcO3pBAGEoUqq+9gub0/vI7/z8EUA4Mbs69S7SCarwaq0+gnI4xxQXoTdf7LCSslNlubTv85snl5+D/A7j8yQvC7vq7xSibWmtTBfwadXVbx5FtkdvRa/v1JBLIo5TQAYDAMF4IhzXmGHJFJ7AsUfFq7n8OdHB8k2gyAh0EgQlRGpbrkQqiCXKQGgb+S5KmOyogbVBmGlRQiKoTxAS6ugUq7q6nVVLHyLUFqwoLEwHgz15aUMLQbDAID+icodCi3KBkdH3OL3acZTLtZuctC+08iLKUGyTQmFR4wrAOQyJQIoW1wmZPzvd8pE9u3xYOLLaHxsbsDvOHBPhu9qcPXJzfo6gvo6mgHQsq3rrHrJQ9a4DkghSSFvF2Yf5uvQa4LcqebI4X8hXwI0wLyiURtkIgAAAABJRU5ErkJggg==&logoColor=white)](https://kiali.io/)
[![Cilium](https://img.shields.io/badge/Cilium-E1272A?&style=plastic&logo=Cilium&logoColor=white)](https://cilium.io/)
[![Dex](https://img.shields.io/badge/Dex-0B1220?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABdklEQVR42l2SvUolQRCFT9+5/gyKKGogGyvIxRfwh81kQRARkwUjE3dfYAMTEwPxLQwFwUTEwFADAze6oYtgpKDgnUCX7qn9NqnRcQ40VDWnz6mqLkkSEOQApoFfKaVvno8BMxXvndt4tAc840gpbQC5mV0BB85pAaEKhoHz6oGZvQA3wKGTd/2+yluV/RdgBVgCfgDTtSpawHc+8FN1AH2NfAqY8njQzM6A0swuJElFUUyY2SHQA+aBzF0LoCjLcluSYowL7rhWKW97/Q/dbrff1Z9q/T4BOTCeUtqoBtqW9E9SKanV6XRySX/9VHiTpBDCs6RjYFPSq2KM8658B4z6sNaAP8AtsOouc8AZQIxxQUDbzB7NbL8xnDaQe5yb2bUb/Aayep+rwAhwCnwFBiWp1+uNm9ll7TvW6+oBGAAma4S7lNKyT3QR2AG2mtv2vofAEZ+x02ghSFJ9T0MIAWBI0rKkWUltM7vPsuxE0qskQgilJP0HQpfNU7ovlXoAAAAASUVORK5CYII=&logoColor=white)](https://dexidp.io/)
[![OpenBao](https://img.shields.io/badge/OpenBao-336D5C?&style=plastic&logo=OpenBao&logoColor=white)](https://openbao.org/)
[![Falco](https://img.shields.io/badge/Falco-00AEC7?&style=plastic&logo=Falco&logoColor=white)](https://falco.org/)
[![Cert-Manager](https://img.shields.io/badge/Cert--Manager-3060E0?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABt0lEQVR42lWSMWuUURBFz9zvEzYLGkmEgEgwiJJCsBBBlICNGhFsUtiKtV38IQZLWxuL1GJn0LWzsxFtsgmLQUOMxLBm992xeZH1VcNjmJl77g2AzAxAEVEy8yawDGwCBVgAehHxpvZFRDiYeJn5yPYD4BsgICQV23OS3kbE8+NFkZkCZoBnwDZwGrhu2wCSRsAn2wNgUdIqsB11wgsgbV+sp/0EupICsO0OsCOpZ3u+aZoVZeYp23/qWbfq9stA1P9LwBlJ12yflTTIzHMCbgAHtu9VqVOSUtJ6Zr4EhhHRraDuAIellKXW9kNJu7bHQB84sj2dmYdAsb0P7GfmEZBA0zTNSispKogd2x1JP6oVy7Z3q66TwHlgZHsESMArSaUSnAau2P4NrEpaAz5Kmpc0C3SBsaT1FuhVfVu2G0l7kp4AV4ED4Lbtz8BX4HsdvtFGxK9SShfYA6aAOWDD9gVJXdvvjuVI+lLt2D4OwKztNUlbtV4ATlSLjoCB7U1Ji8Ph8Gmn0+n/F7nxePw4Iu5XQFEpAsyUUt63bbv2L3ITIY+IcGYuAXdLKf2macY1SR8i4vVk31/g4Pve4xo6VgAAAABJRU5ErkJggg==)](https://cert-manager.io/)
[![Trivy](https://img.shields.io/badge/Trivy-09153D?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAACrklEQVR42jWSS2yMURxHf/977/eY6TCtarWLGdGHV3U0TSykS00oEokEG+IVJCJBgtiNBTsisUBIJGzQBRsRhDZWGo+ItkM6pVGm0moxk3l8873u36Isz0nO7gAAmEE8CAUAgAT/upvgTMd1Hm29xrmLCUAAAHgQihk0D5yetwB49GiMPy4/y5nmGc7EmDMx5uHGGc52n+fc7Xr8a/r7d0gCgKd3uGZDd8cBqeeOY8HiVlQA+H4IMKAMibgJ5H9OhmRcehFM3trYRWUqDp/YGVt44wJC1QZ3FXR5IhTsCMgoAQRoh8EiwIJ2A3IM8KpfSubhc/Lt0M37pcKalV0pLy/1gEUcF1otIyIHIIY2kkSGlKiOIrT6vJt8vOFkri9FicjEsFCNHZ2dP/W2vud6/457LIMBi8tLAKFAYophpmauV/a5D4OtyddOA+eL0yPUVjf+YUmjlZqd9UEyrhPJWX1i16Pqlq/fYsiDHx9qnjulN/vTXnNEoVDXHFXI5p0RaqsbH45G7E7D9D0dBKYPG7oiMdJ7kYX2vKW7T1PRDs1G4fklDQfSjPxx3KwwTYG52YDrFgkvlyO0LNPI+w72TBzA1oOHeNqomt0R5imPjCbTEL+9UBkErYg1VX2hyyVd075S4dWQi+6UjbmoHRSsQHWJAG8KLi2NGqiEusZlaJOZhGWLMGrUyrGsT5aNsL3d4KF3Hrjsu2C/+q7gIRkx2BIUfiq62loYl5YUodyy6cxAqViFDmTq+7eIGY/7lExIbUaUFfaSWW+ydjRERtuiyTZEQ1i9uiaqTs0/RMCRfT9Wj79Hejzrbg+0Uut7mMvpAC8rIBn6QUvMetBba1++srZpKASANFgAgwoApAEc2/urp6128sm61km94tlnXfv085Odb6Z61P+h+1kizeIvZ+1KgKvnIycAAAAASUVORK5CYII=&logoColor=white)](https://trivy.dev/)
[![Kyverno](https://img.shields.io/badge/Kyverno-206090?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABzElEQVR42l2SP2tUQRTFf/e+eclumigSiCzYCSEWYqFImggi/mlErCwsRBAEC3s/QGwEv4OdIgSDICF+AhfEJtptQFCrNbIi5r2Ze2zeA9lp7jBzzsw95x6YW5KSJJc0krTWndXzOJ8jmZllMwvgVkQ8BDCztr/vsdb/Yma5218FbkfEH3cPYBl4D7wys1bSopkd9cQLwKNSyriqqlPAi1LKJTNbb5pmazAY3AN+R8RaROzUdb3tkhwYA/tmdifnvGtmn6qqSu6+OBwOD4DtiLgOzFJK7ySZd3pqYBQRT1JKOznnu6WUiIhfki4DHyLiOdACIzNTb8p6KeUZwGQyGZRS3kj6KulLKeWjpBMAOefHbdveBEidScvuftC27Y2U0hGwD7wtpUzNbBM4J2kBmAENgHcWXwOmKaUaOJ5z3gNWzeyiu78GjnVyZsCmJEtmJkmfgZed3r79b+6+ZGbjuVnXZiaXlIAFYNQlpk/JyZzzag/u01RKSZLqFBFP3X0hIq64+30za5qmOQ88cPeQ9NfM9iTVEbFVVdUhcNbd/Tuw4u4/u9e9rutZRCR3HwCHfdTcfQqsAD/6vjckLfXErp6WdOb/jEoaStoA+AfP9h9wF+Y6uAAAAABJRU5ErkJggg==)](https://kyverno.io/)
[![Fluentbit](https://img.shields.io/badge/Fluentbit-49BDA5?&style=plastic&logo=Fluentbit&logoColor=white)](https://fluentbit.io/)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?&style=plastic&logo=OpenTelemetry&logoColor=white)](https://fluentbit.io/)
[![Prometheus](https://img.shields.io/badge/Prometheus-red?&style=plastic&logo=Prometheus&logoColor=white)](https://prometheus.io/)
[![Grafana](https://img.shields.io/badge/Grafana-orange?&style=plastic&logo=Grafana&logoColor=white)](https://grafana.com/)
[![Thanos](https://img.shields.io/badge/Thanos-6D41FF?style=flat&logo=thanos&logoColor=white)](https://thanos.io/)
[![Golang](https://img.shields.io/badge/Golang-00ADD8?style=plastic&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAACB0lEQVR42p2PTUtUYRiGr/edM87osRmdUZMhlBkwsSgY+yDd1EIhCrQsqE2bwD/gD3AThBC0KoLCTWW6KGrXJgSnwEJFaaAm03BS0jTT0clR55z3aZFGH7ioa/PADdd98yiAeDxePTo2lm6qjwYXVXmb5fftc7RlK6W0dp2sbKwlS83ik2cjHzLxhobq0cHBtDp66uxtu6LyYnZ2OukGQuWRw401vkgVpSUhBFhdXWElPcHnoRfjvs3cnD9UXp9bmH+sTnZ0Ss2Fy2Q+TtF6aD9HomVmAeTREigDTUGoslCJ+bzuHxwhEAqTun8TT3Vtnc4Xlzacb22WcxVFbMxM66G+Hu3fHdUHCy3dZKPfJwbU+vhrY59odlOJAXcpOXydCISPtXdkXmZdcUXM3d4+AaR7+J3MiogjIqdbWqSmsszcW3alsb0jE4GwDsdiETtYUpR0NBrDpbYzTLx9Q+LhA7qudOEBervv0DPwirTRFAeDRbtieyJWzllzCzCSysGNb4ZowEflzDhVqX4srXn+dC9zx9uYdCtYXgctRlzHcS0AAXwKJjcUqa+C6Bid126RN8LVTxrPF4PXcSm0vQg/sLYuAhRoKATydQfozS5jtMKuDeLNC65Hb0nyu7gduYBn0zDlDQDg3zS4Sv1c4s/F3wqUwq/4pf9vrB3yHYVtNP+M+j9Rbb3wHWmV1F0rvNSTAAAAAElFTkSuQmCC&logoColor=white)](https://go.dev/)
</div>
---

# Homelab v0

> A GitOps-driven Kubernetes platform on **multi-node Talos Linux**, running as VMs on an Apple Silicon Mac Studio. Built to mirror an enterprise stack and to prepare for CNCF certifications.

---

## Contents

- [Overview](#overview)
- [Stack at a glance](#stack-at-a-glance)
- [Design principles](#design-principles)
- [Repository structure](#repository-structure)
- [Bootstrap order](#bootstrap-order)
- [GitOps: the seeder hierarchy](#gitops-the-seeder-hierarchy)
- [Kargo: hydration and the branch model](#kargo-hydration-and-the-branch-model)
- [Observability and alerting](#observability-and-alerting)
- [CI (GitHub Actions)](#ci-github-actions)
- [Secrets hygiene](#secrets-hygiene)
- [Roadmap](#roadmap)
- [Notes and decisions](#notes-and-decisions)

---

## Overview

This repo is a **monorepo**. A single `kubectl apply` bootstraps an ArgoCD app-of-apps tree that installs and manages every platform component. Promotable workloads flow through **Kargo** (dev → staging → prod), with fully-rendered manifests committed to per-stage branches so every change is reviewable as a plain-YAML diff.

The cluster runs as **three Talos VMs** (1 control-plane + 2 workers) under UTM/QEMU, bridged to the LAN so Cilium can announce LoadBalancer IPs on the local network.

---

## Stack at a glance

| Layer | Tool | Why |
|-------|------|-----|
| OS / cluster | **Talos** (via talhelper) | Immutable, API-driven, GitOps-native machine config |
| CNI · L3/4 | **Cilium** | eBPF dataplane, kube-proxy replacement, LB IPAM + L2, Hubble |
| Mesh · L7 | **Istio** | mTLS, routing, retries on top of Cilium |
| CD | **ArgoCD** | App-of-apps, self-healing, sync-waves |
| Promotion | **Kargo** | Watches Helm chart bumps, hydrates + promotes across stages |
| CI | **GitHub Actions** | Lint, schema-validate, render diffs on PR |
| Policy | **Kyverno** | Admission policy **and** image verification (cosign) |
| Secrets | **OpenBao + ESO** | Open (MPL-2.0) Vault fork; ESO syncs to native Secrets |
| Certs | **cert-manager** | LE DNS-01 for UIs, internal CA for the rest |
| Metrics | **Prometheus** | Direct scrape; rule evaluation |
| Logs | **Fluent Bit → Loki** | Lightweight agent, BTP-authentic |
| Traces | **OTel Collector → Tempo** | Standard trace pipeline |
| Dashboards | **Grafana** | Modern Explore + trace↔log correlation |
| Alerting | **Alertmanager → ntfy** | CNCF-native, config-as-code |
| Runtime security | **Falco + Trivy-operator** | Syscall detection + image/config scanning |
| RBAC | **rbac-manager** (Fairwinds) | Declarative RBAC via a single CRD |
| Storage | **local-path** | Simple v0 StorageClass (Longhorn later) |

---

## Design principles

1. **One repo, directory-scoped boundaries.** Clean per-domain folders so a later `git filter-repo` split is mechanical, not a migration.
2. **Two app categories, deliberately separated.**
   - `platform/` — cluster **singletons** (Cilium, cert-manager, OpenBao…). One instance each, tracked by Argo directly from `main`. Nothing to promote.
   - `apps/` — **promotable** workloads that flow dev → staging → prod through Kargo and render to per-stage branches.
3. **Super-seeder → seeders → child apps.** A single `kubectl apply` bootstraps the whole tree.
4. **Hydration is visible.** Kargo renders Helm/Kustomize to plain YAML on stage branches; the PR diff between branches *is* the hydrated-manifest view.

---

## Repository structure

```text
homelab/
├── README.md
├── Taskfile.yaml                       # optional: wraps the by-hand bootstrap steps
│
├── .github/workflows/
│   ├── lint.yaml                       # yamllint · kubeconform · helm lint
│   ├── render-diff.yaml                # helm template / kustomize build → PR diff comment
│   └── talos-validate.yaml             # talhelper validate · talosctl validate
│
├── talos/                              # STEP 1 — substrate (talhelper)
│   ├── talconfig.yaml                  #   topology: 1 cp + 2 workers, arm64
│   ├── talenv.yaml                     #   pinned Talos + Kubernetes versions
│   ├── patches/
│   │   ├── cni-none.yaml               #   cni: none + proxy: disabled (Cilium owns L3/4)
│   │   └── kubelet.yaml
│   └── clusterconfig/                  #   talhelper output — SOPS-encrypted or gitignored
│
├── bootstrap/                          # applied BY HAND, once, to reach GitOps
│   ├── README.md                       #   exact apply order
│   ├── cilium/values.yaml              #   STEP 2 — CNI before pods schedule
│   ├── argocd/values.yaml              #   STEP 4 — install Argo itself
│   └── root-app.yaml                   #   ★ SUPER-SEEDER — the single kubectl apply
│
├── clusters/homelab/
│   ├── seeders/                        # ★ SEEDERS — one App per platform domain
│   │   ├── 00-networking.yaml          #   → platform/networking    (sync-wave 0)
│   │   ├── 10-storage.yaml             #   → platform/storage       (wave 1)
│   │   ├── 20-cert-manager.yaml        #   → platform/cert-manager  (wave 2)
│   │   ├── 30-secrets.yaml             #   → platform/secrets       (wave 3)
│   │   ├── 40-policy.yaml              #   → platform/policy        (wave 4)
│   │   ├── 50-observability.yaml       #   → platform/observability (wave 5)
│   │   ├── 60-mesh.yaml                #   → platform/mesh          (wave 6)
│   │   ├── 70-security.yaml            #   → platform/security      (wave 7)
│   │   ├── 80-rbac.yaml                #   → platform/rbac          (wave 7)
│   │   └── 90-kargo.yaml               #   → platform/kargo         (wave 8, last)
│   └── sync-waves.md
│
├── platform/                           # SINGLETONS — Argo tracks from main
│   ├── networking/                     #   Cilium values · LB IPPool · L2 policy
│   ├── storage/                        #   local-path-provisioner
│   ├── cert-manager/                   #   LE DNS-01 issuer + internal CA issuer
│   ├── secrets/                        #   openbao/ (k8s auth) · eso/ (ClusterSecretStore)
│   ├── policy/                         #   kyverno/ + policies (verifyImages, baseline)
│   ├── observability/                  #   prometheus · grafana · loki · tempo
│   │                                   #   · fluent-bit · otel-collector · alerting
│   ├── mesh/                           #   istio: base · istiod · gateway
│   ├── security/                       #   falco · trivy-operator
│   └── rbac/                           #   rbac-manager
│
├── apps/                               # PROMOTABLE workloads — Kargo-managed
│   └── podinfo/
│       ├── base/                       #   Helm values / Kustomize base (the "source")
│       └── stages/                     #   dev / staging / prod overlays
│
├── kargo/                              # promotion model (added LAST)
│   └── projects/apps/
│       ├── project.yaml                #   stages = namespaces
│       ├── warehouse-podinfo.yaml      #   subscribes to Helm chart version bumps (GHCR)
│       └── stages/
│           ├── dev.yaml                #   auto-promote on new version
│           ├── staging.yaml            #   auto after dev verifies
│           └── prod.yaml               #   manual gate
│
└── stages/README.md                    # explains the rendered-branch pattern
```

---

## Bootstrap order

Only steps **1, 2, and 4** are by-hand. Everything from step 5 on is Argo-managed via seeders.

| # | Step | Path | Notes |
|---|------|------|-------|
| 1 | Talos VMs | `talos/` | talhelper; `cni: none`, kube-proxy disabled |
| 2 | Cilium CNI | `bootstrap/cilium/` | by hand — nothing schedules without it |
| 3 | StorageClass | `platform/storage/` | local-path for v0 |
| 4 | ArgoCD + super-seeder | `bootstrap/argocd/`, `bootstrap/root-app.yaml` | the pivot to GitOps |
| 5 | cert-manager | `platform/cert-manager/` | LE DNS-01 + internal CA issuers |
| 6 | OpenBao + ESO | `platform/secrets/` | k8s auth; unseal path documented |
| 7 | Kyverno | `platform/policy/` | `verifyImages` replaces Portieris |
| 8 | Observability | `platform/observability/` | Prometheus scrape · Fluent Bit→Loki · OTel→Tempo |
| 9 | Istio | `platform/mesh/` | L7 mesh on top of Cilium |
| 10 | Falco · Trivy · rbac-manager | `platform/security/`, `platform/rbac/` | |
| 11 | Kargo | `platform/kargo/` + `kargo/` | last — stages must exist first |

---

## GitOps: the seeder hierarchy

<details>
<summary><b>How the app-of-apps tree is wired</b></summary>

<br>

- **Super-seeder** (`bootstrap/root-app.yaml`) — the *only* thing you `kubectl apply` after Argo is up. Its source is `clusters/homelab/seeders/`; it deploys nothing but the seeders.
- **Seeders** (`clusters/homelab/seeders/*.yaml`) — one Application per platform domain, each pointing at a `platform/<domain>/` directory and carrying a **sync-wave** so ordering is deterministic (networking → storage → secrets → …).
- **Child apps** (`platform/<domain>/app.yaml`) — the actual Helm/Kustomize installs.

Adding a component = adding a folder under `platform/` and one seeder entry. Everything below the super-seeder is declarative and self-healing.

</details>

---

## Kargo: hydration and the branch model

Kargo renders into **git branches you diff**, not a folder you eyeball:

- **`main`** — the *source*: Helm charts, values, Kustomize bases.
- **`env/dev` · `env/staging` · `env/prod`** — Kargo runs `helm template` / `kustomize build` (**hydration**) and commits fully-rendered plain YAML here, one branch per stage.
- **ArgoCD Applications for `apps/` point at the `env/*` branches**, so Argo applies pre-rendered manifests with zero Helm logic at apply time.

Promotion is a git commit from one env branch to the next — the PR diff shows the exact hydrated-manifest change before it hits the cluster. **That diff is the visualization.**

```text
new Helm chart version pushed to GHCR
        │
        ▼
Kargo Warehouse detects the bump            (warehouse-podinfo.yaml)
        │
        ▼
Stage: dev      hydrate → commit env/dev     → Argo syncs → podinfo-dev
        │       (auto-promote; optional AnalysisRun verifies vs Prometheus)
        ▼
Stage: staging  hydrate → commit env/staging → Argo syncs → podinfo-staging
        │
        ▼
Stage: prod     MANUAL gate → commit env/prod → Argo syncs → podinfo-prod
```

Stages map to **namespaces** on the one cluster — enough to learn the promotion model without multiple clusters.

---

## Observability and alerting

**Signals, kept in their lanes:**

- **Metrics** — Prometheus scrapes directly (no OTel hop). Storage stays single-Prometheus for v0; **Mimir** or **Thanos** is a later "learn horizontal scale" milestone, not a v0 dependency.
- **Logs** — Fluent Bit agent → Loki.
- **Traces** — OTel Collector → Tempo.
- **Dashboards** — Grafana as the daily driver (modern Explore + trace↔log correlation). **Plutono + Vali** can run in a separate namespace as a BTP-authentic reference, but Grafana is the primary.

**Alerting is CNCF-native:**

- **Prometheus** evaluates alerting rules (PromQL → firing alerts).
- **Alertmanager** handles routing, grouping, dedup, silencing, inhibition — defined as YAML in `platform/observability/alerting/`.
- **Receiver:** ntfy (self-hosted push) or a Discord/Slack webhook.
- Grafana Alerting is an optional later add if you want log-based alerts in the same UI. `kube-prometheus-stack` bundles Prometheus + Alertmanager + Grafana, so you get all three at once.

---

## CI (GitHub Actions)

CD is owned by Argo + Kargo, so CI only **validates and renders** — it never touches the cluster.

| Workflow | Does |
|----------|------|
| `lint.yaml` | yamllint, `kubeconform` schema validation, `helm lint` |
| `render-diff.yaml` | On PR, render affected paths and post the diff as a comment — catches breakage before Kargo hydrates |
| `talos-validate.yaml` | `talhelper validate` + `talosctl validate` for machine-config changes |

---

## Secrets hygiene

- `talos/clusterconfig/` holds machine secrets — **SOPS-encrypt** (age key or internal CA) or gitignore entirely.
- No plaintext secrets in the repo: only `ExternalSecret` / `SecretStore` CRs are committed; values live in OpenBao.
- The one secret that can't live in OpenBao (ESO's auth to OpenBao) is bootstrapped via **Kubernetes auth** — a ServiceAccount token, not a committed static token.

---

## Roadmap

- [ ] Talos VMs up via talhelper (bridged networking, arm64)
- [ ] Cilium CNI — kube-proxy replacement, LB IPAM + L2, Hubble
- [ ] StorageClass (local-path)
- [ ] ArgoCD + super-seeder
- [ ] cert-manager — LE DNS-01 + internal CA
- [ ] OpenBao + ESO (k8s auth)
- [ ] Kyverno + policy baseline
- [ ] Observability — Prometheus, Grafana, Loki, Tempo, Fluent Bit, OTel, Alertmanager
- [ ] Istio
- [ ] Falco + Trivy-operator, rbac-manager, exporters
- [ ] Kargo — warehouse + dev/staging/prod stages
- [ ] _Later:_ Longhorn, Thanos/Mimir, Kafka (Strimzi) as a learning workload

---

## Notes and decisions

<details>
<summary><b>Why these choices (and what was dropped)</b></summary>

<br>

- **Portieris dropped** — Kyverno's `verifyImages` does cosign/Notation signature verification natively; Portieris only adds value for legacy Notary v1.
- **OpenBao over Vault** — MPL-2.0 (truly open), API-compatible, LF-hosted. ESO integrates via the Vault provider; OpenBao's own operator is stalled and the project points users to ESO.
- **Cilium replaces MetalLB** — LB IPAM + L2 announcements cover LoadBalancer services. Requires **bridged** VM networking (Ethernet, not Wi-Fi) so the Mac host can ARP-resolve LB IPs. Carve the LB pool from an unused slice of the LAN subnet.
- **Grafana over Plutono** — Plutono *is* Grafana, frozen at 7.5-era Apache-licensed. AGPL only matters if you distribute/host for third parties, which a private homelab doesn't. Grafana keeps the modern trace↔log correlation.
- **No message broker in v0** — nothing in the platform needs one. Kafka via Strimzi is a later, deliberate learning workload.
- **rbac-manager caveat** — great for GitOps, but CKA/CKS test **native** RBAC. Use the CRD in the lab; keep hand-writing raw Roles/RoleBindings for the exam.

</details>

---

## Certifications

**Achieved**
- KCNA — Kubernetes and Cloud Native Associate
- AZ-900 — Microsoft Azure Fundamentals
- CKA — Certified Kubernetes Administrator
- 
**In Progress**
- CKAD — Certified Kubernetes Administrator
- CLF-C02 — AWS Certified Cloud Practitioner
- Path: **Kubestronaut**

---

<div align="center">

[LinkedIn](https://linkedin.com/in/joel-plourde) · [joel.plourde@linux.com](mailto:joel.plourde@linux.com) · Canada

</div>
