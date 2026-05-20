## [unreleased]

### 🚀 Features

- *(pipelines)* Adding release, build and changelog pipelines

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
- RS Reassign on rack update (#3646)
- Herder Requests
- 4 new breads, only craftable by the baker! (#5970)
- Fast pickup of specific items after crafting (#6067)
- *(schemtic)* Walls fortress moatgatehouse (#7493)
- Fix anchor point of the fortress mine (#8524)
- Fix deprecation warning for getEnchantmentLevel (#8637)
- Quest log [1.20] (#9320)
- Prevent crash on old corrupted job data on world upgrade
- Fix crafters/couriers not fireable
- Messages
- Call sites
- Attribute serialization changed - do we care?
- Quarrier's interaction with the zigzag iterator (#9959)
- Move domum crafting to its own tab (#10109)
- Rotation of pillarwalk4 (#10515)
- New alternative half chunk Fortress library (#10838)
- Remove fence towards the magma area of the Desert Oasis nether mine (#10910)
- Alchemist, Apiary, Bakery (#10955)
- New walls in Ancient Athens (#10996)
- Feature/colony connections (#11012)
- Both guard tower styles in Minecolonies Original looked the same (#11131)
- Rescan of Desert Oasis world gen files in 1.21 (#11188)
- New Fortress gatehouse (#11207)
- New Fortress -> Cavern adapter decoration (#11279)
- Postbox Minimum Stock, second attempt  (#11280)
- Crafter infinite loop due to ingredient/craft count mismatch (#11305)
- Smelting crafters could not request fuel (#11367)
- Anchor in Colonial residence (#11538)
- Several Dark Oak Treehouse fixes (#11556)
- Tags and signs (#11613)
- Infinite loop in resource gathering quarry (#11615)
- Use regular placeholders instead of solid placeholders in the Colonial courier's hut (#11670)
