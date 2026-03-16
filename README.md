# Architecture
Multi Cluster Deployment with GitOps using ArgoCD


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
EKS Cluster-1   EKS Cluster-2
   │               │
Application     Application
