# SKILL : Guidage PSH (Personnes en Situation de Handicap)

## Métadonnées

```yaml
version: 1.0
date_creation: Janvier 2026
indicateurs_qualiopi: [1, 4, 6, 9, 10, 17, 19, 20, 26]
indicateur_principal: 26
niveau_douleur: 3 (Angoisse → Sérénité)
douleur_cible: "Je suis totalement perdu sur la gestion des PSH"
```

---

## Objectif du Skill

Guider les utilisateurs QALIA dans la prise en charge des Personnes en Situation de Handicap selon les exigences Qualiopi, en fournissant :
1. Les adaptations pédagogiques conformes
2. Les éléments de preuve requis
3. Les formulations réglementaires exactes

---

## Cadre Réglementaire

### Indicateur 26 — Exigences

> **Niveau attendu** : "Le prestataire mobilise les expertises, outils et réseaux nécessaires pour accueillir, accompagner/former ou orienter les publics en situation de handicap."

### Éléments de Preuve Attendus

| Type | Exemples |
|------|----------|
| **Référent handicap** | Nomination, formation, coordonnées affichées |
| **Réseau mobilisé** | Agefiph, FIPHFP, Cap Emploi, MDPH |
| **Adaptations documentées** | Supports adaptés, aménagements temps, matériel |
| **Accessibilité** | Locaux, outils numériques, modalités pédagogiques |
| **Procédure accueil** | Questionnaire amont, entretien, fiche suivi |

---

## Types de Handicap et Adaptations

### 1. Handicap Visuel

```yaml
adaptations_pedagogiques:
  - Supports en gros caractères (min 14pt, idéal 18pt)
  - Contraste élevé (noir/blanc ou jaune/bleu)
  - Documents compatibles lecteurs d'écran (PDF taggé)
  - Description audio des visuels
  - Eviter tableaux complexes

adaptations_organisationnelles:
  - Place proche du formateur
  - Éclairage adapté (ni éblouissant, ni insuffisant)
  - Binôme pour guidance si nécessaire

outils_recommandes:
  - JAWS, NVDA (lecteurs écran)
  - ZoomText (agrandissement)
  - Synthèse vocale
```

### 2. Handicap Auditif

```yaml
adaptations_pedagogiques:
  - Supports écrits complets (pas juste slides)
  - Sous-titrage des vidéos
  - Interprète LSF si besoin
  - Transcription temps réel (Tadeo, AVA)
  - Visuels explicatifs > oral

adaptations_organisationnelles:
  - Face au formateur (lecture labiale)
  - Environnement calme (éviter bruit fond)
  - Boucle magnétique si équipé

outils_recommandes:
  - Ava (transcription smartphone)
  - Otter.ai (prise de notes automatique)
  - Roger Pen (micro directionnel)
```

### 3. Handicap Moteur

```yaml
adaptations_pedagogiques:
  - Supports numériques (éviter écriture manuelle)
  - Exercices adaptés (pas de manipulation fine si impossible)
  - Temps supplémentaire si fatigue

adaptations_organisationnelles:
  - Accessibilité locaux (rampe, ascenseur, toilettes)
  - Mobilier adapté (hauteur, espace)
  - Pauses régulières

outils_recommandes:
  - Claviers adaptés (gros touches, une main)
  - Souris ergonomiques, trackball
  - Logiciels commande vocale
```

### 4. Handicap Cognitif / Troubles DYS

```yaml
adaptations_pedagogiques:
  - Police adaptée (OpenDyslexic, Arial, Verdana)
  - Interligne 1.5 minimum
  - Phrases courtes
  - Éviter textes denses
  - Schémas et visuels
  - Répétition et reformulation

adaptations_organisationnelles:
  - Temps supplémentaire (tiers-temps)
  - Environnement calme
  - Instructions écrites ET orales
  - Découpage tâches complexes

outils_recommandes:
  - Logiciels text-to-speech
  - Correcteurs orthographiques avancés
  - Mind mapping (Mindmeister, XMind)
```

### 5. Handicap Psychique

```yaml
adaptations_pedagogiques:
  - Cadre bienveillant et prévisible
  - Programme clair communiqué à l'avance
  - Éviter les changements de dernière minute
  - Feedback positif régulier

adaptations_organisationnelles:
  - Possibilité de pauses si besoin
  - Contact référent disponible
  - Respect confidentialité

attention:
  - Ne jamais forcer la divulgation
  - Rester dans son rôle de formateur
  - Orienter vers professionnels de santé si nécessaire
```

---

## Procédure Accueil PSH

### Phase 1 : Identification Amont

```markdown
## Questionnaire Type (extrait)

**Question** : Avez-vous des besoins spécifiques liés à une situation de handicap ?
- [ ] Non
- [ ] Oui → Si oui, souhaitez-vous en échanger avec notre référent handicap ?

**Question** : Avez-vous besoin d'aménagements particuliers ?
- [ ] Supports adaptés (gros caractères, audio...)
- [ ] Aménagement du temps (pauses, durée...)
- [ ] Aménagement des locaux (accessibilité...)
- [ ] Autre : _____________

**Important** : Ces informations sont confidentielles et servent uniquement à adapter la formation à vos besoins.
```

