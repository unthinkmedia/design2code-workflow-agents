```
<instructions>
[COMPREHENSIVE_AGENT_INSTRUCTIONS]
</instructions>

### XML Structure Advantages
Claude responds exceptionally well to XML-structured instructions:

```xml
<agent_profile>
<identity>
    <name>[AGENT_NAME]</name>
    <role>[PRIMARY_ROLE]</role>
    <expertise>[DOMAIN_AREAS]</expertise>
</identity>

<mission>[CORE_PURPOSE]</mission>

<objectives>
    <primary>[TOP_PRIORITY]</primary>
    <secondary>[SECOND_PRIORITY]</secondary>
    <tertiary>[THIRD_PRIORITY]</tertiary>
</objectives>

<behavioral_guidelines>
    <communication_style>[STYLE_DETAILS]</communication_style>
    <response_format>[FORMAT_PREFERENCES]</response_format>
    <tone>[TONE_DESCRIPTION]</tone>
</behavioral_guidelines>

<capabilities>
    <can_do>
        <item>[CAPABILITY_1]</item>
        <item>[CAPABILITY_2]</item>
    </can_do>
    <cannot_do>
        <item>[LIMITATION_1]</item>
        <item>[LIMITATION_2]</item>
    </cannot_do>
</capabilities>

<workflows>
    <standard_process>
        <step_1>[FIRST_STEP]</step_1>
        <step_2>[SECOND_STEP]</step_2>
        <step_3>[VERIFICATION]</step_3>
    </standard_process>
</workflows>

<quality_assurance>
    <requirements>
        <item>[REQUIREMENT_1]</item>
        <item>[REQUIREMENT_2]</item>
    </requirements>
</quality_assurance>
</agent_profile>
```

## Claude Context Advantages

### Extended Context Window
- **Claude 3 Haiku**: ~75,000 tokens (56,000 words)
- **Claude 3 Sonnet**: ~200,000 tokens (150,000 words)  
- **Claude 3 Opus**: ~200,000 tokens (150,000 words)

### Comprehensive Instruction Strategy
Take advantage of Claude's large context to include:

```
EXTENDED INSTRUCTION SECTIONS:
✓ Detailed examples for each major use case
✓ Comprehensive error handling scenarios
✓ Multiple workflow variations
✓ Extensive quality criteria
✓ Cultural and accessibility considerations
✓ Advanced reasoning frameworks
```

## Claude-Specific Behavioral Patterns

### Constitutional AI Integration
Claude naturally aligns with ethical principles, so emphasize value-based guidance:

```xml
<ethical_framework>
    <core_values>
        <helpfulness>Prioritize genuinely assisting users</helpfulness>
        <harmlessness>Avoid potential negative consequences</harmlessness>
        <honesty>Be transparent about limitations and uncertainty</honesty>
    </core_values>
    
    <decision_principles>
        <principle>When goals conflict, prioritize safety and user wellbeing</principle>
        <principle>Acknowledge uncertainty rather than guessing</principle>
        <principle>Respect user autonomy while providing guidance</principle>
    </decision_principles>
</ethical_framework>
```

### Reasoning and Analysis Strengths
Claude excels at complex reasoning, so leverage this:

```xml
<reasoning_approach>
    <analysis_method>
        <step>Break down complex problems systematically</step>
        <step>Consider multiple perspectives and approaches</step>
        <step>Evaluate evidence and reasoning quality</step>
        <step>Synthesize insights into actionable guidance</step>
    </analysis_method>
    
    <critical_thinking>
        <requirement>Question assumptions explicitly</requirement>
        <requirement>Consider alternative explanations</requirement>
        <requirement>Identify potential biases or limitations</requirement>
        <requirement>Provide reasoning transparency</requirement>
    </critical_thinking>
</reasoning_approach>
```

## Tool Integration Guidelines

### Function Calling Format
Claude uses specific XML formatting for tools:

```xml
<tool_usage_guidelines>
    <general_principles>
        <principle>Always explain tool usage to users</principle>
        <principle>Validate tool inputs before calling</principle>
        <principle>Handle tool errors gracefully</principle>
        <principle>Interpret tool outputs for user benefit</principle>
    </general_principles>
    
    <tool_call_process>
        <step_1>Determine if tool use is necessary</step_1>
        <step_2>Explain intended tool usage to user</step_2>
        <step_3>Execute tool call with proper formatting</step_3>
        <step_4>Interpret and synthesize results</step_4>
        <step_5>Provide clear summary of actions taken</step_5>
    </tool_call_process>
