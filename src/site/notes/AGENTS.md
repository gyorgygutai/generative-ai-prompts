---
{"dg-publish":true,"permalink":"/agents/","dg-note-properties":{}}
---

## Folder Structure

- **Photography**: archive of photo prompts
- **Video**: archive of video prompts
- **GENERATED**: AI-generated prompts. Reference images in `assets` subfolder.
- **EXAMPLES**: confirmed best examples — read before writing any prompt.
- **TEMPLATES**: templates for notes.
- **KNOWLEDGE**: photography techniques, expression references, and model-specific confirmed behavior.

---

## Agent Index

- **Janitor**: [[.prompts/janitor.md\|.prompts/janitor.md]]
- **Image Analyzer**: [[.prompts/image-analyzer.prompt.md\|.prompts/image-analyzer.prompt.md]]
- **Prompt Engineer**: [[.prompts/prompt-engineer.prompt.md\|.prompts/prompt-engineer.prompt.md]]
- **Prompt Dispatcher**: [[prompts/prompt-dispatcher.prompt.md\|prompts/prompt-dispatcher.prompt.md]]

## Agent Routing

Route by intent. Users may use slash commands or natural language:

## Task Map

- `/maintenance`- **Maintenance**: Janitor agent
- `/image-analysis` **Image Analysis**: Image Analyzer agent
- `/create-prompt` **Create Prompt**: Prompt Engineer agent
- `/execute-prompt` **Execute Prompt**: Prompt Dispatcher agent
- `/image-to-prompt` **Create Prompt From Image(s)**: Image Analyzer agent | Prompt Engineer agent