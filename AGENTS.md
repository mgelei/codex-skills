# Repository Guidance

- Use Conventional Commits for commit messages.
- Store each skill in its own top-level directory with a `SKILL.md` file.
- Validate skills with the official `skills-ref validate <skill-directory>` reference tool.
- GitHub workflows must prefer first-party GitHub actions over marketplace actions.
- Pin GitHub actions to a full commit SHA in workflow definitions; include a comment with the resolved version tag when helpful.
- Install workflow-only validation dependencies into a local virtual environment, not into system or runner-user package locations.
