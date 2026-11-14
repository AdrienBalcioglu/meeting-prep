# Meeting Prep — a skill for Claude

A Claude skill that briefs you before a meeting: who is in the room, what happened last time, what is still open, and what to ask.

**[Website](https://adrienbalcioglu.github.io/meeting-prep/)**

- **The meeting**: purpose and expected outcome
- **The people**: role, last exchange, who is waiting for what
- **The history**: last decisions and open commitments, each with its date
- **The questions**: three to five, specific to this meeting

It works with whatever is connected: calendar, email, chat, tasks. A missing source means a skipped section, never a guess.

## Install

### Claude Code

```bash
git clone https://github.com/AdrienBalcioglu/meeting-prep.git ~/.claude/skills/meeting-prep
```

### Claude (claude.ai / desktop)

1. Download [`SKILL.md`](SKILL.md).
2. Put it in a folder named `meeting-prep` and zip the folder.
3. In Claude, go to **Settings → Capabilities → Skills** and upload the zip.

## Use

```
/meeting-prep
```

or just ask: *"Brief me on my 3pm."*

You can also say: *"Brief me on every meeting today"*.

## Principles

- **Read-only.** It never sends, replies, accepts or archives anything.
- **No invention.** Every claim comes from a source, with its date.
- **Private.** Nothing is stored; everything is read fresh on each run.
- **Short.** One page.

## License

[MIT](LICENSE) © 2026 Adrien Balcioglu
