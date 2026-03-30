# K8s Assignment 7 — Node Scheduling & Pod Management

Kubernetes lab covering core scheduling and pod lifecycle concepts.

## Topics

| # | Topic | Key Field / Resource |
|---|-------|----------------------|
| 1 | Hard node pinning | `spec.nodeName` |
| 2 | Label-based scheduling | `nodeSelector` |
| 3 | Taint effects | `NoSchedule` · `PreferNoSchedule` · `NoExecute` |
| 4 | Node affinity | `requiredDuringScheduling` · `preferredDuringScheduling` |
| 5 | QoS classes | `Guaranteed` · `Burstable` · `BestEffort` |
| 6 | DaemonSet | One pod per node |
| 7 | Static pods | Kubelet-managed via `/etc/kubernetes/manifests/` |

## Prerequisites

- Minikube running locally
- `kubectl` configured
