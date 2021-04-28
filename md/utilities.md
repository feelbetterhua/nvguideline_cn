<h3>一、安装设置</h3>
<h4>1.系统设置：</h4>
<p><strong>安装所有需要的Microsoft VC++ Redistributable Packages</strong>(下载链接均来自微软官方)</p>
<ul>
<li><p>Microsoft VC++ 2013</p>
<p>x86: <a href='https://aka.ms/highdpimfc2013x86chs'>vc_redist.x86.exe</a></p>
<p>x64: <a href='https://aka.ms/highdpimfc2013x64chs'>vc_redist.x64.exe</a></p>
</li>
<li><p>Microsoft VC++ 2015-2019 </p>
<p>x86: <a href='https://aka.ms/vs/16/release/vc_redist.x86.exe'>vc_redist.x86.exe</a></p>
<p>x64: <a href='https://aka.ms/vs/16/release/vc_redist.x64.exe'>vc_redist.x64.exe</a></p>
</li>

</ul>
<p>如果之前卸载过新维加斯，<strong>请确保删除所有了游戏文件、相关存档并清除注册表残余</strong>。如果使用Windows 10系统，请单独添加英语作为第二语言，并在游戏时确保切换到英语键盘。</p>
<p>指南中使用到的常用目录：</p>
<ul>
<li>根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em></li>
<li>Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></li>

</ul>
<h4>2.禁用叠加层：</h4>
<p>需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li>Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li>GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>

</ul>
<h4>3.首次运行以初始化ini文件：</h4>
<p><strong>首次安装完成后，在Steam或GOG中启动游戏，等待其完成初始化设置</strong>。完成后弹出Detecting Video Hardware的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li>如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行</li>

</ul>
<p>选择 Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质<strong>（不要选择最低画质）</strong>。</p>
<p>根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。单击 OK，然后单击 PLAY 进入游戏。进入主菜单后没有异常就可以退出游戏。</p>
<h3>二、汉化安装</h3>
<p>本指南使用民间汉化第六版，首先请确保可以正常进入游戏，然后下载汉化补丁</p>
<p><a href='https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA' target='_blank' class='url'>https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv</p>
<p>双击汉化补丁进行安装，一路点击下一步。<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。</p>
<p>在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简洁安装，<strong>只需要汉化必须文件</strong>。点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1</p>
<p>点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后在下方 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 或 中文宋体小字二选一)，点击会后弹出对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1</p>
<p>GOG版汉化后必需文件 </p>
<p><a href='https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ' target='_blank' class='url'>https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7</p>
<p>将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<blockquote><p>汉化补丁使用了Steam版的exe文件并进行了修改，打上补丁的GOG版就相当于Steam版。
天邈汉化使用原版exe文件，目前天邈插件尚不完善，<strong>不推荐使用天邈与民间汉化混装的模式</strong>。</p>
</blockquote>
<p>此时汉化已经完成，<strong>直接点击根目录下的 FalloutNV.exe 进入游戏</strong>，主界面和菜单应该都已汉化。</p>
<p><strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。</p>
<h3>三、重要前置</h3>
<h4>1.FalloutCustom.ini优化</h4>
<p><a href='https://pan.baidu.com/s/1QqaXomJtGfgw7fx3R-vGGw' target='_blank' class='url'>https://pan.baidu.com/s/1QqaXomJtGfgw7fx3R-vGGw</a> 提取码：mfnv</p>
<p>将压缩包内的文件解压至 <em>文档/My Games/FalloutNV</em>，完成后导航到该目录打开FalloutCustom.ini，将 INumHWThreads 后的数字更改为CPU所具有的线程数。</p>
<blockquote><p>可以打开同目录下的RendererInfo.txt ，查看最后一行 HW Thread Count 后面的数字</p>
</blockquote>
<h4>2.前置补丁包</h4>
<p><a href='https://pan.baidu.com/s/1QTfHCnq8c7c334jHFtcvtQ' target='_blank' class='url'>https://pan.baidu.com/s/1QTfHCnq8c7c334jHFtcvtQ</a> 提取码：mfnv </p>
<p><strong>在安装前，请确保安装了所有需要的Microsoft VC++ Redistributable Packages(见第一步)</strong></p>
<p>将压缩包内的所有内容解压到根目录，并在出现提示时选择覆盖，解压后nvse_loader.exe应该与FalloutNV.exe在同一目录。</p>
<p>对exe文件进行4gbPatch：</p>
<ul>
<li><strong>针对修改版exe文件(民间汉化，目前本指南使用)</strong>：
导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行。在弹出的窗口中双击选择 FalloutNV.exe ，等待根目录下出现 FalloutNV.exe.Backup 后点击 OK 退出</li>
<li>针对原版exe文件(天邈汉化)：
导航到根目录，右键单击 FalloutNVpatch.exe ，选择 以管理员身份运行。弹出的窗口中应该显示 FalloutNV.exe patched! ，按键盘上的任意键退出</li>

</ul>
<blockquote><p>个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 <strong><a href='https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md' title='前置说明'>前置说明</a></strong></p>
</blockquote>
<p><strong>验证NVSE和4GBpatch是否正常运行：</strong></p>
<p>在根目录下双击nvse_loader.exe运行游戏。进入游戏主菜单后，按 ~ 键打开控制台</p>
<p>此时控制台应显示xNVSE及JIP NVSE的版本，将getislaa输入控制台并按Enter键，控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li>如果没有正确显示版本，请检查前置包是否正确安装</li>
<li>如果没有报告GetisLAA &gt;&gt; 2.0000，请检查4GBpatch是否正确完成</li>

</ul>
<p><strong>验证完成后，不要在Steam/GOG内运行游戏，只通过NVSE(nvse_loader.exe)进行游戏</strong></p>
<blockquote><p>使用民间汉化后，运行游戏不再需要强制打开Steam，如果需要成就请提前打开平台
通过Steam或GOG验证游戏文件完整性可以恢复原版exe文件，但会撤消4GBpatch补丁</p>
</blockquote>
<hr />
<p>以上是基础汉化的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。</p>
