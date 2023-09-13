## This repo is for helm and helm related stuff.

## this is a sample command for upgrading your cluster with your custom values.yaml file
## list of commands:
helm upgrade my-prom prometheus-community/kube-prometheus-stack -f myvalues.yaml
helm list
helm install "yourlabel" repo/package ## note that this is unsafe and should not be used on production en cause you have no control over it
helm repo list
helm show values reponame/package
helm pull repo/package
