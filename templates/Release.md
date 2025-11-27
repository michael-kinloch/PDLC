# Release Phase Template

## Overview

The Release phase manages the transition of validated software from testing to production. This phase ensures controlled, documented, and reversible deployments.

---

## Release Notes

### Release Information

| Field | Value |
|-------|-------|
| **Release Version** | |
| **Release Date** | |
| **Release Manager** | |
| **Release Type** | Major / Minor / Patch / Hotfix |

### What's New

#### Features

| Feature | Description | Documentation |
|---------|-------------|---------------|
| | | |
| | | |

#### Improvements

| Improvement | Description |
|-------------|-------------|
| | |
| | |

#### Bug Fixes

| Bug ID | Description | Severity |
|--------|-------------|----------|
| | | |
| | | |

### Breaking Changes

| Change | Impact | Migration Steps |
|--------|--------|-----------------|
| | | |

### Known Issues

| Issue | Workaround | Target Fix Version |
|-------|------------|-------------------|
| | | |

### Dependencies

| Dependency | Version | Notes |
|------------|---------|-------|
| | | |

---

## Deployment Plan

### Pre-Deployment Checklist

- [ ] Release notes finalized
- [ ] All tests passing in staging
- [ ] Database migrations tested
- [ ] Rollback plan documented
- [ ] Stakeholders notified of deployment window
- [ ] Support team briefed
- [ ] Monitoring dashboards prepared

### Deployment Sequence

| Step | Action | Responsible | Duration | Verification |
|------|--------|-------------|----------|--------------|
| 1 | Enable maintenance mode (if needed) | | | |
| 2 | Database backup | | | |
| 3 | Run database migrations | | | |
| 4 | Deploy application | | | |
| 5 | Run smoke tests | | | |
| 6 | Disable maintenance mode | | | |
| 7 | Monitor for issues | | | |

### Deployment Environments

| Environment | Deploy Order | Bake Time | Approval Required |
|-------------|--------------|-----------|-------------------|
| Staging | 1 | 24 hours | No |
| Production (Canary) | 2 | 1 hour | Yes |
| Production (Full) | 3 | - | Yes |

### Rollback Plan

#### Rollback Triggers

- [ ] Error rate exceeds threshold (>X%)
- [ ] Critical functionality broken
- [ ] Security vulnerability discovered
- [ ] Performance degradation (>X% slowdown)

#### Rollback Steps

| Step | Action | Responsible | Duration |
|------|--------|-------------|----------|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## Agent Prompts

> **💡 Agent Guidance**: Use these prompts to drive AI-assisted release activities.

### Release Notes Generation
```
Generate release notes from the following commit log and issue tracker entries, organizing by features, improvements, and bug fixes:
[Insert commit log or PR list]
```

### Deployment Script Review
```
Review this deployment script for potential issues, missing steps, and best practices:
[Insert deployment script]
```

### Impact Analysis
```
Analyze the potential impact of this release on existing functionality, integrations, and user experience:
[Insert release summary]
```

### Rollback Plan Validation
```
Evaluate this rollback plan for completeness and identify any gaps or risks:
[Insert rollback plan]
```

### Communication Draft
```
Draft a release announcement for [internal/external] stakeholders based on the following release notes:
[Insert release notes]
```

### Post-Deployment Monitoring
```
Suggest key metrics and alerts to monitor after deploying the following changes:
[Insert change summary]
```

---

## Review Checklist

### Release Readiness

- [ ] All planned features completed
- [ ] QA sign-off obtained
- [ ] Security review completed
- [ ] Performance benchmarks met
- [ ] Documentation updated
- [ ] Release notes reviewed and approved
- [ ] Deployment plan reviewed

### Deployment Verification

- [ ] Smoke tests passing in production
- [ ] Core functionality verified
- [ ] Integrations functioning
- [ ] No error spikes in logs
- [ ] Performance within acceptable range
- [ ] User-facing features accessible

### Post-Deployment

- [ ] Stakeholders notified of successful deployment
- [ ] Monitoring dashboards reviewed
- [ ] Support team confirmed readiness
- [ ] Release tagged in version control
- [ ] Documentation published
- [ ] Retrospective scheduled (if applicable)

---

## Communication Plan

### Pre-Release Communication

| Audience | Message | Channel | Timing |
|----------|---------|---------|--------|
| Internal Teams | Deployment window | Email/Slack | 48 hours before |
| Support Team | Feature briefing | Meeting | 24 hours before |
| Customers | Maintenance notice (if any) | Status Page | 24 hours before |

### Post-Release Communication

| Audience | Message | Channel | Timing |
|----------|---------|---------|--------|
| Internal Teams | Deployment complete | Email/Slack | Immediately after |
| Customers | Release announcement | Blog/Email | Within 24 hours |

---

## Metrics and Monitoring

### Key Metrics to Watch

| Metric | Baseline | Threshold | Dashboard |
|--------|----------|-----------|-----------|
| Error Rate | | | |
| Response Time (p95) | | | |
| Throughput | | | |
| CPU Utilization | | | |
| Memory Usage | | | |

### Alert Configuration

| Alert | Condition | Severity | Notification |
|-------|-----------|----------|--------------|
| | | | |
| | | | |

---

## Sign-Off

### Pre-Deployment Approval

| Role | Name | Date | Approval |
|------|------|------|----------|
| Release Manager | | | |
| QA Lead | | | |
| Technical Lead | | | |
| Product Owner | | | |

### Post-Deployment Verification

| Role | Name | Date | Status |
|------|------|------|--------|
| Release Manager | | | Verified / Issues Found |
| Operations | | | Verified / Issues Found |

---

## Notes and Observations

<!-- Document any release notes, issues encountered, or lessons learned -->

---

*Template Version: 1.0 | Last Updated: YYYY-MM-DD*
