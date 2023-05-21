# kubectl-ktop
Plugin for Kubernetes to get statistics"

# Installation
```sh
curl -LO https://raw.githubusercontent.com/vanelin/kubectl-kubeplugin/main/scripts/kubeplugin
chmod +x ./kubeplugin
sudo mv ./kubeplugin /usr/local/bin/kubectl-kubeplugin

```
or using [krew](https://krew.sigs.k8s.io/):

<pre>
kubectl krew index add vanelin <a href="https://raw.githubusercontent.com/vanelin/kubectl-kubeplugin">https://raw.githubusercontent.com/vanelin/kubectl-kubeplugin</a>
kubectl krew install vanelin/kubeplugin
</pre>

# Usage
```sh
kubectl kubeplugin <namespace> <pod/node>
kubectl kubeplugin --help
```