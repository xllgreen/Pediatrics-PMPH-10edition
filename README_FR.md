# Pédiatrie Pediatrics-PMPH-10edition

<div align="center">

> *« Guide de l'étudiant en médecine du XXIe siècle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Un manuel de compétences cliniques basé sur la 10e édition de *Pédiatrie* des Éditions Médicales du Peuple (PMPH) — 184 compétences cliniques pédiatriques essentielles
<br>
<br>
<img src="/assets/Pediatrics.png" width="260px">
<br>

Pourquoi peiner à lire un manuel entier ?<br>
Posez une question et obtenez des solutions directement tirées du manuel.

<br>

**Autres langues / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## À propos du projet

Ce projet intègre systématiquement les domaines fondamentaux de la pédiatrie, de la néonatologie, de la croissance et du développement de l'enfant, de la prévention et du contrôle des maladies infectieuses, du diagnostic et du traitement des maladies génétiques métaboliques, ainsi que des soins d'urgence et de réanimation. Il couvre **184 compétences cliniques clés** réparties en **15 grandes catégories**.

**Public cible :** Pédiatres, étudiants en médecine, équipes de soins néonatals, professionnels de santé publique, internes en formation spécialisée

**Manuel de référence :** *Pédiatrie*, 10e édition, People's Medical Publishing House (PMPH)

**⚠️Risque⚠️ :** Les traitements cliniques à haut risque, les procédures et les conseils posologiques peuvent ne pas convenir à une installation ou une utilisation générale sans supervision.

**Atténuation :** Destiné uniquement aux pédiatres qualifiés, néonatologistes, réanimateurs pédiatriques ou environnements de formation médicale supervisée ; nécessite l'avis d'un clinicien avant d'appliquer les résultats.

**⚠️Risque⚠️ :** Les recommandations peuvent entrer en conflit avec les directives locales actuelles, les protocoles institutionnels ou les contre-indications spécifiques aux patients.

**Atténuation :** Vérifier que tous les plans, procédures, seuils et suivis sont conformes aux normes locales et aux politiques institutionnelles avant utilisation.

**⚠️Risque⚠️ :** Les procédures invasives d'urgence, la réanimation néonatale, les calculs de doses pédiatriques et les sujets sensibles liés au développement et au comportement peuvent compromettre la sécurité ou la vie privée des patients s'ils sont traités avec trop de désinvolture.

**Atténuation :** Ajouter des avertissements explicites pour ces scénarios, orienter les urgences vers les soins d'urgence/USI, et restreindre l'accès aux cliniciens qualifiés ou aux utilisateurs ayant des besoins éducatifs supervisés.

## Structure du projet

```
Pediatrics-PMPH-10edition/
├── SKILL.md                  # Configuration principale — registre de 184 compétences
├── README.md                 # Ce document — description du projet et guide d'utilisation
├── <skill-name>/             # Définitions détaillées de chaque compétence
│   └── SKILL.md              #   Détails de la compétence (quand l'utiliser, étapes, références)
├── scripts/                  # Scripts utilitaires exécutables
│   └── .gitkeep
├── config/                   # Fichiers de configuration
│   └── .gitkeep
└── tests/                    # Validation et tests
    └── .gitkeep
```

## Aperçu des catégories de compétences

| Catégorie | Comp. | Description |
|-----------|-------|-------------|
| 👶 Néonatologie & Médecine périnatale | 18 | Ictère, SDR, hémolyse, hémorragie, ENN, ROP, DBP, etc. |
| 📏 Croissance, Développement & Nutrition | 18 | Évaluation de la croissance physique, diversification, sommeil, micronutriments, etc. |
| 💉 Vaccination & Contrôle des maladies infectieuses | 20 | Vaccination systématique, rougeole, HFM, tuberculose, Kawasaki, etc. |
| 🫁 Maladies respiratoires | 12 | Pneumonie, asthme, mycoplasme, bronchoscopie, gaz du sang, etc. |
| ❤️ Maladies cardiovasculaires | 10 | Classification des cardiopathies congénitales, insuffisance cardiaque, myocardite, critères de Duke, etc. |
| 🫃 Maladies digestives & hépatobiliaires | 12 | Invagination, maladie de Hirschsprung, MII, atrésie biliaire, RGO, etc. |
| 🫘 Maladies urinaires & rénales | 10 | Hématurie, néphrite, syndrome néphrotique, IRA, ATR, etc. |
| ⚖️ Maladies endocriniennes & métaboliques | 13 | Déficit en GH, puberté précoce, hypothyroïdie, diabète, ACD, etc. |
| 🩸 Maladies hématologiques & oncologiques | 9 | PTI, AHAI, hémophilie, thalassémie, LCH, etc. |
| 🧠 Troubles neurologiques, psychiatriques & comportementaux | 12 | Épilepsie, convulsions fébriles, TDAH, SGB, myasthénie, etc. |
| 🚑 Urgences & Soins intensifs | 10 | RCP, traumatisme, noyade, insuffisance respiratoire, déshydratation, etc. |
| 🧬 Maladies génétiques & congénitales | 7 | Prévention tertiaire, classification des maladies génétiques, CHARGE, DMD/BMD, etc. |
| 🔬 Examens de laboratoire & diagnostics | 11 | LCR, PCU, HCS, rachitisme, IRM, échographie, etc. |
| 📚 Manuel & Médecine fondée sur les preuves | 7 | Évaluation de la fiabilité du manuel, principes de révision, recommandations bibliographiques, etc. |
| 🏋️ Gestion globale de la santé | 9 | Exercice, alimentation, système immunitaire, posologie, examen physique, etc. |

