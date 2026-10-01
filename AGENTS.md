# AGENTS.md

This is the `workoho` organization's public `.github` repository. GitHub reads
the files in it as defaults for every repository of the organization, private
ones included, and as the organization's public profile. There is no build, no
test and no CI. `README.md` has the layout.

## Commands

```bash
git status                       # nothing else is needed to check a change
gh api "repos/workoho/<repo>/community/profile"  # what a repository inherits
```

`gh` is assumed and declared nowhere else. A missing one is named with its
install command, not worked around. Run `gh auth status` first.

## Rules

- **This repository is public, and so is every file in it.** No customer
  names, no internal URLs, no secrets, no tenant identifiers.
- **A default ships to every repository that has no file of its own.** Before
  you change one, think about the repositories that inherit it. Issue
  templates are all or nothing: a repository with its own `ISSUE_TEMPLATE`
  folder ignores the defaults completely.
- **Issue and pull request templates take the marker names from the
  `git-conventions` skill** in the `wkho-code` plugin. A name spelled in two
  places drifts apart in one of them.
- `profile/README.md` is the public organization profile. Do not change its
  wording without Julian's word. `profile/workoho-wordmark*.svg` are copies of
  the files in the `visual-identity` skill of the `wkho` plugin, and a change
  to a mark is a pull request in `workoho/brand`.
- There is no `LICENSE` here, because GitHub does not inherit one.
- No `workflow-templates/` on purpose. The starting points for workflows live
  in the `repo-setup` skill, and a second copy would drift.
- American spellings in every English text a person reads, British forms never;
  quoted wording keeps its original.

## Working here

- Allowed without asking: reading anything, creating a branch, committing on
  your own branch.
- Never without an explicit instruction: pushing to `main`, `gh pr merge`,
  changing repository or organization settings.
- Force push: on your own pull request branch with `--force-with-lease`, never
  on `main`, never on someone else's branch.
- Commits, branches and pull requests follow the `git-conventions` skill in the
  `wkho-code` plugin.
