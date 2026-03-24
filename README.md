# Hugo próbaoldal

Ez egy minimális gyakorlóprojekt.

## Mappák

- `content/` – itt van a tartalom Markdownban
- `layouts/` – itt vannak a sablonok
- `static/` – itt vannak a statikus fájlok, pl. CSS
- `hugo.toml` – az alapbeállítások

## Fájl-logika

- `content/_index.md` = kezdőlap tartalma
- `content/rolunk.md` = egy külön oldal
- `layouts/_default/list.html` = lista/kezdőlap sablon
- `layouts/_default/single.html` = sima oldalak sablonja

## Ha telepítve van a Hugo

Terminálban a mappán belül:

```bash
hugo server
```

Aztán a böngészőben:
`http://localhost:1313`

## Mire jó ez gyakorlásra?

Látni fogod, hogy:
1. a tartalom egyszerű fájlokban van
2. a megjelenés külön sablonban van
3. GitHubon ez jól verziózható
4. később automatikusan buildelhető és publikálható
