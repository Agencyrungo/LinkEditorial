# SYSTÈME ÉDITORIAL — Documentation Complète

## Vue d'ensemble

Ce système est conçu pour être :
- **Scalable** : Ajouter des réseaux, des produits, des membres d'équipe
- **Duplicable** : Réutilisable pour tout projet/marque
- **Évolutif** : S'adapte aux phases de croissance
- **Claude Code Ready** : Optimisé pour l'IA

---

## Architecture

```
/
├── Input/                    → SOURCES (ce qu'on utilise)
├── Output/                   → LIVRABLES (ce qu'on produit)
├── Banque_Contenus/          → MÉDIAS (photos, vidéos, templates)
├── _Template_Systeme/        → MODÈLE VIERGE (à dupliquer)
├── .claude/commands/         → COMMANDES CLAUDE CODE
└── SYSTEME.md                → CE FICHIER
```

---

## Flux de travail

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   INPUT     │ ──► │  CLAUDE     │ ──► │   OUTPUT    │
│   Sources   │     │   CODE      │     │  Livrables  │
└─────────────┘     └─────────────┘     └─────────────┘
      │                   │                    │
      ▼                   ▼                    ▼
  Témoignages        Génération           Publication
  Actualités         + Contrôle           + KPI
  Stratégie
```

---

## Objectifs financiers (Méthode Hormozi)

| Horizon | Objectif | Actions clés |
|---------|----------|--------------|
| **4 mois** | 100K€/mois | Scaling clients, offres premium |
| **6 mois** | 150K€/mois | Communauté active (Le Cercle) |
| **12 mois** | 1M€/mois | Écosystème complet |
| **24 mois** | 100M€/an | Enterprise + International |

---

## Principes fondamentaux

### 1. Unicité absolue
Chaque post doit être unique en :
- Structure
- Format
- Hook
- Angle

**INTERDIT :** Appliquer mécaniquement une formule à tous les posts.

### 2. Anonymisation obligatoire
Tous les témoignages doivent être anonymisés :
- ❌ "Anthony de SAPFI, formation travaux sur corde"
- ✅ "Un formateur spécialisé dans les travaux en hauteur"

### 3. Actualités et contexte
Avant chaque génération de contenu :
1. Vérifier `Input/07_Actualites/Presentes/`
2. Vérifier `Input/06_Temoignages/A_Collecter/`
3. Intégrer si pertinent

### 4. Progression narrative
La ligne éditoriale suit une progression sur 6 mois :
- Janvier : Le Réveil
- Février : La Preuve
- Mars : L'Autorité
- Avril : L'Écosystème
- Mai : La Croissance
- Juin : Le Bilan

---

## Pour Claude Code

### Commandes disponibles
- `/qalia-post` : Génère un post LinkedIn unique
- `/qalia-skill` : Affiche le SKILL complet
- `/qalia-check` : Vérifie un post avant publication

### Fichiers clés à lire
1. `Input/04_Skill/SKILL-v3.md`
2. `Input/02_Identite/Personnalite/personnalite-romu.md`
3. `Output/Reseaux_Sociaux/LinkedIn/Ligne_Editoriale/`

### Règles de génération
1. **Jamais** de structure répétitive
2. **Toujours** vérifier actus et témoignages
3. **Toujours** anonymiser
4. **Toujours** varier le format

---

## Ajouter un nouveau réseau social

1. Créer le dossier dans `Output/Reseaux_Sociaux/[NOM]/`
2. Ajouter l'algorithme dans `Input/01_Strategie/Algorithmes/[NOM]/`
3. Créer la ligne éditoriale spécifique
4. Adapter les formats aux spécificités du réseau

## Ajouter un membre d'équipe

1. Créer `Input/02_Identite/Equipe/[Prenom_NOM]/`
2. Ajouter fichiers : bio, ton, spécialités
3. Créer section dédiée dans le SKILL si la personne communique

## Ajouter un partenaire/ambassadeur

1. Créer le dossier dans `Input/11_Ecosysteme/[Type]/[Nom]/`
2. Documenter : offre, conditions, contact
3. Intégrer dans la ligne éditoriale si pertinent

---

## Template duplicable

Le dossier `_Template_Systeme/` contient une version vierge de cette architecture, prête à être dupliquée pour tout nouveau projet.

**Usage :**
```bash
cp -r _Template_Systeme/ Nouveau_Projet/
```

---

*Système créé pour QALIA — Scalable, duplicable, évolutif*
*Compatible Claude Code*
