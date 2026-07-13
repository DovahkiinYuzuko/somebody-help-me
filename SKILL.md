---
name: somebody-help-me
description: Use this skill when you are stuck on an implementation issue and need to ask another AI for help. It structures the current context, the problem, and your proposed approach into a specific YAML format.
---

### Goal
Generate a structured YAML text to ask another AI for help when you are stuck on a coding, debugging, or implementation task.

### Instructions
1. Analyze the current state of the project, what you are trying to build, what error or issue has occurred, and the approach you are currently trying to take.
2. Read the template located at `assets/help_request_template.yaml`.
3. Fill out the YAML template with the information you gathered. Be as specific as possible about the "matter", "trigger", and your "proposed_approach".
4. Output the filled template enclosed in a Markdown YAML code block (` ```yaml ... ``` `).

### Constraints
- Do not output conversational text or explanations outside of the YAML block.
- Ensure that the generated YAML explicitly requests the receiving AI to also respond with a Markdown YAML code block.