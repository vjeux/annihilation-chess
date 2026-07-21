# ⚔️ Annihilation Chess — Rules

A chess variant where **the king is just an ordinary piece**. There is no check and no
checkmate. You win by **capturing every single enemy piece**.

## The Board

Standard 8×8 chess board, standard starting position, standard piece movement — pawns,
knights, bishops, rooks, queens, and kings all move exactly as in normal chess. Castling,
en passant, and pawn promotion all work normally.

## The King Is Not Special

This is the whole twist:

- **There is no check and no checkmate.** The concept simply doesn't exist.
- The king is a **normal fighting piece**. It can be captured like anything else, and after
  it's gone you keep playing with your remaining army.
- You can move your king **onto an attacked square** if you want — it's a legal move. That's
  your decision and your risk.
- You may **castle** whenever the squares between king and rook are empty and neither piece
  has moved — you can even castle "through" or "into" squares an enemy attacks, since attacks
  on the king no longer matter.

## How to Win

**Capture the entire enemy army.** The last player with any pieces left on the board wins.
Because there's no checkmate, total annihilation is the *only* way to win.

## Draws

- **Stalemate** — you have pieces but no legal move.
- **50-move rule** — no capture or pawn move for a long stretch.

## Strategy Notes

- Material is everything. Every trade matters because you need to clear the *whole* board.
- Your king is a useful attacker in the endgame — use it. There's no reason to keep it safe.
- The enemy king is worth capturing not for a "win," but because it's a strong piece removed
  from their army.

## The Bot

The opponent is a ~1000-rated bot. It plays normal chess for material, treats its king as a
fighting piece, and — once it's far enough ahead — actively **hunts your last pieces**,
driving them toward the edge to finish the annihilation. It still makes human-like mistakes.
