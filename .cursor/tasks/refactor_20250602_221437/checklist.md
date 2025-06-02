# Refactor Execution Checklist

## 🚀 Phase 1: Core Consolidation (Low Risk)

### Pre-Phase 1 Setup
- [ ] **Git Backup**: Create commit before Phase 1
- [ ] **User Confirmation**: Get approval to start Phase 1
- [ ] **Baseline Measurement**: Record current line counts

### 1.1 Extract Common Mathematical Notation
- [ ] **Analyze Notation Patterns**: Scan all .mdc files for repeated mathematical notation
- [ ] **Create Shared Definitions**: Create `000-notation-definitions.mdc`
- [ ] **Standardize Symbols**: Define consistent symbol usage
- [ ] **Update Cross-References**: Replace duplicates with references
- [ ] **Validation**: Verify all references work correctly
- [ ] **User Approval**: Get confirmation before proceeding

### 1.2 Merge Similar Concepts
- [ ] **Identify Overlapping Concepts**: Find duplicate/similar concepts across files
- [ ] **Plan Consolidation**: Decide which file should contain each concept
- [ ] **Merge Related Rules**: Combine similar rules into single definitions
- [ ] **Update Cross-References**: Fix all internal links
- [ ] **Validation**: Test all merged concepts work correctly
- [ ] **User Approval**: Get confirmation before proceeding

### 1.3 Create Reference System
- [ ] **Design Reference Format**: Define symbolic link format
- [ ] **Implement Cross-References**: Replace prose with symbolic references
- [ ] **Create Reference Index**: Build master reference guide
- [ ] **Update All Files**: Apply reference system consistently
- [ ] **Validation**: Verify all references resolve correctly
- [ ] **User Approval**: Get confirmation before proceeding

### Phase 1 Completion
- [ ] **Measure Reduction**: Calculate line count reduction
- [ ] **Functionality Test**: Verify all rules still work
- [ ] **Git Commit**: Save Phase 1 progress
- [ ] **User Review**: Get approval for Phase 1 completion

---

## 🔧 Phase 2: Content Compression (Medium Risk)

### Pre-Phase 2 Setup
- [ ] **Git Backup**: Create commit before Phase 2
- [ ] **User Confirmation**: Get approval to start Phase 2
- [ ] **Target File Analysis**: Focus on large files (101, 161, 881, 851)

### 2.1 Convert Prose to Mathematical Notation
- [ ] **File: 101-mandatory-protocols.mdc**
  - [ ] Convert verbose explanations to mathematical notation
  - [ ] Replace prose with symbolic operators
  - [ ] Implement concise notation system
  - [ ] Validation and user approval
- [ ] **File: 161-refactor-workflow.mdc**
  - [ ] Convert workflow descriptions to mathematical notation
  - [ ] Use symbolic representation for processes
  - [ ] Compress step descriptions
  - [ ] Validation and user approval
- [ ] **File: 881-prd-workflow-system.mdc**
  - [ ] Convert workflow prose to notation
  - [ ] Implement symbolic process representation
  - [ ] Compress verbose sections
  - [ ] Validation and user approval
- [ ] **File: 851-xi-diagnostics.mdc**
  - [ ] Convert diagnostic prose to mathematical notation
  - [ ] Use symbolic error representation
  - [ ] Compress explanation sections
  - [ ] Validation and user approval

### 2.2 Remove Redundant Examples
- [ ] **Identify Redundant Examples**: Find duplicate/similar examples
- [ ] **Create Shared Example Library**: Central example repository
- [ ] **Replace with References**: Use references instead of full examples
- [ ] **Keep Essential Examples Only**: Remove non-critical examples
- [ ] **Validation**: Verify examples still illustrate concepts
- [ ] **User Approval**: Get confirmation before proceeding

### 2.3 Compress Verbose Explanations
- [ ] **Extract Core Meaning**: Identify essential information only
- [ ] **Convert to Bullet Points**: Replace paragraphs with concise points
- [ ] **Implement Hierarchical Structure**: Use nested organization
- [ ] **Remove Redundant Words**: Eliminate unnecessary prose
- [ ] **Validation**: Verify meaning preserved
- [ ] **User Approval**: Get confirmation before proceeding