</tool_usage_guidelines>
```

### Artifact Creation
When creating artifacts, include specific guidance:

```xml
<artifact_guidelines>
    <when_to_create>
        <scenario>Substantial code or content creation</scenario>
        <scenario>Reference materials user will reuse</scenario>
        <scenario>Complex documents or analysis</scenario>
    </when_to_create>
    
    <artifact_types>
        <code>Use for programming solutions</code>
        <documents>Use for reference materials</documents>
        <visualizations>Use for charts and interactive content</visualizations>
    </artifact_types>
    
    <quality_standards>
        <requirement>Complete, functional solutions</requirement>
        <requirement>Clear documentation and comments</requirement>
        <requirement>Professional formatting and structure</requirement>
    </quality_standards>
</artifact_guidelines>
```

## Advanced Claude Features

### Conversation Management
Claude maintains excellent conversation continuity:

```xml
<conversation_handling>
    <context_awareness>
        <track_user_goals>Monitor user's overall objectives</track_user_goals>
        <remember_preferences>Adapt to stated preferences</remember_preferences>
        <build_on_previous>Reference and build on earlier discussion</build_on_previous>
    </context_awareness>
    
    <adaptation_strategy>
        <skill_level>Adjust explanations to user expertise</skill_level>
        <communication_style>Match user's preferred interaction style</communication_style>
        <detail_level>Provide appropriate depth for context</detail_level>
    </adaptation_strategy>
</conversation_handling>
```

### Uncertainty Handling
Claude is excellent at expressing uncertainty appropriately:

```xml
<uncertainty_management>
    <confidence_levels>
        <high_confidence>State information clearly</high_confidence>
        <medium_confidence>Include appropriate caveats</medium_confidence>
        <low_confidence>Explicitly acknowledge uncertainty</low_confidence>
        <no_knowledge>Clearly state knowledge limitations</no_knowledge>
    </confidence_levels>
    
    <uncertainty_expressions>
        <approach>Use specific uncertainty language</approach>
        <approach>Provide confidence ranges when applicable</approach>
        <approach>Suggest verification methods</approach>
        <approach>Offer alternative perspectives</approach>
    </uncertainty_expressions>
</uncertainty_management>
```

## Implementation Template

### Complete Claude Instruction Template
```xml
<instructions>
<agent_identity>
    <name>[AGENT_NAME]</name>
    <role>[SPECIFIC_ROLE_DESCRIPTION]</role>
    <mission>[COMPREHENSIVE_MISSION_STATEMENT]</mission>
    <expertise>[DOMAIN_KNOWLEDGE_AREAS]</expertise>
</agent_identity>

<core_objectives>
    <primary_objective>[HIGHEST_PRIORITY_GOAL]</primary_objective>
    <secondary_objectives>
        <objective>[SECOND_PRIORITY]</objective>
        <objective>[THIRD_PRIORITY]</objective>
    </secondary_objectives>
    <success_criteria>[HOW_TO_MEASURE_SUCCESS]</success_criteria>
</core_objectives>

<behavioral_framework>
    <communication_style>
        <tone>[TONE_DESCRIPTION]</tone>
        <formality_level>[FORMALITY_GUIDANCE]</formality_level>
        <adaptation>[HOW_TO_ADAPT_TO_USERS]</adaptation>
    </communication_style>
    
    <response_approach>
        <structure>[PREFERRED_ORGANIZATION]</structure>
        <length>[LENGTH_GUIDELINES]</length>
        <examples>[WHEN_TO_INCLUDE_EXAMPLES]</examples>
    </response_approach>
    
    <reasoning_style>
        <transparency>[REASONING_VISIBILITY]</transparency>
        <depth>[ANALYSIS_DEPTH]</depth>
        <perspective>[MULTIPLE_VIEWPOINTS]</perspective>
    </reasoning_style>
</behavioral_framework>

<capabilities_and_limitations>
    <core_capabilities>
        <capability>[DETAILED_CAPABILITY_1]</capability>
        <capability>[DETAILED_CAPABILITY_2]</capability>
    </core_capabilities>
    
    <explicit_limitations>
        <limitation>[CLEAR_BOUNDARY_1]</limitation>
        <limitation>[CLEAR_BOUNDARY_2]</limitation>
    </explicit_limitations>
    
    <boundary_handling>
        <approach>[HOW_TO_HANDLE_EDGE_CASES]</approach>
        <escalation>[WHEN_TO_REFER_ELSEWHERE]</escalation>
    </boundary_handling>
</capabilities_and_limitations>

<workflow_standards>
    <standard_process>
        <step_1>[INITIAL_ASSESSMENT]</step_1>
        <step_2>[INFORMATION_GATHERING]</step_2>
        <step_3>[ANALYSIS_AND_REASONING]</step_3>
        <step_4>[SOLUTION_DEVELOPMENT]</step_4>
        <step_5>[QUALITY_VERIFICATION]</step_5>
        <step_6>[RESPONSE_DELIVERY]</step_6>
    </standard_process>
    
    <quality_assurance>
        <check>[ACCURACY_VERIFICATION]</check>
        <check>[COMPLETENESS_REVIEW]</check>
        <check>[SAFETY_CONSIDERATION]</check>
        <check>[USER_GOAL_ALIGNMENT]</check>
    </quality_assurance>
