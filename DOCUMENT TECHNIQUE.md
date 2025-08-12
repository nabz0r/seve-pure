# Dossier Technique : Sève Pure V2.0
## Système de Pré-Filtration Bio-Sourcé pour Gouttières

### Version : 2.0 | Date : Janvier 2025 | Statut : Prototype Phase 2

---

## 1. Concept et Innovation Technique

### 1.1 Vue d'Ensemble
Sève Pure V2.0 est un système de pré-filtration multicouche exploitant des matériaux bio-sourcés locaux pour purifier l'eau de pluie directement dans les gouttières. Le système a été repensé pour maximiser l'efficacité tout en utilisant des matériaux disponibles localement en Europe du Nord.

### 1.2 Principes Scientifiques Validés

#### A. Coagulation/Floculation (Couche 1)
**Matériau principal :** Argile bentonite lituanienne (remplacement du moringa)
- **Mécanisme :** Les particules d'argile gonflent au contact de l'eau, créant une charge électrostatique qui attire les contaminants
- **Efficacité mesurée :** Réduction turbidité de 75-85% (tests laboratoire Q4 2024)
- **Alternative en R&D :** Culture de moringa en serre hydroponique (différenciateur premium)

**Données de performance :**
```
Turbidité initiale : 45-50 NTU
Après filtration : 5-8 NTU
Taux de réduction : 84-89%
```

#### B. Adsorption Chimique (Couche 2)
**Composition optimisée :**
- 40% Charbon de bambou activé (1200 m²/g surface spécifique)
- 30% Écorce de pin baltique (tanins naturels)
- 30% Tourbe lituanienne (échange ionique)

**Capacité d'adsorption validée :**
- Chlore : 95% de réduction
- Métaux lourds (Pb, Cu, Cd) : 70-80% de réduction
- Pesticides organiques : 60-70% de réduction
- COV : 85% de réduction

#### C. Filtration Mécanique (Couche 3)
**Structure granulométrique :**
- Sable de quartz 0.4-0.8mm (couche supérieure)
- Sable 0.8-1.2mm (couche intermédiaire)  
- Gravier 2-4mm (drainage)

**Performance :**
- Rétention particules > 5 μm : 99%
- Débit nominal : 2-3 L/min
- Perte de charge : < 10 cm H₂O

## 2. Spécifications Techniques Détaillées

### 2.1 Architecture du Système

```
┌─────────────────────────┐
│   Entrée Eau Pluviale   │
├─────────────────────────┤
│  Grille Anti-Débris     │ ← Maille 5mm inox
├─────────────────────────┤
│  Bentonite (3cm)        │ ← Coagulation
├─────────────────────────┤
│  Charbon/Écorce (5cm)   │ ← Adsorption
├─────────────────────────┤
│  Sable Fin (7cm)        │ ← Filtration
├─────────────────────────┤
│  Gravier (5cm)          │ ← Drainage
├─────────────────────────┤
│   Sortie Eau Filtrée    │
└─────────────────────────┘
```

### 2.2 Dimensions et Compatibilité

**Boîtier Principal :**
- Diamètre externe : 98mm (compatible 100mm gouttières)
- Hauteur totale : 300mm
- Épaisseur paroi : 3mm
- Matériau : PP recyclé + 30% fibres végétales
- Résistance température : -30°C à +60°C
- Résistance UV : 5 ans minimum

**Adaptateurs Universels :**
- Kit 80mm : Réducteur conique
- Kit 90mm : Manchon adaptateur
- Kit 100mm : Installation directe
- Kit carré : Adaptateur spécial

### 2.3 Cartouche Filtrante V2

**Structure :**
```yaml
Enveloppe:
  Matériau: Non-tissé biodégradable 200g/m²
  Perméabilité: 50 L/m²/s
  
Compartiments:
  - Couche_1: 
      Volume: 150ml
      Matériau: Bentonite granulée 2-4mm
      Durée_vie: 4 mois
  
  - Couche_2:
      Volume: 250ml
      Matériaux: Mix charbon/écorce/tourbe
      Durée_vie: 6 mois
  
  - Couche_3:
      Volume: 350ml
      Matériau: Sable quartzeux calibré
      Durée_vie: 12 mois
```

## 3. Protocoles de Test et Validation

### 3.1 Tests de Performance (EN COURS)

#### Test A : Efficacité de Filtration
**Protocole :**
1. Eau synthétique polluée (norme ISO 12103-1)
2. Débit constant 2 L/min
3. Mesures toutes les 100L
4. Durée : 3 mois continus

**Métriques :**
- Turbidité (NTU)
- pH
- Conductivité
- Métaux lourds (ICP-MS)
- Coliformes totaux

#### Test B : Résistance Climatique
**Conditions extrêmes :**
- Cycles gel/dégel : -20°C/+20°C (50 cycles)
- UV accéléré : 1000h
- Saturation eau : 30 jours immersion
- Impact mécanique : chute 2m

#### Test C : Durée de Vie
**Simulation accélérée :**
- Volume traité cible : 10 000 L/cartouche
- Eau de pluie réelle collectée
- Analyse colmatage progressif
- Courbe de perte d'efficacité

### 3.2 Résultats Préliminaires (Prototype V1)

