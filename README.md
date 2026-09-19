# 📱 Sideloading Hub

Repository personale per la gestione e la distribuzione di applicazioni iOS, media player e strumenti avanzati per **SideStore**, **AltStore** e **LiveContainer**.

[![Auto-Extract & Build](https://github.com/SimoGHcoder/iosrepo/actions/workflows/auto_extract.yml/badge.svg)](https://github.com/SimoGHcoder/iosrepo/actions/workflows/auto_extract.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🔗 Aggiungi la Repository

Per aggiungere questa sorgente alla tua applicazione di sideloading preferita, usa il link sottostante:

`https://raw.githubusercontent.com/SimoGHcoder/iosrepo/main/apps.json`

---

## 🚀 Applicazioni Disponibili

La repository ospita e aggiorna automaticamente le seguenti categorie di applicazioni:

| Applicazione | Categoria | Descrizione |
| :--- | :--- | :--- |
| **Nuvio** | Media Player | Streaming e riproduzione multimediale avanzata. |
| **Stremio** | Media Player | Centro multimediale e gestione cataloghi streaming. |
| **Tool / Mod** | Utilità | Strumenti di sistema, CAD e applicazioni modificate. |

*Nota: La lista si aggiorna dinamicamente a seconda dei pacchetti IPA rilasciati o sincronizzati nella repository.*

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
