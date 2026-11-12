# Hack the Pool 2026

**27.–28. Oktober 2026 · Österreichische Akademie der Wissenschaften, Wien**

Ein Hackathon von [Kulturpool](https://kulturpool.at) und dem [ACDH](https://www.oeaw.ac.at/acdh/), gefördert von CLARIAH-AT. Zwei Tage lang treffen österreichische Kulturdaten auf offene Wissensgraphen — Schwerpunkte: **Linked Open Data** und **Ähnlichkeitssuche**.

![Crash Override](docs/gifs/hackers-crash-override.gif)

## Doku

| | |
|---|---|
| [01 · Location](docs/01-location.md) | Adresse und Anreise |
| [02 · Programm](docs/02-programm.md) | Ablauf der beiden Tage |
| [03 · Quests](docs/03-quests.md) | Fünf Themen als Startpunkt |
| [04 · Daten & APIs](docs/04-daten.md) | Endpunkte, Dumps, Zugänge |
| [05 · Queries](docs/05-queries.md) | Sammlung: SPARQL & API-Abfragen |
| [06 · Beispiele](docs/06-beispiele.md) | Sammlung: Notebooks, Snippets, Projekte |

## Projekte

### Todesursache: Franz Ferdinand · Team expedition_pool_edition

Die Weltreise des Thronfolgers an Bord S.M.S. Kaiserin Elisabeth 1892/93 und seine Jagden: aus einem
Archiv-Vault zur k.u.k. Kriegsmarine, dem gedruckten Tagebuch, Zeitungen (ANNO) und Museumssammlungen
(Kulturpool, Weltmuseum Wien, Europeana) ein verknüpfter Datensatz, dazu drei Ansichten.

<embed src="slides/Cause_of_Death_Franz_Ferdinand.pdf" width="100%" height="850px"/>

Alles im Ordner [`expedition_pool_edition/`](expedition_pool_edition/) ([README](expedition_pool_edition/README.md)); Einstieg:
[`expedition_pool_edition/3_visualization/web/index.html`](expedition_pool_edition/3_visualization/web/index.html).


### Poolboard

Nutzer:innen erhalten ein zufälliges **Startobjekt** aus Kulturpool (kulturpool.at) und entdecken von dort aus Schritt für Schritt ähnliche Objekte. Zu jedem Objekt gibt es 10 **Metadaten-Vorschläge** und 10 **Bild-Vorschläge**. Gewählte Objekte bilden eine **Reise** (max. 20 Objekte, linear). Am Ende entsteht ein **Board**, das zeigt, wie die Objekte durch **Verbindungen** zusammenhängen. Boards liegen lokal in der **History** und lassen sich im Kulturpool-Favoriten-Format exportieren und importieren.

<embed src="slides/Poolboard.pdf" width="100%" height="850px"/>

Alles im Ordner [`poolboard/`](poolboard/) ([README](poolboard/README.md)).


### Cleaning Metadata from Hell: The Bademeister:innen Pool Tool

PoolTool analysiert Metadaten aus Kulturpool. Eine Web-Oberfläche gleicht unterschiedliche Schreibweisen mit kontrollierten Vokabularen ab — etwa „Foto“, „Fotos“ und „Photographie“ mit „Fotografie“. Nutzer:innen prüfen die Vorschläge und entscheiden, welche Varianten ersetzt werden. Die normalisierten Datensätze lassen sich zusammen mit einem Änderungsprotokoll und einem Verarbeitungsbericht exportieren.

<embed src="slides/PoolTool.pdf" width="100%" height="850px"/>

Alles im Ordner [`PoolTool/`](PoolTool/) ([README](PoolTool/README.md)).


### Kleid____oskop

Mode Kaleidoskop ist ein Prototyp, mit dem man historische Modebilder ohne Suchfeld erkunden kann. Ausgangspunkt ist eine von vier Perspektiven: Farbe, Silhouette, Accessoires oder visuelle Ähnlichkeit (Embedding). Die Website zeigt dann eine Reihe von Bildern, die sich in diesem Merkmal schrittweise verändern.

<embed src="slides/kleid_oskop.pdf" width="100%" height="850px"/>

Alles im Ordner [`kleid_oskop/`](kleid_oskop/) ([README](kleid_oskop/README.md)).


### Veryfakecation: Verification Alert System

Veryfakecation ist eine Web-Anwendung zur fachlichen Prüfung vorgeschlagener Verknüpfungen zwischen Kulturpool-Datensätzen und Wikidata-Entitäten, insbesondere bei unsicheren Bewertungen eines Sprachmodells. Nutzer:innen sehen den ursprünglichen Datensatz sowie die Modellentscheidung samt Begründung und können Zuordnungen bestätigen oder ablehnen und ihre Entscheidung kommentieren.

<embed src="slides/verifakeaction.pdf" width="100%" height="850px"/>

Alles im Ordner [`verifakecation/`](verifakecation/) ([README](verifakecation/README.md)).

## Anmeldung

[umfrage.kulturpool.at/hack-the-pool-2026](https://umfrage.kulturpool.at/hack-the-pool-2026) — bis 6. Oktober 2026. Alle Infos zur Veranstaltung auf [info.kulturpool.at](https://info.kulturpool.at/hack-the-pool-2026/).

## Mitsammeln

Queries und Beispiele wachsen hier gemeinsam. Neues kommt per Pull Request in [05 · Queries](docs/05-queries.md) bzw. [06 · Beispiele](docs/06-beispiele.md) — kurz beschreiben, was die Abfrage tut, und wenn möglich lauffähig halten.

## Vorjahr

[Hack the Pool 2025](https://github.com/kulturpool/Hack-The-Pool-2025) — Beispiele und Projekte der letzten Ausgabe.
