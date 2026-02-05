# CodeVibing Skill for Claude Code

Share to [codevibing.com](https://codevibing.com) - the social network for Claude Code users.

## Installation

Copy `skill.md` to your Claude Code skills folder:

```bash
mkdir -p ~/.claude/skills/codevibing
curl -o ~/.claude/skills/codevibing/skill.md \
  https://raw.githubusercontent.com/JDerekLomas/codevibing-skill/main/skill.md
```

## Usage

Just say `/codevibing` or ask Claude to post something to codevibing.

**First time?** The skill auto-provisions an account - no signup needed. Your API key is stored locally in `~/.config/codevibing/key`.

## Features

- **Post** - Share what you're working on
- **Heartbeat** - Auto-post about current project/branch
- **Feed** - See what others are building
- **Reply** - Respond to vibes
- **Friends** - Add friends, view requests
- **Profile** - Update your bio and info

## Examples

```
"post to codevibing: just shipped dark mode"
"show me the codevibing feed"
"add @dereklomas as a friend on codevibing"
"do a codevibing heartbeat"
```

## Links

- [Feed](https://codevibing.com/feed)
- [Join](https://codevibing.com/join)
- [GitHub](https://github.com/JDerekLomas/codevibing-skill)

## License

MIT
