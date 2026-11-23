# Security Policy

This policy covers every repository owned by the Military Veteran Team (MVT) at LPT Realty.

## Supported Versions

MVT web apps are deployed continuously. Only the version currently running in production (the `main` branch of each repository) receives security fixes. Older commits, branch previews and archived repositories are not supported.

| Version | Supported |
| ------- | --------- |
| Current production (`main`) | Yes |
| `dev` and `staging` previews | Fixed as part of the next release |
| Archived repositories | No |

## Reporting a Vulnerability

Please do not open a public issue, pull request or discussion for a security problem, and do not post it in a team chat channel.

Report it privately in one of two ways:

1. Use **Report a vulnerability** on the repository's Security tab (GitHub private vulnerability reporting), where it is turned on.
2. Email matth@militaryvetteam.com and fin@militaryvetteam.com with the subject line "Security report".

Include as much of this as you can:

- The app or repository and the page or URL affected
- What you did, what you expected and what happened
- Steps to reproduce it, with screenshots if they help
- Whether any client, agent or workforce data was visible or changed

Do not include passwords, API keys, tokens or client personal data in the report. If you found one exposed, tell us where it is, not what it is.

## What to Expect

- We acknowledge a report within 1 business day.
- We give a first assessment within 3 business days.
- We aim to fix or contain critical issues within 7 days, and other issues within 30 days.
- We tell you when the fix is live, and we credit you if you would like that.

## Rules for Testing

- Test only with your own account and your own data.
- Do not access, change, download or delete data that belongs to other people.
- Do not run denial of service tests, send spam or use social engineering against MVT staff, agents or clients.
- Stop and report as soon as you confirm a problem.

We will not take action against anyone who reports a problem in good faith and follows these rules.

## For MVT Team Members

- Never commit passwords, API keys, tokens or client data. Secrets belong in the approved secret store, never in code, issues, pull requests or chat.
- If a secret is exposed, report it right away so it can be rotated. Deleting the commit is not enough.
- Access questions and changes go to the MVT security team, not to a public channel.
