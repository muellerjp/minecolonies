## [unreleased]

### 🐛 Bug Fixes

- *(translation)* Reenabling translations properly for open-minecolonies
## [omc-v0.0.8] - 2026-05-22

### 🐛 Bug Fixes

- *(translation)* Removing the languagehandler path call

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.7] - 2026-05-22

### 🐛 Bug Fixes

- *(dependencies)* Updateing versions of the minecol dependencies

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.6] - 2026-05-21

### 🐛 Bug Fixes

- *(release)* Fixing fileversions to include tags with clear fallback

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.5] - 2026-05-21

### 🐛 Bug Fixes

- *(release)* Testing build folders

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.4] - 2026-05-21

### 🐛 Bug Fixes

- *(release)* Typo

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.3] - 2026-05-21

### 🐛 Bug Fixes

- *(build+release)* Wrote custom build.gradle for runClient and build testing with other mods; updated gradle properties; fixed build.yml to produce correct version strings; simplyfied release.yml
- *(build)* Updated versions in gradle.properties; updated minecolonies dependencies to implementation dependencies

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.2] - 2026-05-20

### 🐛 Bug Fixes

- *(release)* Changing the build file names; and only submitting one file to curseforge

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [omc-v0.0.1] - 2026-05-20

### 🐛 Bug Fixes

- *(pipelines)* Fixing branch filters and add custom tag prefix

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
## [ocm-v0.0.1] - 2026-05-20

### 🚀 Features

- *(pipelines)* Adding release, build and changelog pipelines
- *(logo)* Add open-minecolonies logo

### 🐛 Bug Fixes

- *(docu)* Updated readme with logo and disclaimer
- *(release)* Adding cursforge-id
- *(tiers)* Make getItemTier and getItemLevel use nbt
- *(naming)* Changed name of initVanillaEquipmentTiers to initRegisterEquipmentTiers.
- *(miner)* Reverting tag-change to keep backwards compatibility for styles
- *(miner)* Added todo to remove tag fallback in next major version; added devcontainer to gitignore
- *(miner)* Removing hardcoded minecraft sign requirement. Replaced with tag check to allow all blocks that are registered as signs.

### ⚙️ Miscellaneous Tasks

- *(changelog)* Update CHANGELOG.md
- *(changelog)* Update CHANGELOG.md
- *(changelog)* Update CHANGELOG.md
## [1.21.1-1.1.1313-snapshot] - 2026-05-19

### 💼 Other

- Use regular placeholders instead of solid placeholders in the Colonial courier's hut (#11670)
## [1.21.1-1.1.1299-snapshot] - 2026-04-06

### 💼 Other

- Infinite loop in resource gathering quarry (#11615)
## [1.21.1-1.1.1295-snapshot] - 2026-04-03

### 💼 Other

- Tags and signs (#11613)
## [1.21.1-1.1.1280-snapshot] - 2026-02-22

### 💼 Other

- Several Dark Oak Treehouse fixes (#11556)
## [1.21.1-1.1.1264-snapshot] - 2026-02-11

### 💼 Other

- Anchor in Colonial residence (#11538)
## [1.21.1-1.1.1192] - 2025-11-14

### 💼 Other

- Smelting crafters could not request fuel (#11367)
## [1.21.1-1.1.1168] - 2025-11-02

### 💼 Other

- Crafter infinite loop due to ingredient/craft count mismatch (#11305)
## [1.21.1-1.1.1159] - 2025-10-26

### 💼 Other

- Postbox Minimum Stock, second attempt  (#11280)
## [1.21.1-1.1.1152] - 2025-10-20

### 💼 Other

- New Fortress -> Cavern adapter decoration (#11279)
## [1.21.1-1.1.1134] - 2025-09-23

### 💼 Other

- New Fortress gatehouse (#11207)
## [1.21.1-1.1.1133] - 2025-09-22

### 💼 Other

- Rescan of Desert Oasis world gen files in 1.21 (#11188)
## [1.21.1-1.1.1100] - 2025-08-24

### 💼 Other

- Both guard tower styles in Minecolonies Original looked the same (#11131)
## [1.21.1-1.1.1061] - 2025-08-03

### 💼 Other

- Feature/colony connections (#11012)
## [1.21.1-1.1.1033] - 2025-07-13

### 💼 Other

- New walls in Ancient Athens (#10996)
## [1.21.1-1.1.1009] - 2025-06-22

### 💼 Other

- Alchemist, Apiary, Bakery (#10955)
## [1.21.1-1.1.979] - 2025-06-01

### 💼 Other

- Remove fence towards the magma area of the Desert Oasis nether mine (#10910)
## [1.21.1-1.1.951] - 2025-05-10

### 💼 Other

- New alternative half chunk Fortress library (#10838)
## [1.21.1-1.1.819] - 2024-12-08

### 💼 Other

- Rotation of pillarwalk4 (#10515)
## [1.1.660-1.21.1-beta] - 2024-08-24

### 💼 Other

- Move domum crafting to its own tab (#10109)
## [1.1.630] - 2024-08-18

### 💼 Other

- Quest log [1.20] (#9320)
- Prevent crash on old corrupted job data on world upgrade
- Fix crafters/couriers not fireable
- Messages
- Call sites
- Attribute serialization changed - do we care?
- Quarrier's interaction with the zigzag iterator (#9959)
## [1.0.1190-ALPHA] - 2023-01-14

### 💼 Other

- Fix anchor point of the fortress mine (#8524)
- Fix deprecation warning for getEnchantmentLevel (#8637)
## [0.14.330-ALPHA] - 2021-08-15

### 💼 Other

- *(schemtic)* Walls fortress moatgatehouse (#7493)
## [0.13.626-ALPHA] - 2021-02-18

### 💼 Other

- 4 new breads, only craftable by the baker! (#5970)
- Fast pickup of specific items after crafting (#6067)
## [0.10.291-ALPHA] - 2019-06-03

### 💼 Other

- Herder Requests
## [0.10.290-ALPHA] - 2019-06-02

### 💼 Other

- RS Reassign on rack update (#3646)
## [0.10.197-RELEASE] - 2018-12-28

### 💼 Other

- ImageButton added; Image sub-image offset/size; all copy constructors removed, as behavior was never supported.
- Stage, Tree, and AI outline complete
- ChopTree
- Find and Chop down trees
- Damage Axe, Plant Saplings, Dump inventory
- Initial cluster search commit
- Use queues(works great!), sort clusters after creation
- Animations and sounds
- Use Forge ToolTypes
- Item damage works and tool breaks
- Use isWood instead of instanceof BlockLog
- Smaller CLUSTER_TREE_DISTANCE
- Initial* breaking leaves commit
- Deposit Sapling Stacks if have more than 5 (a bit overkill maybe)
- Gather items, Leaf block drops
- Improved tree detection
- Break logs faster with better tools. Also nerfs the lumberjack for most axe types.
- Client <-> Server Messaging
- Support images of size other than 256x256
- Fixes rendering bug of itemIcon 2: NotNull sucks
- Unmark TessellatorRenderHandler as Utility class (#2366)
- Builder now creates a TileEntity if it is not present in the template.
- Control possible lag in building's onWorldTick() (#2637)
- Baker skipping last Recipe (#2650)
