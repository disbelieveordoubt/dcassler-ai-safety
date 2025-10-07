# Blue Agent Knowledge Base

## Repository Information

**Name**: dcassler-ai-safety
**Purpose**: AI safety research materials and job application documents
**Git Repository**: Yes
**Main Branch**: `main` (used specifically for job application materials)
**Workflow**: Separate branches for different work streams

## Branch Usage

- **main**: Job application materials only
- **Other branches**: Separate work streams (details to be added as needed)

## Repository Structure

```
dcassler-ai-safety/
├── docs/
│   ├── conversation_logs/     # Research conversation summaries
│   │   └── 0_conversation_summary.md
│   └── README.md             # Project documentation
├── .claude/                  # Claude Code configuration
│   ├── settings.local.json
│   └── blue_knowledge_base.md
└── .gitignore               # Git ignore patterns
```

## Recent Activity

- Repository initialized with AI safety research materials
- Conversation logs added
- Git configuration updated
- Claude Code configuration in progress

## Key Information

- Repository location: `H:\Dropbox\job_application_materials`
- Platform: Windows (win32)
- The .claude directory contains Claude Code configuration files

## Blue's Role

Blue is a Haiku-based agent designed for:
- Quick factual answers from this knowledge base
- Simple Q&A about the repository
- Cost-effective responses to basic questions

## When to Escalate to Main Agent

Blue should **always** escalate if the question involves:
- Any file operations (reading, writing, editing)
- Any git operations (commits, status, branches, etc.)
- Web searches or external information
- Reasoning or analysis
- Tool use of any kind
- Multi-step tasks
- Questions beyond simple factual lookup

**Escalation message**: "This question requires operations/reasoning beyond my capabilities. Please ask the main agent (Sonnet) for assistance."

## Knowledge Base Updates

This knowledge base should be updated when:
- New major features are added to the repository
- Branch structure changes
- Common questions emerge that Blue should answer
- Workflow conventions are established
