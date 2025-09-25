# GitHub Copilot Instructions for Design2Code Workflow Agents

## Repository Overview

This repository contains a comprehensive AI agent workflow system that transforms visual designs into production-ready React components using BaseUI design system principles. The system consists of four specialized AI agents working together in an end-to-end pipeline.

## Agent Creation Guidelines

**If we want to create a new agent, make sure to look at `agentCreationContext/` for context.**

The `agentCreationContext/` folder contains essential resources for creating effective AI agents:

- `writingGuide2025.md` - Comprehensive best practices for AI agent instruction creation
- `modelSelectionGuide.md` - Guidelines for choosing optimal AI models for different tasks
- `claudeFormatBestPractice.md` - Specific patterns and formatting for Claude-based agents

When creating new agents, always reference these context files to ensure consistency with established patterns and best practices.

## Existing Agent System

### Core Workflow Agents

1. **UI Analysis Agent** (`design2code_uiAnalysis.chatmode.md`)
   - Analyzes screenshots and Figma designs using Atomic Design methodology
   - Extracts component hierarchies (atoms, molecules, organisms)
   - Provides comprehensive color analysis and design system insights

2. **Design Token Strategist** (`design2code_designTokenizer.chatmode.md`)
   - Transforms UI analysis into systematic design token architecture
   - Creates light/dark mode color systems with WCAG compliance
   - Generates implementation-ready token files and documentation

3. **BaseUI Component Builder** (`design2code_BaseUIComponentBuilder.chatmode.md`)
   - Builds production-ready React components using BaseUI primitives
   - Integrates with BaseUI's headless component architecture
   - Provides comprehensive TypeScript interfaces and documentation

4. **Layout Implementation Agent** (`design2code_siteBuilder.chatmode.md`)
   - Converts designs to pixel-perfect React implementations
   - Includes automated visual regression testing with Playwright
   - Provides accuracy assessment and improvement recommendations

### Agent Design Patterns

When working with or extending these agents, follow these patterns:

- **Identity-First Design**: Clear name, role, mission, and expertise definition
- **Hierarchical Objectives**: Prioritized goals with explicit conflict resolution
- **Explicit Behavior Specification**: Detailed communication styles and processes
- **Comprehensive Error Handling**: Planned responses for edge cases and failures
- **Quality Assurance Integration**: Built-in validation and testing requirements

## Development Guidelines

### File Organization

```
project/
├── .design/                   # Generated analysis and documentation
├── agentCreationContext/      # Agent development resources
├── *.chatmode.md             # Individual agent definitions
├── README.md                 # Complete workflow documentation
└── TODO.md                   # Planned improvements and explorations
```

### Agent Integration

- Each agent builds on outputs from previous phases
- Maintain consistent documentation formats across agents
- Ensure LLM-friendly markdown structure for easy parsing
- Include comprehensive examples and usage patterns

### Quality Standards

- All generated components must use BaseUI primitives
- Accessibility compliance (WCAG AA minimum) is mandatory
- TypeScript interfaces required for all React components
- Comprehensive documentation with usage examples
- Automated testing integration where applicable

### Workflow Phases

1. **Design Analysis** → Systematic UI breakdown using Atomic Design
2. **Token Strategy** → Comprehensive design token architecture
3. **Component Building** → Production-ready React components with BaseUI
4. **Implementation** → Pixel-perfect layouts with automated testing

## Contribution Guidelines

### Adding New Agents

1. Review `agentCreationContext/` materials thoroughly
2. Follow established agent structure patterns
3. Ensure integration with existing workflow phases
4. Include comprehensive testing and validation
5. **REQUIRED: Update README.md with new agent documentation**
   - Add agent to the workflow overview section
   - Include new agent in the phase descriptions
   - Update the agent list in "Existing Agent System"
   - Add usage examples and integration patterns
   - Update workflow diagrams if applicable
6. Add relevant TODO.md entries for future improvements

**Important**: Any agent updates or additions must include corresponding README updates to maintain documentation accuracy and completeness.

### Improving Existing Agents

- Maintain backward compatibility with existing workflows
- **REQUIRED: Update documentation to reflect changes**
  - Modify agent descriptions in README.md
  - Update workflow phase documentation
  - Revise usage examples if behavior changes
  - Update capability lists and limitations
- Test integration with other workflow phases
- Consider impact on generated outputs and file formats

**Important**: All agent modifications must be reflected in the README.md to keep documentation synchronized with actual agent capabilities.

### Code Generation Standards

- Use BaseUI components exclusively for UI elements
- Follow TypeScript best practices with proper type definitions
- Implement responsive design patterns
- Include accessibility attributes and ARIA compliance
- Provide multiple styling approach examples (Tailwind, CSS Modules, CSS-in-JS)

## Integration Points

### Figma Integration

- Support for direct Figma link analysis with node ID extraction
- Automatic design token and screenshot extraction
- Enhanced accuracy through direct design data access

### Playwright Testing

- Automated visual regression testing capabilities
- Screenshot comparison and accuracy assessment
- Performance and accessibility testing integration

### BaseUI Integration

- Always reference latest BaseUI documentation from `base-ui.com/llms.txt`
- Follow BaseUI's slot-based composition patterns
- Maintain compatibility with BaseUI's accessibility standards

## Best Practices

### Documentation

- Structure all outputs as LLM-friendly markdown
- Include comprehensive examples and usage patterns
- Provide clear navigation between related documents
- Generate interactive HTML previews where applicable

### Testing & Validation

- Include automated testing strategies in agent design
- Implement quality gates and validation checkpoints
- Provide clear success criteria and metrics
- Plan for iterative improvement and refinement

### Maintenance

- Regular updates to reflect BaseUI API changes
- Continuous improvement based on usage patterns
- Documentation updates for new features and capabilities
- Performance optimization and error handling enhancements

---

*When in doubt about agent creation or modification, always reference the `agentCreationContext/` folder for established patterns and best practices.*
