# Holzfenster-Planer IV 68 / IV 78

Planungstool für die Schreinerwerkstatt: berechnet aus dem Rohbau- oder
Rahmenaußenmaß alle Fertigungsdaten für Holzfenster in den Systemen **IV 68**
und **IV 78**.

## Funktionen

- **Maßkette**: Rahmenaußenmaß → Rahmenfalzmaß → Flügelfalzmaß (FFB/FFH,
  Bezugsmaß für den Beschlag) → Flügelaußenmaß → Glasfalz → Glas-Bestellmaß
- **Fenstertypen**: Dreh-Kipp, Dreh, Kipp, Festverglasung – 1-flügelig,
  2-flügelig mit Stulp oder mit Pfosten
- **Zuschnittliste** mit Kantelquerschnitten (roh/fertig), Glasleisten und
  Wetterschutzprofilen inkl. Zuschnittzugabe
- **Beschlagliste** mit Richtgrößen (Getriebe-/Scherengröße nach FFH/FFB,
  Mittel-/Zusatzverriegelungen, Schließbleche, Stulpgetriebe)
- **Materialbedarf**: Kantel-Laufmeter, Holzvolumen, Glasfläche und -gewicht,
  Dichtungen, Dichtstoff, Oberfläche/Lasurmenge, Flügelgewichte mit
  Tragkraft-Warnung
- **Positionsliste** für ganze Projekte mit Gesamtbedarf und Bestellliste
  (wird lokal im Browser gespeichert), Druck-/PDF-Ausgabe
- **Profileinstellungen** (Anschlag, Falzluft, Überschlag, Glaseinstand usw.)
  sind anpassbar an die eigene Kantel und das eigene Beschlagsystem

## Starten

Einfach `index.html` im Browser öffnen – keine Installation nötig, läuft
komplett offline. Alternativ mit einem lokalen Webserver:

```bash
python3 -m http.server 8000
```

und dann <http://localhost:8000> aufrufen.

## Hinweis

Alle Werte sind Richtwerte nach gängiger Werkstattpraxis (DIN-68121-nahe
Profile, Dreh-Kipp-Standardbeschlag). Vor der Fertigung mit den
Einbauvorschriften des Beschlagherstellers und den Daten des Glaslieferanten
abgleichen.
