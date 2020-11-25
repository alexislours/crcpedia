# RoomFloorParam
[View this table in your browser](RoomFloorParam-value.md) (version 1.6.0).

**Named columns**: 14/14

**Documented columns**: 8/14

**Description**: Floor params
## Act

**Name**: Act

**Hash**: 0xf74f3d2c

**Hashed string**: Act.hshCstringRef

**Notes**: If this is similar to RoomWallParam's Act column, then something about special floors? But the only value in this column is "None"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Price

**Name**: Price

**Hash**: 0x718b024d

**Hashed string**: Price s32

**Notes**: 888 all the way down

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Scale

**Name**: Scale

**Hash**: 0x49295020

**Hashed string**: Scale.hshCstringRef

**Notes**: Whether or not the floor scales to the room size/shape. Values are "Scale" & "None"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Scale10x6

**Name**: Scale10x6

**Hash**: 0xb117eb21

**Hashed string**: Scale10x6.hshCstringRef

**Notes**: Controls special floor scaling behavior for rectangular rooms. Values are "Scale" & "None"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Floorboards

**Name**: Floorboards

**Hash**: 0xab771eae

**Hashed string**: Floorboards u16

**Notes**: Looks like a UniqueID from another table - maybe floor noises?? Potentially matches up with CarpetMaterial in ItemParam

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## ItemTableId

**Name**: ItemTableId

**Hash**: 0x58aff4fb

**Hashed string**: ItemTableId u16

**Notes**: Haven't double-checked but 90% sure this joins on the UniqueID in ItemParam

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes* | Yes* | Yes* | Yes* | Yes* | Yes*| 

*Found in the BCSVs but unreferenced in the executable

## LandingUniqueID

**Name**: LandingUniqueID

**Hash**: 0x8fced711

**Hashed string**: LandingUniqueID u16

**Notes**: Joins on UniqueID in RoomLandingParam

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## HasJmp

**Name**: HasJmp

**Hash**: 0xa4db9685

**Hashed string**: HasJmp u8

**Notes**: boolean flag, 1 vs 0; mostly set on special floors?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Horizon

**Name**: Horizon

**Hash**: 0x3543c34a

**Hashed string**: Horizon u8

**Notes**: boolean flag, 1 vs 0

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## ItemName

**Name**: ItemName

**Hash**: 0xb8cc232c

**Hashed string**: ItemName string64

**Notes**: Japanese string

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | Yes* | Yes*| 

*Found in the BCSVs but unreferenced in the executable

## ResourceName

**Name**: ResourceName

**Hash**: 0x4b9c4229

**Hashed string**: ResourceName string64

**Notes**: Name of resource in Romfs; example, "RoomTexFloorBasement00"

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


## Reverberation (Unused)

**Name**: Reverberation

**Hash**: 0x05836619

**Hashed string**: Reverberation s8

**Notes**: Removed in 1.3.0

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | No | No | No | No| 

*Found in the BCSVs but unreferenced in the executable

## Rotatable

**Name**: Rotatable

**Hash**: 0x8ed948dd

**Hashed string**: Rotatable u8

**Notes**: boolean flag, 1 vs 0 -- whether or not the floor can be rotated horizontal/vertical

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | Yes| 


