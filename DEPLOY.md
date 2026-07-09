# Jewelkunst live deployen

Dieses Projekt ist eine Node.js/Express-App und laeuft auf jedem Node-Hosting.

## Schnellster Weg: Railway

1. Oeffne Railway:

```text
https://railway.app/new
```

2. Waehle **Deploy from GitHub repo**
3. GitHub verbinden
4. Repository auswaehlen:

```text
nicofrommer-web/jewelkunst
```

5. Railway erkennt `railway.json` und `nixpacks.toml`
6. Deploy starten

Start Command:

```bash
npm start
```

Healthcheck:

```text
/health
```

## Alternative: Render

1. Oeffne Render:

```text
https://dashboard.render.com/new/web
```

2. GitHub Repository verbinden:

```text
nicofrommer-web/jewelkunst
```

3. Build Command:

```bash
npm install
```

4. Start Command:

```bash
npm start
```

Render erkennt auch `render.yaml`.

## Alternative: Vercel

1. Oeffne Vercel:

```text
https://vercel.com/new
```

2. Repository importieren:

```text
nicofrommer-web/jewelkunst
```

3. Deploy klicken

`vercel.json` ist bereits vorhanden.

## Alternative: eigener VPS mit Docker

```bash
git clone https://github.com/nicofrommer-web/jewelkunst.git
cd jewelkunst
docker build -t jewelkunst .
docker run -p 3000:3000 jewelkunst
```

Dann oeffnen:

```text
http://SERVER-IP:3000
```

## Lokal testen

```bash
npm install
npm start
```

Browser:

```text
http://localhost:3000
```
