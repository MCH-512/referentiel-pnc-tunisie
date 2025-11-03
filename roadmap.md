# Roadmap : Référentiel PNC Tunisie

## 📌 État actuel (version 1.0)

✅ **Fonctionnalités livrées** :
- Site web statique avec Docsify
- Navigation thématique organisée
- Contenu complet des trois textes réglementaires :
  - Décision 240/2019 (cadre opérationnel)
  - Décision 201/2009 (conditions de licence)
  - Décision 226/2004 (programmes de formation)
- Identification des gaps réglementaires
- Propositions d'amélioration concrètes

✅ **Public cible** :
- PNC en activité
- Candidats PNC
- Instructeurs
- Centres de formation
- Autorités (DGAC)

---

## 🚀 Phase 2 : Améliorations techniques (1-3 mois)

### 🔍 2.1. Recherche texte avancée
- **Objectif** : Permettre aux utilisateurs de trouver rapidement des articles spécifiques
- **Fonctionnalités** :
  - Barre de recherche en haut de page
  - Résultats affichés par pertinence
  - Filtrage par document source (240/2019, 201/2009, 226/2004)
- **Priorité** : ⭐⭐⭐⭐⭐

### 📱 2.2. Version mobile optimisée
- **Objectif** : Rendre le référentiel consultable facilement sur smartphone
- **Fonctionnalités** :
  - Menu hamburger responsive
  - Police adaptée aux petits écrans
  - Boutons de navigation plus larges
- **Priorité** : ⭐⭐⭐⭐

### 📥 2.3. Export PDF des sections
- **Objectif** : Permettre le téléchargement hors ligne des contenus
- **Fonctionnalités** :
  - Bouton "Exporter en PDF" sur chaque page
  - Formatage adapté pour l'impression
  - En-tête avec référence réglementaire
- **Priorité** : ⭐⭐⭐⭐

---

## 🔧 Phase 3 : Fonctionnalités métier (3-6 mois)

### 📅 3.1. Calendrier des échéances personnelles
- **Objectif** : Aider les PNC à gérer leurs obligations réglementaires
- **Fonctionnalités** :
  - Formulaire simple pour entrer sa date de licence
  - Calcul automatique des dates de recyclage
  - Rappels visuels (couleurs selon l'urgence)
  - Export des dates importantes
- **Priorité** : ⭐⭐⭐⭐⭐

### 🗂️ 3.2. Dossier PNC numérique (version bêta)
- **Objectif** : Proposer un modèle de carnet de vol numérique
- **Fonctionnalités** :
  - Formulaire d'enregistrement des vols
  - Calcul automatique des heures par type d'avion
  - Alertes pour qualification de type à renouveler
  - Version imprimable conforme à la réglementation
- **Priorité** : ⭐⭐⭐⭐

### 🎓 3.3. Banque de scénarios CRM
- **Objectif** : Compléter le gap sur la formation CRM
- **Fonctionnalités** :
  - 10 scénarios types avec descriptions détaillées
  - Grilles d'évaluation comportementale
  - Vidéos d'exemples (hébergées sur YouTube/Vimeo)
  - Quiz interactifs avec feedback
- **Priorité** : ⭐⭐⭐⭐⭐

---

## 🌐 Phase 4 : Intégration et collaboration (6-12 mois)

### 🤝 4.1. Espace contributeurs
- **Objectif** : Impliquer la communauté professionnelle
- **Fonctionnalités** :
  - Formulaire de soumission de bonnes pratiques
  - Système de notation par les pairs
  - Validation par un comité technique
  - Attribution de crédits de formation
- **Priorité** : ⭐⭐⭐

### 🔄 4.2. API publique
- **Objectif** : Permettre l'intégration avec d'autres systèmes
- **Fonctionnalités** :
  - Endpoints REST pour récupérer les textes réglementaires
  - Documentation technique complète
  - Exemples d'intégration avec des systèmes de formation
  - Limites d'utilisation raisonnables
- **Priorité** : ⭐⭐

### 🏛️ 4.3. Module de dialogue avec la DGAC
- **Objectif** : Faciliter la remontée des gaps vers les autorités
- **Fonctionnalités** :
  - Formulaire structuré pour les propositions d'amélioration
  - Suivi des statuts des propositions
  - Base de connaissances des décisions antérieures
  - Calendrier des consultations publiques
- **Priorité** : ⭐⭐⭐⭐

---

## 📊 Indicateurs de succès

| Indicateur | Objectif à 3 mois | Objectif à 6 mois | Objectif à 12 mois |
|------------|------------------|-------------------|-------------------|
| Nombre d'utilisateurs uniques/mois | 100 | 500 | 2000 |
| Temps moyen passé sur le site | 3 minutes | 5 minutes | 8 minutes |
| Taux de rebond | < 60% | < 45% | < 30% |
| Nombre de contributions externes | 5 | 20 | 50 |
| Nombre de partenariats officiels | 1 | 3 | 5 |

---

## 👥 Équipe et processus

### Structure minimale pour la Phase 2 :
- **Responsable technique** : Développement des fonctionnalités (toi-même initialement)
- **Veille réglementaire** : Mise à jour des textes (collaboration avec un juriste)
- **Communauté** : Modération des contributions (bénévoles expérimentés)

### Processus de décision :
1. **Identification** d'un besoin ou d'une amélioration
2. **Priorisation** selon l'impact sécurité et complexité
3. **Prototypage** rapide (1-2 semaines)
4. **Test** avec un groupe restreint d'utilisateurs
5. **Déploiement** progressif
6. **Évaluation** avec les indicateurs définis

---

## 💰 Modèle économique durable

### Sources de financement :
- **Subventions publiques** : Fonds de développement de l'aviation civile
- **Partenariats** : Contrats avec les centres de formation
- **Crowdfunding** : Campagne de soutien par la communauté PNC
- **Prestations de service** : Formation sur mesure pour les compagnies

### Principes :
- **Gratuité** pour tous les contenus réglementaires
- **Transparence** totale sur les sources de financement
- **Indépendance** éditoriale garantie
- **Réinvestissement** des surplus dans de nouvelles fonctionnalités

---

## 🎯 Prochaines étapes immédiates

1. **Cette semaine** :
   - [ ] Activer la recherche texte (modifier `index.html`)
   - [ ] Créer une version mobile test (ajouter meta viewport)

2. **Mois prochain** :
   - [ ] Réunir un groupe test de 5 PNC pour feedback
   - [ ] Préparer le premier scénario CRM (passager perturbateur)
   - [ ] Contacter un centre de formation pour partenariat pilote

3. **Trimestre** :
   - [ ] Présenter le projet à la DGAC pour validation conceptuelle
   - [ ] Demander un soutien technique à l'Université de l'Aviation Civile
   - [ ] Lancer une campagne de communication sur LinkedIn

---

> 💡 **Philosophie** : Ce référentiel n'est pas seulement un outil technique, mais une **initiative citoyenne** pour améliorer la sécurité aérienne en Tunisie par la transparence, la collaboration et l'innovation. Chaque fonctionnalité doit servir cet objectif premier.

*Document mis à jour : Novembre 2023*
