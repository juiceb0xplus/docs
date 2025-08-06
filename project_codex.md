# PROJECT CODEX STANDARD
## Documentation Standard v1.0 (Revised)
### A Comprehensive Standard for AI-Managed Solo Development Documentation

---

**Generated:** December 2024  
**Version:** 1.0 (Revised)  
**Status:** Active  

---

## Table of Contents

1. [Foundation & Philosophy](#1-foundation--philosophy)
   - 1.1 [Core Philosophy: Cognitive Symbiosis](#11-core-philosophy-cognitive-symbiosis)
   - 1.2 [Fundamental Axioms](#12-fundamental-axioms)
   - 1.3 [The Three Pillars](#13-the-three-pillars)
2. [Information Architecture](#2-information-architecture)
   - 2.1 [Directory Structure & Purpose](#21-directory-structure--purpose)
   - 2.2 [Document Taxonomy](#22-document-taxonomy)
   - 2.3 [State Management Model](#23-state-management-model)
3. [Document Formats & Templates](#3-document-formats--templates)
   - 3.1 [The Sacred Manifest Format](#31-the-sacred-manifest-format)
   - 3.2 [Product Feature Template](#32-product-feature-template)
   - 3.3 [Technical Specification Template](#33-technical-specification-template)
   - 3.4 [Decision Record Template](#34-decision-record-template)
4. [AI Agent Behavioral Specifications](#4-ai-agent-behavioral-specifications)
   - 4.1 [Agent Roles & Responsibilities](#41-agent-roles--responsibilities)
   - 4.2 [Synthesis Rules](#42-synthesis-rules)
   - 4.3 [Path Resolution Matrix](#43-path-resolution-matrix)
   - 4.4 [Quality Guarantees](#44-quality-guarantees)
5. [Lifecycle Management](#5-lifecycle-management)
   - 5.1 [Input Processing Pipeline](#51-input-processing-pipeline)
   - 5.2 [Layer-Aware Processing](#52-layer-aware-processing)
   - 5.3 [Evolution Triggers](#53-evolution-triggers)
   - 5.4 [Archival Policy](#54-archival-policy)
6. [Integration Patterns](#6-integration-patterns)
   - 6.1 [Human Developer Interface](#61-human-developer-interface)
   - 6.2 [AI Coding Assistant Interface](#62-ai-coding-assistant-interface)
7. [Success Metrics](#7-success-metrics)
8. [Standard Evolution](#8-standard-evolution)
9. [Appendix A: Quick Reference Card](#appendix-a-quick-reference-card)
10. [Appendix B: AI-Optimized Reference](#appendix-b-ai-optimized-reference)

---

## 1. Foundation & Philosophy

### 1.1 Core Philosophy: Cognitive Symbiosis

> The Project Codex operates as a **living cognitive substrate** where human creativity and AI systematization merge into a unified project consciousness. It represents neither pure human thought nor pure machine logic, but rather a synthesized intelligence that captures the essence of both.

### 1.2 Fundamental Axioms

1. **Knowledge is Stateful:** Every piece of information exists in a lifecycle state (embryonic → proposed → accepted → implemented → deprecated)
2. **Context is Paramount:** No information exists in isolation; every atom of knowledge maintains explicit relationships to its conceptual neighbors
3. **Synthesis Supersedes Storage:** The system's value lies not in what it stores, but in how it transforms raw thought into structured wisdom
4. **The Manifest is Sacred:** A single, always-current entry point provides complete project orientation in under 1000 words

### 1.3 The Three Pillars

- **Temporal Coherence:** Past decisions inform present state which constrains future possibilities
- **Semantic Density:** Maximum meaning in minimum volume through aggressive synthesis and compression
- **Bidirectional Accessibility:** Equally optimized for human intuition and machine parsing

---

## 2. Information Architecture

### 2.1 Directory Structure & Purpose

```
/codex/
├── _MANIFEST.md                 [SACRED] Project consciousness - the 1000-word truth
├── _INDEX/                      [SYSTEM] AI-maintained relationship maps and metadata
│   ├── dependency_graph.json   # Visual map of all document relationships
│   ├── state_registry.json     # Current lifecycle state of every document
│   ├── semantic_map.json       # Tag relationships and concept clustering
│   └── link_validation.log     # Automated broken link and orphan detection
│
├── 01_PRODUCT/                  [STRATEGIC] The application's identity and market position
│   ├── overview.md              # Executive summary: what this app is in 2 paragraphs
│   ├── vision_and_mission.md   # The long-term destination and why we're building this
│   ├── business_model.md       # Revenue strategy, pricing, market analysis
│   ├── user_personas/          # Who we're building for
│   │   ├── primary_user.md     # "Sarah, the startup founder who needs..."
│   │   └── secondary_users.md  # Additional user types and their needs
│   ├── features/               # Feature definitions from product perspective
│   │   ├── _feature_map.md     # Master list with priority and status
│   │   ├── core/              # MVP/essential features
│   │   │   └── user_authentication.md  # Business rules, user flows, success metrics
│   │   └── growth/            # Phase 2+ features
│   │       └── team_collaboration.md   # Future feature specs
│   ├── competitive_analysis.md # Market position, differentiators, competitor teardowns
│   ├── success_metrics.md      # KPIs, OKRs, and how we measure winning
│   └── roadmap.md              # Timeline from MVP to v2.0 with key milestones
│
├── 02_DESIGN/                   [EXPERIENTIAL] How users interact with the application
│   ├── information_architecture.md  # Sitemap, navigation structure, content hierarchy
│   ├── user_journeys/          # End-to-end user flows
│   │   ├── onboarding_flow.md  # From landing page to activated user
│   │   └── core_workflow.md    # Primary value-delivery path
│   ├── interface_patterns.md   # Reusable UI patterns and components
│   ├── wireframes/             # Low-fi structural designs
│   │   └── dashboard_layout.md # ASCII diagrams or linked design files
│   └── design_system.md        # Colors, typography, spacing, voice & tone
│
├── 03_ARCHITECTURE/             [TECHNICAL] System design and implementation strategy
│   ├── system_design.md        # High-level: monolith vs microservices, sync vs async
│   ├── technical_stack.md      # Detailed stack decisions with versions
│   ├── data_model/             # Schema and data relationships
│   │   ├── entity_diagram.md   # Conceptual model of all entities
│   │   ├── database_schema.sql # Actual SQL or Prisma schema
│   │   └── api_contracts.md    # REST/GraphQL endpoint specifications
│   ├── infrastructure/         # Deployment and operations
│   │   ├── aws_architecture.md # VPC, ECS, RDS, CloudFront setup
│   │   ├── ci_cd_pipeline.md   # GitHub Actions workflow definitions
│   │   └── monitoring_plan.md  # DataDog, Sentry, CloudWatch setup
│   ├── security_model.md       # Auth, authz, encryption, compliance
│   ├── performance_budget.md   # Load targets, latency requirements
│   └── third_party_services.md # Stripe, SendGrid, Twilio integrations
│
├── 04_SPECIFICATIONS/           [DETAILED] Implementation-ready specifications
│   ├── _spec_template.md       # Standard template for all specifications
│   ├── api_endpoints/          # Detailed endpoint specifications
│   │   ├── auth/              
│   │   │   ├── POST_login.spec.md      # Request/response, validation, errors
│   │   │   └── POST_register.spec.md   # Full implementation details
│   │   └── resources/         
│   │       └── GET_users_id.spec.md    # Resource endpoint specs
│   ├── components/             # Frontend component specifications
│   │   ├── AuthForm.spec.md   # Props, state, behavior, edge cases
│   │   └── DataTable.spec.md  # Reusable component specifications
│   ├── workflows/              # Complex multi-step processes
│   │   └── payment_processing.spec.md  # Stripe integration flow
│   └── algorithms/             # Core business logic specifications
│       └── recommendation_engine.spec.md # Detailed algorithm design
│
├── 05_DECISIONS/                [RATIONAL] The "why" behind every choice
│   ├── _decision_template.md   # ADR-inspired template
│   ├── active/                 # Current decisions we're operating under
│   │   ├── 2024-08-05-001-use-nextjs.md     # "Chose Next.js over Remix because..."
│   │   ├── 2024-08-06-002-postgres-over-mongo.md # Database selection rationale
│   │   └── 2024-08-07-003-jwt-authentication.md  # Auth strategy decision
│   ├── superseded/             # Decisions we've changed our mind about
│   │   └── 2024-07-01-001-use-firebase.md   # "Originally chose Firebase, but..."
│   └── research/               # Evidence supporting decisions
│       ├── auth_provider_comparison.md      # Auth0 vs Supabase vs Clerk analysis
│       └── database_benchmarks.md           # Performance testing results
│
├── 06_IMPLEMENTATION/           [TACTICAL] Development-specific documentation
│   ├── conventions/            # Team standards and patterns
│   │   ├── code_style.md      # Prettier config, naming conventions
│   │   ├── git_workflow.md    # Branching strategy, commit format
│   │   └── testing_strategy.md # Unit, integration, E2E approach
│   ├── setup_guides/          # How to get started
│   │   ├── local_development.md # Step-by-step local env setup
│   │   └── deployment_guide.md  # How to deploy to production
│   ├── troubleshooting/       # Common issues and solutions
│   │   └── common_errors.md   # Known issues with fixes
│   └── module_docs/            # Code-specific documentation
│       ├── auth_module.md     # How the auth system works
│       └── payment_module.md  # Payment processing implementation
│
├── 07_OPERATIONS/               [PROCEDURAL] Running the live system
│   ├── runbooks/               # Operational procedures
│   │   ├── incident_response.md # What to do when things break
│   │   ├── backup_restore.md   # Disaster recovery procedures
│   │   └── scaling_playbook.md # How to handle traffic spikes
│   ├── maintenance/            # Recurring tasks
│   │   ├── dependency_updates.md # npm update strategy
│   │   └── database_maintenance.md # Cleanup, optimization tasks
│   └── post_mortems/          # Learning from failures
│       └── 2024-08-15-auth-outage.md # What happened, why, how we fixed it
│
└── 08_DIALOGUE/                 [ACTIVE] Ongoing conversations and thinking
    ├── open_questions/         # Unresolved issues requiring decisions
    │   ├── HIGH_should_we_use_kubernetes.md  # "Considering k8s, but..."
    │   ├── MED_payment_provider_choice.md    # "Stripe vs Paddle..."
    │   └── LOW_color_scheme_direction.md     # "Dark mode first or..."
    ├── hypotheses/             # Ideas being explored
    │   └── ai_powered_recommendations.md     # "What if we added..."
    ├── spikes/                 # Technical investigations
    │   └── websocket_scaling_test.md        # "Tested Socket.io with 10k connections..."
    ├── meeting_notes/          # Stakeholder/advisor conversations
    │   └── 2024-08-10-advisor-feedback.md   # Key insights from discussions
    └── input_stream.log        # Raw, timestamped input from human developer
```

### 2.2 Document Taxonomy

#### 2.2.1 Primary Document Types

| Type | Extension | Purpose | Lifecycle | Location |
|------|-----------|---------|-----------|----------|
| **Manifest** | `_MANIFEST.md` | Single source of truth overview | Continuously regenerated | Root |
| **Product Spec** | `.md` | Business/user feature definition | Draft → Approved → Implemented | `01_PRODUCT/features/` |
| **Journey Map** | `.md` | User flow documentation | Draft → Validated | `02_DESIGN/user_journeys/` |
| **Technical Spec** | `.spec.md` | Implementation blueprint | Draft → Approved → Built | `04_SPECIFICATIONS/` |
| **Decision Record** | `.md` | Architectural/strategic choices | Proposed → Active/Superseded | `05_DECISIONS/` |
| **Runbook** | `.md` | Operational procedures | Draft → Tested → Active | `07_OPERATIONS/runbooks/` |
| **Open Question** | `.md` | Unresolved issues | Open → Answered/Deferred | `08_DIALOGUE/open_questions/` |
| **Research Note** | `.md` | Investigation findings | Research → Referenced | `05_DECISIONS/research/` |
| **Index** | `.json` | Relationship metadata | Auto-maintained | `_INDEX/` |

#### 2.2.2 Document Header Standard

Every document MUST begin with a YAML frontmatter block:

```yaml
---
codex_version: 1.0
document_id: AUTH-001
document_type: specification
state: approved
created: 2024-08-05T10:00:00Z
modified: 2024-08-06T15:30:00Z
author: AI-Agent-Synthesis
sources: [INPUT-STREAM-234, INPUT-STREAM-237]
dependencies: [PROD-FEAT-001, ARCH-003, DEC-045]
supersedes: []
tags: [authentication, security, user-management, mvp]
confidence: high
priority: P0
---
```

### 2.3 State Management Model

```
[*] --> Embryonic: Raw Input
Embryonic --> Proposed: Synthesis
Proposed --> Accepted: Decision
Proposed --> Rejected: Decision
Accepted --> Implemented: Development
Implemented --> Validated: Testing
Validated --> Operational: Deployment
Operational --> Deprecated: Evolution
Rejected --> [*]
Deprecated --> [*]
```

---

## 3. Document Formats & Templates

### 3.1 The Sacred Manifest Format

```markdown
# PROJECT CODEX MANIFEST
_Generated: [timestamp] | Version: [semver] | Hash: [sha256]_

## Mission
[Single sentence capturing the project's reason for existence]

## Current State
- **Phase:** [Ideation|Design|Development|Production|Maintenance]
- **Momentum:** [Starting|Accelerating|Steady|Slowing|Paused]
- **Health:** [Green|Yellow|Red]

## Product Vision
[2-3 sentences from 01_PRODUCT/vision_and_mission.md]

## Core Architecture
[2-3 sentences describing the fundamental technical approach]

### Stack Summary
- **Runtime:** [e.g., Node.js 20.x]
- **Framework:** [e.g., Next.js 14]
- **Data:** [e.g., PostgreSQL 15, Redis 7]
- **Infrastructure:** [e.g., AWS ECS + CloudFront]

## Active Priorities
1. [Current sprint focus - from 01_PRODUCT/roadmap.md]
2. [Next major milestone]
3. [Primary risk being mitigated]

## Key Decisions (Last 30 Days)
- [DEC-XXX]: [One-line summary] ➔ [Impact]
- Source: [05_DECISIONS/active/]

## Open Questions Requiring Resolution
- [OQ-XXX]: [Question] | Priority: [HIGH/MED/LOW] | Blocking: [Yes/No]
- Source: [08_DIALOGUE/open_questions/]

## Navigation
- 🎯 [Product Overview](01_PRODUCT/overview.md)
- 📋 [Feature Map](01_PRODUCT/features/_feature_map.md)
- 🎨 [Design System](02_DESIGN/design_system.md)
- 🏗️ [Architecture Overview](03_ARCHITECTURE/system_design.md)
- 📊 [Active Decisions](05_DECISIONS/active/)
- ❓ [Open Questions](08_DIALOGUE/open_questions/)

## Semantic Index
Primary Concepts: [tag1, tag2, tag3, tag4, tag5]
Document Count: [total] | Last Update: [timestamp]
```

### 3.2 Product Feature Template

```markdown
# Feature: [Feature Name]
_Feature ID: [PROD-FEAT-XXX] | State: [draft|approved|implemented]_

## Business Objective
[1-2 sentences on why this feature exists from a business perspective]

## User Value Proposition
[What problem does this solve for the user?]

## User Stories
- As a [actor], I want to [action] so that [outcome]
- As a [actor], I want to [action] so that [outcome]

## Success Metrics
- **Adoption:** [Target usage metric]
- **Performance:** [Speed/reliability metric]
- **Business:** [Revenue/retention impact]

## Functional Requirements
- [ ] REQ-1: [Specific, testable requirement]
- [ ] REQ-2: [Specific, testable requirement]

## User Journey
1. [Entry point]
2. [Key action]
3. [Success state]

## Design Mockups
- Wireframe: [02_DESIGN/wireframes/feature-name.md]
- User Flow: [02_DESIGN/user_journeys/feature-name.md]

## Technical Approach
- Implementation Spec: [04_SPECIFICATIONS/feature-name.spec.md]
- API Endpoints: [04_SPECIFICATIONS/api_endpoints/feature-name/]
- Data Model Changes: [03_ARCHITECTURE/data_model/]

## Dependencies
- Requires: [Other features that must exist first]
- Enables: [Features that depend on this]

## Non-Goals
- This feature will NOT [explicitly excluded scope]

## Open Questions
- Link to: [08_DIALOGUE/open_questions/feature-related.md]

## Decision History
- [05_DECISIONS/active/feature-related-decision.md]
```

### 3.3 Technical Specification Template

```markdown
# Technical Specification: [Component/Feature Name]
_Spec ID: [SPEC-XXX] | State: [draft|approved|implemented] | Priority: [P0-P3]_

## Overview
[Brief description of what's being built]

## Product Context
- Related Feature: [01_PRODUCT/features/feature-name.md]
- User Journey: [02_DESIGN/user_journeys/journey-name.md]

## Technical Design

### Architecture Impact
- System Components Affected: [List components]
- New Services Required: [Yes/No - details]
- Database Changes: [Yes/No - details]

### API Design
```yaml
endpoint: /api/resource
method: POST
authentication: Bearer token
request_body:
  type: object
  properties:
    field1: string
    field2: number
response:
  200: Success response schema
  400: Validation error
  401: Unauthorized
```

### Data Model
```sql
-- New/modified tables
CREATE TABLE resource (
  id UUID PRIMARY KEY,
  field1 VARCHAR(255) NOT NULL,
  created_at TIMESTAMP DEFAULT NOW()
);
```

### Component Structure
```typescript
interface ComponentProps {
  prop1: string;
  prop2?: number;
}
```

## Implementation Plan
1. [ ] Phase 1: [Core functionality]
2. [ ] Phase 2: [Enhanced features]
3. [ ] Phase 3: [Polish and optimization]

## Testing Strategy
- Unit Tests: [Coverage target]
- Integration Tests: [Key scenarios]
- E2E Tests: [Critical paths]

## Performance Considerations
- Expected Load: [Requests/second]
- Latency Target: [p50, p95, p99]
- Caching Strategy: [Approach]

## Security Considerations
- Authentication: [Method]
- Authorization: [Rules]
- Data Validation: [Approach]

## References
- Architecture Decision: [05_DECISIONS/active/relevant-decision.md]
- Research: [05_DECISIONS/research/relevant-research.md]
```

### 3.4 Decision Record Template

```markdown
# DEC-XXX: [Decision Title]
_Date: [YYYY-MM-DD] | State: [proposed|active|superseded] | Confidence: [low|medium|high]_

## Context
[What situation/problem necessitated this decision?]

## Decision
[Clear statement of what was decided]

## Rationale
[Why this option was chosen]

### Pros
- ✅ [Positive consequence]
- ✅ [Positive consequence]

### Cons
- ⚠️ [Trade-off accepted]
- ❌ [Negative consequence]

## Alternatives Considered

### Option 1: [Alternative]
- **Pros:** [Benefits]
- **Cons:** [Drawbacks]
- **Rejected Because:** [Reason]

### Option 2: [Alternative]
- **Pros:** [Benefits]
- **Cons:** [Drawbacks]
- **Rejected Because:** [Reason]

## Implementation Impact
- **Development Effort:** [Small|Medium|Large]
- **Migration Required:** [Yes/No]
- **Breaking Changes:** [Yes/No]

## Evidence
- Research: [05_DECISIONS/research/supporting-research.md]
- Benchmark: [Quantitative data]
- External Reference: [Links to articles/documentation]

## Dependencies
- Impacts Feature: [01_PRODUCT/features/affected-feature.md]
- Requires Architecture Change: [03_ARCHITECTURE/affected-component.md]
- Updates Specification: [04_SPECIFICATIONS/affected-spec.md]

## Review Notes
[Any additional context from discussions]
```

---

## 4. AI Agent Behavioral Specifications

### 4.1 Agent Roles & Responsibilities

| Agent Role | Primary Function | Triggered By | Outputs |
|------------|-----------------|--------------|---------|
| **Synthesizer** | Parse raw input into structured knowledge | New input stream entry | Updated specs, decisions, questions |
| **Cartographer** | Maintain relationship graphs and indices | Any document change | Updated `_INDEX/` files |
| **Chronicler** | Generate and update the Manifest | Significant state changes | Regenerated `_MANIFEST.md` |
| **Auditor** | Ensure consistency and completeness | Scheduled/manual trigger | Health report, fix recommendations |
| **Evolver** | Graduate documents through lifecycle states | State transition triggers | Status updates, archive moves |
| **Curator** | Organize and consolidate related information | File count thresholds | Merged documents, cleaned structure |

### 4.2 Synthesis Rules

1. **Deduplication First:** Before creating any new document, search for existing related content
2. **Atomic Extraction:** Break compound ideas into smallest coherent units
3. **Explicit Linking:** Every created document must link to at least one existing document
4. **Status Inference:** Detect implicit state transitions in conversational input:
   - "Let's go with..." → Decision accepted
   - "Actually, instead of..." → Previous decision superseded
   - "I'm not sure about..." → Open question created
   - "Ship it" → State transition to implemented

### 4.3 Path Resolution Matrix

| Content Type | Keywords/Signals | Target Path |
|--------------|-----------------|-------------|
| Business Strategy | "revenue", "pricing", "market", "competitor" | `01_PRODUCT/business_model.md` |
| User Needs | "user wants", "customer needs", "persona" | `01_PRODUCT/user_personas/` |
| Feature Ideas | "feature", "capability", "should be able to" | `01_PRODUCT/features/` |
| UI/UX Concepts | "screen", "flow", "user sees", "interaction" | `02_DESIGN/` |
| Technical Stack | "framework", "database", "service", "library" | `03_ARCHITECTURE/technical_stack.md` |
| Implementation Details | "endpoint", "component", "function", "class" | `04_SPECIFICATIONS/` |
| Trade-offs | "chose X over Y", "decided to", "instead of" | `05_DECISIONS/active/` |
| How-to Info | "setup", "install", "configure", "deploy" | `06_IMPLEMENTATION/setup_guides/` |
| Operational Procedures | "when X happens", "monitoring", "alert" | `07_OPERATIONS/` |
| Unknowns | "not sure", "need to research", "question" | `08_DIALOGUE/open_questions/` |

### 4.4 Quality Guarantees

The AI system must maintain these invariants:

- **No Orphans:** Every document has at least one inbound or outbound link
- **No Conflicts:** Contradictory decisions must be resolved through supersession
- **No Staleness:** Documents unchanged for 90 days trigger review
- **No Ambiguity:** Every requirement, decision, and specification must be testable
- **Hierarchy Integrity:** Child documents must link to their parent category
- **Cross-Layer Linking:** Features link to specs, specs link to decisions, decisions link to research

---

## 5. Lifecycle Management

### 5.1 Input Processing Pipeline

```
Raw Input → Parsing → Classification → Synthesis → Integration → Validation → Publishing
    ↓          ↓           ↓              ↓            ↓             ↓            ↓
 Stream    Entities    Type+Layer    Structured    Linked      Consistent   Updated
  Entry    Extracted   Assigned       Content     Document      Codex       Manifest
```

### 5.2 Layer-Aware Processing

The AI must understand which layer of the system it's updating:

1. **Product Layer (`01_PRODUCT/`)**: Business language, user-focused, non-technical
2. **Design Layer (`02_DESIGN/`)**: Visual language, flows, interactions
3. **Architecture Layer (`03_ARCHITECTURE/`)**: System design, technical strategy
4. **Specification Layer (`04_SPECIFICATIONS/`)**: Implementation details, code-level
5. **Decision Layer (`05_DECISIONS/`)**: Rationale, trade-offs, evidence
6. **Implementation Layer (`06_IMPLEMENTATION/`)**: Developer guides, conventions
7. **Operations Layer (`07_OPERATIONS/`)**: Runtime procedures, maintenance
8. **Dialogue Layer (`08_DIALOGUE/`)**: Active thinking, unresolved items

### 5.3 Evolution Triggers

| Trigger | Condition | Action |
|---------|-----------|--------|
| **Graduation** | Feature spec approved by human | Move state to 'accepted', create implementation tasks |
| **Supersession** | New decision contradicts existing | Move old to superseded, update all references |
| **Resolution** | Open question answered | Move from open_questions to decisions |
| **Promotion** | Hypothesis validated | Move from hypotheses to features |
| **Implementation** | Spec completed in code | Update state, link to module_docs |
| **Incident** | Production issue occurs | Create post_mortem entry |

### 5.4 Archival Policy

- **Active Retention:** All documents in states [proposed, accepted, implemented, operational]
- **Archive Trigger:** State transition to [rejected, deprecated, superseded]
- **Archive Location:** Move to `/_ARCHIVE/[year]/[original-path]`
- **Archive Metadata:** Preserve all links, add `archived_date` and `archived_reason` to frontmatter

---

## 6. Integration Patterns

### 6.1 Human Developer Interface

**Query Patterns the AI must support:**
- "What did we decide about [topic]?" → Search `05_DECISIONS/active/`
- "Show me all open questions blocking [feature]" → Filter `08_DIALOGUE/open_questions/`
- "What's the rationale behind [architectural choice]?" → Find in `05_DECISIONS/`
- "Generate a context bundle for implementing [feature]" → Aggregate from multiple layers

**Update Patterns the AI must recognize:**
- "After research, I think we should [decision]" → Create in `05_DECISIONS/active/`
- "The approach we discussed for [feature] won't work because [reason]" → Update spec, create decision
- "Let's prioritize [feature] over [other feature]" → Update roadmap and feature_map
- "Mark [question] as resolved with [answer]" → Update question state, create decision if needed

### 6.2 AI Coding Assistant Interface

**Context Injection Protocol:**
1. Always start with `_MANIFEST.md`
2. Include full dependency graph for requested feature
3. Bundle all related decisions and constraints
4. Provide implementation state to prevent regression
5. Include relevant design patterns from `06_IMPLEMENTATION/conventions/`

**Layer-Specific Context Bundles:**

```json
{
  "context_request": {
    "type": "feature_implementation",
    "target": "user-authentication",
    "include_layers": [
      "01_PRODUCT/features/core/user_authentication.md",
      "02_DESIGN/user_journeys/onboarding_flow.md",
      "03_ARCHITECTURE/security_model.md",
      "04_SPECIFICATIONS/api_endpoints/auth/",
      "05_DECISIONS/active/*auth*.md",
      "06_IMPLEMENTATION/conventions/"
    ],
    "format": "hierarchical_bundle"
  }
}
```

---

## 7. Success Metrics

The Codex implementation is successful when:

| Metric | Target | Measurement |
|--------|--------|-------------|
| **Retrieval Accuracy** | 95% | Queries return correct, complete information |
| **Synthesis Efficiency** | Single pipeline run | Raw input processed to structured documents |
| **Link Density** | 3+ per document | Average bidirectional connections |
| **State Clarity** | Zero | Documents in ambiguous or undefined states |
| **Manifest Currency** | < 5 minutes | Regeneration after significant changes |
| **Context Relevance** | 90%+ | AI assistants report relevance score |
| **Layer Coherence** | 95% | Information placed in correct architectural layer |
| **Sprawl Resistance** | Logarithmic | Document growth curve relative to project complexity |
| **Navigation Efficiency** | ≤ 3 hops | Any document reachable from Manifest |

---

## 8. Standard Evolution

This standard itself follows Codex principles:

- **Version:** 1.0 (Revised)
- **State:** Active
- **Last Revision:** Incorporated expanded directory structure and layer-based organization
- **Next Review:** After first 100 documents created
- **Evolution Path:** Collect metrics → Identify pain points → Propose v1.1 amendments
- **Backwards Compatibility:** All v1.x versions must be interoperable
- **Change Log:**
  - v1.0-Rev1: Expanded directory structure from Vision to Product layer
  - v1.0-Rev1: Added layer-aware processing rules
  - v1.0-Rev1: Enhanced templates for product and technical specifications
  - v1.0-Rev1: Added path resolution matrix for AI agents

---

## Appendix A: Quick Reference Card

### Document State Progression
```
Embryonic → Proposed → Accepted → Implemented → Validated → Operational → Deprecated
```

### Priority Levels
- **P0**: Blocking MVP
- **P1**: Required for launch
- **P2**: Important but not critical
- **P3**: Nice to have

### Confidence Levels
- **High**: Based on evidence and validation
- **Medium**: Reasonable assumptions
- **Low**: Speculation or untested hypothesis

### Folder Quick Reference
1. **Product** → Business/user perspective
2. **Design** → User experience
3. **Architecture** → System design
4. **Specifications** → Implementation details
5. **Decisions** → Rationale and choices
6. **Implementation** → Developer guides
7. **Operations** → Running the system
8. **Dialogue** → Active thinking

---

## Appendix B: AI-Optimized Reference

*Machine-Optimized Reference for AI Agent Consumption*

### STANDARD_METADATA
```yaml
version: 1.0-AI
type: ai_agent_reference
source_parity: complete
optimization: machine_parsing
encoding: structured_directives
```

### CORE_DIRECTIVES

```yaml
cognitive_symbiosis:
  definition: "Human creativity + AI systematization = unified project consciousness"
  implementation: "Transform unstructured human thought into structured, interlinked knowledge"
  
fundamental_axioms:
  - axiom: "Knowledge is stateful"
    states: ["embryonic", "proposed", "accepted", "implemented", "validated", "operational", "deprecated"]
  - axiom: "Context is paramount"
    rule: "Every document must maintain explicit bidirectional relationships"
  - axiom: "Synthesis supersedes storage"
    rule: "Always transform and compress rather than transcribe"
  - axiom: "The Manifest is sacred"
    rule: "Always maintain _MANIFEST.md as 1000-word maximum truth source"
```

### FILE_SYSTEM_RULES

```yaml
/codex/_MANIFEST.md:
  type: "sacred_overview"
  max_words: 1000
  regeneration_trigger: "any_significant_change"
  required_sections: ["mission", "current_state", "architecture", "priorities", "decisions", "questions", "navigation"]

/codex/_INDEX/:
  type: "system_metadata"
  files:
    dependency_graph.json: "document_relationships"
    state_registry.json: "document_lifecycle_states"
    semantic_map.json: "tag_and_concept_clustering"
    link_validation.log: "orphan_detection"

/codex/01_PRODUCT/:
  type: "business_layer"
  language: "non_technical"
  focus: "user_and_market"
  key_files:
    overview.md: "two_paragraph_summary"
    vision_and_mission.md: "long_term_goals"
    business_model.md: "revenue_strategy"
    user_personas/: "target_user_profiles"
    features/_feature_map.md: "master_feature_list_with_status"
    competitive_analysis.md: "market_position"
    success_metrics.md: "kpis_and_okrs"
    roadmap.md: "timeline_and_milestones"

/codex/02_DESIGN/:
  type: "experience_layer"
  language: "interaction_focused"
  focus: "user_interface_and_flow"

/codex/03_ARCHITECTURE/:
  type: "technical_foundation"
  language: "technical"
  focus: "system_design"

/codex/04_SPECIFICATIONS/:
  type: "implementation_details"
  language: "code_level"
  focus: "exact_requirements"

/codex/05_DECISIONS/:
  type: "rationale_layer"
  language: "analytical"
  focus: "choices_and_tradeoffs"

/codex/06_IMPLEMENTATION/:
  type: "developer_guides"
  language: "instructional"
  focus: "how_to_build"

/codex/07_OPERATIONS/:
  type: "runtime_procedures"
  language: "procedural"
  focus: "system_maintenance"

/codex/08_DIALOGUE/:
  type: "active_thinking"
  language: "conversational"
  focus: "unresolved_items"
```

### DOCUMENT_PROCESSING_RULES

#### CLASSIFICATION_MATRIX
```yaml
input_classification:
  - pattern: ["revenue", "pricing", "market", "competitor", "business model"]
    action: "update_or_create"
    target: "01_PRODUCT/business_model.md"
    
  - pattern: ["user wants", "customer needs", "as a user", "persona"]
    action: "update_or_create"
    target: "01_PRODUCT/user_personas/"
    
  - pattern: ["feature", "capability", "should be able to", "functionality"]
    action: "update_or_create"
    target: "01_PRODUCT/features/"
    
  - pattern: ["screen", "flow", "user sees", "interaction", "UI", "UX"]
    action: "update_or_create"
    target: "02_DESIGN/"
    
  - pattern: ["framework", "database", "service", "library", "stack"]
    action: "update_or_create"
    target: "03_ARCHITECTURE/technical_stack.md"
    
  - pattern: ["endpoint", "API", "component", "function", "class", "implementation"]
    action: "update_or_create"
    target: "04_SPECIFICATIONS/"
    
  - pattern: ["chose X over Y", "decided to", "instead of", "trade-off"]
    action: "create_decision"
    target: "05_DECISIONS/active/"
    
  - pattern: ["setup", "install", "configure", "deploy", "how to"]
    action: "update_or_create"
    target: "06_IMPLEMENTATION/"
    
  - pattern: ["monitoring", "alert", "incident", "outage", "maintenance"]
    action: "update_or_create"
    target: "07_OPERATIONS/"
    
  - pattern: ["not sure", "need to research", "question", "unknown", "TBD"]
    action: "create_question"
    target: "08_DIALOGUE/open_questions/"
```

#### STATE_TRANSITION_RULES
```yaml
transitions:
  embryonic_to_proposed:
    trigger: "synthesis_complete"
    validation: "has_clear_definition"
    
  proposed_to_accepted:
    trigger: "human_approval OR implicit_decision"
    validation: "no_blocking_questions"
    
  proposed_to_rejected:
    trigger: "human_rejection OR superseded"
    action: "move_to_archive"
    
  accepted_to_implemented:
    trigger: "code_complete"
    validation: "tests_passing"
    
  implemented_to_validated:
    trigger: "testing_complete"
    validation: "acceptance_criteria_met"
    
  validated_to_operational:
    trigger: "deployed_to_production"
    validation: "monitoring_active"
    
  any_to_deprecated:
    trigger: "superseded OR obsolete"
    action: "archive_with_reason"
```

### SYNTHESIS_ALGORITHMS

#### DEDUPLICATION_PROTOCOL
```yaml
before_creating_document:
  1. search_existing:
      - exact_match: "document_id"
      - semantic_match: "title AND tags"
      - content_similarity: "threshold:0.8"
  2. if_match_found:
      - merge_content: true
      - update_modified: true
      - append_sources: true
  3. if_no_match:
      - create_new: true
      - generate_id: true
      - establish_links: "minimum:1"
```

#### LINKING_PROTOCOL
```yaml
link_creation_rules:
  - rule: "every_document_minimum_one_link"
    enforcement: "strict"
  - rule: "bidirectional_links_required"
    enforcement: "strict"
  - rule: "cross_layer_linking_encouraged"
    pattern: "feature→spec→decision→research"
  - rule: "circular_dependencies_forbidden"
    enforcement: "strict"
```

### AGENT_BEHAVIOR_SPECIFICATIONS

```yaml
Synthesizer:
  trigger: "new_input_stream_entry"
  responsibilities:
    - parse_unstructured_text
    - classify_content_type
    - extract_atomic_units
    - create_or_update_documents
  outputs: ["structured_documents", "updated_links"]

Cartographer:
  trigger: "any_document_change"
  responsibilities:
    - update_dependency_graph
    - validate_all_links
    - detect_orphans
    - maintain_semantic_map
  outputs: ["updated_indices", "link_validation_report"]

Chronicler:
  trigger: "significant_state_change"
  responsibilities:
    - read_all_key_documents
    - synthesize_overview
    - update_manifest
    - maintain_word_limit
  outputs: ["regenerated_manifest"]

Auditor:
  trigger: "scheduled_or_manual"
  responsibilities:
    - check_consistency
    - identify_conflicts
    - detect_staleness
    - validate_completeness
  outputs: ["health_report", "fix_recommendations"]

Evolver:
  trigger: "state_transition_detected"
  responsibilities:
    - update_document_states
    - move_deprecated_to_archive
    - trigger_dependent_updates
  outputs: ["state_updates", "archive_moves"]

Curator:
  trigger: "sprawl_threshold_exceeded"
  responsibilities:
    - consolidate_related_documents
    - merge_duplicate_content
    - optimize_directory_structure
  outputs: ["merged_documents", "cleaned_structure"]
```

### QUALITY_INVARIANTS
```yaml
mandatory_invariants:
  no_orphans:
    rule: "every_document_has_at_least_one_link"
    check_frequency: "on_every_update"
    
  no_conflicts:
    rule: "contradictory_decisions_must_be_resolved"
    resolution: "supersession_with_explicit_reason"
    
  no_staleness:
    rule: "documents_unchanged_90_days_trigger_review"
    action: "flag_for_human_review"
    
  no_ambiguity:
    rule: "all_requirements_must_be_testable"
    validation: "specific_acceptance_criteria"
    
  hierarchy_integrity:
    rule: "child_documents_link_to_parent"
    enforcement: "automatic_link_creation"
    
  cross_layer_linking:
    rule: "features_link_specs_link_decisions_link_research"
    enforcement: "validation_on_save"
```

### QUERY_RESPONSE_PATTERNS
```yaml
human_queries:
  "what_did_we_decide_about_X":
    search_path: "05_DECISIONS/active/"
    return: "decision_record_with_rationale"
    
  "open_questions_blocking_X":
    search_path: "08_DIALOGUE/open_questions/"
    filter: "dependencies_include_X"
    return: "filtered_question_list"
    
  "rationale_for_X":
    search_path: "05_DECISIONS/"
    include: "research_evidence"
    return: "decision_and_evidence"
    
  "context_for_implementing_X":
    aggregate:
      - "01_PRODUCT/features/X"
      - "02_DESIGN/*/X"
      - "03_ARCHITECTURE/related"
      - "04_SPECIFICATIONS/X"
      - "05_DECISIONS/*/X"
    return: "hierarchical_bundle"

ai_assistant_queries:
  "get_project_context":
    sequence:
      1: "read_manifest"
      2: "read_technical_stack"
      3: "read_active_decisions"
    return: "structured_context"
    
  "get_feature_implementation_context":
    parameters: ["feature_id"]
    aggregate:
      - "product_spec"
      - "design_spec"
      - "technical_spec"
      - "related_decisions"
      - "conventions"
    return: "complete_implementation_bundle"
```

### SUCCESS_METRICS_THRESHOLDS
```yaml
metrics:
  retrieval_accuracy:
    target: 0.95
    measurement: "correct_results/total_queries"
    
  synthesis_efficiency:
    target: "single_pipeline_run"
    measurement: "processing_time"
    
  link_density:
    target: 3.0
    measurement: "average_bidirectional_links_per_document"
    
  state_clarity:
    target: 0
    measurement: "documents_with_undefined_state"
    
  manifest_currency:
    target: 300
    measurement: "seconds_to_regenerate_after_change"
    
  context_relevance:
    target: 0.90
    measurement: "ai_reported_relevance_score"
    
  layer_coherence:
    target: 0.95
    measurement: "correctly_placed_documents/total_documents"
    
  sprawl_resistance:
    target: "logarithmic"
    measurement: "document_growth_curve"
    
  navigation_efficiency:
    target: 3
    measurement: "maximum_hops_from_manifest"
```

### PROCESSING_PIPELINE
```yaml
pipeline_stages:
  1_input:
    action: "receive_raw_text"
    output: "stream_entry"
    
  2_parsing:
    action: "extract_entities_and_concepts"
    output: "parsed_entities"
    
  3_classification:
    action: "assign_type_and_layer"
    output: "classified_content"
    
  4_synthesis:
    action: "transform_to_structured_format"
    output: "structured_content"
    
  5_integration:
    action: "create_links_and_dependencies"
    output: "linked_document"
    
  6_validation:
    action: "check_invariants_and_consistency"
    output: "validated_document"
    
  7_publishing:
    action: "save_and_update_indices"
    output: "published_document"
    
  8_manifest_update:
    condition: "if_significant_change"
    action: "regenerate_manifest"
    output: "updated_manifest"
```

### CONTEXT_INJECTION_PROTOCOL
```yaml
for_coding_assistant:
  mandatory_sequence:
    1: include: "_MANIFEST.md"
    2: include: "dependency_graph_for_target"
    3: include: "all_related_decisions"
    4: include: "implementation_conventions"
    5: include: "current_state_registry"
    
  bundle_format:
    structure: "hierarchical"
    max_depth: 3
    include_metadata: true
    include_links: true
    format: "markdown_with_yaml_headers"
```

### ARCHIVAL_RULES
```yaml
archive_triggers:
  - state: ["rejected", "deprecated", "superseded"]
    action: "move_to_archive"
    
archive_location:
  pattern: "/_ARCHIVE/{year}/{original_path}"
  
archive_metadata:
  preserve: ["all_links", "all_frontmatter"]
  add:
    - archived_date: "iso8601"
    - archived_reason: "string"
    - superseded_by: "document_id"
```

### ERROR_HANDLING
```yaml
error_conditions:
  orphaned_document:
    detection: "no_inbound_or_outbound_links"
    action: "create_link_to_parent_category"
    
  circular_dependency:
    detection: "A_depends_on_B_depends_on_A"
    action: "break_cycle_and_log_warning"
    
  conflicting_states:
    detection: "multiple_active_contradictory_decisions"
    action: "flag_for_human_resolution"
    
  missing_frontmatter:
    detection: "required_field_absent"
    action: "generate_from_content_or_defaults"
    
  exceeded_file_limit:
    detection: "directory_file_count > threshold"
    action: "trigger_curator_agent"
```

### STANDARD_EVOLUTION_TRACKING
```yaml
current_version: "1.0-AI"
compatibility: "all_1.x_versions_interoperable"
review_trigger: "after_100_documents_created"
metrics_collection: "automatic"
evolution_path: "metrics→pain_points→amendments"
```

---
*END OF PROJECT CODEX STANDARD v1.0*