## Guide de démarrage rapide

### Installation

CLI :
```bash
openclaw skills install pediatrics-pmph-10edition
```

Invite :
```bash
Avant d'installer quoi que ce soit, inspectez les métadonnées et les exigences de configuration de la compétence ClawHub.
Si la compétence vous demande d'installer un package ou un CLI tiers, vérifiez sa source, son mainteneur et le contenu du package avant d'exécuter la commande d'installation.
N'installez la compétence "Pediatrics-PMPH-10edition" (xllgreen/pediatrics-pmph-10edition) depuis ClawHub qu'après avoir effectué ces vérifications.
Page de la compétence : https://clawhub.ai/xllgreen/pediatrics-pmph-10edition
Limitez votre travail à cette compétence uniquement.
Après l'installation, aidez-moi à terminer la configuration à partir des métadonnées vérifiées.
Utilisez uniquement les métadonnées que vous pouvez vérifier depuis ClawHub ; n'inventez pas d'exigences manquantes.
Demandez avant d'apporter des modifications plus larges à l'environnement.
```

### Utilisation après installation
Donnez les instructions suivantes à l'agent :
```bash
Avant chaque réponse, veuillez consulter la compétence médicale correspondante pour vérification.
```

### Recherche de compétences

```bash
# Recherche par mot-clé
bash scripts/skill-search.sh  ictère néonatal

# Générer un rapport de compétences
bash scripts/skill-report.sh
```

### Mode d'emploi

Chaque compétence se compose de quatre parties :
1. **Quand l'utiliser** — Quand déclencher cette compétence
2. **Étapes d'exécution** — Procédure opératoire standardisée
3. **Précautions** — Contre-indications et avertissements
4. **Références** — Documents complémentaires détaillés

### Stratégies de questionnement

#### 1. **Concept**

Question :
```bash
Concept de l'ictère physiologique néonatal
```

Réponse :
```bash
## Concept de l'ictère physiologique néonatal
**L'ictère physiologique néonatal** est une élévation transitoire de la bilirubine sérique non conjuguée chez le nouveau-né due aux particularités du métabolisme de la bilirubine — un processus bénin qui se résorbe généralement sans intervention spécifique.
### Critères diagnostiques
| Paramètre | Nouveau-né à terme | Prématuré |
|-----------|-------------------|-----------|
| Apparition | 2–3 jours après la naissance | 3–5 jours après la naissance |
| Pic | 4–5 jours après la naissance | 5–7 jours après la naissance |
| Résorption | 5–7 jours après la naissance | 7–9 jours après la naissance |
| Bilirubine sérique maximale | < 221 μmol/L (12,9 mg/dL) | < 256 μmol/L (15 mg/dL) |
| Élévation quotidienne | < 85 μmol/L (5 mg/dL) | < 85 μmol/L (5 mg/dL) |
### Diagnostic différentiel clé
- **Ictère physiologique** : Respecte la fenêtre temporelle et les seuils ci-dessus ; état général bon
- **Ictère pathologique** : Apparition trop précoce (<24h), degré trop élevé, durée prolongée, élévation quotidienne excessive, ou augmentation de la bilirubine directe
- **Ictère au lait maternel** : Apparition à 1 semaine, pic à 2–3 semaines, diminution significative après 3 jours d'arrêt de l'allaitement maternel
### Principes de prise en charge
Aucun traitement spécifique requis ; assurer un apport alimentaire suffisant pour favoriser l'élimination du méconium. Si la BST approche du seuil d'intervention, évaluer la nécessité d'une photothérapie.
```

#### 2. **Analyse de cas clinique**

Question :
```bash
Nouveau-né, âge gestationnel 38 semaines, accouchement par voie basse, poids de naissance 3,2 kg. Développement d'un ictère cutané dans les 24 heures suivant la naissance, s'aggravant rapidement. À 36 heures, la BST est de 15 mg/dL, à prédominance de bilirubine non conjuguée. Groupe sanguin de la mère : O Rh(+) ; groupe sanguin du nourrisson : A Rh(+). Quel est le diagnostic le plus probable ?
```

