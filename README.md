# physik-simulationen

Physik-Simulationen für den Schulunterricht, erstellt mit Claude. In HTML, passend für die Nutzung am iPad und in Moodle.

> **Hinweis:** Die Simulationen wurden mit Hilfe von KI (Claude) erstellt. Ihre physikalische Korrektheit wurde nicht systematisch geprüft. Bitte vor dem Einsatz im Unterricht selbst kontrollieren. Jede Simulation zeigt dazu unten rechts dauerhaft die Zeile „Mit KI erstellt · Physik nicht geprüft · Ergebnisse kritisch prüfen“.

**Startseite mit allen Simulationen:** https://simulationen.familiemueller.space/

Die alte Adresse https://benevonmattheis88.github.io/physik-simulationen/ leitet automatisch dorthin weiter, alte Links und QR-Codes funktionieren also weiter.

## Aufbau

Die Ordner sind erst nach Thema, dann nach Stufe (Unterstufe, Mittelstufe, Oberstufe) gegliedert. Darin liegen die Simulationen.

```
index.html                    Startseite mit allen Simulationen
CNAME                         eigene Adresse (simulationen.familiemueller.space) für GitHub Pages
datenschutz.html              Datenschutzhinweis
versionen.html                Ältere Versionen: archivierte Stände und Links zum GitHub-Verlauf
aenderungen.html              Änderungsliste aller Simulationen (Daten für „Neu seit deinem letzten Besuch“)
mechanik/
  oberstufe/
    Bewegungsdiagramme.html
    Gravitationslabor.html
    Kreisbewegung.html
    Kurvenlabor.html
    Stosslabor.html
elektrizitaet/
  mittelstufe/
    Stromkreis_Labor.html
    Ersatzwiderstand_herleiten.html
energie/
  mittelstufe/
    Energiefluss_Baukasten.html
kernphysik/
  mittelstufe/
    Kernlabor.html
    Kernlabor_einzeln/        jeder Reiter des Kernlabors als eigene Seite
    Fusionslabor.html
optik/
  mittelstufe/
    Prisma_Labor.html
  oberstufe/
    Beugungslabor.html        Beugung an Einzelspalt, Doppelspalt und Gitter
archiv/                       eingefrorene ältere Stände, gleiche Ordnerstruktur,
                              Dateiname mit Datum, z. B. Kurvenlabor_2026-10-28.html
```

## Nutzung

