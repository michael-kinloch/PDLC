# Testing Phase Template

## Overview

The Testing phase validates that the developed solution meets requirements, functions correctly, and is ready for production release. This phase covers all testing activities from unit tests to user acceptance testing.

---

## Test Plan

### Testing Scope

| Category | In Scope | Out of Scope |
|----------|----------|--------------|
| Features | | |
| Integrations | | |
| Environments | | |

### Testing Types

| Test Type | Description | Responsibility | Tool |
|-----------|-------------|----------------|------|
| Unit Testing | Individual component validation | Developers | |
| Integration Testing | Component interaction validation | Developers/QA | |
| E2E Testing | Full workflow validation | QA | |
| Performance Testing | Load and stress validation | QA/DevOps | |
| Security Testing | Vulnerability assessment | Security Team | |
| UAT | User acceptance validation | Product/Users | |

### Testing Schedule

| Phase | Start Date | End Date | Status |
|-------|------------|----------|--------|
| Unit Testing | | | |
| Integration Testing | | | |
| System Testing | | | |
| Performance Testing | | | |
| Security Testing | | | |
| UAT | | | |

---

## Test Coverage

### Coverage Targets

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| Line Coverage | 80% | | |
| Branch Coverage | 75% | | |
| Function Coverage | 90% | | |

### Coverage by Component

| Component | Line % | Branch % | Status |
|-----------|--------|----------|--------|
| | | | Pass / Fail |
| | | | Pass / Fail |

---

## Test Cases

### Critical Test Scenarios

| ID | Scenario | Steps | Expected Result | Status |
|----|----------|-------|-----------------|--------|
| TC-001 | | | | Pass / Fail / Blocked |
| TC-002 | | | | Pass / Fail / Blocked |
| TC-003 | | | | Pass / Fail / Blocked |

### Edge Cases

| ID | Edge Case | Test Approach | Status |
|----|-----------|---------------|--------|
| EC-001 | | | |
| EC-002 | | | |

### Regression Test Suite

- [ ] Core functionality tests passing
- [ ] Critical path tests passing
- [ ] Integration tests passing
- [ ] No new regressions introduced

---

## Defect Tracking

### Defect Summary

| Severity | Open | In Progress | Resolved | Closed |
|----------|------|-------------|----------|--------|
| Critical | | | | |
| High | | | | |
| Medium | | | | |
| Low | | | | |

### Open Defects

| ID | Title | Severity | Assigned To | Status |
|----|-------|----------|-------------|--------|
| | | | | |
| | | | | |

---

## Agent Prompts

> **💡 Agent Guidance**: Use these prompts to drive AI-assisted testing activities.

### Test Case Generation
```
Generate comprehensive test cases for the following feature, including happy path, edge cases, and error scenarios:
[Insert feature description]
```

### Test Data Generation
```
Generate realistic test data sets for the following scenarios and data model:
Scenarios: [Insert scenarios]
Data Model: [Insert model]
```

### Bug Analysis
```
Analyze the following bug report and suggest potential root causes and areas of investigation:
[Insert bug details]
```

### Test Coverage Analysis
```
Review the following code and existing tests, then identify gaps in test coverage and suggest additional test cases:
[Insert code and tests]
```

### Performance Test Design
```
Design a performance testing strategy for the following system, including load profiles, metrics to measure, and acceptance criteria:
[Insert system description]
```

### Security Test Cases
```
Generate security test cases for the following feature, covering OWASP Top 10 vulnerabilities:
[Insert feature description]
```

---

## QA Checklist

### Pre-Testing

- [ ] Test environment configured and accessible
- [ ] Test data prepared
- [ ] Test accounts and credentials available
- [ ] Test tools configured
- [ ] Build deployed to test environment

### Functional Testing

- [ ] All acceptance criteria validated
- [ ] Happy path scenarios pass
- [ ] Error handling verified
- [ ] Boundary conditions tested
- [ ] Cross-browser testing complete (if applicable)
- [ ] Mobile responsiveness verified (if applicable)

### Non-Functional Testing

- [ ] Performance benchmarks met
- [ ] Load testing completed
- [ ] Security scan passed
- [ ] Accessibility requirements verified
- [ ] Usability validated

### Test Completion

- [ ] All critical and high defects resolved
- [ ] Test coverage targets met
- [ ] Regression suite passing
- [ ] Test summary report generated
- [ ] Sign-off obtained from stakeholders

---

## Test Environments

| Environment | Purpose | URL | Status |
|-------------|---------|-----|--------|
| QA | Functional testing | | |
| Staging | Pre-production validation | | |
| Performance | Load testing | | |

---

## Test Summary Report

### Executive Summary

<!-- High-level summary of testing outcomes -->

### Test Execution Summary

| Metric | Value |
|--------|-------|
| Total Test Cases | |
| Passed | |
| Failed | |
| Blocked | |
| Pass Rate | |

### Recommendations

- [ ] Proceed to release
- [ ] Proceed with known issues (list below)
- [ ] Additional testing required
- [ ] Not ready for release

### Known Issues for Release

| ID | Description | Workaround | Target Fix Version |
|----|-------------|------------|-------------------|
| | | | |

---

## Sign-Off

| Role | Name | Date | Approval |
|------|------|------|----------|
| QA Lead | | | Approved / Rejected |
| Product Owner | | | Approved / Rejected |
| Technical Lead | | | Approved / Rejected |

---

## Notes and Observations

<!-- Document any testing observations, risks, or recommendations -->

---

*Template Version: 1.0 | Last Updated: YYYY-MM-DD*
