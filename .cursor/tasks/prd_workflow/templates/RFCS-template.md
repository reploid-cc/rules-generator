# RFCS Template - Sequential Implementation Roadmap

## Purpose
Template for organizing RFC implementation in sequential order. Used by AI when generating step 5 outputs.

## Structure Template
```
RFCs/
├── RFC-001-[foundation].md
├── RFC-002-[data].md  
├── RFC-003-[api].md
├── RFC-004-[security].md
├── RFC-005-[ui].md
├── RFC-006-[integration].md
└── implementation-prompts/
    ├── implementation-prompt-RFC-001.md
    ├── implementation-prompt-RFC-002.md
    ├── implementation-prompt-RFC-003.md
    ├── implementation-prompt-RFC-004.md
    ├── implementation-prompt-RFC-005.md
    └── implementation-prompt-RFC-006.md
```

## Implementation Order Rules
1. **Sequential only**: RFC-002 cannot start until RFC-001 complete
2. **Dependency validation**: Each RFC validates prerequisites met
3. **Quality gates**: Pass validation before next RFC
4. **Rollback ready**: Each RFC includes rollback procedures

## Complexity Assessment
```
Phase 1 (Foundation): RFC-001, RFC-002 = 2-3 weeks
Phase 2 (Core Services): RFC-003, RFC-004 = 3-4 weeks  
Phase 3 (User Experience): RFC-005, RFC-006 = 2-3 weeks
```

---
*Template for AI reference - not actual workflow output* 