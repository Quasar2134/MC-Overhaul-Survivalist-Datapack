# MC-Overhaul-Survivalist-Datapack
Survival overhaul datapack for Minecraft Java Edition 1.21.5


Installation:
1) Download datapack.zip and resourcepack.zip and extract both
2) In the Minecraft launcher click on 'Installations', then click on the folder icon to the right of the version, 1.21.5.
3) Move the folder, MC Overhaul Survivalist, from the extracted resource pack zip file into .minecraft/resourcepacks .
4) In the main menu, navigate to Options -> Resource Packs... then select, MC Overhaul Survivalist
5) In the world creation menu, navigate to More -> Data Packs -> Open Pack Folder which will open a temporary folder. Move the folder, MC Overhaul Survivalist, from the extracted datapack file into the temp folder.
6) World can then be created.

Important!:
- Don't invoke mc_overhaul:hard_reset function (resets every advancement and reloads the server). Only used for debug purposes.
- Some items can be destroyed when handheld, worn as armour or dropped when submerged in fluids, but not when in any other inventory slot (be careful when looting shipwrecks!)
- Items taken from the creative inventory won't have the components stated in the features below (they must be obtained naturally)

Features:
  - More biome placed features, refurbished biomes and structures as well as new structures
  - 3 new overworld biomes
  - 4 new structures
  - 3 new advancement tabs representing compendiums to unlock with lore and brief descriptions for each entry
    - Biomes are unlocked when entering the respective biome on solid ground, but in the overworld and end the sky must be seen
    - Structures are unlocked when entering the respective structure
    - Mobs are unlocked by completing certain tasks/challenges as well as looking at them through a spyglass
  - More mobs now have non-zero knockback resistance
  - Improved recipes
  - New hydration system that leads to death if not taken care of, submerge into freshwater, fill water bottles or eat certain foods to replenish. Fire resistance effect will also stop hydration drain.
  - TNT is more volatile and most explosions create chain reactions
    - Gamerule, tntExplodes=false will stop regular tnt from exploding as well as remove all explosion volatility and chain reactions
  - Sleeping now passes time on status effects
  - Many items are now immune to fire and some are immune to lava and or explosions
  - Swords can block most attacks (except for wooden and stone) with a smaller delay frame than a shield, but not explosions or projectiles
  - Some items change or get destroyed when subject to lava, fire or water
    - Paper, Sugar, Maps, etc are dissolved in water
    - Bowls of soup/stew lose their food underwater
    - Sponges are converted to wet sponges when underwater
    - Bee hives/nests will force the bees out when underwater
  - Improved falling block physics with destructive effects
  - Elytra can be de-activated in survival mode by sneaking
