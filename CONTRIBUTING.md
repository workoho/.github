# Contributing to Workoho repositories

This is the default for every Workoho repository without a `CONTRIBUTING.md`
of its own. A repository's own file wins.

- **Open an issue first** when the change is more than a typo or a small fix,
  so you do not build something we cannot take.
- **Write in English.** A repository whose issues and history are in German
  keeps that language.
- **Commit messages** follow
  [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), for
  example `fix(ui): make the sticky top bar stick`. Imperative subject,
  lowercase, no period, at most 100 characters. Leave issue numbers out of commit messages;
  they belong in the pull request body.
- **Pull request title** is a Conventional Commits title. Maintainers add the
  review-time bracket at the end, you do not have to.
- **Pull request body** stays under 200 words and uses the markers in the
  template: `Symptom:` or `Gap:`, `Change:`, `Verified:`.
- **One change per pull request.** We squash on merge.
- **Run the repository's checks before you push.** Its `AGENTS.md` or README
  names the command.
- **If an AI agent wrote part of the text or the code, say so.**
- **Never put a secret or a customer's data into an issue, a pull request or a
  commit.** A secret that reaches the history counts as burnt.

Security problems go through [SECURITY.md](SECURITY.md), not an issue.
