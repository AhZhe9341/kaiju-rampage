# KAIJU / SECTOR 00 · FUSION

A desktop browser action game where you control a giant monster,
destroy a city, and battle military forces and rival titans.
Build Rage through combat and unleash empowered attacks.

🎮 [Play Now](https://AhZhe9341.github.io/kaiju-rampage/)

## Features

- Three playable titans with distinct combat styles
- Three districts: Downtown, Industrial Harbor, and Residential
- Four modes: Rampage, Blitz, Survival, and Endless
- Standard and Hard difficulty with separate records
- Coordinated military movement, reinforced buildings, and escalating pressure
- Independent Energy and Rage resources
- Destructible buildings, rival titan invasions, and in-run mutations
- Chinese and English interfaces
- Configurable keyboard bindings and visual comfort settings

## Default Controls

| Input | Action |
|---|---|
| WASD / Arrow keys | Move |
| Mouse | Aim |
| Left click | Light attack combo |
| Hold and release right click | Charged heavy attack |
| Space | Dodge |
| E | Spend Energy to activate your ultimate |
| R | Activate Rage when the Rage meter is full |
| Q | Execute a weakened rival at close range |
| Tab | Open pending mutation choices |
| Esc | Pause / Resume |
| H | Show / Hide control hints |
| F8 | Toggle performance statistics |

Keyboard bindings can be adjusted in Settings.

## Game Modes

| Mode | Objective |
|---|---|
| Rampage | Destroy 85% of the city with no time limit |
| Blitz | Destroy 50% of the city within 180 seconds |
| Survival | Survive for 180 seconds |
| Endless | Survive escalating threats for as long as possible |

## Energy and Rage

Energy powers your ultimate ability.

Rage builds through effective combat and destruction.
At full Rage, press R to enter a 15-second empowered state,
followed by 5 seconds of overheat.

Activating Rage preserves your Energy. During Rage,
ultimates still consume Energy and use their empowered versions.

Military Energy Centers are tactical power facilities. Destroying one disrupts
military power for 15 seconds and grants only the normal destruction-based Rage.
It does not unlock Rage mode, refill Energy, or grant special Rage.

## Difficulty and Tactics

Choose Standard or Hard during deployment. Both increase alert through elapsed
time, destruction, and military defeats. Hard escalates faster, has a larger
reinforcement cap, shorter breaks, and scarcer healing.

Heavy melee is more effective against reinforced tall buildings and landmarks.
Energy regenerates slowly; effective hits are the primary source. Building
destruction grants less Rage than combat. Existing enemies remain active during
respite, while heavy targeting and new reinforcements pause. Prolonged disengagement
can trigger an airstrike with a three-second warning.

Supply trucks restore 10% HP on Standard or 8% on Hard. Endless medical caches
restore 6% or 4% respectively and remain unconsumed at full health.

New records are separated by difficulty; earlier records are retained in local storage.

## How to Play

Open the online game in a desktop browser with a keyboard and mouse.

Alternatively, download `index.html` and open it locally.
No installation, dependencies, or build step is required.

## Technology

Built as a single HTML file using:

- Vanilla JavaScript
- HTML5 Canvas 2D
- Web Audio API
- Isometric projection and procedural modeling
- Object pooling and offscreen rendering caches

Hosted on GitHub Pages.

## Project Notice

This is an unofficial fan-made prototype inspired by classic
monster cinema. It is not affiliated with or endorsed by the
relevant rights holders.

Referenced characters and trademarks belong to their respective owners.
