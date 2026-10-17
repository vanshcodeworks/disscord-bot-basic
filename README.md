# Discord Bot (basic)

Minimal Discord bot built on `discord.js`.

## Setup

```bash
npm install
```

Add your bot token and prefix to `.env` (git-ignored), then:

```bash
node index.js
```

## Files

```
index.js       bot entrypoint, event handlers
package.json
```

## Notes

Deliberately minimal - no command framework, no database, no configuration
beyond the token and prefix. Useful as a starting point rather than as a
finished bot.