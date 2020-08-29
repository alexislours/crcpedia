# FgMainParam
**Named columns**: 22/23

**Documented columns**: 17/23

**Description**: Parameters for outdoor objects, such as trees
## CollisionHeight

**Name**: CollisionHeight

**Hash**: 0x0c315945

**Hashed string**: CollisionHeight f32

**Notes**: Collision height of the model, 0 if no collision

**Versions**: , , , , 

## InsectParam

**Name**: InsectParam

**Hash**: 0x360b721a

**Hashed string**: InsectParam.hshCstringRef

**Notes**: the counterpart for InsectStatusParam's AppearFg

**Versions**: , , , , 

## Kind

**Name**: Kind

**Hash**: 0x9b7aa0a0

**Hashed string**: Kind.hshCstringRef

**Notes**: the type of object the row is (e.g. fruit tree, cedar stump, rose, etc.), and is used a lot when the specific object doesn't matter (e.g. "all fences" or "all fruit trees")

**Versions**: , , , , 

## PicIconHeight

**Name**: PicIconHeight

**Hash**: 0x123efcf1

**Hashed string**: PicIconHeight f32

**Notes**: Always 0

**Versions**: , , , , 

## BuryItem

**Name**: BuryItem

**Hash**: 0x6ac5a6df

**Hashed string**: BuryItem u16

**Notes**: Item burried

**Versions**: , , , , 

## BuryItem2

**Name**: BuryItem2

**Hash**: 0xd59ff85e

**Hashed string**: BuryItem2 u16

**Notes**: Item burried

**Versions**: , , , , 

## BuryItem3

**Name**: BuryItem3

**Hash**: 0xe8ffd1ee

**Hashed string**: BuryItem3 u16

**Notes**: Item burried

**Versions**: , , , , 

## ChangeFg

**Name**: ChangeFg

**Hash**: 0x76e7fe08

**Hashed string**: ChangeFg u16

**Notes**: varies depending on the item, but is loosely "what item id does this item become if something happens to it" (trees -> stumps (axed), flower blooms -> stems (picked), flowering bushes -> flowerless bushes (out of season))

**Versions**: , , , , 

## DigItem

**Name**: DigItem

**Hash**: 0xf4678f13

**Hashed string**: DigItem u16

**Notes**: Item returned when digging

**Versions**: , , , , 

## EffectAttribute

**Name**: EffectAttribute

**Hash**: 0x6ab4b6fb

**Hashed string**: EffectAttribute u16

**Notes**: Always 0

**Versions**: , , , , 

## GrowupFg

**Name**: GrowupFg

**Hash**: 0x2c6a189e

**Hashed string**: GrowupFg u16

**Notes**: Item ID that the item in FgMainParam grows up into, i.e. sapling → tree stage 1, red cosmos stems → red cosmos buds, etc. its value is a bit weird for bushes because bushes have a slightly different path in code to handle whether they're in season or not

**Versions**: , , , , 

## NutItem

**Name**: NutItem

**Hash**: 0xbe17c845

**Hashed string**: NutItem u16

**Notes**: Fruit falling from the object

**Versions**: , , , , 

## PicItem

**Name**: PicItem

**Hash**: 0xb7a46956

**Hashed string**: PicItem u16

**Notes**: Item returned when picking up

**Versions**: , , , , 

## SoundAttribute

**Name**: SoundAttribute

**Hash**: 0x2e17a0a7

**Hashed string**: SoundAttribute u16

**Notes**: Always 0

**Versions**: , , , , 

## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: , , , , 

## ColorIndex

**Name**: ColorIndex

**Hash**: 0x64b8fff8

**Hashed string**: ColorIndex s8

**Versions**: , , , , 

## DebugName

**Name**: DebugName

**Hash**: 0x3f45f2bf

**Hashed string**: DebugName string64

**Versions**: , , , , 

## Grow

**Name**: Grow

**Hash**: 0xf5a73337

**Hashed string**: Grow u8

**Notes**: growth stage, a bit weird for bushes

**Versions**: , , , , 

## Label

**Name**: Label

**Hash**: 0x87bf00e8

**Hashed string**: Label string32

**Versions**: , , , , 

## ModelName

**Name**: ModelName

**Hash**: 0x39b5a93d

**Hashed string**: ModelName string32

**Notes**: 3D model file name

**Versions**: , , , , 

## Nature

**Name**: Nature

**Hash**: 0x623dc307

**Hashed string**: Nature u8

**Notes**: bitfield

**Versions**: , , , , 

## 0xa4b2d66d

**Hash**: 0xa4b2d66d

**Type**: u8/s8

**Notes**: bitfield

**Versions**: , , , , 

## ResName

**Name**: ResName

**Hash**: 0x48ef0398

**Hashed string**: ResName string64

**Versions**: , , , , 

