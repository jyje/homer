# Git Commit Helper Examples

Below are examples of commit messages following the project policy.

## Feature addition

```markdown
✨ feat(n8n): add n8n application

Add n8n workflow automation application to the cluster.
```

## Intentional functional configuration change

```markdown
🛠️ fix(nfs): rollback health probes and chart rename to fix distroless image compatibility

Revert recent changes including health probes and chart renaming because the
distroless image lacks 'sh' and other shell utilities required for probes.
```

## Routine maintenance

```markdown
🔧 chore(helm): remove deprecated Helm chart versions and clean up configuration files

Remove old chart versions and clean up unused configuration files for homer applications.
```

## Bug fix

```markdown
🐛 bug(open-webui): resolve inconsistencies in git commit policy rule

Fix three bugs in the git commit policy rule:
1. Translate Korean text to English to match the 'Always English' policy
2. Clarify gitmoji mapping conflicts.
3. Add missing types to the Type list.
```

## Dependency update

```markdown
⬆️ dep(open-webui): update chart to 10.2.1 from 8.10.0

Upgrade open-webui Helm chart to latest version.
```

## Refactoring

```markdown
♻️ refactor(nfs): rename custom Helm chart with -jyje suffix and add health probes

Rename Helm chart directory and add health probe configurations.
```

## Security

```markdown
🔐 security(open-webui): add CORS_ALLOW_ORIGIN environment variable for enhanced security

Configure CORS settings to restrict allowed origins.
```

## Typo fix

```markdown
✏️ typo(docs): fix typo in gitmoji standard reference

Correct "gitmodi" to "gitmoji" in documentation.
```

## Skill update

```markdown
🔧 chore(git-commit-helper): add git log search step when recommending type

Search last 10 commits and last 10 of the chosen type to keep wording and style consistent with recent history. Do not use docs type for skill updates.
```

```markdown
🛠️ fix(git-commit-helper): stop adding Co-Authored-By in commit message

Cursor adds co-author automatically; remove from format and examples to avoid duplicate.
```
