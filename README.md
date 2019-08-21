# Arduino applications for Azure Sphere
* Version 1.0.0
* **OS Windows 10 ( only )** 
* Sysroot 2+Beta1905 ( use last beta )
* It is very beta version - **may be bugs yet** 
* [Source code](https://github.com/Wiz-IO/framework-azure/tree/master/arduino)
* [Examples](https://github.com/Wiz-IO/platform-azure/tree/master/Examples)

![Project](https://raw.githubusercontent.com/Wiz-IO/LIB/master/azure/arduino-azure-sphere.png) 

**Board** 
* [Azure Sphere MT3620 Starter AES-MS-MT3620-SK-G by Avnet](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-ms-mt3620-sk-g-3074457345636825680/)

## Installation
* **You need install the original** [Microsoft Azure Sphere SDK](https://docs.microsoft.com/en-us/azure-sphere/install/install) ( there is compiler, tools and uploader )
* Install Python ( 2 or 3, need for packer and uploader )
* Add JSON link to Arduino - Preferences: https://raw.githubusercontent.com/Wiz-IO/arduino-azure-sphere/master/package_wizio.azure_index.json 
* Open Borad Manager, Find **azure** and Install 
*
* Goto folder: C:\Users\USER_NAME\AppData\Local\Arduino15\packages\WizIO\hardware\azure\VERSION
* **Open: boards.txt and edit your path to 'Microsoft Azure Sphere SDK'**
* if is new beta - change to max version
*
* Restart Arduino IDE, Select Board 
* Create your INO, 
* Open INO Project folder and put file **app_manifest.json** and edit your **Capabilities**
* Click [Compile] or [Upload]

Simple: app_manifest.json or [Application manifest](https://docs.microsoft.com/en-us/azure-sphere/app-development/app-manifest)
```json
{
    "SchemaVersion": 1,
    "Name": "",
    "ComponentId": "",
    "EntryPoint": "",
    "CmdArgs": [],
    "Capabilities": {
        "AllowedConnections" : [],
        "AllowedTcpServerPorts": [],
        "AllowedUdpServerPorts": [],
        "Gpio": [],
        "Uart": [],        
        "I2cMaster": [],
        "SpiMaster": [],
        "SystemTime" : true,
        "WifiConfig" : true
    }
}
```


## IF YOU WANT HELP / SUPPORT - CONNECT ME
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ESUP9LCZMZTD6)
