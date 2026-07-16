# Arbeitsweise in diesem Repo

## Genki-PDF: einmal lesen, immer speichern

Das Genki-PDF liegt in `_lokal-NICHT-PUSHEN/` und ist ein reiner Scan — jede
gelesene Seite wird als Bild gerendert und kostet Tokens. Deshalb gilt:

**Jedes Mal, wenn du Seiten aus dem PDF liest, schreibe das Gelesene sofort nach
`_lokal-NICHT-PUSHEN/genki-auszuege/kapitel-NN.md`.** Vorher dort nachsehen — was
schon erfasst ist, wird nicht neu gelesen.

Diese Auszüge sind Kopien aus einem geschützten Buch und werden **niemals gepusht**.
Sie bleiben ausschließlich in `_lokal-NICHT-PUSHEN/`.

Was ins öffentliche Repo darf, ist nur *Abgeleitetes*: eigene Aufgaben, eigene
Erklärungen nach Tae Kim, Verweise auf Kapitel und Seiten.

## Seitenversatz — nicht konstant!

Der Versatz zwischen PDF- und Buchseite **verschiebt sich im Buch**:

| PDF | Buch | Versatz |
|---|---|---|
| 30 | 31 | +1 |
| 36 | 38 | +2 |
| 46 | 48 | +2 |

Also nicht blind umrechnen. Faustregel: PDF = Buchseite − 2 im 会話・文法編 ab Kapitel 1,
danach die Kopfzeile der ersten gelesenen Seite prüfen und bei Bedarf korrigieren.
Bekannte Anker stehen oben — beim Lesen neuer Bereiche gern ergänzen.

## Was ohne PDF schon bekannt ist

- [`genki/grammatik-index.md`](genki/grammatik-index.md) — welche Grammatik in welchem
  Kapitel, mit Seitenzahlen. Reicht zum Planen eines Blattes; **dafür das PDF nicht öffnen.**
- `_lokal-NICHT-PUSHEN/wanikani-level-1-10.md` — Kanji/Vokabeln, die der Schüler kennt.
  Kanji daraus ohne Furigana, alles andere mit.

## Grenzen des Repos

- Erklärt wird nach Tae Kim, nicht nach Genki. Genki liefert nur die Reihenfolge.
- Japanisch in Kana/Kanji, Romaji nur wo nötig.
- Keine Namen oder Level des Schülers ins öffentliche Repo.
