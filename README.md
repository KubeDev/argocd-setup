# argocd-setup

### Obtendo a senha do admin
```
kubectl get secret argocd-initial-admin-secret -n argocd -o jsonpath='{.data.password}' | base64 -d
```
