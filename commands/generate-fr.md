# Generate Feature Request (FR) for Linear

Generate a comprehensive Feature Request issue following our established FR pattern. I'll help you create a well-structured FR with all necessary sections.

## Information I Need

Please provide the following details:

1. **Title**: Brief descriptive title for the feature
2. **Component**: Which component? (auth/api/frontend/backend/scraping/infrastructure)
3. **Current Problem**: What's wrong or missing currently?
4. **Proposed Solution**: High-level approach to solve it
5. **Technical Details**: Any specific implementation requirements or constraints
6. **Priority**: How urgent? (critical/high/medium/low)
7. **Effort**: Estimated size (small/medium/large/xl)
8. **Dependencies**: Any blocking issues or related work?

## Template I'll Use

```markdown
## Overview

$HIGH_LEVEL_DESCRIPTION

## Strategic Context

**Current Gap**: $CURRENT_PROBLEM
**Business Value**: $BUSINESS_VALUE
**Technical Need**: $TECHNICAL_JUSTIFICATION

## Technical Requirements

### Phase 1: $PHASE_NAME ($TIME_ESTIMATE)

- [ ] **$REQUIREMENT_1**
  * $DETAIL_1
  * $DETAIL_2
  ```$LANGUAGE
  // Example implementation
  $CODE_EXAMPLE
  ```

- [ ] **$REQUIREMENT_2**
  * $DETAIL_1

### Phase 2: $PHASE_NAME ($TIME_ESTIMATE)

- [ ] **$REQUIREMENT_3**
- [ ] **$REQUIREMENT_4**

## Implementation Plan

### $IMPLEMENTATION_STEP_1

$DETAILED_INSTRUCTIONS

### $IMPLEMENTATION_STEP_2

$DETAILED_INSTRUCTIONS

## Acceptance Criteria

- [ ] $SPECIFIC_MEASURABLE_CRITERION_1
- [ ] $SPECIFIC_MEASURABLE_CRITERION_2
- [ ] $TESTING_REQUIREMENT
- [ ] $DOCUMENTATION_REQUIREMENT

## Dependencies

* **Blocked by**: $BLOCKING_ISSUES
* **Blocks**: $DEPENDENT_ISSUES
* **Related**: $RELATED_ISSUES

## Technical Implementation Details

### $TECHNICAL_COMPONENT_1

```$LANGUAGE
// Implementation example
$CODE_EXAMPLE
```

### $TECHNICAL_COMPONENT_2

$TECHNICAL_SPECIFICATIONS

## Security Considerations

* $SECURITY_REQUIREMENT_1
* $SECURITY_REQUIREMENT_2

## Performance Considerations

* $PERFORMANCE_REQUIREMENT_1
* $PERFORMANCE_REQUIREMENT_2

## Definition of Done

- [ ] Implementation complete and tested
- [ ] Unit tests written and passing
- [ ] Integration tests completed
- [ ] Documentation updated
- [ ] Code reviewed and approved
- [ ] Deployed to staging environment
- [ ] Production deployment validated
```

## What I'll Do

Based on your input, I will:

1. Format the title as `[FR] {Component} {Feature/Action}`
2. Break down requirements into logical phases with time estimates
3. Include relevant code examples in TypeScript/JavaScript
4. Add appropriate labels: `effort:$SIZE`, `type:feature` or `type:technical-debt`, `component:$COMPONENT`, `priority:$PRIORITY`
5. Create clear acceptance criteria and definition of done
6. Consider security and performance implications
7. Structure the implementation plan with concrete steps

Please provide the information above, and I'll generate a complete FR ready for Linear!
