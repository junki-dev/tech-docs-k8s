Technical Documents Service - [K8S]
===

## Skills

- kubectl
- Helm
- GCP(Google Cloud Platform)

## Create Secrets
```bash
$ kubectl.docker create secret generic mongodb --from-literal=connectionString={mongodbUri}
```

## Commands
```bash
# create helm chart
$ helm create docs

# install helm chart
$ helm install docs .

# update helm chard
$ helm upgrade docs .

# restart pods
$ kubectl rollout restart deployment docs
```

## Docs

- [Project Description](https://www.notion.so/tech-docs-bab0d6f1b22e4328a7aae0e352f264a6?pvs=4)
- [Resume](https://www.notion.so/Junki-Kim-03c4ef023f88413d9b569e2119e7665d?pvs=4)
