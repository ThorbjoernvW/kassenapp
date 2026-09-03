# KassenApp V0.11

Neu in V0.11:
- Mobile Burger-Navigation öffnet jetzt als kompaktes Dropdown oben rechts.
- Keine vollflächige Seitenleiste mehr auf dem Handy.

# KassenApp V0.10

Neu in V0.10:
- Zwei Modi für die Eingabe des gegebenen Geldes: Schnellwahl und Tastenfeld.
- Tastenfeld mit 0–9, Komma, 00, Passend und Löschtaste.
- Schnelle Cent-Eingabe: 2000 entspricht 20,00 €.
- Der zuletzt verwendete Eingabemodus wird lokal gespeichert.

# KassenApp V0.9

## Fehlerbehebung
- Der Fehler `normalizeOrder is not defined` beim Speichern von Artikeln ist behoben.
- Die fehlende Funktion zur Normalisierung der Artikelreihenfolge wurde wieder ergänzt.
- Sie wird beim Anlegen, Bearbeiten und Löschen von Artikeln verwendet.
- JavaScript-Syntax wurde nach der Reparatur geprüft.

## Parkplatz
- Auswertung über Verkaufszeiten / größter Ansturm
- Aufteilung Essen / Getränke
- Historische Artikelversionierung

## V0.13
- Mobile Einstellungen: Aktiv/Inaktiv-Schalter bleibt vollständig innerhalb der Artikelkarte.
- Mobile Tastenfeldeingabe: Zahlentasten bleiben nach einem Tap nicht mehr durch einen Touch-Hover-Zustand grün.


## V0.13 – Offline-Betrieb
- Service Worker speichert die App-Oberfläche lokal im Browser.
- Nach dem ersten erfolgreichen Laden über GitHub Pages kann die KassenApp auch ohne Internet geöffnet und benutzt werden.
- Verkäufe, Artikel und Einstellungen bleiben weiterhin lokal im Browser gespeichert.
- Bei einer neuen veröffentlichten Version wird der App-Cache automatisch erneuert.

### Offline testen
1. V0.13 auf GitHub Pages veröffentlichen.
2. Die Seite auf dem Handy bei bestehender Internetverbindung einmal vollständig öffnen.
3. Danach Flugmodus einschalten.
4. Seite neu öffnen bzw. neu laden. Die Kasse sollte weiterhin funktionieren.

Hinweis: Beim allerersten Aufruf ist Internet nötig, damit die App-Dateien lokal gespeichert werden können.
