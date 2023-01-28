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

回到主界面，如果正确安装了[汉化前置](utilities.md "汉化前置")，则右栏上方应显示NVSE，如下图所示，点击 运行 启动游戏

![MO2_shortcut](https://s1.ax1x.com/2023/01/22/pSJaE1P.jpg "MO2_shortcut")

**设置完成，之后都从Mod Organizer 2中的NVSE进行游戏**

## 二、Mod 安装

#### 1. 单个Mod安装

打开Mod Organizer 2，单击顶栏的按钮 ![install_pic](https://s1.ax1x.com/2020/08/01/aGy1D1.png "install_pic")，导航到下载好的Mod压缩包，双击选择它

在弹出的窗口中确定Mod名称，一些Mod名称可能显示不全，在下拉菜单中更改或手动命名

点击 确定 安装补丁包，安装完成后该补丁会在左栏显示，选中名称前的方框以激活Mod

已激活Mod的esp/esm插件会在右栏出现并自动选中，如果该Mod不含插件则不会出现

在左栏中取消激活Mod右栏中对应的插件会自动消失，而只在右栏中取消激活插件Mod中的其他文件依旧会加载

在左栏中拖动Mod以更改**文件覆盖顺序**，在右栏中拖动插件以更改**插件加载顺序**

#### 2. Mod整合安装

> 注意：此方法目前并不是MO2的正式用法，可能存在问题

Mod Organizer 2安装后的Mod文件都存放在\MO2\mods 文件夹，因此理论上可以将其他人安装并配置好的Mod文件直接拷贝到该文件夹内。同时，Mod覆盖排序和插件加载排序文件存放在\MO2\profiles 下不同配置文件夹中，这样就可以在保证Mod文件一致的情况下，直接使用他人的排序文件，以实现快速的Mod列表分享。

以下是我个人的制作的Mod整合，提供了(几乎)完整的汉化，并附带调整好的覆盖和插件排序。

https://pan.baidu.com/s/1f_ESFi5E303u-E9E5618qw 提取码：mfnv

解压MFNV_mods和Texture_Base中的压缩包到\MO2\mods文件夹中，确保解压后mods文件夹内如下图所示

![MO2_mods](https://s1.ax1x.com/2023/01/22/pSJtocT.jpg "MO2_mods")

解压MFNV_profiles.7z压缩包中的全部文件到\MO2\profiles文件夹中，打开Mod Organizer 2，右上方的下拉框中应有MFNV选项，如下图所示

![MO2_profiles](https://s1.ax1x.com/2023/01/22/pSJUGee.jpg "MO2_profiles")

在下拉框中选择MFNV，选择后左栏中的Mod应该进行了排序并分类，如下图所示

![MO2_modlist](https://s1.ax1x.com/2023/01/22/pSJaGcV.jpg "MO2_modlist")

#### INI编辑：

完成Mod整合安装后，单击MO2顶部栏上的 工具 按钮 ![inieditor_pic](https://s1.ax1x.com/2020/08/01/aGhXHH.jpg "inieditor_pic")，然后选择 INI编辑器

导航到 falloutcustom.ini 选项卡，该选项卡中的内容应该与[汉化前置](utilities.md "汉化前置")中的FalloutCustom.ini内容相同

在最下方**增加**以下内容

    [Menu]
    iConsoleFont=8
    iDebugTextFont=8
    
    [Fonts]
    sFontFile_8=Textures\Fonts\fixedsys_kar.fnt
    sFontFile_9=Textures\Fonts\NVFont_Test.fnt


点击 保存，然后关闭INI编辑器

安装完成，运行游戏进行测试，游戏内应正常加载激活的Mod。