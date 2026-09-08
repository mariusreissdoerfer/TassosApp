# Holzfenster-Planer IV 68 / IV 78

Planungs- und Kalkulationstool für die Schreinerwerkstatt: berechnet aus dem
Rohbau- oder Rahmenaußenmaß alle Fertigungsdaten für Holzfenster in den
Systemen **IV 68** und **IV 78** – inklusive Bestelllisten und Kalkulation.

**Live:** <https://mariusreissdoerfer.github.io/TassosApp/>

## Funktionen

- **Werkstattformeln** (Basis 80 mm Blendrahmen / 80 mm Flügel, anpassbar):
  Flügelaußenmaß = Rahmenaußenmaß −78 mm (Breite) / −93 mm (Höhe),
  Stulp = (Breite −48 mm) ÷ 2, Glasmaß = −212/−227 mm,
  Regenschutzschiene = −167 mm. Abweichende Kantelbreiten werden
  automatisch eingerechnet.
- **Ausführungen**: Standard (Regenschutzschiene Alu, 20° Aufdeckschräge)
  oder Denkmalschutz (Wetterschenkel Holz, 45° Aufdeckschräge)
- **Fenstertypen**: Dreh-Kipp, Dreh, Kipp, Festverglasung – 1-flügelig,
  2-flügelig mit Stulp oder Pfosten; Sicherheit Standard / RC 1 N / RC 2
- **Auftragsdaten**: Kommission/Kundenname, Etage (EG/OG …), Raum
- **Fensterzeichnung**: maßstäbliche Ansicht von innen mit
  DIN-Öffnungssymbolen und Bemaßung
- **Glas**: Klar- oder Ornamentglas, VSG, Randverbundfarbe, Besonderheiten,
  Silikonfarbe (Otto Seal S 110)
- **Oberfläche**: innen und außen getrennt – RAL-Farbe deckend oder
  Remmers-Lasur mit echten Farbtönen (Fensterlasur/HK-Lasur RC-Codes,
  Induline-Töne)
- **Produktionslisten**: je Position ein kompaktes Werkstattblatt mit
  eigener Fensteransicht (FL-Nummern und Öffnungscodes DKL/DKR/K/F),
  Blendrahmen-/Flügel-/Falzmaßen, Glasmaßen, Kanteln, Beschlag, Farben
  und Bemerkung – druckbar mit einer Seite pro Position
- **Beschlag Siegenia TITAN AF nach Beschlagliste**: Teile und Größen werden
  nach den FFB/FFH-Auswahltabellen der Siegenia-Beschlaglisten gewählt
  (1-flg. Dreh-Kipp RC2 S001DE-12, Zweitflügel DS 16 S002DE-14, Katalog
  02.2026) inkl. Schließblech-Anzahlen und Bandseiten-Drehpunkten;
  Materialnummern sind vorbelegt, Preise in der Stammdatenmaske
- **Profilschnitte** (Leitz-Werkzeugsatz L 161503926): Vertikalschnitt mit
  Regenschiene, Variante Wetterschenkel und Horizontalschnitt Mittelschluss
  als eigener Tab; der passende Ausschnitt erscheint automatisch auf der
  Produktionsliste und im Ergebnis (Bilder unter `img/`)
- **Holz-Bestellliste**: Kantellängen auf volle 100 mm aufgerundet
  (Lieferlängen 800–3500 mm), aggregiert über alle Positionen
- **Bestelllisten je Projekt**: Holz, Glas (Bestellmaße), Beschlag mit
  Artikelnummern, Dichtungen/Silikon/Regenschienen/Oberfläche
- **Kalkulation**: Materialpreise + Aufschlag in der Preismaske hinterlegen →
  Richtpreis je Position und Projektsumme
- **Handyfähig**, Positionsliste und Stammdaten werden lokal im Browser
  gespeichert, Druck-/PDF-Ausgabe

## Starten

Einfach die Live-Adresse öffnen oder `index.html` lokal im Browser öffnen –
keine Installation nötig, läuft komplett offline.

## Hinweis

Alle Werte sind Richtwerte nach Werkstattformel. Siegenia-Artikelnummern und
-Bestellgrößen vor der Fertigung nach aktuellem Katalog prüfen, Glasdaten mit
dem Lieferanten abgleichen.
