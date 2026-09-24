# 📱 Sideloading Hub

Repository personale per la gestione e la distribuzione di applicazioni iOS, media player e strumenti avanzati per **SideStore**, **AltStore** e **LiveContainer**.

[![iOS Repository Sync & Build](https://github.com/SimoGHcoder/iosrepo/actions/workflows/update-repo.yml/badge.svg)](https://github.com/SimoGHcoder/iosrepo/actions/workflows/update-repo.yml)
[![Stremio IPA Sync](https://github.com/SimoGHcoder/iosrepo/actions/workflows/fetch_stremio.yml/badge.svg)](https://github.com/SimoGHcoder/iosrepo/actions/workflows/fetch_stremio.yml)
[![Nuvio IPA Sync](https://github.com/SimoGHcoder/iosrepo/actions/workflows/auto-update-nuvio.yml/badge.svg)](https://github.com/SimoGHcoder/iosrepo/actions/workflows/auto-update-nuvio.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🔗 Aggiungi la Repository

Per aggiungere questa sorgente alla tua applicazione di sideloading preferita, usa il link sottostante:

`https://raw.githubusercontent.com/SimoGHcoder/iosrepo/main/apps.json`

---

## 🚀 Applicazioni Disponibili

La repository ospita e aggiorna automaticamente le seguenti categorie di applicazioni:

<!-- APPS_TABLE_START -->
| Applicazione | Categoria | Descrizione |
| :--- | :--- | :--- |
| **GitHub** | Utilità / Mod | Applicazione GitHub. |
| **AI Code Editor** | Utilità / Mod | Applicazione AI Code Editor. |
| **Stremio** | Media Player | Download automatico dell'IPA ufficiale di Stremio estratto dalla CDN dir... |
| **Spotify** | Musica & Audio | 🚀 **Aggiornamento Disponibile** |
| **Shapr3D** | Strumento CAD | 🚀 **Aggiornamento Disponibile** |
| **Nuvio** | Media Player | - 0b427905 fix(mdblist): correct library sorting @tapframe   |
| **calimoto** | Navigazione GPS | 🚀 **Aggiornamento Disponibile** |
<!-- APPS_TABLE_END -->

---

## 📖 Come installare la Source

### 🍏 AltStore / SideStore
1. Apri **AltStore** o **SideStore** sul tuo dispositivo iOS.
2. Vai nella scheda **Browse** (Sfoglia).
3. Tocca il tasto **`+`** (o l'icona sorgenti in alto).
4. Inserisci l'URL della repository e conferma l'aggiunta.

### 📦 LiveContainer
1. Apri **LiveContainer**.
2. Aggiungi la sorgente inserendo il link della repository nelle impostazioni delle fonti/repository supportate.

---

## ⚙️ Informazioni Tecniche
La pipeline di questa repository è configurata tramite **GitHub Actions** per automatizzare l'estrazione dei metadati (`Info.plist`), il recupero e la conversione delle icone delle app (supporto formati CGBitmap/PNG) e la generazione strutturata del file `apps.json` a ogni singola release o aggiornamento degli asset IPA.
