<p>一、游戏安装</p>

<p>1.安装参数：
<strong>如果还没有安装游戏，请不要安装在 C:/Program Files(x86)/Steam 文件夹</strong>（如果已经按照在上述文件夹则无法使用BSA Decompressor）
所有modding工具必须安装在默认Windows文件夹之外（如Program Files，Program Files（x86）和Documents）。
Fallout New Vegas和Mod Organizer 2必须安装在同一个盘上，但不要将Mod Organizer 2和mod文件夹安装在游戏根目录下。</p>

<p>2.常用术语：
根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em>
Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em>
MO2：Mod Organizer 2（将很快安装）</p>

<p><strong>3.禁用叠加层：</strong>
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。
Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。
GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</p>

<p>4.设置Fallout New Vegas Modding文件夹：
modding文件夹将充当安装的所有工具的主目录，以及任何备份/屏幕截图等。
在与Fallout New Vegas相同盘上的默认Windows文件夹和游戏根目录之外创建一个新文件夹，将它命名为<em>Fallout NV Modding</em>，创建两个子文件夹名为<em>Backups</em>和<em>Tools</em>
备份整个游戏，将 Fallout New Vegas 文件夹复制到刚才创建的 Backups 中。</p>

<p><strong>5.首次运行以初始化ini文件：</strong>
从根文件夹运行 FalloutNVLauncher.exe
弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。
*   如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</p>

<p>选择 Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质。
*   如果没有正确识别GPU，请手动选择合适的画质选项</p>

<p>根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。
单击 OK，然后单击 PLAY 进入游戏。进入主菜单后没有异常就可以退出游戏。</p>

<p>二、一些工具</p>

<p>1.Microsoft VC ++ 2013
[http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist<em>x86.exe](http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist</em>x86.exe)
特别安装说明：
运行安装程序，如果收到已安装该程序的消息，请退出安装程序
*   FNV和4GB Patcher所需的库</p>

<p>2.Microsoft VC ++ 2015,2017,2019
<a href="https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads">https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads</a>
特别安装说明：
单击 Visual Studio 2017 标题下的 x86：vc<em>redist.x86.exe 和x64：vc</em>redist.x64.exe
运行两个.exe文件，如果收到已安装该程序的消息，请退出安装程序</p>

<blockquote><p>对于非Win10用户，则可能还需要遵循以下说明 <a href="https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows">https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows</a></p></blockquote>

<ul><li>Mod Organizer 2和NVR所需的库</li></ul>