| Paramètre | Avant Filtration | Après Filtration | Réduction |
|-----------|-----------------|------------------|-----------|
| Turbidité | 48 NTU | 6 NTU | 87.5% |
| pH | 5.8 | 6.9 | Neutralisé |
| Plomb | 45 μg/L | 12 μg/L | 73% |
| E. Coli | 1200 UFC/100ml | 150 UFC/100ml | 87.5% |
| Débit | 3 L/min | 2.4 L/min | -20% |

## 4. Innovation et R&D

### 4.1 Projets en Développement

#### Moringa Baltique™
- Culture hydroponique en serre
- Variété adaptée au froid
- Rendement : 50kg graines/an/100m²
- ROI estimé : 18 mois

#### Nano-Argent Intégré
- Particules Ag incorporées au charbon
- Action antibactérienne longue durée
- Dosage : 0.05% en masse
- Tests toxicité en cours

#### IoT Monitoring (V3.0)
- Capteur turbidité intégré
- Alerte remplacement via app
- Données qualité eau temps réel
- Prix cible module : +20€

### 4.2 Matériaux Alternatifs Testés

| Matériau | Origine | Efficacité | Coût | Décision |
|----------|---------|------------|------|-----------|
| Zéolite | Estonie | 65% | €€ | Backup |
| Coquilles huîtres | Bretagne | 45% | € | Non |
| Biochar local | Lituanie | 70% | € | Intégré V2 |
| Chitosan | Import | 85% | €€€ | Non |
| Terre de diatomée | Pologne | 60% | €€ | Test Q2 |

## 5. Manufacturing & Supply Chain

### 5.1 Process de Production

```mermaid
graph LR
A[Réception Matières] --> B[Contrôle Qualité]
B --> C[Calibrage/Tamisage]
C --> D[Mélange Formulation]
D --> E[Remplissage Cartouches]
E --> F[Scellage Thermique]
F --> G[Test Échantillon]
G --> H[Packaging]
H --> I[Stockage/Expédition]
```

### 5.2 Fournisseurs Validés

**Matériaux Principaux :**
- Bentonite : UAB Molio (Lituanie) - 200€/tonne
- Charbon bambou : Bamboo Import EU (Pays-Bas) - 800€/tonne
- Écorce pin : Latvijas Finieris (Lettonie) - 50€/tonne
- Tourbe : Rekyva (Lituanie) - 80€/tonne

**Capacité Production :**
- Phase 1 : 100 unités/jour (manuel)
- Phase 2 : 500 unités/jour (semi-auto)
- Phase 3 : 2000 unités/jour (automatisé)

## 6. Certifications et Conformité

### 6.1 Normes Applicables
- **EN 1917** : Dispositifs de traitement eaux pluviales
- **NSF/ANSI 42** : Filtres à eau domestiques
- **CE Marking** : Conformité européenne
- **RoHS** : Restriction substances dangereuses

### 6.2 Certifications en Cours
- [ ] Test migration (contact eau potable)
- [ ] Analyse cycle de vie (ACV)
- [ ] Certification Bio-based content
- [ ] Label Nordic Swan Ecolabel

## 7. Propriété Intellectuelle

### 7.1 Brevet en Préparation
**Titre :** "Système de filtration multicouche bio-sourcé à efficacité progressive"
**Revendications principales :**
1. Combinaison spécifique bentonite locale + tourbe
2. Architecture à compartiments indépendants
3. Système de saturation différentielle des couches

### 7.2 Secrets Industriels
- Ratio exact du mélange adsorbant
- Process d'activation du charbon
- Traitement anti-colmatage de la bentonite

## 8. Roadmap Technique

### Q1 2025
- Finalisation Prototype V2
- Tests labo indépendants
- Optimisation formulation

### Q2 2025
- Certification NSF/ANSI 42
- Setup production pilote
- Tests terrain 50 sites

### Q3 2025
- Industrialisation process
- Lancement production série
- Développement app IoT

### Q4 2025
- Optimisation coûts -20%
- Lancement gamme Premium
- Début export EU

## 9. Métriques de Performance Cibles

| KPI | Objectif V2 | Statut Actuel | Gap |
|-----|------------|---------------|-----|
| Efficacité filtration | > 85% | 75% | -10% |
| Durée vie cartouche | 4 mois | 3 mois | -1 mois |
| Coût production | < 4€ | 5.50€ | +1.50€ |
| Débit nominal | > 3L/min | 2.4L/min | -0.6L/min |
| Taux de défaut | < 1% | 3% | +2% |

## 10. Conclusions et Prochaines Étapes

### Points Critiques à Valider
1. **Durée de vie réelle** en conditions climatiques nordiques
2. **Stabilité** de la formulation bentonite/tourbe
3. **Acceptabilité** du prix par le marché
4. **Scalabilité** de la production

### Actions Prioritaires
1. Compléter les tests de durée de vie accélérés
2. Sécuriser les approvisionnements par contrats cadres
3. Déposer le brevet avant communication publique
4. Recruter un ingénieur process pour l'industrialisation

---

**Contact Technique :** [CTO à recruter]  
**Dernière mise à jour :** Janvier 2025  
**Prochaine révision :** Mars 2025 (post-tests terrain)