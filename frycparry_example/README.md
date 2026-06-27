## 1.21 - example frycparry datapack

This datapack:

- creates custom parry attributes named **"my_parry_attributes"** and **"some_other_parry_attributes"** (`data/frycparry/parry_attributes/`)
- applies default sword attributes to trident and **"my_parry_attributes"** to pickaxes and **"some_other_parry_attributes"** to stick, dirt, iron sword and stone (`data/frycparry/parry_items/`)
- replaces set of items excluded from parrying to make parrying with trident possible (it is excluded by default) and disable parrying with stone shovel (`data/frycparry/tags/item/parrying_excluded_items.json`)
- enables parrying for trident, golden axe, stick and dirt (`data/frycparry/tags/item/items_can_parry.json`)
- makes vindicator and zombie immune to "disarmed" status effect (`data/frycparry/tags/entity_type/disarm_resistant_mobs.json`)


More info [here](https://github.com/Xires87/SwordParry#datapacks)