# Datenschutzerklärung

**App:** Node-RED Tasks Test
**Verantwortlicher:** christian goger
**Kontakt:** christan.goger@gmail.com
**Stand:** 06.11.2026

## Zweck der Anwendung

Diese Anwendung dient ausschließlich dazu, auf meinem eigenen Node-RED-System eine Aufgabe in meiner eigenen Google-Tasks-Liste anzulegen. Sie ist kein öffentlicher Dienst und wird nicht an Dritte weitergegeben.

## Welche Daten verarbeitet werden

- **Google-Zugriffstoken:** Die Anwendung nutzt einen OAuth-Refresh-Token, um einen kurzlebigen Zugriffstoken für die Google Tasks API zu erhalten.
- **Aufgabendaten:** Titel und Fälligkeitsdatum der Aufgabe, die die Anwendung anlegt.

Es werden keine weiteren personenbezogenen Daten erhoben, gespeichert oder ausgewertet.

## Speicherung

Die Zugangsdaten (Client-ID, Client-Secret, Refresh-Token) liegen ausschließlich als Umgebungsvariablen auf meinem eigenen Node-RED-System. Sie werden nicht in Quellcode oder Repositorys gespeichert.

## Weitergabe an Dritte

Es erfolgt keine Weitergabe an Dritte. Daten werden nur an die Google-APIs (`oauth2.googleapis.com` und `tasks.googleapis.com`) übermittelt, um die Aufgabe anzulegen.

## Widerruf des Zugriffs

Der Zugriff kann jederzeit unter [myaccount.google.com/permissions](https://myaccount.google.com/permissions) widerrufen werden. Danach ist der Refresh-Token ungültig.

## Kontakt

Bei Fragen zum Datenschutz wende dich an: christan.goger@gmail.com
