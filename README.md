# Docker Node.js Sample

## Projektbeschreibung


Dieses Projekt ist eine einfache **ToDo-Applikation**, die mit **Node.js** entwickelt wurde.

Die Anwendung kann auf verschiedene Arten gestartet werden:

- direkt auf dem Computer mit Node.js
- mit einem Docker-Container
- mit Docker Compose
Hallo ich bin Yannis

Dieses Projekt ist eine **ToDo-Applikation mit Node.js**.  
Die Anwendung kann **lokal**, mit **Docker** oder mit **Docker Compose** gestartet werden.

## Voraussetzungen

- **Node.js**
- **npm**
- **Docker**
- **Docker Compose**
- **Git**

## Repository klonen

Das Repository kann mit folgendem Befehl geklont werden:

```bash
git clone DEINE-REPOSITORY-URL
cd docker-nodejs-sample

# 7. Fragen zur Docker-Dokumentation

### 1. Was ist ein Docker-Image?

Ein Docker-Image ist eine Vorlage, die alles enthält, was eine Anwendung zum Starten benötigt.

### 2. Was ist ein Docker-Container?

Ein Docker-Container ist eine laufende Instanz eines Docker-Images.

### 3. Was ist der Unterschied zwischen Image und Container?

Das Image ist die Vorlage und der Container ist die daraus gestartete Anwendung.

### 4. Welche Aufgabe besitzt ein Dockerfile?

Das Dockerfile beschreibt Schritt für Schritt, wie ein Docker-Image erstellt wird.

### 5. Wozu wird `.dockerignore` verwendet?

Mit `.dockerignore` wird festgelegt, welche Dateien und Ordner nicht in das Docker-Image kopiert werden sollen.

### 6. Welche Aufgabe besitzt `compose.yaml`?

Die `compose.yaml` beschreibt, wie die Docker-Container erstellt und gestartet werden.

### 7. Was bedeutet die Portangabe `3000:3000`?

Der erste Port `3000` ist der Port des Computers. Der zweite Port `3000` ist der Port im Container.

### 8. Weshalb wird `package.json` vor dem restlichen Quellcode kopiert?

Damit Docker zuerst die benötigten Node.js-Pakete installieren kann. Ausserdem kann dadurch der Docker-Cache besser genutzt werden.

### 9. Was macht `docker compose up`?

Der Befehl erstellt und startet die in `compose.yaml` definierten Container.

### 10. Was macht `docker compose down`?

Der Befehl stoppt und entfernt die von Docker Compose erstellten Container.

### 11. Weshalb wird nach Änderungen teilweise `--build` benötigt?

`--build` sorgt dafür, dass das Docker-Image neu erstellt wird und die Änderungen übernommen werden.
(Finished word dokumentation)
