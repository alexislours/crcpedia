# ItemParam
**Named columns**: 91/98

**Documented columns**: 63/98

**Description**: The big table everyone loves. Params for every item in the game
## AudioPreset

**Name**: AudioPreset

**Hash**: 0x2654be7c

**Hashed string**: AudioPreset.hshCstringRef

**Notes**: Audio quality for music players

**Versions**: , , , , 

## CarpetMaterial

**Name**: CarpetMaterial

**Hash**: 0x9c32cf82

**Hashed string**: CarpetMaterial s32

**Notes**: Determines footstep sound (and possibly effect)

**Versions**: , , , , 

## ClothGroup

**Name**: ClothGroup

**Hash**: 0x690e3379

**Hashed string**: ClothGroup.hshCstringRef

**Notes**: Groups clothing variants. Match to Labels in ItemClothGroup, and use UniqueIDs from that table to reference clothing name strings

**Versions**: , , , , 

## Color1

**Name**: Color1

**Hash**: 0xa6b1a7fd

**Hashed string**: Color1.hshCstringRef

**Versions**: , , , , 

## Color2

**Name**: Color2

**Hash**: 0xb7cccd84

**Hashed string**: Color2.hshCstringRef

**Versions**: , , , , 

## DebugFtrSeries

**Name**: DebugFtrSeries

**Hash**: 0x0e0acf95

**Hashed string**: DebugFtrSeries.hshCstringRef

**Notes**: _UNK_00000000_ and 'None'

**Versions**: , , , , 

## Depth

**Name**: Depth

**Hash**: 0xf8316716

**Hashed string**: Depth f32

**Notes**: I can't find the hash in code at all (0xf831, 0x6716, and 0xf8316716), so either I'm doing something wrong or it's just unused

**Versions**: , , , , 

## DragSE

**Name**: DragSE

**Hash**: 0x43507f0d

**Hashed string**: DragSE.hshCstringRef

**Notes**: Drag sound effect

**Versions**: , , , , 

## FossilSet

**Name**: FossilSet

**Hash**: 0xd7f212ea

**Hashed string**: FossilSet.hshCstringRef

**Versions**: , , , , 

## Height

**Name**: Height

**Hash**: 0xc187c516

**Hashed string**: Height f32

**Notes**: the height of the item, used in a bunch of places such as determining where rocks and fossils can appear

**Versions**: , , , , 

## ItemAct

**Name**: ItemAct

**Hash**: 0xf1246e5f

**Hashed string**: ItemAct.hshCstringRef

**Notes**: Interaction type (LoopAuto = passive animation)

**Versions**: , , , , 

## ItemCatalogType

**Name**: ItemCatalogType

**Hash**: 0xdaf0238c

**Hashed string**: ItemCatalogType.hshCstringRef

**Notes**: Determines if the item is on sale in the catalog, not for sale in the catalog, or doesn't even appear in the catalog

**Versions**: , , , , 

## ItemDailyCategory

**Name**: ItemDailyCategory

**Hash**: 0x8900b8a0

**Hashed string**: ItemDailyCategory.hshCstringRef

**Notes**: Possibly related to Nature Day Nook Miles+ achievements

**Versions**: , 

## ItemFrom

**Name**: ItemFrom

**Hash**: 0xdb1a2f07

**Hashed string**: ItemFrom.hshCstringRef

**Notes**: Where the item is obtained. Used for HHA base points

**Versions**: , , , , 

## ItemGender

**Name**: ItemGender

**Hash**: 0xf80e9fee

**Hashed string**: ItemGender.hshCstringRef

