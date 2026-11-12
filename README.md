# Give Claude Code its own phone (Bland skill)

**Install it by pasting this into Claude Code:**

```
Install the connecting-claude-code-to-bland skill from https://github.com/christianjohnston-ai/claude-code-bland-phone : save its SKILL.md as ~/.claude/skills/connecting-claude-code-to-bland/SKILL.md exactly as written (create the folders, replace an older copy if there is one). Do not run anything else yet. Tell me when it is saved.
```

Claude Code calls you when it needs a decision, then keeps working with your answer. With one more step, the voice on
the phone can ask Claude Code questions while you talk, and it can hand the call to you once it reaches the right person
(for example, the one shop that has your part in stock).

## What you need

- Claude Code
- A free account at [bland.ai](https://www.bland.ai) and its API key, saved in a text file on your computer (do not paste
  the key into the chat; the skill moves it somewhere safe)
- About $0.14 a minute of call time once the free credits are used

## Set it up

1. Paste the install prompt above.
2. Then paste: `Use the skill at ~/.claude/skills/connecting-claude-code-to-bland/SKILL.md to set me up. Read it first, then do Part 1.`
3. Any time after that, say "give me a call".

Everything Claude will do is in [SKILL.md](./SKILL.md). Read it first if you want to see exactly what runs.

MIT licensed. Made by [@ohyesinvest](https://www.instagram.com/ohyesinvest).
