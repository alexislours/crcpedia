# FishStatusParam
[View this table in your browser](FishStatusParam-value.md) (version 1.4.0).

**Named columns**: 17/19

**Documented columns**: 15/19

**Description**: Fish parameters
## AppearArea

**Name**: AppearArea

**Hash**: 0x64330cb0

**Hashed string**: AppearArea.hshCstringRef

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## AppearType

**Name**: AppearType

**Hash**: 0x0de2a3be

**Hashed string**: AppearType.hshCstringRef

**Notes**: "Anywhere", "BrackishWater" (river mouth), "Pond", "River", "RiverCliffTop", "Sea", "SeaBeachBridge" (pier)

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## BuoyLv

**Name**: BuoyLv

**Hash**: 0x770288fd

**Hashed string**: BuoyLv.hshCstringRef

**Notes**: Catch difficulty. Fish with lower values are harder to catch, with more erratic movements and narrower timing window

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## EscapeScale

**Name**: EscapeScale

**Hash**: 0xb7c9dd05

**Hashed string**: EscapeScale f32

**Notes**: doesn't appear to be used in the main binary

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## FishMuseumAction

**Name**: FishMuseumAction

**Hash**: 0x132dd5b9

**Hashed string**: FishMuseumAction.hshCstringRef

**Notes**: How fish behave in the museum

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x4108715d

**Hash**: 0x4108715d

**Type**: f32

**Notes**: Seems museum-related, some kind of angle

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SearchRadius

**Name**: SearchRadius

**Hash**: 0x7ec9ada7

**Hashed string**: SearchRadius.hshCstringRef

**Notes**: Vision cone. Fish with higher values will turn to face the bobber more easily

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ShadowType

**Name**: ShadowType

**Hash**: 0xac0ebe24

**Hashed string**: ShadowType.hshCstringRef

**Notes**: Yep, shadow type. Also determines strength and vibration level when reeling in. Interesting example: "J" shadows (sharks) look exactly the same as "K" shadows (suckerfish), but feel heavier

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ItemID

**Name**: ItemID

**Hash**: 0x20cb67bc

**Hashed string**: ItemID u16

**Notes**: Matches ItemParam UniqueID and STR_ItemName ids

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## OpenDonatedNum

**Name**: OpenDonatedNum

**Hash**: 0xeac6a012

**Hashed string**: OpenDonatedNum u16

**Notes**: Total lifetime fish catches required to unlock this one. Can be checked with the "Angling for Perfection!" Nook Miles achievement

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ToyItemID

**Name**: ToyItemID

**Hash**: 0xdaaf8ba0

**Hashed string**: ToyItemID u16

**Notes**: ItemParam ID for the corresponding fish model object

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


## DebugName

**Name**: DebugName

**Hash**: 0xab51a3cf

**Hashed string**: DebugName string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## IsCreateBait

**Name**: IsCreateBait

**Hash**: 0x3dc49bc2

**Hashed string**: IsCreateBait u8

**Notes**: Whether or not bait can be used to spawn this fish

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## IsSidewaysShow

**Name**: IsSidewaysShow

**Hash**: 0x0e91fc27

**Hashed string**: IsSidewaysShow u8

**Notes**: Denotes bigger fish that require a special "Show off" animation. Previously thought to be for rain/snow boost in spawn rates

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Label

**Name**: Label

**Hash**: 0x87bf00e8

**Hashed string**: Label string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x1f875d3d

**Hash**: 0x1f875d3d

**Type**: string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResName

**Name**: ResName

**Hash**: 0x48ef0398

**Hashed string**: ResName string64

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResNameMuseum

**Name**: ResNameMuseum

**Hash**: 0x1c8856db

**Hashed string**: ResNameMuseum string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


