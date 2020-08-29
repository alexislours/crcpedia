# MuseumWatchPoint
[View this table in your browser](MuseumWatchPoint-value.md) (version 1.4.0).
**Named columns**: 13/14

**Documented columns**: 10/14

**Description**: Camera positions inside the museum
## SilhouetteID

**Name**: SilhouetteID

**Hash**: 0x3e884a6d

**Hashed string**: SilhouetteID u32

**Notes**: The index for the silhouette in MuseumNPCSilhouette if SilhouettePoint is 1, 0 otherwise.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## StageName

**Name**: StageName

**Hash**: 0xbe776e71

**Hashed string**: StageName.hshCstringRef

**Notes**: The room in which this watch point is. Matches with MuseumNPCSpotTalk.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## 0x35ac2c17

**Hash**: 0x35ac2c17

**Type**: hshCstringRef

**Notes**: Either Always, Daytime or Night. During what time period this watch point is visible.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WalkWatchOffsetX

**Name**: WalkWatchOffsetX

**Hash**: 0x1f3893e5

**Hashed string**: WalkWatchOffsetX f32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WalkWatchOffsetY

**Name**: WalkWatchOffsetY

**Hash**: 0x2258ba55

**Hashed string**: WalkWatchOffsetY f32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WalkWatchOffsetZ

**Name**: WalkWatchOffsetZ

**Hash**: 0x65f8c085

**Hashed string**: WalkWatchOffsetZ f32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WatchAngleY

**Name**: WatchAngleY

**Hash**: 0xd200ffd3

**Hashed string**: WatchAngleY f32

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WatchPosX

**Name**: WatchPosX

**Hash**: 0x2633f2c1

**Hashed string**: WatchPosX f32

**Notes**: The x coordinate of the position from where this view point is seen.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WatchPosY

**Name**: WatchPosY

**Hash**: 0x1b53db71

**Hashed string**: WatchPosY f32

**Notes**: The y coordinate of the position from where this view point is seen.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## WatchPosZ

**Name**: WatchPosZ

**Hash**: 0x5cf3a1a1

**Hashed string**: WatchPosZ f32

**Notes**: The z coordinate of the position from where this view point is seen.

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


## BattlePoint

**Name**: BattlePoint

**Hash**: 0x91eaeedd

**Hashed string**: BattlePoint u8

**Notes**: 1 if this view point is used for insect battles, 0 otherwise.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


## PointName

**Name**: PointName

**Hash**: 0x85fb9dd5

**Hashed string**: PointName string65

**Notes**: The view point's name in Japanese. Usually is the name of whatever's exposed.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes* | Yes* | Yes* | Yes* | Yes* | 

*Found in the BCSVs but unreferenced in the executable

## SilhouettePoint

**Name**: SilhouettePoint

**Hash**: 0xf58109f5

**Hashed string**: SilhouettePoint u8

**Notes**: 1 if this view point is for a silhouette (in the third fossil room), 0 otherwise.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 |
|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | 


