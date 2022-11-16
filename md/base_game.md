#### 首先请确保已完成[汉化前置](utilities.md "汉化前置")并可以正常进行游戏

------

## 一、Mod Organizer 2安装配置

下载 Mod Organizer 2安装文件

https://pan.baidu.com/s/12hwpAf9PqKQf8FWb3JV5Gg 提取码：mfnv 

下载完成后运行安装程序，选择 I accept the agreement ，然后点击 Next 进行下一步

提示选择安装位置时，选择除游戏根文件夹之外的任何位置，单击 Next ，直到安装程序完成

安装完成后，导航到Mod Organizer 2的安装位置，右键单击 ModOrganizer.exe 选择 属性

选择到 兼容性 选项卡，然后选中 **以管理员身份运行此程序**

点击 应用 然后单击 确定 退出，运行ModOrganizer.exe

Mod Organizer 2初始化配置：

1. 从名为 Creating a new instance 的弹出窗口中，选择 **Creating a portable instance**
2. 在下一页中，选择 **New Vegas**
3. 在下一页中，保持 **Location** 文件路径为默认
4. 在最后一页中，选择 **Finish**
5. 弹出窗口 Show Tutorial? ，选择 No
6. 弹出窗口 Register? ，选择 Yes

配置完成，进入主界面，点击顶部的 配置设置和解决方案 按钮 ![MO2setting_pic](https://s1.ax1x.com/2020/07/23/UOXh7T.jpg "MO2setting_pic")

在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)，点击 OK 软件切换成中文

- **以下选项只在有Nexus账户时才设置，没有的可以跳过**

  在设置中选择 Nexus 选项卡

  单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面

  选择 Authorise，等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器

  点击 OK 退出MO2中的设置菜单，MO2会提示重启，选择重启即可

返回主界面，右键单击右栏空白处并选择 全部启用

按照下图中的顺序改变左栏和右栏中的顺序

