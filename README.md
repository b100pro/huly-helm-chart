## Helm chart for huly project management application

set below values and install the helm chart

- `ingress.domain`
- `ingress.collaboratorDomain`
- `ingress.transactorDomain`
- `ingress.accountDomain`
- `ingress.statsDomain`
- `ingress.rekoniDomain`
- `account.serverSecret`

```bash
helm repo add huly https://raw.githubusercontent.com/logi-camp/huly-helm-chart/refs/heads/main
helm install huly -n huly huly/huly
```