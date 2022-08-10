### 一、安装设置

#### 1.系统设置：

**安装所有需要的Microsoft VC++ Redistributable Packages**(下载链接均来自微软官方)

- Microsoft VC++ 2013
	- x86: [vc_redist.x86.exe](https://aka.ms/highdpimfc2013x86chs)
	- x64: [vc_redist.x64.exe](https://aka.ms/highdpimfc2013x64chs)

- Microsoft VC++ 2015-2019 
	- x86: [vc_redist.x86.exe](https://aka.ms/vs/16/release/vc_redist.x86.exe)
	- x64: [vc_redist.x64.exe](https://aka.ms/vs/16/release/vc_redist.x64.exe)

如果之前卸载过新维加斯，**请确保删除所有了游戏文件、相关存档并清除注册表残余**。如果使用Windows 10系统，请单独添加英语作为第二语言，并在游戏时确保切换到英语键盘。

指南中使用到的常用目录：

* 根文件夹(根目录)：_Steam/steamapps/common/Fallout New Vegas_ 或 _GOG Galaxy/Games/Fallout New Vegas_
* Data文件夹：_Steam/steamapps/common/Fallout New Vegas/Data_ 或 _GOG Galaxy/Games/Fallout New Vegas/Data_

#### 2.首次运行以初始化ini文件：
**首次安装完成后，在Steam或GOG中启动游戏，等待其完成初始化设置**。完成后弹出Detecting Video Hardware的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。

> 如果没有任何弹出窗口，请导航到 _文档/My Games/FalloutNV_ 并删除以.INI结尾的所有文件，然后重新运行

选择Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质**（不要选择最低画质）**。

根据你的偏好设置分辨率，注意Antiailiasing项最多可以设置为8 Samples。单击OK，然后单击PLAY进入游戏。进入主菜单后没有异常就可以退出游戏。

### 二、汉化安装
本指南使用民间汉化第六版，首先请确保可以正常进入游戏，然后下载汉化补丁

https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA 提取码: 7miv

双击汉化补丁进行安装，一路点击下一步。**在"选择目标位置"界面检查安装位置是否正确**。下一步时会弹出对话框提示目录已经存在，点击是即可。

在"选择组件"界面中反选所有选项，或在下拉菜单中选择"简洁安装"**(只需要汉化必须文件)**。点击下一步进行安装，安装完成后在最后界面选择"运行FNVTools设置游戏" ，结束后自动弹出FNVTools2.1

点击FNVTools中的"INI设置和优化" ，进入INI设置和优化后在下方"切换INI字体设置" 一栏选择想要的字体(中文幼圆大字或中文宋体小字二选一)，点击会后弹出对话框，选择是，再点击确定。最后点击最下方的保存 ，然后关闭 FNVTools2.1。

GOG版汉化后必需文件：

https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ 提取码: s5x7

将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）

> 民间汉化补丁使用了Steam版的exe文件并进行了修改，打上补丁的GOG版就相当于Steam版。
天邈汉化使用原版exe文件，目前天邈汉化尚不完善，推荐使用民间汉化。

此时汉化已经完成，**直接点击根目录下的FalloutNV.exe进入游戏**，主界面和菜单应该都已汉化。

**点击"选项"-"显示"，滚轮滑到最下，将"一般字幕"设置为开启**。然后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。

### 三、重要前置
#### 1.FalloutCustom.ini优化
https://pan.baidu.com/s/144Lja3qMQiuhmYZDM3_EFg 提取码：mfnv

将压缩包内的文件解压至 *此电脑/文档/My Games/FalloutNV*，完成后导航到该目录打开FalloutCustom.ini，将iNumHWThreads=后的数字更改为CPU所具有的线程数并保存。

> 如果不知道CPU所具有的线程数，可以打开同目录下的RendererInfo.txt ，查看HW Thread Count后面的数字

#### 2.前置补丁包

**在安装前，请确保安装了所有需要的Microsoft VC++ Redistributable Packages(见第一步)**

https://pan.baidu.com/s/1ltE-k_jax7W8GspFsJSSSw 提取码：mfnv

将压缩包内的所有内容解压到根目录，在出现提示时选择覆盖。解压后nvse_loader.exe应该与FalloutNV.exe在同一目录，之后进行以下操作。

1.对exe文件进行4gbPatch：

- **针对民间汉化修改版exe文件(本指南使用)**

  导航到根目录，右键单击4gb_patch.exe，选择"以管理员身份运行"。在弹出的窗口中双击选择 FalloutNV.exe ，等待弹出窗口并且根目录下出现FalloutNV.exe.Backup后点击OK退出

- (针对天邈汉化原版exe文件）
  
  导航到根目录，右键单击FalloutNVpatch.exe，选择"以管理员身份运行"。当弹出的窗口中显示 FalloutNV.exe patched! ，按键盘上的任意键退出。

2.进入根目录，运行**cpu_info.exe**。如果弹出的界面中显示=> Use AVX2 <=，则无需改动。如果不是，则进行如下操作：

- 首先将根目录下的d3dx9_38.dll文件删除
- 显示Use AVX时，则将d3dx9_38.AVX重命名为d3dx9_38.dll
- 显示Use SSE2时，则将d3dx9_38.SSE2重命名为d3dx9_38.dll

> 个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 **[前置说明](mod_introduction.md "前置说明")**

**3.验证NVSE和4GBpatch是否正常运行：**

在根目录下双击nvse_loader.exe运行游戏。进入游戏主菜单后，按 ~ 键打开控制台

此时控制台应显示xNVSE及JIP NVSE的版本，将getislaa输入控制台并按Enter键，控制台应该报告 GetisLAA &gt;&gt; 2.0000

* 如果没有正确显示版本，请检查前置包是否正确安装

* 如果没有报告GetisLAA &gt;&gt; 2.0000，请检查4GBpatch是否正确完成


**验证完成后，不要在Steam/GOG内运行游戏，只通过NVSE(nvse_loader.exe)进行游戏**

> 使用民间汉化后，运行游戏不再需要强制打开Steam，如果需要成就请提前打开平台
通过Steam或GOG验证游戏文件完整性可以恢复原版exe文件，但会撤消4GBpatch补丁

------

以上是基础汉化的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。