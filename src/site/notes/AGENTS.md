---
{"dg-publish":true,"permalink":"/agents/","dg-note-properties":{}}
---

## Folder Structure

- **_templates**: templates for notes.

---

## Agent Index

- **Janitor**: [[.agents/janitor.agent.md\|.agents/janitor.agent.md]]
- **Image Analyzer**: [[.agents/image-analyzer.agent.md\|.agents/image-analyzer.agent.md]]
- **Prompt Engineer**: [[.agents/prompt-engineer.agent.md\|.agents/prompt-engineer.agent.md]]
- **Prompt Dispatcher**: [[.agents/prompt-dispatcher.agent.md\|.agents/prompt-dispatcher.agent.md]]

## Agent Routing

Route by intent. Users may use slash commands or natural language:

## Task Map

- `/maintenance`- **Maintenance**: Janitor agent
- `/image-analysis` **Image Analysis**: Image Analyzer agent
- `/create-prompt` **Create Prompt**: Prompt Engineer agent
- `/execute-prompt` **Execute Prompt**: Prompt Dispatcher agent
- `/image-to-prompt` **Create Prompt From Image(s)**: Image Analyzer agent | Prompt Engineer agent
