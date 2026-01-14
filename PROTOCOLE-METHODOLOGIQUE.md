# PROTOCOLE MÉTHODOLOGIQUE — LinkedIn QALIA S1 2026

## À VALIDER PAR ROMU AVANT EXÉCUTION

---

## CONTEXTE & OBJECTIFS FINANCIERS

### Situation actuelle
- Romu seul (Mehdi indisponible)
- Coaching par **Alec Henry / Entrepreneurs.com**
- Première cliente intégrée (Shirley) — Cercle Pionnier + Apporteur d'affaires

### Objectifs financiers (méthode Hormozi)

| Horizon | Objectif | Milestone |
|---------|----------|-----------|
| **4 mois** (Mai 2026) | 100K€/mois | ~333 clients à 300€ OU offres premium |
| **6 mois** (Juillet 2026) | 150K€/mois | Scaling + communauté active |
| **12 mois** (Janvier 2027) | 1M€/mois | Écosystème complet |
| **24 mois** (Janvier 2028) | 100M€/an | Enterprise + international |

---

## PHASE 0 : ORGANISATION DES FICHIERS

### Structure Input (fichiers sources)

```
Input/
├── 01_Strategie/
│   ├── Definition-Avatar-QALIA.md
│   ├── Manifeste-Douleur-QALIA.md
│   └── Strategie-Acquisition-QALIA.md
├── 02_Skill/
│   ├── Skill-Source-v2.md
│   ├── Personnalite-Romu.md
│   └── Exemples-Templates.md
├── 03_Ligne_Editoriale_SOURCE/
│   ├── Ligne-Editoriale-Q1-Source.md
│   ├── Posts-Janvier-Source.md
│   ├── Posts-Fevrier-Source.md
│   └── Posts-Mars-Source.md
├── 04_Demonstrations/
│   ├── Demo-Oct3-PM.txt (wow moments à extraire)
│   ├── Demo-Nov19.txt
│   ├── Demo-Sep16.txt
│   └── Demo-Sep29.txt
├── 05_Feedback/
│   ├── Feedback-Epouse-10Jan.txt
│   ├── Feedback-Enrichissement-1.txt
│   └── Feedback-Enrichissement-2.txt
├── 06_Methodes/
│   ├── Hormozi-Playbook.md
│   ├── Chemin-Critique-Hormozi.md
│   ├── Customer-Journey-Blueprint.txt
│   └── Guide-Algorithme-LinkedIn.txt
└── 07_Qalia_Source/
    ├── Instructions-Qalia.md
    ├── Orchestration.md
    └── [DOC-01 à DOC-09].md
```

### Structure Output (livrables)

```
Output/
├── SKILL-v3-Amplifie.md
├── LIGNE-EDITORIALE-S1-2026.md
├── Posts/
│   ├── POSTS-JANVIER-2026.md
│   ├── POSTS-FEVRIER-2026.md
│   ├── POSTS-MARS-2026.md
│   ├── POSTS-AVRIL-2026.md
│   ├── POSTS-MAI-2026.md
│   └── POSTS-JUIN-2026.md
└── Claude-Code/
    └── .claude/
        └── commands/
            └── qalia-linkedin-post.md
```

---

## PHASE 1 : ANALYSE DES SOURCES

### 1.1 Extraction des "Wow Moments" des démos

**Objectif :** Extraire les réactions émotionnelles RÉELLES des prospects pour les utiliser (anonymisées) dans les posts.

| Fichier | À extraire |
|---------|------------|
| Demo-Oct3-PM.txt | Réactions "c'est de la folie", moments de surprise |
| Demo-Nov19.txt | Objections, transformations, décisions |
| Demo-Sep16.txt | Questions, doutes, résolutions |
| Demo-Sep29.txt | Contextes spécifiques, douleurs exprimées |

**Livrables :**
- Liste de 20+ citations anonymisées utilisables
- 10+ situations de douleur concrètes
- 5+ transformations avant/après

### 1.2 Synthèse Méthode Hormozi

**Principes clés à intégrer :**
- Offre irrésistible (valeur > prix perçu)
- Lead generation magnétique
- Système de vente à fort taux de conversion
- Livraison scalable sans perte de qualité
- Rétention client (LTV maximisée)