</workflow_standards>

<error_handling>
    <common_scenarios>
        <scenario type="insufficient_information">
            <response>[HOW_TO_HANDLE_MISSING_INFO]</response>
        </scenario>
        <scenario type="conflicting_requirements">
            <response>[HOW_TO_HANDLE_CONFLICTS]</response>
        </scenario>
        <scenario type="outside_scope">
            <response>[HOW_TO_HANDLE_SCOPE_ISSUES]</response>
        </scenario>
    </common_scenarios>
    
    <recovery_strategies>
        <strategy>[ERROR_ACKNOWLEDGMENT_APPROACH]</strategy>
        <strategy>[ALTERNATIVE_SOLUTION_OFFERING]</strategy>
        <strategy>[GRACEFUL_DEGRADATION_METHOD]</strategy>
    </recovery_strategies>
</error_handling>

<special_considerations>
    <tool_usage>
        [TOOL_SPECIFIC_GUIDANCE_IF_APPLICABLE]
    </tool_usage>
    
    <artifact_creation>
        [ARTIFACT_CREATION_GUIDELINES_IF_APPLICABLE]
    </artifact_creation>
    
    <safety_priorities>
        [SAFETY_SPECIFIC_INSTRUCTIONS]
    </safety_priorities>
</special_considerations>
</instructions>
```

## Testing & Optimization

### Claude-Specific Testing
```xml
<testing_framework>
    <test_categories>
        <category>Complex reasoning scenarios</category>
        <category>Ethical dilemma handling</category>
        <category>Tool integration accuracy</category>
        <category>Artifact creation quality</category>
        <category>Long conversation consistency</category>
    </test_categories>
    
    <performance_metrics>
        <metric>Instruction adherence over extended contexts</metric>
        <metric>Quality of reasoning and analysis</metric>
        <metric>Appropriate uncertainty expression</metric>
        <metric>Tool usage effectiveness</metric>
        <metric>Artifact completeness and functionality</metric>
    </performance_metrics>
</testing_framework>
```

### Common Claude Optimization Strategies

**Leverage Reasoning Strengths:**
```
- Include "think step by step" language
- Ask for explicit reasoning chains
- Request consideration of multiple perspectives
- Encourage questioning of assumptions
```

**XML Structure Benefits:**
```
- Better instruction parsing and following
- Clear hierarchical organization
- Easier to modify specific sections
- Enhanced readability for complex instructions
```

**Context Window Utilization:**
```
- Include comprehensive examples
- Provide detailed error handling scenarios
- Add extensive quality criteria
- Include multiple workflow variations
```

## Best Practices Summary

### Claude-Specific Strengths to Leverage
1. **Exceptional reasoning ability** - Use detailed analytical frameworks
2. **Strong ethical alignment** - Emphasize value-based decision making
3. **Large context windows** - Include comprehensive instructions and examples
4. **XML structure affinity** - Organize instructions hierarchically
5. **Uncertainty handling** - Trust Claude to express appropriate confidence levels

### Implementation Workflow
1. Start with Universal Guide foundation
2. Structure instructions using XML format
3. Leverage extended context for comprehensive coverage
4. Include detailed reasoning frameworks
5. Test across complex scenarios
6. Iterate based on Claude's specific feedback patterns

### Integration Considerations
- Claude works well with both simple and complex instruction sets
- Takes advantage of large context windows for comprehensive guidance
- Excellent at maintaining consistency across long conversations
- Strong at handling ambiguous or edge case scenarios
- Natural alignment with ethical and safety considerations

This Claude-specific guide should be used in conjunction with the Universal Agent Instructions Drafting Guide for complete implementation optimized for Anthropic's Claude models.```
<instructions>
[COMPREHENSIVE_AGENT_INSTRUCTIONS]
</instructions>```
<instructions>
[COMPREHENSIVE_AGENT_INSTRUCTIONS]
</instructions># Claude-Specific Implementation Guide

## Overview
This guide supplements the Universal Agent Instructions Drafting Guide with Claude-specific implementation details for Anthropic's Claude models (Claude 3 Haiku, Sonnet, and Opus variants).

## Claude Architecture Essentials

### Instruction Format
Claude uses a single, comprehensive instruction block rather than separate system/user messages:

```
<instructions>
[COMPREHENSIVE_AGENT_INSTRUCTIONS]
</instructions>