# Arduino applications for Azure Sphere
* Version 1.0.0
* **OS Windows 10 ( only )** 
* Sysroot 2+Beta1905 ( use last beta )
* It is very beta version - **may be bugs yet** 

![Project](https://raw.githubusercontent.com/Wiz-IO/LIB/master/azure/arduino-azure-sphere.png) 

**Board** 
* [Azure Sphere MT3620 Starter AES-MS-MT3620-SK-G by Avnet](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-ms-mt3620-sk-g-3074457345636825680/)

## Installation
* You need original [SDK](https://docs.microsoft.com/en-us/azure-sphere/install/install) to be installed ( there is compiler and uploader )
* Install Python ( 2 or 3 )
* Add JSON link to Arduino - Preferences: https://raw.githubusercontent.com/Wiz-IO/arduino-azure-sphere/master/package_wizio.azure_index.json 
* Open Borad Manager, Find 'azure' and Install 
*
* Goto folder: C:\Users\USER_NAME\AppData\Local\Arduino15\packages\WizIO\hardware\azure\VERSION
* Open: **boards.txt** and edit your path to SDK
*
* Restart Arduino IDE, Select Board 
* Open Project folder: Put file **app_manifest.json** and Edit your **Capabilities**
* Click [Compile] or [Upload]


## IF YOU WANT HELP / SUPPORT - CONNECT ME
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ESUP9LCZMZTD6)
