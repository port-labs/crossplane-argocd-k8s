# crossplane-argocd-k8s

Resources for the [guide](https://docs.getport.io/create-self-service-experiences/setup-backend/github-workflow/examples/kubernetes/manage-clusters) to manage k8s clusters using Crossplane and ArgoCD.

### Reasons to Choose Crossplane:

- **Kubernetes-Centricity**: If your infrastructure is heavily built around Kubernetes, Crossplane offers a seamless integration. It treats external resources (databases, cloud services, etc.) as native Kubernetes objects, letting you manage everything with Kubernetes tools (kubectl, Helm, etc.)
- **Custom Resource Definitions (CRDs)**: Crossplane lets you build your own abstractions as CRDs, simplifying complex infrastructure configurations and tailoring them to your organization's specific needs.
- **YAML**: Crossplane uses YAML, which is a common format in the Kubernetes ecosystem.
