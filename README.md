# Zeiterfassung Poseidon

Ein einfaches Zeiterfassungssystem mit Weboberfläche und RFID-Badge-Leser, entwickelt im Basislehrjahr als Abschlussprojekt.

## Funktionen

- Ein- und Ausbadgen über RFID oder Webinterface
- Live Anzeige von Arbeitszeit, Saldo und Differenz
- History-Seite mit Übersicht von allen Buchungen
- LEDs für (optisches) Feedback ob eingebadged oder nicht
- Lokale Datenspeicherung auf dem ESP8266 (LittleFS)

## Aufbau

- HTML, CSS, JavaScript für die Web-GUI
- Arduino Code für den ESP8266
- Kommunikation über Hotspot
- Speicherung von Status und Buchungen im Flash
