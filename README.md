# TC-Robot-Control-System
Repository for Robot Control System for Manufacturing Robot based on Hexpod Robot
## About the Control System
1、本系统使用需保证Win7以上操作环境，V2015开发环境以及TwinCAT运行平台作为控制平台基础

2、适用于移动制造机器人或者其他机电产品的通用化控制平台，控制模型通过Simulink开发，控制主程序通过PLC开发，传感器检测程序通过C++开发

3、通用移动平台为交大六足并联构型机器人，作业设备控制可以更换控制程序形成整体控制
## About the I/O Equipments
1、本系统所用系统总线为EHTERCAT，支持带有ETHERCAT通讯方式的外部设备直接扫描并进行扩展；

2、其余接口外部设备需要配备相应的倍福通讯模块或者与系统进行ADS通信，或ADS通讯方式接入其余第三方接口
## About the Version
1、版本V1.0 - V2.0.1：对应项目“TC_Robot_System_Test"，六足机器人基础运动控制系统，支持18个电机控制，仅能用于六足机器人的原地运动控制

2、版本V2.5：对应项目“TC_Walking_Robot_Control_System"，引入了六足机器人Simulink控制模型，集成六足原地运动控制及行走运动控制，支持18个电机控制，至此六足机器人可完成非稳定性行走控制

3、版本V3.0：对应项目"TC_Walking_Welding_Robot_Control"，集成六足原地运动控制、行走运动控制以及移动焊接机器人完整控制，支持24个电机（六足18个，焊接臂6个）控制，至此移动制造完整控制系统框架建立完成
