# 🌍🧠🎨 **LOCUS** 🎨🧠🌍

### A Location-Bound Global Canvas 📍🖌️🌐

**Locus** is a geospatial social canvas where the world itself becomes the feed 🌎📡🖍️. Instead of posting *about* places 📸📍💬, users draw, write, and leave images **directly on the map of reality** 🗺️✏️🧩. Every location becomes a collaborative layer of expression 🎭🌍🧠.

---
<img width="860" height="613" alt="IMG_0995" src="https://github.com/user-attachments/assets/0e972a26-2d53-4e63-9a87-1eda6a24d079" />


## ⚡ Concept ⚡

Stand somewhere 🌍🧍‍♂️📍.
Open Locus 📱✨🗺️.
See what the world left there before you 👀🎨🧩.
Add something of your own ✏️🖌️📸.

Every coordinate becomes a **living canvas tile** 📦🗺️🎨 that evolves over time ⏳🧠🌱.

---

## 🚀 Core Features 🚀

📍 **Location-Locked Canvas**
Users see the canvas associated with their real-world position 🌍📡🗺️.

🔍 **Pan + Zoom Exploration**
Explore nearby tiles like a living mural 🗺️🔍🎨.

✏️ **Draw on the World**
Freehand strokes using PencilKit 🖌️📱✨.

💬 **Drop Text Anywhere**
Leave messages tied to physical space 🧠💬📍.

🖼️ **Attach Images to Places**
Memes, art, signals from the void 🌌📸🧩.

↩️ **Undo + Draft Editing**
Iterate locally before committing changes 🔄🧠✏️.

💾 **Save to the Global Canvas**
Push your edits to the shared tile state 🌍📦✨.

⚡ **Instant Feedback**
Your changes appear immediately on your canvas 👀⚡🎨.

---

## 🧠 Architecture 🧠

### 📱 iOS Client

SwiftUI + PencilKit + CoreLocation 📱🧠🖌️

Responsibilities:

* UI + navigation 🎛️📱✨
* canvas rendering 🖼️🎨📦
* drawing + editing tools ✏️🖌️🧠
* tile fetch + save 🌍📡💾

---

### 🌐 Backend API

Node.js + TypeScript + Express 🌐⚙️🧠

Responsibilities:

* tile reads 📦📡
* edit submission ✏️📤
* validation + versioning 🧠🔐
* object storage coordination 🗂️📸

---

### 🗄️ Data Layer

PostgreSQL + object storage 🗄️🧩📦

Stores:

* tile metadata 📦🧠
* canvas objects 🎨📸
* version state 🔢⚙️

---

## 🧩 Tile Model 🧩

The world is partitioned into deterministic geographic tiles 🌍📐📦.

Each tile contains:

```
TileState
tile_id
version
objects[]
```

Objects include:

✏️ StrokeObject
💬 TextObject
🖼️ ImageObject

Tiles update using a **last-write-wins** policy ⚡📦🔁.

---

## 🧪 Testing 🧪

📱 XCTest + XCUITest 🧠📱⚙️
🌐 Jest + Supertest 🧪🌐📡

CI ensures:

* builds succeed 🏗️✅⚡
* endpoints behave correctly 📡🧠✔️
* encoding/decoding contracts hold 🔐📦🧩

---

## 🏗️ Tech Stack 🏗️

**iOS**

Swift 🧠📱
SwiftUI 🎨📱
CoreLocation 📍📡
PencilKit ✏️🖌️
SwiftData 💾🧠

**Backend**

Node.js ⚙️🌐
TypeScript 🧠⚡
Express 🚀🌐

**Data**

Postgres 🗄️📦
Object Storage 📸☁️

**CI**

GitHub Actions ⚡🔁🧠

---

## ⚠️ Known Limitations ⚠️

❌ No global undo history ⏳🚫
❌ Minimal moderation 🚨⚠️
❌ Simple conflict rule 🔁⚡
❌ Editing restricted to local radius 📍🚧

---

## 🌱 Future Directions 🌱

CRDT-based merging 🧠🔁🌐
Global discovery 🌍🔍📡
Moderation systems 🚨⚖️🧠
Rich collaborative layers 🎨🧩🌍

---

## 🌌 Vision 🌌

Locus treats **place as memory** 🧠📍🌍.
Every street corner becomes a shared artifact 🏙️🎨✨.
The world becomes writable 🖊️🌎🧩.

![IMG_1155](https://github.com/user-attachments/assets/6e46d946-0705-4ca1-9e87-b627e7f6a45b)


