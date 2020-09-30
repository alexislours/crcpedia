# MuseumFossilDonateInfo
[View this table in your browser](MuseumFossilDonateInfo-value.md) (version 1.5.0).

**Named columns**: 5/5

**Documented columns**: 4/5

**Description**: Camera params for fossils donated to the museum
## StageName

**Name**: StageName

**Hash**: 0xbe776e71

**Hashed string**: StageName.hshCstringRef

**Notes**: The room in which the fossil is displayed. Matches with StageName in MuseumNPCSpotTalk.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes| 


## ModelID

**Name**: ModelID

**Hash**: 0xfdeed09c

**Hashed string**: ModelID u16

**Notes**: The ID for this fossil piece's resource.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes| 


## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes| 


## WatchItem

**Name**: WatchItem

**Hash**: 0xb76b7d37

**Hashed string**: WatchItem u16

**Notes**: The item corresponding to this fossil part. Matches with UniqueID in ItemParam.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes| 


## CameraParamName

**Name**: CameraParamName

**Hash**: 0xb16c3035

**Hashed string**: CameraParamName string33

**Notes**: The fossil name? Altough all entries don't match with ItemParam's Label. If the field is empty, the appropriate value is the one from the row with the closest inferior ModelID that has the same StageName.

**Versions**: 

 | 1.0.0 | 1.1.0 | 1.2.0 | 1.3.0 | 1.4.0 | 1.5.0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Yes | Yes | Yes | Yes | Yes | Yes| 


