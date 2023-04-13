# OpenCore-EFI
个人的黑苹果所使用的EFI

# 个人配置如下：
## 主板

CVN Z490 Gaming pro v20


## CPU

intel i7 10700k


## 显卡

6800xt


或者其他免驱独显

不需要额外更改配置

## 网卡

BCM943602CS


## 内存
3200 8g*2
（开启XMP）

## 硬盘

crucial P3 Plus 1TB


# BIOS配置
### 高级 - 超级IO配置
全部关闭
### 高级 - 可信计算
全部关闭
### 高级 - 处理器配置
超线程 开启

VMX 开启

封装C状态值  关闭

增强型C状态  关闭

Intel Speed Shift Technology 关闭

Intel Trusted Execution technology 关闭

SGX 关闭
### 高级 - USB配置
全部启用
### 建议
开启iGPU以使用核显加速进行硬件解码

关闭安全启动和CSM