### Phase 2 Completion
- [ ] **Measure Reduction**: Calculate line count reduction
- [ ] **Functionality Test**: Verify all rules still work
- [ ] **Git Commit**: Save Phase 2 progress
- [ ] **User Review**: Get approval for Phase 2 completion

---

## ⚡ Phase 3: Structure Optimization (Higher Risk)

### Pre-Phase 3 Setup
- [ ] **Git Backup**: Create commit before Phase 3
- [ ] **User Confirmation**: Get approval to start Phase 3
- [ ] **Structure Analysis**: Plan file splitting and organization

### 3.1 Split Large Files
- [ ] **Analyze File Structure**: Identify logical split points
- [ ] **Plan Module Organization**: Design new file structure
- [ ] **Split Large Files**: Break down 200+ line files
  - [ ] Split `101-mandatory-protocols.mdc` if still large
  - [ ] Split `161-refactor-workflow.mdc` if still large
  - [ ] Split other large files as needed
- [ ] **Maintain Cross-References**: Ensure all links work
- [ ] **Validation**: Test all split modules work correctly
- [ ] **User Approval**: Get confirmation before proceeding

### 3.2 Create Hierarchical Reference System
- [ ] **Design Hierarchy**: Plan parent-child relationships
- [ ] **Implement Inheritance**: Use symbolic inheritance patterns
- [ ] **Reduce Duplication**: Eliminate redundancy through hierarchy
- [ ] **Update All References**: Fix hierarchical links
- [ ] **Validation**: Verify hierarchy works correctly
- [ ] **User Approval**: Get confirmation before proceeding

### 3.3 Implement Symbolic Notation System
- [ ] **Create Symbol Dictionary**: Define all symbols used
- [ ] **Implement Mathematical Shorthand**: Use concise notation
- [ ] **Optimize for AI Parsing**: Ensure AI-friendly format
- [ ] **Update All Files**: Apply symbolic notation consistently
- [ ] **Validation**: Test AI parsing efficiency
- [ ] **User Approval**: Get confirmation before proceeding

### Phase 3 Completion
- [ ] **Measure Final Reduction**: Calculate total line count reduction
- [ ] **Comprehensive Testing**: Full system functionality test
- [ ] **Git Commit**: Save Phase 3 progress
- [ ] **User Review**: Get approval for Phase 3 completion

---

## 🎯 Final Validation & Cleanup

### Final Testing
- [ ] **Complete Functionality Test**: Verify all User Rules work
- [ ] **Cross-Reference Validation**: Check all links resolve
- [ ] **Mathematical Notation Accuracy**: Verify notation correctness
- [ ] **AI-Facing Format Compliance**: Test AI parsing
- [ ] **Performance Measurement**: Measure context reduction achieved

### Success Criteria Verification
- [ ] Context size reduced by 40-50%
- [ ] All User Rules functionality preserved
- [ ] Mathematical notation standardized
- [ ] Cross-references working correctly
- [ ] AI-facing format optimized
- [ ] Zero breaking changes introduced

### Final Cleanup
- [ ] **Archive Refactor Assets**: Move to completed folder
- [ ] **Update Documentation**: Reflect new structure
- [ ] **Final Git Commit**: Save completed refactor
- [ ] **User Final Approval**: Get confirmation for asset cleanup

---

## 🔴 Emergency Procedures

### If Issues Detected
1. **STOP IMMEDIATELY**
2. **Analyze Issue**: Identify root cause
3. **Propose Solutions**: Present options to user
4. **Execute Rollback**: If user requests
5. **Document Error**: Log in Ξ.error_memory
6. **Learn from Failure**: Update process for future

### Rollback Procedure
1. **Identify Last Good State**: Find last working commit
2. **Git Reset**: Revert to last good state
3. **Verify Functionality**: Test all rules work
4. **Document Rollback**: Record what was reverted
5. **Analyze Failure**: Understand what went wrong

---

*Checklist Created: 2025-06-02 22:14:37*
*Status: Ready for execution* 