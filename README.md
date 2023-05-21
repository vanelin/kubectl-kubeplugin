# kubectl kubeplugin
Plugin for Kubernetes to get statistics

# Installation
using curl:

```sh
curl -LO https://raw.githubusercontent.com/vanelin/kubectl-kubeplugin/main/scripts/kubeplugin
chmod +x ./kubeplugin
sudo mv ./kubeplugin /usr/local/bin/kubectl-kubeplugin

```
or using [krew](https://krew.sigs.k8s.io/):

<pre>
kubectl krew index add vanelin <a href="https://github.com/vanelin/kubectl-kubeplugin">https://github.com/vanelin/kubectl-kubeplugin</a>
kubectl krew install vanelin/kubeplugin
</pre>

# Usage
```sh
kubectl kubeplugin <namespace> <pod/node>
kubectl kubeplugin --help
```

[![asciicast](https://asciinema.org/a/586334.svg)](https://asciinema.org/a/586334)