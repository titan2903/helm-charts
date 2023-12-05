# helm-charts

Helm repository for example charts.

## Get started

Add this repository to Helm. Based on this [doc](https://medium.com/containerum/how-to-make-and-share-your-own-helm-package-50ae40f6c221).

```sh
helm repo add <helm_repo_name> https://<github_username>.github.io/<github_repo_name>
```

Install an example.

```sh
helm upgrade --install <apps_name> <helm_repo_name>/helm-charts
```
