# Contributing to TooBrief

Org: **Newscontent**. Repos are named `toobrief-<job>`.

## Pick the right repo

Start at **[toobrief-docs](https://github.com/Newscontent/toobrief-docs)**. Clone only the repo for your role.

| You work on | Repo |
|-------------|------|
| Docs | [toobrief-docs](https://github.com/Newscontent/toobrief-docs) |
| API / ingest / ML | [toobrief-backend](https://github.com/Newscontent/toobrief-backend) |
| Android | [toobrief-android](https://github.com/Newscontent/toobrief-android) |
| iOS | [toobrief-ios](https://github.com/Newscontent/toobrief-ios) |
| Public site | [toobrief-website](https://github.com/Newscontent/toobrief-website) |
| Admin / newsroom UI | [toobrief-admin](https://github.com/Newscontent/toobrief-admin) |
| Network monitor | [toobrief-netlapse](https://github.com/Newscontent/toobrief-netlapse) |

Do not mix Android and backend changes in one pull request.

## Issues

Use the issue forms (Bug / Feature / Intern). Track work on the [TooBrief Issue Dashboard](https://github.com/orgs/Newscontent/projects/1).

## Pull requests

1. Branch from `main` (`feature/…` or `fix/…`).
2. Follow that repo’s README Day-1 commands and run tests locally.
3. Open a PR with why + test plan (see `pull_request_template.md`).
4. Wait for CI on that repo. Do not push unrelated files to `toobrief-backend` `main` — it auto-deploys the API.

## Secrets

Never commit `.env`, keystores, `google-services.json`, or API keys. Secret *names* are listed in [toobrief-docs/GITHUB_SECRETS.md](https://github.com/Newscontent/toobrief-docs/blob/main/GITHUB_SECRETS.md).
