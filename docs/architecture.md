# Architektur

Der ACStorage Controller bildet eine regelbasierte Koordinationsschicht zwischen Home Assistant und mehreren Wechselrichter-/Batteriesystemen.

## Ziel

- PV-Überschuss besser nutzen
- Nur ein ACStorage-System gleichzeitig aktivieren
- Gegenseitiges Laden und Entladen vermeiden
- Batteriestände und Netzfluss berücksichtigen
- Entscheidungen transparent und nachvollziehbar halten

## Technische Idee

Die Automationen bewerten Zustände wie Netzfluss, Ladezustand, aktive Auswahl und Grenzwerte. Daraus wird eine gewünschte Steuerungsentscheidung abgeleitet.
