# Development Phase Template

## Overview

The Development phase transforms the approved design into working software. This phase focuses on code quality, implementation standards, and iterative delivery.

---

## Implementation Details

### Sprint/Iteration Overview

| Sprint | Start Date | End Date | Goals | Status |
|--------|------------|----------|-------|--------|
| Sprint 1 | | | | Not Started / In Progress / Complete |
| Sprint 2 | | | | Not Started / In Progress / Complete |
| Sprint 3 | | | | Not Started / In Progress / Complete |

### Feature Breakdown

| Feature | Priority | Assigned To | Branch | Status |
|---------|----------|-------------|--------|--------|
| | High/Medium/Low | | | |
| | High/Medium/Low | | | |

---

## Code Log

### Significant Changes

| Date | Author | Change Description | PR/Commit | Impact |
|------|--------|-------------------|-----------|--------|
| | | | | |
| | | | | |

### Technical Debt Log

| ID | Description | Priority | Estimated Effort | Status |
|----|-------------|----------|------------------|--------|
| TD-001 | | | | Open / Resolved |
| TD-002 | | | | Open / Resolved |

### Dependencies Added

| Package | Version | Purpose | Security Reviewed |
|---------|---------|---------|-------------------|
| | | | Yes / No |
| | | | Yes / No |

---

## Development Standards

### Code Quality Gates

- [ ] Code follows established style guide
- [ ] Unit tests written and passing
- [ ] Code coverage meets minimum threshold (>80%)
- [ ] Static analysis passed (linting, type checking)
- [ ] No critical security vulnerabilities
- [ ] Documentation updated

### Branching Strategy

```
main
  └── develop
        ├── feature/[feature-name]
        ├── bugfix/[bug-name]
        └── hotfix/[hotfix-name]
```

### Commit Message Format

```
type(scope): description

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

---

## Agent Prompts

> **💡 Agent Guidance**: Use these prompts to drive AI-assisted development activities.

### Code Review
```
Review the following code for best practices, potential bugs, performance issues, and security vulnerabilities:
[Insert code snippet or PR link]
```

### Refactoring Suggestions
```
Analyze this code and suggest refactoring improvements to enhance readability, maintainability, and performance:
[Insert code snippet]
```

### Test Generation
```
Generate comprehensive unit tests for the following function/class, covering edge cases and error scenarios:
[Insert code]
```

### Documentation Generation
```
Generate documentation for the following code, including function descriptions, parameter explanations, and usage examples:
[Insert code]
```

### Debugging Assistance
```
Help debug the following issue. The expected behavior is [expected], but the actual behavior is [actual]:
[Insert code and error details]
```

### Security Review
```
Perform a security review of this code and identify potential vulnerabilities (injection, XSS, authentication issues, etc.):
[Insert code]
```

---

## Development Checklist

### Pre-Development

- [ ] Design documents reviewed and understood
- [ ] Development environment set up
- [ ] Branch created from latest develop
- [ ] Task/story requirements clear

### During Development

- [ ] Code follows established patterns and standards
- [ ] Unit tests written alongside code
- [ ] Comments added for complex logic
- [ ] No hardcoded secrets or credentials
- [ ] Error handling implemented
- [ ] Logging added for key operations

### Pre-Merge

- [ ] All tests passing
- [ ] Code review completed and approved
- [ ] Static analysis passing
- [ ] Documentation updated
- [ ] Breaking changes documented
- [ ] Feature flag configured (if applicable)

### Post-Merge

- [ ] Feature tested in integration environment
- [ ] Monitoring confirms no issues
- [ ] Stakeholders notified of completion

---

## Environment Configuration

### Development Environments

| Environment | URL | Purpose | Access |
|-------------|-----|---------|--------|
| Local | localhost | Individual development | Developer |
| Dev | | Integration testing | Team |
| Staging | | Pre-production validation | Team + QA |

### Configuration Management

| Config Item | Source | Environment Variable |
|-------------|--------|---------------------|
| | | |
| | | |

---

## Review and Approval

### Code Review Requirements

- Minimum 1 approving review required
- All automated checks must pass
- Security-sensitive changes require security team review

### Developer Sign-Off

| Developer | Date | Confirmation |
|-----------|------|--------------|
| | | Code complete and tested |
| | | Peer review addressed |

---

## Notes and Observations

<!-- Document any implementation notes, workarounds, or lessons learned -->

---

*Template Version: 1.0 | Last Updated: YYYY-MM-DD*
