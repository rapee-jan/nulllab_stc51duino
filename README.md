# STC51duino
based on[STC](https://www.stcmcudata.com/)The company's Arduino software development support package for 8051 core series microcontrollers. Currently, we are working on the support package for the STC89C52RC learning microcontroller to facilitate developers to learn and use it. In the future, we will gradually adapt to mainstream series chips such as STC12/STC15/STC8.
## STC51duino development board Arduino IDE support package installation

1、**File->Preferences**

2、Enter the following URL in the Additional Development Board Manager URL:

>https://raw.githubusercontent.com/rapee-jan/nulllab_stc51duino/refs/heads/main/package_nulllab_stc51duino_proxy_index.json 

![](./doc/option_zh.png)

3、**Tools->Development Board->Development Board Management**
Search for STC51duino and select the latest version to install (if it cannot be found, please install Arduino IDE 1.8.15 or above)

![board_manage_zh](./doc/board_manager_zh.png)

4、**Tools->Development Board**
![](./doc/board_chioce.png)

The STC51duino development environment is now complete.

## nulllab STC51duino development plan
The ones with a check mark have been implemented and verified, and the ones without a check mark are under development. We look forward to more developers maintaining them together.

- [x] [Development of STC8951C52_Duino learning development board]()
- [ ] [Development of ISP command line tool for STC's 8051 series microcontrollers]()
- [ ] [Develop Arduino API for STC8951C52RC+ chip]()
- [ ] [Development of STC15F2K60S2_Duino learning development board]()
- [ ] [Development of STC12C5A60S2_Duino learning development board]()
- [ ] [Development of STC8H8K64S4U_Duino learning development board]()
