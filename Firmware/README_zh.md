> 升级后需要手动恢复出厂设置，否则会导致设备无法正常工作。

# 固件升级方法
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

## 通过浏览器升级，支持Chrome内核的浏览器
1. 使用数据线连接设备
2. 打开浏览器，访问 https://tools.weactstudio.com/FirmwareUpdater/
3. 根据提示操作

# 版本历史
**V1.0.2.0**
1. 新增定时开关，按设定时间自动通断输出。关闭时间设为 0 为单次，非 0 为循环。
2. 新增 5 组通讯命令，覆盖 OC 放电、自动输出、滤波窗口、输出补偿、定时设置。
3. 优化界面刷新速度。
4. 修复一些问题。

**V1.0.1.0**
1. 通讯协议新增输入电压读取功能以及PD输入电压读取和设置功能。
2. 修复通讯协议中WHO_AM_I命令返回值错误的问题。

**V1.0.0.1**
1. 初始版本
