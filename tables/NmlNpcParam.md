# NmlNpcParam
[View this table in your browser](NmlNpcParam-value.md) (version 1.4.0).

**Named columns**: 31/39

**Documented columns**: 26/39

**Description**: Main params for villager NPCs
## 0xa54f92fd

**Hash**: 0xa54f92fd

**Type**: u32/s32

**Notes**: AITag row index counts as preferred clothes. 4 = China, 9 = None, 10 = Japanese.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0xe2efe82d

**Hash**: 0xe2efe82d

**Type**: u32/s32

**Notes**: AITag row index counts as preferred clothes. All 9 (None).

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x5ef86f1f

**Hash**: 0x5ef86f1f

**Type**: u32/s32

**Notes**: preferred style 1

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x195815cf

**Hash**: 0x195815cf

**Type**: u32/s32

**Notes**: preferred style 2

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0xbea84522

**Hash**: 0xbea84522

**Type**: hshCstringRef

**Notes**: "Normal", "Prefer", and "Avoid"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Hobby

**Name**: Hobby

**Hash**: 0x9eea1288

**Hashed string**: Hobby.hshCstringRef

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## NpcLooks

**Name**: NpcLooks

**Hash**: 0x04f52f6a

**Hashed string**: NpcLooks.hshCstringRef

**Notes**: Personality

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Social

**Name**: Social

**Hash**: 0xaa4403ea

**Hashed string**: Social.hshCstringRef

**Notes**: Affects wave type and ability to respond to reactions. Probably more that this does?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## VmPauseType

**Name**: VmPauseType

**Hash**: 0x0e7ab6a6

**Hashed string**: VmPauseType.hshCstringRef

**Notes**: Related to pauses/length of the notes in villagers' melodies?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## VmRhythmType

**Name**: VmRhythmType

**Hash**: 0xdd2d2adc

**Hashed string**: VmRhythmType.hshCstringRef

**Notes**: Village melody rhythm. 'Normal' = normal, 'Shuffle' = swing rhythm, 'Random' = notes have random length

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## AccentWall

**Name**: AccentWall

**Hash**: 0x08238405

**Hashed string**: AccentWall u16

**Notes**: All 0s (My personal theory is that AccentWall is used for 1 wall that's different from the other 3 in the room. Unused by the game)

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## BromideItemID

**Name**: BromideItemID

**Hash**: 0x71bf253b

**Hashed string**: BromideItemID s16

**Notes**: Villager's photo ID

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## FloorType

**Name**: FloorType

**Hash**: 0x0b52f5bb

**Hashed string**: FloorType u16

**Notes**: Only 0 and 54

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## PosterItemID

**Name**: PosterItemID

**Hash**: 0x0f640691

**Hashed string**: PosterItemID s16

**Notes**: Villager's poster ID

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## RainHat

**Name**: RainHat

**Hash**: 0x03200971

**Hashed string**: RainHat u16

**Notes**: Default hat worn in the rain

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## RainWare

**Name**: RainWare

**Hash**: 0x1d69405f

**Hashed string**: RainWare u16

**Notes**: Default top worn in the rain

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SmartphoneRemakeCommonPattern

**Name**: SmartphoneRemakeCommonPattern

**Hash**: 0x57e889b2

**Hashed string**: SmartphoneRemakeCommonPattern s16

**Notes**: Which Sable pattern ID is used for their phone

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SmartphoneRemakePattern

**Name**: SmartphoneRemakePattern

**Hash**: 0xf8be7f94

**Hashed string**: SmartphoneRemakePattern u16

**Notes**: Which phone remake pattern is used for their phone (only used when SmartphoneRemakeCommonPattern is -1?)

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Tops

**Name**: Tops

**Hash**: 0x870f1e29

**Hashed string**: Tops u16

**Notes**: Default top

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Umbrella

**Name**: Umbrella

**Hash**: 0xbb9c816e

**Hashed string**: Umbrella u16

**Notes**: Default umbrella

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WallType

**Name**: WallType

**Hash**: 0xda63a0cc

**Hashed string**: WallType u16

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## BirthMDay

**Name**: BirthMDay

**Hash**: 0x919ea52a

**Hashed string**: BirthMDay u8

**Notes**: Birthday date

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## BirthMonth

**Name**: BirthMonth

**Hash**: 0x9456b6a3

**Hashed string**: BirthMonth u8

**Notes**: Birthday month

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Color1

**Name**: Color1

**Hash**: 0x34eb5dc3

**Hashed string**: Color1 u8

**Notes**: Preferred color 1

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Color2

**Name**: Color2

**Hash**: 0x265ef22d

**Hashed string**: Color2 u8

**Notes**: Preferred color 2

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## HavokResName

**Name**: HavokResName

**Hash**: 0x4ce98793

**Hashed string**: HavokResName string64

**Notes**: Ressource name for the havok file for clothes animations.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## HelperBoneResName

**Name**: HelperBoneResName

**Hash**: 0xc1fb0035

**Hashed string**: HelperBoneResName string64

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## InitLive

**Name**: InitLive

**Hash**: 0x454b2adc

**Hashed string**: InitLive u8

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## InitRemakeId

**Name**: InitRemakeId

**Hash**: 0x566f1d31

**Hashed string**: InitRemakeId u8

**Notes**: Chooses the remake body of the furniture in the 2 starting villagers' houses

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Label

**Name**: Label

**Hash**: 0x2f1b930d

**Hashed string**: Label string8

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## NpcColor

**Name**: NpcColor

**Hash**: 0x41977699

**Hashed string**: NpcColor u8

**Notes**: Determines the color of the bubble and text surrounding their name while you talk to them. The value is the index of the array in the NpcColor BYML in the Pack folder (stored as an rgb float array).

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## NpcTalkType

**Name**: NpcTalkType

**Hash**: 0x33af13e1

**Hashed string**: NpcTalkType u8

**Notes**: Personality subtype. Used to choose between FreeA_AlwaysA and FreeA_AlwaysB dialogue

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResName

**Name**: ResName

**Hash**: 0x48ef0398

**Hashed string**: ResName string64

**Notes**: Villager model file name

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SpecialELink

**Name**: SpecialELink

**Hash**: 0x04ac1bea

**Hashed string**: SpecialELink u8

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SpecialSLink

**Name**: SpecialSLink

**Hash**: 0xbe782346

**Hashed string**: SpecialSLink u8

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x21c5bbd6

**Hash**: 0x21c5bbd6

**Type**: u8/s8

**Notes**: Village melody note length, lower values have shorter notes. Name probably starts with "Vm"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0xe52f0037

**Hash**: 0xe52f0037

**Type**: u8/s8

**Notes**: Related to village melody. 1, 2, 3, 6, 8, 10, 12, 14, and 18

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x42f255d5

**Hash**: 0x42f255d5

**Type**: u8/s8

**Notes**: Related to village melody. 1 through 6

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


