# glasskube-argocd-packages


## Install Argo CD with `glasskube`

```shell
brew install glasskube argocd
glasskube install argo-cd
```

## Install a Glasskube package as Argo CD app

```shell
argocd app create keptn --repo https://github.com/pmig/glasskube-argocd-packages --path keptn --dest-server https://kubernetes.default.svc
```