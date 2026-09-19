# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Git identity

Always configure the git identity of the session machine before making any commit:

```bash
git config user.name "Young-Ho Kim"
git config user.email "yghokim@younghokim.net"
```

Run these at the start of every session (and after any fresh clone or container
restart), and verify with `git config user.name` / `git config user.email`.
All commits in this repository must be authored by
`Young-Ho Kim <yghokim@younghokim.net>` — never by a default or agent identity
such as `Claude <noreply@anthropic.com>`.

## Commit messages

Do **not** add Claude (or any AI assistant) as a co-author. Commit messages must
not contain trailers such as:

```
Co-Authored-By: Claude <noreply@anthropic.com>
```

Keep commit messages plain and descriptive: a short imperative subject line, and
a body only when it adds context. No AI attribution, badges, or generated-by
footers.
