# HeatZone Card

Custom Lovelace-Karte für die Steuerung von Heizungsprofilen in Home Assistant.
Nur in Verbindung mit der heatzone Integration funktionsfähig.

## Installation über HACS

1. In HACS → `Integrationen` → oben rechts auf die drei Punkte → **Benutzerdefiniertes Repository**.
2. URL deines Repos eintragen, Kategorie: **Lovelace**.
3. Danach in HACS unter `Frontend` nach **HeatZone Profile** suchen und installieren.
4. HACS legt die Datei unter `www/community/heatzone-profile/heatzone-profile.js` ab.

Die Ressource wird in der Regel automatisch von HACS hinzugefügt. Falls nicht, manuell:

```yaml
resources:
  - url: /hacsfiles/heatzone-profile/heatzone-profile.js
    type: module
