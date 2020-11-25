# EventPlazaPlacementParam
[View this table in your browser](EventPlazaPlacementParam-value.md) (version 1.6.0).

**Named columns**: 12/19

**Documented columns**: 14/19

**Description**: Placement of furniture and objects in the plaza
## 0x036dd90c

**Hash**: 0x036dd90c

**Type**: u32/s32

**Notes**: Event name

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | Yes* | No| 

*Found in the BCSVs but unreferenced in the executable

## EventType

**Name**: EventType

**Hash**: 0x70703269

**Hashed string**: EventType.hshCstringRef

**Notes**: PermanentObj, CalendarEvent, VisitorNpc, and NpcGroupActivity

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## 0x24e5b19d

**Hash**: 0x24e5b19d

**Type**: u32/s32

**Notes**: NPC group activity name?

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## PlacementKind

**Name**: PlacementKind

**Hash**: 0x65a97fab

**Hashed string**: PlacementKind.hshCstringRef

**Notes**: Ftr, NPC, and EventObj

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## 0x160cb241

**Hash**: 0x160cb241

**Type**: string

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| No | No | No | No | No | Yes | No| 


## EventFtrUniqueID

**Name**: EventFtrUniqueID

**Hash**: 0x20dd4435

**Hashed string**: EventFtrUniqueID u16

**Notes**: ID of row from EventPlazaFtrParam

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## EventObjUniqueID

**Name**: EventObjUniqueID

**Hash**: 0x26db5137

**Hashed string**: EventObjUniqueID u16

**Notes**: ID of row from EventPlazaObjModelParam

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## OffsetX

**Name**: OffsetX

**Hash**: 0x4154052c

**Hashed string**: OffsetX s16

**Notes**: X position

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## OffsetZ

**Name**: OffsetZ

**Hash**: 0x3b94564c

**Hashed string**: OffsetZ s16

**Notes**: Z position

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## CalendarEventKey

**Name**: CalendarEventKey

**Hash**: 0x52f0badd

**Hashed string**: CalendarEventKey string32

**Notes**: Event name. Identical to 36dd90c

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## 0xb8e42602

**Hash**: 0xb8e42602

**Type**: u8

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| No | No | No | No | Yes | Yes | No| 


## DisableInDream

**Name**: DisableInDream

**Hash**: 0x30127dfd

**Hashed string**: DisableInDream u8

**Notes**: 1 = Doesn't appear in dreams, 0 = Does appear in dreams

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| No | No | No | No | Yes | Yes | No| 


## 0xe6c63c5c

**Hash**: 0xe6c63c5c

**Type**: string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## 0x7215b154

**Hash**: 0x7215b154

**Type**: string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## 0x56ee0925

**Hash**: 0x56ee0925

**Type**: string32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| No | No | No | No | No | Yes | No| 


## NpcSpLabel

**Name**: NpcSpLabel

**Hash**: 0x5ba37406

**Hashed string**: NpcSpLabel string32

**Notes**: Special NPC used

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## PlacementKey

**Name**: PlacementKey

**Hash**: 0xe2d0ac54

**Hashed string**: PlacementKey string32

**Notes**: Row name

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


## VisitorNpcLabel

**Name**: VisitorNpcLabel

**Hash**: 0x7e322ef0

**Hashed string**: VisitorNpcLabel string32

**Notes**: Special NPC used

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 | 1.6.0
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes | No| 


