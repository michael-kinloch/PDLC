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

## SpecKit Integration (Spec-Driven Development)

> **📋 GitHub SpecKit**: This section integrates [GitHub SpecKit](https://github.com/github/spec-kit) for spec-driven development with AI agents. SpecKit ensures predictable outcomes by making specifications executable artifacts that drive implementation.

### SpecKit Workflow Commands

Use these slash commands with your AI coding agent (Copilot, Claude Code, Cursor, etc.):

| Command | Purpose | When to Use |
|---------|---------|-------------|
| `/speckit.constitution` | Define project principles and guidelines | Project setup, governance updates |
| `/speckit.specify` | Create feature specification (what & why) | Before implementation planning |
| `/speckit.plan` | Generate technical implementation plan | After spec approval |
| `/speckit.tasks` | Break down plan into actionable tasks | After plan review |
| `/speckit.implement` | Execute tasks according to plan | Development phase |

### Feature Specification Template

For each feature, create a spec following this structure:

```markdown
# Feature Specification: [FEATURE NAME]

**Feature Branch**: `[###-feature-name]`  
**Created**: [DATE]  
**Status**: Draft | In Review | Approved

## User Scenarios & Testing

### User Story 1 - [Title] (Priority: P1)
[Description of user journey]

**Acceptance Scenarios**:
1. **Given** [state], **When** [action], **Then** [outcome]

## Requirements

### Functional Requirements
- **FR-001**: System MUST [capability]
- **FR-002**: Users MUST be able to [action]

### Key Entities
- **[Entity]**: [Description, attributes, relationships]

## Success Criteria
- **SC-001**: [Measurable outcome]
```

### Implementation Plan Template

```markdown
# Implementation Plan: [FEATURE]

**Branch**: `[###-feature-name]` | **Date**: [DATE]

## Technical Context
**Language/Version**: [e.g., Python 3.11, TypeScript 5.0]  
**Primary Dependencies**: [e.g., FastAPI, React]  
**Storage**: [e.g., PostgreSQL, MongoDB]  
**Testing**: [e.g., pytest, Jest]

## Project Structure
[Define source layout per project type]

## Constitution Check
[Validate against project principles]
```

### Task Breakdown Template

```markdown
# Tasks: [FEATURE NAME]

## Phase 1: Setup
- [ ] T001 Create project structure
- [ ] T002 Initialize dependencies

## Phase 2: User Story 1 (Priority: P1) 🎯 MVP
**Goal**: [What this story delivers]

### Implementation
- [ ] T003 [P] Create [Entity] model in src/models/
- [ ] T004 Implement [Service] in src/services/
- [ ] T005 Add [endpoint] in src/api/

**Checkpoint**: User Story 1 functional and testable
```

### SpecKit Agent Prompts

#### Specify a Feature
```
/speckit.specify Build [feature description]. It should allow users to [key capabilities]. 
Focus on [primary user value]. Include [specific requirements].
```

#### Create Implementation Plan
```
/speckit.plan Using [technology stack]. The application should [architectural approach]. 
Use [database/storage]. Follow [coding standards/patterns].
```

#### Generate Tasks
```
/speckit.tasks Break down the implementation plan into actionable tasks organized by user story.
Include parallel task markers [P] and checkpoints for each story.
```

#### Execute Implementation
```
/speckit.implement Execute tasks in order, respecting dependencies. 
Commit after each logical task group. Validate at each checkpoint.
```

### SpecKit Feature Tracker

| Feature ID | Feature Name | Spec Status | Plan Status | Tasks Status | Implementation |
|------------|--------------|-------------|-------------|--------------|----------------|
| 001 | | Draft / Approved | Draft / Approved | Generated / In Progress | Not Started / In Progress / Complete |
| 002 | | Draft / Approved | Draft / Approved | Generated / In Progress | Not Started / In Progress / Complete |

### SpecKit Directory Structure

```
.specify/
├── memory/
│   └── constitution.md      # Project principles and guidelines
├── specs/
│   └── [###-feature-name]/
│       ├── spec.md          # Feature specification
│       ├── plan.md          # Implementation plan
│       ├── tasks.md         # Task breakdown
│       ├── research.md      # Technical research
│       └── data-model.md    # Entity definitions
└── templates/
    ├── spec-template.md
    ├── plan-template.md
    └── tasks-template.md
```

### SpecKit Checklist

- [ ] Project constitution defined (`.specify/memory/constitution.md`)
- [ ] Feature specification created and reviewed
- [ ] Technical plan approved by architect
- [ ] Tasks generated and prioritized
- [ ] User stories independently testable
- [ ] Implementation follows task order
- [ ] Checkpoints validated at each story completion

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
