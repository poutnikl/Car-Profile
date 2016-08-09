
#### Experimental Car profile template. Beware of lack of turning restrictions, given by current BRouter design.

* This is a development version of Car profile template, that may be a head of the released [Car profiles](https://github.com/poutnikl/Brouter-profiles/raw/master/BR-Car-Profiles.zip). 
* See more at [Brouter-profiles](https://github.com/poutnikl/Brouter-profiles). 

* You can derive respective development versions of the profiles from this latest [Template file](https://raw.githubusercontent.com/poutnikl/Car-Profile/master/Car-test-Template.brf) by 2 ways. 

    * 1/ Use modification table below ( for now not covering all profiles ). While saving, do not forget the .brf extension.
    * 2/ Use this [Windows batchfile sedbatch.bat](https://raw.githubusercontent.com/poutnikl/Brouter-profiles/master/sedbatch.bat). 
        * Check its prerequisities inside the batch code ( presence and provided location of sed.exe, wget.exe and (optionally) 7z.exe utilities.
        * Run the batch with "car" parameter as "sedbatch car" from the Windows command line.

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

* See more at 
    * [Brouter-profiles](https://github.com/poutnikl/Brouter-profiles) and
    * [Brouter profiles wiki pages](https://github.com/poutnikl/Brouter-profiles/wiki)