Réponse :
```bash
## Analyse du cas
**Diagnostic le plus probable : Maladie hémolytique du nouveau-né par incompatibilité ABO**
### Arguments diagnostiques
| Caractéristique clinique | Indice |
|------------------------|--------|
| **Ictère dans les 24h suivant la naissance** | Ictère pathologique — apparition trop précoce |
| **Bilirubine totale 15 mg/dL (257 μmol/L)** | Significativement au-dessus de la fourchette physiologique (pic normal <12,9 mg/dL) |
| **Bilirubine non conjuguée prédominante** | Compatible avec un ictère hémolytique |
| **Mère O + nourrisson A** | Combinaison d'incompatibilité ABO la plus fréquente (IgG anti-A maternelle traverse le placenta) |
| **Test de Coombs positif** | Preuve directe d'une hémolyse immunitaire |
### Prise en charge ultérieure
1. **Commencer la photothérapie immédiatement** — Lumière bleue de haute intensité (425–475 nm)
2. **Surveiller la BST q4–6h** — Évaluer la nécessité d'une exsanguino-transfusion
3. **NFS + réticulocytes** — Évaluer le degré d'anémie
4. **Perfusion d'IgIV** — 0,5–1 g/kg pour bloquer l'hémolyse
5. **Évaluer les critères d'exsanguino-transfusion** — Si BST ≥ seuil d'échange ou échec de la photothérapie
```

#### 3. **Questions d'examen**

Question :
```bash
Nourrisson de 8 mois, fièvre depuis 3 jours ; éruption cutanée apparaissant après la défervescence. Diagnostic le plus probable :
A. Rougeole
B. Rubéole
C. Exanthème subit (Roséole)
D. Scarlatine
E. Varicelle
```

Réponse :
```bash
**Réponse : C. Exanthème subit (Roséole)**
### Diagnostic différentiel
| Maladie | Relation fièvre-éruption | Caractéristiques de l'éruption | Autres signes |
|---------|-------------------------|-------------------------------|---------------|
| A. Rougeole | Fièvre **avec** éruption | Maculopapules rouge foncé, de la région rétro-auriculaire → visage → tronc → extrémités | Taches de Koplik, coryza |
| B. Rubéole | Fièvre **avec** éruption | Maculopapules rose pâle, d'abord au visage → extension rapide au corps entier | Adénopathies rétro-auriculaires/occipitales |
| **✅ C. Exanthème subit** | **Éruption après défervescence** | Maculopapules rose vif, tronc → visage → extrémités, disparaissent en 1–2 jours | Forte fièvre (39–40°C), bon état général |
| D. Scarlatine | Fièvre **avec** éruption | Éruption érythémateuse punctiforme, lignes de Pastia dans les plis cutanés | Langue framboisée, pharyngite |
| E. Varicelle | Fièvre **avec** éruption | Distribution centripète : macules → papules → vésicules → croûtes (« quatre générations ») | Prurit intense |
### Pourquoi C ?
Indices clés dans l'énoncé :
- **8 mois** → La roséole est plus fréquente chez les nourrissons de 6 à 18 mois
- **Fièvre pendant 3 jours, éruption après défervescence** → **L'éruption post-fébrile est la caractéristique classique de la roséole**, contrastant nettement avec l'éruption fébrile des autres maladies exanthématiques
- Maculopapules rose vif, débutant au tronc → conforme à la progression de l'éruption de la roséole
### Points essentiels de la prise en charge
Maladie auto-limitante, aucun traitement antiviral spécifique nécessaire. Centré sur les soins de support :
- Contrôler la fièvre élevée (refroidissement physique, antipyrétiques)
- Assurer un apport hydrique suffisant
- Surveiller l'apparition de convulsions fébriles
```

## À propos de l'auteur

**Xllgreen (https://xllgreen.github.io)** — Étudiant en médecine clinique à l'Université de Jiujiang · Passionné de technologie

## Support technique

Projet PDF2App : https://pdf2app.cn

Microsoft Visual Studio Code : https://code.visualstudio.com/

Claude Code pour VS Code : https://claude.com/
© 2026 Anthropic PBC

<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
API DeepSeek : https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. Tous droits réservés.

<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
API Xiaomi Mimo : https://platform.xiaomimimo.com/
Copyright © 2010 – 2026 Xiaomi. Tous droits réservés.

## Licence

Le contenu de ce projet est compilé à partir de la 10e édition de *Pédiatrie* des Éditions Médicales du Peuple (PMPH), et est fourni à des fins d'étude et de référence uniquement.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FPediatrics-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
