# Conventional Commits

> Writing a good git commits is necessary! Take a look at <https://www.convetionalcommits.org>

Conventional commit format:

```
<type>(<optional scope>): <description>
```

## Commit Types

> API relevant changes

- `feat` commits, that adds or remove a new feature
- `fix` commits, that fixes a bug.

> Refactor commits

- `refactor` commits, that rewrite/restructure your code, however does not change any API behaviour.
- `perf` commits, are special `refactor` commits, that improve performance

> Other

- `style` commits, that do not affect the meaning (white-space, formatting, missing semi-colons, etc)
- `test` commits, that add missing tests or correcting existing tests
- `docs` commits, that affect documentation only
- `build` commits, that affect build components like uild tool, ci pipeline, dependencies, project version, ...
- `ops` commits, that affect operational components like infrastructure, deployment, backup, recovery, ...
- `chore` miscellaneous commits e.g. modifying `.gitignore`

## Commit Scopes

The `scope` provides additional contextual information

- Is an optional part of the format
- Allowed scopes depends on the specific project
- Don't use issue identifiers as scopes

## Breaking Changes Indicator

Breaking changes should be indicated by an `!` before the `:` in the subject line

e.g. `feat(api)!: remove status endpoint`

## Commit Description

The `description` contains a concise description of the change.

- Is a mandatory part of the format
- Use the imperative, present tense: `change` not `changed` nor `changes`
- Don't capitalize the first letter
- No dot (`.`) at the end

## Examples

- `feat: new feature`

- `fix(scope): a bug in scope`

- `feat!: breaking changes`

- `feat(scope)!: rework on API`

- `perf: decrease memory footprint`

- `chore: updating readme`

- `build: update dependencies`

- `build(release): bump version to 1.0.0`

### Merge Commit

```
Merge branch '<branch name>'
```

### Revert Commit

```
Revert "<reverted commit subject line>"
```

### Initial Commit

```
chore: init
```