- Jede Simulation ist eine eigenständige HTML-Datei ohne Nachladen aus dem Netz.
- Link für eine Simulation: `https://simulationen.familiemueller.space/` plus Ordner und Dateiname, z. B. `.../mechanik/oberstufe/Kurvenlabor.html`. Groß- und Kleinschreibung zählt.
- Auf der Startseite gibt es bei jeder Simulation einen Knopf „HTML-Datei herunterladen“, z. B. zum Hochladen in Moodle oder für die Offline-Nutzung.
- In Moodle als Aktivität „Link/URL“ mit Anzeige „Im neuen Fenster“ einbinden, oder die Datei herunterladen und als Aktivität „Datei“ hochladen.
- Dateien bitte nicht umbenennen oder verschieben, sonst funktionieren Links und QR-Codes nicht mehr.
- Ältere Stände: Seite „Ältere Versionen“ (`versionen.html`, verlinkt von der Startseite). Archivierte Stände in `archiv/` laufen direkt im Browser und werden nicht mehr verändert (außer KI-Hinweis), ihre Links bleiben fest. Alle übrigen Stände findet man im GitHub-Verlauf der jeweiligen Datei.
- Startseite: Wer schon einmal da war, sieht oben „Neu seit deinem letzten Besuch“ mit den seitdem geänderten Simulationen. Der Besuchszeitpunkt bleibt nur im eigenen Browser. **Jede Änderung an einer Simulation bekommt einen Eintrag in `aenderungen.html`** (Datenblock `aenderungsdaten`: Zeitpunkt, Simulation, kurzer Text).
- Änderungen an `Kernlabor.html` müssen auch in die Dateien in `Kernlabor_einzeln/` übernommen werden.
- Startseite in zwei Teilen: oben **Lernmodule** (zum Selbstlernen mit Rückmeldung und Ergebnis-Übersicht für Moodle: Ersatzwiderstand, Aufgaben im Energiefluss-Baukasten, Nachfahren in den Bewegungsdiagrammen), darunter die **Simulationen** zum Vorführen und Erkunden, nach Thema sortiert. Die Dateien liegen trotzdem alle im Themenordner.
- Einzelne Reiter lassen sich direkt verlinken, siehe [Direktlinks zu einzelnen Reitern](#direktlinks-zu-einzelnen-reitern).

## Direktlinks zu einzelnen Reitern

Hängt man an den Link einer Simulation `#` und den Namen eines Reiters an, öffnet sie sich gleich in diesem Reiter. Beim Umschalten zeigt die Adresszeile immer den passenden Direktlink, man kann ihn also auch einfach von dort kopieren. Ohne `#…` startet die Simulation wie bisher.

- Das funktioniert mit Links (z. B. Moodle-Aktivität „Link/URL“, QR-Code). Bei einer in Moodle hochgeladenen Datei kann man kein `#…` anhängen.
- Für das Kernlabor gibt es zusätzlich weiterhin die Einzelseiten in `Kernlabor_einzeln/` (nur ein Reiter, ohne Reiterleiste).

### Kernlabor

| Reiter | Direktlink |
|---|---|
| Atomkern bauen | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#bau |
| Rutherford | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#rutherford |
| Zerfälle | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#zerfall |
| Ablenkung | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#ablenkung |
| Abschirmung | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#abschirmung |
| Strahlenschutz | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#strahlenschutz |
| Halbwertszeit | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#halbwertszeit |
| Spaltung | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#spaltung |
| Spaltung: Ablauf | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#ablauf |
| Kettenreaktion | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#kette |
| Reaktor | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Kernlabor.html#reaktor |

### Fusionslabor

| Reiter | Direktlink |
|---|---|
| Verschmelzen | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Fusionslabor.html#verschmelzen |
| Woher kommt die Energie? | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Fusionslabor.html#energie |
| Sonne | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Fusionslabor.html#sonne |
| Fusionsreaktor | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Fusionslabor.html#reaktor |
| Spaltung und Fusion | https://simulationen.familiemueller.space/kernphysik/mittelstufe/Fusionslabor.html#vergleich |

### Stromkreis-Labor

| Reiter | Direktlink |
|---|---|
| Widerstand | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#widerstand |
| Reihe (Widerstände) | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#reihe-widerstaende |
| Parallel (Widerstände) | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#parallel-widerstaende |
| Lampe | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#lampe |
| Reihe (Lampen) | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#reihe-lampen |
| Parallel (Lampen) | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#parallel-lampen |
| Gemischt | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#gemischt |
| Kennlinie | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#kennlinie |
| Draht | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#draht |
| Aufgabe 1 | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#aufgabe-1 |
| Aufgabe 2 | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#aufgabe-2 |
| Aufgabe 3 | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#aufgabe-3 |
| Aufgabe 4 | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Stromkreis_Labor.html#aufgabe-4 |

### Ersatzwiderstand herleiten

| Reiter | Direktlink |
|---|---|
| 1 · Parallel | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Ersatzwiderstand_herleiten.html#parallel |
| 2 · Reihe | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Ersatzwiderstand_herleiten.html#reihe |
| 3 · Übungen | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Ersatzwiderstand_herleiten.html#uebungen |
| 4 · Übersicht | https://simulationen.familiemueller.space/elektrizitaet/mittelstufe/Ersatzwiderstand_herleiten.html#uebersicht |

### Energiefluss-Baukasten

| Reiter | Direktlink |
|---|---|
| Frei bauen | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#frei |
| Aufgaben (Liste) | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgaben |
| Aufgabe Fahrraddynamo | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-fahrraddynamo |
| Aufgabe Wasserkocher | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-wasserkocher |
| Aufgabe Solarventilator | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-solarventilator |
| Aufgabe Auto | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-auto |
| Aufgabe Wasserkraftwerk | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-wasserkraftwerk |
| Aufgabe Zentralheizung | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-zentralheizung |
| Aufgabe Kohlekraftwerk | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#aufgabe-kohlekraftwerk |
| Übersicht (Ergebnisse) | https://simulationen.familiemueller.space/energie/mittelstufe/Energiefluss_Baukasten.html#uebersicht |

### Bewegungsdiagramme

| Reiter | Direktlink |
|---|---|
| Bewegungen | https://simulationen.familiemueller.space/mechanik/oberstufe/Bewegungsdiagramme.html#bewegungen |
| Selbst steuern | https://simulationen.familiemueller.space/mechanik/oberstufe/Bewegungsdiagramme.html#selbst-steuern |
| Nachfahren | https://simulationen.familiemueller.space/mechanik/oberstufe/Bewegungsdiagramme.html#nachfahren |
| Übersicht (Ergebnisse beim Nachfahren) | https://simulationen.familiemueller.space/mechanik/oberstufe/Bewegungsdiagramme.html#uebersicht |

### Gravitationslabor

| Reiter | Direktlink |
|---|---|
| Labor | https://simulationen.familiemueller.space/mechanik/oberstufe/Gravitationslabor.html#labor |
| Weltall | https://simulationen.familiemueller.space/mechanik/oberstufe/Gravitationslabor.html#weltall |
| Drehwaage | https://simulationen.familiemueller.space/mechanik/oberstufe/Gravitationslabor.html#drehwaage |

### Kreisbewegung

| Reiter | Direktlink |
|---|---|
| Beschreiben | https://simulationen.familiemueller.space/mechanik/oberstufe/Kreisbewegung.html#beschreiben |
| Kraft | https://simulationen.familiemueller.space/mechanik/oberstufe/Kreisbewegung.html#kraft |

### Kurvenlabor

| Reiter | Direktlink |
|---|---|
| Kurve | https://simulationen.familiemueller.space/mechanik/oberstufe/Kurvenlabor.html#kurve |
| Kettenkarussell | https://simulationen.familiemueller.space/mechanik/oberstufe/Kurvenlabor.html#kettenkarussell |
| Looping | https://simulationen.familiemueller.space/mechanik/oberstufe/Kurvenlabor.html#looping |

### Stoßlabor (Fälle)

| Reiter | Direktlink |
|---|---|
| Demo C: elastisch m/m | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-c |
| A: plastisch m/m | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-a |
| B: plastisch 2m/m | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-b |
| D: elastisch 2m/m | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-d |
| E: elastisch m/2m | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-e |
| F: Gegenstoß | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-f |
| G: plastischer Gegenstoß | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#fall-g |
| H: teilelastisch m/2m (früher „Hausaufgabe“) | https://simulationen.familiemueller.space/mechanik/oberstufe/Stosslabor.html#hausaufgabe |

### Prisma-Labor

| Reiter | Direktlink |
|---|---|
| Weißes Licht | https://simulationen.familiemueller.space/optik/mittelstufe/Prisma_Labor.html#weisses-licht |
| Einfarbiges Licht | https://simulationen.familiemueller.space/optik/mittelstufe/Prisma_Labor.html#einfarbig |

### Beugungslabor

| Reiter | Direktlink |
|---|---|
| Einzelspalt | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#einzelspalt |
| Doppelspalt | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#doppelspalt |
| Gitter | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#gitter |
| Einzelspalt mit Herleitung | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#einzelspalt-herleitung |
| Doppelspalt mit Herleitung | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#doppelspalt-herleitung |
| Gitter mit Herleitung | https://simulationen.familiemueller.space/optik/oberstufe/Beugungslabor.html#gitter-herleitung |
