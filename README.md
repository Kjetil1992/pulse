# IronLog 🏋️

Treningssporing som PWA — kan installeres på telefonen som en ekte app.

---

## Publiser på nettet (én gang)

### 1. Last opp til GitHub

1. Gå til [github.com](https://github.com) og opprett en gratis konto
2. Klikk **New repository** → gi det navn `ironlog` → **Create repository**
3. Last ned [GitHub Desktop](https://desktop.github.com/) hvis du ikke vil bruke terminal
4. Dra inn alle filene i dette prosjektet og trykk **Commit** → **Push**

### 2. Koble til Vercel

1. Gå til [vercel.com](https://vercel.com) og logg inn med GitHub-kontoen din
2. Klikk **Add New Project** → velg `ironlog`-repoet ditt
3. Vercel oppdager Vite automatisk — bare klikk **Deploy**
4. Etter 1–2 minutter får du en lenke, f.eks. `ironlog.vercel.app` 🎉

### 3. Del lenken

Send lenken til venner. De kan bruke appen rett i nettleseren.

---

## Installer på telefonen (PWA)

### iPhone (Safari)
1. Åpne lenken i **Safari**
2. Trykk på **Del**-ikonet (firkant med pil opp)
3. Velg **Legg til på hjemskjerm**
4. Trykk **Legg til** — ferdig! 📱

### Android (Chrome)
1. Åpne lenken i **Chrome**
2. Trykk på de tre prikkene øverst til høyre
3. Velg **Legg til på startskjermen**
4. Trykk **Installer** — ferdig! 📱

---

## Oppdater appen

Gjør endringer i koden → push til GitHub → Vercel oppdaterer automatisk.
Alle brukere får den nye versjonen neste gang de åpner appen.

---

## Prosjektstruktur

```
ironlog/
├── public/
│   ├── manifest.json   ← PWA-konfig
│   ├── sw.js           ← Service worker (offline-støtte)
│   ├── icon-192.png    ← App-ikon (bytt ut med eget om ønskelig)
│   └── icon-512.png
├── src/
│   ├── main.jsx        ← Inngangspunkt
│   └── App.jsx         ← Hele appen
├── index.html
├── vite.config.js
└── package.json
```
