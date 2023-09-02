# ArgoCD
ArgoCD 를 공부합니다.

---

### ArgoCD install on Cluster


```bash
$ kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

**OR**

### ArgoCD Install with Helm
```bash
$ helm repo add argo https://argoproj.github.io/argo-helm
```

```bash
$ helm install -n argocd argocd-demo argo/argo-cd
```
