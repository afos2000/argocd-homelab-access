# argocd-homelab-access

Request access to ArgoCD at https://argocd.andreskube.uk.

## How to get access

1. **Create an account** at https://keycloak.andreskube.uk/realms/argocd/account (click "Register")
2. **Open a PR** adding your Keycloak username to `users.yaml` under the role you want
3. Once merged, log in at https://argocd.andreskube.uk with your new account

## Roles

| Role | Permissions |
|------|------------|
| `readonly` | View applications, clusters, repositories, logs |
| `admin` | Full access - manage apps, projects, exec into pods |
