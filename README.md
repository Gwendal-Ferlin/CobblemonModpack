# Changelog - Cobblemon Academy 2.0 (Version Corrigée)

Ce document liste toutes les modifications apportées à chaque version du modpack corrigé.

---

## Format de versionnage

Les versions suivent le format : `vX.Y.Z`
- **X** : Version majeure (changements majeurs, incompatibilités)
- **Y** : Version mineure (ajouts de fonctionnalités, mods)
- **Z** : Version patch (corrections de bugs, ajustements)

---

## [v1.0.0] - 03-02-2026

### 📋 Résumé

Version initiale du modpack corrigé basé sur **Cobblemon Academy 2.0**.

#### 🔧 Corrections principales
- ✅ **Système de combat** : Correction du mod Raid Dens
- ✅ **Safari** : Correctif pour rendre le Safari fonctionnel
- ✅ **Items légendaires** : Ajustement du spawn dans le datapack Academy

#### ✨ Nouveaux mods (11)
- 🎮 **Système de raids** : 6 niveaux de rareté avec probabilités configurées
- 🥚 **Reproduction** : Système de breeding complet dans les pastures
- ⚡ **Méga-Évolutions** : Incluant les formes ZA (non fonctionnelles)
- 🌟 **Mécaniques avancées** : Z-Moves, Tera, Dynamax/Gigantamax, fusions
- 💰 **Économie** : Système d'argent (CobbleDollars) et système de Grading/Safari (Numismatic Overhaul)
- 🌌 **Dimension** : Eternal Starlight pour le Safari

#### 📦 Datapacks (8)
- **300+ Pokémon** ajoutés aux raids :
  - 141 Légendaires et Mythiques (TIER_SEVEN)
  - 50+ Méga-Évolutions (TIER_SEVEN)
  - 101+ Pokémon du Pokédex National (TIER_ONE à TIER_FIVE)
  - 30 Ultra-Chimères et Pokémon Paradoxe (TIER_FIVE à TIER_SEVEN)
  - Formes Dynamax/Gigantamax (TIER_SEVEN)
  - Mécanique Tera
- **5 arènes thématiques** : Fire, Water, Grass, Fighting, Ice Arena

### 🛠️ Préparation

> ⚠️ IMPORTANT : Installer la version 2.1 --- https://www.curseforge.com/minecraft/modpacks/cobblemon-academy-2-0

### ✨ Modifications

#### Mods (dans le dossier /mods)

- `Abes-Hutts-Cobblemon` - Version 1.7.1-1.0.2
  - Modification : <span style="color:red">Supprimer l'ancienne version (a faire meme si le dossier mod est récupérer)</span>
  - Description : Correction du mod combat (Raid Dens)
  - Lien : [Curseforge](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/academy-mc1.21.1-v2.0.0%2Bbuild.514-fabric.jar)

- `academy-mc1.21.1` - Version v2.0.0+build.514
  - Modification : <span style="color:red">Supprimer l'ancienne version</span>
  - Description : Correctif Safari
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/tree/main/mods)

- `Accessories` - Version 1.21.1-1.7.1-1.0.2
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Compatibilité Raid Dens
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/accessories-fabric-1.1.0-beta.52%2B1.21.1.jar)

- `CobbledGacha` - Version 1.21.1-2.1.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout de machine de Gambling (Non actif sur le serveur)
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/cobbledgacha-fabric-1.21.1-2.1.1.jar)

- `CobbleDollars` - Version 2.0.0+Beta-5.1+1.21.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout de système d'argent dans le jeu (shop non actif pour le moment)
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/CobbleDollars-fabric-2.0.0%2BBeta-5.1%2B1.21.1.jar)

- `Cobblemonraiddens` - Version 0.6.4+1.21.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout d'un systeme de raid avec 6 niveau de rareté et tout type de pokémon. Configuration des probabilités de spawn dans l'overworld : 9.0, 15.0, 25.0, 25.0, 20.0, 5.0, 1.0 (valeurs de rareté décroissantes). Voir section Datapack pour les differents pokémon
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/cobblemonraiddens-fabric-0.6.4%2B1.21.1.jar)

- `Cobbreeding` - Version 2.1.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Système de reproduction dans les pastures. Les Pokémon compatibles pondent des œufs après activation. Héritage : IVs (Power items, Destiny Knot), Nature (Everstone), Forme régionale, Abilité (y compris cachée), Eggmoves (tous les moves appris), Pokeball. Shiny hunting (Masuda/Gen2). Oeufs éclosent dans l'inventaire. Mirror Herb pour apprendre les Egg Moves.
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/Cobbreeding-fabric-2.1.1.jar)

- `Eternal Starlight` - Version 0.4.2-hotfix+1.21.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout d'Eternal Starlight pour avoir une dimension focntionnel pour le safari
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/eternalstarlight-0.4.2-hotfix%2B1.21.1%2Bfabric.jar)

- `Mega Showdown` - Version 1.6.3+1.7.2+1.21.1
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout de mega evolutions, Z-Move, Tera Cristallisation, Gigamax, correctif de certains models, ajout de fusions (kyurem/necrozma), certains formes (Zygarde/Zacian/Groudon/Kyogre) et permet de monter certains pokémon en plus (dont Rayquaza).
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/mega_showdown-fabric-1.6.3%2B1.7.2%2B1.21.1.jar)

