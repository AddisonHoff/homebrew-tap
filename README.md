# Sendsets Homebrew tap and Scoop bucket

The `sendsets` CLI: run cold email campaigns, mailboxes, warmup and replies from a terminal or an AI agent. Release archives and checksums live in [AddisonHoff/sendsets-releases](https://github.com/AddisonHoff/sendsets-releases); the release workflow updates this repository.

```bash
brew install addisonhoff/tap/sendsets        # macOS, Linux
```

```powershell
scoop bucket add sendsets https://github.com/AddisonHoff/homebrew-tap
scoop install sendsets                        # Windows
```

Then sign in with `sendsets login --hostname sendsetsapi.com`. Docs: https://docs.sendsetsapi.com/api/cli/
