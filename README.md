# Certified Kubernetes Security Specialist (CKS)

## Intensive 2-week learning plan

An intensive 2-week learning plan for the Certified Kubernetes Security Specialist (CKS) exam, assuming you can dedicate 6 hours per day.

### Week 1

#### Day 1: Introduction and Overview

- **Read the Curriculum and Certification Details (1 hour)**
  - CKS Curriculum: [CKS Curriculum v1.30](https://github.com/cncf/curriculum/blob/master/CKS_Curriculum_%20v1.30.pdf)
  - Certification: [Certified Kubernetes Security Specialist](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)
  - Important Instructions: [CKS Important Instructions](https://docs.linuxfoundation.org/tc-docs/certification/important-instructions-cks)
- **Start KodeKloud Course (3 hours)**
  - [Certified Kubernetes Security Specialist (CKS) course](https://learn.kodekloud.com/user/courses/certified-kubernetes-security-specialist-cks)
  - Course Introduction (08:55)
  - Exam Information (01:47)
  - Certification Details
  - Join our Community
  - Understanding the Kubernetes Attack Surface
    - The Attack (08:06)
    - The 4C's of Cloud Native Security (03:13)
    - A Quick Reminder (01:10)
- **Start LFS260 Course (2 hours)**
  - [Kubernetes Security Essentials (LFS260)](https://training.linuxfoundation.org/training/kubernetes-security-essentials-lfs260)
  - Course Introduction
  - Cloud Security Overview

#### Day 2: Cluster Setup and Hardening

- **KodeKloud Course (3 hours)**
  - Cluster Setup and Hardening
    - Section Introduction (01:15)
    - What are CIS Benchmarks (05:52)
    - Lab - Run CIS Benchmark Assessment tool on Ubuntu
    - CIS benchmark for Kubernetes (02:41)
    - Kube-bench (01:15)
    - Lab - Kube-bench
    - Kubernetes Security Primitives (03:18)
    - Authentication (05:34)
    - Service Accounts (14:34)
    - Lab - Service Accounts
    - TLS Introduction (01:28)
- **LFS260 Course (3 hours)**
  - Preparing to Install
  - Installation Preparations
  - Lab Exercises

#### Day 3: Cluster Setup and Hardening (continued)

- **KodeKloud Course (3 hours)**
  - TLS Basics (20:03)
  - TLS in Kubernetes (07:48)
  - TLS in Kubernetes - Certificate Creation (10:55)
  - View Certificate Details (04:31)
  - Lab - View Certificates
  - Certificates API (06:07)
  - Lab - Certificates API
  - KubeConfig (08:32)
  - Lab - KubeConfig
  - API Groups (05:52)
- **LFS260 Course (3 hours)**
  - Installing the Cluster
  - Cluster Installation
  - Lab Exercises

#### Day 4: Securing the Kube-apiserver and Networking

- **KodeKloud Course (3 hours)**
  - Authorization (07:30)
  - RBAC (04:28)
  - Lab - RBAC
  - Cluster Roles and Role Bindings (04:33)
  - Lab - Cluster Roles and Role Bindings
  - Kubelet Security (14:48)
  - Lab - Kubelet Security
  - Kubectl Proxy & Port Forward (06:48)
  - Lab - Kubectl Proxy & Port Forward
  - Kubernetes Dashboard (06:13)
  - Securing Kubernetes Dashboard (01:38)
  - Lab - Secure Kubernetes Dashboard
- **LFS260 Course (3 hours)**
  - Securing the Kube-apiserver
  - Lab Exercises

#### Day 5: Networking and Workload Considerations

- **KodeKloud Course (3 hours)**
  - Network Policy (07:51)
  - Developing Network Policies (11:36)
  - Lab - Network Security Policy
  - Ingress (22:34)
  - Lab - Ingress
- **LFS260 Course (3 hours)**
  - Networking Essentials
  - Lab Exercises

#### Day 6: System Hardening

- **KodeKloud Course (3 hours)**
  - System Hardening
    - Section Introduction (01:30)
    - Least Privilege Principle (05:16)
    - Minimize host OS footprint Intro (00:51)
    - Limit Node Access (05:48)
    - Lab - Limit Node Access
    - SSH Hardening (05:49)
    - Privilege Escalation in Linux (03:05)
    - Lab - SSH Hardening and sudo
- **LFS260 Course (3 hours)**
  - Workload Considerations
  - Lab Exercises

#### Day 7: Killer Shell Course (Part 1)

- **Killer Shell Course (6 hours)**
  - Watch and follow along with the [Killer Shell CKS Full Course](https://www.youtube.com/watch?v=d9xfB5qaOfg).
    - Introduction and Welcome
    - K8s Security Best Practices
    - Create your course K8s cluster
    - Crictl instead of Docker
    - Foundation - Kubernetes Secure Architecture
    - Foundation - Containers under the hood
    - Cluster Reset
    - Cluster Setup - Network Policies
    - Cluster Setup - GUI Elements

### Week 2

#### Day 8: Killer Shell Course (Part 2)

- **Killer Shell Course (6 hours)**
  - Continue with the Killer Shell CKS Full Course.
    - K8s Docs Version
    - Cluster Setup - Secure Ingress
    - Cluster Setup - Node Metadata Protection
    - Cluster Setup - CIS Benchmarks
    - Cluster Setup - Verify Platform Binaries
    - Cluster Hardening - RBAC
    - Cluster Hardening - Exercise caution in using ServiceAccounts
    - Cluster Hardening - Restrict API Access
    - Cluster Hardening - Upgrade Kubernetes

#### Day 9: Killer Shell Course (Part 3)

- **Killer Shell Course (5 hours)**
  - Continue with the Killer Shell CKS Full Course.
    - Microservice Vulnerabilities - Manage Kubernetes Secrets
    - Microservice Vulnerabilities - Container Runtime Sandboxes
    - Microservice Vulnerabilities - OS Level Security Domains
    - Microservice Vulnerabilities - mTLS
    - Cluster Reset
    - Open Policy Agent (OPA)
    - Supply Chain Security - Image Footprint
    - Supply Chain Security - Static Analysis

#### Day 10: Killer Shell Course (Part 4)

- **Killer Shell Course (5 hours)**
  - Complete the Killer Shell CKS Full Course.
    - Supply Chain Security - Image Vulnerability Scanning
    - Supply Chain Security - Secure Supply Chain
    - Runtime Security - Behavioral Analytics at host and container level
    - Runtime Security - Immutability of containers at runtime
    - Runtime Security - Auditing
    - System Hardening - Kernel Hardening Tools
    - System Hardening - Reduce Attack Surface

#### Day 11: Minimize Microservice Vulnerabilities

- **KodeKloud Course (3 hours)**
  - Minimize Microservice Vulnerabilities
    - Section Introduction (00:54)
    - Security Contexts (01:52)
    - Lab - Security Contexts
    - Admission Controllers (08:07)
    - Lab - Admission Controllers
    - Validating and Mutating Admission Controllers (10:26)
    - Lab - Validating and Mutating Admission Controllers
    - Pod Security Policies (08:53)
- **LFS260 Course (3 hours)**
  - Issue Detection
  - Lab Exercises

#### Day 12: Minimize Microservice Vulnerabilities (continued)

- **KodeKloud Course (3 hours)**
  - Pod Security Admission and Pod Security Standards (04:57)
  - Lab - Pod Security Admission
  - Open Policy Agent (OPA) (09:48)
  - Lab - OPA
  - OPA in Kubernetes (08:59)
  - Lab - OPA in Kubernetes
  - OPA Gatekeeper in Kubernetes
  - Lab - OPA Gatekeeper
- **LFS260 Course (3 hours)**
  - Domain Review
  - Exam Preparation

#### Day 13: Supply Chain Security

- **KodeKloud Course (3 hours)**
  - Supply Chain Security
    - Section Introduction (00:30)
    - Minimize base image footprint (07:24)
    - Image Security (04:43)
    - Lab - Image Security
    - Whitelist Allowed Registries - Image Policy Webhook (05:16)
    - Lab - Whitelist Allowed Registries - ImagePolicyWebhook
    - Use static analysis of user workloads (02:46)
    - Lab - kubesec
    - Scan images for known vulnerabilities (Trivy) (08:34)
    - Lab - Trivy
- **LFS260 Course (3 hours)**
  - Lab Exercises
  - Course Completion

#### Day 14: Monitoring, Logging, and Runtime Security and Simulators

- **KodeKloud Course (3 hours)**

  - Monitoring, Logging, and Runtime Security
    - Section Introduction (00:50)
    - Perform behavioral analytics of syscall process (04:47)
    - Falco Overview and Installation (02:53)
    - Use Falco to Detect Threats (08:39)

- Falco Configuration Files (06:54)
  - Lab - Use Falco to Detect Threats
  - Mutable vs Immutable Infrastructure (04:50)
  - Ensure Immutability of Containers at Runtime (05:18)
  - Lab - Ensure Immutability of Containers at Runtime
- **Killer Shell Simulators (4 hours)**
  - CKS Simulator 1 (2 hours)
  - CKS Simulator 2 (2 hours)

### Additional Resources and Links

- **Kubernetes Security Documentation**: [Kubernetes Security Documentation](https://kubernetes.io/docs/concepts/security/)
- **KodeKloud CKS Course**: [KodeKloud CKS Course](https://learn.kodekloud.com/user/courses/certified-kubernetes-security-specialist-cks)
- **KodeKloud CKS Challenges**: [KodeKloud CKS - Challenges](https://learn.kodekloud.com/user/courses/cks-challenges)
- **Linux Foundation Kubernetes Security Essentials (LFS260)**: [Kubernetes Security Essentials (LFS260)](https://training.linuxfoundation.org/training/kubernetes-security-essentials-lfs260)
- **Killer Shell CKS Course**: [Killer Shell CKS Full Course](https://www.youtube.com/watch?v=d9xfB5qaOfg)

### Notes and Tips:

- **Balance the Content**: Spend more time on hands-on labs and mock exams towards the end of each week to solidify your understanding.
- **Prioritize Weak Areas**: Adjust the plan slightly based on which areas you find most challenging.
- **Hands-on Practice**: Emphasize practical experience by setting up a Kubernetes cluster and practicing security configurations.
- **Stay Updated**: Follow Kubernetes and security-related news to stay updated on any changes or new best practices.
- **Join Study Groups**: Participate in online forums or study groups to discuss and resolve doubts.

This plan integrates all necessary resources and ensures comprehensive coverage within two weeks, preparing you effectively for the CKS exam. Good luck!
