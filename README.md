ArgoCD app of apps pattern.
---

Using this pattern we deploy ArgoCD as an Application.

1. First apply the `applications.yaml` manifest

`kubectl apply -f applications.yaml`

2. Now, you can add the Application in argo cd. Set repository url as this repository and the path as `applications`.

3. Sync the Application in argo cd.