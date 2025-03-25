# ArgoKube

Objective:
1. Automate deployments using Argo CD.
2. Store Kubernetes manifests in Git (GitOps approach).
3. Enable self-healing, auto-scaling, and rolling updates with Kubernetes.
4. Use CI/CD pipelines (Jenkins/GitHub Actions) to trigger deployments.

Workflow:

1. Developer pushes code to GitHub/GitLab.
2. CI pipeline builds a Docker image and pushes it to Docker Hub.
3. Argo CD detects a change in Git and deploys the updated version to Kubernetes.
4. Kubernetes ensures auto-scaling, self-healing, and rolling updates.


