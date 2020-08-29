# MysteryTourParam
**Named columns**: 11/16

**Documented columns**: 12/16

**Description**: Main params for Mystery Tours (NMT islands)
## ItemPlacementKind

**Name**: ItemPlacementKind

**Hash**: 0xdd59b554

**Hashed string**: ItemPlacementKind.hshCstringRef

**Notes**: Specificity of the mystery island environment, either "Normal", "StoneMaterial", "StoneCoin", "Bamboo", "TreeSisterFruit" or "StoneGold"

**Versions**: , , , , 

## TourType

**Name**: TourType

**Hash**: 0x1c8d9dbc

**Hashed string**: TourType.hshCstringRef

**Notes**: Whether it's a "Normal" mystery island or the "MayDay" island

**Versions**: , , 

## FishPattern

**Name**: FishPattern

**Hash**: 0xb1f384dc

**Hashed string**: FishPattern s16

**Notes**: UniqueID of MysteryTourFishParam for special fish spawn like on "Big Fish Island" or on "Fin Island"

**Versions**: , , , , 

## InsectPattern

**Name**: InsectPattern

**Hash**: 0xe23c6453

**Hashed string**: InsectPattern s16

**Notes**: UniqueID of MysteryTourInsectParam for special bug spawn.

**Versions**: , , , , 

## MustItem0

**Name**: MustItem0

**Hash**: 0xbc5f2a7b

**Hashed string**: MustItem0 u16

**Notes**: Required Item to access the island, either -2 (no items required), the id of the vaulting pole or the id of the ladder.

**Versions**: , , , , 

## MustItem1

**Name**: MustItem1

**Hash**: 0x813f03cb

**Hashed string**: MustItem1 u16

**Notes**: Required Item to access the island, either -2 (no items required), the id of the vaulting pole or the id of the ladder.

**Versions**: , , , , 

## MysteryTourFieldUniqueID

**Name**: MysteryTourFieldUniqueID

**Hash**: 0x72573f73

**Hashed string**: MysteryTourFieldUniqueID u16

**Notes**: UniqueID of MysteryTourFieldParam for river generation.

**Versions**: , , , , 

## MysteryTourItemUniqueID

**Name**: MysteryTourItemUniqueID

**Hash**: 0x7a09986c

**Hashed string**: MysteryTourItemUniqueID u16

**Notes**: UniqueID of MysteryTourItemParam.

**Versions**: , , , , 

## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: , , , , 

## 0x7215b154

**Hash**: 0x7215b154

**Type**: string32

**Notes**: "BuiltTownOffice" if having the Resident Service built is required to access the island.

**Versions**: , , , , 

## 0x88bd09c2

**Hash**: 0x88bd09c2

**Type**: string32

**Notes**: Flag for island that can only be accessed once a day, presumably one to check and one to change the value of the flag?

**Versions**: , , , , 

## 0x4e5cd9f3

**Hash**: 0x4e5cd9f3

**Type**: string32

**Notes**: Same as above

**Versions**: , , , , 

## 0x8f2f4bf9

**Hash**: 0x8f2f4bf9

**Type**: string32

**Notes**: Only accessible if WiIlbur explained how mystery islands work.

**Versions**: , , , , 

## 0x0b3d1d54

**Hash**: 0x0b3d1d54

**Type**: string32

**Notes**: Checks if the EnableGotoRareMysteryTour flag has been activated.

**Versions**: , 

## SelectWeight

**Name**: SelectWeight

**Hash**: 0xd89a0db0

**Hashed string**: SelectWeight u8

**Notes**: Weight of the island selection when the game gets a random one. The games generate a number between 0 and 999. If said number is superior to the sum of all island weight available, it will pick randomly between the starter islands (UniqueID 0, 1, 2 and 4).

**Versions**: , , , , 

## StatusPattern

**Name**: StatusPattern

**Hash**: 0xb1589411

**Hashed string**: StatusPattern u8

**Versions**: , 

