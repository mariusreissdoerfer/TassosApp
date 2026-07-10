# Holzfenster-Planer IV 68 / IV 78

Planungstool für die Schreinerwerkstatt: berechnet aus dem Rohbau- oder
Rahmenaußenmaß alle Fertigungsdaten für Holzfenster in den Systemen **IV 68**
und **IV 78**.

## Funktionen

- **Maßkette**: Rahmenaußenmaß → Rahmenfalzmaß → Flügelfalzmaß (FFB/FFH,
  Bezugsmaß für den Beschlag) → Flügelaußenmaß → Glasfalz → Glas-Bestellmaß
- **Fenstertypen**: Dreh-Kipp, Dreh, Kipp, Festverglasung – 1-flügelig,
  2-flügelig mit Stulp oder mit Pfosten
- **Fensterzeichnung**: maßstäbliche Ansicht von innen mit
  DIN-Öffnungssymbolen, Griffposition und Bemaßung
- **Zuschnittliste** mit Kantelquerschnitten (roh/fertig), Glasleisten und
  Wetterschutzprofilen inkl. Zuschnittzugabe
- **Beschlagliste Siegenia TITAN AF** mit Richtgrößen (Getriebe-/Scherenarm
  nach FFH/FFB, Mittel-/Zusatzverriegelungen, Schließbleche,
  Stulpflügelgetriebe)
- **Materialbedarf**: Kantel-Laufmeter, Holzvolumen, Glasfläche und -gewicht,
  Dichtungen, Dichtstoff, Oberfläche/Lasurmenge, Flügelgewichte mit
  Tragkraft-Warnung
- **Positionsliste** für ganze Projekte mit Gesamtbedarf und Bestellliste
  (wird lokal im Browser gespeichert), Druck-/PDF-Ausgabe
- **Profileinstellungen** (Anschlag, Falzluft, Überschlag, Glaseinstand usw.)
  sind anpassbar an die eigene Kantel und das eigene Beschlagsystem
- **Handyfähig**: responsives Layout, auch auf dem Smartphone in der
  Werkstatt nutzbar

## Starten

Einfach `index.html` im Browser öffnen – keine Installation nötig, läuft
komplett offline. Alternativ mit einem lokalen Webserver:

```bash
python3 -m http.server 8000
```

und dann <http://localhost:8000> aufrufen.

## Hinweis

Alle Werte sind Richtwerte nach gängiger Werkstattpraxis (DIN-68121-nahe
Profile). Die Beschlagliste orientiert sich am Siegenia-TITAN-AF-Sortiment
für Holzfenster; exakte Artikelnummern und Bestellgrößen vor der Fertigung
nach aktuellem Siegenia-Katalog bestimmen und die Glasdaten mit dem
Lieferanten abgleichen.
