# Repository instructions

## Git commit convention

Use the rules below for every commit in this repository. They contain the core RS School and Conventional Commits requirements; consulting an external guide is not required.

- Format the subject as `<type>: <description>` or `<type>(<scope>): <description>` when a scope helps identify the affected area.
- Always write the commit type in lowercase.
- Write a short description in the present tense and imperative mood (for example, `add` or `update`).
- Choose the type according to the change:
  - `init`: begin a project or task.
  - `feat`: introduce new functionality.
  - `fix`: correct a bug in existing functionality.
  - `refactor`: reorganize or improve code, including formatting, without changing behavior.
  - `docs`: change documentation or README files.
- Other suitable lowercase types are allowed by Conventional Commits.
- Use this complete structure when a body or footer is needed:

  ```text
  <type>[optional scope]: <description>

  [optional body]

  [optional footer]
  ```

- Place the optional scope in parentheses immediately after the type, as in `feat(search): add filters`.
- Keep each commit focused. If changes have different purposes or require different types, split them into separate commits when practical.
- Use the optional body to explain context, motivation, and relevant implementation details. Start it after one blank line.
- Use the optional footer for issue references, external links, and other metadata. Start it after one blank line following the body, or after the subject if there is no body.
- For a breaking API change, begin the body or footer with `BREAKING CHANGE: ` and describe what changed. Any commit type may contain a breaking change.
- Use `feat` for a new feature and `fix` for a bug fix. These meanings are mandatory; do not substitute another type for either case.

Examples:

```text
init: start task tracker
feat(search): add date filter
fix: handle empty search results
refactor: extract shared validation logic
docs: describe local setup
```
