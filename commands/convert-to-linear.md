# Convert to Linear Format

Convert existing requirements, notes, or documentation into properly formatted Linear issues following our established patterns.

## What I Can Convert

Provide any of the following:
- Meeting notes with action items
- Email threads about features
- Rough requirements documents
- Existing issues from other systems (Jira, GitHub, etc.)
- Technical specifications
- Bug reports in any format
- Feature ideas or proposals

## Conversion Process

I will:

1. **Identify Issue Type**: Determine if this should be FR, US, PRD, Bug, or Task
2. **Extract Key Information**: Pull out requirements, context, and constraints
3. **Structure Properly**: Organize into our standard Linear format
4. **Fill Gaps**: Add missing sections with placeholders
5. **Add Metadata**: Suggest appropriate labels and properties

## Example Conversions

### From Email Thread
**Input**:
```
From: Product Manager
Subject: Need CSV export feature

Hey team, customers are asking for a way to export their data.
They want CSV format and ability to filter by date range.
This is becoming urgent as we're losing deals over it.
```

**Output**: Formatted US with user story, acceptance criteria, and success metrics

### From Technical Spec
**Input**:
```
API Rate Limiting Spec
- Implement per-user limits
- 1000 requests/hour standard
- 10000 requests/hour premium
- Redis for counter storage
- Return 429 with retry-after header
```

**Output**: Formatted FR with phases, technical requirements, and implementation plan

### From Bug Report
**Input**:
```
Login is broken!
When I use @ symbol in password it gives error.
This worked last week.
```

**Output**: Structured bug report with reproduction steps and environment details

## What I'll Add

Beyond converting your content, I'll add:

- Proper issue title with type prefix
- Standard sections for that issue type
- Placeholder text for missing information
- Suggested labels and metadata
- Related issues section
- Definition of Done
- Notes about what needs clarification

## Output Format

```markdown
[Converted and structured content]

---
## 📝 Conversion Notes

**Source**: $SOURCE_TYPE
**Completeness**: $PERCENTAGE%

**Missing Information**:
- $WHAT_NEEDS_CLARIFICATION_1
- $WHAT_NEEDS_CLARIFICATION_2

**Suggested Labels**:
- effort: $SIZE
- type: $TYPE
- component: $COMPONENT
- priority: $PRIORITY

**Recommended Next Steps**:
1. $ACTION_1
2. $ACTION_2
```

Paste your content and I'll convert it into a proper Linear issue!
