# Analyze Linear Issue

Analyze an existing Linear issue and suggest improvements based on our established patterns and best practices.

## What I Need

Please provide:
1. The Linear issue content (paste the full issue text)
2. The issue type (FR/US/PRD)
3. Any specific concerns or areas you'd like me to focus on

## What I'll Analyze

I will review the issue for:

### Structure & Format
- Proper title format with [FR], [US], or [PRD] prefix
- Appropriate sections for the issue type
- Clear hierarchy and organization
- Use of checkboxes for trackable items

### Content Quality
- **Clarity**: Is the problem/need clearly stated?
- **Completeness**: Are all necessary sections included?
- **Specificity**: Are requirements specific and measurable?
- **Context**: Is there sufficient business and technical context?

### Technical Details
- Code examples where appropriate
- Technical implementation details
- Architecture considerations
- Performance and security implications

### Requirements & Criteria
- Clear acceptance criteria
- Comprehensive Definition of Done
- Proper dependency tracking
- Appropriate effort and priority labels

### Best Practices
- User story format (for US)
- Phased approach (for FR)
- Success metrics (for PRD)
- Risk assessment where appropriate

## What I'll Provide

1. **Strengths**: What's done well in the current issue
2. **Gaps**: What's missing or could be improved
3. **Specific Suggestions**: Concrete improvements with examples
4. **Revised Sections**: Rewritten portions following best practices
5. **Additional Considerations**: Things to think about that weren't covered

## Example Analysis Output

```markdown
## Analysis Summary

**Issue Type**: Feature Request
**Overall Quality**: Good foundation, needs more technical detail

### Strengths ✅
- Clear problem statement
- Good phase breakdown
- Includes acceptance criteria

### Areas for Improvement 🔧

1. **Missing Security Considerations**
   - Add section on authentication requirements
   - Consider data privacy implications

2. **Incomplete Technical Details**
   - Add code examples for API endpoints
   - Include database schema changes

3. **Vague Acceptance Criteria**
   Current: "System should perform well"
   Suggested: "API response time < 200ms for 95th percentile"

### Suggested Additions

#### Security Considerations Section
```markdown
## Security Considerations
* All API endpoints require JWT authentication
* Implement rate limiting: 100 requests/minute per user
* Audit log all data modifications
```

[Additional suggestions...]
```

Please paste the Linear issue you'd like me to analyze!
