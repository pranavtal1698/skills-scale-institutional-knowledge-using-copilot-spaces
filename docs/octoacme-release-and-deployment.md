# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (reviewed by Security Lead)
- Release notes drafted
- Rollback / mitigation plan documented (coordinated with DevOps Engineer)
- Smoke tests prepared (QA/Testing team)
- Support team prepared (Support Lead notified)
- Design verification complete (UX/UI Designer sign-off if applicable)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA/Testing)
- [ ] Security final verification (Security Lead)
- [ ] Deploy to production (automated pipeline preferred, managed by DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Support Lead)
- [ ] Monitor for issues in production (DevOps Engineer)

For detailed handoff to support team, see [Cross-Functional Handoff Checklist](octoacme-cross-functional-handoffs.md).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer and Support Lead)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Triage root cause and capture action items
  - Coordinate with Security Lead if security-related
  - Update support team on status and workarounds (Support Lead)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
