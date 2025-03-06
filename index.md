---

layout: col-sidebar
title: OWASP EKS Goat
tags: example-tag
level: 2
type: code
pitch: A very brief, one-line description of your project

---

OWASP EKS Goat is a hands-on AWS EKS security lab that teaches real-world attack and defense techniques for AWS managed Kubernetes cluster. It includes practical labs on misconfigurations, privilege escalation, and security hardening using IAM, RBAC, cloud native tool, and runtime security tools. Designed for security professionals, cloud engineers, and DevOps teams, it enhances both offensive and defensive Kubernetes security skills.

* Focuses on exploiting and defending AWS EKS clusters.
* Attack Scenarios: Exploiting Jenkins CVE to leak credentials via IMDSv2, leading to ECR image backdooring and EKS cluster takeover. This enables pod-to-node breakout, followed by IAM privilege escalation, ultimately allowing data exfiltration via S3.
* Defense Strategies: Labs on automated EKS scanning, enforcing Pod Security Context, Kyverno using CEL, and real-time monitoring with the eBPF tool Tetragon, along with AWS GuardDuty integration.
* Hardening Measures: Conducting compliance audits with Kubescape/Kubebench as well as Hadolint along with ECR scanning and security, and ensuring container image security.

### Road Map

* Current State:
    * Created and open-sourced hands-on labs for AWS EKS misconfigurations and vulnerabilities.
    * Developed detailed documentation to accompany lab walkthrough and theoretical concepts.
    * Implementation of initial attack &  defense scenarios with IAM and Kubernetes RBAC.
    * Continue using mdbook for documentation.

* Short-Term Goals:
    * Transition existing infrastructure deployment scripts to Terraform.
    * Update documentation to include images and step-by-step instructions for each lab.
    * Expand the defensive scenarios, adding advance topics such as network policies.
    * Add quizes for interaction.

* Long-Term Objectives:
    * Establish a continuous integration/continuous deployment (CI/CD) pipeline to automate the deployment and teardown of lab environments.
    * Develop a community forum to facilitate participant interaction, knowledge sharing, and collaborative learning.
    * Integrate threat modeling lab for AWS EKS infrastructure using EKS Goat to detect and mitigate proactively.
 
