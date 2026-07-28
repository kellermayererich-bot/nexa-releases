# NEXA - Auslieferung

Dieses Repository enthaelt **ausschliesslich** die fertigen Pakete der Anwendung NEXA
und deren Beschreibungsdatei. Der Quelltext liegt hier nicht.

| Datei | Bedeutung |
|---|---|
| `nexa-update.json` | Fassung, Adresse und Pruefsumme des aktuellen Pakets |
| `apk/NEXA-vX.Y.Z.apk` | das Paket selbst |

Die Anwendung fragt beim Start `nexa-update.json` ab und bietet eine neuere Fassung an.
Installiert wird nur nach Bestaetigung durch den Nutzer; zusaetzlich prueft Android,
ob das Paket mit demselben Schluessel signiert ist wie das bereits installierte.
