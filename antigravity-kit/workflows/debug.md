---
description: Debugging command. Activates DEBUG mode with 4-phase systematic-debugging methodology.
---

# /debug - Systematic Problem Investigation

$ARGUMENTS

---

## Purpose

Activate DEBUG mode using the `systematic-debugging` methodology: 4-phase investigation with root cause analysis and evidence-based verification.

---

## Behavior

When `/debug` is triggered, follow the **4-Phase Systematic Debugging Methodology**:

1. **Phase 1: Observation & Evidence** (Gather symptoms, logs, context)
2. **Phase 2: Hypothesis Generation** (Identify potential root causes)
3. **Phase 3: Experimentation** (Test hypotheses with evidence)
4. **Phase 4: Synthesis & Prevention** (Apply fix, root cause report, future prevention)

---

## Output Format

```markdown
## 🔍 Debug: [Issue]

### 1. Symptom
[What's happening]

### 2. Information Gathered
- Error: `[error message]`
- File: `[filepath]`
- Line: [line number]

### 3. Hypotheses
1. ❓ [Most likely cause]
2. ❓ [Second possibility]
3. ❓ [Less likely cause]

### 4. Investigation

**Testing hypothesis 1:**
[What I checked] → [Result]

**Testing hypothesis 2:**
[What I checked] → [Result]

### 5. Root Cause
🎯 **[Explanation of why this happened]**

### 6. Fix
```[language]
// Before
[broken code]

// After
[fixed code]
```

### 7. Prevention
🛡️ [How to prevent this in the future]
```

---

## Examples

```
/debug login not working
/debug API returns 500
/debug form doesn't submit
/debug data not saving
```

---

## Key Principles

- **Ask before assuming** - get full error context
- **Test hypotheses** - don't guess randomly
- **Explain why** - not just what to fix
- **Prevent recurrence** - add tests, validation
