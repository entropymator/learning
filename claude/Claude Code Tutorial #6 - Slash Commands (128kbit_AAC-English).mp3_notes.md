# Claude Code Tutorial #6 - Slash Commands (128kbit_AAC-English)

This tutorial focuses on understanding and utilizing slash commands (hereafter referred to as commands) within the Cloud Code environment. Commands can be used for various tasks such as clearing context, initializing files, managing directories, and more. Typing '/' displays a list of all available commands.

## Main Ideas
- Creating custom commands for common project tasks
- Adding new commands to Claude code that pull in markdown files
- Using command arguments in custom commands
- Modifying the preview page of a project, specifically focusing on icons

## Key Manipulations and Scripting or Coding Used
- Creating a 'commands' folder inside the '.cloud' folder (or creating it if not present)
- Defining instructions for Claude code in markdown files within the 'commands' folder
- Utilizing the '@' symbol to load another file as context in custom commands
- Using the front matter at the top of command files to define properties and argument hints
- Capturing command arguments with `$arguments`
- Passing multiple values from `$arguments` using square brackets to create variables
- Restarting Claude after making changes to the command file for them to take effect
- Implementing an icon library in the preview page of a project

## Reflective or Quiz-Style Questions
1. What are slash commands (commands) used for in Cloud Code, and how can you display a list of available commands?
2. How would you create a custom command for generating UI components in Claude code? Provide at least three steps.
3. What is the purpose of using `$arguments` within a command file, and how are multiple values passed from it using square brackets?