# Contributing to CampusDesk (Group 14)

Everyone's commits and pull requests are graded, so follow these rules.

## Branches

- `main` is protected. Nobody pushes to it directly.
- `develop` is where finished features come together.
- Create your branch from `develop` and include the Jira key:
- `feature/CD-19-create-ticket`
- `fix/CD-31-login-error`
- `docs/CD-11-requirements`

## Commit messages

Start with the Jira key and a verb, and say what changed:

- Good: `CD-19 Add ticket form validation`
- Bad: `update`, `stuff`, `final final`

Commit small and often. Five commits over a week beat 40 the night before.

## Pull requests

1. Open a PR from your branch into `develop`.
2. One feature per PR. Add a short description, and a screenshot if the UI changed.
3. Ask for a review in Slack #dev.
4. A different member reviews it, leaves at least one comment, and approves it.
5. Merge, then move the Jira card to Done.

At the end of each sprint, `develop` is merged into `main` through a PR.
