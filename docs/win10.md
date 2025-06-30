Win10错误代码0x80004005无法访问共享设备的解决方法

1、按win+R打开运行，输入“regedit”，打开注册表编辑器。


2、打开“HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters”


3、找到“AllowInsecureGuestAuth”，如果没有，就新建一个DWORD（32）项重命名为“AllowInsecureGuestAuth”，设为“1”，确定。