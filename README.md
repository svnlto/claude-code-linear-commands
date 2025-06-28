# Claude Code Linear Commands

A comprehensive set of Claude Code commands for generating well-structured Linear issues following established patterns. Transform ideas, requirements, and bugs into properly formatted Linear issues with consistent structure and documentation.

## 🎯 Overview

This system streamlines Linear issue creation by:
- **Issue Type Templates**: Standardized formats for FRs, User Stories, PRDs, and Bugs
- **Quick Issue Generation**: Minimal input for rapid idea capture
- **Conversion Tools**: Transform existing documents into proper Linear format
- **Analysis & Improvement**: Review and enhance existing issues
- **Consistent Structure**: Follow established patterns for team consistency

## 🚀 Quick Start

```bash
# Generate a quick issue from minimal input
/quick-issue FR: Add rate limiting to API endpoints

# Create detailed Feature Request
/generate-fr

# Generate comprehensive User Story
/generate-us

# Create Product Requirements Document
/generate-prd

# Convert existing content to Linear format
/convert-to-linear

# Analyze and improve existing issues
/analyze-issue
```

## 📁 Repository Structure

```
claude-code-linear-commands/
├── commands/                     # Claude command definitions
│   ├── quick-issue.md           # Quick issue generator
│   ├── generate-fr.md           # Feature Request generator
│   ├── generate-us.md           # User Story generator
│   ├── generate-prd.md          # Product Requirements Document
│   ├── convert-to-linear.md     # Convert existing content
│   └── analyze-issue.md         # Analyze existing issues
│
└── README.md                    # This documentation
```

## 🔄 How It Works

### Command-Based Issue Generation
Each command follows a specific pattern to generate well-structured Linear issues:

### Quick Issue Generation (`/quick-issue`)
```
User: /quick-issue FR: Add rate limiting to API endpoints
```
Claude generates a properly formatted Feature Request with basic structure, ready for refinement.

### Detailed Issue Creation (`/generate-fr`, `/generate-us`, `/generate-prd`)
```
User: /generate-fr
Claude: I need information about the feature...
User: [Provides details]
Claude: [Generates comprehensive issue with all sections]
```

### Content Conversion (`/convert-to-linear`)
```
User: /convert-to-linear
[Pastes email thread or meeting notes]
Claude: [Converts to structured Linear issue format]
```

### Issue Analysis (`/analyze-issue`)
```
User: /analyze-issue
[Pastes existing Linear issue]
Claude: [Provides improvement suggestions and enhanced sections]
```

## 📋 Command Reference

### `/quick-issue [description]`
Generate a quick Linear issue with minimal input. Perfect for capturing ideas.

**Example:**
```
/quick-issue FR: Add rate limiting to API endpoints
/quick-issue Bug: Login fails with special characters
/quick-issue US: User needs to export data as CSV
```

### `/generate-fr`
Create a comprehensive Feature Request with technical requirements and implementation plan.

**Output includes:**
- Strategic context and business value
- Phased technical requirements
- Implementation details with code examples
- Security and performance considerations

### `/generate-us`
Generate a detailed User Story with acceptance criteria and success metrics.

**Output includes:**
- User-focused story format
- Clear acceptance criteria
- Technical implementation notes
- Success metrics and KPIs

### `/generate-prd`
Create a Product Requirements Document for complex features.

**Output includes:**
- Executive summary and problem statement
- Detailed feature specifications
- Implementation timeline
- Risk assessment and mitigations

### `/convert-to-linear`
Transform existing content into proper Linear issue format.

**Accepts:**
- Meeting notes
- Email threads
- Technical specifications
- Bug reports from other systems

### `/analyze-issue`
Review and improve existing Linear issues.

**Provides:**
- Structure and content analysis
- Specific improvement suggestions
- Enhanced sections following best practices

## 🎯 Features

### Standardized Templates
Every issue type follows established patterns:
- Consistent structure and sections
- Appropriate metadata and labels
- Clear acceptance criteria

### Multiple Issue Types
- **Feature Requests (FR)**: Technical requirements with implementation details
- **User Stories (US)**: User-focused functionality with success metrics
- **Product Requirements (PRD)**: Comprehensive product specifications
- **Quick Issues**: Rapid capture for later refinement

### Content Intelligence
- Automatic issue type detection
- Smart section population
- Missing information identification

### Team Consistency
- Follows established Linear patterns
- Maintains organizational standards
- Reduces review cycles

## 💡 Best Practices

### For Users
1. **Be Specific**: Clear descriptions lead to better structured issues
2. **Choose Right Command**: Use `/quick-issue` for rapid capture, detailed commands for thorough specs
3. **Provide Context**: Include business value and technical constraints
4. **Review Output**: Check generated issues before adding to Linear

### For Issues
1. **One Feature Per Issue**: Keep scope focused and manageable
2. **Include Examples**: Add code snippets and implementation details
3. **Define Success**: Clear acceptance criteria and success metrics
4. **Link Dependencies**: Reference related issues and blockers

## 🔧 Installation

### Prerequisites

These commands require the Linear MCP server to be configured in your Claude Code setup. The Linear MCP server enables Claude to directly interact with your Linear workspace.

**Setup the Linear MCP server:** Follow the official Linear documentation at [linear.app/changelog/2025-05-01-mcp](https://linear.app/changelog/2025-05-01-mcp) to configure the Linear integration.

### Install Commands

1. Clone this repository:
```bash
git clone https://github.com/svnlto/claude-code-linear-commands.git
```

2. Copy the commands to your project:
```bash
cp -r commands ~/.claude/commands/
# OR for project-specific
cp -r commands /your/project/.claude/commands/
```

3. Start using the commands in Claude Code:
```bash
/quick-issue Your first issue description
```

## 📚 Examples

### Quick Issue Creation
```
/quick-issue FR: Add caching to product API endpoints
/quick-issue Bug: Users can't upload files larger than 5MB
/quick-issue US: Admin needs bulk user management tools
```

### Feature Request Development
```
/generate-fr
# Provide feature details
# Get comprehensive FR with technical specs, implementation phases, and acceptance criteria
```

### Converting Meeting Notes
```
/convert-to-linear
[Paste meeting notes about new dashboard feature]
# Get structured Linear issue with proper sections and requirements
```

### User Story Creation
```
/generate-us
# Define user type, need, and value
# Get detailed user story with acceptance criteria and success metrics
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Add new commands or improve existing ones
4. Submit a pull request

### Ideas for Contribution
- Add templates for additional issue types
- Create issue validation commands
- Build integrations with Linear API
- Add team-specific customizations

## 📄 License

MIT License - Feel free to use and modify for your projects.
