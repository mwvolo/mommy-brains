# Mommy Brains Arrives

A Halloween countdown for Mommy Brains. The page lives at https://mwvolo.github.io/mommy-brains/.

## Changing the odds

The "Will She Make It?" dials read `settings.json`. Edit it on GitHub (the pencil icon), commit, and the page picks it up within a minute or two. Visitors can move the dials on their own screen, but only this file changes what everyone sees.

| Setting | Values | Effect on the odds |
|---|---|---|
| `alarm` | `true` / `false` | Alarm set for 5:30: +6 |
| `bag` | `true` / `false` | Bag packed: +8 |
| `tank` | `true` / `false` | Kelly's tank is full: +4 |
| `candy` | `true` / `false` | Candy promised: +5 |
| `wellsee` | `true` / `false` | Heard a "we'll see": -12 |
| `weather` | `"clear"`, `"rain"`, `"fog"`, `"storm"` | Weather on I-10: +3 to -10 |
| `resolve` | 0 to 100 | Mommy Brains' resolve: -10 to +10 |
| `temptation` | 0 to 100 | Back-road temptation: 0 to -6 |
| `volatility` | `"calm"`, `"restless"`, `"possessed"` | How much the number wanders |
| `arrived` | `true` / `false` | She's here: pins the odds at 100% and parks the blue car in the driveway |

Map data © OpenStreetMap contributors. Routes by Valhalla.
