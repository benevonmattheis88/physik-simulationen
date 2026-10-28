# physik-simulationen

Physik-Simulationen für den Schulunterricht, erstellt mit Claude. In HTML, passend für die Nutzung am iPad und in Moodle.

**Startseite mit allen Simulationen:** https://benevonmattheis88.github.io/physik-simulationen/

## Aufbau

Die Ordner sind erst nach Thema, dann nach Stufe (Unterstufe, Mittelstufe, Oberstufe) gegliedert. Darin liegen die Simulationen.

```
mechanik/
  oberstufe/
    Kreisbewegung.html
    Kurvenlabor.html
    Stosslabor.html
elektrizitaet/
  mittelstufe/
    Stromkreis_Labor.html
    Ersatzwiderstand_herleiten.html
kernphysik/
  mittelstufe/
    Kernlabor.html
    Kernlabor_einzeln/        jeder Reiter des Kernlabors als eigene Seite
```

## Nutzung

- Jede Simulation ist eine eigenständige HTML-Datei ohne Nachladen aus dem Netz.
- Link für eine Simulation: `https://benevonmattheis88.github.io/physik-simulationen/` plus Ordner und Dateiname, z. B. `.../mechanik/oberstufe/Kurvenlabor.html`. Groß- und Kleinschreibung zählt.
- In Moodle als Aktivität „Link/URL“ mit Anzeige „Im neuen Fenster“ einbinden, oder die Datei herunterladen und als Aktivität „Datei“ hochladen.
- Dateien bitte nicht umbenennen oder verschieben, sonst funktionieren Links und QR-Codes nicht mehr.
- Änderungen an `Kernlabor.html` müssen auch in die Dateien in `Kernlabor_einzeln/` übernommen werden.
