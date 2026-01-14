# SKILL — Calculateur ROI QALIA

```yaml
name: roi-calculator
version: 1.0.0
author: Romuald DARIOT
purpose: Calculer et présenter le ROI QALIA aux prospects
updated: Janvier 2026
```

---

## Formule de Base

```
ROI = (Valeur gagnée - Coût QALIA) / Coût QALIA × 100
```

---

## Variables d'Entrée

| Variable | Description | Valeur par défaut |
|----------|-------------|-------------------|
| `heures_ingenierie` | Heures/mois actuelles sur ingénierie | 40h |
| `tjm` | Taux journalier moyen | 100€/h |
| `gain_temps_pct` | % de temps récupéré avec QALIA | 75% |
| `prix_qalia` | Abonnement mensuel | 297€ |

---

## Calculs

### Calcul Perte Actuelle

```
perte_mensuelle = heures_ingenierie × tjm
perte_annuelle = perte_mensuelle × 12

Exemple (défaut) :
40h × 100€ = 4,000€/mois
4,000€ × 12 = 48,000€/an
```

### Calcul Gain avec QALIA

```
heures_recuperees = heures_ingenierie × gain_temps_pct
valeur_recuperee = heures_recuperees × tjm

Exemple (défaut) :
40h × 75% = 30h récupérées
30h × 100€ = 3,000€/mois de valeur
```

### Calcul ROI

```
profit_net_mensuel = valeur_recuperee - prix_qalia
profit_net_annuel = profit_net_mensuel × 12
roi_annuel = (profit_net_annuel / (prix_qalia × 12)) × 100

Exemple (défaut) :
3,000€ - 297€ = 2,703€/mois de profit net
2,703€ × 12 = 32,436€/an
ROI = 32,436 / 3,564 × 100 = 910%
```

### Calcul Payback

```
payback_heures = prix_qalia / tjm
payback_jours = payback_heures / 8

Exemple (défaut) :
297€ / 100€ = 2.97 heures
2.97 / 8 = 0.37 jours ≈ 3 heures de travail
```

---

## Grille de Simulation par Profil

### Profil Débutant (5 dossiers/mois)

| Paramètre | Valeur |
|-----------|--------|
| Heures ingénierie | 30h/mois |
| TJM | 80€/h |
| Perte actuelle | 2,400€/mois |
| Gain QALIA (75%) | 1,800€/mois |
| Profit net | 1,503€/mois |
| ROI annuel | **507%** |
| Payback | **3.7 heures** |

### Profil Intermédiaire (8 dossiers/mois)

| Paramètre | Valeur |
|-----------|--------|
| Heures ingénierie | 50h/mois |
| TJM | 100€/h |
| Perte actuelle | 5,000€/mois |
| Gain QALIA (75%) | 3,750€/mois |
| Profit net | 3,453€/mois |
| ROI annuel | **1,163%** |
| Payback | **3 heures** |

### Profil Expert (10+ dossiers/mois)

| Paramètre | Valeur |
|-----------|--------|
| Heures ingénierie | 60h/mois |
| TJM | 130€/h |
| Perte actuelle | 7,800€/mois |
| Gain QALIA (75%) | 5,850€/mois |
| Profit net | 5,553€/mois |
| ROI annuel | **1,869%** |
| Payback | **2.3 heures** |

---

## Script de Présentation ROI

### Étape 1 : Collecter les données

```
"Combien d'heures par mois consacrez-vous à l'ingénierie Qualiopi ?"
"Quel est votre TJM actuel ?"
```

### Étape 2 : Calculer en direct

```
"OK, [X]h à [Y]€/h = [Z]€/mois de temps non facturé.
Sur un an, c'est [Z×12]€ de perte d'opportunité."
```

### Étape 3 : Montrer le gain

```
"Avec QALIA, vous récupérez environ 75% de ce temps.
Soit [X×0.75]h par mois.
Valeur : [X×0.75×Y]€/mois."
```

### Étape 4 : ROI

```
"QALIA coûte 297€/mois.
Votre profit net : [gain - 297]€/mois.
ROI : [calcul]%

L'investissement se rembourse en [payback] heures de travail."
```

---

## Objections ROI

### "Les chiffres sont théoriques"

```
"Ces chiffres sont basés sur VOS données.
Le gain réel dépend de votre usage.
Nos utilisateurs confirment 20-30h récupérées."
```

### "Je ne facture pas ces heures"

```
"Chaque heure non facturée est une heure que vous pourriez :
- Facturer à un client
- Consacrer à votre développement
- Passer en famille

Le coût d'opportunité est réel."
```

---

## Formules Rapides

| Situation | Formule |
|-----------|---------|
| ROI minimum | `(tjm × 10h - 297) / 297 × 100` |
| Payback heures | `297 / tjm` |
| Seuil rentabilité | `297 / tjm` heures récupérées |

---

*SKILL Calculateur ROI v1.0*
*Janvier 2026*
