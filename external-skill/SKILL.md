---
name: External Skill
description: A skill defined outside of .mintlify/skills, symlinked in to test directory symlink resolution.
version: 1.0.0
---

This skill lives in the `external-skill/` directory at the repo root and is symlinked into `.mintlify/skills/` as `external-skill`.

<!-- MARKER: external-skill-resolved-via-symlink -->
If you see this marker in the uploaded skill, the out-of-contentDirectory symlink resolution works.
