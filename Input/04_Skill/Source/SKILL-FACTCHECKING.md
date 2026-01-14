# SKILL : Fact-Checking Contenus QALIA

## Métadonnées

```yaml
version: 1.0
date_creation: Janvier 2026
objectif: Vérifier l'exactitude factuelle de tout contenu avant publication
usage: Systématique avant publication
priorite: CRITIQUE
```

---

## Pourquoi le Fact-Checking est Critique

### Risques d'Erreurs Factuelles

1. **Perte de crédibilité** — Une erreur = doute sur tout
2. **Problèmes juridiques** — Fausses promesses = risque légal
3. **Confusion clients** — Chiffres erronés = attentes déçues
4. **Détection par audience** — Formateurs experts repèrent vite

### Principes Fondamentaux

> **Règle d'or** : Si tu ne peux pas le prouver, ne le dis pas.

> **Règle d'argent** : En cas de doute, vérifier ou omettre.

---

## Catégories de Vérification

### 1. Chiffres QALIA

| Élément | Valeur Correcte | Source | Vérification |
|---------|-----------------|--------|--------------|
| Prix mensuel | **297€/mois** | Offre commerciale | Toujours vérifier |
| Engagement | Sans engagement | Offre commerciale | Jamais mentionner durée |
| Temps ingénierie | **1-2 heures** | Retours utilisateurs | Pas 30 min |
| Temps démo | **1 heure** | Process commercial | Pas moins |
| Ratio transformation | **10j → 1-2h** | Mesures terrain | Cohérent |
| Indicateurs couverts | **28/32** | Mapping technique | Pas 32/32 |
| Indicateurs directs | **15** | Mapping technique | Vérifier liste |
| Indicateurs indirects | **9** | Mapping technique | Vérifier liste |
| Indicateurs non couverts | **4** | Mapping technique | Ind. 12-15 |

### 2. Témoignages et Citations

| Vérification | Action |
|--------------|--------|
| Source identifiable | Retrouver dans transcriptions démo |
| Citation exacte | Copier verbatim, pas paraphraser |
| Contexte respecté | Ne pas déformer le sens |
| Anonymisation | Supprimer tout élément identifiant |
| Date approximative | Mentionner période (ex: "fin 2025") |

### 3. Affirmations Qualiopi

| Affirmation | Statut | Source |
|-------------|--------|--------|
| "32 indicateurs" | ✅ Fait | Guide de lecture |
| "7 critères" | ✅ Fait | Guide de lecture |
| "QALIA couvre 28 indicateurs" | ✅ Fait | Mapping interne |
| "Conformité garantie" | ⚠️ Nuancer | Jamais "garantie" seule |
| "Outil officiel ministère" | ❌ Faux | C'est un SOUHAIT |

### 4. Affirmations sur Romuald

| Affirmation | Statut | Réalité |
|-------------|--------|---------|
| "Expert Qualiopi" | ✅ OK | Expérience démontrée |
| "Certifié Qualiopi" | ❌ FAUX | Travaille avec SAPFI |
| "De La Réunion" | ✅ OK | Résidence actuelle |
| "Originaire de Cergy" | ✅ OK | Mais peu pertinent |
| "QI de 170" | ❌ INTERDIT | Ne jamais mentionner |
| "Grande probité" | ❌ INTERDIT | Démontrer, pas proclamer |

---

## Processus de Vérification

### Étape 1 : Identifier les Faits

```yaml
lire_contenu:
  - Surligner tous les chiffres
  - Surligner toutes les citations
  - Surligner toutes les affirmations vérifiables
  - Surligner toutes les promesses

classer:
  - CHIFFRE: Valeur numérique
  - CITATION: Propos attribué
  - AFFIRMATION: Déclaration factuelle
  - PROMESSE: Engagement de résultat
```

### Étape 2 : Vérifier Chaque Élément

```yaml
chiffres:
  - Comparer à la source officielle
  - Vérifier cohérence avec autres contenus
  - En cas de doute, utiliser valeur conservatrice

citations:
  - Retrouver source originale
  - Vérifier exactitude mot pour mot
  - Vérifier contexte non déformé

affirmations:
  - Identifier la source de vérité
  - Distinguer fait vs opinion vs souhait
  - Reformuler si ambigu

promesses:
  - Peut-on la tenir systématiquement ?
  - Y a-t-il des exceptions connues ?
  - Nuancer si nécessaire ("dans la plupart des cas")
```

### Étape 3 : Corriger ou Valider

```yaml
si_correct:
  action: Valider et documenter la source

si_incorrect:
  action: Corriger avec valeur exacte

si_invérifiable:
  action: Supprimer ou reformuler en opinion

si_nuance_nécessaire:
  action: Ajouter contexte ou condition
```

---

## Erreurs Fréquentes à Éviter

### Erreur 1 : Arrondir les Prix

```yaml
incorrect:
  - "200€/mois"
  - "300€/mois"
  - "environ 300€"

correct:
  - "297€/mois"
  - "Pour moins de 300€" (acceptable)
```

### Erreur 2 : Exagérer les Temps

