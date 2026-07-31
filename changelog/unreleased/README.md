# Unreleased

Changes since v0.1.5. The version number is assigned at release, when this folder is renamed.

- [2026-07-30] Workspace Memory: an agent keeps long-term notes between Sessions under `agent_state/memory/` — topic files per Workspace and one shared index, with only the index entering the context and bodies read on demand. Scope is Project + Agent + Workspace, a temporary Workspace gets none, and the Web App gains a Memory tab that keeps the index in step with a rename or delete. Existing agents are unchanged until they adopt the `{{MEMORY}}` placeholder. ([details](2026-07-30-workspace-memory.md))
