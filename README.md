# 🧭 Kubernetes YAML Resources

This repository contains a comprehensive collection of Kubernetes YAML manifest files created while learning and practicing **Kubernetes (K8s)**. It includes core components, resource configurations, probes, affinity rules, node selectors, and more — all essential for deploying and managing applications in a Kubernetes environment.

## 📦 What’s Included

> Each file demonstrates a specific K8s concept or object.

### 🔧 Workload Resources
- `deployment.yml` / `deployment_recreate.yml`
- `daemonset.yml`
- `replicaset.yml`
- `statefulset.yml`
- `pod.yml`

### 📦 Storage & Volumes
- `storageclass.yml`
- `springapp_pv.yml`, `springapp_pvc.yml`, `springapp_nfs.yml`
- `springapp_hostpath.yml`, `springapp_emptyDir.yml`

### 🌐 Networking
- `service.yml`
- `networkpolicies.yml`
- `livenessprobe_readinessprobe.yml`

### ⚙️ Scheduling & Affinity
- `nodeselector.yml`
- `nodeaffinity_hardrule.yml`, `nodeaffinity_preferredrule.yml`
- `podaffinity_req_pref.yml`
- `taints_tolerations.yml`

### 📊 Resource Management
- `resourcequota.yml`
- `resourcerequest.yml`
- `resourcemanagement.yml`

### 🔄 Update Strategies
- `deployment_rollingupdate.yml`

### 🧠 Extras & Practice
- `nginx.yml`, `newwebappsvc.yml`
- `springapp+mongo deployment.yml`
- `readme_staticpods.yml`

## 🎯 Purpose

This repo was built during my hands-on learning of Kubernetes to:

- Understand real-world YAML structure and resource configurations
- Practice different deployment patterns
- Explore resource allocation and cluster-level rules
- Learn how to build production-ready K8s manifests

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. Apply any YAML file:
    kubectl apply -f <filename>.yml

3. Clean up resources:
     kubectl delete -f <filename>.yml

   
🙋‍♀️ Author
Sathwikaa Devarapalli
Cloud & DevOps Enthusiast | Kubernetes Learner
📧 sathwikaa.devarapalli@gmail.com
🌐 LinkedIn
   
