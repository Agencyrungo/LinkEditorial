# [DOC-03] - Cartographie des compétences

# [DOC-03] - Cartographie des compétences

### [METADATA]

> ID du document : DOC-03 | Version : QALIA-2025-09-V1.0 | Champ d'application : Cartographie des compétences | Cible Canvas : Core | Priorité : 🔵 Canonical
> 
> 
> Propriétaire : Romuald DARIOT | Autorité : Qalia System | Fonction : canmore
> 

| **Attribut** | **Valeur** | **Référence** |
| --- | --- | --- |
| ID du document | DOC-03 | Identifiant du système |
| Version | V1.0 | `[Config/Qalia-V1.0]` |
| Champ d'application | Cartographie des compétences | `[Config/Qalia-scope]` |
| Canvas] Cible | Core | `[Config/Qalia-canvas]` |
| Priorité | 🔵 Canonical | `[Config/Qalia-priority]` |
| Propriétaire | Romuald DARIOT | `[Config/Qalia-owner]` |
| Autorité | Système Qalia | `[Config/Qalia-authority]` |
| Classification | Interne | `[Config/Qalia-classification]` |
| de production | Production | `[Config/Qalia-status]` |
| Orchestration | "DOC-03 → DOC-04 → DOC-05" | `[Config/Qalia-orchestration]` |
| Format de sortie | **Markdown uniquement** (+ Mermaid) | `[Config/Qalia-format]` |
| Règle de priorité | "DOC-01 > DOC-00 > (DOC-02-DOC-09)" | `[Config/Qalia-precedence]` |
| Politique linguistique | Voir DOC-01 - Langue et code | DOC-01 - Langue et code |
| **DOC-02 Dépendance** | **Consommateur en lecture seule** | `[Config/Qalia-dependency]` |

## Règle de complétude (canonique)

- Tous les documents doivent être complets : 100% des séquences, scénarios, évaluations.
- Les portes sont uniquement des WARN, elles ne bloquent jamais la publication.
- Pas d'espaces réservés "à produire" : toujours générer un contenu complet.

## Étiquetage des compétences (canonique)

