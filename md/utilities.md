<p class="has-line-data" data-line-start="0" data-line-end="1">一、安装设置</p>
<p class="has-line-data" data-line-start="2" data-line-end="4">1.系统设置：<br>
如果之前卸载过新维加斯，<strong>请确保删除所有了游戏文件、相关存档并清除注册表残余</strong>。如果使用Win10系统，请修改以下设置：</p>
<ul>
<li class="has-line-data" data-line-start="5" data-line-end="6">关闭系统自带的游戏模式</li>
<li class="has-line-data" data-line-start="6" data-line-end="7">单独添加英语作为第二语言，并在游戏时确保切换到英语键盘。</li>
<li class="has-line-data" data-line-start="7" data-line-end="9">游戏时关掉所有通知，以及其他可能在后台弹出的软件。</li>
</ul>
<p class="has-line-data" data-line-start="9" data-line-end="11">2.安装设置：<br>
<strong>如果还没有安装游戏，请不要安装在 C:/Program Files(x86)/Steam 文件夹</strong>（如果已经按照在上述文件夹则无法使用BSA Decompressor）常用目录：</p>
<ul>
<li class="has-line-data" data-line-start="12" data-line-end="13">根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em></li>
<li class="has-line-data" data-line-start="13" data-line-end="15">Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></li>
</ul>
<p class="has-line-data" data-line-start="15" data-line-end="17"><strong>3.禁用叠加层：</strong><br>
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li class="has-line-data" data-line-start="18" data-line-end="19">Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li class="has-line-data" data-line-start="19" data-line-end="21">GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>
</ul>
<p class="has-line-data" data-line-start="21" data-line-end="23"><strong>4.首次运行以初始化ini文件：</strong><br>
在Steam或GOG中启动游戏，等待其完成初始化设置。完成后弹出Detecting Video Hardware的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="24" data-line-end="26">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行</li>
</ul>
<p class="has-line-data" data-line-start="26" data-line-end="28">选择 Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质（建议不要选择最低画质）。<br>
根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。单击 OK，然后单击 PLAY 进入游戏。进入主菜单后没有异常就可以退出游戏。</p>
<p class="has-line-data" data-line-start="29" data-line-end="30">二、汉化安装</p>
<p class="has-line-data" data-line-start="31" data-line-end="39">首先请确保可以正常进入游戏，然后下载汉化补丁<br>
<a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv<br>
双击汉化补丁进行安装，一路点击下一步。<br>
<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。<br>
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简洁安装，<strong>只需要汉化必须文件</strong>。<br>
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1<br>
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置<br>
<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="39" data-line-end="40">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="40" data-line-end="41">然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong></li>
<li class="has-line-data" data-line-start="41" data-line-end="43">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="43" data-line-end="47">GOG版汉化后必需文件：<br>
<a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7<br>
特殊安装说明：<br>
将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<blockquote>
<p class="has-line-data" data-line-start="47" data-line-end="48">汉化补丁使用Steam版的exe文件替换了原文件，因此打上补丁的GOG版就相当于Steam版</p>
</blockquote>
<p class="has-line-data" data-line-start="49" data-line-end="50">此时汉化已经完成，进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。</p>
<p class="has-line-data" data-line-start="51" data-line-end="52">三、BSA文件优化</p>
<p class="has-line-data" data-line-start="53" data-line-end="63">BSA Decompressor<br>
<a href="https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw">https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw</a> 提取码: xmjd<br>
<strong>这一步要求游戏安装在 C:/Program Files(x86)/Steam 文件夹之外，如果不满足则跳过</strong><br>
特殊安装说明：<br>
<strong>如果使用机械硬盘或正在/计划使用TTW，则不要安装</strong><br>
将下载的文件解压缩到除Windows默认文件夹外的安全位置<br>
右键单击FNV BSA Decompressor.exe，选择以管理员身份运行<br>
打开程序后，应该自动检测到游戏所在目录，如果没有请自行导航到 Fallout New Vegas 文件夹<br>
点击 Decompressor 开始运行，完成后点击 EXIT 退出程序<br>
退出后，导航至根文件夹删除 libogg.dll</p>
<ul>
<li class="has-line-data" data-line-start="64" data-line-end="66">优化BSA文件，提升加载速度并解决一些音频播放的问题</li>
</ul>
<p class="has-line-data" data-line-start="66" data-line-end="73">四、调整FalloutCustom.ini<br>
导航到 文档/My Games/FalloutNV，新建一个文本文档，重命名为FalloutCustom.ini<br>
打开FalloutCustom.ini，将以下内容粘贴到文档中：<br>
[General]<br>
bUseThreadedAI=1<br>
INumHWThreads=4<br>
bPreemptivelyUnloadCells=1</p>
<p class="has-line-data" data-line-start="74" data-line-end="77">[BackgroundLoad]<br>
bBackgroundCellLoads=1<br>
bSelectivePurgeUnusedOnFastTravel=1</p>
<p class="has-line-data" data-line-start="78" data-line-end="92">[Display]<br>
fLightLODDefaultStartFade=10240.0<br>
fLightLODRange=10240.0<br>
fLightLODMinStartFade=10240.0<br>
fLightLODMaxStartFade=10240.0<br>
fShadowLODDefaultStartFade=200.0<br>
fShadowLODRange=200.0<br>
fShadowLODMinStartFade=100.0<br>
fShadowLODMaxStartFade=1000.0<br>
fSpecularLODDefaultStartFade=10240.0<br>
fSpecularLODRange=10240.0<br>
fSpecularLODMinStartFade=10240.0<br>
fSpecularLODMaxStartFade=10240.0<br>
iPresentInterval=0</p>
<p class="has-line-data" data-line-start="93" data-line-end="100">[Controls]<br>
fForegroundMouseAccelBase=0<br>
fForegroundMouseAccelTop=0<br>
fForegroundMouseBase=0<br>
fForegroundMouseMult=0<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</p>
<p class="has-line-data" data-line-start="101" data-line-end="103">[Grass]<br>
fGrassStartFadeDistance=17000</p>
<p class="has-line-data" data-line-start="104" data-line-end="107">[Audio]<br>
iAudioCacheSize=8192<br>
iMaxSizeForCachedSound=2048</p>
<ul>
<li class="has-line-data" data-line-start="108" data-line-end="109">将INumHWThreads更改为CPU所具有的线程数，可以打开同目录下的RendererInfo.txt ，对应最后一行 HW Thread Count后面的数字</li>
<li class="has-line-data" data-line-start="109" data-line-end="113">如果你不以16：9的宽高比运行游戏，可以删除<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</li>
</ul>
<p class="has-line-data" data-line-start="113" data-line-end="114">完成后保存关闭。</p>
<p class="has-line-data" data-line-start="115" data-line-end="116">五、重要前置</p>
<p class="has-line-data" data-line-start="117" data-line-end="123">前置补丁包<br>
<a href="https://pan.baidu.com/s/1MocEJs5hfTZFzTDpMlY3Bw">https://pan.baidu.com/s/1MocEJs5hfTZFzTDpMlY3Bw</a> 提取码: je8y<br>
特别安装说明：<br>
将压缩包内的所有内容解压到根目录，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行<br>
在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！<br>
此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，等待根目录下出现 FalloutNV.exe.Backup 后点击 OK 退出</p>
<ul>
<li class="has-line-data" data-line-start="124" data-line-end="126">个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md" title="前置说明">前置说明</a></strong></li>
</ul>
<p class="has-line-data" data-line-start="126" data-line-end="130"><strong>验证NVSE和4GBpatch是否运行：</strong><br>
在根目录下双击nvse_loader.exe运行游戏。进入游戏主菜单后，按 ~ 键打开控制台<br>
将getnvseversion输入控制台并按Enter键，控制台应报告 NVSE version: 5<br>
将getislaa输入控制台并按Enter键，控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="131" data-line-end="133">如果没有，请检查前置包是否正确安装</li>
</ul>
<p class="has-line-data" data-line-start="133" data-line-end="134"><strong>验证完成后都通过NVSE进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="134" data-line-end="135">通过Steam或GOG验证游戏文件完整性将撤消4GBpatch补丁</p>
</blockquote>
<p class="has-line-data" data-line-start="136" data-line-end="137">六、最终测试及可选选项</p>
<p class="has-line-data" data-line-start="138" data-line-end="139">至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：</p>
<ul>
<li class="has-line-data" data-line-start="140" data-line-end="141">确保选择了合适的画质选项，之后通过NVSE进行游戏</li>
<li class="has-line-data" data-line-start="141" data-line-end="142">启动一个新存档，快速通过医生的教程</li>
<li class="has-line-data" data-line-start="142" data-line-end="143">离开医生的房间后，打开pipboy检查各个选项是否有问题</li>
<li class="has-line-data" data-line-start="143" data-line-end="145">在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</li>
</ul>
<hr>
<p class="has-line-data" data-line-start="147" data-line-end="148">以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。</p>
