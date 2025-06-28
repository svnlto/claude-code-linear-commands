# Quick Issue Generator

Generate a quick Linear issue with minimal input. Perfect for capturing ideas or tasks that need to be fleshed out later.

## Quick Input Format

Just tell me in natural language what you need. For example:
- "FR: Add rate limiting to API endpoints"
- "US: User needs to export data as CSV"
- "Bug: Login fails with special characters in password"
- "Task: Update dependencies to latest versions"

Or provide minimal structure:
```
Type: FR/US/Bug/Task
Title: Brief description
Priority: critical/high/medium/low
Component: auth/api/frontend/backend/infrastructure
Details: Any additional context
```

## What I'll Generate

Based on your input, I'll create a properly formatted issue with:

### For Quick FRs
```markdown
## Overview
$QUICK_DESCRIPTION

## Requirements
- [ ] $EXTRACTED_REQUIREMENT_1
- [ ] $EXTRACTED_REQUIREMENT_2

## Implementation Notes
$ANY_PROVIDED_DETAILS

## Definition of Done
- [ ] Implementation complete
- [ ] Tests added
- [ ] Documentation updated

---
*Note: This is a quick FR that needs further refinement*
```

### For Quick US
```markdown
As a $INFERRED_USER, I want $FEATURE so that $INFERRED_BENEFIT.

## Acceptance Criteria
- [ ] $BASIC_CRITERION_1
- [ ] $BASIC_CRITERION_2

## Technical Notes
$ANY_PROVIDED_DETAILS

---
*Note: This is a quick US that needs further refinement*
```

### For Bugs
```markdown
## Description
$PROBLEM_DESCRIPTION

## Steps to Reproduce
1. $INFERRED_STEP_1
2. $INFERRED_STEP_2

## Expected Behavior
$WHAT_SHOULD_HAPPEN

## Actual Behavior
$WHAT_HAPPENS

## Environment
- Component: $COMPONENT
- Priority: $PRIORITY

---
*Note: This bug report needs verification and additional details*
```

### For Tasks
```markdown
## Description
$TASK_DESCRIPTION

## Action Items
- [ ] $ACTION_1
- [ ] $ACTION_2

## Context
$ANY_PROVIDED_CONTEXT

---
*Note: This task needs proper scoping and acceptance criteria*
```

## Examples

**Input**: "FR: Add caching to product API endpoints for better performance"

**Output**: A formatted FR with basic structure, ready for refinement

**Input**: "Bug: Users can't upload images larger than 5MB"

**Output**: A bug report with reproduction steps and environment details

Just give me your quick description and I'll create a properly formatted issue!
