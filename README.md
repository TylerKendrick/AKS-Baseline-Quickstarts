# AKS Baseline Guidance

Microsoft provides security benchmarks and standards for establishing secure, compliant environments within the Azure cloud platform. Some of the most relevant concepts are provided below with some example reference architectures to follow.
The official document that maintains these standards is known as the [Azure Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/). This project exists to serve as a way to more easily navigate the security standards and best practices relevant to AKS.

For information about the roadmap for AKS, [see here](https://github.com/Azure/AKS/projects/1)

## Security Standards and Practices

The [security baseline for AKS](https://learn.microsoft.com/en-us/security/benchmark/azure/baselines/aks-security-baseline) provides compliance with the [Azure Security Benchmark v1](https://learn.microsoft.com/en-us/security/benchmark/azure/). This document should be used as a reference for establishing a secure cluster that is compliant with regulatory standards and security controls outlined in the benchmark. 

### Reference Links

Below are documents that have official guidance on implementing secure practices using AKS.

* [Security Considerations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/security)
* [Security Concepts](https://learn.microsoft.com/en-us/azure/aks/concepts-security)
* [Security Controls](https://learn.microsoft.com/en-us/security/benchmark/azure/overview)
* [Built-In Policies](https://learn.microsoft.com/en-us/azure/governance/policy/samples/built-in-policies#kubernetes)
* [Azure Policy Security Controls for AKS](https://learn.microsoft.com/en-us/azure/aks/security-controls-policy)
* [CIS Kubernetes Benchmark](https://learn.microsoft.com/en-us/azure/aks/cis-kubernetes)
* [Secure Pod Traffic](https://learn.microsoft.com/en-us/azure/aks/use-network-policies)
* [Integration with existing networks](https://learn.microsoft.com/en-us/azure/aks/operator-best-practices-network)

## Architecture Best Practices

* [Baseline](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/baseline-aks)
* [Well Architected Framework](https://learn.microsoft.com/en-us/azure/architecture/framework/)
* [Well Architected AKS](https://learn.microsoft.com/en-us/azure/architecture/framework/services/compute/azure-kubernetes-service/azure-kubernetes-service)
* [Self-Assesment](https://learn.microsoft.com/en-us/assessments/?id=azure-architecture-review&mode=pre-assessment&session=local)
* [Micro-services](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-microservices/aks-microservices)

## Developing within a Cluster

* [Developer Best Practices](https://learn.microsoft.com/en-us/azure/aks/best-practices)
* [Autogenerate container artifacts with Draft](https://learn.microsoft.com/en-us/azure/aks/draft)
* [Pod Best Practices](https://learn.microsoft.com/en-us/azure/aks/developer-best-practices-pod-security)
* [Bridge to Kubernetes](https://learn.microsoft.com/en-us/visualstudio/bridge/overview-bridge-to-kubernetes)
* [Chaos Engineering and Testing](https://learn.microsoft.com/en-us/azure/chaos-studio/chaos-studio-overview)
* [GitOps](https://learn.microsoft.com/en-us/azure/architecture/example-scenario/gitops-aks/gitops-blueprint-aks)
* [Landing Zone Accelerators](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/landing-zone-accelerator)

## Application Aspects within AKS

### Secrets Management

* [KeyVault RBAC](https://learn.microsoft.com/en-us/azure/key-vault/general/rbac-guide?tabs=azure-cli)
* [Use a CSI Driver](https://learn.microsoft.com/en-us/azure/aks/csi-secrets-store-driver)
* [Add Key Management to a cluster](https://learn.microsoft.com/en-us/azure/aks/use-kms-etcd-encryption)

### Storage

* [Storage Overview](https://learn.microsoft.com/en-us/azure/aks/concepts-storage)
* [Use a CSI](https://learn.microsoft.com/en-us/azure/aks/csi-storage-drivers)

### Identity

* [Identity Overview](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)
* [Defender for Containers](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-containers-introduction)
* [Managed AAD Integration](https://learn.microsoft.com/en-us/azure/aks/managed-aad)
* [Pod Identities in AAD](https://learn.microsoft.com/en-us/azure/aks/workload-identity-overview)

## Monitoring / Alerts

* [Azure Monitor](https://learn.microsoft.com/en-us/azure/aks/monitor-aks)
* [Container Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-overview)
* [Alerts](https://learn.microsoft.com/en-us/azure/defender-for-cloud/alerts-reference#alerts-k8scluster)

## Logging

* [Kubelet Logs](https://learn.microsoft.com/en-us/azure/aks/kubelet-logs)
* [Resource Logs](https://learn.microsoft.com/en-us/azure/aks/monitor-aks-reference#resource-logs)
* [Live Logs](https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-livedata-overview)


## Quickstarts