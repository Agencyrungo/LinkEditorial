# SKILL : Reporting & Mesure KPIs Éditoriaux QALIA

## Métadonnées

```yaml
version: 1.0
date_creation: Janvier 2026
objectif: Mesurer et analyser les performances du contenu LinkedIn QALIA
usage: Analyse hebdomadaire/mensuelle
```

---

## Objectif du Skill

Fournir un cadre de mesure des performances éditoriales pour :
1. Tracker l'efficacité du contenu LinkedIn
2. Identifier les formats/sujets performants
3. Optimiser la stratégie éditoriale
4. Mesurer le ROI du temps investi

---

## KPIs Primaires (Engagement)

### Métriques LinkedIn

| KPI | Formule | Objectif Bon | Objectif Excellent |
|-----|---------|--------------|-------------------|
| **Taux d'engagement** | (Likes + Comments + Shares) / Impressions × 100 | ≥ 3% | ≥ 5% |
| **Impressions** | Vues du post | ≥ 1000 | ≥ 5000 |
| **Commentaires** | Nombre commentaires | ≥ 10 | ≥ 25 |
| **Partages** | Nombre partages | ≥ 3 | ≥ 10 |
| **Dwell Time** | Temps lecture moyen | ≥ 30s | ≥ 60s |

### Métriques Profil

| KPI | Formule | Objectif Bon | Objectif Excellent |
|-----|---------|--------------|-------------------|
| **Visites profil** | Clics profil post-publication | ≥ 50 | ≥ 150 |
| **Demandes connexion** | Nouvelles connexions/semaine | ≥ 10 | ≥ 30 |
| **Abonnés newsletter** | Croissance mensuelle | ≥ 5% | ≥ 15% |

---

## KPIs Secondaires (Conversion)

### Funnel QALIA

| Étape | KPI | Objectif |
|-------|-----|----------|
| Awareness | Impressions totales/mois | ≥ 20k |
| Interest | Clics profil/mois | ≥ 500 |
| Consideration | DM reçus/mois | ≥ 20 |
| Intent | Demandes démo | ≥ 5 |
| Conversion | Clients signés | ≥ 2 |

### Taux de Conversion

```yaml
awareness_to_interest: 2.5% (Impressions → Clics profil)
interest_to_consideration: 4% (Clics → DM)
consideration_to_intent: 25% (DM → Demande démo)
intent_to_conversion: 40% (Démo → Client)
```

---

## KPIs par Type de Contenu

### Performance par Format

| Format | Engagement Moyen | Meilleur Usage |
|--------|------------------|----------------|
| Post texte pur | 2-3% | Storytelling, douleurs |
| Carrousel | 4-6% | Tutoriels, listes |
| Sondage | 5-8% | Engagement, données |
| Document PDF | 3-5% | Guides, checklists |
| Vidéo native | 3-4% | Témoignages, démos |

### Performance par Thématique

| Thème | Engagement Typique | Priorité |
|-------|-------------------|----------|
| Douleur temps admin | ÉLEVÉ | 1 |
| Conformité Qualiopi | ÉLEVÉ | 1 |
| Pilotage/indicateurs | MOYEN | 2 |
| Témoignages | TRÈS ÉLEVÉ | 1 |
| Behind-the-scenes | MOYEN | 3 |
| Actualités formation | FAIBLE | 4 |

---

## Grille de Reporting Hebdomadaire

### Template Semaine

```markdown
## Reporting Semaine [XX] - [Date]

### Posts Publiés
| Jour | Titre | Format | Douleur | Engagement |
|------|-------|--------|---------|------------|
| Lun | | | | |
| Mar | | | | |
| Mer | | | | |
| Jeu | | | | |
| Ven | | | | |

### Métriques Globales
- Impressions totales : ___
- Engagement moyen : ___%
- Commentaires totaux : ___
- Visites profil : ___
- Nouveaux abonnés : ___

### Top Performer
- Post : [Titre]
- Pourquoi : [Analyse]

### Flop de la Semaine
- Post : [Titre]
- Pourquoi : [Analyse]

### Actions S+1
1. [ ] Action 1
2. [ ] Action 2
```

