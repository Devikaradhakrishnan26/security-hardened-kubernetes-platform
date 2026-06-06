
# Kubernetes Cluster Design

## Environments

The platform contains:

- Development
- Staging
- Production

## Namespaces

Development:

- payment-dev
- risk-dev
- customer-dev
- platform-dev

Staging:

- payment-staging
- risk-staging
- customer-staging
- platform-staging

Production:

- payment-prod
- risk-prod
- customer-prod
- platform-prod

## Node Pools

Each cluster contains:

- System Node Pool
- Application Node Pool
- Monitoring Node Pool

## Security

Production is isolated within a protected environment boundary.

Future controls include:

- RBAC
- Network Policies
- Vault
- Audit Logging
