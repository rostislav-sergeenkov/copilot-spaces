# PR & CI Checklist

Use this checklist before opening a pull request to ensure quality and traceability.

## Before Opening a PR

- [ ] **Issue link**: PR description references the related issue (e.g., "Refs #123" or "Fixes #456")
- [ ] **Acceptance criteria**: PR description includes or references the acceptance criteria from the issue
- [ ] **Tests included**: Unit tests and/or integration tests added for new functionality or bug fixes
- [ ] **CI passing**: All automated tests, linting, and security scans pass successfully
- [ ] **PR size**: Keep PR small and focused (<= 400 lines when possible) for faster review
- [ ] **Required approvals**: At least one approval from a team member (or as defined by team policy)
- [ ] **Security scans**: No new security vulnerabilities introduced; CodeQL or other security tools pass
- [ ] **Documentation**: Update relevant docs if the change affects user-facing features or APIs
- [ ] **Commit messages**: Clear, descriptive commit messages that explain what and why

## During Review

- [ ] Address review comments promptly
- [ ] Re-request review after making changes
- [ ] Ensure CI stays green after addressing feedback

## Before Merging

- [ ] Final CI check passes
- [ ] All conversations resolved
- [ ] No merge conflicts with target branch