- `Mega Showdown Item Pack` - Version 1.4.2
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Permet le crafs de certains item de Megashowdown (dont changement de forme).
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/mega-showdown-item-pack-1.4.2.jar)

- `Numismatic Overhaul` - Version 0.3.5+1.21
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Dépendance du Safari. Ajout d'un systeme économique pour pouvoir entrer dans le safari et grader ces cartes.
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/numismatic-overhaul-0.3.5%2B1.21.jar)

- `Navas ZA Megas` - Version 1.5
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajout des méga evolutions du jeu Pokémon ZA (non fonctionnel)
  - Lien : [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/blob/main/mods/zamega-fabric-1.5.jar)
  


#### Datapacks (/datapacks que coté serveur, pas necessaire coté ordi)

- `Academy`
  - Modification : <span style="color:lightyellow">Modification du code</span>
  - Description : Correctif pour ajuster le spawn des items légendaires. Correctif pour rendre le safari fonctionnel
  - Emplacement : `datapacks/Academy/`

- `cobblemonraiddens-legendaries`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute 141 Pokémon Légendaires et Mythiques aux raids (TIER_SEVEN). Inclut toutes les générations (1-9), formes régionales, formes Origin (Dialga, Palkia, Giratina), et toutes les formes d'Arceus et Silvally
  - Emplacement : `datapacks/cobblemonraiddens-legendaries/`

- `cobblemonraiddens-mega`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute 50+ formes Méga-Évolution (hors ZA) aux raids (TIER_SEVEN). Mécanique MEGA : Pokémon apparaissent automatiquement en forme Méga. Inclut Primal Groudon et Primal Kyogre
  - Emplacement : `datapacks/cobblemonraiddens-mega/`

- `cobblemonraiddens-natdex`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute 101+ Pokémon du Pokédex National aux raids (TIER_ONE à TIER_FIVE). Répartition par difficulté : débutants (Wurmple) à avancés (Kingambit, Baxcalibur). Inclut formes régionales et variantes
  - Emplacement : `datapacks/cobblemonraiddens-natdex/`

- `cobblemonraiddens-ub+paradox`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute 30 Ultra-Chimères et Pokémon Paradoxe aux raids (TIER_FIVE à TIER_SEVEN). Inclut toutes les Ultra-Chimères (Nihilego à Blacephalon), Pokémon Paradoxe du Passé (Scarlet) et du Futur (Violet)
  - Emplacement : `datapacks/cobblemonraiddens-ub+paradox/`

- `cobblemonraiddens-dynamax`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute la mécanique Dynamax/Gigantamax aux raids (TIER_SEVEN). 35+ formes Gigantamax (Générations 1 et 8). Mécanique DYNAMAX : transformation avec den spécial. Inclut Eternatus Eternamax
  - Emplacement : `datapacks/cobblemonraiddens-dynamax/`

- `cobblemonraiddens-tera`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute la mécanique Tera aux raids. Mécanique TERA : Pokémon peuvent apparaître avec un type Tera. Archive à confirmer après extraction complète
  - Emplacement : `datapacks/cobblemonraiddens-tera/`

- `CobblemonRaidDenDesigns-0.3_RELEASE`
  - Modification : <span style="color:lightgreen">Ajout dans le dossier</span>
  - Description : Ajoute 5 arènes thématiques personnalisées pour les raids. Remplace les dens standards par des structures NBT : Fire Arena, Water Arena, Grass Arena, Fighting Arena, Ice Arena. Arènes assignées selon le type du Pokémon
  - Emplacement : `datapacks/CobblemonRaidDenDesigns-0.3_RELEASE/`


#### Configurations

- `Eternal Starlight` (fichier de configuration)
  - Mod concerné : Eternal Starlight
  - Changements : Ajout du fichier de configuration de la version Academy 1.4 pour configurer la dimension Safari
  - Emplacement : `config/eternal_starlight.json`

- `cobblemon/spawning/`
  - Mod concerné : Cobblemon
  - Changements : Ajout du dossier de configuration pour le spawn des Pokémon dans la génération de la dimension Eternal Starlight (Safari)
  - Emplacement : `config/cobblemon/spawning/`

### ⚠️ Problèmes connus

    - Méga-Évolutions ZA non fonctionnelles
    - Fossiles non dropable
    - Shop CobbleDollards non intégré
    - Loot CobbledGacha a rebalancé (mod désactivé)

### 🔗 Liens utiles

    - [Github](https://github.com/Gwendal-Ferlin/CobblemonModpack/)
    - [Modpack Curseforge](https://www.curseforge.com/minecraft/modpacks/cobblemon-academy-2-0)

---

## Légende

- ✨ **Modifications** : Nouvelles fonctionnalités, mods, datapacks, etc.
- 🐛 **Corrections** : Bugs corrigés
- ⚠️ **Problèmes connus** : Bugs ou limitations non résolus

---

## Historique des versions

| Version | Date | Description | Statut |
|---------|------|-------------|--------|
| v1.0.0 | 03/02/2026 | Version initiale corrigée | ✅ |

**Statuts** :
- ✅ **Stable** : Version testée et fonctionnelle
- 🔄 **En développement** : Version en cours de travail
- ⚠️ **Beta** : Version de test avec problèmes connus
- 🚫 **Dépréciée** : Version obsolète, ne plus utiliser

