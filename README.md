# .github

The public `.github` repository of the `workoho` organization. GitHub reads
three things from it, and everything here is public.

| Path | What GitHub does with it |
| :--- | :----------------------- |
| `profile/README.md` | Shows it on the organization's public profile page |
| `SECURITY.md`, `CONTRIBUTING.md` | Default for every repository without its own, private ones included |
| `.github/ISSUE_TEMPLATE/`, `.github/PULL_REQUEST_TEMPLATE.md` | Default issue forms and pull request template, with the exception below |

**A repository with its own `ISSUE_TEMPLATE` folder ignores the default
issue templates completely**, `config.yml` too. Every other file is replaced
one by one. The defaults do not show up in the file browser or in a clone of
the repository that inherits them.

**Not inherited, so it stays in each repository:** `LICENSE`, `README.md`,
`CODEOWNERS`. GitHub does not support a default for them.

The member-only profile is not here. It comes from the private
`.github-private` repository, which also holds the organization's rulesets and
property schema.

Docs read on 2026-10-01: *Creating a default community health file* and
*Customizing your organization's profile* on docs.github.com.

## Brand

`profile/workoho-wordmark.svg` and `profile/workoho-wordmark-dark.svg` are
copies from `visual-identity` in the `wkho` plugin, vendored from
`workoho/brand` at v1.4.4. The README picks the file by color scheme.

## Working on it

`AGENTS.md` has the rules for people and agents. Commits, branches and pull
requests follow `git-conventions`.
