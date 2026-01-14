# SKILL : Gardien de la Plateforme de Marque

## Métadonnées

```yaml
version: 1.0
date_creation: Janvier 2026
objectif: Garantir la cohérence de marque QALIA sur tous les contenus
usage: Vérification avant publication
```

---

## Objectif du Skill

Valider chaque contenu contre la plateforme de marque QALIA pour :
1. Assurer la cohérence de voix et ton
2. Vérifier les éléments factuels
3. Protéger l'identité de marque
4. Éviter les erreurs de communication

---

## Checklist de Validation

### 1. Identité QALIA

| Élément | Correct ✅ | Incorrect ❌ |
|---------|-----------|-------------|
| **Nom** | QALIA (avec Q) | Kalia, Qualia, qalia |
| **Nature** | Copilote IA | Outil IA, Robot, Logiciel |
| **Positionnement** | Amplificateur d'expertise | Remplaçant du formateur |
| **Promesse** | Conformité + temps libéré | Conformité garantie seule |

### 2. Chiffres et Prix

| Élément | Correct ✅ | Incorrect ❌ |
|---------|-----------|-------------|
| **Prix mensuel** | 297€/mois | 200€, 299€, 300€ |
| **Engagement** | Sans engagement | Engagement X mois |
| **Temps ingénierie** | 1-2 heures (référence) | 30 minutes |
| **Temps démo** | 1 heure | 30 minutes |
| **Ratio transformation** | 10 jours → 1-2h | 10 jours → 30 min |
| **Indicateurs couverts** | 28/32 | 32/32 |

### 3. Formulations Interdites

| Ne jamais dire | Pourquoi | Alternative |
|----------------|----------|-------------|
| "Gratuit" (pour Skool) | Rien n'est gratuit | "Offert avec QALIA" |
| "QI de 170" | Information personnelle confidentielle | Omettre |
| "Grande probité" | On ne proclame pas, on démontre | Montrer par les actes |
| "Certifié Qualiopi" (Romu) | Faux - travaille avec SAPFI | "Expert Qualiopi" |
| "Outil officiel ministère" | C'est un souhait, pas une réalité | "Vision future" |
| Logo Qualiopi | Romu n'est pas certifié | Ne pas utiliser |

### 4. Voix et Ton

```yaml
voix_qalia:
  autorisee:
    - Directe et franche
    - Experte mais accessible
    - Empathique (vécu la douleur)
    - Confiante sans arrogance
    - Humoristique avec mesure

  interdite:
    - Corporate / froide
    - Arrogante / condescendante
    - Trop technique sans explication
    - Hyperboles excessives
    - Promesses non vérifiables
```

### 5. Cibles

| Cible | Priorité | Langage adapté |
|-------|----------|----------------|
| OF établis | Primaire | Expert, ROI, conformité |
| Coachs individuels | Secondaire | Accessible, temps, simplicité |
| Auditeurs/Certificateurs | Future | Très technique |
| Ministères | Future (aspiration) | Institutionnel |

---

## Processus de Validation

### Étape 1 : Vérification Factuelle

```yaml
questions:
  - Les chiffres sont-ils exacts ? (297€, 2h, 28/32)
  - Les témoignages sont-ils anonymisés ?
  - Les promesses sont-elles vérifiables ?
  - Y a-t-il des affirmations présentées comme faits qui sont des souhaits ?

action_si_erreur: Corriger avant publication
```

### Étape 2 : Vérification Tonale

```yaml
questions:
  - Le ton est-il cohérent avec la voix QALIA ?
  - Le message est-il adapté à la cible ?
  - Y a-t-il des formulations interdites ?
  - Le niveau d'expertise affiché est-il approprié ?

action_si_erreur: Reformuler
```

### Étape 3 : Vérification Visuelle

```yaml
questions:
  - Les couleurs sont-elles conformes ? (#1B7E94, blanc, #932951)
  - Le logo est-il utilisé correctement ?
  - Le logo Qualiopi est-il absent ? (obligatoire)
  - La lisibilité mobile est-elle assurée ?

action_si_erreur: Retoucher avant publication
```

