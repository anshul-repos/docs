
# Other Interview Questions

## 1. How to Implement Security in an Application

- **Authentication**: user identity system <JWT, OAuth2, or OIDC>
- **Authorization**: check permissions/previleges on every API call
- **Encryption**: HTTPS / TLS everywhere
- **Input Validation**:
- **Secrets Management**:
- **Session & Token Security**:
- **Logging: Never log passwords or tokens
- **Dependency Security**: Run `govulncheck` to check known vulns
- **Rate Limiting : Prevent brute-force and abuse
- **Kubernetes / Cloud** : RBAC, Network Policies
- **Monitoring & Alerts**: Set up monitoring for failed logins, spikes, or suspicious requests
- **CI/CD & Deployment**: code scanning tools
