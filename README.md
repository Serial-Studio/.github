# GitHub settings for the Serial Studio organization

This is a special repository that holds the
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
that apply to every repository in the [Serial Studio](https://github.com/Serial-Studio)
organization, plus the organization profile shown at
[github.com/Serial-Studio](https://github.com/Serial-Studio).

## What lives here

| Path | Applies to |
|------|-----------|
| `profile/README.md` | The organization profile page |
| `CODE_OF_CONDUCT.md` | Every repo without its own |
| `CONTRIBUTING.md` | Every repo without its own |
| `GOVERNANCE.md` | Every repo without its own |
| `SECURITY.md` | Every repo without its own |
| `SUPPORT.md` | Every repo without its own |
| `FUNDING.yml` | The "Sponsor" button on every repo |
| `.github/ISSUE_TEMPLATE/` | Repos without their own issue templates |
| `.github/PULL_REQUEST_TEMPLATE.md` | Repos without their own PR template |

A file of the same name inside an individual repository always wins. The main
[Serial-Studio](https://github.com/Serial-Studio/Serial-Studio) repository ships its own
`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and issue templates, so the defaults here cover
the other repositories.

These files are not a fallback for licensing. Each repository states its own license, and
the main application is dual-licensed: GPLv3 for the open-source build and a commercial
license for the Pro modules. See
[LICENSE.md](https://github.com/Serial-Studio/Serial-Studio/blob/master/LICENSE.md).
