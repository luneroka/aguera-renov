<div align="right">

🇬🇧 [English Version](./README.EN.md)

</div>

<div align="center">

# 🏗️ AGUERA RENOV

### Site web professionnel pour une entreprise de rénovation

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)]()
[![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=for-the-badge&logo=sanity&logoColor=white)]()
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)]()

Site vitrine moderne développé pour une entreprise française de rénovation, combinant une expérience utilisateur soignée, une optimisation SEO avancée et une gestion dynamique du contenu.

**🌐 Site en ligne :** https://www.aguera-renov.fr

</div>

---

## ✨ Présentation

AGUERA RENOV est un site web déployé en production pour une entreprise réelle du secteur de la rénovation.

L'objectif du projet était de créer une présence en ligne moderne capable de :

- 🏠 Présenter les services et le savoir-faire de l'entreprise
- 📸 Mettre en valeur les réalisations et chantiers terminés
- 📈 Améliorer la visibilité sur les moteurs de recherche
- 📩 Générer des demandes de devis qualifiées
- 🛠️ Permettre la mise à jour du contenu sans intervention technique

---

## 🚀 Fonctionnalités

### Site public

- Design responsive (mobile, tablette et desktop)
- Animations et interactions modernes
- Présentation détaillée des services
- Galerie de réalisations
- Formulaire de contact avec notifications par email
- Architecture optimisée pour le référencement naturel
- Pages légales et réglementaires
- Génération automatique du sitemap

### Gestion du contenu

- Intégration d'un CMS Headless
- Gestion dynamique des réalisations
- Gestion dynamique des services
- Modification des informations de l'entreprise
- Workflow simple pour les utilisateurs non techniques

---

## 🛠️ Stack Technique

| Catégorie | Technologies |
|------------|-------------|
| Frontend | Next.js 14, React, TypeScript |
| Styling | Tailwind CSS, DaisyUI |
| Animations | Framer Motion |
| CMS | Sanity |
| Emails | Resend |
| Déploiement | Vercel |

---

## 🏛️ Architecture

```text
Visiteur
   │
   ▼
Frontend Next.js
   │
   ├── Sanity CMS
   │      └── Gestion du contenu
   │
   └── Resend
          └── Formulaire de contact
```

### Pourquoi cette architecture ?

✅ Excellent référencement naturel (SEO)

✅ Temps de chargement rapides

✅ Mise à jour du contenu simplifiée

✅ Faible maintenance

✅ Déploiement scalable

---

## 🎯 Points Clés

### Développement orienté SEO

Le site a été conçu avec une forte attention portée à la visibilité sur les moteurs de recherche :

- Optimisation des métadonnées
- Hiérarchie de pages structurée
- Génération automatique du sitemap
- Approche mobile-first
- Optimisation des performances

### Autonomie du client

Le site permet au dirigeant de gérer lui-même :

- L'ajout de nouvelles réalisations
- La mise à jour des services
- La modification du contenu
- La gestion de sa présence en ligne

### Projet réel en production

Contrairement à de nombreux projets de démonstration, cette application est utilisée quotidiennement par une entreprise réelle.

---

## 📷 Captures d'écran

<div align="center">

| Accueil | Services |
|-----------|-----------|
| <img src="./docs/screenshots/aguera-index.png" width="450"> | <img src="./docs/screenshots/aguera-services.png" width="450"> |

| Réalisations | Fiche Google Business |
|-----------|-----------|
| <img src="./docs/screenshots/aguera-realisations.png" width="450"> | <img src="./docs/screenshots/aguera-google.png" width="450"> |

| Contact |
|-----------|
| <img src="./docs/screenshots/aguera-contact.png" width="900"> |

</div>

---

## 💻 Développement local

```bash
npm install
npm run dev
```

Ouvrir :

```text
http://localhost:3000
```

---

## 🔐 Variables d'environnement

Cette version publique du dépôt ne contient aucun secret de production.

```env
RESEND_API_KEY=

SANITY_PROJECT_ID=
SANITY_DATASET=
SANITY_API_VERSION=
SANITY_READ_TOKEN=

RECIPIENT_EMAIL=
```

---

## 📚 Ce que ce projet m'a apporté

Ce projet m'a permis de renforcer mes compétences sur :

- Le développement d'applications Next.js prêtes pour la production
- L'intégration de CMS Headless
- Les bonnes pratiques SEO
- Le développement de projets client réels
- Le responsive design
- L'intégration de services d'email transactionnel
- La modélisation de contenu
- Le déploiement et la maintenance d'applications web

---

## ⚠️ Avertissement

Ce dépôt constitue une version portfolio d'un projet client réel.

Les informations sensibles, identifiants, secrets et configurations spécifiques au client ont été supprimés ou anonymisés avant publication.

---

## 👨‍💻 Auteur

**Yoann Robert**

Développeur Full-Stack & Passionné de Data

- GitHub : https://github.com/luneroka
- Portfolio : https://yoannrobert.com
- LinkedIn : https://www.linkedin.com/in/robertyoann/

---
⭐ Si ce projet vous intéresse, n'hésitez pas à consulter mes autres réalisations sur GitHub.
