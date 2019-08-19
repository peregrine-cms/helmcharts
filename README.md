# helmcharts

This project is the Helm repository for Peregrine CMS.

## Prerequisites 

1. Install the Helm client on your workstation
2. Install Tiller on your Kubernetes cluster


## Deploy the Peregrine Chart

Run the following commands to deploy Peregrine.

1. Add the Peregrine CMS repository.

```
$ helm repo add peregrine https://peregrine-cms.github.io/helmcharts/
$ helm repo update
```

2. Deploy Peregrine.

```
$ helm install --name r1 peregrine/peregrine
```