```yaml
incorrect:
  - "30 minutes pour une ingénierie complète"
  - "En quelques clics"

correct:
  - "1-2 heures pour une ingénierie complète"
  - "1 heure en démo, 2 heures en autonomie"
```

### Erreur 3 : Souhaits Présentés comme Faits

```yaml
incorrect:
  - "QALIA est l'outil officiel du ministère"
  - "Recommandé par France Compétences"

correct:
  - "QALIA aspire à devenir une référence institutionnelle"
  - "Conçu pour répondre aux exigences France Compétences"
```

### Erreur 4 : Citations Approximatives

```yaml
incorrect:
  - "Un formateur a dit que c'était génial" (paraphrase)

correct:
  - "'C'est de la folie' — réaction d'un formateur en démo"
```

### Erreur 5 : Promesses Absolues

```yaml
incorrect:
  - "Conformité Qualiopi garantie"
  - "Zéro risque d'échec"

correct:
  - "Conformité native aux exigences Qualiopi"
  - "Réduction significative du risque de non-conformité"
```

---

## Sources de Vérité

### Documents de Référence QALIA

| Document | Contenu | Usage |
|----------|---------|-------|
| SKILL-v3-AMPLIFIE.md | Règles éditoriales | Ton, formulations |
| STRATEGIE-CERCLE-PIONNIER.md | Pricing (confidentiel) | Prix |
| SKILL-MAPPING-INDICATEURS.md | Couverture Qualiopi | Chiffres indicateurs |
| extraits-demos-COMPLET.md | Citations vérifiées | Témoignages |
| CARTOGRAPHIE-SOLUTIONS.md | Douleurs et solutions | Promesses |

### Sources Externes

| Source | Usage | URL |
|--------|-------|-----|
| Guide Qualiopi | Indicateurs, critères | travail-emploi.gouv.fr |
| France Compétences | RNCP, référentiels | francecompetences.fr |
| Légifrance | Textes réglementaires | legifrance.gouv.fr |

---

## Checklist Fact-Check Rapide

### Avant Publication

```markdown
## Checklist Fact-Check

**Contenu** : _______________
**Date** : _______________

### Chiffres
- [ ] Prix = 297€/mois
- [ ] Temps ingénierie = 1-2h (pas 30 min)
- [ ] Indicateurs = 28/32 (pas 32/32)
- [ ] Ratio = 10j → 1-2h

### Citations
- [ ] Source vérifiée
- [ ] Verbatim exact
- [ ] Contexte respecté
- [ ] Anonymisé

### Affirmations
- [ ] Faits ≠ Souhaits
- [ ] Pas de promesses absolues
- [ ] Nuances si nécessaire

### Identité
- [ ] Pas "certifié Qualiopi" pour Romu
- [ ] Pas de mention QI/probité
- [ ] Pas de logo Qualiopi
- [ ] Skool = "offert" (pas gratuit)

### Validation
- [ ] ✅ VALIDÉ
- [ ] ⚠️ CORRECTIONS FAITES
- [ ] ❌ NON PUBLIÉ
```

---

## Gestion des Erreurs Publiées

### Si Erreur Détectée Après Publication

```yaml
erreur_mineure:
  action: Corriger discrètement si possible (stories, commentaires)
  exemple: Typo, chiffre légèrement arrondi

erreur_significative:
  action: Corriger et acknowledger si repéré
  exemple: Prix erroné, temps exagéré

erreur_grave:
  action: Supprimer et republier corrigé
  exemple: Fausse affirmation, citation inventée
```

### Communication Erreur

```yaml
ton:
  - Honnête et direct
  - Pas d'excuses excessives
  - Focus sur la correction

exemple:
  - "Correction : le temps réaliste est 1-2h, pas 30 min.
     Je préfère vous donner le vrai chiffre."
```

---

## Alertes Fact-Check Automatiques

### Patterns à Détecter

```yaml
prix_suspect:
  regex: /(?<!297)\s*€/
  action: Vérifier si 297€

temps_exagere:
  regex: /30\s*min.*ingénierie/i
  action: Alerter - doit être 1-2h

certification_romu:
  regex: /certifié\s+qualiopi/i
  action: Vérifier pas attribué à Romu

promesse_absolue:
  regex: /garanti|100%|toujours|jamais/i
  action: Vérifier nuance présente

gratuit_skool:
  regex: /gratuit.*(skool|cercle)/i
  action: Alerter - doit être "offert"
```

---

## Formation Continue

### Questions à Se Poser

1. "D'où vient ce chiffre ?"
2. "Puis-je le prouver si on me le demande ?"
3. "Est-ce un fait ou mon interprétation ?"
4. "Cette promesse est-elle toujours vraie ?"
5. "Y a-t-il des exceptions que j'omets ?"

### Réflexe Fact-Checker

> Avant d'écrire un chiffre, une citation ou une affirmation :
> **STOP** → **VÉRIFIER** → **SOURCER** → **ÉCRIRE**

---

*SKILL-FACTCHECKING v1.0*
*Priorité : CRITIQUE*
*Usage : Systématique*