### Phase 2 : Entretien Référent

```yaml
objectif: Définir les adaptations nécessaires
duree: 15-30 minutes
modalite: Téléphone ou visio au choix
points_abordes:
  - Nature des besoins (sans exiger détails médicaux)
  - Adaptations déjà expérimentées
  - Solutions envisageables
  - Interlocuteurs à mobiliser (Agefiph, etc.)

formalisation:
  - Fiche de suivi PSH (anonymisée dans dossier)
  - Plan d'adaptation validé
  - Contact régulier pendant formation
```

### Phase 3 : Mise en Œuvre

```yaml
avant_formation:
  - Vérifier accessibilité locaux
  - Préparer supports adaptés
  - Informer formateur (avec accord apprenant)
  - Préparer matériel spécifique

pendant_formation:
  - Vérifier confort apprenant
  - Ajuster si nécessaire
  - Point intermédiaire référent

apres_formation:
  - Évaluation adaptations
  - Retour d'expérience
  - Amélioration continue
```

---

## Réseau à Mobiliser

### Organismes Nationaux

| Organisme | Mission | Contact |
|-----------|---------|---------|
| **Agefiph** | Emploi handicapé privé | agefiph.fr |
| **FIPHFP** | Emploi handicapé public | fiphfp.fr |
| **Cap Emploi** | Accompagnement emploi | capemploi.com |
| **MDPH** | Droits et orientation | Par département |

### Ressources Spécialisées

| Ressource | Spécialité |
|-----------|------------|
| **CFPSAA** | Déficience visuelle |
| **FNSF** | Surdité |
| **APF France Handicap** | Moteur |
| **UNAPEI** | Intellectuel |
| **UNAFAM** | Psychique |

### Outils Agefiph

- **RHF** (Ressource Handicap Formation) : conseil gratuit
- **Aide à l'adaptation** : financement adaptations
- **Formation référent** : montée compétences

---

## Formulations Conformes

### À Utiliser

✅ "Personne en situation de handicap" (PSH)
✅ "Besoins spécifiques"
✅ "Adaptations pédagogiques"
✅ "Accessibilité"
✅ "Accompagnement individualisé"

### À Éviter

❌ "Handicapé" (seul, comme substantif)
❌ "Invalide"
❌ "Personne normale" (vs handicapée)
❌ "Souffre de..."
❌ "Malgré son handicap..."

---

## Intégration QALIA

### Génération Automatique

QALIA peut générer :
1. **Questionnaire amont PSH** personnalisé
2. **Fiche adaptations** par type de handicap
3. **Plan d'accompagnement** individualisé
4. **Check-list accessibilité** locaux et outils
5. **Traçabilité** des adaptations mises en œuvre

### Indicateurs Liés

| Indicateur | Lien avec PSH |
|------------|---------------|
| Ind. 1 | Information conditions accueil PSH |
| Ind. 4 | Analyse besoins spécifiques |
| Ind. 6 | Adaptation modalités pédagogiques |
| Ind. 9 | Conditions matérielles adaptées |
| Ind. 10 | Adaptation parcours |
| Ind. 17 | Intervenants formés PSH |
| Ind. 19 | Supports adaptés |
| Ind. 20 | Ressources référent handicap |
| Ind. 26 | Indicateur principal PSH |

---

## Éléments de Preuve QALIA

### Documents Générables

```yaml
doc_psh_01_questionnaire:
  nom: "Questionnaire identification besoins PSH"
  format: PDF ou formulaire en ligne
  contenu: Questions respectueuses, RGPD compliant

doc_psh_02_fiche_suivi:
  nom: "Fiche de suivi accompagnement PSH"
  format: PDF
  contenu: Adaptations prévues, mises en œuvre, évaluation

doc_psh_03_plan_adaptation:
  nom: "Plan d'adaptation individualisé"
  format: PDF
  contenu: Besoins identifiés, solutions, calendrier, responsable

doc_psh_04_checklist:
  nom: "Check-list accessibilité formation"
  format: PDF
  contenu: Locaux, supports, outils, vérifications
```

---

## Usage Communication LinkedIn

### Angle Éditorial

La douleur PSH (Niveau 3) n'a pas d'extrait émotionnel dans les démos actuelles.

**Créer du contenu** :
- Posts éducatifs sur l'accessibilité
- Témoignages (anonymisés) d'accompagnement réussi
- Valorisation du référent handicap

### Phrases Clés

- "Gérer les PSH vous inquiète ? QALIA vous guide pas à pas."
- "L'inclusion n'est pas une option Qualiopi. C'est un indicateur."
- "Référent handicap : QALIA vous donne les outils."

---

*SKILL-GUIDAGE-PSH v1.0*
*Indicateur principal : 26*
*Niveau douleur : 3*