### Étape 4 : Vérification Stratégique

```yaml
questions:
  - Ce contenu sert-il un objectif business ?
  - Le CTA est-il approprié au niveau de douleur ciblé ?
  - Y a-t-il un lien dans le post LinkedIn ? (interdit)
  - Les hashtags sont-ils ≤3 et pertinents ?

action_si_erreur: Ajuster la stratégie
```

---

## Éléments de Marque Non Négociables

### TOUJOURS

✅ QALIA avec Q majuscule
✅ Prix exact : 297€/mois
✅ Temps référence : 1-2 heures
✅ Positionnement : copilote (pas outil)
✅ Anonymisation des témoignages
✅ Skool = "offert" (pas gratuit)

### JAMAIS

❌ Logo Qualiopi dans les visuels
❌ "Certifié Qualiopi" pour Romu
❌ QI ou probité mentionnés
❌ Ministère comme fait établi
❌ Prix différent de 297€
❌ 30 minutes pour ingénierie complète
❌ Lien externe dans post LinkedIn

---

## Grille de Scoring

### Score de Conformité Marque

| Critère | Points | Score |
|---------|--------|-------|
| Chiffres exacts | /20 | |
| Formulations correctes | /20 | |
| Ton approprié | /20 | |
| Visuels conformes | /20 | |
| Stratégie alignée | /20 | |
| **TOTAL** | **/100** | |

### Interprétation

| Score | Action |
|-------|--------|
| 90-100 | ✅ Publier |
| 70-89 | ⚠️ Corrections mineures |
| 50-69 | 🔄 Révision nécessaire |
| <50 | ❌ Refonte complète |

---

## Cas Particuliers

### Cercle Pionnier (Confidentiel)

```yaml
ce_qu_on_peut_dire:
  - "Communauté de formateurs pionniers"
  - "Accès offert avec QALIA"
  - "Places limitées"

ce_qu_on_ne_dit_jamais:
  - Structure de pricing (50€/197€/247€)
  - Normalisation à M13
  - Nombre exact de places par palier
```

### Témoignages

```yaml
obligatoire:
  - Anonymisation complète
  - Contexte suffisant mais flou
  - Autorisation implicite (contenu de démo)

interdit:
  - Noms réels
  - Organisations identifiables
  - Secteurs trop précis
```

### Comparaisons Concurrents

```yaml
autorise:
  - "Contrairement aux solutions génériques..."
  - "Là où ChatGPT s'arrête, QALIA continue"

interdit:
  - Nommer les concurrents
  - Dénigrer directement
  - Comparatifs prix
```

---

## Alertes Automatiques

### Mots-Clés à Surveiller

```yaml
prix:
  pattern: /\d+€/
  verification: Doit être 297€
  alerte_si: Différent

temps:
  pattern: /\d+\s*(min|minutes|heures|jours)/
  verification: Cohérent avec références
  alerte_si: "30 min" pour ingénierie complète

certifications:
  pattern: /(certifié|certification)\s+qualiopi/i
  verification: Pas attribué à Romu
  alerte_si: Attribution directe

gratuit:
  pattern: /gratuit/i
  verification: Jamais pour Skool/Cercle
  alerte_si: Contexte Skool
```

---

## Rapport de Validation

### Template

```markdown
## Rapport Validation Marque

**Contenu** : [Titre/Description]
**Date** : [YYYY-MM-DD]
**Validateur** : [Nom]

### Résultats

| Critère | Score | Notes |
|---------|-------|-------|
| Chiffres | /20 | |
| Formulations | /20 | |
| Ton | /20 | |
| Visuels | /20 | |
| Stratégie | /20 | |
| **TOTAL** | /100 | |

### Corrections Requises
1. [Correction 1]
2. [Correction 2]

### Décision
[ ] ✅ Approuvé
[ ] ⚠️ Approuvé avec corrections
[ ] ❌ Refusé

**Signature** : _______________
```

---

*SKILL-GARDIEN-MARQUE v1.0*
*Objectif : Cohérence marque 100%*
*Usage : Avant chaque publication*