### 1.3 LinkedIn Algorithm 2026

**Règles confirmées :**
- PDF Carousels = 3x vidéo, 6x texte
- ≤3 hashtags (niche)
- Golden hour : répondre 60-90 min
- Varier formats (pas 3x même format)
- Dwell time = temps de lecture mesuré
- Contenu expertise > viralité

### 1.4 Customer Journey

**Étapes à mapper sur la ligne éditoriale :**
1. Awareness (découverte)
2. Consideration (évaluation)
3. Decision (achat)
4. Retention (fidélisation)
5. Advocacy (recommandation)

---

## PHASE 2 : RECONSTRUCTION DU SKILL AMPLIFIÉ

### Principes de reconstruction

| Aspect | Source originale | Amplification |
|--------|------------------|---------------|
| **Ton** | Direct, ancré, authentique | + Intensité émotionnelle |
| **Unicité** | Chaque post différent | Préserver variété ABSOLUE |
| **Storytelling 5 lignes** | OCCASIONNEL (pas systématique) | Outil parmi d'autres |
| **Émotions** | Présentes | Extraites des démos réelles |
| **Méthode Hormozi** | Non intégrée | Intégrer principes |

### Ce que le SKILL doit contenir

1. **Identité Romu** — amplifiée, pas modifiée
2. **Cible OF** — enrichie avec douleurs des démos
3. **Règles LinkedIn 2026** — mises à jour
4. **Bibliothèque de formats** — 15+ formats différents
5. **Intégration Le Cercle** — progressive
6. **Wow moments anonymisés** — exploitables
7. **Progression narrative** — sur 6 mois

### Formats de posts (variété obligatoire)

| Format | Usage | Fréquence |
|--------|-------|-----------|
| Texte seul percutant | Prise de position | 30% |
| Texte + image authentique | Témoignage anonymisé | 20% |
| Carousel PDF éducatif | Process, guide | 25% |
| Vidéo courte (30-60s) | Behind the scenes | 10% |
| Question engagement | Discussion | 10% |
| Storytelling personnel | Origines, valeurs | 5% |

**RÈGLE ABSOLUE :** Aucun post ne doit ressembler au précédent dans sa structure.

---

## PHASE 3 : IMPLÉMENTATION CLAUDE CODE

### Création du slash command

**Fichier :** `.claude/commands/qalia-linkedin-post.md`

**Contenu :**
- Accès au SKILL complet
- Instructions pour générer UN post unique
- Checklist de validation automatique
- Interdiction d'appliquer mécaniquement une structure

### Test de validation

Avant validation finale :
- [ ] Générer 5 posts test
- [ ] Vérifier unicité de chaque post
- [ ] Vérifier respect de la voix Romu
- [ ] Vérifier anonymisation témoignages

---

## PHASE 4 : LIGNE ÉDITORIALE 6 MOIS

### Architecture narrative progressive

| Mois | Thème | Intensité | Nouveauté |
|------|-------|-----------|-----------|
| **Janvier** | Le Réveil | ★★☆☆☆ | Reprise, premiers signaux |
| **Février** | La Preuve | ★★★☆☆ | Témoignages anonymisés, vidéo |
| **Mars** | L'Autorité | ★★★★☆ | Expert reconnu, masterclass teaser |
| **Avril** | L'Écosystème | ★★★★☆ | Le Cercle (Skool), Assets |
| **Mai** | La Croissance | ★★★★★ | Scaling, offres structurées |
| **Juin** | Le Bilan | ★★★★★ | Rétrospective, vision S2, urgence été |

### Intégrations progressives

#### Le Cercle (Skool)
- **Mars** : Première mention subtile ("communauté de formateurs")
- **Avril** : Annonce officielle avec bénéfices
- **Mai** : Témoignages membres, avantages exclusifs
- **Juin** : Offre spéciale été

#### Intérêt Auditeurs/Certificateurs
- **Avril** : Post sur "Qualiopi vu par les auditeurs"
- **Mai** : Teaser "mode auditeur" en préparation
- **Juin** : Annonce partenariat potentiel

#### Programme Apporteur d'Affaires
- **Mai** : Mention naturelle (cas client qui recommande)
- **Juin** : Annonce formelle avec conditions

### ANONYMISATION OBLIGATOIRE

