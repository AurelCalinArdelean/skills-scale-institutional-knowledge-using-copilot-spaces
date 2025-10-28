```markdown
# Pull Request Checklist (OctoAcme)

Use this checklist on all feature/change PRs to improve review speed and release readiness.

- [ ] Link to related issue(s) and the project one-pager (if relevant)
- [ ] Include clear acceptance criteria in the PR description
- [ ] Keep PRs small and focused (aim <= 400 lines of changes)
- [ ] Automated tests added/updated and all CI checks pass
- [ ] Security and linting scans pass
- [ ] Add testing instructions / reproduction steps in the PR body
- [ ] Update docs or changelog when behavior changes
- [ ] Assign reviewers and set expected review context (what to look for)
- [ ] Mark the PR with the appropriate labels (e.g., bug, feature, docs)
- [ ] If the change impacts UX, attach screenshots or a short demo video
- [ ] Confirm whether this requires a migration or release note

Reviewer guidance:
- Verify acceptance criteria are testable.
- Run the provided testing steps or smoke tests when needed.
- Check for adequate automated test coverage for new logic.

Merge rules:
- At least one required approval (or team-defined approval policy) and all CI checks successful.
- For larger or riskier changes, consider an additional reviewer from a dependent team.
```
