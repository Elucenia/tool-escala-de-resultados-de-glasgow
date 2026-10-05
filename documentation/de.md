<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · de · no clinical/professional/rights approval -->

# Glasgow-Outcome-Skala (GOS)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-resultados-de-glasgow)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Zustand des Patienten

`gos`

- `1` — 1 – Tod
- `2` — 2 – Anhaltender vegetativer Zustand: keine sinnvolle Reaktion, Schlaf-Wach-Zyklen
- `3` — 3 – Schwere Behinderung: bei Bewusstsein, aber im Alltag von einer anderen Person abhängig
- `4` — 4 – Mäßige Behinderung: selbstständig, aber mit Residualdefiziten (kann Verkehrsmittel nutzen und in geschützter Umgebung arbeiten)
- `5` — 5 – Gute Erholung: kehrt trotz geringer Defizite zum normalen Leben zurück

## Fassung der Methode

GOS/Jennett–Bond 1975: 5 Kategorien; günstig 4–5; nicht GOSE mit 8 Kategorien

## Dokumentierte Formel

Passendste Kategorie wählen. Studien unterscheiden meist günstig (4 und 5) und ungünstig (1 bis 3).

## Grenzen und Population

Bewertet das funktionelle Ergebnis nach Hirnverletzung unter Berücksichtigung körperlicher und geistiger Beeinträchtigung. Dokumentieren Sie Nachbeobachtungszeit und Ausgabe mit fünf Kategorien. GOS darf weder mit der GOSE mit acht Kategorien gleichgesetzt noch als Vorhersage anhand von Aufnahmedaten verstanden werden.

## Referenzen

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
