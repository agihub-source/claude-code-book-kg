# Graph Report - .  (2026-04-16)

## Corpus Check
- 1 files · ~10,000 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 49 nodes · 49 edges · 10 communities detected
- Extraction: 84% EXTRACTED · 16% INFERRED · 0% AMBIGUOUS · INFERRED: 8 edges (avg confidence: 0.5)
- Token cost: 0 input · 0 output

## God Nodes (most connected - your core abstractions)

## Surprising Connections (you probably didn't know these)
- `Agent Mode` --uses--> `File Operations`  [INFERRED]
   →   _Bridges community 0 → community 3_
- `Claude Code` --interface--> `CLI Interface`  [EXTRACTED]
   →   _Bridges community 0 → community 1_
- `Claude Code` --capability--> `Code Analysis`  [EXTRACTED]
   →   _Bridges community 0 → community 2_
- `Claude Code` --feature--> `Git Integration`  [EXTRACTED]
   →   _Bridges community 0 → community 4_
- `Claude Code` --supports--> `MCP Support`  [EXTRACTED]
   →   _Bridges community 0 → community 5_

## Communities

### Community 0 - "Core Claude Code"
Cohesion: 0.25
Nodes (9): Agent Mode, Anthropic, Approval Gates, Claude Code, Error Handling, Git Commit, IDE Integration, Prompt Design (+1 more)

### Community 1 - "Commands & CLI"
Cohesion: 0.22
Nodes (9): API Key Config, claude chat, claude config, claude init, claude run, claude tools, CLI Interface, Output Format (+1 more)

### Community 2 - "File Operations"
Cohesion: 0.29
Nodes (7): Code Analysis, Code Generation, Code Review, Debugging, Documentation, Refactoring, Testing

### Community 3 - "Code Capabilities"
Cohesion: 0.33
Nodes (6): Create File, Edit File, File Operations, Read File, Search Files, Write File

### Community 4 - "Git Integration"
Cohesion: 0.4
Nodes (5): Git Branch, Git Diff, Git Integration, Git Merge, Git Status

### Community 5 - "MCP Protocol"
Cohesion: 0.4
Nodes (5): MCP Support, MCP Tool Call, MCP Client, MCP Server, MCP Tools List

### Community 6 - "Best Practices"
Cohesion: 0.4
Nodes (5): Claude Haiku, Claude Opus, Claude Sonnet, Context Budget, Model Selection

### Community 7 - "Configuration"
Cohesion: 1.0
Nodes (1): Context Management

### Community 8 - "Models"
Cohesion: 1.0
Nodes (1): claude models

### Community 9 - "Community 9"
Cohesion: 1.0
Nodes (1): Delete File

## Knowledge Gaps
- **Thin community `Configuration`** (1 nodes): `Context Management`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Models`** (1 nodes): `claude models`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 9`** (1 nodes): `Delete File`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 3 inferred relationships involving `Claude Code` (e.g. with `IDE Integration` and `Prompt Design`) actually correct?**
  _`Claude Code` has 3 INFERRED edges - model-reasoned connections that need verification._