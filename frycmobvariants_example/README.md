## 1.21 - example frycmobvariants datapack

This datapack:
- prevents zombie to explorer conversion by replacing "zombie_to_explorer.json" (`data/frycmobvariants/mob_conversion_rules/zombie_to_explorer.json`)
- gives zombies iron axe or netherite pickaxe and leather helmet or diamond helmet (or no helmet) - this rule has the lowest priority, so it works only when other rules fail (`data/frycmobvariants/mob_conversion_rules/zombie_eq_test.json`)
- defines "frycmobvariants:sheep_to_zombie_convert_biomes" biome tag (`data/frycmobvariants/tags/worldgen/biome/sheep_to_zombie_convert_biomes.json`)
- converts sheeps to zombies on biomes from "frycmobvariants:sheep_to_zombie_convert_biomes" tag and initializes their equipment (`data/frycmobvariants/mob_conversion_rules/sheep_to_zombie.json`)
- converts pigs to withers - chance increases as X coordinate increases and is equal to 0% on 10000 X (and below) and equal to 100% on 20000 X (and above) (`data/frycmobvariants/mob_conversion_rules/pig_to_wither.json`)
- makes forgotten drops emeralds when killed with looting (`data/frycmobvariants/loot_table/entities/forgotten.json`)
- converts endermen to shulkers when not in end dimension (`data/frycmobvariants/mob_conversion_rules/enderman_to_shulker.json`)

More info [here](https://github.com/Xires87/MobVariants#datapacks)