---
title: "Hardening EKS Clusters & Runtime Security"
date: 2025-12-26
phase: "Phase 4: Kubernetes Security"
tags: ["EKS", "Falco", "Karpenter", "DevSecOps"]
---
The challenge was securing a multi-tenant EKS environment. I implemented a **Zero Trust** architecture using **Istio Service Mesh** for mTLS and **Falco** for runtime threat detection.

* **Result:** Reduced attack surface by 60% by eliminating public endpoints.
* **Automation:** Integrated OPA Gatekeeper to enforce "No Root" policies on all pods.