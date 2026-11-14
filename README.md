# Dardan Hoxhaj

DevOps Engineer on the Platform Solutions team at Docker (remote, Nov 2025–present). My background is in IAM and cloud security, with prior support engineering roles at Brex and Apple. I have an A.S. in Applied Information Technology from Pace University.

Based in Westchester, NY, and open to remote roles in DevOps/SRE, cloud security/IAM, and support engineering.

## Featured projects

**[agent-access-gateway](https://github.com/dardan-hoxhaj/agent-access-gateway)**  
Local identity and access gateway for AI agents. Keycloak issues short-lived (~5 min) OAuth 2.0 client-credentials tokens, one client per agent. A FastAPI gateway validates the JWT against Keycloak's JWKS, OPA enforces deny-by-default authorization (and fails closed if OPA is unreachable), and every allow or deny is written to a JSON audit log that never records the token. Terraform covers ECR and a GitHub OIDC role (validate-only, not deployed). CI runs ruff, pytest (22 tests, 88% coverage), OPA tests, Trivy, and gitleaks.

**[reliability-lab](https://github.com/dardan-hoxhaj/reliability-lab)** — in progress  
DevOps/SRE lab covering Terraform on AWS, Kubernetes, CI/CD, Prometheus/Grafana, and SLOs.

## Tech

Python, FastAPI, Keycloak, OAuth 2.0, JWT, OPA, Terraform, Docker, AWS, GitHub Actions

## Contact

- GitHub: [dardan-hoxhaj](https://github.com/dardan-hoxhaj)
- LinkedIn: [linkedin.com/in/dardan-h-53058b261](https://www.linkedin.com/in/dardan-h-53058b261)
