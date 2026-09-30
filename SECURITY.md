# Security policy

If you think you have found a security vulnerability in Vectros, please tell us privately. Do not
open a public issue, pull request, or discussion about it.

## How to report

**Use GitHub private vulnerability reporting.** On the repository where you found the problem,
open the **Security** tab and choose **Report a vulnerability**. Only you and the Vectros team can
see the report.

If a repository does not show that option, or the problem is in the hosted Vectros API or apps
rather than in the code in a repository, email security@vectros.ai.

## What to include

- What you found and where: the package or app, its version, and the endpoint or file involved.
- Steps to reproduce, or a proof of concept.
- What an attacker could do with it.

Use synthetic data only. Please do not include real customer data, real credentials, or anything
you are not authorized to hold in your report.

## Scope

This policy covers the code in the repositories of this organization (the SDKs, the MCP server,
the React components, the blueprints package, the Claude Code agent memory package, the reference
apps, and the examples), the Vectros command-line tool, and the hosted Vectros API and apps.

If you are unsure whether something is in scope, report it anyway.

## What we ask of you

- Test only against accounts and data you own or are authorized to use.
- Do not read, change, or delete data that belongs to anyone else.
- Do not run denial-of-service tests, and do not use social engineering or physical attacks.
- Give us reasonable time to investigate and fix an issue before you disclose it publicly.
- Check that the issue reproduces on the latest published release of the package.

## What to expect

We read reports and reply in the report itself. We do not publish a fixed response or fix
timeline. We will tell you when a fix has shipped.

## Not for vulnerabilities

For ordinary bugs and feature requests, use
[vectros-feedback](https://github.com/vectros-ai/vectros-feedback/issues/new/choose) instead.
