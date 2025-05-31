# .cursor System - User Rules Compliant Architecture

## 🎯 System Overview

Complete .cursor system implementing User Rules standards (Ω*, Ψ, M, T, Λ, Φ, Ξ) with integrated PRD-to-RFC workflow for product development management.

```
Ω* = max(∇ΣΩ) ⟶ intent-aligned reasoning
T = Σ(τ_complex) ⇌ structured task system  
PRD.workflow = T.sprint integration
```

## 🎯 Core Architecture

### Mathematical Framework
- **Ω**: Core reasoning modes (deductive, analogical, exploratory, procedural, contrastive, skeptical)
- **Ψ**: Cognitive trace & mandatory dialogue system 
- **M**: File-based memory system (.cursor/memory/)
- **T**: Structured task system (.cursor/tasks/)
- **Λ**: Rule-based self-learning (.cursor/rules/)
- **Φ**: Hypothesis abstraction engine
- **Ξ**: Diagnostics & refinement system

### PRD Workflow Integration
```
T.prd_workflow = 6-step_sequential_process {
    step_1: Interactive PRD Creation,
    step_2: PRD Comprehensive Verification,
    step_3: Features Extraction & Prioritization, 
    step_4: Technical Rules Generation,
    step_5: RFCs Generation & Implementation Planning,
    step_6: PRD Change Management
}
```

## 🎯 Directory Structure

```
.cursor/
├── README.md                      # This file
├── rules/                         # Λ.path - Self-learning rules
│   ├── 001-core-standards.mdc     # Ω* core reasoning framework
│   ├── 101-mandatory-protocols.mdc # Ψ.dialog + M.memory protocols  
│   ├── 131-tdd-spec-engine.mdc    # TDD integration with complexity triggers
│   ├── 801-task-system.mdc        # T task management system
│   ├── 821-lambda-learning.mdc    # Λ rule-based self-learning
│   ├── 841-phi-hypothesis.mdc     # Φ hypothesis abstraction
│   ├── 851-xi-diagnostics.mdc     # Ξ diagnostics & refinement
│   └── 881-prd-workflow-system.mdc # PRD workflow T integration
├── memory/                        # M.memory_path - File-based memory
│   ├── README.md                  # Memory system documentation
│   └── errors.md                  # Ξ.error_memory for pattern tracking
├── tasks/                         # T.plan_path - Structured tasks
│   └── prd_workflow/              # PRD-to-RFC workflow implementation
│       ├── step_1.md              # Interactive PRD Creation
│       ├── step_2.md              # PRD Comprehensive Verification  
│       ├── step_3.md              # Features Extraction & Prioritization
│       ├── step_4.md              # Technical Rules Generation
│       ├── step_5.md              # RFCs Generation & Implementation Planning
│       ├── step_6.md              # PRD Change Management
│       ├── README.md              # Workflow documentation
│       ├── templates/             # Template files for RFC generation
│       │   ├── RFCS-template.md   # RFCS master file template
│       │   └── implementation-prompt-template.md # Implementation template
│       ├── outputs/               # Generated workflow outputs
│       │   └── README.md          # Output documentation
│       ├── progress/              # T.progress tracking
│       │   └── current-step.json  # Current workflow state
│       └── specs/                 # TDD specifications (auto-generated)
```

## 🎯 Key Features

### 1. User Rules Compliance
- **People-facing content**: Clear, friendly prompts without mathematical notation
- **AI-facing content**: Optimized with mathematical notation and validation gates
- **Separation of concerns**: Clean distinction between user prompts and system logic

### 2. TDD Integration
```
TDD.trigger_conditions = (
    if τ.complexity >= medium (1-4h effort)
    ⨁ or τ.dependencies_count > 2
    ⨁ or τ.integration_points > 1
    → generate TDD.spec_path
)
```

### 3. Sequential Implementation
- **RFC Generation**: Strict numerical order (001, 002, 003...)
- **Dependency Management**: Each RFC builds on previous completions
- **No Parallel Implementation**: One RFC at a time for controlled development

### 4. Quality Gates
```
T.validation_gates = (
    completeness_check + stakeholder_review + technical_feasibility
    ⨁ dependency_analysis + implementation_readiness
)
```

### 5. Mandatory Protocols
- **Ψ.dialog_enabled**: Every response must end with interactive feedback call
- **M.memory_path**: Dynamic context loading and sync operations
- **Environment.protocol**: Never modify .env without permission

## 🎯 Workflow Commands

### PRD Workflow Activation
```
"init PRD" → T.create_prd_workflow_from_scratch
"init PRD to RFC" → T.execute_complete_prd_to_rfc_sequence  
"init PRD step [1-6]" → T.jump_to_specific_prd_step
"init PRD - [changes]" → T.handle_prd_change_management
```

### Progress Tracking
```json
{
  "current_step": 0,
  "workflow_status": "not_started",
  "step_outputs": {
    "step_1": {"status": "pending", "output_file": "outputs/PRD.md"},
    "step_5": {"output_file": "outputs/RFCs/ + outputs/RFCS.md + outputs/RFC-xxx.md + outputs/implementation-prompts/"}
  }
}
```

## 🎯 Integration Hooks

### System-wide Event Hooks
```
Σ_hooks = {
    on_task_created: [M.recall, Φ.match_snapshot],
    on_step_completed: [T.update_progress, M.sync_if_contextual],
    on_sprint_review: [M.sync, Λ.extract, Ψ.summarize],
    on_error_detected: [Ξ.track, Λ.suggest],
    on_user_feedback: [Ψ.dialog, M.append_if_relevant]
}
```

## 🎯 Quality Assurance

### Rule-Based Learning
- **Λ.autonomy**: Auto-detect rule-worthy recurrences
- **Λ.pattern_alignment**: Align code with best practices  
- **Ξ.pattern_suggestion**: Generate rule drafts for recurring issues

### Diagnostics & Refinement
- **Ξ.cleanup_phase**: Detect code drift and suggest improvements
- **Ξ.error_memory**: Track recurring issues for pattern learning
- **Ξ.recurrence_threshold**: Generate rules after 2+ occurrences

## 🎯 System Philosophy

### Core Principles
1. **Intent-aligned reasoning**: Ω* framework for systematic problem solving
2. **Mandatory interaction**: Zero tolerance for responses without Ψ.dialog
3. **Memory-driven context**: M.retrieval for dynamic reference resolution
4. **Structured execution**: T.sprint system for complex task management
5. **Continuous learning**: Λ.extract patterns for rule improvement
6. **Quality-first**: TDD integration and validation gates

### Execution Standards
- **Vietnamese responses**: All communication in Vietnamese
- **Transparency**: Report every action step clearly
- **Execution-first**: Act immediately, only pause for completion or blocking issues
- **Quality gates**: Validation at every major step
- **Documentation**: Clear, actionable content with examples

---
*Complete .cursor system: Ω* reasoning + T.prd_workflow + User Rules compliance* 