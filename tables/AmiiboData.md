# AmiiboData
**Named columns**: 9/9

**Documented columns**: 3/9

**Description**: Amiibo settings, including villagers and Special NPCs
## CharacterId

**Name**: CharacterId

**Hash**: 0xc7ad2fdf

**Hashed string**: CharacterId u32

**Notes**: An ID for the villager (and its outfit if it's a special character)

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## NumberingId

**Name**: NumberingId

**Hash**: 0x04a47035

**Hashed string**: NumberingId u16

**Notes**: A unique ID maybe?

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## SpNpcCloth

**Name**: SpNpcCloth

**Hash**: 0xf6b34c16

**Hashed string**: SpNpcCloth s16

**Notes**: always 0

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## NfpType

**Name**: NfpType

**Hash**: 0xac4a3345

**Hashed string**: NfpType u8

**Notes**: 0 if it's a "regular" amiibo, 1 if it's an amiibo card

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## NpcLabel

**Name**: NpcLabel

**Hash**: 0x34c8eed5

**Hashed string**: NpcLabel string8

**Notes**: the character's id

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## NpcType

**Name**: NpcType

**Hash**: 0x81a43e76

**Hashed string**: NpcType u8

**Notes**: 1 if special NPC, 0 if regular villager

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## Reaction

**Name**: Reaction

**Hash**: 0xdca79149

**Hashed string**: Reaction u8

**Notes**: Same values as Studio. One or both of these determine whether an amiibo can be spawned at Photopia or the campsite (in conjunction with NpcType)

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## SeriesId

**Name**: SeriesId

**Hash**: 0x5b7ca0b2

**Hashed string**: SeriesId u8

**Notes**: always 5

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

## Studio

**Name**: Studio

**Hash**: 0x1d99c513

**Hashed string**: Studio u8

**Notes**: Same values as Reaction. One or both of these determine whether an amiibo can be spawned at Photopia or the campsite (in conjunction with NpcType)

**Versions**: 1.0.0, 1.1.0, 1.2.0, 1.3.0, 1.4.0

