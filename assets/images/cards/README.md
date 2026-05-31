# Karten-Grafiken

Alle Spielkarten als PNG, umbenannt auf web-sichere ASCII-Slugs (keine Leerzeichen,
Umlaute oder Klammern – wichtig für GitHub Pages).

## Namens-Konvention

Jeder Charakter erscheint mit **einer** Kartenseite:

| Suffix         | Kartentyp           | Erkennungsmerkmal auf der Karte                    |
|----------------|---------------------|----------------------------------------------------|
| `…-staerke.png`| Kämpfer-Karte       | Stärke + Gäng-Name oben links (z. B. „8 Bronko")   |

Beispiel: `der-baenker-staerke.png` (Stärke „2 Cobra").

> **Hinweis:** Die früheren 32 charakterbezogenen `…-lp.png`-Karten wurden entfernt.
> Die Lebenspunkte sind jetzt der **Bronko-LP-Stapel** → siehe `lp/` unten.

## `lp/` – Der Bronko-LP-Stapel (Lebenspunkte)

Jeder Spieler hat seinen Bronko als offenen 10-Karten-Stapel à 10 LP:
`lp-100.svg` (oben, unversehrt) … `lp-10.svg` (unten, kaputt geprügelt) = 100 LP.
Bei Schaden (auf volle 10 aufgerundet) wirft man die oberste(n) Karte(n) ab.

> **PLATZHALTER:** Die `lp-*.svg` sind rein prozedural generierte Platzhalter.
> Für die finale Optik einfach durch echte Grafiken ersetzen (bei Wechsel auf `.png`
> die `src`-Pfade in `hofregeln/index.html` mitziehen).

Die zwei Spezial-Charaktere haben nur **eine** Karte (kein LP-Pendant):
`dr-nar-kose.png`, `duenenwolf.png`.

> Hinweis: Das Original-Paar „Riemenpiedler" war umgekehrt benannt
> (`Riemenpiedlers.png` = Stärke, `Riemenpiedler.png` = LP) und wurde korrekt zugeordnet.

## `special/` – Token- & Spielkarten (keine Charaktere)

- `bronko-blut.png`  – Bronko-Blut-Karte (geht an den Rundensieger)
- `donko-haufen.png` – Donko-Haufen-Karte (markiert den Donko)
- `mit-weste.png`    – Weste-Karte, Seite „Mit Weste kämpfen!"
- `ohne-weste.png`   – Weste-Karte, Seite „Ohne Weste kämpfen!"
- `flucht-1.png` … `flucht-3.png` – die drei Fluchtkarten
- `orden.png`, `orden-2.png` … `orden-5.png` – die fünf Bronko-Orden
- `rueckseite.png`   – Kämpfer-Rückseite (B&D-Logo)
- `rueckseite-lp.png`– Bronko-LP-Rückseite (Faust)
