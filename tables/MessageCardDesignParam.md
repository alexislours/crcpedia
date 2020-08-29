# MessageCardDesignParam
**Named columns**: 19/21

**Documented columns**: 16/21

**Description**: Params and seasonality for mail card designs
## BackColor

**Name**: BackColor

**Hash**: 0xa2fe7f71

**Hashed string**: BackColor u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## BodyColor

**Name**: BodyColor

**Hash**: 0x41afe839

**Hashed string**: BodyColor u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## 0x63a46970

**Hash**: 0x63a46970

**Type**: u16/s16

**Notes**: Never used by game code

**Versions**: , , , , 

## FootColor

**Name**: FootColor

**Hash**: 0x57c98e5b

**Hashed string**: FootColor u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## HeadColor

**Name**: HeadColor

**Hash**: 0x32c0c064

**Hashed string**: HeadColor u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## PenColor1

**Name**: PenColor1

**Hash**: 0x990406a9

**Hashed string**: PenColor1 u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## PenColor2

**Name**: PenColor2

**Hash**: 0xdea47c79

**Hashed string**: PenColor2 u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## PenColor3

**Name**: PenColor3

**Hash**: 0xe3c455c9

**Hashed string**: PenColor3 u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## PenColor4

**Name**: PenColor4

**Hash**: 0x51e489d9

**Hashed string**: PenColor4 u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## RuleColor

**Name**: RuleColor

**Hash**: 0x94d6cb5d

**Hashed string**: RuleColor u16

**Notes**: indices to MessageCardColorParam

**Versions**: , , , , 

## SelectableBeginDate1

**Name**: SelectableBeginDate1

**Hash**: 0x953983b4

**Hashed string**: SelectableBeginDate1 u16

**Notes**: mail card design unlock date, stored as month * 100 + day. (e.g. 1120 = november 20th)

**Versions**: , , , , 

## SelectableBeginDate2

**Name**: SelectableBeginDate2

**Hash**: 0xd299f964

**Hashed string**: SelectableBeginDate2 u16

**Notes**: southern hemisphere override for previous date

**Versions**: , , , , 

## SelectableEndDate1

**Name**: SelectableEndDate1

**Hash**: 0xada3644a

**Hashed string**: SelectableEndDate1 u16

**Notes**: mail card design unlock end date

**Versions**: , , , , 

## SelectableEndDate2

**Name**: SelectableEndDate2

**Hash**: 0xea031e9a

**Hashed string**: SelectableEndDate2 u16

**Notes**: southern hemisphere override for previous date

**Versions**: , , , , 

## TextLotId

**Name**: TextLotId

**Hash**: 0x5f384120

**Hashed string**: TextLotId s16

**Notes**: Always -1

**Versions**: , , , , 

## 0x84818e10

**Hash**: 0x84818e10

**Type**: u16/s16

**Notes**: Always -1

**Versions**: , , , , 

## UniqueID

**Name**: UniqueID

**Hash**: 0x54706054

**Hashed string**: UniqueID u16

**Versions**: , , , , 

## Kind

**Name**: Kind

**Hash**: 0x24da7ada

**Hashed string**: Kind u8

**Notes**: Always 0

**Versions**: , , , , 

## ResourceName

**Name**: ResourceName

**Hash**: 0x4b9c4229

**Hashed string**: ResourceName string64

**Notes**: MessageCard image in Layout

**Versions**: , , , , 

## SelectableSeason

**Name**: SelectableSeason

**Hash**: 0xaa738fed

**Hashed string**: SelectableSeason u8

**Notes**: Sets card seasonality. 1-4 are regular seasons; 5 uses SelectableBeginDate1 and SelectableEndDate1 for both hemispheres; 6 is the same as 5 but uses SelectableBeginDate2 and SelectableEndDate2 for southern hemisphere

**Versions**: , , , , 

## UnlockTrigger

**Name**: UnlockTrigger

**Hash**: 0x7a6965c5

**Hashed string**: UnlockTrigger u8

**Versions**: , , , , 

