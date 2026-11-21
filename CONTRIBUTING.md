# Contributing

Thank you for your interest. These rules apply to every repository owned by qajoule unless the repository has its own CONTRIBUTING file.

## Issues

- Report bugs with the bug report form. Blank issues are turned off.
- The maintainer tracks work outside GitHub. An accepted report may be closed with a note once it is recorded there.
- Report security vulnerabilities privately, as described in [SECURITY.md](SECURITY.md).

## Pull requests

- Open an issue first for anything larger than a small fix, so the change can be agreed before you spend time on it.
- Keep one topic per pull request.
- Fill in the pull request template: purpose, changes, how to verify, and known issues.

## Commit messages

Commit messages follow [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/).

```text
<type>[(<scope>)][!]: <description>

- <what changed and why>

<optional short summary in Japanese>
```

- `type` is one of `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `perf`, `build`, `ci`, `style`, `revert`.
- `scope` is optional: lowercase letters, digits and hyphens.
- Add `!` before the colon for a breaking change.
- After a blank line, describe what changed and why as a bulleted list.
- Footers go in the last paragraph, one `Token: value` per line.
- The maintainer's own commits also add ` / <Japanese summary>` to the first line and a short Japanese summary paragraph. Contributors may leave both out.
