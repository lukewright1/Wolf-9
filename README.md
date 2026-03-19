# 🐺 Back 9 Wolf
 
> *"The most dangerous animal on the golf course isn't a gator in the water hazard. It's your buddy Dave going Lone Wolf on hole 17 when he's already up 6 points."*
 
---
 
## What is this?
 
A web app for scoring the **Wolf** golf game — the greatest betting game ever invented by people who weren't satisfied with just losing money on their handicap.
 
You and your degenerate golf friends pick a Wolf on each hole, someone goes Lone Wolf at the worst possible time, and somehow it all comes down to the last putt on 18. Every. Single. Time.
 
## How to play
 
1. **Hole 1 (or 10):** Everyone hits. Lowest score sets the wolf order. Ties broken by who holed out first, which causes its first argument of the day.
 
2. **Each hole:** The Wolf watches everyone tee off, one by one. After each shot they decide: *take this guy as a partner, or keep watching?* 
 
3. **The Wolf either:**
   - **Picks a partner** — Wolf + buddy vs the other two. 1 point each if they win.
   - **Goes Lone Wolf** — Wolf vs everybody. Win = **3 points**. Lose = 1 point to each of the others. This is where friendships are tested.
   - **Gets Forced Wolf** — In a 4-player game, every player must go lone wolf at least once. The app enforces this automatically so Dave can't weasel out of it.
 
4. **Settlement:** $1 per point, head-to-head between all players. Venmo requests sent before the parking lot clears.
 
## Features
 
- 🏌️ **Full Wolf scoring** — partner mode, lone wolf, forced wolf, the whole thing
- ⛳ **338 US golf courses** built-in — Pebble Beach to your local muni
- 🔍 **Live course search** via Golf Course API — finds basically everything
- 🏆 **Results & settlement** — exactly who owes who, down to the dollar
- 📱 **iPhone-optimized** — add to home screen, plays like a native app
- 🐺 **Player profiles** — custom colors, photos, the works
- 📋 **History** — so you can prove that yes, Tim does owe you $14 from last month
- 🌙 **Dark mode** — for those early tee times when you haven't fully woken up yet
 
## How to use
 
Open it. Add players. Hit Start. The app tells you who's Wolf, who owes whom, and when to go Lone Wolf (hint: never on a par 3 when you're shaky with the 8-iron).
 
## The Rules Nobody Agrees On
 
This app implements the *correct* rules. If your group plays differently, you're wrong, but the course search still works great.
 
## Tech
 
One HTML file. No framework. No build step. No `node_modules` folder eating your hard drive. Just vibes and vanilla JavaScript.
 
```
index.html  ← the whole thing
```
 
## Contributing
 
Found a bug? A course with wrong pars? Did Dave find a loophole in the Forced Wolf rule again?
 
Open an issue. Or just fix it and send a PR. The whole app is one file, how hard can it be.
 
---
 
*Built for the Back 9 at Los Lagos, Costa Mesa, CA — where the greens are fast, the bets are real, and someone always goes Lone Wolf on 18.*
 
