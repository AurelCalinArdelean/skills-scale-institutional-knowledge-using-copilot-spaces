```markdown
# Release & Deployment Checklist (OctoAcme)

Standard checklist to reduce risk and improve release quality.

Pre-release
- [ ] All acceptance criteria met for planned items
- [ ] All PRs merged, CI green, and security scans passed
- [ ] Release notes drafted and owner assigned
- [ ] Rollback/mitigation plan documented
- [ ] Stakeholders and support notified of upcoming release
- [ ] Staging environment smoke tests prepared and owner assigned

Staging verification
- [ ] Deploy to staging via CI/CD pipeline
- [ ] Run automated smoke tests and manual verification for critical flows
- [ ] Verify metrics and alerts are functioning as expected
- [ ] Sign-off from QA and PM for production rollout

Production deploy
- [ ] Deployment window scheduled (if applicable)
- [ ] Backup/snapshot created if applicable
- [ ] Production deploy via automated pipeline
- [ ] Post-deploy verification steps executed (monitoring, smoke tests)
- [ ] Announce release to stakeholders and support channel

Post-release
- [ ] Monitor for regressions and critical alerts for at least N hours (define per release)
- [ ] Open follow-up tasks for cleanup or improvements discovered in the release
- [ ] Run a short retrospective if the release had incidents or was high-risk

Incident response (if needed)
- [ ] Trigger incident runbook and notify on-call
- [ ] Escalate per the project's escalation path
- [ ] Record timeline, RCA, and action items; add to retrospective
```
