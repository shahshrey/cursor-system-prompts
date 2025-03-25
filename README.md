# Cursor System Prompts

A collection of the actual system prompts and tool definitions used by Claude AI models within the Cursor IDE.

## Overview

This repository contains the official system prompts and tool definitions that Cursor IDE uses behind the scenes to instruct Claude AI models (3.5 and 3.7 Sonnet). By making these prompts public, users can:

1. Learn how Cursor enables AI to understand code, respond to queries, and make edits to codebases
2. Understand the inner workings of Cursor's AI assistance capabilities
3. Use this knowledge to create their own custom Cursor rules that enhance their specific workflows and roles

## Repository Structure

- **System Prompts**: Core instructions used by Cursor to guide Claude AI models
  - `claude_3.5_system_prompt.md` - System prompt for Claude 3.5
  - `claude_3.7_system_prompt.md` - System prompt for Claude 3.7 Sonnet

- **Rules**: Guidelines for AI behavior
  - `rule.md` - Core workflow rules for effective codebase interaction

- **Tools Directory**: JSON schemas defining available tools for the AI
  - `codebase_search.json` - Semantic code search tool
  - `read_file.json` - File content reading tool
  - `edit_file.json` - File editing tool
  - `list_dir.json` - Directory exploration tool
  - And many others...

## Key Features

- **Behind-the-Scenes Access**: See exactly how Cursor instructs Claude to act as a pair programming partner
- **Tool Definitions**: Detailed specifications of all tools available to the AI
  - Semantic code search
  - File reading and editing
  - Directory exploration
  - Terminal command execution
  - And more

- **Learning Resource**: Study the prompts to understand AI instruction techniques
- **Custom Rule Development**: Use insights from these prompts to create personalized Cursor rules that support your specific workflows

## Usage

This repository serves as both documentation and a learning resource:

1. **Transparency**: Understand exactly how Cursor's AI assistance works
2. **Education**: Learn effective prompt engineering for coding assistance
3. **Customization**: Create your own Cursor rules based on these examples to enhance your development workflow
4. **Inspiration**: Use these prompts as a foundation for creating specialized AI workflows for your specific roles and projects

## Contributing

To contribute to this project, please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

[Watch how to jailbreak Cursor](https://github.com/shahshrey/cursor-system-prompts/blob/main/jailbreak.mp4)

