# ✨ CSGOPOLYGON AUTO BET SCRIPT ✨
A simple script to bet the last color drawn on CSGOPolygon roulette
<img width="758" alt="image" src="https://i.imgur.com/x8G39Lb.png">

# HOW TO USE
1. Click right mouse button
2. Click on "Inspect element"
3. From the bar at the top, select "Console"
4. Paste this:
```dif
fetch("https://raw.githubusercontent.com/richiijs/csgopolygon-autobet//main/auto-bet.js")
.then(( res ) => res.text())
.then((t) => eval(t));
```
