# PLC 信息点命名约定

## 基本规则

`AABBCDDEE_FFF_GGG`

- `AA`: [隧道代码](#隧道代码)
- `BB`: [类别代码](#类别代码)
- `C` : [隧道方向](#隧道方向)
- `DD`: [设备代码](#设备代码)
- `EE`: [分组代码](#分组代码)
- `FFF`: [设备名称](#设备名称)
- `GGG`: [信息点](#信息点)


### 隧道代码

隧道代码为固定两个字符长度, 详细如下表：

隧道代码 | 隧道名称
------------ | -------------
JN | 京广路隧道南段
JB | 京广路隧道北段
WS | 纬四路隧道
JS | 经三路隧道
WL | 未来路隧道
HZ | 红专路隧道
SD | 商鼎路隧道

### 类别代码

类别代码为固定两个字符长度, 详细如下表：

类别代码 | 类别
------------ | -------------
JT | 交通系统
PS | 排水系统
TF | 通风系统
ZM | 照明系统

### 隧道方向

方向代码 | 方向
------------ | -------------
L | 在 2D 隧道平面图上, 车流方向为**左**的隧道(洞)
R | 在 2D 隧道平面图上, 车流方向为**右**的隧道(洞)

### 设备代码

设备代码 | 设备类别
------------ | -------------
21 | 车道指示器
31 | 雨水泵
32 | 废水泵
61 | 基本照明
62 | 应急照明
63 | 加强照明
71 | 耐高温排风机
72 | 送风机
73 | 排风机
74 | 射流风机
75 | 轴流风机
            
### 分组代码

各隧道各不相同, 整理中

### 设备名称

设备名称为**可变长度字符串**, 整理中...

此名称可能来自图纸标注, 也可能是录入时确定, 各隧道各不相同.

举例点名 `JNJTL2103_ZSD30_RG` 对应:
> * `JN` 京广路隧道南段
> * `JT` 交通系统
> * `L`  左向隧道
> * `21` 车道指示器
> * `JN` 第 `03` 车道
> * `ZSD30` 车道指示器为 `ZSD30`
> * `RG` 开关量输入.箭头开关

### 信息点

设备名称为**可变长度字符串**.

整理中...


