# Problème de génération du Riz Zèle (Hearty Grains)

## Problème identifié

Les erreurs suivantes apparaissent dans les logs :
```
[ERROR]: Block-attached entity at invalid position: class_2338{x=620, y=-24, z=-302}
[ERROR]: Block-attached entity at invalid position: class_2338{x=620, y=-20, z=-303}
```

## Cause probable

Le mod Cobblemon essaie de générer des `cobblemon:hearty_grains` (riz zèle) dans les marais, mais :
- Les positions générées sont invalides (Y négatif, sous l'eau)
- Le jeu rejette ces placements
- Résultat : aucun riz zèle n'apparaît dans les marais

## Solutions possibles

### Solution 1 : Correction appliquée ✅
**PROBLÈME TROUVÉ ET CORRIGÉ !**

Le problème venait des fichiers de génération de Cobblemon qui fixaient la hauteur à Y=62 de manière absolue. Cela causait des erreurs quand le terrain était à d'autres niveaux.

**Correction appliquée :**
- Création de fichiers de surcharge dans `datapacks/Academy/data/cobblemon/worldgen/placed_feature/`
- Modification de la hauteur pour utiliser une plage flexible (Y 50-64 au-dessus du fond) au lieu d'une hauteur fixe
- Les fichiers `swamp_grains.json` et `plains_grains.json` ont été corrigés

### Solution 2 : Attendre une mise à jour du mod
La génération de `hearty_grains` est gérée directement par le mod Cobblemon. Une correction a été appliquée via votre datapack pour surcharger la génération défectueuse.

### Solution 2 : Planter manuellement
Vous pouvez obtenir du riz zèle via :
- Les matériaux naturels des Pokémon (défini dans `natural_materials/farmersdelight.json`)
- Planter manuellement dans les marais sur les blocs valides :
  - `minecraft:mud`
  - `minecraft:farmland`
  - `minecraft:muddy_mangrove_roots`
  - `farmersdelight:rich_soil_farmland`

### Solution 3 : Vérifier la configuration Cobblemon
Vérifier si Cobblemon exporte des fichiers de configuration après la première exécution qui pourraient permettre de modifier la génération.

## Tags de plantation configurés

- **Sur terre** : `datapacks/Academy/data/cobblemon/tags/block/hearty_grains_land_plantable.json`
- **Dans l'eau** : `datapacks/Academy/data/cobblemon/tags/block/hearty_grains_water_plantable.json`

## Note

Le `wild_rice` de Farmer's Delight (configuré avec chance 20 dans `config/farmersdelight-common.json`) est un item différent et ne devrait pas interférer avec `hearty_grains` de Cobblemon.
