# Generate User Story (US) for Linear

Generate a comprehensive User Story issue following our established US pattern. I'll help you create a user-focused story with clear acceptance criteria.

## Information I Need

Please provide the following details:

1. **User Type**: Who is the primary user? (e.g., shopper, developer, admin)
2. **Feature Need**: What do they want to do?
3. **Value/Benefit**: Why do they need this? What value does it provide?
4. **Title**: Brief action-oriented title
5. **Component**: Which component? (auth/api/frontend/backend/etc)
6. **Acceptance Criteria**: What must be true for this to be complete? (3-5 items)
7. **Success Metrics**: How will we measure success?
8. **Priority**: How urgent? (critical/high/medium/low)
9. **Effort**: Estimated size (small/medium/large/xl)
10. **Dependencies**: Any blocking issues?

## Template I'll Use

```markdown
# User Story

As a $USER_TYPE, I want $FEATURE so that $BENEFIT.

## ⚠️ Dependencies

**Blocked by**: $BLOCKING_ISSUES
**Blocks**: $DEPENDENT_ISSUES

## Persona

🎯 **$PRIMARY_PERSONA** + **$SECONDARY_PERSONAS**

## Acceptance Criteria

- [ ] $USER_FACING_CRITERION_1
- [ ] $USER_FACING_CRITERION_2
- [ ] $USER_FACING_CRITERION_3
- [ ] $TECHNICAL_CRITERION
- [ ] $QUALITY_CRITERION

## Technical Implementation

* **$COMPONENT_1**: $TECHNICAL_APPROACH
* **$COMPONENT_2**: $TECHNICAL_APPROACH
* **$COMPONENT_3**: $TECHNICAL_APPROACH

## $FEATURE_SPECIFIC_SECTION

### $TIER_OR_OPTION_1

* $SPECIFICATION_1
* $SPECIFICATION_2
* $LIMIT_OR_CONSTRAINT

### $TIER_OR_OPTION_2

* $SPECIFICATION_1
* $SPECIFICATION_2
* $LIMIT_OR_CONSTRAINT

## Success Metrics

* **$METRIC_1**: $TARGET_VALUE
* **$METRIC_2**: $TARGET_VALUE
* **$METRIC_3**: $TARGET_VALUE

## Definition of Done

- [ ] Feature implemented per acceptance criteria
- [ ] All tests passing (unit, integration, E2E)
- [ ] Responsive design verified
- [ ] Accessibility requirements met
- [ ] Performance benchmarks achieved
- [ ] Documentation updated
- [ ] Product owner approval received

## Implementation Notes

* $IMPORTANT_IMPLEMENTATION_DETAIL_1
* $IMPORTANT_IMPLEMENTATION_DETAIL_2
* $POTENTIAL_GOTCHA_OR_CONSIDERATION
```

## What I'll Do

Based on your input, I will:

1. Format the title as `[US] {User Action} for {Benefit}`
2. Write a clear user story in the "As a... I want... So that..." format
3. Define specific, measurable acceptance criteria
4. Include relevant technical implementation details
5. Add appropriate labels: `effort:$SIZE`, `type:feature`, `component:$COMPONENT`, `priority:$PRIORITY`
6. Create success metrics that align with business goals
7. Consider edge cases and implementation notes

Please provide the information above, and I'll generate a complete US ready for Linear!
