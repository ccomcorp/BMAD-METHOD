
# BMAD-METHOD Advertising Research Expansion Pack

## Overview

The BMAD-METHOD Advertising Research Expansion Pack is a comprehensive 14-agent system designed for full-service marketing agency research. This expansion transforms BMAD into a powerful advertising research platform capable of conducting market intelligence, consumer insights, competitive analysis, campaign performance evaluation, and strategic synthesis.

## System Architecture

The system is organized into three specialized categories:

### Core Research Agents (4 agents)
These agents form the foundation of advertising research capabilities:

1. **Market Intelligence Lead** - Industry landscape analysis, market sizing, trend forecasting, and opportunity identification
2. **Consumer Insights Specialist** - Psychographic profiling, customer journey mapping, need-state analysis, and sentiment tracking
3. **Competitive Intelligence Analyst** - Competitor tracking, SWOT analysis, market share monitoring, and campaign reverse-engineering
4. **Campaign Performance Analyst** - ROI analysis, attribution modeling, channel performance evaluation, and A/B test interpretation

### Specialist Research Agents (4 agents)
These agents provide deep expertise in specialized research domains:

5. **Brand Perception Researcher** - Brand health tracking, reputation analysis, brand association mapping, and crisis detection
6. **Digital Behavior Analyst** - Website behavior analysis, mobile app usage tracking, digital journey mapping, and conversion optimization
7. **Media Landscape Researcher** - Media consumption analysis, media mix recommendations, channel attribution, and reach/frequency optimization
8. **Cultural Trends Analyst** - Cultural movement tracking, generational analysis, lifestyle trends, and cultural moment prediction

### Support and Synthesis Agents (6 agents)
These agents ensure research quality, coordination, and strategic synthesis:

9. **Data Collection Orchestrator** - Data source identification, quality validation, collection scheduling, and API management
10. **Statistical Validation Specialist** - Statistical rigor assurance, significance testing, bias detection, and confidence interval calculation
11. **Industry Context Expert** - Industry benchmarking, regulatory tracking, best practice identification, and contextual analysis
12. **Report Synthesis Director** - Narrative construction, insight prioritization, visualization selection, and executive summary creation
13. **Source Verification Auditor** - Fact-checking, source credibility assessment, citation management, and research integrity auditing
14. **Research Orchestration Manager** - Task delegation, timeline management, workflow coordination, and quality assurance oversight

## Agent Capabilities

### Research Methods
Each agent employs specialized research methodologies:
- **Quantitative**: Surveys, analytics, statistical analysis, market sizing, performance metrics
- **Qualitative**: Interviews, focus groups, ethnography, content analysis, expert consultation
- **Mixed Methods**: Triangulation, multi-source validation, integrated analysis

### Data Sources
Agents leverage diverse data sources:
- Primary research (surveys, interviews, user testing)
- Secondary research (industry reports, academic studies, government data)
- Digital analytics (web, mobile, social media)
- Market intelligence (syndicated research, databases)
- Competitive intelligence (public sources, monitoring)
- Cultural intelligence (social listening, trend tracking)

