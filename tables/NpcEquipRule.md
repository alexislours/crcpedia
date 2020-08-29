# NpcEquipRule
**Named columns**: 20/20

**Documented columns**: 8/20

**Description**: Parameters for each PurposeTag (AITag) for villager clothing
## ClothesFrequencyWear

**Name**: ClothesFrequencyWear

**Hash**: 0x423d1c4d

**Hashed string**: ClothesFrequencyWear.hshCstringRef

**Notes**: Likelyhood of wearing a top from the PurposeTag during this EquipRule?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ClothesPurposeLimit

**Name**: ClothesPurposeLimit

**Hash**: 0xb219374f

**Hashed string**: ClothesPurposeLimit.hshCstringRef

**Notes**: Limits tops to within the PurposeTag during this EquipRule?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ClothesTemporarilyCreate

**Name**: ClothesTemporarilyCreate

**Hash**: 0x68d62ca8

**Hashed string**: ClothesTemporarilyCreate.hshCstringRef

**Notes**: Determines whether villagers will use a TempCreate top if they don't own any tops in the PurposeTag

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## PurposeScore

**Name**: PurposeScore

**Hash**: 0x1f401b52

**Hashed string**: PurposeScore s32

**Notes**: Likelyhood out of 10 that clothes are worn from the PurposeTag regardless of taste and season?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## PurposeTag

**Name**: PurposeTag

**Hash**: 0xe765b554

**Hashed string**: PurposeTag u32

**Notes**: Numbers line up with row index (not UniqueID!) within AITag.bcsv

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## ScoreMultiplier

**Name**: ScoreMultiplier

**Hash**: 0xcbbe9d2d

**Hashed string**: ScoreMultiplier f32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## SeasonScore

**Name**: SeasonScore

**Hash**: 0x79be959d

**Hashed string**: SeasonScore s32

**Notes**: Likelyhood out of 10 that clothes are worn from the PurposeTag based on season? Possibly uses the 'Season' AITagCategory instead of ItemParam's Seasonality

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## TasteScore

**Name**: TasteScore

**Hash**: 0xa3dc7c4c

**Hashed string**: TasteScore s32

**Notes**: Likelyhood out of 10 that clothes are worn from the PurposeTag based on the villager's tastes?

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


## CapFrequencyWear

**Name**: CapFrequencyWear

**Hash**: 0xf9cf603a

**Hashed string**: CapFrequencyWear u8

**Notes**: Likelyhood of wearing a cap from the PurposeTag during this EquipRule? Numbers should line up with ClothesFrequencyWear, but that has 3 different strings and this has 4 values.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## CapPurposeLimit

**Name**: CapPurposeLimit

**Hash**: 0x2c2a379e

**Hashed string**: CapPurposeLimit u8

**Notes**: Limits caps to within the PurposeTag during this EquipRule?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## CapTemporarilyCreate

**Name**: CapTemporarilyCreate

**Hash**: 0xa4396b29

**Hashed string**: CapTemporarilyCreate u8

**Notes**: Determines whether villagers will use a TempCreate cap if they don't own any caps in the PurposeTag

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## GlassesFrequencyWear

**Name**: GlassesFrequencyWear

**Hash**: 0x744b3452

**Hashed string**: GlassesFrequencyWear u8

**Notes**: Likelyhood of wearing glasses from the PurposeTag during this EquipRule?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## GlassesPurposeLimit

**Name**: GlassesPurposeLimit

**Hash**: 0xa073aa81

**Hashed string**: GlassesPurposeLimit u8

**Notes**: Limits glasses to within the PurposeTag during this EquipRule?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## GlassesTemporarilyCreate

**Name**: GlassesTemporarilyCreate

**Hash**: 0xfdf8907b

**Hashed string**: GlassesTemporarilyCreate u8

**Notes**: Determines whether villagers will use TempCreate glasses if they don't own any glasses in the PurposeTag

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


## MaskFrequencyWear

**Name**: MaskFrequencyWear

**Hash**: 0x74275e7a

**Hashed string**: MaskFrequencyWear u8

**Notes**: Likelyhood of wearing a mask from the PurposeTag during this EquipRule? All 0s

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## MaskPurposeLimit

**Name**: MaskPurposeLimit

**Hash**: 0xcc198281

**Hashed string**: MaskPurposeLimit u8

**Notes**: Limits masks to within the PurposeTag during this EquipRule? All 0s

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## MaskTemporarilyCreate

**Name**: MaskTemporarilyCreate

**Hash**: 0x14767df7

**Hashed string**: MaskTemporarilyCreate u8

**Notes**: Determines whether villagers will use a TempCreate mask if they don't own any masks in the PurposeTag. All 0s

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## Name

**Name**: Name

**Hash**: 0x036e8ebe

**Hashed string**: Name string64

**Notes**: Japanese name

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

