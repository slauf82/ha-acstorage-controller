# HA ACStorage Controller

Rule-based Home Assistant automation project for coordinating ACStorage behavior in a photovoltaic / battery setup.

## Kurzbeschreibung

Entwicklung einer regelbasierten Steuerung für Batteriespeicher auf Basis von PV-Erzeugung, Netzfluss und Ladezuständen. Ziel des Projekts ist die Optimierung des Eigenverbrauchs sowie die intelligente Koordination mehrerer Wechselrichter und Batteriesysteme.

## Schwerpunkte

- Energiemanagement
- Regelbasierte Entscheidungslogik
- Multi-Inverter-Koordination
- Lade- und Entladestrategien
- PV-Überschussoptimierung
- Status-Synchronisation
- Zustandsmodelle

## Technologien

- Home Assistant
- YAML
- Python-basierte Home-Assistant-Laufzeit
- REST / Integrationen
- JSON
- Git
- Automation

## Enthaltene Automationen

- `003_auto_acstorage_sync.yaml` – Status-Synchronisation
- `004_auto_acstorage_steuerung.yaml` – Regelbasierte Steuerung

## Hinweis

Die YAML-Dateien sind Showcase- und Referenzdateien. Entity-Namen müssen an die jeweilige Home-Assistant-Installation angepasst werden.
