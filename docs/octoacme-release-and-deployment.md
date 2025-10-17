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
- Release notes drafted (Technical Writer)
- Rollback / mitigation plan documented (DevOps)
- Smoke tests prepared
- Monitoring and alerting configured (DevOps)
- Support team enablement completed (Support Lead)
- UI/UX acceptance review for user-facing changes (UX Designer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Release Readiness Checklist (by Role)

### Development Team
- [ ] All PRs merged and acceptance criteria verified
- [ ] Automated tests passing in CI

### DevOps Engineer
- [ ] Monitoring and alerting configured
- [ ] Rollback plan validated and documented
- [ ] Infrastructure and deployment pipeline ready

### Technical Writer
- [ ] Release notes completed and reviewed
- [ ] Documentation updated for new features
- [ ] Knowledge base articles published or updated

### Support Lead
- [ ] Support team trained on new features
- [ ] Escalation paths confirmed
- [ ] Support playbooks and FAQs updated

### UX Designer (if user-facing changes)
- [ ] UI/UX acceptance review completed
- [ ] Accessibility compliance verified

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
