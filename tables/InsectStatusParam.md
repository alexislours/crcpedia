# InsectStatusParam
**Named columns**: 16/16

**Documented columns**: 12/16

**Description**: Insect parameters
## AppearArea

**Name**: AppearArea

**Hash**: 0x64330cb0

**Hashed string**: AppearArea.hshCstringRef

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## AppearWeather

**Name**: AppearWeather

**Hash**: 0xa103c985

**Hashed string**: AppearWeather.hshCstringRef

**Notes**: Controls appearance restrictions depending on weather

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## GetScale

**Name**: GetScale

**Hash**: 0x27450132

**Hashed string**: GetScale f32

**Notes**: Might modify model scale when caught? Doesn't appear to be used in the main binary

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Kind

**Name**: Kind

**Hash**: 0x9b7aa0a0

**Hashed string**: Kind.hshCstringRef

**Notes**: Groups bugs based on spawn type

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WaitScale

**Name**: WaitScale

**Hash**: 0xda0b5c29

**Hashed string**: WaitScale f32

**Notes**: Might modify model scale when in the wild?

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ItemID

**Name**: ItemID

**Hash**: 0x20cb67bc

**Hashed string**: ItemID u16

**Notes**: Matches ItemParam UniqueID and STR_ItemName ids

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## OpenAchievementCount

**Name**: OpenAchievementCount

**Hash**: 0x5d4ef312

**Hashed string**: OpenAchievementCount u16

**Notes**: Total lifetime insect catches required to unlock this one. Can be checked with the "You've Got the Bug" Nook Miles achievement

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ToyItemID

**Name**: ToyItemID

**Hash**: 0xdaaf8ba0

**Hashed string**: ToyItemID u16

**Notes**: ItemParam ID for the corresponding fish model object

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## AppearFg

**Name**: AppearFg

**Hash**: 0xbace6554

**Hashed string**: AppearFg u8

**Notes**: bitfield; for insects whose spawn conditions relate to Fg objects ("nature" objects like flowers or rocks), sets those objects and specific restrictions, like type of tree or flower colors

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## DebugName

**Name**: DebugName

**Hash**: 0x3f45f2bf

**Hashed string**: DebugName string64

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Label

**Name**: Label

**Hash**: 0x87bf00e8

**Hashed string**: Label string32

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## Property

**Name**: Property

**Hash**: 0x0909f3d4

**Hashed string**: Property u8

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResNameField

**Name**: ResNameField

**Hash**: 0x11b0b143

**Hashed string**: ResNameField string32

**Notes**: Regular model

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResNameReplaceField

**Name**: ResNameReplaceField

**Hash**: 0x4c777e9e

**Hashed string**: ResNameReplaceField string32

**Notes**: Field model, if it differs

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ResNameReplaceMuseum

**Name**: ResNameReplaceMuseum

**Hash**: 0xe4b73f7d

**Hashed string**: ResNameReplaceMuseum string32

**Notes**: Museum model, if it differs

**Versions**: 

 | 1.0.0 | 1.1.1 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


