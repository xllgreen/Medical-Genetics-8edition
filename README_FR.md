# Génétique Médicale Medical-Genetics-8edition

<div align="center">

> *« Guide de l'étudiant en médecine du XXIe siècle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Manuel de compétences cliniques en génétique basé sur *Génétique Médicale* 8e édition — 131 compétences cliniques essentielles en génétique médicale
<br>
<br>
<img src="/assets/Medical-Genetics-8edition.png" width="260px">
<br>

Pourquoi s'acharner à lire tout un livre ?<br>
Posez simplement une question et laissez le manuel trouver la solution pour vous.

<br>

**Langues / Other Languages:**

[中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Présentation du projet

Ce projet intègre systématiquement les domaines fondamentaux de la génétique médicale, de la génomique, des maladies métaboliques, du diagnostic prénatal, de la thérapie génique et de la régulation épigénétique, couvrant **131 compétences cliniques essentielles**.

**Public cible** : Médecins généticiens cliniciens, étudiants en médecine, conseillers en génétique, chercheurs en médecine de précision, équipes soignantes en diagnostic prénatal

**Manuel de référence** : *Génétique Médicale* 8e édition

**⚠️ Risque ⚠️** : Cet ensemble de compétences peut produire des recommandations à fort impact dans les domaines clinique, reproductif, médico-légal ou de la thérapie génique. S'il est utilisé uniquement comme avis professionnel, il peut comporter des risques.
**Mesure d'atténuation** : Utilisez toute production uniquement comme matériel pédagogique ou pour examen par un clinicien. Avant de prendre des décisions concernant un diagnostic, un traitement, une grossesse, une analyse médico-légale, un test de paternité, un test génétique ou une thérapie génique, assurez-vous qu'une supervision médicale, génétique ou juridique qualifiée est en place.
**⚠️ Risque ⚠️** : L'analyse de cas génétiques peut impliquer des informations sensibles sur la santé personnelle ou familiale.
**Mesure d'atténuation** : Avant de partager ou de traiter des informations identifiables d'ordre génétique, reproductif ou antécédent familial, des contrôles appropriés de consentement, de confidentialité et d'accord local doivent être appliqués.

## Structure du projet

```
Medical-Genetics-8edition/
├── SKILL.md              # Configuration centrale — Registre des 131 compétences
├── README.md             # Ce document — Description du projet et guide d'utilisation
├── index.md              # Index complet des compétences
├── <skill-name>/         # Définition détaillée de chaque compétence
│   └── SKILL.md          #   Détails de la compétence (quand l'utiliser, procédure, précautions)
└── assets/               # Ressources images
```

## Catégories de compétences

| Catégorie | Nb de compétences | Description |
|-----------|-------------------|-------------|
| 🧬 Classification et mécanismes des maladies génétiques | 14 | Classification en cinq classes, déficits enzymatiques, collagénopathies, drépanocytose, etc. |
| 🔬 Variabilité structurelle chromosomique et génomique | 16 | Description caryotypique, G-banding, délétions/translocations/inversions, polymorphisme, règle GT-AG, etc. |
| 📊 Modes de transmission et analyse de pedigree | 10 | Analyse AD/AR/XR, hypothèse de Lyon, modèle de Knudson, gène SRY, etc. |
| 🤰 Dépistage prénatal et techniques diagnostiques | 6 | NIPT, dépistage échographique, DPI, choix de voie invasive/non invasive, etc. |
| ⚕️ Anomalies chromosomiques et risque reproductif | 12 | Translocation réciproque, translocation robertsonienne, inversion péricentrique/paracentrique, mosaïque, etc. |
| 🔋 Génétique mitochondriale et maladies | 11 | Transcription/traduction de l'ADNmt, hérédité maternelle, effet de seuil, classification biochimique/clinique/génétique |
| 🧮 Maladies complexes et risque polygénique | 10 | Équilibre de Hardy-Weinberg, mise à jour bayésienne, risque de récurrence des maladies polygéniques, etc. |
| 💉 Thérapie génique et intervention moléculaire | 8 | Réparation/renforcement génique, sélection de vecteurs viraux, évaluation de la sécurité CRISPR, inactivation génique |
| 🧫 Génétique tumorale et régulation épigénétique | 9 | Gènes suppresseurs de tumeurs, oncogènes, théorie de Knudson, modification des histones, méthylation de l'ADN |
| 📡 ARN non codant et biomarqueurs | 3 | miRNA, lncRNA, biomarqueurs cardiovasculaires circRNA |
| 🏥 Diagnostic et traitement des maladies génétiques spécifiques | 11 | Thalassémie, PCU, maladie de Pompe, Tay-Sachs, albinisme, hémophilie A, etc. |
| ⚖️ Médecine systémique et applications éthiques | 8 | Médecine systémique, projet 1000 Génomes, mariage consanguin, évaluation éthique, exposition aux tératogènes |
| 🛡️ Réparation de l'ADN et stabilité | 3 | Réparation des dommages à l'ADN, sites fragiles, dégradation non-sens (NMD) |

## Démarrage rapide

### Installation

CLI :
```bash
openclaw skills install medical-genetics-8edition
```

Invite :
```bash
Avant d'installer quoi que ce soit, inspectez les métadonnées et les exigences de configuration de la compétence ClawHub.
Si la compétence vous demande d'installer un package ou un CLI tiers, vérifiez sa source, son mainteneur et son contenu avant d'exécuter la commande d'installation.
N'installez la compétence "Medical Genetics 8edition" (xllgreen/medical-genetics-8edition) depuis ClawHub qu'après avoir effectué ces vérifications.
Page de la compétence : https://clawhub.ai/xllgreen/medical-genetics-8edition
Limitez le travail à cette seule compétence.
Après l'installation, aidez-moi à terminer la configuration à partir des métadonnées vérifiées.
Utilisez uniquement les métadonnées que vous pouvez vérifier depuis ClawHub ; n'inventez pas d'exigences manquantes.
Demandez avant d'apporter des modifications plus larges à l'environnement.
```

### Utilisation

Chaque compétence se compose de trois parties :
1. **Quand l'utiliser** — Conditions de déclenchement de la compétence
2. **Procédure** — Flux de travail opérationnel standardisé
3. **Précautions** — Contre-indications et avertissements

### Stratégies de questionnement

#### 1. Compréhension conceptuelle
Question :
```bash
Qu'est-ce que l'équilibre de Hardy-Weinberg ?
```
Réponse :
```bash
## Équilibre de Hardy-Weinberg

L'équilibre de Hardy-Weinberg est un principe fondamental de la génétique des populations. Il décrit que dans des conditions idéales (croisement aléatoire, absence de mutation, absence de sélection, absence de migration, population de taille infinie), les fréquences alléliques et génotypiques restent constantes de génération en génération.

### Formule de base
Pour un locus autosomique biallélique (A et a) :
- p = fréquence de A, q = fréquence de a
- p + q = 1
- Fréquences génotypiques : p²(AA) + 2pq(Aa) + q²(aa) = 1

### Applications cliniques
- **Estimation de la fréquence des porteurs** : Pour les maladies AR où l'incidence q² est connue, la fréquence des porteurs 2pq ≈ 2q
- **Contrôle qualité** : Vérifier si les données de génotypage sont conformes à l'HWE
- **Détection de stratification populationnelle** : Un écart à l'HWE peut indiquer une stratification de la population ou une pression sélective
```

#### 2. Analyse de cas clinique
Question :
```bash
Un couple phénotypiquement normal a déjà eu un enfant atteint d'une maladie autosomique récessive. Quel est le risque de récurrence pour leur prochain enfant ? Si ils ont déjà eu deux enfants non atteints, comment le risque évolue-t-il ?
```
Réponse :
```bash
## Analyse de conseil génétique

### Faits de base
- Les deux parents phénotypiquement normaux → Les deux sont **porteurs** (Aa × Aa)
- Déjà un enfant atteint → Mode de transmission confirmé

### Évaluation du risque de récurrence

| Scénario | Risque de récurrence | Explication |
|----------|---------------------|-------------|
| Risque de base par grossesse | 25 % (1/4) | Ratio mendélien |
| Après un enfant atteint | 25 % (1/4) | Événement indépendant ; risque par grossesse inchangé |
| Après deux enfants non atteints | 25 % (1/4) | Événement indépendant ; n'altère pas le risque ultérieur |
| Risque individuel après mise à jour bayésienne | Réduit | Cela révise la *probabilité que le couple soit porteur* |

### Points clés du conseil génétique
1. **Chaque grossesse est indépendante** : Les résultats antérieurs n'affectent pas le risque ultérieur
2. **Confirmation du statut de porteur** : Un test génétique pour les deux parents est recommandé
3. **Diagnostic prénatal** : Un diagnostic génétique prénatal est disponible pour les grossesses futures
4. **Diagnostic génétique préimplantatoire (DPI)** : Une option disponible

> ⚠️ Distinguez bien la « probabilité révisée d'être porteur après des enfants non atteints » (bayésien) du « risque de récurrence par grossesse » (événement indépendant) — ce sont des concepts différents.
```

#### 3. Questions d'examen
Question :
```bash
Quel est le caryotype le plus fréquent dans le syndrome de Down ?
A. 47,XX,+21
B. 46,XX,der(14;21)(q10;q10),+21
C. 47,XX,+21/46,XX
D. 46,XX,inv(21)
```
Réponse :
```bash
**Réponse : A. 47,XX,+21**

**Justification :**
- **Trisomie libre (type standard)** : 47,XX,+21 ou 47,XY,+21 — représente **92-95 %** des cas de syndrome de Down
- **Type translocation** : ex. 46,XX,der(14;21)(q10;q10),+21 — représente **2-4 %**
- **Type mosaïque** : ex. 47,XX,+21/46,XX — représente **2-3 %**

**Points cliniques :**
| Type de caryotype | Proportion | Risque de récurrence |
|------------------|-----------|---------------------|
| Trisomie libre | 92-95 % | Corrélé à l'âge maternel |
| Translocation | 2-4 % | Corrélé au parent porteur (si la mère est porteuse d'une translocation équilibrée, risque ~10-15 %) |
| Mosaïque | 2-3 % | Dépend de la proportion de cellules anormales ; risque de récurrence généralement faible |

> Remarque : La trisomie libre est le caryotype le plus fréquent dans le syndrome de Down et est positivement corrélée à l'âge maternel.
```

## À propos de l'auteur

**Xiaolü Lü (xllgreen)** (https://xllgreen.github.io) — Étudiant en médecine à l'Université de Jiujiang, Passionné de technologie

## Support technique
<br>
PDF2App : https://pdf2app.cn
<br>
Microsoft Visual Studio Code : https://code.visualstudio.com/
<br>
Claude Code for VS Code : https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API : https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. Tous droits réservés
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API : https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. Tous droits réservés
<br>

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FMedical-Genetics-8edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
 </picture>
</a>
