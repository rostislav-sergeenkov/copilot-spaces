# Release Checklist

Follow this prescriptive checklist for every release to ensure safe, reliable deployments.

## Pre-release Preparation

- [ ] **All acceptance criteria met**: Verify all features/fixes in the release meet their acceptance criteria
- [ ] **PRs merged**: All planned PRs have been reviewed, approved, and merged to the release branch
- [ ] **CI passing**: All automated tests, linting, and security scans pass on the release branch
- [ ] **Security scans complete**: No critical or high-severity vulnerabilities in dependencies or code
- [ ] **Release notes drafted**: Clear, user-facing release notes prepared with version, date, and notable changes
- [ ] **Rollback plan documented**: Document steps to rollback if deployment fails or causes issues
- [ ] **Smoke tests prepared**: Define and document smoke tests to run post-deployment
- [ ] **Deployment window scheduled**: Notify stakeholders of deployment time (if applicable)
- [ ] **Backup or snapshot**: Create backup/snapshot of production data or configuration (if applicable)

## Deployment

- [ ] **Deploy to staging**: Deploy release candidate to staging environment
- [ ] **Run smoke tests on staging**: Verify critical paths work as expected in staging
- [ ] **Deploy to production**: Execute production deployment via automated pipeline (preferred) or manual runbook
- [ ] **Monitor deployment**: Watch logs, metrics, and alerts during and immediately after deployment
- [ ] **Run post-deploy verifications**: Execute smoke tests to verify production is functioning correctly

## Post-deployment

- [ ] **Verify key metrics**: Check error rates, latency, and usage metrics are within expected ranges
- [ ] **Announce release**: Notify stakeholders, support teams, and relevant channels of successful deployment
- [ ] **Monitor for issues**: Continue monitoring for 24-48 hours for unexpected issues
- [ ] **Update documentation**: Ensure user-facing docs reflect any new features or changes
- [ ] **Close release milestone**: Mark release complete in project tracking system

## Rollback Steps (If Needed)

If a deployment fails or causes a critical issue:

- [ ] **Trigger incident response**: Notify on-call and incident response team immediately
- [ ] **Execute rollback**: Revert to last known-good release using documented rollback plan
- [ ] **Verify rollback successful**: Run smoke tests to confirm system is stable
- [ ] **Communicate status**: Update stakeholders on incident status and timeline
- [ ] **Triage root cause**: Conduct post-incident review to identify root cause
- [ ] **Document action items**: Capture learnings and action items to prevent recurrence
