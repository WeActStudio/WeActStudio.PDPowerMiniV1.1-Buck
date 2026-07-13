> 升级后需要手动恢复出厂设置，否则会导致设备无法正常工作。

## 版本历史
**V1.0.1.0**
1. 通讯协议新增输入电压读取功能以及PD输入电压读取和设置功能。
2. 修复通讯协议中WHO_AM_I命令返回值错误的问题。

**V1.0.0.1**
1. 初始版本

## Windows下怎样升级
1. 解压WeActStudio_Upgrade_Tool.7z
2. 运行WeActStudio_Upgrade_Tool.exe
3. 使用数据线连接设备
4. 选择fpk固件
5. 打开串口
6. 点击发送按钮，开始升级

## Linux、macOS或Windows下怎样升级
1. 解压WeActStudio_Upgrade_Tool_Python.zip
2. 使用数据线连接设备
3. 运行WeActStudio_Upgrade_Tool.py, 需要安装pyserial库  
示例：python WeActStudio_Upgrade_Tool.py firmware.fpk
4. 等待升级完成