#Node.js CI Pipeline

![CI Status](https://github.com/Tkr8kdigital180/mein-erster-workflow/workflows/Node.js%20CI/badge.svg)

Dieses Repository enthält eine einfache Node.js CI/CD-Pipeline mit GitHub Actions.

## Workflow-Übersicht

Der Workflow führt bei jedem Push auf `main` oder `develop` sowie bei Pull Requests auf `main` folgende Schritte aus:

1. Code auschecken 
2. Node.js installieren (Versionen 16.x, 18.x, 20.x) 
3. Dependencies installieren
4. Tests ausführen
5. Erfolgsmeldung ausgeben
## Struktur

