# Transzfer

Egyszerű, offline-képes lokáció-transzfer app Zebra kézi terminálokhoz (és bármilyen böngészőhöz).

## Fájlok
- `index.html` – nyitóoldal, innen érhető el mindkét verzió
- `transzfer.html` – Acumatica (Inventory ID) alapú verzió, SAP-kód kereszthivatkozással
- `transzfer-sap.html` – SAP (Item No.) alapú verzió

## Feltöltés GitHubra és publikálás (GitHub Pages)

1. Hozz létre egy új repót a GitHubon (pl. `transzfer`).
2. Töltsd fel ide ezt a 3 fájlt (Add file → Upload files), majd Commit.
3. Menj a repo **Settings → Pages** menüpontjára.
4. **Source**: válaszd a `main` branch-et, `/ (root)` mappát, majd **Save**.
5. Pár másodperc/perc múlva megkapod az élő linket, valahogy így:
   `https://<felhasznalonev>.github.io/<repo-nev>/`

Ezt a linket nyisd meg a Zebra terminál böngészőjében — onnantól bármikor elérhető, internet nélkül is működik (miután egyszer betöltődött), és a "Hozzáadás a kezdőképernyőhöz" opcióval ikonként is kirakhatod.

## Frissítés
Ha módosítasz valamit, csak töltsd fel újra ugyanazokat a fájlneveket (felülírással) — a GitHub Pages automatikusan frissül.
