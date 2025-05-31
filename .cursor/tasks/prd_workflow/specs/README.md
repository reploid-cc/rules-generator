# TDD Specifications Directory

## 🎯 Purpose
Auto-generated TDD specifications for PRD workflow steps based on complexity assessment.

## 🎯 TDD Trigger Conditions
```
TDD.auto_spec_trigger = (
    generate spec_step_x.md if τ.complexity > medium
    ⨁ or if user explicitly requests "TDD"
)

T.complexity = {
    simple: <1h + single_file + no_dependencies,
    medium: 1-4h + multi_file + few_dependencies → TDD_TRIGGER,
    complex: >4h + architecture_changes + many_dependencies → TDD_TRIGGER
}
```

## 🎯 Auto-Generation Rules
- **Step 1**: Medium complexity (30min, guided questioning) → No TDD by default
- **Step 2**: Medium complexity (25min, document enhancement) → No TDD by default  
- **Step 3**: Medium complexity (30min, feature extraction) → No TDD by default
- **Step 4**: Medium complexity (35min, rules generation) → No TDD by default
- **Step 5**: Complex complexity (45min, RFC breakdown) → **TDD AUTO-TRIGGERED**
- **Step 6**: Variable complexity (20min, change management) → TDD if complex changes

## 🎯 Generated File Structure
```
specs/
├── spec_step_5.md              # Auto-generated for RFC complexity
├── spec_step_x.md              # Generated when complexity > medium
└── README.md                   # This file
```

## 🎯 Specification Content
Each spec file includes:
- Test cases inferred from step requirements
- Edge case validation
- Regression test scenarios  
- Quality gate verification tests
- Integration testing requirements

## 🎯 TDD Loop Integration
```
TDD.loop = (
    spec → run → fail → fix → re-run
    ⨁ if pass: Ψ.capture_result, M.sync, Λ.extract
)
```

---
*TDD specifications: complexity-triggered automated test generation* 