# Project Codex AI v1.1 - PRISM Architecture Reference

**Machine-Optimized Reference for AI Agent Consumption**

---

## Document Information

| Attribute | Value |
|-----------|-------|
| **Version** | 1.1-AI-PRISM |
| **Type** | AI Agent Reference |
| **Implementation** | PRISM Architecture |
| **Last Updated** | 2025-08-07 |
| **Source Parity** | Complete |
| **Optimization** | Machine Parsing |
| **Processing Mode** | Manual Pipeline Orchestration |

---

## Table of Contents

1. [Document Information](#document-information)
2. [Standard Metadata](#standard-metadata)
3. [Core Directives](#core-directives)
4. [File System Rules](#file-system-rules)
5. [PRISM Pipeline Specification](#prism-pipeline-specification)
6. [PRISM Sub-Agent Specifications](#prism-sub-agent-specifications)
7. [Document Processing Rules](#document-processing-rules)
8. [Classification Matrix](#classification-matrix)
9. [State Transition Rules](#state-transition-rules)
10. [Synthesis Algorithms](#synthesis-algorithms)
11. [Quality Invariants](#quality-invariants)
12. [Pipeline State Management](#pipeline-state-management)
13. [Query Response Patterns](#query-response-patterns)
14. [Success Metrics & Thresholds](#success-metrics-thresholds)
15. [Context Injection Protocol](#context-injection-protocol)
16. [Archival Rules](#archival-rules)
17. [Error Handling](#error-handling)
18. [Standard Evolution Tracking](#standard-evolution-tracking)

---

## Standard Metadata

```yaml
version: 1.1-AI-PRISM
type: ai_agent_reference
implementation: PRISM_architecture
source_parity: complete
optimization: machine_parsing
encoding: structured_directives
processing_mode: manual_pipeline_orchestration
```

---

## Core Directives

```yaml
cognitive_symbiosis:
  definition: "Human creativity + AI systematization = unified project consciousness"
  implementation: "Transform unstructured human thought into structured, interlinked knowledge via manual pipeline"
  mode: "Human-initiated pipeline stages with verification gates"
  
fundamental_axioms:
  - axiom: "Knowledge is stateful"
    states: ["embryonic", "proposed", "accepted", "implemented", "validated", "operational", "deprecated"]
  - axiom: "Context is paramount"
    rule: "Every document must maintain explicit bidirectional relationships"
  - axiom: "Synthesis supersedes storage"
    rule: "Always transform and compress rather than transcribe"
  - axiom: "The Manifest is sacred"
    rule: "Always maintain _MANIFEST.md as 1000-word maximum truth source"
  - axiom: "Human sovereignty"
    rule: "All operations require explicit human initiation and verification"
```

---

## File System Rules

```yaml
/codex/_MANIFEST.md:
  type: "sacred_overview"
  max_words: 1000
  regeneration_trigger: "pipeline_stage_6_publication"
  required_sections: ["mission", "current_state", "architecture", "priorities", "decisions", "questions", "navigation", "pipeline_status"]

/codex/_INDEX/:
  type: "system_metadata"
  update_trigger: "pipeline_stage_5_validation"
  files:
    dependency_graph.json: "document_relationships"
    state_registry.json: "document_lifecycle_states"
    semantic_map.json: "tag_and_concept_clustering"
    link_validation.log: "orphan_detection"

/codex/_pipeline/:
  type: "temporary_processing"
  lifecycle: "created_stage_1_cleared_stage_6"
  files:
    extracted_units.json: "stage_1_output"
    classified_units.json: "stage_2_output"
    synthesized_documents/: "stage_3a_output"
    relationship_map.json: "stage_3b_output"
    validation_report.json: "stage_5_output"
    state.yaml: "pipeline_state_persistence"

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

---

## PRISM Pipeline Specification

```yaml
pipeline_architecture:
  name: "PRISM"
  definition: "Progressive Refinement through Isolated Specialized Modules"
  stages: 6
  sub_agents: 7
  mode: "manual_orchestration"
  checkpoints: "between_every_stage"

stage_definitions:
  stage_1_extraction:
    agent: "extractor"
    input: "raw_text_files"
    output: "_pipeline/extracted_units.json"
    manual_checkpoint: "review_unit_accuracy"
    
  stage_2_classification:
    agent: "classifier"
    input: "_pipeline/extracted_units.json"
    output: "_pipeline/classified_units.json"
    manual_checkpoint: "confirm_layer_assignments"
    
  stage_3a_synthesis_content:
    agent: "synthesizer-content"
    input: "_pipeline/classified_units.json"
    output: "_pipeline/synthesized_documents/"
    manual_checkpoint: "review_document_quality"
    
  stage_3b_synthesis_relationships:
    agent: "synthesizer-relationships"
    input: "synthesized_documents + existing_codex"
    output: "_pipeline/relationship_map.json"
    manual_checkpoint: "verify_relationships"
    
  stage_4_integration:
    agent: "integrator"
    input: "synthesized_documents + relationship_map"
    output: "updated_codex_structure"
    manual_checkpoint: "approve_conflicts"
    
  stage_5_validation:
    agent: "validator"
    input: "integrated_codex"
    output: "_pipeline/validation_report.json"
    manual_checkpoint: "address_failures"
    
  stage_6_publication:
    agent: "publisher"
    input: "validated_codex"
    output: "staged_git_changes"
    manual_checkpoint: "commit_decision"
```

---

## PRISM Sub-Agent Specifications

```yaml
extractor:
  stage: 1
  context_window: "5-10k_tokens"
  responsibilities:
    - parse_unstructured_text
    - extract_atomic_units
    - assign_confidence_scores
    - preserve_source_context
  behavioral_rules:
    - break_compound_statements: true
    - preserve_context: true
    - confidence_range: [0.0, 1.0]
    - maintain_source_references: true
  output_schema:
    type: "json"
    structure: "units_array_with_metadata"

classifier:
  stage: 2
  context_window: "20-30k_tokens"
  responsibilities:
    - categorize_into_layers
    - assign_document_types
    - set_priority_levels
    - determine_lifecycle_states
  behavioral_rules:
    - single_layer_assignment: true
    - apply_path_resolution_matrix: true
    - infer_state_from_language: true
    - generate_file_paths: true
  output_schema:
    type: "json"
    structure: "classified_units_with_paths"

synthesizer-content:
  stage: 3a
  context_window: "30-40k_tokens"
  responsibilities:
    - transform_units_to_documents
    - apply_document_templates
    - merge_related_units
    - generate_frontmatter
  behavioral_rules:
    - use_correct_template: true
    - maintain_source_traceability: true
    - ensure_completeness: true
    - follow_codex_standards: true
  output_schema:
    type: "markdown_files"
    structure: "codex_compliant_documents"

synthesizer-relationships:
  stage: 3b
  context_window: "50-100k_tokens"
  responsibilities:
    - build_connection_graph
    - establish_bidirectional_links
    - identify_dependencies
    - map_semantic_relationships
  behavioral_rules:
    - minimum_links_per_doc: 3
    - bidirectional_required: true
    - prevent_circular_dependencies: true
    - cross_layer_linking: true
  output_schema:
    type: "json"
    structure: "relationship_graph"

integrator:
  stage: 4
  context_window: "150-200k_tokens"
  responsibilities:
    - merge_with_existing_codex
    - resolve_conflicts
    - deduplicate_content
    - update_cross_references
  behavioral_rules:
    - similarity_threshold: 0.7
    - preserve_accepted_states: true
    - newer_wins_conflicts: true
    - log_all_decisions: true
  output_schema:
    type: "file_system_updates"
    structure: "merged_codex_with_report"

validator:
  stage: 5
  context_window: "150-200k_tokens"
  responsibilities:
    - check_quality_invariants
    - verify_link_integrity
    - validate_state_transitions
    - calculate_metrics
  behavioral_rules:
    - never_modify_documents: true
    - flag_by_severity: true
    - comprehensive_coverage: true
    - generate_actionable_report: true
  output_schema:
    type: "json"
    structure: "validation_report_with_metrics"

publisher:
  stage: 6
  context_window: "40-50k_tokens"
  responsibilities:
    - regenerate_manifest
    - update_indices
    - prepare_git_commit
    - generate_publication_report
  behavioral_rules:
    - manifest_word_limit: 1000
    - atomic_staging: true
    - never_auto_commit: true
    - include_pipeline_metadata: true
  output_schema:
    type: "git_staging_plus_report"
    structure: "ready_for_commit"
```

---

## Document Processing Rules

### Classification Matrix

```yaml
input_classification:
  - pattern: ["revenue", "pricing", "market", "competitor", "business model"]
    action: "classify_for_synthesis"
    target: "01_PRODUCT/business_model.md"
    stage: 2
    
  - pattern: ["user wants", "customer needs", "as a user", "persona"]
    action: "classify_for_synthesis"
    target: "01_PRODUCT/user_personas/"
    stage: 2
    
  - pattern: ["feature", "capability", "should be able to", "functionality"]
    action: "classify_for_synthesis"
    target: "01_PRODUCT/features/"
    stage: 2
    
  - pattern: ["screen", "flow", "user sees", "interaction", "UI", "UX"]
    action: "classify_for_synthesis"
    target: "02_DESIGN/"
    stage: 2
    
  - pattern: ["framework", "database", "service", "library", "stack"]
    action: "classify_for_synthesis"
    target: "03_ARCHITECTURE/technical_stack.md"
    stage: 2
    
  - pattern: ["endpoint", "API", "component", "function", "class", "implementation"]
    action: "classify_for_synthesis"
    target: "04_SPECIFICATIONS/"
    stage: 2
    
  - pattern: ["chose X over Y", "decided to", "instead of", "trade-off"]
    action: "classify_as_decision"
    target: "05_DECISIONS/active/"
    stage: 2
    
  - pattern: ["setup", "install", "configure", "deploy", "how to"]
    action: "classify_for_synthesis"
    target: "06_IMPLEMENTATION/"
    stage: 2
    
  - pattern: ["monitoring", "alert", "incident", "outage", "maintenance"]
    action: "classify_for_synthesis"
    target: "07_OPERATIONS/"
    stage: 2
    
  - pattern: ["not sure", "need to research", "question", "unknown", "TBD"]
    action: "classify_as_question"
    target: "08_DIALOGUE/open_questions/"
    stage: 2
```

---

## State Transition Rules

```yaml
transitions:
  embryonic_to_proposed:
    trigger: "pipeline_stage_3_synthesis"
    validation: "has_clear_definition"
    requires: "manual_review"
    
  proposed_to_accepted:
    trigger: "manual_approval_stage_4"
    validation: "no_blocking_questions"
    requires: "human_decision"
    
  proposed_to_rejected:
    trigger: "manual_rejection_stage_4"
    action: "queue_for_archive"
    requires: "human_decision"
    
  accepted_to_implemented:
    trigger: "development_complete_notification"
    validation: "tests_passing"
    requires: "pipeline_update"
    
  implemented_to_validated:
    trigger: "testing_complete_notification"
    validation: "acceptance_criteria_met"
    requires: "pipeline_update"
    
  validated_to_operational:
    trigger: "deployment_notification"
    validation: "monitoring_active"
    requires: "pipeline_update"
    
  any_to_deprecated:
    trigger: "manual_deprecation_decision"
    action: "archive_in_stage_4"
    requires: "human_decision"
```

---

## Synthesis Algorithms

### Deduplication Protocol

```yaml
stage_4_deduplication:
  1. search_existing:
      - exact_match: "document_id"
      - semantic_match: "title AND tags"
      - content_similarity: "threshold:0.7"
  2. if_match_found:
      - merge_strategy: "manual_review"
      - preserve: "accepted_states"
      - update_modified: true
      - append_sources: true
  3. if_no_match:
      - create_new: true
      - generate_id: true
      - establish_links: "minimum:3"
```

### Linking Protocol

```yaml
stage_3b_link_creation:
  - rule: "every_document_minimum_three_links"
    enforcement: "strict"
    stage: "3b"
  - rule: "bidirectional_links_required"
    enforcement: "strict"
    stage: "3b"
  - rule: "cross_layer_linking_encouraged"
    pattern: "feature→spec→decision→research"
    stage: "3b"
  - rule: "circular_dependencies_forbidden"
    enforcement: "strict"
    stage: "3b"
```

---

## Quality Invariants

```yaml
stage_5_validation_invariants:
  no_orphans:
    rule: "every_document_has_at_least_three_links"
    check: "stage_5"
    severity: "error"
    
  no_conflicts:
    rule: "contradictory_decisions_must_be_resolved"
    resolution: "stage_4_manual_review"
    severity: "error"
    
  no_staleness:
    rule: "documents_unchanged_90_days_trigger_review"
    action: "flag_in_validation_report"
    severity: "warning"
    
  no_ambiguity:
    rule: "all_requirements_must_be_testable"
    validation: "specific_acceptance_criteria"
    severity: "warning"
    
  hierarchy_integrity:
    rule: "child_documents_link_to_parent"
    enforcement: "stage_3b_automatic"
    severity: "error"
    
  cross_layer_linking:
    rule: "features_link_specs_link_decisions_link_research"
    enforcement: "stage_3b_validation"
    severity: "warning"
    
  link_density:
    rule: "average_links_per_document"
    minimum: 3.0
    check: "stage_5"
    severity: "warning"
```

---

## Pipeline State Management

```yaml
state_persistence:
  file: "_pipeline/state.yaml"
  format: "yaml"
  updates: "after_each_stage"
  
state_schema:
  current_stage: "integer:1-6"
  last_completed: "integer:0-6"
  status: "enum[ready|processing|awaiting_review|blocked|complete]"
  started: "iso8601"
  last_activity: "iso8601"
  stages:
    "[stage_name]":
      completed: "boolean"
      timestamp: "iso8601"
      metrics: "object"
  artifacts:
    "[stage_name]": "file_path"
  manual_checkpoints:
    "[stage_name]":
      reviewed: "boolean"
      reviewer: "string"
      timestamp: "iso8601"
      notes: "string"
```

---

## Query Response Patterns

```yaml
pipeline_status_queries:
  "current_pipeline_state":
    read: "_pipeline/state.yaml"
    return: "current_stage_and_status"
    
  "validation_results":
    read: "_pipeline/validation_report.json"
    return: "issues_and_metrics"
    
  "pending_review":
    check: "state.status"
    filter: "awaiting_review"
    return: "stage_requiring_attention"
    
  "integration_conflicts":
    read: "stage_4_output"
    filter: "conflicts"
    return: "conflict_list_with_suggestions"

codex_content_queries:
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
```

---

## Success Metrics & Thresholds

```yaml
pipeline_metrics:
  pipeline_completion_rate:
    target: 0.95
    measurement: "successful_runs/total_runs"
    
  average_pipeline_time:
    target: 1800
    measurement: "seconds_stage_1_to_6"
    
  stage_success_rate:
    target: 0.90
    measurement: "per_stage_success/attempts"
    
  manual_intervention_time:
    target: 300
    measurement: "average_seconds_per_checkpoint"

document_metrics:
  extraction_accuracy:
    target: 0.95
    measurement: "correct_units/total_units"
    
  classification_precision:
    target: 0.90
    measurement: "correct_layer/total_classified"
    
  synthesis_quality:
    target: 0.85
    measurement: "validated_docs/total_synthesized"
    
  integration_conflicts:
    target: 0.10
    measurement: "conflicts/total_documents"
    
  validation_pass_rate:
    target: 0.75
    measurement: "checks_passed/total_checks"
    
  link_density:
    target: 3.0
    measurement: "average_bidirectional_links_per_document"
    
  orphan_rate:
    target: 0.00
    measurement: "orphaned_documents/total_documents"
```

---

## Context Injection Protocol

```yaml
for_coding_assistant:
  post_pipeline_context:
    1: include: "_MANIFEST.md"
    2: include: "dependency_graph_for_target"
    3: include: "all_related_decisions"
    4: include: "implementation_conventions"
    5: include: "current_state_registry"
    6: include: "last_validation_report"
    
  bundle_format:
    structure: "hierarchical"
    max_depth: 3
    include_metadata: true
    include_links: true
    include_pipeline_status: true
    format: "markdown_with_yaml_headers"
```

---

## Archival Rules

```yaml
archive_triggers:
  - state: ["rejected", "deprecated", "superseded"]
    action: "move_to_archive"
    stage: 4
    requires: "manual_approval"
    
archive_location:
  pattern: "/_ARCHIVE/{year}/{original_path}"
  
archive_metadata:
  preserve: ["all_links", "all_frontmatter"]
  add:
    - archived_date: "iso8601"
    - archived_reason: "string"
    - pipeline_run_id: "string"
    - superseded_by: "document_id"
```

---

## Error Handling

```yaml
pipeline_error_conditions:
  stage_failure:
    detection: "non_zero_exit_code"
    action: "halt_pipeline_save_state"
    recovery: "manual_intervention_required"
    
  orphaned_document:
    detection: "links < 3"
    action: "flag_in_validation_report"
    stage: 5
    
  circular_dependency:
    detection: "A_depends_on_B_depends_on_A"
    action: "break_cycle_flag_for_review"
    stage: "3b"
    
  conflicting_states:
    detection: "multiple_active_contradictory_decisions"
    action: "halt_stage_4_require_resolution"
    stage: 4
    
  missing_frontmatter:
    detection: "required_field_absent"
    action: "generate_from_defaults_flag_warning"
    stage: 3
    
  validation_threshold_failure:
    detection: "pass_rate < 0.75"
    action: "block_publication_require_fixes"
    stage: 5
    
  context_window_exceeded:
    detection: "tokens > sub_agent_limit"
    action: "chunk_input_or_reduce_scope"
    stage: "any"
```

---

## Standard Evolution Tracking

```yaml
current_version: "1.1-AI-PRISM"
implementation: "PRISM_architecture"
compatibility: "all_1.x_versions_pipeline_compatible"
review_trigger: "after_50_pipeline_runs"
metrics_collection: "pipeline_stage_5"
evolution_path: "pipeline_metrics→bottleneck_analysis→v1.2_amendments"
```