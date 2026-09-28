# Kubernetes Platform GitOps

Enterprise GitOps infrastructure repository managing deployments via Helm and ArgoCD.

## Layout
- `charts/`: Modular Helm charts for event gateway and backend services.
- `manifests/`: Base network policies, RBAC roles, and cluster resource quotas.
- `apps/`: ArgoCD root application definitions (Application-of-Applications pattern).
