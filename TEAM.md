# God's Eye View — privé teamkopie

Los van Echo. Los van `sanctuary-site`. Niet de Unity-game.

Bron: [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) (MIT).

## Wat dit is

Referentie voor de commandocentrale-ideeën in de Sanctuary-game:

- top-down / God-view over het station
- tracks van miners / scheepjes
- cockpit-gevoel

De Cesium-app zelf gaat **niet** de Unity-wereld in. Ideeën wel.

## Wie raakt wat aan

| Wie | Dit repo | Sanctuary-site | Unity |
|-----|----------|----------------|-------|
| Wesley / team | ja | via Claude | via Echo |
| Echo | alleen als Wesley het vraagt | nee | ja |
| Claude | nee | ja | nee |

## Bron binnenhalen (eenmalig, op je pc)

Repo is expres leeg aangemaakt als privé-schil. Op je pc:

```bash
git clone --mirror https://github.com/bilawalsidhu/gods-eye-view.git gev-src
cd gev-src
git remote set-url origin https://github.com/WeSs1982/gods-eye-view.git
git push --mirror origin
```

Daarna de mirror-map weggooien. Licentie `LICENSE` van upstream blijft staan.

## Niet doen

- Niet mergen in `sanctuary-site`
- Niet onder de Echo-gametak zetten
- YouTube-pipeline en lesmaker niet aanraken
