# 👋 Salut, moi c'est Pierre

Développeur **Full-Stack** passionné par les architectures robustes, la qualité logicielle et les produits qui résolvent de vrais problèmes.

Je conçois des applications web performantes et évolutives avec un fort accent sur :

- ⚙️ L'architecture logicielle
- 🧪 La qualité de code et les tests automatisés
- 🚀 Les performances et la scalabilité
- 📡 Les plateformes de streaming vidéo temps réel

En parallèle de mon activité professionnelle, je développe plusieurs projets personnels autour de l'escalade, du streaming et des applications SaaS.

---

## 🚀 Domaines d'expertise

### Backend

- PHP 8+
- Symfony
- API Platform
- Doctrine ORM
- JWT Authentication
- Scheb 2FA
- Messenger

### Frontend

- React
- Next.js
- TypeScript
- TanStack Router
- React Query
- TailwindCSS
- Ant Design
- Stimulus

### Streaming & Vidéo

- FFmpeg
- MediaMTX
- WebRTC
- HLS
- RTMP / RTSP / SRT
- Video.js

### Infrastructure

- Docker
- Linux
- GitHub Actions
- CI/CD
- PostgreSQL

---

## 🏗️ Architecture & Qualité

Parce qu'un projet doit pouvoir évoluer sereinement dans le temps :

- Clean Architecture
- API REST
- Domain-Driven Design (DDD)
- CQRS
- Architecture orientée événements
- Analyse statique avec PHPStan
- Tests unitaires et fonctionnels avec PHPUnit
- Contrôle des règles d'architecture avec PHPArkitect
- Automatisation qualité avec GrumPHP
- Conventional Commits
- Intégration et déploiement continus

---

## 🧗 Projet principal — Climbing Live

**Climbing Live** est une plateforme de retransmission vidéo conçue pour les compétitions d'escalade.

L'objectif est de permettre à des organisateurs de diffuser facilement un événement avec plusieurs caméras tout en conservant une faible latence et une qualité de diffusion optimale.

### Fonctionnalités

- 🎥 Diffusion multi-caméras
- 📱 Ingestion des flux depuis smartphones ou caméras
- ⚡ Streaming WebRTC faible latence
- 📺 Diffusion HLS
- 🏆 Gestion des compétitions
- 🎬 Gestion des flux vidéo
- 📊 Interface d'administration

### Architecture

```text
Smartphones / Caméras
        │
        ▼
 RTMP / RTSP / SRT
        │
        ▼
     MediaMTX
      (Ingest)
        │
        ▼
 FFmpeg Workers
    (Transcode)
        │
 ┌──────┴──────┐
 ▼             ▼
HLS         WebRTC
 ▼             ▼
 Next.js Video Player
```

### Dépôts

| Projet | Description | Stack |
|---------|-------------|---------|
| `climbing-live` | Frontend de diffusion multi-caméras | Next.js, TypeScript, TailwindCSS |
| `climbing-live-api` | API de gestion des compétitions et des athlètes | Symfony, API Platform |
| `climbing-live-streams` | Infrastructure de streaming et de transcodage | MediaMTX, FFmpeg, Docker |

---

## 🧠 Projets en cours

### 🧗 EKIP

Plateforme communautaire dédiée aux grimpeurs pour trouver des partenaires, organiser des sorties et partager leur progression.

### 🎯 GoalTracker AI

Application SaaS de suivi d'objectifs intégrant l'intelligence artificielle pour générer automatiquement des plans d'action et des sous-tâches.

---

## 💼 Expérience professionnelle

Développement d'applications métier sur mesure avec Symfony pour diverses organisations.

---

## 🛠️ Stack principale

| Frontend | Backend | Streaming | Infrastructure |
|-----------|-----------|-----------|-----------|
| React | Symfony | FFmpeg | Docker |
| Next.js | API Platform | MediaMTX | Linux |
| TypeScript | Doctrine | WebRTC | PostgreSQL |
| TailwindCSS | JWT / 2FA | HLS | GitHub Actions |

---

## 🌱 En dehors du code

- 🧗 Passionné d'escalade de bloc et de falaise
- 🎯 Objectif personnel : continuer à progresser vers le haut niveau en bloc
- 🥾 Amateur de trek longue distance
- 🎬 Création audiovisuelle et projets vidéo

---

## 📫 Me contacter

- 💼 LinkedIn : www.linkedin.com/in/pierre-dumas-18559521b

---

> *“Code, grimpe, répète.”*
