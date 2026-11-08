# Security

This policy applies to every project of the selfhostr organization. A project may add details in its own `SECURITY.md`, which then takes precedence for that project.

## Report a vulnerability

Please do not open a public issue. Use GitHub's private reporting on the repository concerned:

| Project | Report privately |
| --- | --- |
| dumbmonit | [selfhostr/dumbmonit](https://github.com/selfhostr/dumbmonit/security/advisories/new) |
| suckerpot | [selfhostr/suckerpot](https://github.com/selfhostr/suckerpot/security/advisories/new) |
| orch | [selfhostr/orch](https://github.com/selfhostr/orch/security/advisories/new) |
| djsnake | [selfhostr/djsnake](https://github.com/selfhostr/djsnake/security/advisories/new) |
| kegtrack | [selfhostr/kegtrack](https://github.com/selfhostr/kegtrack/security/advisories/new) |
| dmsforall | [selfhostr/dmsforall](https://github.com/selfhostr/dmsforall/security/advisories/new) |
| mccb | [selfhostr/mccb](https://github.com/selfhostr/mccb/security/advisories/new) |
| mccs | [selfhostr/mccs](https://github.com/selfhostr/mccs/security/advisories/new) |

Include the affected version, the steps to reproduce and the impact you see. We aim to acknowledge a report within 7 days and to give a first assessment within 14 days. We are two people, so these are goals rather than guarantees. We credit reporters who want to be named.

## Supported versions

The latest release of each project and its current development branch. Older versions do not get fixes.

## What every repository has

- Private vulnerability reporting
- Secret scanning with push protection
- Dependabot alerts and security updates
- CodeQL and OpenSSF Scorecard workflows
- A `SECURITY.md` and code owners
- A protected default branch: no deletion, no force push, and changes through a pull request with one approval

Organization owners can bypass the branch rules. We keep this on purpose, because with two maintainers a required second person would sometimes block an urgent fix. It also means that not every change has been reviewed by someone else.
