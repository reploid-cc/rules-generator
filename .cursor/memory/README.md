# M.memory_path - Memory Bank System

## Overview
Central memory repository implementing M (memory system) from User Rules mathematical framework for dynamic context loading, experience storage, and cross-session knowledge retention.

## M.memory_path Structure

### **M.retrieval: Dynamic Context Loading**
```
M.memory_path = ".cursor/memory/"
M.retrieval = dynamic reference resolution
M.sync = (
    triggered on review
    ⨁ store ideas, constraints, insights, edge notes
)
```

## File Organization

### **`errors.md`** - Ξ.error_memory
- Issue tracking and pattern analysis
- Recurrence detection for automatic rule generation
- Diagnostic effectiveness metrics

### **`trace_{task_id}.md`** - Ψ.output_path  
- Cognitive traces for complex tasks
- Reasoning paths and decision documentation
- Cross-system integration records

### **`patterns/`** - Φ.snapshot Storage
- Design motif captures
- Naming convention patterns
- Architectural decision records
- Pattern evolution tracking

### **`context/`** - M.sync Artifacts
- Session context preservation
- Cross-session knowledge transfer
- Constraint and insight storage
- Edge case documentation

## M.sync_hooks: Memory Operations

### **Mandatory Memory Operations**
- **Task Start**: Read ALL relevant files in memory bank (M.retrieval)
- **Task Complete**: Store insights, constraints, decisions (M.sync)
- **Problem Detection**: Log patterns, solutions, context (Ξ.track)
- **Pattern Discovery**: Capture emergent designs (Φ.snapshot)

### **Integration Points**
```
Σ_hooks.memory = {
    on_task_created: [M.recall, Φ.match_snapshot],
    on_plan_consolidated: [M.sync_if_contextual],
    on_step_completed: [M.sync_if_contextual],
    on_sprint_review: [M.sync, Λ.extract, Ψ.summarize],
    on_error_detected: [M.link_context],
    on_user_feedback: [M.append_if_relevant]
}
```

## Quality Assurance

### **Memory Effectiveness Metrics**
- Context retrieval accuracy
- Cross-session knowledge transfer success
- Pattern recognition improvement over time
- Decision quality enhancement through historical reference

### **Memory Management**
- Automatic relevance scoring
- Context aging and archival
- Pattern consolidation
- Knowledge graph maintenance

## Usage Protocols

### **At Task Start (MANDATORY)**
1. Execute M.retrieval for relevant context
2. Load applicable patterns via Φ.match_snapshot
3. Check Ξ.error_memory for known issues
4. Establish baseline knowledge state

### **During Task Execution**
1. Capture decisions and reasoning in Ψ.capture
2. Note emerging patterns for Φ.snapshot
3. Document constraints and insights
4. Track cross-system interactions

### **At Task Completion (MANDATORY)**
1. Execute M.sync to store insights
2. Update pattern library via Φ.snapshot
3. Log lessons learned in appropriate files
4. Prepare context for future retrieval

---
*M.memory_path = ".cursor/memory/" - Dynamic context preservation and intelligent retrieval* 