# Dev Hub — Roadmap & TODO

> Ultima actualizare: 15 Apr 2026

## ✅ Completat
- [x] Deploy pe Vercel (`dev-hub-seven-plum.vercel.app`)
- [x] Tab GitHub — 30 repo-uri cu search, filtre limbaj, sortare, paginare
- [x] Tab Vercel — 33 proiecte reale din echipa `gzeus-projects`
- [x] Tab Stats — distribuție limbaje + activitate Vercel per trimestru
- [x] Tab Threads — panel Vercel Toolbar (0 active)
- [x] Dark/Light mode toggle
- [x] Design responsive mobile

---

## 🔜 TODO — Prioritate Mare

### v2.2 — UX & Date reale
- [ ] **Fetch toate cele 141 repo-uri** (nu doar 30) — paginare API GitHub
- [ ] **Afișare ultimul deployment Vercel** pe fiecare card (branch, status, data)
- [ ] **Link deployment live** pe cardurile Vercel (nu doar link dashboard)
- [ ] **Stars pe repo-uri GitHub** — afișare + sortare după stele
- [ ] **Badge "private"** pe repo-urile private (14 total)

### v2.3 — Features Noi
- [ ] **Tab Deployments** — istoric deployments per proiect Vercel cu status (✅ Ready / ❌ Error / 🔄 Building)
- [ ] **Quick Actions** — buton "Open in VS Code" / "Copy clone URL" pe fiecare repo card
- [ ] **Notificări Issues** — highlight repo-uri cu issues deschise mai vechi de 7 zile
- [ ] **Favorite / Pin** — sistem de pinuire repo-uri importante (salvat in localStorage)
- [ ] **Keyboard shortcuts** — `/` pentru search, `1-4` pentru tab switch

### v2.4 — Stats Avansate
- [ ] **Grafic activitate commits** — contribuții pe ultimele 30/90 zile
- [ ] **Top proiecte** — după stele, forks, activitate recentă
- [ ] **Distribuție teme** — blockchain, AI, GameFi, DeFi etc. (bazat pe topics)
- [ ] **Vercel bandwidth / invocations** (dacă API-ul permite)

---

## 🔮 TODO — Idei Viitoare
- [ ] **Sidebar navigare** în loc de tabs (pentru ecrane mari)
- [ ] **README preview** inline pe hover sau click pe repo card
- [ ] **GitHub Issues viewer** — lista issues per repo direct în hub
- [ ] **Vercel Toolbar Threads** — răspuns la threads direct din Dev Hub
- [ ] **PWA** — installable ca app pe desktop/mobil
- [ ] **Sync automat** — refresh date la fiecare 5 minute (în memorie, nu fetch extern)
- [ ] **Export CSV** — exportă lista repo-uri sau deployments

---

## 📋 Convenții
- Fiecare feature → branch separat → PR → merge în `main`
- Vercel face auto-deploy la fiecare push pe `main`
- Nu se salvează date sensibile (token-uri, etc.) în frontend
- Toate datele sunt hardcodate (static site) sau fetch la runtime fără auth