**Notes**: Seems to prevent villagers from wearing non-matching gendered items? (What's NpcGender then?)

**Versions**: , , , , 

## ItemHHACategory

**Name**: ItemHHACategory

**Hash**: 0xf17f8753

**Hashed string**: ItemHHACategory.hshCstringRef

**Notes**: Used for category bonus for HHA calculations

**Versions**: , , , , 

## ItemHHAPart

**Name**: ItemHHAPart

**Hash**: 0x16a66e06

**Hashed string**: ItemHHAPart.hshCstringRef

**Notes**: Used for type bonus for HHA calculations

**Versions**: , , , , 

## ItemHHASeason

**Name**: ItemHHASeason

**Hash**: 0x05639ab0

**Hashed string**: ItemHHASeason.hshCstringRef

**Notes**: Used for seasonal and lucky bonuses for HHA calculations ('All' = lucky)

**Versions**: , , , , 

## ItemHHASet

**Name**: ItemHHASet

**Hash**: 0x059d1682

**Hashed string**: ItemHHASet.hshCstringRef

**Notes**: Used for set bonus for HHA calculations

**Versions**: , , , , 

## ItemHHASituation1

**Name**: ItemHHASituation1

**Hash**: 0xa7c79784

**Hashed string**: ItemHHASituation1.hshCstringRef

**Notes**: Used for situation bonus for HHA calculations

**Versions**: , , , , 

## ItemHHASituation2

**Name**: ItemHHASituation2

**Hash**: 0xb6bafdfd

**Hashed string**: ItemHHASituation2.hshCstringRef

**Notes**: 2nd situation grouping

**Versions**: , , , , 

## ItemHHATheme

**Name**: ItemHHATheme

**Hash**: 0xd61205d0

**Hashed string**: ItemHHATheme.hshCstringRef

**Notes**: Used for theme bonus for HHA calculations

**Versions**: , , , , 

## ItemHobbyType

**Name**: ItemHobbyType

**Hash**: 0x7b2fdfc1

**Hashed string**: ItemHobbyType.hshCstringRef

**Notes**: Could possibly be related to villagers' HobbyPoint values in their NpcRoom bymls?

**Versions**: , , , , 

## ItemKind

**Name**: ItemKind

**Hash**: 0x5270eb75

**Hashed string**: ItemKind.hshCstringRef

**Notes**: Type of item

**Versions**: , , , , 

## ItemLayout

**Name**: ItemLayout

**Hash**: 0x9dcea17e

**Hashed string**: ItemLayout.hshCstringRef

**Notes**: Determines if the item can be placed on the floor, on top of another item (upper), or if another item can be placed on top of it (downer)

**Versions**: , , , , 

## ItemLightColor

**Name**: ItemLightColor

**Hash**: 0xa69385c1

**Hashed string**: ItemLightColor.hshCstringRef

**Versions**: , , , , 

## 0x7dcd5be1

**Hash**: 0x7dcd5be1

**Type**: hshCstringRef

**Notes**: Low', 'High', 'Normal' and 'None'. Similar to ItemHobbyType. Could have a name similar to ItemLifeType?

**Versions**: , , , , 

## ItemMailAttachCategory

**Name**: ItemMailAttachCategory

**Hash**: 0x70e19913

**Hashed string**: ItemMailAttachCategory.hshCstringRef

**Versions**: , , , , 

## ItemMenu

**Name**: ItemMenu

**Hash**: 0x348d7b06

**Hashed string**: ItemMenu.hshCstringRef

**Notes**: What icon is used in inventory. Must be matched to a Label in the ItemMenuIcon table to get the actual ResName (image filename)

**Versions**: , , , , 

## ItemMessageCategory

**Name**: ItemMessageCategory

**Hash**: 0x5032ef59

**Hashed string**: ItemMessageCategory.hshCstringRef

**Notes**: One thing this seems to do is group quest fish/insects. 

**Versions**: , , , , 

## 0x164a5f24

**Hash**: 0x164a5f24

**Type**: hshCstringRef

**Notes**: Villager clothing style preference 1

**Versions**: , , , , 

## 0x9ba040c2

**Hash**: 0x9ba040c2

**Type**: u32/s32

**Notes**: Villager clothing style preference 2

**Versions**: , , , , 

## ItemNpcFtrActionType

**Name**: ItemNpcFtrActionType

**Hash**: 0xaa6a39c6

**Hashed string**: ItemNpcFtrActionType.hshCstringRef

**Notes**: How villagers interact with the furniture

**Versions**: , , , , 

## ItemNpcFtrWatchType

**Name**: ItemNpcFtrWatchType

**Hash**: 0xd9855b4e

**Hashed string**: ItemNpcFtrWatchType.hshCstringRef

**Notes**: The direction of the item that villagers interact from

**Versions**: , , , , 

## ItemNpcReactionGenreType

**Name**: ItemNpcReactionGenreType

**Hash**: 0xa812e496

**Hashed string**: ItemNpcReactionGenreType.hshCstringRef

**Notes**: Used to choose how villagers comment on furniture genres

**Versions**: , , , , 

## ItemNpcReactionThemeType

**Name**: ItemNpcReactionThemeType

**Hash**: 0xeffadab6

**Hashed string**: ItemNpcReactionThemeType.hshCstringRef

**Notes**: Used to choose how villagers comment on furniture themes

**Versions**: , , , , 

## ItemNpcRoomLayoutLimit

**Name**: ItemNpcRoomLayoutLimit

**Hash**: 0xbf80f575

**Hashed string**: ItemNpcRoomLayoutLimit.hshCstringRef

**Notes**: Determines whether villagers can put this on the floor in their house. ('Valid' = can only be placed on surface)

**Versions**: , , , , 

## ItemNpcRoomReplaceCategory

**Name**: ItemNpcRoomReplaceCategory

**Hash**: 0xead62c46

**Hashed string**: ItemNpcRoomReplaceCategory.hshCstringRef

**Notes**: Groups items so only items in the same group can replace default floor furniture in villagers' houses

**Versions**: , , , , 

## ItemOrderSale

**Name**: ItemOrderSale

**Hash**: 0xba4fd546

**Hashed string**: ItemOrderSale.hshCstringRef

**Notes**: Yes' and 'No'. Items that appear in Nook Shopping seem to have 'Yes'

**Versions**: , , , , 

## ItemOutfitInfo

**Name**: ItemOutfitInfo

**Hash**: 0x7724bf93

**Hashed string**: ItemOutfitInfo.hshCstringRef

**Notes**: Categorizes clothes and tools

**Versions**: , , , , 

## ItemPlayerTopsBottomsForm

**Name**: ItemPlayerTopsBottomsForm

**Hash**: 0x9feb9da6

**Hashed string**: ItemPlayerTopsBottomsForm.hshCstringRef

**Versions**: , , , , 

## ItemPriorityPlace

**Name**: ItemPriorityPlace

**Hash**: 0x510f21dc

**Hashed string**: ItemPriorityPlace.hshCstringRef

**Notes**: Determines if the item is recommended for outdoors or indoors. Outdoors items give bonus points for island rating. It's unknown what indoors is used for

**Versions**: , , , , 

## ItemRandomColorGroup

**Name**: ItemRandomColorGroup

**Hash**: 0x5504464e

**Hashed string**: ItemRandomColorGroup.hshCstringRef

**Notes**: Used to keep colors consistent for groups of items which the colors are randomly chosen for your island

**Versions**: , , , , 

## ItemRegionFilter

**Name**: ItemRegionFilter

**Hash**: 0xea9fc92a

**Hashed string**: ItemRegionFilter.hshCstringRef

**Notes**: Determines that celebratory candles aren't suitable for Europe

**Versions**: , , , , 

## ItemSize

**Name**: ItemSize

**Hash**: 0xe06fb090

**Hashed string**: ItemSize.hshCstringRef

**Versions**: , , , , 

## ItemUICategory

**Name**: ItemUICategory

**Hash**: 0x28297660

**Hashed string**: ItemUICategory.hshCstringRef

**Notes**: Item storage categories. "Floor" is housewares, "Upper" is miscellaneous.

**Versions**: , , , , 

## ItemUIFurnitureCategory

**Name**: ItemUIFurnitureCategory

**Hash**: 0x8221388c

**Hashed string**: ItemUIFurnitureCategory.hshCstringRef

**Notes**: How items are sorted in each storage category for "Sort: Type"

**Versions**: , , , , 

## ItemUnitIcon

**Name**: ItemUnitIcon

**Hash**: 0x010d74a6

**Hashed string**: ItemUnitIcon.hshCstringRef

**Notes**: Icon used for dropped items

**Versions**: , , , , 

## LampType

**Name**: LampType

**Hash**: 0xd65f862b

**Hashed string**: LampType.hshCstringRef

**Notes**: type of light emission, like "Candle" or "FluorLamp"

**Versions**: , , , , 

## LocalWindType

**Name**: LocalWindType

**Hash**: 0x9a3fb47c

**Hashed string**: LocalWindType.hshCstringRef

**Notes**: For objects that create wind effects, like fans

**Versions**: , , , , 

## NpcFtrWatchPos

**Name**: NpcFtrWatchPos

**Hash**: 0x85c63b71

**Hashed string**: NpcFtrWatchPos f32

**Versions**: , , , , 

## NpcGender

**Name**: NpcGender

**Hash**: 0x8392798c

**Hashed string**: NpcGender.hshCstringRef

**Versions**: , , , , 

## NpcOutfit

**Name**: NpcOutfit

**Hash**: 0x60c99a5e

**Hashed string**: NpcOutfit.hshCstringRef

**Notes**: Positions the villagers wear caps and glasses

**Versions**: , , , , 

## OutfitSE

**Name**: OutfitSE

**Hash**: 0x041c3234

**Hashed string**: OutfitSE.hshCstringRef

**Notes**: Presumably outfit sound effect. Currently 'None' for every item

**Versions**: , , , , 

## Price

**Name**: Price

**Hash**: 0x718b024d

**Hashed string**: Price s32

**Notes**: The amount of bells the item is bought for. Divide by 4 to get sale price at Nook's Cranny. All items have prices but not all of them can be bought with bells

**Versions**: , , , , 

## RideHeight

**Name**: RideHeight

**Hash**: 0xb662662c

**Hashed string**: RideHeight f32

**Versions**: , , , , 

## Seasonality

**Name**: Seasonality

**Hash**: 0x0e6ca0d4

**Hashed string**: Seasonality.hshCstringRef

**Notes**: Seems to set seasonal "appropriateness", but not restrictions on whether those items are available

**Versions**: , , , , 

## WallPlaceType

**Name**: WallPlaceType

**Hash**: 0xe1bf0894

**Hashed string**: WallPlaceType.hshCstringRef

**Versions**: , , , , 

## BridgeTypeId

**Name**: BridgeTypeId

**Hash**: 0x5c1c3044

**Hashed string**: BridgeTypeId u16

**Notes**: Matches to UniqueID in StructureBridgeTypeParam

**Versions**: , , , , 

## ColorGroupSortId

**Name**: ColorGroupSortId

**Hash**: 0x02169dc7

**Hashed string**: ColorGroupSortId u16

**Notes**: All items with values above 0 (from 1 to 8) seem to be clothing. But some clothing items are 0 too

**Versions**: , , , , 

## CookingRecipeID

**Name**: CookingRecipeID

**Hash**: 0xc353ef20

**Hashed string**: CookingRecipeID u16

**Notes**: Yum

**Versions**: , , , , 

## DiyRecipeID

**Name**: DiyRecipeID

**Hash**: 0xbcf5d17a

**Hashed string**: DiyRecipeID s16

**Notes**: Matches to UniqueID in RecipeCraftParam, so links a crafted object back to its DIY recipe

**Versions**: , , , , 

## FakeArtConvertId

**Name**: FakeArtConvertId

**Hash**: 0xbee071da

**Hashed string**: FakeArtConvertId u16

**Notes**: Matches UniqueIDs of fake art to real art and vice versa

**Versions**: , , , , 

## FloorTableId

**Name**: FloorTableId

**Hash**: 0xc833b068

**Hashed string**: FloorTableId u16

**Notes**: Matches to UniqueID in RoomFloorParam

**Versions**: , , , , 

## 0x9ec34ed4

**Hash**: 0x9ec34ed4

**Type**: u16/s16

**Versions**: , , , , 

## ItemShareTextureUniqueID

**Name**: ItemShareTextureUniqueID

**Hash**: 0x9bd046a2

**Hashed string**: ItemShareTextureUniqueID u16

**Notes**: Used for insects and their toy versions, presumably as a common identifier to reference shared textures

**Versions**: , , , , 

## RemakeID

**Name**: RemakeID

**Hash**: 0xcb5eb33f

**Hashed string**: RemakeID s16

**Notes**: Matches to UniqueID in ItemRemake

**Versions**: , , , , 

## SewingRecipeID

**Name**: SewingRecipeID

**Hash**: 0x88a6501c

**Hashed string**: SewingRecipeID s16

**Versions**: , , , , 

## SlopeTableId

**Name**: SlopeTableId

**Hash**: 0xbfba247c

**Hashed string**: SlopeTableId u16

**Notes**: Matches to UniqueID in StructureSlopeParam

**Versions**: , , , , 

## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: , , , , 

## WallTableId

**Name**: WallTableId

**Hash**: 0x0f9f6747

**Hashed string**: WallTableId u16

**Notes**: Matches to UniqueID in RoomWallParam

**Versions**: , , , , 

## AITagBitRankA

**Name**: AITagBitRankA

**Hash**: 0xe8c448b2

**Hashed string**: AITagBitRankA u8

**Notes**: Bit field that groups clothes for villagers to equip in certain situations. See link below for more information: https://docs.google.com/spreadsheets/d/1Hg9RM8t-wfJWBOhRyqQAbsQN-gv_qLLA2JalqNE-B2U/edit?usp=sharing

**Versions**: , , , , 

## AITagBitRankB

**Name**: AITagBitRankB

**Hash**: 0xfa71e75c

**Hashed string**: AITagBitRankB u8

**Notes**: Bit field that groups clothes for villagers to equip in certain situations

**Versions**: , , , , 

## AITagBitRankC

**Name**: AITagBitRankC

**Hash**: 0x42cd8039

**Hashed string**: AITagBitRankC u8

**Notes**: Unused bit field that groups clothes for villagers to equip in certain situations

**Versions**: , , , , 

## AITagBitRankS

**Name**: AITagBitRankS

**Hash**: 0x12d4d7a6

**Hashed string**: AITagBitRankS u8

**Notes**: Bit field that groups clothes for villagers to equip in certain situations

**Versions**: , , , , 

## CanNotLookFace

**Name**: CanNotLookFace

**Hash**: 0xfd415a4c

**Hashed string**: CanNotLookFace u8

**Notes**: Prevents villagers from seeing your wasp-stung face

**Versions**: , , , , 

## CaptureClosetIcon

**Name**: CaptureClosetIcon

**Hash**: 0xe4697080

**Hashed string**: CaptureClosetIcon u8

**Notes**: Used for generating wardrobe icons. No effect on gameplay

**Versions**: , , , , 

## CaptureDiyIcon

**Name**: CaptureDiyIcon

**Hash**: 0xe24d9b0e

**Hashed string**: CaptureDiyIcon u8

**Notes**: Used for generating recipe icons. No effect on gameplay

**Versions**: , , , , 

## 0xf179f796

**Hash**: 0xf179f796

**Type**: u8/s8

**Notes**: Used for determining interaction state when generating icons. No effect on gameplay

**Versions**: , , , , 

## CaptureFtrIcon

**Name**: CaptureFtrIcon

**Hash**: 0xe65df243

**Hashed string**: CaptureFtrIcon u8

**Notes**: Used for generating storage icons. No effect on gameplay

**Versions**: , , , , 

## CaptureGardeningIcon

**Name**: CaptureGardeningIcon

**Hash**: 0x116f007f

**Hashed string**: CaptureGardeningIcon u8

**Notes**: Used for generating gardening??? icons. Maybe Leif shop icons. No effect on gameplay

**Versions**: 

## CapturePreset

**Name**: CapturePreset

**Hash**: 0xfc275e86

**Hashed string**: CapturePreset string32

**Notes**: Used for generating icons. No effect on gameplay

**Versions**: , , , , 

## DefaultSwitch

**Name**: DefaultSwitch

**Hash**: 0xd862189a

**Hashed string**: DefaultSwitch u8

**Notes**: Likely default on/off state

**Versions**: , , , , 

## FrontSwitch

**Name**: FrontSwitch

**Hash**: 0x147e658d

**Hashed string**: FrontSwitch u8

**Notes**: Whether it can only be turned on/off from the front

**Versions**: , , , , 

## HasJmp

**Name**: HasJmp

**Hash**: 0xa4db9685

**Hashed string**: HasJmp u8

**Notes**: Includes all rugs with .pbc files (collision files?)

**Versions**: , , , , 

## 0x4b97cdab

**Hash**: 0x4b97cdab

**Type**: u8/s8

**Versions**: , , , , 

## IsSwingFtr

**Name**: IsSwingFtr

**Hash**: 0xbea3e8b8

**Hashed string**: IsSwingFtr u8

**Notes**: If the items have wind animations

**Versions**: , , , , 

## ItemHHADirection

**Name**: ItemHHADirection

**Hash**: 0x3cda3274

**Hashed string**: ItemHHADirection u8

**Notes**: 1 = can get HHA penalty for facing walls

**Versions**: , , , , 

## ItemName

**Name**: ItemName

**Hash**: 0xb8cc232c

**Hashed string**: ItemName string64

**Notes**: Japanese item name?

**Versions**: , , , , 

## ItemReleaseVersion

**Name**: ItemReleaseVersion

**Hash**: 0x805cdabb

**Hashed string**: ItemReleaseVersion u8

**Notes**: Version the item was added. Matches to row index (not UniqueID!) in ReleaseVersionParam

**Versions**: , , , , 

## Label

**Name**: Label

**Hash**: 0x3febc642

**Hashed string**: Label string50

**Versions**: , , , , 

## NpcDefaultSwitch

**Name**: NpcDefaultSwitch

**Hash**: 0xdeb3f8dc

**Hashed string**: NpcDefaultSwitch u8

**Notes**: Default on/off state when placed in villagers' houses

**Versions**: , , , , 

## ResName

**Name**: ResName

**Hash**: 0x48ef0398

**Hashed string**: ResName string64

**Notes**: Model name

**Versions**: , , , , 

## RumbleForEdit

**Name**: RumbleForEdit

**Hash**: 0x86efa036

**Hashed string**: RumbleForEdit u8

**Versions**: , , , , 

## 0xb5677509

**Hash**: 0xb5677509

**Type**: u8/s8

**Versions**: 

## ToiletType

**Name**: ToiletType

**Hash**: 0x0eb7fa40

**Hashed string**: ToiletType u8

**Notes**: Usable toilets are set to 1

**Versions**: , , 

## TouchRumble

**Name**: TouchRumble

**Hash**: 0x7404ebb3

**Hashed string**: TouchRumble u8

**Versions**: , , , , 

## ValidEffect

**Name**: ValidEffect

**Hash**: 0x49cc96d0

**Hashed string**: ValidEffect u8

**Versions**: , , , , 

