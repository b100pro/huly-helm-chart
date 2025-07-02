## Helm chart for huly project management application

set below values and install the helm chart

- `ingress.domain`
- `ingress.collaborator.domain`
- `ingress.transactor.domain`
- `ingress.account.domain`
- `ingress.stats.domain`
- `ingress.rekoni.domain`
- `account.serverSecret`

```bash
helm repo add huly https://raw.githubusercontent.com/b100pro/huly-helm-chart/refs/heads/main
helm install huly -n huly huly/huly
```
