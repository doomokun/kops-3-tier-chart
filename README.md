# kops-3-tier-chart

# Chart pages
pages: https://doomokun.github.io/kops-3-tier-chart

repo: https://github.com/doomokun/kops-3-tier-chart
git: git@github.com:doomokun/kops-3-tier-chart.git

branch: main

# Helm Commands
```
$ helm repo add kops-3-tier-repo https://doomokun.github.io/kops-3-tier-chart

$ helm package .
$ helm repo index .
$ helm repo index . --url https://doomokun.github.io/kops-3-tier-chart

$ helm upgrade --install kops-3-tier kops-3-tier-repo/kops-3-tier-chart --namespace=kops-3-tier

$ helm repo list
$ helm search repo
$ helm install #{chart name you like} #{helm search repo NAME}

$ helm list
$ helm delete #{NAME}
$ helm delete --purge #{NAME}
```