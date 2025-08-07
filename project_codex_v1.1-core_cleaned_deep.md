# PROJECT CODEX STANDARD

## Documentation Standard v1.1 - PRISM Architecture Edition

### A Comprehensive Standard for AI-Managed Solo Development Documentation with Manual Pipeline Orchestration

---

**Generated:** December 2024
**Version:** 1.1 (PRISM)
**Status:** Active
**Implementation:** PRISM Architecture - Progressive Refinement through Isolated Specialized Modules

---

## Table of Contents

1. [Foundation & Philosophy](#1-foundation--philosophy)
   - 1.1 [Core Philosophy: Cognitive Symbiosis](#11-core-philosophy-cognitive-symbiosis)
   - 1.2 [Fundamental Axioms](#12-fundamental-axioms)
   - 1.3 [The Four Pillars](#13-the-four-pillars)
2. [Information Architecture](#2-information-architecture)
   - 2.1 [Directory Structure & Purpose](#21-directory-structure--purpose)
   - 2.2 [Document Taxonomy](#22-document-taxonomy)
   - 2.3 [State Management Model](#23-state-management-model)
3. [Document Formats & Templates](#3-document-formats--templates)
   - 3.1 [The Sacred Manifest Format](#31-the-sacred-manifest-format)
   - 3.2 [Product Feature Template](#32-product-feature-template)
   - 3.3 [Technical Specification Template](#33-technical-specification-template)
   - 3.4 [Decision Record Template](#34-decision-record-template)
4. [PRISM Pipeline Architecture](#4-prism-pipeline-architecture)
   - 4.1 [Pipeline Overview](#41-pipeline-overview)
   - 4.2 [Sub-Agent Specifications](#42-sub-agent-specifications)
   - 4.3 [Context Window Management](#43-context-window-management)
   - 4.4 [Quality Guarantees](#44-quality-guarantees)
5. [Lifecycle Management](#5-lifecycle-management)
   - 5.1 [PRISM Processing Pipeline](#51-prism-processing-pipeline)
   - 5.2 [Stage-Specific Processing](#52-stage-specific-processing)
   - 5.3 [Pipeline-Initiated Triggers](#53-pipeline-initiated-triggers)
   - 5.4 [Archival Policy](#54-archival-policy)
6. [Integration Patterns](#6-integration-patterns)
   - 6.1 [Human Developer Interface](#61-human-developer-interface)
   - 6.2 [AI Coding Assistant Interface](#62-ai-coding-assistant-interface)
7. [Success Metrics](#7-success-metrics)
8. [Standard Evolution](#8-standard-evolution)
9. [Pipeline Operation Manual](#9-pipeline-operation-manual)
10. [Sub-Agent Behavioral Specifications](#10-sub-agent-behavioral-specifications)
11. [Appendix A: Quick Reference Card](#appendix-a-quick-reference-card)
12. [Appendix B: AI-Optimized Reference](#appendix-b-ai-optimized-reference)

---

## 1. Foundation & Philosophy

### 1.1 Core Philosophy: Cognitive Symbiosis

> The Project Codex operates as a **living cognitive substrate** where human creativity and AI systematization merge into a unified project consciousness. It represents neither pure human thought nor pure machine logic, but rather a synthesized intelligence that captures the essence of both, orchestrated through deliberate human-initiated pipeline operations.

### 1.2 Fundamental Axioms

1. **Knowledge is Stateful:** Every piece of information exists in a lifecycle state (embryonic -> proposed -> accepted -> implemented -> deprecated)
2. **Context is Paramount:** No information exists in isolation; every atom of knowledge maintains explicit relationships to its conceptual neighbors
3. **Synthesis Supersedes Storage:** The system's value lies not in what it stores, but in how it transforms raw thought into structured wisdom
4. **The Manifest is Sacred:** A single, always-current entry point provides complete project orientation in under 1000 words
5. **Human Sovereignty:** The system operates exclusively under human initiation and verification, with no autonomous operations

### 1.3 The Four Pillars

- **Temporal Coherence:** Past decisions inform present state which constrains future possibilities
- **Semantic Density:** Maximum meaning in minimum volume through aggressive synthesis and compression
- **Bidirectional Accessibility:** Equally optimized for human intuition and machine parsing
- **Manual Orchestration:** Human judgment gates between all transformative operations through pipeline stages

---

## 2. Information Architecture

### 2.1 Directory Structure & Purpose

```text
/codex/
|-- _MANIFEST.md                           [SACRED] Project consciousness - the 1000-word truth
|-- _INDEX/                                [SYSTEM] AI-maintained relationship maps and metadata
|   |-- dependency_graph.json             # Visual map of all document relationships
|   |-- state_registry.json               # Current lifecycle state of every document
|   |-- semantic_map.json                 # Tag relationships and concept clustering
|   `-- link_validation.log               # Automated broken link and orphan detection
|
|-- _pipeline/                             [TEMPORARY] Pipeline processing artifacts
|   |-- extracted_units.json              # Stage 1 output: atomic knowledge units
|   |-- classified_units.json             # Stage 2 output: categorized units
|   |-- synthesized_documents/            # Stage 3A output: generated documents
|   |-- relationship_map.json             # Stage 3B output: document connections
|   |-- validation_report.json            # Stage 5 output: quality check results
|   `-- state.yaml                        # Pipeline state between manual invocations
|
|-- 01_PRODUCT/                            [STRATEGIC] The application's identity and market position
|   |-- overview.md                       # Executive summary: what this app is in 2 paragraphs
|   |-- vision_and_mission.md             # The long-term destination and why we're building this
|   |-- business_model.md                 # Revenue strategy, pricing, market analysis
|   |-- user_personas/                    # Who we're building for
|   |   |-- primary_user.md               # "Sarah, the startup founder who needs..."
|   |   `-- secondary_users.md            # Additional user types and their needs
|   |-- features/                         # Feature definitions from product perspective
|   |   |-- _feature_map.md               # Master list with priority and status
|   |   |-- core/                         # MVP/essential features
|   |   |   `-- user_authentication.md    # Business rules, user flows, success metrics
|   |   `-- growth/                       # Phase 2+ features
|   |       `-- team_collaboration.md     # Future feature specs
|   |-- competitive_analysis.md           # Market position, differentiators, competitor teardowns
|   |-- success_metrics.md                # KPIs, OKRs, and how we measure winning
|   `-- roadmap.md                        # Timeline from MVP to v2.0 with key milestones
|
|-- 02_DESIGN/                             [EXPERIENTIAL] How users interact with the application
|   |-- information_architecture.md       # Sitemap, navigation structure, content hierarchy
|   |-- user_journeys/                    # End-to-end user flows
|   |   |-- onboarding_flow.md            # From landing page to activated user
|   |   `-- core_workflow.md              # Primary value-delivery path
|   |-- interface_patterns.md             # Reusable UI patterns and components
|   |-- wireframes/                       # Low-fi structural designs
|   |   `-- dashboard_layout.md           # ASCII diagrams or linked design files
|   `-- design_system.md                  # Colors, typography, spacing, voice & tone
|
|-- 03_ARCHITECTURE/                       [TECHNICAL] System design and implementation strategy
|   |-- system_design.md                  # High-level: monolith vs microservices, sync vs async
|   |-- technical_stack.md                # Detailed stack decisions with versions
|   |-- data_model/                       # Schema and data relationships
|   |   |-- entity_diagram.md             # Conceptual model of all entities
|   |   |-- database_schema.sql           # Actual SQL or Prisma schema
|   |   `-- api_contracts.md              # REST/GraphQL endpoint specifications
|   |-- infrastructure/                   # Deployment and operations
|   |   |-- aws_architecture.md           # VPC, ECS, RDS, CloudFront setup
|   |   |-- ci_cd_pipeline.md             # GitHub Actions workflow definitions
|   |   `-- monitoring_plan.md            # DataDog, Sentry, CloudWatch setup
|   |-- security_model.md                 # Auth, authz, encryption, compliance
|   |-- performance_budget.md             # Load targets, latency requirements
|   `-- third_party_services.md           # Stripe, SendGrid, Twilio integrations
|
|-- 04_SPECIFICATIONS/                     [DETAILED] Implementation-ready specifications
|   |-- _spec_template.md                 # Standard template for all specifications
|   |-- api_endpoints/                    # Detailed endpoint specifications
|   |   |-- auth/
|   |   |   |-- POST_login.spec.md        # Request/response, validation, errors
|   |   |   `-- POST_register.spec.md     # Full implementation details
|   |   `-- resources/
|   |       `-- GET_users_id.spec.md      # Resource endpoint specs
|   |-- components/                       # Frontend component specifications
|   |   |-- AuthForm.spec.md              # Props, state, behavior, edge cases
|   |   `-- DataTable.spec.md             # Reusable component specifications
|   |-- workflows/                        # Complex multi-step processes
|   |   `-- payment_processing.spec.md    # Stripe integration flow
|   `-- algorithms/                       # Core business logic specifications
|       `-- recommendation_engine.spec.md # Detailed algorithm design
|
|-- 05_DECISIONS/                          [RATIONAL] The "why" behind every choice
|   |-- _decision_template.md             # ADR-inspired template
|   |-- active/                           # Current decisions we're operating under
|   |   |-- 2024-08-05-001-use-nextjs.md  # "Chose Next.js over Remix because..."
|   |   |-- 2024-08-06-002-postgres-over-mongo.md # Database selection rationale
|   |   `-- 2024-08-07-003-jwt-authentication.md  # Auth strategy decision
|   |-- superseded/                       # Decisions we've changed our mind about
|   |   `-- 2024-07-01-001-use-firebase.md # "Originally chose Firebase, but..."
|   `-- research/                         # Evidence supporting decisions
|       |-- auth_provider_comparison.md   # Auth0 vs Supabase vs Clerk analysis
|       `-- database_benchmarks.md        # Performance testing results
|
|-- 06_IMPLEMENTATION/                     [TACTICAL] Development-specific documentation
|   |-- conventions/                      # Team standards and patterns
|   |   |-- code_style.md                 # Prettier config, naming conventions
|   |   |-- git_workflow.md               # Branching strategy, commit format
|   |   `-- testing_strategy.md           # Unit, integration, E2E approach
|   |-- setup_guides/                     # How to get started
|   |   |-- local_development.md          # Step-by-step local env setup
|   |   `-- deployment_guide.md           # How to deploy to production
|   |-- troubleshooting/                  # Common issues and solutions
|   |   `-- common_errors.md              # Known issues with fixes
|   `-- module_docs/                      # Code-specific documentation
|       |-- auth_module.md                # How the auth system works
|       `-- payment_module.md             # Payment processing implementation
|
|-- 07_OPERATIONS/                         [PROCEDURAL] Running the live system
|   |-- runbooks/                         # Operational procedures
|   |   |-- incident_response.md          # What to do when things break
|   |   |-- backup_restore.md             # Disaster recovery procedures
|   |   `-- scaling_playbook.md           # How to handle traffic spikes
|   |-- maintenance/                      # Recurring tasks
|   |   |-- dependency_updates.md         # npm update strategy
|   |   `-- database_maintenance.md       # Cleanup, optimization tasks
|   `-- post_mortems/                     # Learning from failures
|       `-- 2024-08-15-auth-outage.md     # What happened, why, how we fixed it
|
`-- 08_DIALOGUE/                           [ACTIVE] Ongoing conversations and thinking
    |-- open_questions/                   # Unresolved issues requiring decisions
    |   |-- HIGH_should_we_use_kubernetes.md # "Considering k8s, but..."
    |   |-- MED_payment_provider_choice.md   # "Stripe vs Paddle..."
    |   `-- LOW_color_scheme_direction.md    # "Dark mode first or..."
    |-- hypotheses/                       # Ideas being explored
    |   `-- ai_powered_recommendations.md # "What if we added..."
    |-- spikes/                           # Technical investigations
    |   `-- websocket_scaling_test.md     # "Tested Socket.io with 10k connections..."
    |-- meeting_notes/                    # Stakeholder/advisor conversations
    |   `-- 2024-08-10-advisor-feedback.md # Key insights from discussions
    `-- input_stream.log                  # Raw, timestamped input from human developer
```

### 2.2 Document Taxonomy

#### 2.2.1 Primary Document Types

| Type | Extension | Purpose | Lifecycle | Location |
|------|-----------|---------|-----------|----------|
| **Manifest** | `_MANIFEST.md` | Single source of truth overview | Pipeline-regenerated | Root |
| **Product Spec** | `.md` | Business/user feature definition | Draft → Approved → Implemented | `01_PRODUCT/features/` |
| **Journey Map** | `.md` | User flow documentation | Draft → Validated | `02_DESIGN/user_journeys/` |
| **Technical Spec** | `.spec.md` | Implementation blueprint | Draft → Approved → Built | `04_SPECIFICATIONS/` |
| **Decision Record** | `.md` | Architectural/strategic choices | Proposed → Active/Superseded | `05_DECISIONS/` |
| **Runbook** | `.md` | Operational procedures | Draft → Tested → Active | `07_OPERATIONS/runbooks/` |
| **Open Question** | `.md` | Unresolved issues | Open → Answered/Deferred | `08_DIALOGUE/open_questions/` |
| **Research Note** | `.md` | Investigation findings | Research → Referenced | `05_DECISIONS/research/` |
| **Index** | `.json` | Relationship metadata | Pipeline-maintained | `_INDEX/` |
| **Pipeline State** | `.json/.yaml` | Pipeline processing artifacts | Temporary | `_pipeline/` |

#### 2.2.2 Document Header Standard

Every document MUST begin with a YAML frontmatter block:

```yaml
---
codex_version: 1.1
document_id: AUTH-001
document_type: specification
state: approved
created: 2024-08-05T10:00:00Z
modified: 2024-08-06T15:30:00Z
author: PRISM-Synthesis
pipeline_stage: 3
sources: [INPUT-STREAM-234, INPUT-STREAM-237]
dependencies: [PROD-FEAT-001, ARCH-003, DEC-045]
supersedes: []
tags: [authentication, security, user-management, mvp]
confidence: high
priority: P0
---
```

### 2.3 State Management Model

All state transitions occur exclusively through pipeline execution with manual approval:

- **[*] → Embryonic:** Pipeline Stage 1 (Extraction)
- **Embryonic → Proposed:** Pipeline Stage 3 (Synthesis) + Manual Review
- **Proposed → Accepted:** Manual Decision + Pipeline Stage 4 (Integration)
- **Proposed → Rejected:** Manual Decision + Pipeline Archival
- **Accepted → Implemented:** Development Complete + Pipeline Update
- **Implemented → Validated:** Testing Complete + Pipeline Update
- **Validated → Operational:** Deployment + Pipeline Update
- **Operational → Deprecated:** Manual Decision + Pipeline Archival
- **Rejected → [*]:** Pipeline Cleanup
- **Deprecated → [*]:** Pipeline Archival

## 3. Document Formats & Templates

### 3.1 The Sacred Manifest Format

```markdown
# PROJECT CODEX MANIFEST
_Generated: [timestamp] | Version: [semver] | Hash: [sha256]_
_Pipeline: PRISM v1.1 | Last Run: [timestamp] | Status: [status]_

## Mission
[Single sentence capturing the project's reason for existence]

## Current State
- **Phase:** [Ideation|Design|Development|Production|Maintenance]
- **Momentum:** [Starting|Accelerating|Steady|Slowing|Paused]
- **Health:** [Green|Yellow|Red] ([validation_score]% validation pass rate)
- **Pipeline:** [Ready|Processing|Blocked] - [last_stage_completed]

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

## Pipeline Status
- **Last Run:** [timestamp]
- **Documents Processed:** [count]
- **New:** [count] | **Modified:** [count] | **Conflicts:** [count]
- **Next Run Scheduled:** [Manual - awaiting input]

## Navigation
- [Product Overview](01_PRODUCT/overview.md)
- [Feature Map](01_PRODUCT/features/_feature_map.md)
- [Design System](02_DESIGN/design_system.md)
- [Architecture Overview](03_ARCHITECTURE/system_design.md)
- [Active Decisions](05_DECISIONS/active/)
- [Open Questions](08_DIALOGUE/open_questions/)

## Semantic Index
Primary Concepts: [tag1, tag2, tag3, tag4, tag5]
Document Count: [total] | Last Update: [timestamp]
Link Density: [average] | Orphan Rate: [percentage]
```

### 3.2 Product Feature Template

```markdown
# Feature: [Feature Name]
_Feature ID: [PROD-FEAT-XXX] | State: [draft|approved|implemented]_
_Pipeline: Stage [N] | Processed: [timestamp]_

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

## Pipeline Metadata
- Extracted: [Stage 1 timestamp]
- Classified: [Stage 2 timestamp]
- Synthesized: [Stage 3 timestamp]
- Integrated: [Stage 4 timestamp]
- Validated: [Stage 5 timestamp]
- Published: [Stage 6 timestamp]
```

### 3.3 Technical Specification Template

```markdown
# Technical Specification: [Component/Feature Name]
_Spec ID: [SPEC-XXX] | State: [draft|approved|implemented] | Priority: [P0-P3]_
_Pipeline: Stage [N] | Processed: [timestamp]_

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

- **Unit Tests:** [Coverage target]
- **Integration Tests:** [Key scenarios]
- **E2E Tests:** [Critical paths]

## Performance Considerations

- **Expected Load:** [Requests/second]
- **Latency Target:** [p50, p95, p99]
- **Caching Strategy:** [Approach]

## Security Considerations

- **Authentication:** [Method]
- **Authorization:** [Rules]
- **Data Validation:** [Approach]

## References

- **Architecture Decision:** [05_DECISIONS/active/relevant-decision.md]
- **Research:** [05_DECISIONS/research/relevant-research.md]

## Pipeline Metadata
- Source Units: [U001, U002, U003]
- Synthesis Confidence: [0.95]
- Integration Conflicts: [None|Resolved]
- Validation Score: [100%]
```

### 3.4 Decision Record Template

```markdown
# DEC-XXX: [Decision Title]
_Date: [YYYY-MM-DD] | State: [proposed|active|superseded] | Confidence: [low|medium|high]_
_Pipeline: Stage [N] | Processed: [timestamp]_

## Context
[What situation/problem necessitated this decision?]

## Decision
[Clear statement of what was decided]

## Rationale
[Why this option was chosen]

### Pros
- [Positive consequence]
- [Positive consequence]

### Cons
- [Trade-off accepted]
- [Negative consequence]

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

## Pipeline Metadata
- Extracted From: [Source conversation/document]
- Classification Confidence: [0.XX]
- Manual Override: [Yes/No - details]
```

---

## 4. PRISM Pipeline Architecture

### 4.1 Pipeline Overview

The PRISM Architecture (Progressive Refinement through Isolated Specialized Modules) operates as a 6-stage, manually-orchestrated pipeline with 7 specialized sub-agents. Each stage requires human verification before proceeding to the next.

**Core Principles:**
- **Full Manual Control:** Every stage initiated by human action
- **Isolated Processing:** Each sub-agent operates in its own 200k token context window
- **State Persistence:** Pipeline state saved between manual invocations
- **No Background Operations:** System dormant between pipeline runs
- **GUI-Ready Design:** Optimized for drag-drop input and button-triggered execution

**Pipeline Flow:**

```text
[Manual Input] -> EXTRACTION -> [Human Review] -> CLASSIFICATION -> [Human Review] ->
SYNTHESIS (Dual) -> [Human Review] -> INTEGRATION -> [Human Review] ->
VALIDATION -> [Human Review] -> PUBLICATION -> [Human Approval] -> [Git Commit]
```


### 4.2 Sub-Agent Specifications

| Stage | Sub-Agent | Primary Function | Input | Output |
|-------|-----------|-----------------|-------|---------|
| **1** | `extractor` | Parse unstructured input into atomic knowledge units | Raw text files (.txt, .md, .json) | `_pipeline/extracted_units.json` |
| **2** | `classifier` | Categorize units into Codex layers and assign metadata | `extracted_units.json` | `_pipeline/classified_units.json` |
| **3A** | `synthesizer-content` | Transform classified units into Codex documents | `classified_units.json` | `_pipeline/synthesized_documents/` |
| **3B** | `synthesizer-relationships` | Establish cross-references and dependency graphs | `synthesized_documents/` + existing codex | `_pipeline/relationship_map.json` |
| **4** | `integrator` | Merge new documents with existing codex, resolve conflicts | Synthesized docs + relationship map | Updated codex files |
| **5** | `validator` | Ensure quality invariants and consistency | Integrated codex | `_pipeline/validation_report.json` |
| **6** | `publisher` | Regenerate manifest, update indices, prepare commit | Validated codex | Updated `_MANIFEST.md` + staged git changes |

### 4.3 Context Window Management

Each sub-agent operates with an independent 200k token context window, optimized for its specific task:

| Sub-Agent | Context Strategy | Token Usage | Rationale |
|-----------|-----------------|-------------|-----------|
| `extractor` | Minimal | 5-10k | Focus on parsing rules only |
| `classifier` | Medium | 20-30k | Needs codex structure awareness |
| `synthesizer-content` | Medium | 30-40k | Templates + examples |
| `synthesizer-relationships` | Large | 50-100k | Full document graph needed |
| `integrator` | Maximum | 150-200k | Complete codex for deduplication |
| `validator` | Maximum | 150-200k | Comprehensive consistency checks |
| `publisher` | Medium | 40-50k | Key documents for manifest |

### 4.4 Quality Guarantees

The pipeline maintains these invariants through staged validation:

**Stage 1 (Extraction):**
- All input text parsed into discrete units
- Each unit assigned confidence score
- Source line tracking maintained

**Stage 2 (Classification):**
- Every unit assigned to exactly one layer
- Priority and state assignments validated
- No units lost in classification

**Stage 3 (Synthesis):**
- No orphan documents created
- All required template sections filled
- Bidirectional relationships established

**Stage 4 (Integration):**
- Deduplication threshold: 70% similarity
- Conflict resolution strategy defined
- No data loss during merge

**Stage 5 (Validation):**
- Link integrity: 100% valid references
- State consistency: No invalid transitions
- Minimum link density: 3 per document

**Stage 6 (Publication):**
- Manifest under 1000 words
- All indices updated
- Git staging atomic and complete

---

## 5. Lifecycle Management

### 5.1 PRISM Processing Pipeline

The PRISM pipeline replaces continuous processing with deliberate, staged transformations:

```
Stage 1: EXTRACTION
|-- Input: Raw conversation/notes/documents
|-- Process: Parse into atomic knowledge units
|-- Output: extracted_units.json
`-- Manual Checkpoint: Review unit accuracy

Stage 2: CLASSIFICATION
|-- Input: extracted_units.json
|-- Process: Categorize into Codex layers
|-- Output: classified_units.json
`-- Manual Checkpoint: Confirm layer assignments

Stage 3: SYNTHESIS (Dual Agent)
|-- 3A: Content Generation
|   |-- Input: classified_units.json
|   |-- Process: Create Codex documents
|   `-- Output: synthesized_documents/
|-- 3B: Relationship Mapping
|   |-- Input: synthesized_documents/
|   |-- Process: Build connection graph
|   `-- Output: relationship_map.json
`-- Manual Checkpoint: Review quality

Stage 4: INTEGRATION
|-- Input: synthesized_documents/ + relationship_map.json
|-- Process: Merge with existing codex
|-- Output: Updated codex structure
`-- Manual Checkpoint: Approve conflicts

Stage 5: VALIDATION
|-- Input: Integrated codex
|-- Process: Check quality invariants
|-- Output: validation_report.json
`-- Manual Checkpoint: Address failures

Stage 6: PUBLICATION
|-- Input: Validated codex
|-- Process: Regenerate manifest, update indices
|-- Output: Git-staged changes
`-- Manual Checkpoint: Commit decision
```


### 5.2 Stage-Specific Processing

Each pipeline stage applies layer-aware processing rules:

**Stage 1 - Extraction Rules:**
- Break compound statements into atomic units
- Preserve context and confidence
- Tag with potential categories
- Extract implicit metadata (dates, priorities, states)

**Stage 2 - Classification Rules:**
- Apply path resolution matrix
- Assign to single primary layer
- Determine document type and state
- Set priority based on keywords and context

**Stage 3A - Content Synthesis Rules:**
- Apply appropriate document template
- Merge related units into cohesive sections
- Generate required frontmatter
- Maintain source traceability

**Stage 3B - Relationship Synthesis Rules:**
- Identify cross-references
- Build bidirectional links
- Create dependency chains
- Map semantic relationships

**Stage 4 - Integration Rules:**
- Check similarity threshold (70%)
- Apply conflict resolution (newer wins by default)
- Preserve existing accepted states
- Update cross-references in existing documents

**Stage 5 - Validation Rules:**
- Verify no orphaned documents
- Check link integrity
- Validate state transitions
- Ensure minimum link density (3.0)

**Stage 6 - Publication Rules:**
- Generate manifest from key documents
- Update all index files
- Create semantic commit message
- Stage all changes atomically

### 5.3 Pipeline-Initiated Triggers

All state transitions occur exclusively through pipeline execution with manual approval:

| Trigger | Condition | Pipeline Stage | Manual Gate |
|---------|-----------|---------------|-------------|
| **Document Creation** | New content synthesized | Stage 3 | Review before integration |
| **State Graduation** | Approval criteria met | Stage 4 | Approve state change |
| **Supersession** | Conflict detected | Stage 4 | Choose resolution |
| **Question Resolution** | Answer provided | Stage 3 | Confirm answer completeness |
| **Link Update** | New relationships found | Stage 3B | Verify relationship accuracy |
| **Archival** | Document deprecated | Stage 4 | Confirm archival |

### 5.4 Archival Policy

Archive operations occur only during pipeline Stage 4 (Integration):

- **Active Retention:** All documents in states [proposed, accepted, implemented, operational]
- **Archive Trigger:** Manual deprecation decision during integration review
- **Archive Location:** Move to `/_ARCHIVE/[year]/[original-path]`
- **Archive Metadata:** Preserve all links, add `archived_date`, `archived_reason`, `pipeline_run_id`
- **Recovery:** Archived documents can be restored in next pipeline run

---

## 6. Integration Patterns

### 6.1 Human Developer Interface

**Pipeline Invocation Patterns:**

```bash
# Stage 1: Extract from new input
claude run --agent extractor --input-file inbox/conversation.txt

# Stage 2: Classify extracted units
claude run --agent classifier --input-file _pipeline/extracted_units.json

# Stage 3A: Synthesize content
claude run --agent synthesizer-content --input-file _pipeline/classified_units.json

# Stage 3B: Map relationships
claude run --agent synthesizer-relationships --auto-approve

# Stage 4: Integrate with existing codex
claude run --agent integrator --plan  # Preview first
claude run --agent integrator --require-approval=writes

# Stage 5: Validate codex
claude run --agent validator --output json

# Stage 6: Publish and prepare commit
claude run --agent publisher --require-approval=all
```

**Query Patterns (Between Pipeline Runs):**

- "What did we decide about [topic]?" → check `05_DECISIONS/active/`
- "Show me pipeline status" → open `_pipeline/state.yaml`
- "What failed validation?" → review `_pipeline/validation_report.json`
- "Show integration conflicts" → inspect Stage 4 output

**Manual Intervention Points:**

- After Extraction: Review unit accuracy, completeness
- After Classification: Adjust layer assignments if needed
- After Synthesis: Check document quality, relationships
- After Integration: Resolve conflicts, approve merges
- After Validation: Address any failures
- Before Publication: Final review before commit

**Pipeline State Management:**

```yaml
# _pipeline/state.yaml
current_stage: 4
last_completed: 3
status: awaiting_manual_review
started: 2024-12-15T10:00:00Z
last_activity: 2024-12-15T10:45:00Z
stages:
  extraction:
    completed: true
    timestamp: 2024-12-15T10:05:00Z
    units_extracted: 24
  classification:
    completed: true
    timestamp: 2024-12-15T10:15:00Z
    units_classified: 24
  synthesis:
    completed: true
    timestamp: 2024-12-15T10:30:00Z
    documents_created: 12
    relationships_mapped: 42
  integration:
    completed: false
    status: conflicts_detected
    conflicts: 2
artifacts:
  extraction: _pipeline/extracted_units.json
  classification: _pipeline/classified_units.json
  synthesis: _pipeline/synthesized_documents/
  relationships: _pipeline/relationship_map.json
```

### 6.2 AI Coding Assistant Interface

**Context Consumption from Pipeline Output:**

After pipeline completion, coding assistants access documentation through:

- **Primary Entry:** Always start with `_MANIFEST.md` for project overview
- **Layer Navigation:** Follow manifest links to specific layers
- **Dependency Traversal:** Use `_INDEX/dependency_graph.json` for related documents
- **State Awareness:** Check `_INDEX/state_registry.json` for document status

**Pipeline-Aware Context Bundles:**

```json
{
  "pipeline_context": {
    "last_run": "2024-12-15T14:55:00Z",
    "documents_updated": 48,
    "validation_score": 0.75,
    "new_decisions": ["DEC-001", "DEC-002", "DEC-004"],
    "open_questions": 3
  },
  "feature_context": {
    "type": "feature_implementation",
    "target": "user-authentication",
    "pipeline_verified": true,
    "include_layers": [
      "01_PRODUCT/features/core/user_authentication.md",
      "02_DESIGN/user_journeys/onboarding_flow.md",
      "03_ARCHITECTURE/security_model.md",
      "04_SPECIFICATIONS/api_endpoints/auth/",
      "05_DECISIONS/active/*auth*.md",
      "06_IMPLEMENTATION/conventions/"
    ],
    "validation_notes": "2 broken links identified, awaiting fix"
  }
}
```

**Integration with Development Workflow:**

- **Pre-Development:** Run pipeline to ensure documentation current
- **During Development:** Reference pipeline-validated specifications
- **Post-Development:** Update documentation via new pipeline run
- **Code Review:** Include pipeline validation report

**Synchronization Protocol:**

```yaml
# Before starting feature development
1. Check pipeline last run timestamp
2. If > 24 hours old, request new pipeline run
3. Wait for validation stage completion
4. Pull context bundle from validated codex

# After completing feature
1. Document changes in input format
2. Trigger pipeline extraction
3. Review synthesis output
4. Approve integration
5. Commit code + documentation together
```

## 7. Success Metrics

The Codex implementation with PRISM Pipeline is successful when:

| Metric | Target | Measurement |
|--------|--------|-------------|
| **Pipeline Completion Rate** | 95% | Successful runs / Total runs |
| **Average Pipeline Time** | <30 min | Total time from Stage 1 to Stage 6 |
| **Stage Success Rate** | >90% per stage | Stages passed without retry |
| **Manual Intervention Time** | <5 min per stage | Average human review time |
| **Extraction Accuracy** | 95% | Correctly parsed units / Total units |
| **Classification Precision** | 90% | Correctly categorized / Total classified |
| **Synthesis Quality** | 85% | Documents passing validation / Total created |
| **Integration Conflicts** | <10% | Conflicts / Total documents |
| **Validation Pass Rate** | >75% | Checks passed / Total checks |
| **Link Density** | 3+ per document | Average bidirectional connections |
| **State Clarity** | 100% | Documents with defined states |
| **Deduplication Rate** | >80% | Duplicates caught / Total similar |
| **Manifest Generation** | <5 seconds | Time to regenerate manifest |
| **Git Staging Accuracy** | 100% | Correctly staged files / Total changes |
| **Orphan Rate** | 0% | Orphaned documents / Total documents |

**Pipeline-Specific Performance Targets:**

| Stage | Target Duration | Success Criteria |
|-------|-----------------|------------------|
| Extraction | <2 min | 95% unit confidence |
| Classification | <3 min | 90% correct layer assignment |
| Synthesis | <10 min | All templates filled |
| Integration | <5 min | <5 conflicts |
| Validation | <5 min | >75% pass rate |
| Publication | <5 min | Complete staging |

---

## 8. Standard Evolution

This standard itself follows Codex principles with pipeline-mediated updates:

- **Version:** 1.1 (PRISM Architecture)
- **State:** Active
- **Implementation:** PRISM Pipeline as reference implementation
- **Processing Mode:** Manual pipeline orchestration
- **Last Revision:** Introduced PRISM Architecture for manual pipeline processing
- **Next Review:** After 50 pipeline runs or 100 documents created
- **Evolution Path:** Collect pipeline metrics -> Identify bottlenecks -> Propose v1.2 amendments
- **Backwards Compatibility:** All v1.x versions must be pipeline-compatible
- **Change Log:**
  - v1.1: Introduced PRISM Architecture with 6-stage pipeline
  - v1.1: Added 7 specialized sub-agents for isolated processing
  - v1.1: Replaced autonomous operations with manual orchestration
  - v1.1: Added pipeline state management and persistence
  - v1.1: Enhanced metrics for pipeline performance tracking
  - v1.1: Added Pipeline Operation Manual (Section 9)
  - v1.1: Added Sub-Agent Behavioral Specifications (Section 10)

---

## 9. Pipeline Operation Manual

### 9.1 Pre-Pipeline Checklist

Before initiating pipeline:
- [ ] Backup existing codex
- [ ] Clear `_pipeline/` directory
- [ ] Prepare input files in supported formats (.txt, .md, .json)
- [ ] Ensure 30+ minutes available for full pipeline run
- [ ] Review previous validation report if exists

### 9.2 Stage-by-Stage Execution Guide

**Stage 1: Extraction**
```bash
# Execute
claude run --agent extractor --input-file [input_file]

# Review Points
- Check unit atomicity
- Verify confidence scores
- Confirm no content lost
- Adjust parsing if needed

# Common Issues
- Compound units: Manually split in JSON
- Low confidence: Add context in notes field
- Missing content: Check input format
```

**Stage 2: Classification**
```bash
# Execute
claude run --agent classifier --input-file _pipeline/extracted_units.json

# Review Points
- Verify layer assignments
- Check priority levels
- Confirm document paths
- Adjust states if needed

# Common Adjustments
- Move between layers
- Merge similar units
- Adjust priority (P0-P3)
- Correct document types
```

**Stage 3: Synthesis**
```bash
# Execute Part A
claude run --agent synthesizer-content --input-file _pipeline/classified_units.json

# Execute Part B
claude run --agent synthesizer-relationships --auto-approve

# Review Points
- Document completeness
- Relationship accuracy
- Template compliance
- Content coherence

# Quality Checks
- All sections filled?
- Links bidirectional?
- Frontmatter complete?
- No contradictions?
```

**Stage 4: Integration**
```bash
# Preview first
claude run --agent integrator --plan

# Then execute
claude run --agent integrator --require-approval=writes

# Conflict Resolution
- SIMILAR: Merge or keep separate?
- CONFLICT: New or existing?
- STATE: Higher or lower?
- PRIORITY: Escalate or maintain?
```

**Stage 5: Validation**
```bash
# Execute
claude run --agent validator --output json

# Address Issues
- ORPHANS: Add links
- BROKEN LINKS: Fix or remove
- MISSING FIELDS: Add metadata
- STALE: Review and update
```

**Stage 6: Publication**
```bash
# Execute
claude run --agent publisher --require-approval=all

# Final Review
- Manifest accurate?
- Indices updated?
- Git staging correct?
- Commit message clear?

# Commit
git commit -m "docs: [Pipeline Run] <description>"
git push origin main
```

### 9.3 Pipeline State Recovery
If pipeline interrupted:

```bash
# Check state
cat _pipeline/state.yaml

# Resume from last completed stage
claude run --agent [next_agent] --resume

# Or restart stage
claude run --agent [current_agent] --force-restart
```

### 9.4 Rollback Procedures
If pipeline produces incorrect results:

```bash
# Restore from backup
git reset --hard HEAD~1

# Or selective revert
git checkout HEAD~1 -- /codex/[specific_file]

# Clear pipeline artifacts
rm -rf _pipeline/*

# Document issue for next run
echo "Issue: [description]" >> _pipeline/rollback_notes.md
```

### 9.5 Pipeline Optimization Tips

- **Batch Processing:** Accumulate inputs for weekly runs
- **Pre-Classification:** Organize inputs by type before extraction
- **Template Preparation:** Customize templates before synthesis
- **Conflict Avoidance:** Review existing docs before pipeline run
- **Validation Focus:** Address P0 issues first

---

## 10. Sub-Agent Behavioral Specifications

### 10.1 Extractor Agent

**Purpose:** Transform unstructured input into atomic knowledge units

**Behavioral Rules:**

- Break compound statements at logical boundaries
- Preserve original context in metadata
- Assign confidence based on clarity (0.0-1.0)
- Tag with potential categories
- Extract implicit information (dates, priorities)
- Never merge distinct concepts
- Maintain source line references

**Input Schema:**

- Raw text file (.txt, .md, .json)

**Output Schema:**

```json
{
  "metadata": {
    "source_file": "string",
    "extraction_timestamp": "ISO8601",
    "total_units": "number"
  },
  "units": [{
    "id": "U[000]",
    "type": "enum[vision|feature|requirement|decision|question]",
    "content": "string",
    "context": "string",
    "confidence": "float",
    "source_line": "number",
    "tags": ["string"]
  }]
}
```

### 10.2 Classifier Agent

**Purpose:** Categorize extracted units into Codex layers

**Behavioral Rules:**

- Apply path resolution matrix strictly
- Assign single primary layer
- Infer state from language patterns
- Set priority based on keywords
- Preserve extraction metadata
- Generate suggested file paths
- Identify relationships to existing docs

**Input Schema:**

```json
extracted_units.json
```

**Output Schema:**

```json
{
  "metadata": {
    "classification_timestamp": "ISO8601",
    "total_classified": "number"
  },
  "classified": [{
    "unit_id": "string",
    "target_layer": "string",
    "document_type": "string",
    "suggested_path": "string",
    "tags": ["string"],
    "state": "string",
    "priority": "enum[P0|P1|P2|P3]",
    "confidence": "float",
    "relationships": ["string"]
  }]
}
```

### 10.3 Synthesizer-Content Agent

**Purpose:** Transform classified units into Codex documents

**Behavioral Rules:**

- Apply correct template for document type
- Merge related units into sections
- Generate complete frontmatter
- Maintain source traceability
- Follow Codex formatting standards
- Ensure all required sections present
- Synthesize coherent narrative

**Input Schema:**

```json
classified_units.json
```

**Output Schema:**

```text
_pipeline/synthesized_documents/
|-- 01_PRODUCT/
|   `-- features/
|       `-- [feature_name].md
|-- 05_DECISIONS/
|   `-- active/
|       `-- [YYYY-MM-DD-###-title].md
`-- [other_layers]/
```

### 10.4 Synthesizer-Relationships Agent

**Purpose:** Build connection graph between documents

**Behavioral Rules:**

- Scan all documents for references
- Create bidirectional links
- Identify dependency chains
- Map semantic relationships
- Detect implicit connections
- Maintain minimum 3 links per doc
- Prevent circular dependencies

**Input Schema:**

- synthesized_documents/ + existing /codex/

**Output Schema:**

```json
{
  "relationships": [{
    "source": "document_id",
    "target": "document_id",
    "type": "enum[depends|implements|supersedes|relates]",
    "bidirectional": "boolean",
    "strength": "float"
  }],
  "statistics": {
    "total_documents": "number",
    "total_relationships": "number",
    "average_links": "float",
    "orphans": ["string"]
  }
}
```

### 10.5 Integrator Agent

**Purpose:** Merge new documents with existing codex

**Behavioral Rules:**

- Check similarity threshold (70%)
- Apply deduplication strategy
- Resolve conflicts by recency
- Preserve accepted states
- Update cross-references
- Maintain file organization
- Log all merge decisions

**Input Schema:**

- synthesized_documents/ + relationship_map.json + existing /codex/

**Output Schema:**

Updated /codex/ structure with integration report:

```json
{
  "new_files": ["string"],
  "modified_files": ["string"],
  "conflicts_resolved": [{
    "file": "string",
    "type": "string",
    "resolution": "string"
  }],
  "duplicates_merged": ["string"]
}
```

### 10.6 Validator Agent

**Purpose:** Ensure codex quality and consistency

**Behavioral Rules:**

- Check all quality invariants
- Verify link integrity
- Validate state transitions
- Ensure completeness
- Calculate metrics
- Flag issues by severity
- Never modify documents

**Input Schema:**

- Complete integrated /codex/

**Output Schema:**

```json
{
  "validation_timestamp": "ISO8601",
  "overall_health": "enum[GREEN|YELLOW|RED]",
  "score": "float",
  "checks": [{
    "name": "string",
    "result": "enum[PASS|WARN|FAIL]",
    "details": "string"
  }],
  "issues": [{
    "severity": "enum[INFO|WARNING|ERROR]",
    "location": "string",
    "description": "string",
    "suggestion": "string"
  }],
  "metrics": {
    "link_density": "float",
    "orphan_rate": "float",
    "state_clarity": "float",
    "freshness": "float"
  }
}
```

### 10.7 Publisher Agent

**Purpose:** Prepare codex for commit and distribution

**Behavioral Rules:**

- Regenerate manifest under 1000 words
- Update all index files
- Create semantic commit message
- Stage changes atomically
- Include pipeline metadata
- Never auto-commit
- Generate publication report

**Input Schema:**

- Validated /codex/

**Output Schema:**

- Updated _MANIFEST.md
- Updated _INDEX/*.json
- Git staged changes
- Commit message draft
- Publication report:

```json
{
  "publication_timestamp": "ISO8601",
  "documents_published": "number",
  "new": "number",
  "modified": "number",
  "indices_updated": ["string"],
  "commit_message": "string",
  "staged_files": ["string"]
}
```

---

## Appendix A: Quick Reference Card

### Pipeline Stage Progression

```text
EXTRACTION -> CLASSIFICATION -> SYNTHESIS -> INTEGRATION -> VALIDATION -> PUBLICATION
```

### Document State Progression (Pipeline-Mediated)

```text
Embryonic -> Proposed -> Accepted -> Implemented -> Validated -> Operational -> Deprecated
```

### Priority Levels

- **P0:** Blocking MVP
- **P1:** Required for launch
- **P2:** Important but not critical
- **P3:** Nice to have

### Confidence Levels

- **High:** Based on evidence and validation
- **Medium:** Reasonable assumptions
- **Low:** Speculation or untested hypothesis

### Pipeline Commands Quick Reference
```bash
# Full pipeline run
claude run --agent extractor --input-file input.txt
claude run --agent classifier --input-file _pipeline/extracted_units.json
claude run --agent synthesizer-content --input-file _pipeline/classified_units.json
claude run --agent synthesizer-relationships
claude run --agent integrator --require-approval=writes
claude run --agent validator --output json
claude run --agent publisher --require-approval=all

# Check pipeline state
cat _pipeline/state.yaml

# Preview changes
claude run --agent [any_agent] --plan

# Auto-approve mode (careful!)
claude run --agent [any_agent] --auto-approve
```

### Folder Quick Reference

- **Product** → Business/user perspective
- **Design** → User experience
- **Architecture** → System design
- **Specifications** → Implementation details
- **Decisions** → Rationale and choices
- **Implementation** → Developer guides
- **Operations** → Running the system
- **Dialogue** → Active thinking
- **_pipeline** → Temporary processing artifacts
- **_INDEX** → System metadata

### Common Pipeline Issues & Solutions

| Issue | Solution |
| --- | --- |
| Low extraction confidence | Add context to input |
| Wrong classification | Manually adjust in JSON |
| Synthesis incomplete | Check template match |
| Integration conflicts | Review resolution strategy |
| Validation failures | Address by priority |
| Publication too large | Increase manifest limit |

---

## Appendix B: AI-Optimized Reference

**Note:** This appendix contains machine-readable specifications for AI agents. The full AI-optimized reference is maintained in a separate file: `project_codex_ai_optimized.md`

For AI agent consumption, refer to the dedicated AI-optimized reference document which includes:

- Machine-parseable YAML specifications
- Structured behavioral rules
- Pipeline state machines
- Validation schemas
- Context window optimization strategies
- Error handling protocols 