### Analytical Frameworks
Agents apply proven analytical frameworks:
- Market analysis (Porter's Five Forces, PESTEL, market sizing)
- Consumer research (VALS, jobs-to-be-done, journey mapping)
- Competitive analysis (SWOT, positioning maps, benchmarking)
- Performance analysis (attribution models, funnel analysis, MMM)
- Brand research (brand equity models, perception mapping)
- Statistical methods (hypothesis testing, regression, forecasting)

## Workflows

### End-to-End Research Workflow
The complete research process from initiation to delivery:

1. **Project Initiation** (Research Orchestration Manager)
   - Define research objectives and scope
   - Identify required agents and tasks
   - Develop project plan and timeline

2. **Data Collection** (Data Collection Orchestrator + Specialist Agents)
   - Identify and validate data sources
   - Coordinate data collection across agents
   - Ensure data quality and completeness

3. **Specialized Research** (Core + Specialist Research Agents)
   - Conduct parallel research streams
   - Apply specialized methodologies
   - Generate domain-specific insights

4. **Quality Validation** (Statistical Validation Specialist + Source Verification Auditor)
   - Validate statistical rigor
   - Verify facts and sources
   - Ensure research integrity

5. **Contextualization** (Industry Context Expert)
   - Provide industry benchmarks
   - Add regulatory context
   - Identify best practices

6. **Synthesis** (Report Synthesis Director)
   - Integrate findings across research streams
   - Prioritize insights by impact
   - Develop actionable recommendations

7. **Delivery** (Research Orchestration Manager)
   - Finalize reports and presentations
   - Conduct stakeholder briefings
   - Capture lessons learned

### Specialized Workflows

#### Market Entry Research
For evaluating new market opportunities:
- Market Intelligence Lead: Market landscape and sizing
- Consumer Insights Specialist: Target audience profiling
- Competitive Intelligence Analyst: Competitive dynamics
- Industry Context Expert: Regulatory and best practices
- Report Synthesis Director: Market entry recommendations

#### Brand Health Assessment
For comprehensive brand evaluation:
- Brand Perception Researcher: Brand health tracking
- Consumer Insights Specialist: Consumer brand perceptions
- Competitive Intelligence Analyst: Competitive brand positioning
- Cultural Trends Analyst: Cultural relevance assessment
- Report Synthesis Director: Brand strategy recommendations

#### Campaign Optimization
For improving campaign performance:
- Campaign Performance Analyst: Performance analysis and attribution
- Digital Behavior Analyst: Digital touchpoint optimization
- Media Landscape Researcher: Media mix optimization
- Consumer Insights Specialist: Audience insights
- Report Synthesis Director: Optimization recommendations

#### Competitive Intelligence
For ongoing competitive monitoring:
- Competitive Intelligence Analyst: Competitor tracking
- Market Intelligence Lead: Market dynamics
- Brand Perception Researcher: Competitive brand perceptions
- Media Landscape Researcher: Competitive media strategies
- Report Synthesis Director: Competitive intelligence briefings

## Usage Guide

### Getting Started

1. **Define Research Objectives**
   - Clearly articulate research questions
   - Identify key stakeholders and audiences
   - Determine scope and timeline

2. **Select Agent Team**
   - Choose appropriate agent team configuration
   - Consider research complexity and requirements
   - Balance comprehensiveness with efficiency

3. **Initiate Research Project**
   - Engage Research Orchestration Manager
   - Provide context and requirements
   - Review and approve project plan

### Agent Team Configurations

#### Full Marketing Research Team
All 14 agents for comprehensive research projects:
```yaml
Use: @research-orchestration-manager
Context: Full-service agency research project
Agents: All 14 agents collaborate
```

#### Core Research Team
4 core agents for foundational research:
```yaml
Use: @research-orchestration-manager
Context: Market and competitive intelligence
Agents: Market Intelligence Lead, Consumer Insights Specialist, 
        Competitive Intelligence Analyst, Campaign Performance Analyst
```

#### Specialist Research Team
4 specialist agents for deep-dive research:
```yaml
Use: @research-orchestration-manager
Context: Brand, digital, media, and cultural research
Agents: Brand Perception Researcher, Digital Behavior Analyst,
        Media Landscape Researcher, Cultural Trends Analyst
```

#### Support & Synthesis Team
6 support agents for quality and synthesis:
```yaml
Use: @research-orchestration-manager
Context: Quality assurance and report synthesis
Agents: Data Collection Orchestrator, Statistical Validation Specialist,
        Industry Context Expert, Report Synthesis Director,
        Source Verification Auditor, Research Orchestration Manager
```

### Command Examples

#### Market Intelligence
```
@market-intelligence-lead analyze-market-landscape [industry]
@market-intelligence-lead size-market [market-segment]
@market-intelligence-lead forecast-trends [timeframe] [industry]
```

#### Consumer Insights
```
@consumer-insights-specialist create-psychographic-profile [segment]
@consumer-insights-specialist map-customer-journey [persona]
@consumer-insights-specialist track-sentiment [brand] [timeframe]
```

#### Competitive Intelligence
```
@competitive-intelligence-analyst profile-competitor [competitor-name]
@competitive-intelligence-analyst conduct-swot [company]
@competitive-intelligence-analyst track-market-share [category]
```

#### Campaign Performance
```
@campaign-performance-analyst analyze-campaign-roi [campaign-id]
@campaign-performance-analyst build-attribution-model [timeframe]
@campaign-performance-analyst optimize-media-mix [budget]
```

## Integration with BMAD Framework

### Compatibility
The Advertising Research Expansion Pack integrates seamlessly with the core BMAD framework:
- Uses standard BMAD agent structure and patterns
- Leverages BMAD task and template systems
- Follows BMAD workflow and orchestration patterns
- Compatible with existing BMAD agent teams

### Complementary Capabilities
Research agents complement core BMAD development agents:
- Research informs product requirements (PO, Analyst)
- Market insights guide architecture decisions (Architect)
- Consumer insights inform UX design (UX Expert)
- Performance data drives optimization (Dev, QA)

### Shared Resources
Research agents leverage BMAD infrastructure:
- Task definitions for research activities
- Template system for research deliverables
- Checklist framework for quality assurance
- Knowledge base for research methodologies

## Best Practices

### Research Quality
- Use multiple data sources to validate findings
- Apply appropriate statistical methods
- Document assumptions and limitations
- Ensure ethical research practices
- Maintain transparency in methodology

### Project Management
- Define clear objectives and success criteria
- Establish realistic timelines and milestones
- Communicate regularly with stakeholders
- Manage scope and expectations
- Document lessons learned

### Collaboration
- Leverage agent specializations appropriately
- Ensure smooth handoffs between agents
- Maintain consistent quality standards
- Share insights across research streams
- Foster collaborative problem-solving

### Deliverables
- Tailor reports to audience needs
- Lead with insights and recommendations
- Use visualizations effectively
- Provide actionable next steps
- Include executive summaries

## File Structure

```
bmad-core/
├── agents/
│   ├── market-intelligence-lead.md
│   ├── consumer-insights-specialist.md
│   ├── competitive-intelligence-analyst.md
│   ├── campaign-performance-analyst.md
│   ├── brand-perception-researcher.md
│   ├── digital-behavior-analyst.md
│   ├── media-landscape-researcher.md
│   ├── cultural-trends-analyst.md
│   ├── data-collection-orchestrator.md
│   ├── statistical-validation-specialist.md
│   ├── industry-context-expert.md
│   ├── report-synthesis-director.md
│   ├── source-verification-auditor.md
│   └── research-orchestration-manager.md
├── tasks/
│   ├── [Market Intelligence Tasks]
│   ├── [Consumer Insights Tasks]
│   ├── [Competitive Intelligence Tasks]
│   ├── [Campaign Performance Tasks]
│   ├── [Brand Research Tasks]
│   ├── [Digital Analytics Tasks]
│   ├── [Media Research Tasks]
│   ├── [Cultural Analysis Tasks]
│   ├── [Data Collection Tasks]
│   ├── [Statistical Validation Tasks]
│   ├── [Industry Context Tasks]
│   ├── [Report Synthesis Tasks]
│   ├── [Source Verification Tasks]
│   └── [Research Orchestration Tasks]
├── templates/
│   ├── [Research Report Templates]
│   ├── [Analysis Templates]
│   └── [Deliverable Templates]
├── agent-teams/
│   ├── team-advertising-research-full.yaml
│   ├── team-advertising-research-core.yaml
│   ├── team-advertising-research-specialist.yaml
│   └── team-advertising-research-support.yaml
└── workflows/
    ├── end-to-end-research-workflow.yaml
    ├── market-entry-research-workflow.yaml
    ├── brand-health-assessment-workflow.yaml
    ├── campaign-optimization-workflow.yaml
    └── competitive-intelligence-workflow.yaml
```

## Support and Resources

### Documentation
- Agent persona and capability documentation
- Task and template specifications
- Workflow guides and examples
- Best practices and guidelines

### Knowledge Base
- Research methodologies reference
- Analytical frameworks library
- Data source directory
- Industry benchmarks database

### Training
- Agent capability overviews
- Workflow walkthroughs
- Use case examples
- Troubleshooting guides

## Version History

### Version 1.0 (Current)
- Initial release with 14 specialized agents
- Complete task and template library
- Four agent team configurations
- Five specialized workflows
- Comprehensive documentation

## Contributing

To contribute to the Advertising Research Expansion Pack:
1. Follow BMAD agent structure and patterns
2. Maintain consistency with existing agents
3. Document all capabilities and dependencies
4. Include comprehensive examples
5. Test workflows end-to-end

## License

This expansion pack is part of the BMAD-METHOD framework and follows the same licensing terms.

---

**Powered by BMAD™ Core**

For questions, issues, or contributions, please refer to the main BMAD-METHOD repository.

