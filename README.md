# Certified Kubernetes Administrator (CKA) Study Materials

A comprehensive collection of **hands-on CKA practice tasks, notes, kubectl commands, YAML examples, troubleshooting guides, and exam-focused exercises** to help you prepare for the **Certified Kubernetes Administrator (CKA)** certification.

> **Practice like you're in the real CKA exam.**

## 📚 Repository Contents

- CKA practice questions
- Hands-on lab exercises
- kubectl one-liners
- YAML manifests
- Common troubleshooting scenarios
- Exam tips & shortcuts
- Kubernetes documentation search tips
- Frequently used commands
- Storage, Networking, Security, Scheduling, Workloads, and Cluster Administration examples

## 📖 Topics Covered

### Core Concepts
- Pods
- ReplicaSets
- Deployments
- Services
- Namespaces
- Labels & Selectors

### Scheduling
- Node Selectors
- Node Affinity
- Taints & Tolerations
- Pod Priority

### Workloads
- Deployments
- DaemonSets
- Jobs
- CronJobs
- Rolling Updates
- Rollbacks
- Scaling

### Configuration
- ConfigMaps
- Secrets
- Environment Variables
- Volume Mounts

### Storage
- Persistent Volumes (PV)
- Persistent Volume Claims (PVC)
- Storage Classes
- emptyDir
- hostPath

### Networking
- ClusterIP
- NodePort
- Ingress
- Network Policies
- DNS

### Security
- Service Accounts
- RBAC
- Security Contexts

### Cluster Maintenance
- etcd Backup & Restore
- kubeadm
- Node Management
- Drain / Cordon / Uncordon

### Troubleshooting
- CrashLoopBackOff
- Pending Pods
- ImagePullBackOff
- Failed Scheduling
- Network Issues
- Storage Issues

## 🎯 Purpose

This repository focuses on **practical, exam-oriented learning** rather than lengthy theory.

It helps you:
- Practice under time constraints
- Learn kubectl efficiently
- Write YAML quickly
- Improve troubleshooting skills
- Navigate the Kubernetes documentation effectively during the exam

## 🛠 Prerequisites

- Basic Linux command-line knowledge
- Docker fundamentals (recommended)
- A Kubernetes cluster such as Minikube, Kind, kubeadm, K3s, or KillerCoda

## 🚀 Recommended Study Order

1. Core Kubernetes Concepts
2. Pods & Deployments
3. Services & Networking
4. ConfigMaps & Secrets
5. Storage (PV/PVC)
6. Scheduling
7. Security (RBAC)
8. Cluster Administration
9. Troubleshooting
10. Mock CKA Tasks

## 💡 Exam Tips

- Prefer `kubectl create` and `kubectl run` when possible.
- Use `--dry-run=client -o yaml` to generate manifests quickly.
- Learn to edit YAML efficiently with `vim`.
- Practice navigating the Kubernetes documentation.
- Verify every task before moving to the next one.

## 🤝 Contributions

Contributions are welcome! Feel free to submit a Pull Request or open an Issue with new tasks, improvements, or bug fixes.

## ⭐ Support

If this repository helps you prepare for the CKA exam, consider giving it a ⭐.

Happy Learning! ☸️
