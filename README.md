---

## 📦 Kubernetes Complete Learning & Implementation

This repository documents my end-to-end Kubernetes learning journey with hands-on implementation.

All concepts were implemented using YAML and tested on both local Kubernetes clusters and cloud environments. The focus was on practical execution, not just theory.

---

## 🏗️ Implementation Approach

* Created Kubernetes resources using YAML (declarative approach)
* Used kubectl to deploy, manage, and debug workloads
* Tested applications on local cluster (Minikube / KIND)
* Explored cloud setup using AWS EKS
* Validated cluster using:

  * `kubectl get pods`
  * `kubectl get nodes`
  * `kubectl top node`

---

## 🚀 Part 1 – Kubernetes Fundamentals

* Monolithic vs Microservices
* Kubernetes Architecture
* Cluster Setup (Local / AWS EC2)
* kubectl Basics
* Pods, Namespaces
* Labels, Selectors, Annotations

👉 Hands-on: Created and managed Pods and Namespaces using kubectl

---

## ⚙️ Part 2 – Kubernetes Workloads

* Deployments
* ReplicaSets
* StatefulSets (MySQL example)
* DaemonSets
* Jobs
* CronJobs

👉 Practical: Deployed Notes Application using NGINX

---

## 🌐 Part 3 – Networking & Configuration

* Cluster Networking
* Services (ClusterIP)
* Ingress
* Network Policies
* ConfigMaps
* Secrets

👉 Hands-on: Configured services and exposed applications using Ingress

---

## 💾 Part 4 – Storage, Resource Management & Scheduling

* Persistent Volumes (PV)
* Persistent Volume Claims (PVC)
* StorageClasses
* Resource Requests and Limits
* Node Affinity
* Taints and Tolerations

👉 Hands-on: Managed storage and controlled pod scheduling

---

## 📈 Part 5 – Scaling, Reliability & Extensibility

* Horizontal Pod Autoscaler (HPA)
* Vertical Pod Autoscaler (VPA)
* Liveness Probes
* Readiness Probes
* RBAC
* Custom Resource Definitions (CRDs)

👉 Practical:

* Applied autoscaling based on load
* Implemented health checks
* Managed access control using RBAC

---

## 🔐 Part 6 – Security & Advanced Ecosystem

* Kubernetes Security
* Monitoring and Logging
* Helm (used for deploying Notes App)
* Service Mesh (Istio)
* Sidecar Pattern
* Init Containers
* Amazon EKS (cluster setup and nodegroup)
* Metrics Server (`kubectl top node`)

👉 Hands-on:

* Explored Helm-based deployments
* Observed service mesh using Istio and Kiali dashboard
* Created and verified EKS cluster and node group
* Monitored cluster resource usage using metrics

---

## 🎯 Key Learnings

* Understanding Kubernetes architecture and internal workflow
* Writing and debugging YAML configurations
* Managing workloads using Deployments, Services, and Ingress
* Implementing scaling using HPA and VPA
* Monitoring cluster resources using metrics
* Troubleshooting real issues using kubectl
* Understanding Kubernetes deployment in cloud (EKS)

---

## 📊 Validation & Output

* Cluster nodes successfully created and verified
* Metrics checked using kubectl top
* Applications deployed and tested locally
* Cloud cluster (EKS) provisioned and validated

---

## 📌 Conclusion

This repository reflects my complete Kubernetes journey from fundamentals to advanced concepts with practical implementation.

The focus was on learning by doing, solving real issues, and understanding how Kubernetes works in real-world environments.

---

## 👨‍💻 Author

Mujtaba Shaikh
Cloud & DevOps Engineer

---

## 🏆 Final Note

All configurations, commands, and YAML files used in this journey are available in this repository.

---
