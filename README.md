<div align="center">🌌 Discord Media Gallery

⚡ "DISCORD" × "GITHUB ACTIONS" × "NODE.JS" × "GITHUB PAGES"

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Automated+Discord+Media+Gallery;Cyberpunk+%2F+Dark+Neon+Experience;Discord+%E2%86%92+GitHub+Actions+%E2%86%92+GitHub+Pages;Fully+automated+media+synchronization" alt="Typing animation"/><br>""GitHub"(https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)"(https://github.com/Nathan-Pro-FR/Discord_Github_Action)
""GitHub Actions"(https://img.shields.io/badge/GitHub_Actions-Automated-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)"(https://github.com/Nathan-Pro-FR/Discord_Github_Action/actions)
""Node.js"(https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)" (https://nodejs.org/)
""Discord"(https://img.shields.io/badge/Discord-API-5865F2?style=for-the-badge&logo=discord&logoColor=white)" (https://discord.com/developers/docs)
""GitHub Pages"(https://img.shields.io/badge/GitHub_Pages-Deployed-222222?style=for-the-badge&logo=githubpages&logoColor=white)"(https://pages.github.com/)
""License"(https://img.shields.io/github/license/Nathan-Pro-FR/Discord_Github_Action?style=for-the-badge)" (LICENSE)

<br>💬 Collecte automatiquement vos médias Discord.
⚙️ Les synchronise avec GitHub Actions.
🌐 Les transforme en galerie web.

<br><img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:7B2FFF,100:FF00FF&height=120&section=header&text=SYSTEM%20ONLINE&fontSize=28&fontColor=ffffff&animation=twinkling" width="100%" alt="System online banner"/></div>---

🛰️ "SYSTEM STATUS"

«Discord Media Gallery est une galerie multimédia statique au style Cyberpunk / Dark Neon, alimentée automatiquement par un salon Discord.»

╔══════════════════════════════════════════════════════════════╗
║                    🌌 MEDIA GALLERY                          ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║   💬 DISCORD                                                 ║
║       │                                                      ║
║       │  📡 API                                              ║
║       ▼                                                      ║
║   🤖 NODE.JS                                                 ║
║       │                                                      ║
║       │  🔄 SYNC                                             ║
║       ▼                                                      ║
║   📦 DONNEES.JSON                                            ║
║       │                                                      ║
║       ├───────────────┐                                      ║
║       ▼               ▼                                      ║
║   📊 STATS         🌐 GITHUB PAGES                           ║
║       │               │                                      ║
║       ▼               ▼                                      ║
║   🔔 DISCORD       🖥️ GALLERY                               ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

---

✨ "FEATURES"

<table>
<tr>
<td width="50%">🤖 Auto Sync

Synchronisation automatique des médias provenant d'un salon Discord.

</td>
<td width="50%">🖼️ Images & Vidéos

Support des principaux médias envoyés sur Discord.

</td>
</tr><tr>
<td>⚙️ GitHub Actions

Pipeline automatisé sans serveur backend permanent.

</td>
<td>🌐 GitHub Pages

Hébergement statique avec un coût d'infrastructure nul.

</td>
</tr><tr>
<td>📊 Statistics

Détection des médias ajoutés, supprimés et rafraîchis.

</td>
<td>🔔 Discord Notifications

Rapports de synchronisation directement dans Discord.

</td>
</tr><tr>
<td>🚨 Error Alerts

Notification privée en cas d'échec du workflow.

</td>
<td>🌌 Cyberpunk UI

Interface Dark Neon / Cyberpunk responsive.

</td>
</tr>
</table>---

🎞️ "LIVE PREVIEW"

<div align="center"><!-- Remplace cette image par ton GIF réel lorsque tu l'auras ajouté --><a href="https://github.com/Nathan-Pro-FR/Discord_Github_Action">
<img src="docs/preview.gif" alt="Discord Media Gallery Preview" width="900">
</a><br>🖥️ Live Demo

"🌐 OUVRIR LA GALERIE" (https://nathan-pro-fr.github.io/Discord_Github_Action/)

</div>«💡 Si "docs/preview.gif" n'existe pas encore, remplace simplement cette image par ton futur GIF de démonstration.»

---

🧬 "HOW IT WORKS"

flowchart LR
    A["💬 Discord"] -->|"📡 API"| B["🤖 recupere_medias.js"]

    B -->|"📦 Génération"| C["donnees.json"]

    C --> D["📊 calcul_stats.js"]
    C --> E["🌐 GitHub Pages"]

    D -->|"🔔 Stats"| F["envoi_webhook.js"]
    F --> G["💬 Discord"]

    E --> H["🖥️ Gallery"]

    B -.->|"❌ Failure"| I["🚨 notif_erreur_mp.js"]
    I --> G

🔄 Pipeline

        💬 DISCORD
             │
             │ 📡 API
             ▼
     ┌─────────────────┐
     │  🤖 NODE.JS     │
     │  MEDIA FETCHER  │
     └────────┬────────┘
              │
              ▼
       📦 donnees.json
              │
       ┌──────┴──────┐
       │             │
       ▼             ▼
  📊 ANALYTICS    🌐 WEBSITE
       │             │
       ▼             ▼
  🔔 WEBHOOK      🖥️ GALLERY
       │
       ▼
  💬 DISCORD

---

🧰 "TECH STACK"

<div align="center">Technologie| Rôle
🟨 JavaScript| Logique applicative
🟢 Node.js| Scripts backend
🟦 HTML5| Structure du frontend
🎨 CSS3| Interface Cyberpunk
📦 JSON| Données des médias
⚙️ GitHub Actions| Automatisation
💬 Discord API| Collecte
🔔 Discord Webhooks| Notifications
🌐 GitHub Pages| Hébergement
🐙 Git| Versionnement

</div>---

🗂️ "PROJECT STRUCTURE"

Discord_Github_Action/
│
├── 🤖 .github/
│   └── ⚙️ workflows/
│       └── sync_discord.yml
│
├── 🎨 css/
│   └── style.css
│
├── 📚 docs/
│   └── preview.gif
│
├── 🖼️ image/
│
├── 📊 calcul_stats.js
├── 📦 donnees.json
├── 📈 dashboard.html
├── 🔔 envoi_webhook.js
├── 🌐 index.html
├── 📱 manifest.json
├── 🚨 notif_erreur_mp.js
├── 📦 package.json
├── 🤖 recupere_medias.js
├── ⚡ script.js
├── 🧠 sw.js
│
├── 📖 README.md
├── 🇫🇷 README.fr.md
├── 📚 README.pro.md
├── 🏗️ ARCHITECTURE.md
├── 🔐 SECURITY.md
├── 🤝 CODE_OF_CONDUCT.md
└── 📜 LICENSE

---

🤖 "AUTOMATED WORKFLOW"

Le workflow GitHub Actions orchestre automatiquement le système.

flowchart TD
    A["⏰ Schedule / Manual"] --> B["📥 Checkout"]
    B --> C["🟢 Setup Node.js"]
    C --> D["📦 Install Dependencies"]
    D --> E["💾 Backup Dataset"]
    E --> F["💬 Fetch Discord Media"]
    F --> G["📊 Calculate Statistics"]
    G --> H["🔔 Send Discord Webhook"]
    H --> I{"📦 Dataset changed?"}

    I -->|"YES"| J["💾 Commit"]
    J --> K["🚀 Push"]

    I -->|"NO"| L["⏭️ Skip Commit"]

    K --> M["✅ Complete"]
    L --> M

    F -.->|"❌ ERROR"| N["🚨 Failure Alert"]
    G -.->|"❌ ERROR"| N
    H -.->|"❌ ERROR"| N

    N --> O["💬 Discord DM"]

---

⏱️ "AUTOMATIC SYNCHRONIZATION"

Le workflow peut être exécuté automatiquement grâce à GitHub Actions.

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

Tu peux également déclencher manuellement une synchronisation depuis :

🐙 GitHub
   ↓
⚙️ Actions
   ↓
🔄 Sync Discord Media
   ↓
▶️ Run workflow

---

📊 "STATISTICS ENGINE"

Le système compare deux datasets :

📦 donnees.previous.json
            │
            │ 🔍 COMPARISON
            ▼
     📊 calcul_stats.js
            ▲
            │
📦 donnees.json

Il détecte :

Statut| Signification
➕ "added"| Nouveau média
➖ "removed"| Média supprimé
🔄 "refreshed"| URL actualisée
📦 "total"| Nombre total

Exemple

╭─────────────────────────────────╮
│       📊 SYNC REPORT            │
├─────────────────────────────────┤
│                                 │
│  ➕ ADDED       12               │
│  ➖ REMOVED      2               │
│  🔄 REFRESHED    4               │
│  📦 TOTAL      158               │
│                                 │
│  🟢 STATUS: SUCCESS              │
╰─────────────────────────────────╯

---

🔔 "DISCORD NOTIFICATIONS"

Après une synchronisation réussie, un Embed Discord peut être envoyé.

┌─────────────────────────────────────────┐
│ 🔄  GALERIE SYNCHRONISÉE                │
├─────────────────────────────────────────┤
│                                         │
│ ➕ Nouveaux médias       12              │
│ ➖ Médias supprimés       2              │
│ 🔄 URLs rafraîchies       4              │
│ 📦 Total                158              │
│                                         │
│ 🟢 Synchronisation réussie               │
│                                         │
│ 🌐 Ouvrir la galerie                    │
│ ⚙️ Voir le workflow                     │
└─────────────────────────────────────────┘

---

🚨 "FAILURE SYSTEM"

En cas d'échec :

sequenceDiagram
    participant G as ⚙️ GitHub Actions
    participant N as 🚨 Error Handler
    participant D as 💬 Discord

    G->>N: ❌ Workflow failure
    N->>N: 🔍 Collect error
    N->>D: 📩 Send private alert
    D-->>N: ✅ Delivered

---

🔐 "SECURITY"

⚠️ Secrets

Ne mets jamais ton token Discord directement dans le code.

❌ Mauvais

const token = "MY_DISCORD_TOKEN";

✅ Correct

env:
  DISCORD_TOKEN: ${{ secrets.DISCORD_TOKEN }}

---

🔑 GitHub Secrets

Configure les secrets dans :

⚙️ Settings
   └── 🔐 Secrets and variables
       └── Actions

Secret| Obligatoire| Utilisation
"DISCORD_TOKEN"| 🔴| Authentification du bot
"CHANNEL_ID"| 🔴| Salon Discord
"DISCORD_WEBHOOK_URL"| 🟡| Notifications
"DISCORD_USER_ID"| 🟡| Alertes privées

«🚨 Si ton token Discord est exposé, révoque-le immédiatement depuis le Discord Developer Portal.»

---

💻 "LOCAL DEVELOPMENT"

1️⃣ Clone

git clone https://github.com/Nathan-Pro-FR/Discord_Github_Action.git

cd Discord_Github_Action

2️⃣ Install

npm install

3️⃣ Configure

Linux / macOS

export DISCORD_TOKEN="your_token"
export CHANNEL_ID="your_channel_id"

Windows PowerShell

$env:DISCORD_TOKEN="your_token"
$env:CHANNEL_ID="your_channel_id"

4️⃣ Run

npm run sync

---

🧪 "NPM COMMANDS"

╭─────────────────────────────────────────────╮
│                 📦 NPM                      │
├─────────────────────────────────────────────┤
│                                             │
│  npm run sync         🤖 Discord Sync       │
│  npm run stats        📊 Statistics         │
│  npm run webhook      🔔 Discord Webhook    │
│  npm run notify-error 🚨 Error Notification │
│                                             │
╰─────────────────────────────────────────────╯

---

🌐 "GITHUB PAGES"

Le frontend est entièrement statique.

          🐙 GITHUB
             │
             ▼
       📦 donnees.json
             │
       ┌─────┴─────┐
       ▼           ▼
    🌐 HTML     ⚡ JS
       │           │
       └─────┬─────┘
             ▼
          🎨 CSS
             │
             ▼
      🌌 CYBERPUNK UI
             │
             ▼
        👤 VISITOR

Aucun serveur backend permanent n'est nécessaire.

---

🖥️ "FRONTEND"

Le frontend repose sur trois éléments principaux :

🌐 HTML

Structure de la galerie.

⚡ JavaScript

Chargement de "donnees.json" et génération dynamique des médias.

🎨 CSS

Thème Dark Neon / Cyberpunk, responsive et animé.

---

🧩 "FILE RESPONSIBILITIES"

Fichier| Fonction
🤖 "recupere_medias.js"| Collecte Discord
📊 "calcul_stats.js"| Statistiques
🔔 "envoi_webhook.js"| Webhook Discord
🚨 "notif_erreur_mp.js"| Alertes d'erreur
🌐 "index.html"| Galerie
📈 "dashboard.html"| Dashboard
⚡ "script.js"| Frontend
🎨 "css/style.css"| UI
📦 "donnees.json"| Dataset
⚙️ "sync_discord.yml"| CI/CD
📱 "manifest.json"| PWA
🧠 "sw.js"| Service Worker

---

🎨 "CYBERPUNK MODE"

L'identité visuelle du projet repose sur :

🌌 DARK BACKGROUND
        +
💠 NEON GLOW
        +
⚡ ANIMATIONS
        +
🟣 CYBERPUNK COLORS
        +
🖥️ RESPONSIVE UI

Ambiance

        ╔════════════════════════════╗
        ║                            ║
        ║      SYSTEM ONLINE         ║
        ║                            ║
        ║      ▓▓▓▓▓▓▓▓▓▓▓▓          ║
        ║      ▓ MEDIA CORE ▓         ║
        ║      ▓▓▓▓▓▓▓▓▓▓▓▓          ║
        ║                            ║
        ║    STATUS: 🟢 ONLINE       ║
        ║                            ║
        ╚════════════════════════════╝

---

🧭 "ROADMAP"

✅ Discord Media Sync
✅ GitHub Actions
✅ Automatic JSON generation
✅ Statistics engine
✅ Discord notifications
✅ Error alerts
✅ GitHub Pages
✅ Cyberpunk UI

🔲 Lightbox mode
🔲 Media filtering
🔲 Infinite scroll
🔲 Pagination
🔲 Thumbnail optimization
🔲 Advanced dashboard

---

📚 "DOCUMENTATION"

Document| Description
🇬🇧 ""README.md"" (README.md)| Documentation principale
🇫🇷 ""README.fr.md"" (README.fr.md)| Documentation française
🏗️ ""ARCHITECTURE.md"" (docs/ARCHITECTURE.md)| Architecture technique
📚 ""README.pro.md"" (README.pro.md)| Documentation professionnelle
🔐 ""SECURITY.md"" (SECURITY.md)| Politique de sécurité
🤝 ""CODE_OF_CONDUCT.md"" (CODE_OF_CONDUCT.md)| Code de conduite

---

💬 "DISCORD BOT PERMISSIONS"

Le bot doit avoir au minimum :

👁️ View Channel
📖 Read Message History

Pour les alertes privées, le bot doit également pouvoir contacter l'utilisateur configuré.

---

🌟 "SUPPORT THE PROJECT"

Si ce projet t'est utile :

<div align="center">⭐ Star le repository

🐛 Signaler un bug

💡 Proposer une fonctionnalité

🔀 Contribuer

<br>""Star" (https://img.shields.io/github/stars/Nathan-Pro-FR/Discord_Github_Action?style=for-the-badge&logo=github&label=STARS)" (https://github.com/Nathan-Pro-FR/Discord_Github_Action/stargazers)
""Issues" (https://img.shields.io/github/issues/Nathan-Pro-FR/Discord_Github_Action?style=for-the-badge&logo=github)" (https://github.com/Nathan-Pro-FR/Discord_Github_Action/issues)
""Pull Requests" (https://img.shields.io/github/issues-pr/Nathan-Pro-FR/Discord_Github_Action?style=for-the-badge&logo=github)" (https://github.com/Nathan-Pro-FR/Discord_Github_Action/pulls)

</div>---

📜 "LICENSE"

Ce projet est distribué sous licence MIT.

Voir ""LICENSE"" (LICENSE) pour plus d'informations.

---

<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:7B2FFF,100:FF00FF&height=100&section=footer&animation=twinkling" width="100%" alt="Neon footer" />🌌 DISCORD MEDIA GALLERY

"SYSTEM ONLINE" • "MEDIA SYNC" • "CYBERPUNK UI"

Made with 💜 by "Nathan-Pro-FR" (https://github.com/Nathan-Pro-FR)

<br><sub>⚡ Discord → GitHub Actions → JSON → GitHub Pages ⚡</sub>

</div>
