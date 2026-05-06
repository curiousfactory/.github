# Curious Factory

> Studio français créateur de **systèmes physiques de party games immersifs** pour lieux de loisir.

## Produits

### 🥊 Quiz Boxing

Quiz multi-joueur sur ring de boxe — borne tactile + télécommandes physiques + score temps réel + LED + son immersif. Déployé dans des bowlings/arcades/escape games depuis 2021.

### 🍹 VIP Arena

Système physique de party games multi-joueurs pour lieux de loisir. Box Raspberry Pi + phones joueurs + immersion audio/lumière DMX. **Beta target : mi-juin 2026.**

## Stack technique

- **Embedded** : C17 + SDL2 (engine), Go (server + fleet agent), Yocto Linux (OS)
- **Cloud** : Go + Fiber (backend), Vue 3 + Tailwind (editor + admin)
- **Mobile** : PWA vanilla JS / Vue 3 lite
- **Hardware** : Raspberry Pi 4/5/CM5
- **Lighting** : Art-Net DMX uniquement
- **Stockage** : SQLite (box) + PostgreSQL (cloud)
- **Infra** : Docker compose, GitHub Actions CI/CD, OVH VPS

## Repos

Tous les repos sont **privés**. Liste accessible aux membres CF via [github.com/orgs/curiousfactory](https://github.com/orgs/curiousfactory).

Composants principaux VIP Arena : `curiousfactory-engine` (Hydra), `viparena-server` (Core), `curiousfactory-fleet` (Orbit), `viparena-cloud` (Hermes + Cipher + Sentinel), `curiousfactory-ui` (cf-ui design system), `viparena-platform` (Beacon Yocto), `viparena-schemas` (contrats partagés), `ci-workflows` (CI réutilisables).

## Équipe

- **Emmanuel Lena** — Dev lead / CTO-bound
- **Thibaut Marzano** — CEO / Product Owner
- **Noélyne** (Nolly) — Stagiaire content
- **Dimitri Bocquet** — Consultant infra (Quiz Boxing)

## Contact

- 🐛 **Bugs / sécu** : voir [SECURITY.md](https://github.com/curiousfactory/.github/blob/main/SECURITY.md)
- 💼 **Commercial** : contact@curiousfactory.fr
- 🌐 **Web** : [curiousfactory.fr](https://curiousfactory.fr)
