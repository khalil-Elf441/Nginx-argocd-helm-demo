
## Exercise Starter Code
The folder conatins the following code:
```bash
.
│   .gitignore
│   README.md
│   Vagrantfile
│
│
├───argocd
│       argocd-helm-nginx-prod.yaml
│       argocd-helm-nginx-staging.yaml
│
└───helm
    └───nginx-deployment
        │   Chart.yaml
        │   values-prod.yaml
        │   values-staging.yaml
        │   values.yaml
        │
        └───templates
                configmap.yaml
                deployment.yaml
                namespace.yaml
                service.yaml
```


**Note**: the specified `config.vm.box_version` in the Vagrantfile updates with time. You will have to change it from `212` shown in the demo video above to a newer version. When a particular version used in Vagrantfile becomes deprecated, the command prompt will show you all available newer versions. 


