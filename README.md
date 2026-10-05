# 🕵️ Imposter!

A party word game for 3–12 players in the same room. Everyone gets the same secret word… except the imposter, who only knows the category. Give clues, then vote: who's faking it?

**Play:** https://atlashome88ai.github.io/imposter/ (also on the Atlas **🎮 Games** page). The same guide is in the game: tap **📖 How to play** on the start screen.

## What you need
- 3 to 12 players, one phone or tablet each, all with internet.
- About 5 minutes a round.

## Set up
1. **One person hosts:** tap **Host the game**, type your name, tap **Create game**. The host plays too.
2. A **QR code** and a **4-letter code** appear on the host's screen.
3. **Everyone else** scans the QR code with their camera (or opens the game, taps **Join as a player**, types the code), types their name and taps **Join**.
4. The host picks a **category** (or 🎲 Surprise me) and taps **Start game**.

## Playing a round
1. Tap **Tap to see your card**, read it in secret, tap **Hide my card**.
2. Most people see the **secret word**; the imposter sees **"You're the imposter!"** (with 4+ players there may be 2).
3. The host taps **Spin** to pick who goes first (never an imposter).
4. Go around the circle **twice**, one clue word each turn.
5. The host taps **Choose imposter**; everyone votes on their own phone.
6. The host taps **Big reveal**; each phone shows whether you were right.

## Tips
- Not too easy, not too hard: for "Pizza", "cheese" is too easy, "triangle" is just right.
- Imposter: listen, then say something that fits the others' clues.

## If something goes wrong
- "Can't find game": check the 4-letter code.
- A phone drops out: open the game again; it reconnects.
- The host's phone must stay on the game until you finish.

## How it works (technical)
One `index.html`, no server of its own. The host's phone runs the game; other phones connect to it directly with [PeerJS](https://peerjs.com/) (WebRTC) using the public PeerJS broker. Hosted on GitHub Pages.
