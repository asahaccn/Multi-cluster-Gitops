# Architecture
Multi Cluster Deployment with GitOps using ArgoCD


```text
Developer
   │
   ▼
Git Repository (GitOps Source of Truth)
   │
   ▼
ArgoCD Controller
   │
   ├───────────────┐
   │               │
   ▼               ▼
Cluster-1       Cluster-2
   │               │
Application     Application
```
