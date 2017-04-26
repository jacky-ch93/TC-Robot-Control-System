# TC-Robot-Control-System
Repository for Robot Control System Test in Hexapod Robot
## About the Control System
本系统使用V2015以及TwinCAT平台作为控制开发平台，开发了适用于机器人或者其他机电产品的通用化控制平台；

本系统以EATHERCAT为通讯总线，附带ELMO驱动器，完成整个程序开发；

如需将本控制系统是用在其他机电设备上，需要调整找零Home的控制逻辑，修改目前用于六足机器人的3-3找零方法。
## About the I/O Equipments
本系统所用系统总线为EHTERCAT，支持带有ETHERCAT通讯方式的外部设备直接扫描并进行扩展；

其余接口外部设备需要配备相应的倍福通讯模块或者与系统进行ADS通信。
## About the Version
本系统版本到V1.3为止，能够支持18个电机的单个电机与整机操作调试工作。
