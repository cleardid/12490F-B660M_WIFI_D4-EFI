# 12490F-B660M_WIFI_D4-EFI
自用的 微星迫击炮B660M DDR4 WIFI + 12490F + RX 580 2304 EFI文件

基于OpenCore 0.8.6	系统MacOS 12.6.2

## 个人配置

| 硬件 |            型号             |
| :--: | :-------------------------: |
| CPU  |          I5 12490F          |
| 主板 |     微星B660M DDR4 WIFI     |
| 显卡 | 华硕 雪豹 RX580 2304满血版  |
| 内存 | 威刚 金色威龙 3200MHz 16G*2 |
| 硬盘 |       西数 SN570 1TB        |
| 电源 |        酷冷至尊G600W        |

## 使用情况

cpu正常，节能三项，睡眠正常，唤醒正常，usb2/3正常，声卡正常，wifi正常,  以太网正常

## 存在的问题

隔空投送不可使用

## 其他说明

自行填写系统生成三码

## BIOS配置

### 启用

BETA -> D.T.M

BETA -> SR-IOV Support

SETTING -> ACPI -> Re-Size BAR Support

### 禁用

SETTING -> 安全引导

OC -> CPU特征 VT-D
