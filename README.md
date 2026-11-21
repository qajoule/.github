# .github

Default community health files for repositories owned by qajoule. GitHub uses a file from here only when a repository has no file of the same kind.

| File | Purpose |
| - | - |
| `CONTRIBUTING.md` | How to report issues, open pull requests and write commit messages |
| `SECURITY.md` | How to report a vulnerability privately |
| `.github/ISSUE_TEMPLATE/` | The bug report form; blank issues are turned off |
| `.github/pull_request_template.md` | The pull request template |
| `.github/workflows/commit-msg.yml` | A reusable workflow that checks the commit messages of a pull request |

See [Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

Workflows are not inherited like the files above. A repository uses the commit message check by adding `.github/workflows/commit-msg.yml`:

```yaml
name: Commit messages
on: pull_request
jobs:
  commit-msg:
    uses: qajoule/.github/.github/workflows/commit-msg.yml@main
```
