# ATLAS Trading Dashboard — Deployment

## Schnell-Anleitung (2 Minuten)

### 1. Vercel Account
→ https://vercel.com (kostenlos mit GitHub)

### 2. Deploy
**Option A — Drag & Drop (am einfachsten):**
1. Gehe zu https://vercel.com/new
2. Ziehe den ganzen `atlas-deploy` Ordner ins Browserfenster
3. Klick "Deploy"
4. Fertig! Du bekommst eine URL wie `atlas-xyz.vercel.app`

**Option B — CLI:**
```bash
npm i -g vercel
cd atlas-deploy
vercel --prod
```

### 3. Auf Handy installieren

**iPhone:**
1. Öffne die URL in Safari
2. Tippe auf "Teilen" (□↑)
3. "Zum Home-Bildschirm"
4. Fertig — sieht aus wie eine echte App!

**Android:**
1. Öffne die URL in Chrome
2. Tippe auf ⋮ Menü
3. "Zum Startbildschirm hinzufügen"
4. Fertig!

### 4. URL mit Eray teilen
Schick ihm einfach den Link — er macht dasselbe auf seinem Handy.

## Features
- Live Kraken-Kurse (BTC, XRP, ADA) alle 20 Sekunden
- Interaktive Charts mit 1h/4h/1d Timeframes
- RSI Signal Scanner (Mean Reversion)
- System-Status aller ATLAS Workflows
- Funktioniert offline als PWA
- Kein Login, kein Backend nötig
