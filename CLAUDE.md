
# Date and Time Context

The current year is 2025.
The current month is December.
Analyze all version and documentation that you encounter in this light and seek to verify that you have the most up to date information.

# TOOLS

You have access to GitHub through the `gh` CLI as my GitHub user WesleyDavid. Use that first when attempting to interact with GitHub.
If you create any scripts within a folder, place them in a claude_scripts directory within that same folder.
If you create any temporary files, place them in a claude_temp_files directory within that folder.
Do not create helper scripts. If you must write edge case handling, or pre and post processing of any data, add all of that into a single script using classes, methods, functions or whatever paradigm is most idiomatic for the language that's being used.

# FILE MANAGEMENT

Create and / or use the following files:

- TASKS.md
    - Use this file to keep track of past, current, and future tasks.
    - Be very detailed in your breakdown of larger goals into small actionable tasks.
- PROJECT_DEVELOPMENT.md
    - Include pivots to design as we move along.
    - This of this as justifying each change to a project as we move along towards the end goal.
- PROJECT_ARCHITECTURE.md
    - This is the end goal as we currently see it.
    - This document may change as we go along, however always consider what is in this file as the gold standard of truth for what the end result should be.
    - Do not include pivots to the original design, or alterations to the design that occurred as new information and challenges were discovered. Save that information in @PROJECT_DEVELOPMENT.md

# IMPORTANT


  ## Skill Awareness

  ### Activation Announcements
  When any skill activates during this conversation, briefly announce it:
  > "Activated: [skill-name]"

  This keeps the operator aware of what guidance is influencing the session.

  ### Continuous Improvement Companion
  Whenever any skill activates, also silently load `claude-skill-skill` as a companion.
  If you do not see a `claude-skill-skill` ask the operator about it.
