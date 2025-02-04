# Feature Implementation Summary

## Changes Made:
- Added a **turn-based multiplayer mode** allowing two players to take turns flipping cards.
- Implemented a **turn indicator (`turnIndicator`)** to show whose turn it is.
- Introduced **score tracking (`player1Score` & `player2Score`)** to count matches for each player.
- Updated the logic in `checkForMatch()` to:
  - Award a point to the current player for a correct match.
  - Switch turns if no match is found.
- Created a **win condition** that announces the player with the most matches.

## Testing:
- Verified that players **alternate turns correctly**.
- Ensured score updates **only when a match is found**.
- Checked that the game announces the **winner or a tie** at the end.

Feature successfully added and verified!
