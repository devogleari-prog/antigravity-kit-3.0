---
description: Create new application command. Triggers App Builder skill and uses the 51-Skill ecosystem.
---

# /create - Create Application

$ARGUMENTS

---

## Task

This command starts a new application creation process.

### Steps:

1. **Request Analysis**
   - Understand what the user wants
   - If information is missing, use `doc-coauthoring` or `brainstorming` skill to ask

2. **Project Planning**
   - Use `project-planner` agent with `plan-writing` skill
   - Determine tech stack and file structure
   - Create plan file and obtain user approval

3. **Application Building (After Approval)**
   - Orchestrate with `app-builder` skill
   - Coordinate expert agents using `intelligent-routing`:
     - `database-architect` → Schema
     - `backend-specialist` → API
     - `frontend-specialist` → UI

4. **Preview**
   - Start with `scripts/auto_preview.py` when complete
   - Present URL to user

---

## Usage Examples

```
/create blog site
/create e-commerce app with product listing and cart
/create todo app
/create Instagram clone
/create crm system with customer management
```

---

## Before Starting

If request is unclear, ask these questions:
- What type of application?
- What are the basic features?
- Who will use it?

Use defaults, add details later.
