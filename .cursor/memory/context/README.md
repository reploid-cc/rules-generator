# Context Directory - Rules Generator

## 🎯 Purpose

The `context` directory is a key component of the memory system, designed to store session-independent context that persists across AI interactions. This directory maintains critical contextual information that enables continuity and knowledge preservation throughout the development process.

## 🎯 Contents

This directory contains the following types of contextual information:

### Session Context
- Environment and project state snapshots
- Current development focus and priorities
- Active tasks and their progress
- Recent decisions and their rationale

### Cross-Session Knowledge
- Information that should persist between AI sessions
- Long-term project insights and observations
- Accumulated knowledge about the codebase
- Understanding that evolves across multiple interactions

### Constraints and Insights
- Project-specific constraints and requirements
- Technical limitations and workarounds
- Performance considerations
- Architectural boundaries and design constraints

### Edge Cases
- Documented exceptions to standard patterns
- Unusual scenarios that require special handling
- Potential problem areas and their mitigation
- Boundary conditions that deserve attention

## 🎯 Usage

The context files in this directory are:
- Automatically updated by the M.sync mechanism
- Referenced during task initialization via M.retrieval
- Preserved across AI resets and new sessions
- Used to maintain continuity in complex development

## 🎯 File Format

Context files typically follow this structure:
```
# Context: {Topic}

## Overview
Brief description of this context area

## Current State
The current status and understanding

## History
Evolution of understanding over time

## Related Contexts
Links to related context files
```

## 🎯 Integration

This directory integrates with:
- **M Memory System**: For context preservation and retrieval
- **Ψ Cognitive Trace**: For reasoning path documentation
- **T Task System**: For task-specific context
- **Φ Hypothesis Engine**: For hypothesis testing against context

---

*M.context_artifacts = session context preservation, cross-session knowledge transfer* 