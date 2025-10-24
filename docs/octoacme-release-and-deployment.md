# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist

For a comprehensive, step-by-step release process, refer to the [Release Checklist](checklists/release-checklist.md).

- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook

If a deployment fails or causes a critical issue:

1. **Trigger incident response**: Notify on-call and incident response team immediately
2. **Execute rollback**: Revert to last known-good release using documented rollback plan (version control, container registry, or infrastructure-as-code)
3. **Verify rollback**: Run smoke tests to confirm system is stable and functioning correctly
4. **Communicate status**: Update stakeholders on incident status, impact, and expected resolution timeline
5. **Triage root cause**: Conduct post-incident review to identify root cause and contributing factors
6. **Document action items**: Capture learnings and create action items to prevent recurrence

**Rollback procedures should be**:
- Documented and tested before each release
- Executable within 15 minutes for critical services
- Validated in staging environment periodically

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
