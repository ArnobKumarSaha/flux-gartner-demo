
```bash 
flux bootstrap github \
--token-auth \
--owner=ArnobKumarSaha \
--repository=flux-gartner-demo \
--branch=master \
--path=core \
--personal --private=false
```

```bash 
kubectl create ns kubeops
kubectl create ns demo

flux get kustomizations --watch
```