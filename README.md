# Kreis und Körper – Jahrgang 10

**Lernseite online:** <https://joergbertholdgnw-cmd.github.io/Berechnung_Koerper_Jg10/>

Interaktive Lernseite zur Unterrichtsreihe „Kreis- und Körperberechnung“ in Jahrgang 10 (Gymnasium Niedersachsen, G9).

Die Seite zeigt den Lernweg als Karte mit „Du bist hier“-Markierung. Jede Station hat:
Ziele (Ich-kann-Sätze) → Animation → Herleitung Schritt für Schritt → Lernvideo → Kernfragen zur Herleitung → Lernprotokoll (Aufgabe, Umkehraufgabe, Vertiefung, Rückblick).
Der Fortschritt wird nur im Browser der Schülerin oder des Schülers gespeichert (localStorage), ohne Anmeldung.

## Stand

| Station | Thema | Stand |
|---|---|---|
| 0 | Startcheck | fertig |
| 1 | Kreisumfang und π (mit Messreihe und Lernprotokoll) | fertig |
| 2 | Flächeninhalt des Kreises (mit Lernprotokoll) | fertig |
| 3 | Kreisausschnitt und Kreisbogen | fertig |
| 4 | Zylinder: Netz und Oberfläche | fertig |
| 5 | Zylinder: Volumen | fertig |
| 6 | Pyramide und Kegel: Oberfläche | fertig |
| 7 | Pyramide und Kegel: Volumen | fertig |
| 8 | Kugel: Volumen | fertig |
| 9 | Kugel: Oberfläche | fertig |
| 10 | Zusammengesetzte Körper und Modellieren | fertig |

Der vollständige Lernweg steht in [docs/lernweg.md](docs/lernweg.md).

## Zusatzmaterial

Die druckfreundliche Lernseite „Körperberechnung“ (Quader und Würfel bis Kugel, mit Schritt-für-Schritt-Animationen, Rechenübungen und Selbsteinschätzung) liegt in `koerperberechnung.html` und ist online erreichbar unter <https://joergbertholdgnw-cmd.github.io/Berechnung_Koerper_Jg10/koerperberechnung.html>.

## Dateien

- `src/lernseite.html` – Quelltext der Stationen-Seite (HTML, CSS, JavaScript in einer Datei)
- `index.html` – daraus gebaute Startseite für GitHub Pages; nach Änderungen an `src/lernseite.html` `./build.sh` ausführen
- `koerperberechnung.html` – eigenständige Lernseite „Körperberechnung“ (wird nicht gebaut, direkt bearbeiten)
- `docs/lernweg.md` – Stationen, Lernziele und Videovorschläge

## Veröffentlichen

In den Repository-Einstellungen unter *Pages* den Branch `main` und den Ordner `/ (root)` wählen. Die Seite ist dann unter der oben genannten Adresse erreichbar.
