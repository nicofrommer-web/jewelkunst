# Jewelkunst Node.js App

Premium-Schmuckmarke mit Fokus auf leise Eleganz, Bedeutung und zeitlose Schmuckstuecke.

Dieses Repository ist jetzt als **direkt startbare Node.js/Express-App** aufgebaut.

## Direkt lokal starten

```bash
npm install
npm start
```

Dann im Browser oeffnen:

```text
http://localhost:3000
```

Statuscheck:

```text
http://localhost:3000/health
```

## Deployment ohne GitHub-Pages-Problem

GitHub Pages kann keine Node.js-Server ausfuehren. Deshalb ist dieses Projekt jetzt vorbereitet fuer:

- Render
- Railway
- Vercel
- VPS / eigener Server

## Render Deployment

1. Render.com oeffnen
2. New > Web Service
3. GitHub Repository verbinden: `nicofrommer-web/jewelkunst`
4. Build Command:

```bash
npm install
```

5. Start Command:

```bash
npm start
```

Render erkennt alternativ auch die Datei `render.yaml`.

## Vercel Deployment

1. Vercel.com oeffnen
2. New Project
3. Repository `nicofrommer-web/jewelkunst` importieren
4. Deploy klicken

Die Datei `vercel.json` ist bereits vorhanden.

## Projektstruktur

```text
package.json
server.js
public/index.html
render.yaml
vercel.json
.gitignore
```

## Marke

Jewelkunst steht fuer Schmuck, der nicht laut sein muss. Warme Materialien, ruhige Formen und eine persoenliche Ausstrahlung fuer Halsketten, Armbaender, Ohrringe und Ringe.
