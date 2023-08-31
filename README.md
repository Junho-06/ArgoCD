# ArgoCD
ArgoCD &amp; Jenkins 로 CI/CD 파이프라인을 구성합니다.

---

### ArgoCD install on Cluster
```bash
$ kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```