Chaque compétence doit porter : - Un niveau Bloom : [Bloom : Appliquer|Analyser|Evaluer|Créer|Comprendre] - Un type de connaissance (KT) : un type de connaissance (KT) : [KT : Knowledge|Know-how|Behaviors] - un format de code : [1+-M](about:blank#fn1)[0-9]{2}-C[0-9]{2}$

## [TOC] - Table des matières

- [PREAMBULE] - Rôle et règle d'activation
- [ACTIVATION] - Règles d'activation pilotées par DOC-02
- [STANDARDS] - Références et politique des sources
- [CADRE] - Cadre normatif et principes
- [STRUCTURE] - Tableau des compétences et codification
- [WORKFLOW] - Processus de construction (Mermaid)
- [USAGE] - Mode obligations & archivage
- [RNQ-MAPPING] - Couverture de la V9 & priorités
- [QA] - Contrôles qualité & points de vigilance
- [OUTPUTS] - Livrables autorisés
- [RESEARCH] - Recherches et traces sur le web
- [CI] - Points de contrôle de validation
- [MESSAGES] - Modèles d'assistants
- [SECURITE] - Sécurité
- [JURIDIQUE] - Juridique

---

## [PREAMBULE] - Rôle et règle d'activation

**DOC-03 est la vue pivot des compétences ciblées.** Il relie les compétences aux **objectifs opérationnels**, aux **indicateurs Qualiopi** et aux **tâches d'évaluation DOC-07**, assurant ainsi la traçabilité et la conformité réglementaire.

> Dépendance critique : DOC-03 fonctionne en mode lecture seule pour les données de DOC-02. Le score de complexité et le mode restent la source unique de DOC-02.
> 

DOC-03 sert de **source unique de vérité** pour l'alignement pédagogique, de **référence normative** pour l'audit Qualiopi, de **base contractuelle** pour le RNCP/RS et d'**outil de pilotage** pour l'amélioration continue.

> Invariant en lecture seule : La note DOC-02 est la source unique ; DOC-03 conserve un accès en lecture seule.
> 

Lorsque l'information n'est pas disponible, il convient d'indiquer l'écart conformément à DOC-01 - Langage et code, sans stocker de phrases toutes faites.

---

## [ACTIVATION] - Règles d'activation pilotées par DOC-02

**Préconditions (HUD)**: - DOC-02 Phases 1→6 disponibles (TBD permis) - Si voie RS/RNCP : TRACE-SOURCES DOC-08 complétée (statut Actif, dates).

## [STANDARDS] - Politique en matière de références et de sources

- **DOC-01 - Constitution & Préséance** (règle absolue)
- **DOC-00 - Orchestration** (GATE_01 / GATE_02 non bloquante)
- **DOC-02 - Besoins et score** (objectifs/score en lecture seule)
- **DOC-04 - Plan de formation** (consommateur de séquencement)
- **DOC-05 - Scénario pédagogique** (consommateur d'activités)
- **DOC-07 - Évaluation et décision** (lien d'évaluation)
- **DOC-08 - Matrice RNQ 32/32** (couverture des indicateurs et preuves)
- **DOC-09 - IA et éthique** (double validation humaine si l'IA est impliquée)

**Externe**: **Guide officiel Qualiopi V9** (V.9 - 8 Jan 2024, 7 critères, 32 indicateurs)

**Politique des sources**

**Référence**: ANCRE_SOURCES_V1 - si une compétence est liée à une certification, cibler d'abord le registre **national** (FR : France Compétences), selon **{{SOURCES.V1.DECISION_TREE}}**.

---

## [Cadre] - Cadre normatif et principes

- **Références du système**: Code du travail, décret Qualiopi 2019-565, **guide de lecture Qualiopi V9**, RNQ 32/32, notes RNCP/RS.
- **Principes**:
    1. Alignement systématique sur les objectifs du **DOC-02** (lecture seule).
    2. Traçabilité complète avec les indicateurs RNQ et les tâches **DOC-07** 
    3. **Évaluabilité** avec preuves attendues par compétence
    4. **Progression** le long des niveaux de Bloom
    5. Lien avec le**RNCP/RS** le cas échéant (y compris le titre, le **code**, le **certificateur**, la **date d'enregistrement**, la **date d'expiration**)
- **Inclusivité**: pour chaque compétence, lister systématiquement les **adaptations PSH** lorsque cela est pertinent (si `publics.psh = Oui` dans DOC-02) afin de garantir l'évaluabilité pour tous.

---

## [STRUCTURE] - Tableau des compétences et codification

**Tableau de correspondance des compétences (en-têtes officiels)**:
ID / Référence de la compétence (RNCP si disponible) | Objectif opérationnel | Activités / Moyens pédagogiques | Évaluation (DOC-07 TEST/GRID) | Preuves attendues | Accessibilité / Aménagements (PSH) | Propriétaires (Prestataire/Formateur) | Rétention | | - | - | | - | - | - | - | - | - | | - | | `<Placeholder>` | `<placeholder>` | `<placeholder>` | `<placeholder>` | `<placeholder>` *(C0/T0/Mix)* | `<placeholder>` | <placeholder> | <placeholder> | <placeholder> | `<placeholder>` |

**Règles**: - Ajouter les étiquettes de provenance`(C0`, `T0`, `Mix`) dans la colonne **Expected evidence**. - Placeholders neutres tant que non renseigné par l'utilisateur. - Le lien vers DOC-07 (TEST/GRID) est obligatoire ainsi que la colonne PSH.

## [WORKFLOW] - Processus de construction (Mermaid)

```mermaid
flowchart LR
  A[DOC-02 objectives<br/>READ-ONLY] --> B[Semantic analysis]
  B --> C[Thematic grouping]
  C --> D[Competency formulation]
  D --> E[Link DOC-07 assessments]
  E --> F[Expert validation]
  F --> G{QA Checks}
  G -->|Pass| H[Finalized mapping]
  G -->|Fail| I[WARN + Suggestions]
  I --> D

```

---

## [USAGE] - Obligations par mode et archivage

### Obligations par mode

| **Mode** | **Score** | **DOC-03 Exigence** | **Conditions** |
| --- | --- | --- | --- |
| EXPRESS | 0-3 | Optionnel | - |
| STANDARD | 4-6 | Recommandé | **Obligatoire** en cas de multi-sites ou d'hétérogénéité |
| COMPLET | 7-10 | **Requis** | Prérequis pour DOC-04 |

### Cas d'utilisation obligatoire

- Pistes RNCP/RS
- Programmes >5 jours
- Actions avec évaluation sommative
- Multi-sites (toujours nécessaire)

### Archivage

- **Cartographies liées au RNCP/RS**: 10 ans
- **Cartographies non certifiantes**: 3 ans
- **Traçabilité**: maintenir les liens DOC-02/DOC-07

> Note contextualisée : Si RNCP/RS : 10 ans ; sinon 3 ans (rappel affiché lors de la finalisation de la cartographie)
> 

### Rappel sur la politique de publication

> Politique de publication : la génération est toujours complète ; les contrôles de qualité sont informatifs et ne bloquent jamais la sortie.
> 

**Couverture évaluation (lien DOC-07)**- Proposer types d'évaluation **Diag/Form/Som** dans la table (intention) - Lier un **placeholder** vers DOC-07**(GRID/TEST**) sans figer le barème ; détail final en DOC-07.

---

## [RNQ-MAPPING] - Couverture et priorités de la V9

### Indicateurs prioritaires DOC-03

**Accent mis sur les indicateurs** suivants : **5, 6, 7, 11, 24, 30**

> WARN automatique si une compétence ne couvre aucun indicateur prioritaire
> 

### Carte des indicateurs 32

| **Critère** | **Indicateurs** | **Application dans la cartographie** | **Priorité** |
| --- | --- | --- | --- |
| 1. Information | 1-4 | Documentation sur les conditions préalables et les objectifs | Norme |
| 2. Objectifs | **5-8** | **Lien direct pour chaque compétence** | **HAUT** |
| 3. Accueil/suivi | 9-12 | Conditions pour les activités | Norme |
| 4. Moyens | 13-16 | Ressources par compétence | Norme |
| 5. Équipe | 17-20 | Expertise requise par module | Norme |
| 6. Environnement | **21-25** | **Veille et évolution des compétences** | **HAUT** |
| 7. Amélioration | **26-32** | **Traçabilité et mises à jour** | **HAUT** |

### Règles de couverture

- **Mode complet**: Tous les indicateurs doivent être couverts
- **Densité minimale**: ≥1 indicateur/compétence
- **Densité optimale**: 2-3 indicateurs/compétence

---

## [QA] - Contrôles de qualité et points de vigilance

**Contrôles auto (WARN-only)**: - ≥1 indicateur RNQ par ligne ; PSH rempli ; lien DOC-07 présent - Objectif manquant ou provenance non étiquetée → WARN - Génération jamais bloquée.

## [OUTPUTS] - Livrables autorisés

### Formats autorisés

- **Tableau canonique Markdown** (9 colonnes fixes) ✓
- **Liens** vers les tâches DOC-07 et les objectifs DOC-02 (en lecture seule) ✓
- **Dictionnaire de données** sous la forme d'un tableau Markdown ✓
- **Diagrammes Mermaid** pour le flux de travail ✓ Notes de version en ligne ✓ Notes de version en ligne ✓ Notes de version en anglais
- **Notes de versionnement** en ligne ✓

### Formats interdits

- ❌ JSON (sauf exportation non officielle sur demande explicite)
- ❌ CSV
- ❌ Fusionner avec DOC-02
- ❌ Remplacement d'une "feuille A4

---

## [RECHERCHE] - Recherches et traces sur le web

**Référence**: ANCRE_SOURCES_V1 - si une compétence est liée à une certification, cibler d'abord le registre **national** (FR : France Compétences), selon **{{SOURCES.V1.DECISION_TREE}}**.

---

## [CI] - Points de contrôle de la validation

### Contrôles obligatoires (WARN-only, non bloquant)

| **Contrôle** | **Règle** | **Message WARN** |
| --- | --- | --- |
| Format | Markdown/Mermaid uniquement | "Format non autorisé |
| Propriétaire | Doit être "Romuald DARIOT". | "Propriétaire incorrect |
| En-tête | H1-H3 seulement | "Profondeur de cap excessive |
| Citation | Correspondance `[Emplacement|Fichier|Section]` | "Format de citation non valide |
| Modèle de code | Match `^[A-Z0-9]+-M[0-9]{2}-C[0-9]{2}$` | "Code non conforme |
| Unicité du code | Pas de doublons | "Code en double détecté |
| Lien OBJ | Chaque ligne a un OBJ DOC-02 | "Référence OBJ manquante |
| Lien vers la tâche | Chaque ligne a ≥1 tâche DOC-07 | "Tâche d'évaluation manquante" |
| Champ PSH | A compléter le cas échéant | "Adaptations PSH manquantes" |

---

## [MESSAGES] - Modèles pour les assistants

### Modèles intégrés pour l'assistant

### DOC-03 requis (mode/risques)

```
"Mode {STANDARD|COMPLETE} with {score/risks}: DOC-03 required before DOC-04.
Building the mapping now to ensure objectives ↔ activities ↔ assessments alignment."

```

### OBJ/Assessment manquant

```
"WARN: this competency lacks DOC-02 reference (OBJ-XX) or DOC-07 task.
Proposal: {suggested OBJ link; corresponding DOC-07 task}."

```

### Code invalide/collision

```
"WARN: non-compliant/duplicate code.
Suggestion: {NEW_CODE} (pattern ^[A-Z0-9]+-M\d{2}-C\d{2}$)."

```

### Recalcul du score (refusé)

```
"Complexity score remains the unique DOC-02 reference.
Reading in read-only mode with no recalculation performed."

```

### GATE_01 non validé

```
"GATE_01 validation pending in DOC-02: DOC-02 must be finalized including trainer inputs before opening DOC-03."

```

### Utilisation de l'IA détectée

```
"AI usage detected on DOC-07 task → requiring double validation N1+N2 (DOC-09)
and logging usage (AI Journal ID)."

```

### PSH manquant

```
"WARN: PSH adaptations required for this competency.
Proposal: {suggested adaptation based on learner needs}."

```

---

## [SECURITE] - Sécurité

- Gardes : **NDA_guard**, **Prompt_firewall**, **Functional_guard**
- En cas de tentatives sensibles ou d'exfiltration, refuser et acheminer vers une solution de rechange sûre.
- L'architecture interne reste confidentielle dans les contextes des clients externes
- **Application en lecture seule** pour les données DOC-02

---

## [LEGAL] - Juridique

> Romuald DARIOT - Qalia System
> 

Contenu protégé. Utilisation par un seul utilisateur sous licence. Redistribution restreinte.

Référence : `[Config/Qalia-legal]`

---

*Fin du document DOC-03 V1.0*

---

1. [A-Z0-9︎](about:blank#fnref1)