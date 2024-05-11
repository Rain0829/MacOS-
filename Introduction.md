# 为什么要移除MDM文件
在刷机前，先需要了解什么是Apple Device Mangment，也被称为MDM(Mobile Device Mangement) 大多数学校，企业会尝试用MDM管理他们发给你的Mac设备。
根据Apple官网的描述， MDM capabilities include updating software and device settings, monitoring compliance with organizational policies, and remotely wiping or locking devices.
大多数情况下，因为无法更新，无法使用某些APP，甚至只能使用某些APP，被管控的电脑无法正常使用。所以需要通过刷机来获得管理员权限，移除MDM文件。

## MacOS Ventura/MacOS Sonoma 刷机
MacOS13之后的Mac如果被监管会被禁止进入Recovery Mode，无法和MacOS13版本以下的Mac以同样方法直接卸载磁盘。需要在DFU模式下安转MacOS12或以下的系统
并且如果软件更新到MacOS13及以上，会让没有加入监管系统的Mac，强制加入监管系统（每10分钟跳一次弹窗）需要删除配置文件