---

## Grille de Reporting Mensuel

### Template Mois

```markdown
## Reporting Mois [Mois YYYY]

### Vue d'Ensemble
| Métrique | M-1 | M actuel | Évolution |
|----------|-----|----------|-----------|
| Posts publiés | | | |
| Impressions | | | |
| Engagement moyen | | | |
| Visites profil | | | |
| DM reçus | | | |
| Démos demandées | | | |

### Performance par Format
| Format | Nombre | Engagement Moyen |
|--------|--------|------------------|
| Texte | | |
| Carrousel | | |
| Sondage | | |

### Performance par Douleur
| Douleur | Posts | Engagement | Conversion |
|---------|-------|------------|------------|
| Temps admin | | | |
| Conformité | | | |
| Pilotage | | | |
| PSH | | | |

### Top 3 Posts du Mois
1. [Titre] — [Engagement]%
2. [Titre] — [Engagement]%
3. [Titre] — [Engagement]%

### Apprentissages
- Ce qui marche : [...]
- Ce qui ne marche pas : [...]
- À tester le mois prochain : [...]

### Objectifs M+1
- [ ] Objectif 1
- [ ] Objectif 2
- [ ] Objectif 3
```

---

## Alertes et Seuils

### Alertes Performance

```yaml
alerte_rouge:
  engagement: < 1%
  impressions: < 500
  commentaires: 0

alerte_orange:
  engagement: 1-2%
  impressions: 500-1000
  commentaires: 1-3

normal:
  engagement: 2-4%
  impressions: 1000-3000
  commentaires: 4-10

excellent:
  engagement: > 4%
  impressions: > 3000
  commentaires: > 10
```

### Actions Correctives

| Alerte | Diagnostic | Action |
|--------|------------|--------|
| Engagement < 1% | Hook faible | Retravailler accroche |
| 0 commentaires | Pas de question | Ajouter CTA engagement |
| Impressions < 500 | Timing/algo | Tester autre créneau |
| Engagement > 5% | Format gagnant | Répliquer le format |

---

## Outils Recommandés

### Natifs LinkedIn

| Outil | Usage | Accès |
|-------|-------|-------|
| LinkedIn Analytics | Métriques posts | Gratuit |
| Creator Mode | Insights avancés | Gratuit |
| LinkedIn Newsletter | Abonnés directs | Gratuit |

### Externes

| Outil | Usage | Coût |
|-------|-------|------|
| Shield Analytics | Dashboard complet | ~15€/mois |
| Taplio | Analytics + scheduling | ~39€/mois |
| Google Sheets | Tracking manuel | Gratuit |

---

## ROI Temps Éditorial

### Calcul ROI

```yaml
temps_creation:
  post_standard: 30-45 min
  carrousel: 60-90 min
  strategie_mois: 2-3h

valeur_generee:
  impressions_1000: ~10€ équivalent pub
  lead_qualifié: ~100-200€
  client_signé: 297€/mois × LTV

roi_mensuel:
  temps_investi: 8-10h
  valeur_pub_équivalente: ~200€
  leads_générés: X × 150€
  clients_signés: Y × 3564€ (12 mois)
```

---

## Benchmarks Secteur Formation

### Moyennes LinkedIn Formation Pro

| Métrique | Moyenne Secteur | Objectif QALIA |
|----------|-----------------|----------------|
| Engagement | 2.1% | ≥ 3% |
| Impressions/post | 800 | ≥ 1500 |
| Commentaires/post | 5 | ≥ 10 |
| Croissance followers/mois | 3% | ≥ 8% |

---

*SKILL-REPORTING v1.0*
*Objectif : Mesure et optimisation continue*
*Fréquence : Hebdomadaire + Mensuel*
