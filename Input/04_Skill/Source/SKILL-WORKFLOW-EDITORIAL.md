# SKILL : Workflow Éditorial Intégré QALIA

## Métadonnées

```yaml
version: 1.0
date_creation: Janvier 2026
objectif: Orchestrer le flux complet de création et validation de contenu
usage: Production contenu LinkedIn et autres plateformes
```

---

## Vue d'Ensemble

Le workflow éditorial QALIA enchaîne 4 étapes obligatoires avant toute publication :

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  1. GÉNÉRATION  │ → │  2. GARDIEN     │ → │  3. FACT-CHECK  │ → │  4. VALIDATION  │
│     Contenu     │    │     Marque      │    │                 │    │    Finale       │
└─────────────────┘    └─────────────────┘    └─────────────────┘    └─────────────────┘
     /post-linkedin        /gardien-marque       /factchecking          /check-post
     /carousel
```

---

## Étape 1 : Génération du Contenu

### Skills Disponibles

| Plateforme | Commande | Usage |
|------------|----------|-------|
| LinkedIn Post | `/post-linkedin` | Posts texte classiques |
| LinkedIn Carrousel | `/carousel` | Carrousels visuels |
| Skool | `/community` | Posts communauté |

### Inputs Requis

```yaml
obligatoire:
  - Douleur ciblée (1-6)
  - Format souhaité
  - Objectif du post

optionnel:
  - Témoignage à intégrer
  - Actualité à commenter
  - Hook spécifique
```

### Output Attendu

- Draft complet du contenu
- Hook + corps + CTA
- Hashtags proposés (si LinkedIn)

---

## Étape 2 : Vérification Marque (Gardien)

### Commande

```
/gardien-marque [contenu généré]
```

### Points de Contrôle

| Catégorie | Vérification |
|-----------|--------------|
| Identité | QALIA avec Q, copilote (pas outil) |
| Prix | 297€/mois exact |
| Chiffres | 1-2h ingénierie, 28/32 indicateurs |
| Interdits | Pas de "gratuit" pour Skool, pas de QI |
| Ton | Direct, expert, empathique |

### Actions Possibles

| Score | Action |
|-------|--------|
| 90-100 | ✅ Passer à étape 3 |
| 70-89 | ⚠️ Corrections mineures puis étape 3 |
| <70 | 🔄 Retour étape 1 (refonte) |

---

## Étape 3 : Fact-Checking

### Commande

```
/factchecking [contenu validé marque]
```

### Points de Contrôle

| Type | Vérification |
|------|--------------|
| Chiffres | Prix, temps, ratios exacts |
| Citations | Source vérifiable, verbatim |
| Affirmations | Fait vs souhait |
| Promesses | Pas d'absolu (garantie, 100%) |

### Actions Possibles

| Résultat | Action |
|----------|--------|
| Validé | ✅ Passer à étape 4 |
| Corrections | ⚠️ Appliquer puis étape 4 |
| Erreur grave | ❌ Retour étape 1 |

---

## Étape 4 : Validation Finale

### Commande

```
/check-post [contenu fact-checké]
```

### Points de Contrôle

| Catégorie | Vérification |
|-----------|--------------|
| Contenu | Un seul message, cohérent |
| LinkedIn | Hook <150 car, 1300-2000 car total |
| Cible OF | Vocabulaire métier, pas condescendant |
| Red Flags | Pas de paradoxe, pas de pitch frontal |

### Décision Finale

| Score | Décision |
|-------|----------|
| 18-20/20 | ✅ PRÊT À PUBLIER |
| 15-17/20 | ⚠️ Ajustements mineurs |
| <15/20 | 🔄 Révision nécessaire |

---

## Workflow Complet (Exemple)

### Scénario : Post Douleur Temps Admin

```yaml
étape_1_génération:
  commande: /post-linkedin
  input: "Douleur 1 - Temps admin, format storytelling"
  output: Draft post

étape_2_gardien:
  commande: /gardien-marque [draft]
  vérification:
    - QALIA bien écrit ✅
    - Prix non mentionné (OK)
    - Ton direct ✅
  score: 95/100 → GO

étape_3_factcheck:
  commande: /factchecking [draft validé]
  vérification:
    - "10 jours → 1-2h" ✅
    - Pas de promesse absolue ✅
  résultat: Validé → GO

étape_4_validation:
  commande: /check-post [draft fact-checké]
  score: 19/20
  décision: ✅ PRÊT À PUBLIER
```

---

## Raccourci Workflow Complet

### Pour lancer tout le workflow en une fois

```
/workflow [type_contenu] [douleur] [format]
```

Exemple :
```
/workflow linkedin 1 storytelling
```

Ce raccourci enchaîne automatiquement les 4 étapes et retourne :
1. Le contenu généré
2. Le rapport de validation
3. Les corrections appliquées
4. La version finale prête à publier

---

## Matrice Décision Rapide

### Si le contenu échoue à une étape

| Étape échouée | Cause fréquente | Action |
|---------------|-----------------|--------|
| Gardien | Mauvaise formulation prix/temps | Corriger les chiffres |
| Gardien | Ton trop corporate | Reformuler plus direct |
| Fact-check | Citation approximative | Retrouver source exacte |
| Fact-check | Promesse absolue | Nuancer le message |
| Validation | Hook trop long | Raccourcir <150 car |
| Validation | Post trop court/long | Ajuster longueur |

---

## Temps Estimé par Workflow

| Étape | Temps IA | Temps Humain (revue) |
|-------|----------|---------------------|
| Génération | 30s | 2-3 min |
| Gardien | 15s | 1 min |
| Fact-check | 15s | 1 min |
| Validation | 15s | 1 min |
| **TOTAL** | ~1 min | 5-6 min |

**Gain vs manuel** : 30-45 min économisées par post

---

## Checklist Avant Publication

```markdown
## Checklist Finale

- [ ] Workflow 4 étapes complété
- [ ] Score gardien ≥ 90/100
- [ ] Fact-check validé
- [ ] Score validation ≥ 18/20
- [ ] Pas de lien dans le post LinkedIn
- [ ] Hashtags ≤ 3
- [ ] Hook < 150 caractères
- [ ] Longueur 1300-2000 caractères
- [ ] Créneau publication optimal (8h-9h ou 17h-18h)

✅ GO PUBLICATION
```

---

*SKILL-WORKFLOW-EDITORIAL v1.0*
*Objectif : Qualité garantie avant publication*
*Usage : Chaque contenu produit*
