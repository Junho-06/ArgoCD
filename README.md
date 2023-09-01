# ArgoCD
ArgoCD &amp; Jenkins 로 CI/CD 파이프라인을 구성합니다.

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
$ helm install 0n argocd argocd-demo argo/argo-cd
```