**AVANT (interdit) :**
> "Anthony de SAPFI. Formation travaux sur corde."

**APRÈS (correct) :**
> "Un formateur spécialisé dans les travaux en hauteur. 20 jours de formation à restructurer."

**Règle :**
- Jamais de prénom réel
- Jamais de nom d'organisme
- Conserver : secteur, durée, problème, résultat

---

## PHASE 5 : CONTRÔLE QUALITÉ

### Checklist par post

**Unicité :**
- [ ] Structure différente du post précédent
- [ ] Format différent (si 2 textes seuls d'affilée)
- [ ] Hook unique (pas de formule répétée)

**Voix Romu :**
- [ ] Ça sonne comme lui à haute voix
- [ ] Direct, pas diplomatique mou
- [ ] Ancré (La Réunion, Cergy, terrain)

**LinkedIn 2026 :**
- [ ] Hook < 150 caractères
- [ ] ≤3 hashtags niche
- [ ] Pas de demande de likes
- [ ] Format varié

**Anonymisation :**
- [ ] Aucun prénom réel
- [ ] Aucun nom d'organisme
- [ ] Contexte préservé

**Méthode Hormozi :**
- [ ] Valeur > promotion
- [ ] Lead nurturing progressif
- [ ] CTA adapté à l'étape du funnel

**Cohérence narrative :**
- [ ] S'inscrit dans la progression mensuelle
- [ ] Pas de répétition de message récent
- [ ] Engagement = conversation, pas monologue

### Checklist mensuelle

- [ ] Mix de formats respecté
- [ ] Intensité progressive
- [ ] Nouveautés du mois introduites
- [ ] Témoignages anonymisés variés
- [ ] Le Cercle mentionné si prévu

---

## CALENDRIER D'EXÉCUTION

### Après validation du protocole

| Jour | Phase | Livrable |
|------|-------|----------|
| J+1 | Phase 0 | Organisation fichiers Input/Output |
| J+2 | Phase 1 | Extraction wow moments démos |
| J+3 | Phase 2 | SKILL v3 amplifié |
| J+4 | Phase 3 | Implémentation Claude Code |
| J+5 | Phase 4 | Ligne éditoriale S1 + Posts Janvier |
| J+6 | Phase 4 | Posts Février + Mars |
| J+7 | Phase 4 | Posts Avril + Mai + Juin |
| J+8 | Phase 5 | Contrôle qualité global |
| J+9 | Commit | Push final sur GitHub |

---

## POINTS DE VALIDATION

### Point 1 : Après Phase 1
- Valider les wow moments extraits
- Valider les situations de douleur

### Point 2 : Après Phase 2
- Valider le SKILL amplifié
- Tester la voix avec 3 posts exemples

### Point 3 : Après Phase 4 (Janvier)
- Valider les 7 posts de janvier
- Vérifier unicité et anonymisation

### Point 4 : Final
- Revue complète des 67 posts
- Validation contrôle qualité

---

## CE QUI A ÉTÉ CORRIGÉ vs ERREURS PRÉCÉDENTES

| Erreur précédente | Correction |
|-------------------|------------|
| Storytelling 5 lignes appliqué partout | Outil OCCASIONNEL, variété absolue |
| Témoignages non anonymisés | TOUS anonymisés impérativement |
| SKILL superficiellement annoté | Reconstruction amplifiée complète |
| Pas d'extraction émotions démos | Phase dédiée d'extraction |
| Pas d'implémentation Claude Code | Slash command dédié |
| Structure identique tous posts | Checklist unicité obligatoire |
| Objectifs financiers non intégrés | Méthode Hormozi intégrée |
| Le Cercle absent | Intégration progressive |
| Auditeurs non ciblés | Plan de ciblage M3-M6 |

---

## VALIDATION REQUISE

**Romu, ce protocole te convient-il ?**

Questions à valider :
1. Les objectifs financiers sont-ils corrects ?
2. La structure Input/Output est-elle adaptée ?
3. Les phases sont-elles dans le bon ordre ?
4. Les points de validation sont-ils suffisants ?
5. Y a-t-il des éléments manquants ?

**Une fois validé, j'exécute phase par phase avec contrôle à chaque étape.**

---

*Protocole créé le 14 janvier 2026*
*En attente de validation*
