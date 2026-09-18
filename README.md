# Docker Node.js Sample

## Projektbeschreibung


Dieses Projekt ist eine einfache **ToDo-Applikation**, die mit **Node.js** entwickelt wurde.

Die Anwendung kann auf verschiedene Arten gestartet werden:

- direkt auf dem Computer mit Node.js
- mit einem Docker-Container
- mit Docker Compose

Dieses Projekt ist eine **ToDo-Applikation mit Node.js**.  
Die Anwendung kann **lokal**, mit **Docker** oder mit **Docker Compose** gestartet werden.

## Voraussetzungen

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- Docker Compose

## Repository klonen

```bash
git clone <REPOSITORY-URL>
cd <PROJEKTORDNER>
```

## Pakete installieren

```bash
npm install
```

## Anwendung lokal starten

```bash
npm start
```

Die Anwendung ist danach unter `http://localhost:3000` erreichbar.

## Docker-Image erstellen

```bash
docker build -t node-app .
```

## Anwendung mit Docker starten

```bash
docker run -p 3000:3000 node-app
```

Danach ist die Anwendung unter `http://localhost:3000` erreichbar.

## Anwendung mit Docker Compose starten

```bash
docker compose up
```

Im Hintergrund:

```bash
docker compose up -d
```

## Anwendung stoppen

Mit Docker Compose:

```bash
docker compose down
```

Bei einem normalen Docker-Container:

```bash
docker stop <CONTAINER-ID>
```

### 9. Was macht `docker compose up`?

Der Befehl erstellt und startet die in `compose.yaml` definierten Container.

### 10. Was macht `docker compose down`?

Der Befehl stoppt und entfernt die von Docker Compose erstellten Container.

### 11. Weshalb wird nach Änderungen teilweise `--build` benötigt?

`--build` sorgt dafür, dass das Docker-Image neu erstellt wird und die Änderungen übernommen werden.
(Finished word dokumentation)
