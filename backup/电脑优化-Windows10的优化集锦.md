# 关于Windows10的优化集锦 @DiYingisaDer 
> 提示：本篇文章为老手滚瓜烂熟，新手一脸懵逼篇章，萌新请参照以下内容进行系统优化，切勿乱改，以免系统报废。
**本篇文章可能会占用您很长的时间，请合理安排，谢谢！**
**介于移动端可能无法正常显示GIF图片，请在电脑端进行浏览。**
> 本篇文章内容是基于以下版本编译	
Windows 10 专业版
版本号	22H2
安装日期	‎2023/‎1/‎17
操作系统内部版本	19045.4529
体验	Windows Feature Experience Pack 1000.19058.1000.0
维护状态：更新中
开始编辑日期 2024/6/27
最近编辑日期 2024/6/28

---

## 一、windows设置-优化
> 提示：点击左下角开始菜单内的设置。

![设置](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/0188456f-4e70-4642-baa2-23c8fd342a9f)





### 系统
![image](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/fe98207c-5f26-4bb1-b8b8-39e28addd758)

---

#### 屏幕设置


**一、设置显示器支持的最高刷新频率(HZ)**

1.点击屏幕下滑找到“高级显示设置”并点击进入；

![1](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/e1f15801-c224-4b3a-a7be-d554c49d9b40)

2.下拉找到刷新频率，将其设置为最高数值。

![2](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/bc65ea6d-b331-4a75-9114-ff185e8f92ce)

> 解：电脑显示器刷新率一般为60HZ、120HZ、144HZ、240HZ，数值越高视觉效果越好，且久看高刷新率显示器后再去看低刷新率显示器视觉上会感觉很卡，另外，购买显示器时要看清楚商品介绍内的最高刷新率，若购买的显示器仅支持60HZ刷新率，那最高只能设置为60HZ，且推荐小白在官方渠道购买，避免被不良厂家打着高刷新率、4K240HZ以及2K60HZ+1K144HZ自由切换的旗号欺骗，用上一段时间后发现买回来的显示器无法设置高刷新率，后知后觉的你再去找商家退货退款，结果发现人家早就跑路了，同样，博主之前遇到过很多小白盲目的对显示器进行超频，本来60HZ的刷新率硬是超频到了80HZ，结果显示器在某天突然花屏，然后报废。

**二、打开硬件加速GPU计划**

1.点击屏幕下滑找到“图形设置”并点击进入，然后将硬件加速GPU计划设置为开。

![3](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/becc39d9-3251-44a7-980b-784c1b871b06)

> 解：此设置可以提高较小的显卡性能，若在打开后出现玩游戏严重掉帧，请将其关闭，另外，可能大多数专家会让你打开Windows设置里的游戏模式，可很少有人告诉你，游戏模式只会对微软商城里下载的游戏有性能提升。

---

#### 通知和操作设置

**一、关闭通知**

1.点击通知和操作，然后将所有被勾选的设置取消勾选，再关闭通知按钮。

![4](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/2d5bb267-29de-4e8d-9ef5-b514f758c3b9)

> 解：在你玩游戏的时候，可能会在你的屏幕右下角弹出，然后你的鼠标可能会不受控制的脱离了你对游戏的控制，若你设置了全屏显示，却误触通知界面，很可能会直接弹回到桌面。

---

#### 专注助手设置

**一、关闭专注助手**

1.点击专注助手，然后将里面的所有功能全部关闭即可。

![5](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/abdbfe82-d730-49cc-9391-b02d59ff1607)

> 解：在关闭通知按钮后，就变得不再那么需要专注助手了，若需要，还自便。

---

#### 电源与睡眠设置

**一、关闭屏幕睡眠功能**

1.点击电源与睡眠，然后将屏幕、睡眠全部改为从不。

![6](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/cc65751f-86ea-4cce-9b0a-c9b88946dfe0)

> 解：设置为从不后，电脑在长时间搁置后，不会再关闭屏幕。

**二、打开卓越性能模式**

1.点击电源与睡眠，下滑找到其他电源设置并点击进入；

![7](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/a10d05a6-a57a-45ec-9773-debaa3e49c7b)

2.点击选择“卓越性能”；

![8](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/e93df6c1-2431-4a61-9f98-a4e965966fa4)

> 提示：若您的电源计划内没有“卓越性能”，请同时按键盘上的 Ctrl + C 复制以下代码，并以管理员是否运行Windows系统自带的“CMD命令提示符”或“PowerShell”，然后同时按键盘上的  Ctrl + V 粘贴已经复制过的代码，然后再按键盘上的回车键(Enter)，便可将“卓越性能”添加到电源计划内。

```
Powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61
``` 

3.右键开始菜单并点击“Windows PowerShell(管理员)”；

![9](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/eb62291f-23f4-4410-ae3c-c2f8e7be2248)

4、将代码粘贴(Ctrl + V)后按回车(Enter)即可。

![10](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/4dc7eaa2-aef9-4cdb-ac9d-d4330f98985e)

> 解：
**平衡模式：** 
此模式会在您电脑处于不频繁使用的情况下降低电压和频率进行省电，在您频繁使用电脑时会增加电压的供给，从而提高电脑频率，以获得更好的性能，但在日常使用过程中可能会因为降低电压从而感受到卡顿；
**高性能模式：** 
此模式会在您电脑处于不频繁使用的情况下依然处于高频率状态，持续保持较好的性能，但在此模式下，不但会加大电源的消耗，还会使电脑的温度升高；
**卓越性能模式：** 
此模式相对高性能模式会拥有更好的性能表现，且在此模式下CPU的电压会更低，从而使电脑温度降低，减少了因电脑散热不好导致的CPU降频导致的卡顿。

**三、关闭快速启动**

1.点击左侧的“选择电源按钮的功能”，进入后点击“更改当前不可用的设置”，将“快速启动”取消勾选后保存修改即可。

> 提示：可以将“快速启动”和“休眠”一起取消勾选。

![11](https://github.com/DiYingisaDer/zang_diying.github.io/assets/125773452/00551368-442f-451f-b98f-fd5336702ce8)

> 解：若勾选了快速启动，电脑可能会减少微乎其微的开机时长，但随着使用次数和时长的增加，快速启用功能会占用您系统硬盘大量的储存空间用创建休眠文件来保存您在关机前所使用窗口的位置，且频繁对硬盘读写会降低硬盘寿命。

<!-- ##{"script":"<script src='https://blog.meekdai.com/assets/GmeekTOC.js'></script>"}## -->