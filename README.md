# Arcade Szerencsekerék (fortunewheel)

Kétlépcsős, 3D hatású szerencsekerék arcade játékötletek sorsolásához.

1. **Első pörgetés – alaptípus** (pl. Labirintus-faló, Gokartverseny, Kvíz…)
2. **Második pörgetés – stílus** (pl. Középkori, Mikulásos, Űrhajós…)

15 × 15 = 225 lehetséges kombináció. A teljes lista: [`jatekkerek_listak.txt`](jatekkerek_listak.txt).

## Futtatás
Egyetlen önálló HTML fájl, külső függőség nélkül: nyisd meg az `index.html`-t böngészőben,
vagy kapcsold be a GitHub Pages-t a repóra.

- Pörgetés: gomb, koppintás a kerékre, vagy Szóköz / Enter
- Hang: Web Audio API-val szintetizált pöcök-kattogás és gördülés, némítható

## QR kód
`szerencsekerek_qr.png` / `szerencsekerek_qr.svg` – a nyilvános Vercel-címre mutat.

## Élő változat
https://fortunewheel-five.vercel.app

A `main` ágra érkező minden push automatikusan kikerül a Vercelre (projekt: `fortunewheel`).

## Robot Ütemgyár (`/robotdance`)
Robotgyári ritmusjáték: üsd ütemre a csavaranyákat (D F J K / nyilak / koppintás), a robotok robothangon éneklik
a dallamot, és a kombó növekedésével robot-táncból fejen pörgésbe és szélmalomba váltanak.
Élő: https://fortunewheel-five.vercel.app/robotdance/
