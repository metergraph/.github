# Public contribution rules

This repository is public. Before publishing a branch, commit, issue, pull
request, comment, release, screenshot, fixture, or log:

- Use a self-contained public description. Keep private tracker IDs, links,
  discussion, and customer context in the internal tracker. Do not put them in
  public branch names, commit messages, issue or PR titles and bodies, or
  release notes.
- Remove secrets, tokens, non-public customer or prospect names and domains,
  tenant or workspace IDs, captured prompts or responses, private paths, and
  cloud account or resource IDs. Use synthetic examples and `example.com`.
- Inspect the exact diff and all metadata before pushing or posting. A CI
  failure after publication cannot undo disclosure.
- Report a suspected vulnerability privately to maintainers. Do not include
  exploit details in a public issue.

If unsure whether a detail is public, stop and ask before publishing. Existing
harmless issue IDs in history do not, by themselves, require rewriting history.
