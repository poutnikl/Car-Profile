
#### Experimental Car profile template. Beware of lack of turning restrictions.

This is a development version. You can easily derive up-to-date versions of my [Car profiles](https://github.com/poutnikl/Brouter-profiles/wiki/Car-profiles) from this latest [Template file](https://raw.githubusercontent.com/poutnikl/Car-Profile/master/Car-test-Template.brf). 
While saving, do not forget the .brf extension.

|Profile name          |What to change                  |Comment                                              |
|----------------------|--------------------------------|-----------------------------------------------------|
|Car-Fast              |Nothing                         |Template default content is identical to this profile|
|Car-FastEco           |assign drivestyle 2             |Trade-off between time and fuel spent                |
|Car-Eco               |assign drivestyle 1             |Sacrifies speed for fuel, but FastEco seems better   |
|Car-TollFree          |assign avoid_toll 1             |Avoids paid motorways, boothes and bridges           |
|Car-unpaved           |assign avoid_unpaved 0          |Stops avoiding unpaved ways                          |
|Car-MainUrb           |assign main_and_urban 1         |Accepts only mainroads and urban communications      |
|                      |                                |Stronger than avoid unpaved, for long range routing  |

[Visit also my Brouter profiles wiki pages](https://github.com/poutnikl/Brouter-profiles/wiki)

