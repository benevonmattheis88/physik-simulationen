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
optik/
  mittelstufe/
    Prisma_Labor.html
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
- Änderungen an `Kernlabor.html` müssen auch in die Dateien in `Kernlabor_einzeln/` übernommen werden.
