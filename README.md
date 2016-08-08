
#### Experimental Car profile template. Beware of lack of turning restrictions, given by current BRouter design.

* This is a development version, that may be ahead from the [released Car profiles](https://github.com/poutnikl/Brouter-profiles/raw/master/BR-Car-Profiles.zip). 

* You can easily derive up-to-date versions of above Car profiles from the development template by generating them on Windows by sedbatch.bat. See [Brouter Profiles Repository](https://github.com/poutnikl/Brouter-profiles). 

* List below is under cunastruction, not reflects fully the profile packages

|Profile name          |What to change/is chnaged       |Comment                                              |
|----------------------|--------------------------------|-----------------------------------------------------|
|Car-Fast              |Nothing                         |Profile tries to suggest fastest routeto this profile|
|Car-FastEco           |assign drivestyle 2             |Trade-off between time and fuel spent                |
|Car-Eco               |assign drivestyle 1             |Sacrifies speed for saving fuel. FastEco seems better|
|Car-TollFree          |assign avoid_toll 1             |Avoids paid motorways, boothes and bridges           |
|Car-NoMotorway        |assign avoid_motorways  1       |Avoid motorways / motorroads                         |
|Car-NoUnpaved         |assign road_restriction 2       |Avoids unpaved ways ( by default just penalizes them |
|Car-MainUrb           |assign road_restriction 3       |Accepts only mainroads and urban communications      |
|Car-LongDists         |assign road_restriction 4       |Long distances - accepts only mainroad network       |
|Car-LongDists-Sec     |assign road_restriction 5       |Long distances - accepts only secondary or better    |
|Car-LongDists-Prim    |assign road_restriction 6       |Long distances - accepts only primary or better      |
|Car-Whatever          |Any of above                    |The style/toll/restriction changes can be combined   |

[Visit also my Brouter profiles wiki pages](https://github.com/poutnikl/Brouter-profiles/wiki)

