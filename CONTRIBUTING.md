# Contributing to EyeNewz

Org: **Newscontent**. Repos are named `eyenewz-<job>`.

## Pick the right repo

Start at **[eyenewz-docs](https://github.com/Newscontent/eyenewz-docs)**. Clone only the repo for your role.

| You work on | Repo |
|-------------|------|
| Docs | [eyenewz-docs](https://github.com/Newscontent/eyenewz-docs) |
| API / ingest / ML | [eyenewz-backend](https://github.com/Newscontent/eyenewz-backend) |
| Android | [eyenewz-android](https://github.com/Newscontent/eyenewz-android) |
| iOS | [eyenewz-ios](https://github.com/Newscontent/eyenewz-ios) |
| Public site | [eyenewz-website](https://github.com/Newscontent/eyenewz-website) |
| Admin / newsroom UI | [eyenewz-admin](https://github.com/Newscontent/eyenewz-admin) |
| Network monitor | [eyenewz-netlapse](https://github.com/Newscontent/eyenewz-netlapse) |

Do not mix Android and backend changes in one pull request.

## Issues

Use the issue forms (Bug / Feature / Intern). Track work on the [EyeNewz Issue Dashboard](https://github.com/orgs/Newscontent/projects/1).

## Pull requests

1. Branch from `main` (`feature/…` or `fix/…`).
2. Follow that repo’s README Day-1 commands and run tests locally.
3. Open a PR with why + test plan (see `pull_request_template.md`).
4. Wait for CI on that repo. Do not push unrelated files to `eyenewz-backend` `main` — it auto-deploys the API.

## Secrets

Never commit `.env`, keystores, `google-services.json`, or API keys. Secret *names* are listed in [eyenewz-docs/GITHUB_SECRETS.md](https://github.com/Newscontent/eyenewz-docs/blob/main/GITHUB_SECRETS.md).
