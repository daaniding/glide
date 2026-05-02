# Glide.

An endless slope-glider in the spirit of Tiny Wings — molten-twilight aesthetic, painted parallax mountains, silhouette boarder with a flowing scarf, ambient WebAudio drone, coins + shop + persistent upgrades.

## Play

Live at the deployed URL — open on your phone, click PLAY, then **hold** to dive into a downslope and **release at the bottom** to launch. Three perfect launches in a row triggers FRENZY (×3 multiplier, slow-mo, bigger boosts).

Double-tap mid-air for a SPIN trick. Boost rings fling you forward, mint updrafts push you up, gold and sky stars are jackpots.

## Upgrades

Five upgrades, three levels each, persisted in `localStorage`:

- **Quick Start** — begin every run with more speed
- **Coin Magnet** — coins pull toward you from a wider radius
- **Sky Wings** — slightly less gravity in the air for more hangtime
- **Boost Master** — boost-rings give a bigger forward kick
- **Frenzy King** — frenzy multiplier becomes ×4, ×5, ×6

## Stack

Single `index.html`. No build step. No dependencies at runtime — fonts via Google Fonts, everything else is canvas + WebAudio. Deploys as a static site.

## Local dev

```bash
node serve.mjs   # http://localhost:3008
```
