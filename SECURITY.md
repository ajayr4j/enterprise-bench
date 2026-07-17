# Security policy

Enterprise-Bench includes synthetic enterprise data, benchmark tasks, local service containers, and agent execution paths. Please report security issues privately.

## Report a vulnerability

If you find a security issue, data leak, exposed credential, unsafe container behavior, or a way for benchmark tasks to access data they should not, do not open a public issue with details.

Report it to:

- security@devrev.ai

Include:

- A short description of the issue.
- Steps to reproduce.
- Affected files, tasks, or services.
- Any logs or screenshots that do not expose secrets.
- Suggested fix, if known.

## Data safety

Do not contribute real customer data, private emails, credentials, tokens, or proprietary documents. Dataset additions must be synthetic or explicitly licensed for public release.

## Supported versions

Security fixes target the current public release branch and the active development branch.

## Scope

In scope:

- Repository code and scripts.
- Benchmark task definitions.
- Synthetic dataset files.
- Local Docker/MCP service setup.
- Documentation that could cause insecure behavior.

Out of scope:

- Vulnerabilities in third-party agent tools or model providers, unless this repo configures them unsafely.
- Reports that require access to private DevRev infrastructure.
