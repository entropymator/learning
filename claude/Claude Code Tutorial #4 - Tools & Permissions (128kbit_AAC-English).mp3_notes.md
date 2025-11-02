# Claude Code Tutorial #4 - Tools & Permissions (128kbit_AAC-English).mp3

## Overview

This tutorial provides an introduction to the built-in tools within Claude Code, focusing on user permissions, file management, and Git integration. The discussion covers various actions such as read, edit, bash, and to-do, along with the use of Git commands like `git add` for file staging and committing.

## Main Ideas

1. Claude Code's built-in tools automate actions based on user instructions, including read, edit, bash, and to-do.
2. User permission is required for certain tasks such as editing files or running the bash command, but not for reading files.
3. Users can grant or deny permissions when prompted by Claude Code with options: yes (grant), no (deny), and yes and don't ask me again (grant once for the current session).
4. The `bash` tool in Claude Code is used for Git commands like adding files to the staging area and committing them with a commit message.
5. Claude Code creates a settings file (settings.local.json) within a .Claude folder in the project, containing a permissions object when the user grants permission for certain tasks without being asked again during the current session.
6. Users can customize the allowed list of commands by running specific commands or manually editing the settings file.
7. The accept edits feature allows Claude Code to edit files without asking for permission within a chat session, which can be turned on and off using Alt+M (or Control+M on Mac).

## Key Manipulations and Scripting or Coding Used

1. User interaction with prompts for granting permissions.
2. Utilization of Git commands like `git add` and commit within the bash tool.
3. Customization of allowed commands by running specific commands or manually editing the settings file.
4. Enabling and disabling the accept edits feature using Alt+M (or Control+M on Mac).

## Reflective/Quiz-style Questions

1. What are the four built-in tools that Claude Code utilizes based on user instructions?
2. Which Git commands can be performed using the bash tool within Claude Code, and how are they executed?
3. How does the accept edits feature work in Claude Code, and what is the keyboard shortcut to enable/disable it?