# Performance Mods
A list of performance-enhancing mods for 1.16.x forge/fabric versions.

Any suggestions/complaints?<br>
Join our [discord](https://discord.gg/8nzHYhVUQS) or use the issues.<br><br>
Mods marked as "*Dangerous*" might be unstable, and cause some unexpected behaviour.

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)


## Fabric 1.16.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement |
| --- | :---: | :---: | :---: | :---: |
| [Alternate Current](https://www.curseforge.com/minecraft/mc-mods/alternate-current) | Unknown | Alternate Current is an efficient and non-locational redstone dust implementation. | SpaceWalkerRS | Server |
| [Angerable Patch](https://www.curseforge.com/minecraft/mc-mods/angerable-patch) | Unknown | Fixes MC-192362 / MC-189565, which causes drastically large log file sizes and lag | Draylar | Client
| [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds) | Unknown | Removes the Block Entity Renderer from the bed and replaces it with the default minecraft model renderer. | Motschen | Client |
| [Better Biome Blend](https://www.curseforge.com/minecraft/mc-mods/better-biome-blend) | Sodium | Better Biome Blend is a mod  which accelerates the biome color blending algorithm. | FionaTheMortal | Client | 
| [C2ME](https://github.com/YatopiaMC/C2ME-fabric/releases) (***DANGEROUS***) | Tic-Tacs, + | A Fabric mod designed to improve the chunk performance of Minecraft. | YatopiaMC | Server |
| [Canvas](https://www.curseforge.com/minecraft/mc-mods/canvas-renderer) | Sodium | Advanced Rendering Engine for Fabric | grondag | Client |
| [Cull Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-leaves) | Unknown | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Motschen | Client |
| [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) (Dangerous) | Hydrogen, Enhanced Block Entities | This mod launches minecraft faster by caching all of the content on first launch and then loading that cache on the next one | alphaqu | Client |
| [Dimensional Threading](https://github.com/WearBlackAllDay/DimensionalThreading/releases) (Dangerous) | Unknown | Minecraft mod which optimizes the processing of multiple Dimensions, by assigning them independent threads | WearBlackAllDay | Server |
| [Enhanced Block Entities](https://modrinth.com/mod/ebe) | Sodium[⁴](/README.md#-some-of-the-mods-that-have-sodium-as-an-incompatibility-might-work-if-you-use-indium), DashLoader | EBE is a mod which aims to increase the performance of block entity rendering, as well as offer customizability via resource packs. | FoundationGames | Client |
| [Entity Distance](https://modrinth.com/mod/entity-distance) | Unknown | Allows the user to adjust the (client) distance at which different entities render | capnkork | Client | 
| [EntityCulling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | None | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible | tr9zw | Client |
| [FastBench](https://www.curseforge.com/minecraft/mc-mods/fastbench-for-fabric) | None | This is a mod aimed at improving performance of all crafting-related functions. | tfarecnim | Server |
| [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest) | Unknown | This mod helps by removing dynamic models from chests and making them render as static chunk geometry. | fake_domi | Client |
| [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fast-furnace-for-fabric) | None | Similar to FastWorkbench, it caches the last recipe used, and checks this recipe first before re-scanning the entire registry | tfarecnim | Server |
| [Fat Experience Orbs](https://www.curseforge.com/minecraft/mc-mods/fat-experience-orbs) | Unknown | This mod makes it so that nearby experience orbs merge together | NinjaPhenix | Server |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both |
| [Hopper Optimizations](https://github.com/2No2Name/hopperOptimizations) | Unknown | A mod that optimizes hoppers and their interactions with entities and inventories | 2No2Name | Server |
| [Hydrogen](https://modrinth.com/mod/hydrogen) | DashLoader | Reduces the memory usage of the game in more modded scenarios | CaffeineMC | Client |
| [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) | Unknown | Krypton is a Minecraft mod designed for the Fabric mod loader that implements a suite of optimizations focused on the Minecraft networking stack | astei | Server |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu) | Mods that remove the DFU | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | astei | Both |
| [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) | None | Lithium is a general-purpose optimization mod for Minecraft which works to improve a number of systems without changing any behavior | CaffeineMC | Server |
| [MCMT-Fabric](https://hatebin.com/zzlqgepiwk) (***DANGEROUS***) | Carpet, Dimensional Threading | This is a mod, that attempts to multithread minecraft's tick execution. | himekifee | Server |
| [Overworld Two](https://www.curseforge.com/minecraft/mc-mods/overworld-two) | Unknown | Optimization mod that generates overworld and nether terrain much faster than vanilla minecraft at the cost of breaking parity. | gegy1000, SuperCoder79 | Server |
| [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) | Starlight | Phosphor is a Minecraft mod which works to optimize one of game's most inefficient areas, the lighting engine | CaffeineMC | Both |
| [Recipe Cache](https://www.curseforge.com/minecraft/mc-mods/recipe-cache) | FastFurnace, FastBench (?) | Caches recipe lookup for crafting and furnaces to lessen server lag caused by crafting stacks of items and large amounts of furnaces ticking | biom4st3r1 | Server | 
| [Resolution Control](https://www.curseforge.com/minecraft/mc-mods/resolutioncontrol) | Unknown | ResolutionControl+ allows you to change Minecraft's render resolution separately from the HUD elements. | Ultimate Boomer | Client |
| [Smoke Suppresion](https://www.curseforge.com/minecraft/mc-mods/smoke-suppression) | Unknown | This is to prevent client-side lag and general annoyance when using large numbers of campfires in farms. | supersaiyansubtlety | Client |
| [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot) | Unknown | Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems | UltimateBoomer | Both |
| [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) | Mods that utilize of the FRAPI[⁴](/README.md#-some-of-the-mods-that-have-sodium-as-an-incompatibility-might-work-if-you-use-indium) | Sodium is a free and open-source rendering engine replacement for the Minecraft client that greatly improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft | CaffeineMC | Client |
| [Starlight](https://github.com/PaperMC/Starlight/releases) | Phosphor | Fabric mod for completely rewriting the vanilla light engine. | Spottedleaf (PaperMC) | Both |
| [Tic-Tacs](https://github.com/Gegy/tic-tacs/releases) (Dangerous) | C2ME | Tic-TACS is an experimental reimplementation of Minecraft's chunk loading engine | gegy | Server |
| [VanillaFix](https://github.com/DimensionalDevelopment/VanillaFix/releases) | Unknown | Bug fixes and optimizations for Minecraft | BoogieMonster1O1 (Dimensional Development) | Both |


## Forge 1.16.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement |
| --- | :---: | :---: | :---: | :---: |
| [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements)[⁵](/README.md#-ai-improvements-newer-versions-114-dont-have-as-much-impact-as-the-older-versions-have-since-in-newer-versions-of-minecraft-a-lot-of-fixes-to-the-ai-are-implemented-sources-curseforge-page-faq-dev) | None | Simplified AI modification mod focused on performance and low-level modifications to AIs in the game | QueenOfMissiles | Server |
| [APTweaks](https://www.curseforge.com/minecraft/mc-mods/adaptive-performance-tweaks) | Dynamic View (View Distance Feature), Clumps | Adaptive Performance Tweaks is a Minecraft Forge Mod which automatically adjust specific settings on the server and client side to allow a balanced TPS/FPS. | Kaworru | Server |
| [Better Biome Blend](https://www.curseforge.com/minecraft/mc-mods/better-biome-blend) | None | Better Biome Blend is a mod  which accelerates the biome color blending algorithm. | FionaTheMortal | Client |
| [Better Fps - Render Distance](https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance) | Unknown | Better FPS Render Distance is a mod which adds a few performance improvements to increase fps. | someaddon | Client |
| [C2ME](https://github.com/YatopiaMC/C2ME-forge/releases) (***DANGEROUS***) | Unknown | A Forge mod designed to improve the chunk performance of Minecraft. | YatopiaMC | Server |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | APTweaks, MCMT | Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area | jaredlll08 | Both |
| [DataFixerSlayer](https://www.curseforge.com/minecraft/mc-mods/datafixerslayer) (Dangerous[³](/README.md#-do-not-blame-me-if-you-didnt-read-this-notice-if-you-try-to-load-a-older-world-in-a-newer-instance-of-the-game-and-you-have-one-of-these-mods-installed-bad-things-will-happen-uninstall-the-mod-first)) | Any other mod that also removes DFU | DataFixerSlayer prevents the DataFixerUpper (DFU) system from loading | Vazkii | Both |
| [DrawerFPS](https://www.curseforge.com/minecraft/mc-mods/drawerfps) | Unknown | Simple, efficient mod which lets you configure at which range Storage Drawers do render items to improve fps. | someaddon | Client |
| [Dynamic View](https://www.curseforge.com/minecraft/mc-mods/dynamic-view) | APTweaks | This is a small/light serverside utility mod to help balancing lag (TPS) and chunk view/load distance. | someaddon | Server |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entity-culling) | None | Entity Culling is a small client-side performance core mod which improves the rendering of entities and tile entities. | meldexun | Client |
| [EntityCulling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | None | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible | tr9zw | Client |
| [FastFurnace minus Replacement](https://www.curseforge.com/minecraft/mc-mods/fastfurnace-minus-replacement) | None | Similar to FastWorkbench, it caches the last recipe used, and checks this recipe first before re-scanning the entire registry. | tfarecnim | Server |
| [FastSuite](https://www.curseforge.com/minecraft/mc-mods/fastsuite) | Unknown | FastSuite is a mod about improving recipe performance, it improves upon all mods that use the JSON recipe system, rather than just a specific subset of recipes | Shadows_of_Fire | Server |
| [FastWorkbench minus Replacement](https://www.curseforge.com/minecraft/mc-mods/fastworkbench-minus-replacement) | None | This is a mod aimed at improving performance of all crafting-related functions. | tfarecnim | Server |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both |
| [Get It Together, Drops!](https://www.curseforge.com/minecraft/mc-mods/get-it-together-drops) | Unknown | This mod adds two configuration options to control how dropped items combine on the ground. This can significantly improve performance in areas with lots of dropped items | bl4ckscor3 | Server |
| [Halogen⁶](https://www.curseforge.com/minecraft/mc-mods/halogen) | Performant, Immersive Portals | A Forge port of Sodium | spoorn | Client |
| [Krypton Reforged](https://www.curseforge.com/minecraft/mc-mods/krypton-reforged) | Unknown | Krypton Reforged is a Forge port of Krypton a Minecraft mod designed for the Fabric mod loader that implements a suite of optimizations focused on the Minecraft networking stack | TeamDeusVult | Server |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazy-dfu-forge) | Mods that remove the DFU | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | Corgi_Taco | Both |
| [MCMT](https://hatebin.com/swopimmvaw) (***DANGEROUS***) | Immersive Portals, Performant, Clumps, ***+++*** | This is a mod, that *attempts* to multithread minecraft's tick execution. | jediminer543 | Server |
| [Magnesium, Sulfuric, Hydrogen Reforged](https://www.curseforge.com/members/someoneelsewastaken/projects) | Unknown | Unofficial ports to forge of Sodium and Phosphor respectively. | someoneelsewastaken | ~~----~~ |
| [Out of Sight](https://www.curseforge.com/minecraft/mc-mods/out-of-sight) | Unknown | Out of Sight simply stops modded tile entities from rendering if they are further than 24 blocks away | Corosus | Client |
| [Overworld Two](https://www.curseforge.com/minecraft/mc-mods/overworld-two-forge) | Unknown | Optimization mod that generates overworld and nether terrain much faster than vanilla minecraft at the cost of breaking parity. | Corgi_Taco, gegy1000, SuperCoder79 | Server |
| [Performant](https://www.curseforge.com/minecraft/mc-mods/performant) (**Dangerous**) | Phosphophyllite, Resourceful Bees, + | Lightweight mod project which hugely improves performance and blocklag. | someaddon | Server |
| [RoadRunner](https://www.curseforge.com/minecraft/mc-mods/roadrunner) | Performant | RoadRunner is an unofficial fork of the popular performance-enhancing Fabric mod Lithium by jellysquid3 for the Forge mod loader. | MaxNeedsSnacks | Server |
| [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot-forge) | Unknown | Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems | UltimateBoomer | Both |
| [Spawner Bug Fix](https://www.curseforge.com/minecraft/mc-mods/spawner-fix) | Unknown | This addresses a bug which causes lag in mods that create custom spawners. | Lupicus | Client |
| [Starlight](https://github.com/PaperMC/Starlight/releases) | Create | Mod for completely rewriting the vanilla light engine. | Spottedleaf (PaperMC) | Both |
| [Starlight x Create](https://www.curseforge.com/minecraft/mc-mods/starlight-x-create) | Unknown | Mod for completely rewriting the vanilla light engine. | Spottedleaf(PaperMC), Create Patch by: AeiouEnigma, Curseforge Upload and 1.16 Maintained by SirOMGitsYOU | Both |
| [~~⠀⠀Cull Particles⠀⠀~~](https://www.curseforge.com/minecraft/mc-mods/cull-particles)[²](/README.md#-cull-particles-isnt-needed-anymore-in-newer-forge-versions-as-it-was-implemented-in-forge)| None | This mod increases fps by not rendering particles that the player can't see | tfarecnim | Client |


[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)
