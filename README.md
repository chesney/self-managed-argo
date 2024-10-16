ArgoCD app of apps pattern.
---

Using this pattern we deploy ArgoCD as an Application.

1. First apply the `applications.yaml` manifest

`kubectl apply -f applications.yaml`

2. Now, the argo cd applicatiion called `Applications` should be available in the argo cd ui.

3. Press on the sync button of the `Applications` application.