# AI Assistant Guide: Daniel Cassler's AI Safety Research Portfolio

## Overview for AI Assistants

**Repository Purpose**: This repository contains Daniel Cassler's professional portfolio demonstrating expertise in AI architectural vulnerabilities and safety research. The project showcases systematic vulnerability detection methodology in large language models.

**Context**: Owner is actively seeking AI safety roles at frontier AI companies, with 15+ years of operational security experience.

## Branch Structure

### `main` Branch
- **Purpose**: Public-facing portfolio and job application materials
- **Contents**: Polished documentation, methodology summaries, evidence portfolio overview
- **Privacy**: Excludes raw conversation logs, sensitive research data, and personal information
- **Licensing**: Apache 2.0
- **Audience**: Hiring managers, interviewers, collaborators

### `private` Branch
- **Purpose**: Complete research workspace with full evidence and development materials
- **Contents**: Raw conversational logs, detailed evidence, AI configurations, additional documentation
- **Privacy**: Contains potentially sensitive research data - NOT for public consumption
- **Licensing**: GPL-3.0 (historically)

## File Structure & Purpose

### Core Documentation Files
- `README.md`: Project overview and navigation
- `methodology.md`: Detailed testing protocol and framework
- `NOTICE`: Attribution requirements
- `LICENSE`: Apache 2.0 license for public use

### Evidence & Research Materials
- `conversations/`: Raw logs of AI interactions demonstrating vulnerabilities
  - `01_rapid_diagnostic_sonnet45.md`: Claude vulnerability demonstration
  - `02_butler_jci_sonnet45.md`: Corrections sector testing
  - `03_k12_teacher_gpt5.md`: Educational context failure
  - `04_deepseek_v31_cot.md`: Chain-of-thought analysis
  - `05_prea_persistence_sonnet40to45.md`: Cross-version persistence
  - `EVIDENCE_PORTFOLIO.md`: Clean summary for presentation

- `full_research/`: Comprehensive research write-ups
- `docs/`: Supplementary appendices and reference materials
- `chatlogs.md`: Aggregated conversational evidence

### AI Configuration Files (.claude/)
- `agents/blue.md`: Assistant configuration for research work
- `blue_knowledge_base.md`: Knowledge context for research queries
- `commands/blue.md`: Custom commands available
- `settings.local.json`: Local AI tool configuration

### Private Materials (Not in main)
- `private/application_statement.md`: Personal job application documents
- Temporary work files in `trash/`

## AI Interaction Guidelines

### When Working on `main` Branch (Public)
- Focus on documentation clarity and professional presentation
- Do not include raw evidence or personal information
- Maintain Apache 2.0 compatibility
- Ensure all changes are portfolio-appropriate

### When Working on `private` Branch (Research)
- Full access to evidence and research materials
- Respect privacy settings in .gitignore
- GPL licensing allows broader research use
- Use raw conversation logs for analysis and summarization

### Sensitive File Handling
- Conversation logs contain real AI vulnerability demonstrations
- May include sensitive domain knowledge (child protection, abuse prevention)
- Handle appropriately for research privacy
- Files in `conversations/` are intentionally ignored in public branches

## Research Domain Context

**Core Research**: "Pre-Reasoning Framework Hijacking" - systematic vulnerability where care-associated vocabulary triggers deterministic routing failures before reasoning layer activation.

**Domain Impact**: Affects high-stakes applications (child protection, medical reporting, Title IX compliance) where care language conflicts with legal/categorical compliance mandates.

**Cross-Model Validation**: Evidence demonstrates persistent architectural failures across Claude, GPT, and DeepSeek variants.

## AI Assistant Recommended Interactions

1. **Content Creation**: Help refine methodology documentation and evidence presentation
2. **Code Review**: Analyze and suggest improvements to repository structure
3. **Research Analysis**: Summarize conversational evidence without compromising privacy
4. **Documentation Organization**: Maintain clean separation between public and private branches
5. **Branch Management**: Assist with merging safe changes back to main branch

## Important Notes

- This portfolio demonstrates specialized skills in systematic vulnerability detection
- Repository owner has extensive operational security background
- All materials intended to showcase research capabilities for hiring
- Maintain professional quality in all public-facing documentation
