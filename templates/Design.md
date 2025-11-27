# Design Phase Template

## Overview

The Design phase translates discovery findings into a concrete solution architecture. This phase ensures technical feasibility, defines system boundaries, and establishes the blueprint for development.

---

## Solution Architecture

### High-Level Architecture

<!-- Describe or diagram the overall solution architecture -->

```
[Insert architecture diagram or description]
```

### Component Overview

| Component | Purpose | Technology | Owner |
|-----------|---------|------------|-------|
| | | | |
| | | | |

### Integration Points

| System | Integration Type | Protocol | Data Flow |
|--------|------------------|----------|-----------|
| | | | |
| | | | |

---

## Design Decisions

### Architecture Decision Records (ADRs)

#### ADR-001: [Decision Title]

| Field | Details |
|-------|---------|
| **Status** | Proposed / Accepted / Deprecated |
| **Context** | |
| **Decision** | |
| **Consequences** | |
| **Alternatives Considered** | |

#### ADR-002: [Decision Title]

| Field | Details |
|-------|---------|
| **Status** | Proposed / Accepted / Deprecated |
| **Context** | |
| **Decision** | |
| **Consequences** | |
| **Alternatives Considered** | |

### Technology Stack

| Layer | Technology | Justification |
|-------|------------|---------------|
| Frontend | | |
| Backend | | |
| Database | | |
| Infrastructure | | |
| Monitoring | | |

---

## Non-Functional Requirements (NFRs)

### Performance

| Metric | Target | Measurement |
|--------|--------|-------------|
| Response Time | | |
| Throughput | | |
| Latency | | |

### Scalability

- **Horizontal Scaling**: 
- **Vertical Scaling**: 
- **Expected Load**: 

### Security

- [ ] Authentication mechanism defined
- [ ] Authorization model documented
- [ ] Data encryption requirements specified
- [ ] Compliance requirements identified (GDPR, SOC2, etc.)

### Reliability

| Metric | Target |
|--------|--------|
| Availability | |
| Recovery Time Objective (RTO) | |
| Recovery Point Objective (RPO) | |

### Maintainability

- [ ] Logging strategy defined
- [ ] Monitoring approach documented
- [ ] Alerting thresholds established

---

## Agent Prompts

> **💡 Agent Guidance**: Use these prompts to drive AI-assisted design activities.

### Architecture Review
```
Review the following architecture design and identify potential bottlenecks, single points of failure, and scalability concerns:
[Insert architecture description]
```

### Technology Selection
```
Given the following requirements and constraints, recommend an appropriate technology stack with justification:
Requirements: [Insert requirements]
Constraints: [Insert constraints]
```

### Security Assessment
```
Analyze this design for security vulnerabilities and recommend security controls and best practices:
[Insert design summary]
```

### NFR Validation
```
Evaluate whether the proposed design meets the following non-functional requirements and suggest improvements:
[Insert NFRs and design details]
```

### API Design
```
Design RESTful API endpoints for the following use cases, following best practices:
[Insert use cases]
```

---

## Review Checklist

### Design Review Criteria

- [ ] **Completeness**: All components and integrations documented
- [ ] **Feasibility**: Technical approach is proven and achievable
- [ ] **Scalability**: Design supports expected growth
- [ ] **Security**: Security requirements addressed in design
- [ ] **Performance**: Performance targets are achievable with proposed design
- [ ] **Maintainability**: Design supports easy maintenance and updates
- [ ] **Cost**: Infrastructure costs estimated and within budget
- [ ] **Dependencies**: External dependencies identified and managed
- [ ] **Standards**: Design follows organizational standards and patterns

### Design Approval

| Role | Name | Date | Status |
|------|------|------|--------|
| Architect | | | Pending / Approved |
| Security Reviewer | | | Pending / Approved |
| Technical Lead | | | Pending / Approved |

---

## Diagrams and Artifacts

### Required Diagrams

- [ ] System Context Diagram
- [ ] Container Diagram
- [ ] Component Diagram (if needed)
- [ ] Data Flow Diagram
- [ ] Sequence Diagrams (for key flows)

### Artifact Links

| Artifact | Location |
|----------|----------|
| Architecture Diagrams | |
| API Specifications | |
| Data Models | |
| Security Review | |

---

## Notes and Observations

<!-- Document any additional context, decisions, or observations -->

---

*Template Version: 1.0 | Last Updated: YYYY-MM-DD*