<p>3.Mod Organizer 2
[https://pan.baidu.com/s/1<em>OOOisb1g1dt57hQNP7KNA](https://pan.baidu.com/s/1</em>OOOisb1g1dt57hQNP7KNA) 提取码: 5gff
特别安装说明：
下载 Mod Organizer 2 (Archive) 主文件
在之前Fallout NV Modding文件夹下的Tools文件夹新建一个文件夹命名为Mod Organizer 2
解压缩所有文件到 Mod Organizer 2 文件夹，进入目录右键单击 ModOrganizer.exe 并选择 属性
导航到 兼容性 选项卡，然后选中 以管理员身份运行此程序
选择 应用 然后单击确定退出
退出后暂时不要打开ModOrganizer.exe，后面会在配置时打开
*   迄今为止新维加斯最佳mod管理器，利用虚拟文件系统保持Data文件夹干净</p>

<p>4.MO2插件
[https://pan.baidu.com/s/1C31Qv<em>retFOZark6l23Opg](https://pan.baidu.com/s/1C31Qv</em>retFOZark6l23Opg) 提取码: 6zgm
特别安装说明：
将压缩包中文件夹和文件解压至 Mod Organizer 2/plugins 文件夹：
- 向 MO2 添加两个新特性：隐藏已合并的插件，以及比较mod列表顺序</p>

<blockquote><p>当需要更新Mod Organizer 2时，将新版压缩包解压到Mod Organizer 2文件夹中，并在出现提示时覆盖。按照上述说明以管理员身份运行程序，重新下载并安装MO2插件。</p></blockquote>

<p>三、汉化安装</p>

<p>首先请确保可以正常进入游戏，下载汉化补丁
<a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA) 提取码: 7miv
双击汉化补丁进行安装，一路点击下一步。
**在 选择目标位置 界面检查安装位置是否正确**。下一步时会弹出对话框提示目录已经存在，点击 是 即可。
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简介安装，**只需要汉化必须文件**。
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置
![fnvtools_pic](https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" title="fnvtools_pic">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a>
*   首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字
<em>   然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong>
</em>   在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</p>

<p><strong>为exe文件添加排除数据执行保护：</strong>
右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>

<p>GOG版汉化后必需文件：
<a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7
特殊安装说明：
将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）</p>

<blockquote><p>汉化补丁使用Steam版的exe文件替换了原文件，因此打上补丁的GOG版就相当于Steam版</p></blockquote>

<p>此时汉化已经完成，进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。
* 如果汉化完成后进入游戏闪退，尝试先关闭数据执行保护，即在上面的步骤中选择 仅为基本Windows程序和服务启动DEP，重启后查看游戏是否能正常打开，可以则重新为exe文件添加排除数据执行保护。</p>

<p>四、BSA文件与音频解码优化</p>

<p>BSA Decompressor
<a href="https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw">https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw</a> 提取码: xmjd
<strong>这一步要求游戏安装在 C:/Program Files(x86)/Steam 文件夹之外，如果没有则直接进行Ogg Vorbis Libraries</strong>
特殊安装说明：
<strong>如果使用机械硬盘或正在/计划使用TTW，则不要安装</strong>
将下载的文件解压缩到除Windows默认文件夹外的安全位置
右键单击FNV BSA Decompressor.exe，选择以管理员身份运行
打开程序后，应该自动检测到游戏所在目录，如果没有请自行导航到 Fallout New Vegas 文件夹
点击 Decompressor 开始运行，完成后点击 EXIT 退出程序
退出后，导航至根文件夹删除 libogg.dll
*   优化BSA文件，提升加载速度并解决一些音频播放的问题</p>

<p>Ogg Vorbis Libraries
[https://pan.baidu.com/s/1k2s5nkiEYoh<em>ySpOe0hp2w](https://pan.baidu.com/s/1k2s5nkiEYoh</em>ySpOe0hp2w) 提取码: ympj
特殊安装说明：
将压缩包内的文件解压到根目录，并在出现提示时覆盖
<strong>如果.dll文件被杀毒软件误报，请将其添加进白名单</strong>
*   最新的Ogg Vorbis编译库，允许游戏播放某些.ogg文件</p>

<p>五、Mod Organizer 2配置及INI优化</p>

<p>1.配置Mod Organizer 2：
运行ModOrganizer.exe
从名为 Choose Instance 的弹出窗口中，选择 Portable
从弹出窗口 Please select the game to manage，选择 New Vegas
如果未显示New Vegas选项，请选择 Browse…，然后导航到根文件夹并选择FalloutNV.exe
如果有一个名为 INI file is read-only 的窗口，请选择 Yes
从弹出窗口 Show Tutorial?，选择 No
从弹出窗口 Register?，选择 Yes
进入主界面，点击顶部的按钮<img alt="setting_pic" title="setting_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true"/>
在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)
点击 OK 软件切换成中文
如果未选中右栏中的所有插件，请右键单击右栏空白处并选择 全部启用
按照下图中的顺序改变左栏和右栏中的加载顺序
<img alt="order_pic" title="order_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/order_pic.jpg?raw=true"/>
*   如果是GOG版本，则加载顺序中可能存在FalloutNV_lang.esp ，请导航到/Data文件夹将其删除</p>

<p>单击MO2顶部栏上的按钮<img alt="setting_pic" title="setting_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true"/>，导航到&amp;quot; 路径&amp;quot;选项卡
以下选项只在有Nexus账户时才设置，没有的可以跳过
<em>   在 N网 选项卡中，单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面
</em>   选择 Authorise
*   等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器</p>

<p>点击 OK 退出MO2中的设置菜单，如果MO2提示重启，选择 Yes</p>

<p>2.在Mod Organizer 2中创建新配置文件：
Mod Organizer 2的配置文件功能允许在不同的mod配置之间轻松切换，可以通过左栏上方的下拉菜单选择配置文件。
单击MO2顶部栏上的按钮<img alt="profile_pic" title="profile_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2profile_pic.jpg?raw=true"/>
单击Default配置文件，然后选择重命名
输入Vanilla作为新名称
选中 Vanilla 配置文件，选择复制
输入Core作为新名称，然后单击 OK
选择 Core 配置文件并选中下方的 使用特定的ini (第二项，应该已经选中) 和 自动档案无效化
关闭配置文件窗口，可能会报错提示缺少ini文件，点击 OK 即可，然后在 配置文件 一栏选择 Core</p>

<p>3.调整FalloutCustom.ini：
确保目前选择的配置文件为 Core
单击MO2顶部栏上的按钮<img alt="inieditor_pic" title="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"/> ，然后选择 INI编辑器
导航到 falloutcustom.ini 选项卡，该选项卡应为空白
将以下内容粘贴到框中：
[General]
bUseThreadedAI=1
INumHWThreads=4
bPreemptivelyUnloadCells=1</p>

<p>[BackgroundLoad]
bBackgroundCellLoads=1
bSelectivePurgeUnusedOnFastTravel=1</p>

<p>[Display]
fLightLODDefaultStartFade=10240.0
fLightLODRange=10240.0
fLightLODMinStartFade=10240.0
fLightLODMaxStartFade=10240.0
fShadowLODDefaultStartFade=200.0
fShadowLODRange=200.0
fShadowLODMinStartFade=100.0
fShadowLODMaxStartFade=1000.0
fSpecularLODDefaultStartFade=10240.0
fSpecularLODRange=10240.0
fSpecularLODMinStartFade=10240.0
fSpecularLODMaxStartFade=10240.0
iPresentInterval=0</p>

<p>[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0
fXenonVertLookSpeed=1200.0000
fXenonHorizLookSpeed=1500.0000</p>

<p>[Grass]
fGrassStartFadeDistance=17000</p>

<p>[Audio]
iAudioCacheSize=8192
iMaxSizeForCachedSound=2048
*   将INumHWThreads更改为CPU所具有的线程数，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字
*   如果你不以16：9的宽高比运行游戏，可以删除
    fXenonVertLookSpeed=1200.0000
    fXenonHorizLookSpeed=1500.0000</p>

<p>完成后点击 保存 ，然后关闭INI编辑器。</p>

<p>六、BethINI</p>

<p><a href="https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw">https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw</a> 提取码: jw7j</p>

<p>注意事项：
BethINI容易被防病毒软件标记为误报，所以最好请其添加到将杀毒软件的白名单中。<strong>请注意，不要通过Mod Organizer 2运行，也不要在Mod Organizer 2打开时运行BethINI</strong>。</p>

<p>安装使用说明：
1.  使用前请确保已运行过FalloutNVLauncher.exe并生成了相应的INI文件
2.  <strong>请确保Mod Organizer 2关闭</strong>，解压缩文件到 <em>/Fallout NV Modding/Tools</em> 文件夹，进入并运行 BethINI.exe 。在弹出的窗口中下拉选择 Fallout New Vegas ，等待进入程序。
3.  进入程序后导航到 Setup 选项卡， <strong>取消选择</strong>下方的全部选项方框。之后在 Mod Organizer 一栏下拉菜单中选择 Browse ,在弹出的框中导航到 Mod Organizer 2 文件夹并双击选择 ModOrganizer.exe
4.  在 INI Path 一栏下拉菜单中选择正在使用的Mod Organizer 2配置文件，如 ModOrganizer&amp;gt;Core 。在弹出对话框中选择 确定 。此时会弹出对话框提示BethINI要重新启动，点击 确定 。重启后会弹出名为 Modify Custom INIs? 对话框， <strong>此时选择 否</strong> 。重新进入BethINI后导航到 Setup 选项卡，请确保全部5个选择框都没有选择。
<img alt="BethINI" title="BethINI" src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/BethINI.PNG"/>
5.  导航到 Basic 选项卡，在 Presets 栏中选择 Vanilla Presets ，再选择 Recommended Tweaks ，程序会自动优化相应的INI文件，之后请根据配置在 Low 到 Ultra 中选择合适的画质选项。
6.  选择完画质后在 Display 一栏中选择合适的分辨率，如果没有需要的分辨率则可以手动输入。可以自行选择 Antialiasing 和 Anisotropic Filtering 倍数。最后选择最下方的 Enable File Selection (如果已经选择则不用管)，确定一切选择正确后点击 Save and Exit 退出。
7.  等待程序关闭后导航到游戏根目录下 <em>data/Shaders</em> 文件夹找到 shaderpackage013.sdp ，将其命名为shaderpackage013.sdp.backup。之后把 shaderpackage017.sdp 复制一份到其他位置，将其重命名为shaderpackage013.sdp，再剪切回原文件夹。
8.  进入游戏，在主菜单中选择 选项-显示 ，检查所有<strong>淡出</strong>选项。如果有超出调节框的请将其减小一档，设置完成后退回主菜单，进入游戏检测运行是否正常。</p>

<p><strong>在使用了BethINI之后，请不要运行FalloutNVLauncher.exe或通过Steam启动新维加斯，FNVTools2.1修改字体也将不起作用</strong>。如果在以后的游戏流程中需要修改画质、改变字体及其他选项，请是点击这里 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/md/display.md" title="可选选项">可选选项</a></strong> 阅读指南有关BethINI的说明。</p>

<p>七、重要前置</p>

<p>NVSE
<a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a>
特别安装说明：
单击 Download (stable version 5.1b4) 旁边的链接进行下载
将压缩包内 nvse<em>5</em>1_beta4 文件夹中的所有内容解压到根目录
*   扩展引擎的脚本功能，对于大多数mod来说都是必不可少的</p>

<p>前置补丁包
<a href="https://pan.baidu.com/s/1yvHtlDNZk2h1nghIrApj9Q) 提取码: 9cma
特别安装说明：
打开Mod Organizer2，单击顶栏的按钮![install_pic](https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2install_pic.PNG?raw=true" title="install_pic">https://pan.baidu.com/s/1yvHtlDNZk2h1nghIrApj9Q</a>，导航到下载好的压缩包，双击选择它。
在弹出的窗口中确定名称为 Utilities ，点击 确定 安装补丁包。
安装完成后该补丁会在左栏显示，选中 Utilities 前的方框以激活Mod。
*   个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md" title="前置说明">前置说明</a></strong></p>

<p>4GBpatch
<a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h
特殊安装说明：
将压缩包内的 4gb<em>patch.exe 解压到根目录
请确保 <strong>没有</strong>运行Mod Organizer 2，导航到根目录，右键单击 4gb</em>patch.exe ，选择 以管理员身份运行
在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！
此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，等待根目录下出现 FalloutNV.exe.Backup 后点击 OK 退出
*   使游戏能够识别大地址，这意味着它可以使用4GB RAM而不是2GB</p>

<p><strong>验证NVSE和4GBpatch是否运行：</strong>
打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行
进入游戏主菜单后，按 ~ 键打开控制台
将getnvseversion输入控制台并按Enter键
控制台应报告 NVSE version: 5
*   如果没有，请检查NVSE是否已正确安装并重试</p>

<p>将getislaa输入控制台并按Enter键
控制台应该报告 GetisLAA &amp;gt;&amp;gt; 2.0000
<em>   如果控制台报告 GetisLAA &amp;gt;&amp;gt; 0.0000，则说明补丁未正确安装
</em>   如果控制台报告 GetisLAA &amp;gt;&amp;gt; 1.0000，则修补程序已正确安装但无法正常运行
*   如果控制台报告错误消息，则表示未正确安装JIP LN NVSE</p>

<p><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p>

<blockquote><p>通过Steam或GOG验证游戏文件完整性将撤消4GBpatch补丁</p></blockquote>

<p>八、最终测试及可选选项</p>

<p>至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：
<em>   确保选择了合适的画质选项，之后通过MO2进行游戏
</em>   启动一个新存档，快速通过医生的教程
<em>   离开医生的房间后，打开pipboy检查各个选项是否有问题
</em>   在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</p>

<p>这里是一些 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/md/display.md" title="可选选项">可选选项</a></strong> ，根据需求找到相应部分设置：
<em>   如果游戏时有画面撕裂的问题，参照<strong>防撕裂设置</strong>
</em>   如果需要游戏以无边框全屏的方式运行（防止切出游戏时卡死），参照<strong>伪全屏设置</strong>
<em>   在使用BSA Decompressor后如果遇到丢失的网格错误（红色大三角），参照<strong>BSA Decompressor修复</strong>
</em>   在使用BethINI后，如果需要修改字体等涉及编辑INI文件的，阅读<strong>有关BethINI的说明</strong>
*   如果要使用ENB以及NVR的截图功能，阅读<strong>有关ENB与NVR的说明</strong></p>

<p>正常按指南完整做到了每一个步骤，并选择了合适的画质与分辨率，游戏应没有卡顿并可以长时间运行不跳出。如果遇到任何问题，尝试先判断是否完全按指南进行设置。指南无法解决的问题，请先尝试百度解决方法，也可以回复进行询问，我尽可能回答。</p>

<hr/>

<p>以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
