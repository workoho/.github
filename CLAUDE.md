@AGENTS.md

## Claude Code specifics

- `.claude/settings.json` declares the `wkho` and `wkho-code` plugins and sets
  `attribution.pr` to the AI disclosure line. You still read the pull request
  body back afterwards and count the line: one is right.
- The `allow` list holds `git status` and nothing else.
