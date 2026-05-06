---
{"dg-publish":true,"permalink":"/agents/","dg-note-properties":{}}
---

## Folder Structure

- **_templates_**: templates for notes.

---

## Agent Index

- **Janitor**: [[.prompts/janitor.prompt.md\|.prompts/janitor.prompt.md]]
- **Image Analyzer**: [[.prompts/image-analyzer.prompt.md\|.prompts/image-analyzer.prompt.md]]
- **Prompt Engineer**: [[.prompts/prompt-engineer.prompt.md\|.prompts/prompt-engineer.prompt.md]]
- **Prompt Dispatcher**: [[.prompts/prompt-dispatcher.prompt.md\|.prompts/prompt-dispatcher.prompt.md]]

## Agent Routing

Route by intent. Users may use slash commands or natural language:

## Task Map

- `/maintenance`- **Maintenance**: Janitor agent
- `/image-analysis` **Image Analysis**: Image Analyzer agent
- `/create-prompt` **Create Prompt**: Prompt Engineer agent
- `/execute-prompt` **Execute Prompt**: Prompt Dispatcher agent
- `/image-to-prompt` **Create Prompt From Image(s)**: Image Analyzer agent | Prompt Engineer agent
