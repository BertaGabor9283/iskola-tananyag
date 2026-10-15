# Tananyag oldal

Egyetemi tárgyak tananyaga hetekre bontva (előadás, gyakorlat, számonkérés).
Statikus oldal, [Quartz](https://quartz.jzhao.xyz) alapon.

## Szerkesztés

- Minden tárgy egy mappa: `content/<tárgy>/`
- `index.md`: tárgyleírás, heti ütemterv, értékelés
- `hetek/het-01.md … het-12.md`: hetenkénti oldalak (előadás, gyakorlat, számonkérés, anyagok)
- A PDF-ek és egyéb anyagok a `content/<tárgy>/hetek/` mellé vagy a `content/<tárgy>/anyagok/` mappába kerülnek

## Helyi előnézet

```bash
npm ci
npx quartz build --serve
```

## Publikálás

A `main` ágra való push után a `.github/workflows/deploy.yaml` automatikusan építi és közzéteszi az oldalt GitHub Pages-en.
A `quartz.config.yaml` `baseUrl` mezőjét a saját GitHub-felhasználónévre kell cserélni.
