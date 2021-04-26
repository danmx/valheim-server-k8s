# Valheim Game Server on Kubernetes

Using [Kustomize](https://kustomize.io) to deploy and [lloesche/valheim-server-docker](https://github.com/lloesche/valheim-server-docker) as a default image.

## Deployment

This will deploy a dedicated namespace for all resources required by a game server.

To set a password create a `password.txt` file in `deploy/secret` directory.

```constole
kubectl apply -k deploy/
```
