# Cursor Commands — 4 real ones I use every day

Battle-tested custom commands that save me hours while building production apps with Cursor.

Just copy the `.cursor/commands/` folder into any project (or clone the repo and copy it over).

https://github.com/MohamadShamchi/cursor-commands/assets/16661478/xxx ← replace with a nice screenshot or short gif later

### The Commands

| Command               | What it does                                                                                  | When I run it                    |
| --------------------- | --------------------------------------------------------------------------------------------- | -------------------------------- |
| `senior-review`       | Brutal senior engineer code review — perf, a11y, security, tech debt, refactoring suggestions | After every major change         |
| `build-production-ui` | “Implement this screen like a staff engineer” → production-ready React/TSX on the first try   | When starting a new screen/flow  |
| `ux-audit`            | Instant PM + UX audit with redesign ideas, A/B test suggestions, accessibility wins           | Before design review or polish   |
| `wrap-up-session`     | End-of-day ritual → writes `SESSION_SUMMARY.md`, organizes scratch files, suggests git commit | Last thing before I close Cursor |

### Quick install

```bash
# One-liner (macOS/Linux)
curl -L https://github.com/MohamadShamchi/cursor-commands/archive/main.zip -o cursor-commands.zip && \
unzip cursor-commands.zip && \
cp -r cursor-commands-main/.cursor ~/ && \
rm -rf cursor-commands.zip cursor-commands-main
```

Or just drag the .cursor folder from this repo into any project.
MIT licensed → steal, tweak, improve, share your own!
Made by @MohamadShamchi — reply with your best commands, I’ll add the good ones with credit ⭐
