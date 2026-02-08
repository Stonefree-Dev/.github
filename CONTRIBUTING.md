# Contributing

## Commit Convention

[Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>: <description>

[optional body]
```

### Types

| Type | Usage |
|------|-------|
| `feat` | New feature or content |
| `fix` | Bug fix |
| `docs` | Documentation only |
| `refactor` | Code restructuring |
| `chore` | Maintenance, config, CI |
| `slide` | Presentation materials |

### Examples

```
feat: Add session 2 slides for parking_lot core architecture
docs: Update jam log with 3rd session notes
fix: Correct PAM-3 encoding overhead calculation
slide: Add speaker script for session 1
chore: Update workflow to strip dates from titles
```

### Rules

- Use English for commit messages
- Use imperative mood ("Add" not "Added")
- Keep the subject line under 72 characters
- Reference discussion numbers when relevant: `docs: Update notes (#3)`

## Branch Naming

```
feature/<topic>       # New content or feature
fix/<description>     # Bug fixes
docs/<description>    # Documentation updates
```
