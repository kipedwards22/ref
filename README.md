# REF — AI Darts Referee (playable prototype)

**Play it:** https://kipedwards22.github.io/ref/

A phone becomes the referee. Prop it up, play darts, and the AI keeps score,
freezes disputed calls, and awards the winner.

In this prototype the camera vision is simulated: tap the board where the
dart landed and the AI ref makes the call. Everything downstream is real —
confidence per dart from true board geometry (calls near a wire score low
and auto-freeze for review), challenges with frozen-frame zoom and two
camera angles, human override, player votes (split vote → the AI call
stands), 501/301 with double-out and checkout suggestions, custom house
rules with an auto-generated scoreboard, and a match report with the full
dispute log.

Single self-contained HTML file — no build, no dependencies. Open
`index.html` or the link above.
