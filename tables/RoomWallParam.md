# RoomWallParam
**Named columns**: 15/15

**Documented columns**: 10/15

**Description**: Wall params
## AO

**Name**: AO

**Hash**: 0x8a377042

**Hashed string**: AO.hshCstringRef

**Notes**: Possibly related to Ambient Occlusion? Values are "UseAO" and "None".

**Versions**: , , , , 

## Act

**Name**: Act

**Hash**: 0xf74f3d2c

**Hashed string**: Act.hshCstringRef

**Notes**: Related to special effect wallpapers' styles. Values are "Random", "Synchro", "LightOff", and "None" - for example, the Skull Wallpaper has a glow-in-the-dark pattern & is set as "LightOff" in this field

**Versions**: , , , , 

## Light

**Name**: Light

**Hash**: 0x85ed8743

**Hashed string**: Light.hshCstringRef

**Notes**: Possibly related to lighting color ... ? Values are "Orange" and "White"

**Versions**: , , , , 

## Price

**Name**: Price

**Hash**: 0x718b024d

**Hashed string**: Price s32

**Notes**: ??? Only value is "888"

**Versions**: , , , , 

## ArchUniqueID

**Name**: ArchUniqueID

**Hash**: 0x499e42f9

**Hashed string**: ArchUniqueID u16

**Notes**: Joins on the UniqueID field in RoomArchParam

**Versions**: , , , , 

## CeilingUniqueID

**Name**: CeilingUniqueID

**Hash**: 0x947875dd

**Hashed string**: CeilingUniqueID u16

**Notes**: Joins on the UniqueID field in RoomCeilingParam

**Versions**: , , , , 

## CurtainTexUniqueID

**Name**: CurtainTexUniqueID

**Hash**: 0xaa9bfc6e

**Hashed string**: CurtainTexUniqueID u16

**Notes**: Joins on the UniqueID field in RoomCurtainTexParam

**Versions**: , , , , 

## CurtainUniqueID

**Name**: CurtainUniqueID

**Hash**: 0xa0e569dc

**Hashed string**: CurtainUniqueID u16

**Notes**: Joins on the UniqueID field in RoomCurtainParam

**Versions**: , , , , 

## ItemTableId

**Name**: ItemTableId

**Hash**: 0x58aff4fb

**Hashed string**: ItemTableId u16

**Notes**: Haven't double-checked but I'm 90% sure this joins on the UniqueID in ItemParam

**Versions**: , , , , 

## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: , , , , 

## WindowUniqueID

**Name**: WindowUniqueID

**Hash**: 0xe3a28616

**Hashed string**: WindowUniqueID u16

**Notes**: Joins on the UniqueID field in RoomWindowParam

**Versions**: , , , , 

## ItemName

**Name**: ItemName

**Hash**: 0xb8cc232c

**Hashed string**: ItemName string64

**Notes**: self-explanatory name; japanese string

**Versions**: , , , , 

## ResourceName

**Name**: ResourceName

**Hash**: 0x4b9c4229

**Hashed string**: ResourceName string64

**Notes**: I believe this is the prefix / filename for the model in Romfs; for example, "RoomTexWallCommon00"

**Versions**: , , , , 

## Reverberation (Unused)

**Name**: Reverberation

**Hash**: 0x05836619

**Hashed string**: Reverberation s8

**Notes**: Removed in 1.3.0

**Versions**: , , 

## TextureWindow

**Name**: TextureWindow

**Hash**: 0x318ebbf2

**Hashed string**: TextureWindow u8

**Notes**: Boolean, 1 or 0. Only about 8 or so walls are tagged 1 - unsure how they're related

**Versions**: , , , , 

