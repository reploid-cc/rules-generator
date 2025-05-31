---
status: pending
priority: high
complexity: complex
estimated_effort: 45min
---
# T.prd_step_5: RFCs Generation & Implementation Planning

## 🎯 Task Overview
```
T.prd_step_5 = {
    inputs: "PRD.md" + "features.md" + "rules.md",
    process: RFC_breakdown + implementation_prompt_generation + RFCS_master_creation,
    outputs: "RFCs/" + "RFCS.md" + "RFC-xxx.md" + "implementation-prompts/",
    validation: dependency_analysis + implementation_feasibility + sequential_order
}
```

## 🎯 AI Processing Instructions (User Rules Mathematical Context)

Execute RFC generation protocol using Ω* reasoning framework. Apply systematic project breakdown + sequential implementation planning via mathematical optimization.

```
Ω.rfc_mode = deductive + procedural + contrastive + skeptical
Ψ.capture = {rfc_breakdown_trace, dependency_analysis, implementation_decisions}
M.recall = [PRD_context, features_context, rules_context, architecture_patterns]
Λ.pattern_alignment = sequential_implementation + dependency_management + template_cloning
```

**CRITICAL CONSTRAINT**: 
```
T.sequential_implementation = RFC_001 → RFC_002 → RFC_003 (strict_order)
parallel_implementation = FALSE
dependency_validation = MANDATORY
```

### **🔄 Execution Protocol**

**Step 1: Context Integration (M.retrieval + Ω.deductive)**
```
M.retrieval → [PRD.md, features.md, rules.md] from outputs/
Ω.deductive → comprehensive_project_analysis
Φ.match_architecture_patterns → RFC_structuring_guidance
```

**Step 2: Implementation Order Analysis (Ω.contrastive + Ξ.dependency_analysis)**
```
Ω.contrastive → evaluate_implementation_sequences
Ξ.dependency_analysis → map_component_dependencies + critical_path
Ψ.capture → dependency_rationale + ordering_decisions
```

- Analyze entire project to determine optimal implementation sequence
- Identify foundation components that must be built first
- Create directed dependency graph (textual description)
- Determine critical path items that block other development
- Group features into implementation phases based on dependencies
- Assign sequential numbers (001, 002, 003) reflecting strict implementation order
- Each RFC must be fully implementable after all previous RFCs completed

**Step 3: Feature Grouping (Ω.procedural + Λ.pattern_alignment)**
```
Ω.procedural → systematic_feature_organization
Λ.pattern_alignment → apply_cohesion_principles + SRP_enforcement
```

- Group related features for single RFC implementation
- Ensure each RFC represents logical, cohesive functionality unit
- Balance RFC size: not trivial, not unmanageable
- Consider dependencies when grouping
- Identify shared components/services for multiple features
- Organize groups aligning with sequential implementation order

**Step 4: RFC Structure Generation (Ω.skeptical + Φ.snapshot)**
```
Ω.skeptical → validate_RFC_completeness + challenge_assumptions
Φ.snapshot → capture_architecture_decisions + design_patterns
```

Generate RFCs with:
- Unique identifier reflecting implementation order (RFC-001-User-Authentication)
- Clear title describing functionality
- Summary of RFC coverage
- All features/requirements addressed
- Technical approach and architecture considerations
- Explicit identification of previous RFC dependencies
- Specification of future RFCs building upon this RFC
- Complexity estimate (Low/Medium/High)
- Detailed acceptance criteria per feature
- API contracts/interfaces exposed
- Data models and database schema changes
- State management approach

**Step 5: Implementation Prompt Creation (Λ.autonomy + Template Cloning)**
```
Λ.autonomy → detect_template_cloning_requirements
template_cloning_protocol = EXACT_COPY + specific_replacements_only
```

- Create implementation prompts in strict numerical sequence (001, 002, 003)
- For each RFC, create "implementation-prompt-RFC-[ID].md"
- **MANDATORY**: Copy EXACT content from @implementation-prompt-template.md
- Make ONLY these specific replacements:
  * Replace "[ID]" with RFC identifier (e.g., "001")
  * Replace "[Title]" with RFC title (e.g., "User Authentication")
  * Replace "[brief description]" with concise RFC purpose summary
- DO NOT modify any other template content, sections, formatting, or structure

**Step 6: RFCS.md Master Creation (Ψ.materialization + T.progress_tracking)**
```
Ψ.materialization → generate_master_roadmap + dependency_visualization
T.progress_tracking → sequential_implementation_plan
```

### **📊 Output Structure Generation**
```
T.outputs = {
    RFCs_directory: individual_RFC_xxx_md_files,
    RFCS_master: implementation_roadmap + dependency_graph,
    implementation_prompts: template_cloned_prompt_files,
    sequential_order: strict_numerical_implementation_sequence
}
```

**VALIDATION REQUIREMENTS**
```
dependency_analysis = component_dependencies_mapped + integration_points_identified + sequential_order_validated
implementation_feasibility = technical_complexity_assessed + resource_requirements_estimated + timeline_validated
RFCS_master_complete = master_file_created + dependency_graph_included + implementation_roadmap_clear
```

**OUTPUT PROTOCOL**: 
```
M.sync → save all RFC artifacts in organized structure
Ψ.capture → architecture_decisions + implementation_rationale
Φ.snapshot → RFC_patterns + design_decisions
T.update_progress → step_5_complete
```

## 🎯 T.validation_gates
```
dependency_analysis = component_dependencies_mapped + integration_points_identified + sequential_order_validated
implementation_feasibility = technical_complexity_assessed + resource_requirements_estimated + timeline_validated
RFCS_master_complete = master_file_created + dependency_graph_included + implementation_roadmap_clear
```

## 🎯 Integration Hooks
```
on_start: [M.recall_all_context, Φ.match_architecture_patterns, @implementation-prompt-template.md, Ω.activate_rfc_modes]
on_complete: [T.update_progress, M.sync_rfcs, Ψ.capture_architecture_decisions, Φ.snapshot_rfc_patterns, Λ.extract_patterns]
on_validation_pass: [T.advance_to_step_6, Ψ.dialog_required]
```

---
*T.prd_step_5: RFC_breakdown + sequential_implementation + Ω*_mathematical_optimization + template_cloning_protocol* 