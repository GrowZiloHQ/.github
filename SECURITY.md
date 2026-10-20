# Security

Do not report active secrets in public issues.

## Never commit
- client passwords or account recovery material
- Google, Meta, CRM or advertising access tokens
- OAuth refresh tokens
- API keys or private keys
- payment details
- private client lead/customer exports
- production database dumps
- personally identifiable client/customer data unless a reviewed policy explicitly allows it

Use approved secret stores and least-privilege access. If a secret is accidentally committed, revoke/rotate it first; deleting it from Git history is not sufficient by itself.
