# argocd-homelab-access

Request access to ArgoCD at https://argocd.andreskube.uk.

## How to request access

1. Make sure you have a **Keycloak account** - ask an admin to create one
2. Open a **PR** adding your Keycloak username to `users.yaml` under the role you want
3. Once merged, you can log in at https://argocd.andreskube.uk

## Roles

| Role | Permissions |
|------|------------|
| `readonly` | View applications, clusters, repositories, logs |
| `admin` | Full access - manage apps, projects, exec into pods |
