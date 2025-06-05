# Learning Kubernetes - Practical Experience

## Overview
This repository documents my hands-on journey learning Kubernetes fundamentals and advanced concepts through practical implementation. Over the course of several weeks, I've progressed from basic cluster setup to advanced Kubernetes features, implementing each concept with actual configuration files.

## What I've Learned and Implemented

### Core Concepts
- ✅ **Cluster Setup**: Installed KIND and kubectl, created Kubernetes clusters
- ✅ **Namespaces**: Created and managed logical cluster partitions
- ✅ **Pods**: Learned about the smallest deployable units in Kubernetes
- ✅ **Labels & Selectors**: Implemented for resource organization and selection

### Workloads & Controllers
- ✅ **Deployments**: Created for Apache and other applications
- ✅ **ReplicaSets**: Learned about maintaining stable pod replicas
- ✅ **DaemonSets**: Implemented for node-level workloads
- ✅ **StatefulSets**: Configured for MySQL with persistent storage
- ✅ **Jobs & CronJobs**: Scheduled one-time and recurring tasks

### Networking & Services
- ✅ **Services**: Created ClusterIP, NodePort services
- ✅ **Ingress**: Configured for external access to services
- ✅ **Network Policies**: Learned about controlling pod communication

### Storage
- ✅ **PersistentVolumes (PV)**: Created storage resources
- ✅ **PersistentVolumeClaims (PVC)**: Configured pod storage requests
- ✅ **ConfigMaps & Secrets**: Managed configuration data securely

### Advanced Features
- ✅ **Horizontal Pod Autoscaling (HPA)**: Automated scaling based on CPU
- ✅ **Vertical Pod Autoscaling (VPA)**: Implemented for resource optimization
- ✅ **Resource Quotas**: Set namespace-level resource constraints
- ✅ **Probes**: Configured liveness, readiness, and startup probes
- ✅ **Taints & Tolerations**: Learned about node affinity/anti-affinity
- ✅ **RBAC**: Implemented Role-Based Access Control with Service Accounts
- ✅ **Custom Resource Definitions (CRDs)**: Extended Kubernetes API

### Specialized Patterns
- ✅ **Init Containers**: Implemented for setup tasks before app startup
- ✅ **Sidecar Containers**: Learned about auxiliary containers
- ✅ **Helm**: Used the package manager for Kubernetes applications

## Project Structure
The repository contains YAML configurations for all implemented concepts, organized by component type:

```
Apache/
mysql/
nginx/
pods/
crd/
dashboard/
helm/
```

## Key Projects Implemented
1. **Apache Web Server Deployment**
   - Complete setup with Deployment, Service, and Namespace
   - Implemented probes for health monitoring
   - Configured resource limits and quotas

2. **MySQL Stateful Application**
   - StatefulSet configuration with persistent storage
   - Secrets management for sensitive data
   - Custom namespace isolation

3. **NGINX Deployment with Advanced Features**
   - Ingress configuration for external access
   - Persistent volume claims for storage
   - Horizontal Pod Autoscaling

4. **Custom Resource Definition Implementation**
   - Created custom resources for specialized needs
   - Implemented controllers for custom resources

## Learning Journey
I followed a structured approach:
1. Started with cluster fundamentals and basic resources
2. Progressed to controllers and workload management
3. Implemented networking and storage solutions
4. Explored advanced features and customization options

Each commit represents a new concept learned and implemented with practical configuration files.

## How to Explore
- Browse the YAML files to see practical implementations
- Check commit history to follow my learning progression
- The organized directory structure reflects different Kubernetes components

This repository serves as both a learning log and a practical reference for Kubernetes implementations.