![loadorder_pic](https://s1.ax1x.com/2020/07/23/UOjS4e.jpg "loadorder_pic")

- 如果是GOG版本，则右栏中可能存在FalloutNV_lang.esp，请导航到Data文件夹将其删除

单击MO2顶部栏上的 配置档案 按钮 ![MO2profile_pic](https://s1.ax1x.com/2020/07/23/UOxi0P.jpg "MO2profile_pic")，单击 Default 配置文件，进行如下操作：

- 反选 使用档案专属的ini文件(或使用独立的游戏ini文件)，反选后会弹出窗口提示是否删除ini文件，选择 Yes 删除即可

- 选择 自动封装包无效化(或自动档案无效化)

如下图所示：

![MO2profilesetting_pic](https://s1.ax1x.com/2020/07/23/UOzuCD.jpg "MO2profilesetting_pic")

> 对于有Mod经验的玩家，如果你了解ini文件的使用原理，可以选择使用独立的游戏ini文件

回到主界面，在右栏上方的下拉菜单选择 NVSE ，点击 运行 启动游戏

**设置完成，之后都从Mod Organizer 2中的NVSE进行游戏**

## 二、Mod 安装

打开Mod Organizer2，单击顶栏的按钮 ![install_pic](https://s1.ax1x.com/2020/08/01/aGy1D1.png "install_pic")，导航到下载好的Mod压缩包，双击选择它

在弹出的窗口中确定Mod名称，一些Mod名称可能显示不全，在下拉菜单中更改或手动命名

点击 确定 安装补丁包，安装完成后该补丁会在左栏显示，选中名称前的方框以激活Mod

已激活Mod的esp/esm插件会在右栏出现并自动选中，如果该Mod不含插件则不会出现

在左栏中取消激活Mod右栏中对应的插件会自动消失，而只在右栏中取消激活插件Mod中的其他文件依旧会加载

在左栏中拖动Mod以更改**覆盖顺序**，在右栏中拖动插件以更改**加载顺序**

#### 基础游戏整合包：

https://pan.baidu.com/s/1oHxqn27YB57DcBksjJnAhw 提取码：mfnv 

解压Base Game.7z中的全部压缩包到游戏根目录以外的位置

通过Mod Organizer 2安装所有解压得到的Mod压缩包

按以下更改**覆盖顺序**：

- Bug Fixes+QOL Improvements

- HUD+UI

按以下更改**加载顺序**：

- **FalloutNV.esm**
- **DeadMoney.esm**
- **HonestHearts.esm**
- **OldWorldBlues.esm**
- **LonesomeRoad.esm**
- **GunRunnersArsenal.esm**
- **ClassicPack.esm**
- **MercenaryPack.esm**
- **TribalPack.esm**
- **CaravanPack.esm**
- **YUP - Base Game + All DLC.esm**
- **Navmesh Fixes and Improvements.esm**
- YUP - NPC Fixes (Base Game + All DLC).esp
- Unofficial Patch NVSE Plus.esp
- DisableMuzzleFlashLights.esp
- The Mod Configuration Menu.esp
- JIP Improved Recipe Menu.esp
- Simple DLC Delay.esp
- DarNifiedUINV.esp
- JustAssortedMods.esp

以下是整合版中使用的Mod及顺序：

Bug Fixes+QOL Improvements

- [YUP - Base Game and All DLC-12.1-Chinese simplified](https://www.nexusmods.com/newvegas/mods/51664 "YUP")

- [Navmesh Fixes and Improvements-0.2-Chinese simplified](https://www.nexusmods.com/newvegas/mods/62041 "Navmesh Fixes")

- [Unofficial Patch NVSE Plus-1.2.8-Chinese simplified](https://www.nexusmods.com/newvegas/mods/71239 "Unofficial Patch NVSE Plus")

- [Collision Meshes FNV-1.6.4](https://www.nexusmods.com/newvegas/mods/59149 "Collision Meshes")

- [Stewie Tweaks INI-6.30-Modified](https://www.nexusmods.com/newvegas/mods/66347 "Stewie Tweaks")

- [No Muzzle Flash Lights-1.0](https://www.nexusmods.com/newvegas/mods/69038 "No Muzzle Flash Lights")

HUD+UI

- [UIO - User Interface Organizer-2.09](https://www.nexusmods.com/newvegas/mods/57174 "UIO")

- [The Mod Configuration Menu-1.5-Chinese simplified](https://www.nexusmods.com/newvegas/mods/42507 "MCM")

- [JIP Improved Recipe Menu-1.20](https://www.nexusmods.com/newvegas/mods/59638 "Improved Recipe Menu")

- [Simple DLC Delay-2.1-Chinese simplified](https://www.nexusmods.com/newvegas/mods/62779 "Simple DLC Delay")

- [DUINV-0.5-Chinese simplified](https://www.nexusmods.com/newvegas/mods/65459 "Darnified UI")

- [Vanilla Hud Cleaned-0.38-modified](https://www.nexusmods.com/newvegas/mods/70001 "Vanilla Hud Cleaned")

- [Vanilla HUD Remastered 4K-v1.83-modified](https://www.nexusmods.com/newvegas/mods/64102 "Vanilla HUD Remastered")

- [Just Assorted Mods-3.2c-Chinese simplified](https://www.nexusmods.com/newvegas/mods/66666 "Just Assorted Mods")

#### INI编辑：

单击MO2顶部栏上的 工具 按钮 ![inieditor_pic](https://s1.ax1x.com/2020/08/01/aGhXHH.jpg "inieditor_pic")，然后选择 INI编辑器

导航到 falloutcustom.ini 选项卡，该选项卡中的内容应该与[汉化前置](utilities.md "汉化前置")中的FalloutCustom.ini内容相同

在最下方增加以下内容

    [Menu]
    iConsoleFont=8
    iDebugTextFont=8
    
    [Fonts]
    sFontFile_8=Textures\Fonts\fixedsys_kar.fnt
    sFontFile_9=Textures\Fonts\NVFont_Test.fnt


点击 保存，然后关闭INI编辑器

安装完成，确定激活需要的Mod和插件并按顺序排序后，通过NVSE进行游戏

按[汉化前置](utilities.md "汉化前置")中的 最终测试 步骤进行验证

* * *

以上是基础游戏的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。