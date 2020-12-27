<p>一、安装设置</p>
<p>1.系统设置：
如果之前卸载过新维加斯，<strong>请确保删除所有了游戏文件、相关存档并清除注册表残余</strong>。如果使用Windows 10系统，请修改以下设置：</p>
<ul>
<li>关闭系统自带的游戏模式</li>
<li>单独添加英语作为第二语言，并在游戏时确保切换到英语键盘。</li>

</ul>
<p><strong>安装所有需要的Microsoft VC++ Redistributable Packages</strong>，如果没有请下载以下压缩包并安装里面的所有文件
  <a href='https://pan.baidu.com/s/1Z2qHznIQXqfGuY2Sg1l9tQ'>https://pan.baidu.com/s/1Z2qHznIQXqfGuY2Sg1l9tQ</a> 提取码: 678q</p>
<p>常用目录：</p>
<ul>
<li>根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em></li>
<li>Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></li>

</ul>
<p><strong>3.禁用叠加层</strong>：
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li>Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li>GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>

</ul>
<p>4.首次运行以初始化ini文件：
<strong>在Steam或GOG中启动游戏，等待其完成初始化设置</strong>。完成后弹出Detecting Video Hardware的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li>如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行</li>

</ul>
<p>选择 Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质（建议不要选择最低画质）。
根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。单击 OK，然后单击 PLAY 进入游戏。进入主菜单后没有异常就可以退出游戏。</p>
<p>二、汉化安装</p>
<p>本指南使用民间汉化第六版，首先请确保可以正常进入游戏，然后下载汉化补丁
<a href='https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA'>https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv
双击汉化补丁进行安装，一路点击下一步。
<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简洁安装，<strong>只需要汉化必须文件</strong>。
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置
<img src="https://s1.ax1x.com/2020/07/07/UFhJVH.jpg" referrerpolicy="no-referrer" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li>首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li>然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong></li>
<li>在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>

</ul>
<p>GOG版汉化后必需文件：
<a href='https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ'>https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7
特殊安装说明：
将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<blockquote><p>汉化补丁使用了Steam版的exe文件并进行了修改，打上补丁的GOG版就相当于Steam版。
天邈汉化使用原版exe文件，目前天邈插件尚不完善，<strong>不推荐使用天邈与民间汉化混装的模式</strong>。</p>
</blockquote>
<p>此时汉化已经完成，进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。</p>
<p>四、调整FalloutCustom.ini
导航到 文档/My Games/FalloutNV，新建一个文本文档，重命名为FalloutCustom.ini
打开FalloutCustom.ini，将以下内容粘贴到文档中：
[General]
bUseThreadedAI=1
INumHWThreads=4
bPreemptivelyUnloadCells=1</p>
<p>[BackgroundLoad]
bBackgroundCellLoads=1
bSelectivePurgeUnusedOnFastTravel=1</p>
<p>[Display]
bFull Screen=1
iPresentInterval=1</p>
<p>[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0
fXenonVertLookSpeed=1200.0000
fXenonHorizLookSpeed=1500.0000</p>
<p>[Grass]
fGrassStartFadeDistance=7000</p>
<p>[Audio]
iAudioCacheSize=8192
iMaxSizeForCachedSound=1024</p>
<ul>
<li>将INumHWThreads更改为CPU所具有的线程数，可以打开同目录下的RendererInfo.txt ，对应最后一行 HW Thread Count后面的数字</li>
<li>如果使用G/Free-sync，则iPresentInterval可以设置为0</li>

</ul>
<p>完成后保存关闭。</p>
<p>五、重要前置</p>
<p>前置补丁包
<a href='https://pan.baidu.com/s/1GvKqkBfxCLWwPzoNb9BDpg' target='_blank' class='url'>https://pan.baidu.com/s/1GvKqkBfxCLWwPzoNb9BDpg</a> 提取码：tyg1
特别安装说明：
在安装前，请确保安装了所有需要的Microsoft VC++ Redistributable Packages(见第一步)
将压缩包内的所有内容解压到根目录，并在出现提示时选择覆盖，解压后nvse_loader.exe应该与FalloutNV.exe在同一目录。
对exe文件进行4gbPatch：</p>
<p><strong>针对修改版exe文件(民间汉化，目前本指南使用)</strong>：
导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行
在弹出的窗口中双击选择 FalloutNV.exe ，等待根目录下出现 FalloutNV.exe.Backup 后点击 OK 退出</p>
<p><strong>针对原版exe文件(天邈汉化，本指南没有使用)</strong>：
导航到根目录，右键单击 FalloutNVpatch.exe ，选择 以管理员身份运行
弹出的窗口中应该显示 FalloutNV.exe patched! ，按键盘上的任意键退出</p>
<ul>
<li>个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 <strong><a href='https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md' title='前置说明'>前置说明</a></strong></li>

</ul>
<p><strong>验证NVSE和4GBpatch是否运行：</strong>
在根目录下双击nvse_loader.exe运行游戏。进入游戏主菜单后，按 ~ 键打开控制台
将getnvseversion输入控制台并按Enter键，控制台应报告 NVSE version: 5
将getislaa输入控制台并按Enter键，控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li>如果没有，请检查前置包是否正确安装</li>

</ul>
<p><strong>验证完成后，不要在Steam/GOG内运行游戏，只通过NVSE(nvse_loader.exe)进行游戏</strong></p>
<blockquote><p>使用民间汉化后，运行游戏不再需要强制打开Steam，如果需要成就请提前打开平台
通过Steam或GOG验证游戏文件完整性可以恢复原版exe文件，但会撤消4GBpatch补丁</p>
</blockquote>
<p>七、最终测试</p>
<p>至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：</p>
<ul>
<li>确保选择了合适的画质选项，之后通过NVSE进行游戏</li>
<li>启动一个新存档，快速通过医生的教程</li>
<li>离开医生的房间后，打开pipboy检查各个选项是否有问题</li>
<li>在游戏中花费至少10分钟做任何事情以确保游戏顺利进行</li>

</ul>
<hr />
<p>以上是基础汉化的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。</p>
