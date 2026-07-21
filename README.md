# ⚔️ Annihilation Chess

A chess.com-style chess variant where **the king is just an ordinary piece** — no check, no
checkmate. The only way to win is to **capture every single enemy piece**.

Play against a ~1000-rated bot.

👉 **[Read the full rules](./RULES.md)**

## Features

- ♟ **Full legal chess engine** — standard movement, castling, en passant, promotion.
- ⚔️ **The annihilation twist** — no check/checkmate; the king is a normal capturable piece;
  win only by clearing the enemy's entire army.
- 🤖 **~1000-rated bot** — plays for material, uses its king actively, and hunts down your
  last pieces to close out the game, with human-like imperfection.
- 🎨 **chess.com-style UI** — the real "neo" piece set, green/cream board, drag-and-drop or
  click-to-move, legal-move dots, last-move highlights, live piece counts.
- 🏹 **Full controls** — right-click-drag arrows, right-click square highlights, **premoves**,
  promotion picker, move list, board flip, resign, sounds, and an in-page rules panel.

## Running it

A single self-contained HTML file — no build step, no dependencies, no network (piece images
are embedded). Just open it:

```bash
open index.html      # macOS
# or
npx serve .
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire game (engine + bot + UI, self-contained) |
| `RULES.md` | Full rules of the variant |
| `vercel.json` | Static-deploy config |
