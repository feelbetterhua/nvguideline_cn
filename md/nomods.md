<p class="has-line-data" data-line-start="0" data-line-end="1">一、游戏安装</p>
<p class="has-line-data" data-line-start="2" data-line-end="5">1.常用术语：<br>
根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em><br>
Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></p>
<p class="has-line-data" data-line-start="6" data-line-end="8">2.禁用叠加层：<br>
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li class="has-line-data" data-line-start="8" data-line-end="9">Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li class="has-line-data" data-line-start="9" data-line-end="11">GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>
</ul>
<p class="has-line-data" data-line-start="11" data-line-end="14">3.运行游戏以初始化ini文件：<br>
从根文件夹运行 FalloutNVLauncher.exe<br>
弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="15" data-line-end="17">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li>
</ul>
<p class="has-line-data" data-line-start="17" data-line-end="19">选择 Options<br>
确认游戏检测到并正确使用你的GPU，并选择了合适画质。</p>
<ul>
<li class="has-line-data" data-line-start="19" data-line-end="21">如果没有正确识别GPU，请手动选择并调整画质选项</li>
</ul>
<p class="has-line-data" data-line-start="21" data-line-end="23">根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。<br>
单击 OK，然后单击 PLAY 进入游戏，进入主菜单后检查后没有异常就退出游戏。</p>
<p class="has-line-data" data-line-start="24" data-line-end="25">二、汉化安装</p>
<p class="has-line-data" data-line-start="26" data-line-end="34">首先请确保可以正常进入游戏，下载汉化补丁<br>
<a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv<br>
双击汉化补丁进行安装，一路点击下一步。<br>
<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。<br>
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简介安装，<strong>只需要汉化必须文件</strong>。<br>
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1<br>
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置<br>
<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="35" data-line-end="36">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="36" data-line-end="37">然后勾选 2 所有的框，<strong>保持 3 中的三个数字不变</strong></li>
<li class="has-line-data" data-line-start="37" data-line-end="39">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="39" data-line-end="41"><strong>为exe文件添加排除数据执行保护：</strong><br>
右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>
<p class="has-line-data" data-line-start="42" data-line-end="47">GOG版汉化后必需文件：<br>
<a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7<br>
安装说明：<br>
将压缩包内的文件解压到根目录<br>
（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<blockquote>
<p class="has-line-data" data-line-start="47" data-line-end="48">汉化补丁使用Steam版的exe文件替换了原文件，因此打上补丁的GOG版就相当于Steam版</p>
</blockquote>
<p class="has-line-data" data-line-start="49" data-line-end="50">进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容及汉化是否有问题。</p>
<p class="has-line-data" data-line-start="51" data-line-end="52">三、重要前置</p>
<p class="has-line-data" data-line-start="53" data-line-end="58">NVSE<br>
<a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a><br>
特别安装说明：<br>
单击 Download (stable version 5.1b4) 旁边的链接进行下载<br>
将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录</p>
<p class="has-line-data" data-line-start="59" data-line-end="63">前置补丁包<br>
<a href="https://pan.baidu.com/s/1eiF8xBpgxPUn6neF-Q5ltw">https://pan.baidu.com/s/1eiF8xBpgxPUn6neF-Q5ltw</a> 提取码: m5zf<br>
特别安装说明：<br>
将压缩包内的所有内容解压到Data文件夹</p>
<p class="has-line-data" data-line-start="64" data-line-end="67">FalloutCustom.ini优化<br>
特别安装说明：<br>
将压缩包内 FalloutCustom.ini 解压到 <em>文档/My Games/FalloutNV</em></p>
<p class="has-line-data" data-line-start="68" data-line-end="76">4GBpatch<br>
<a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h<br>
特殊安装说明：<br>
将压缩包内的 4gb_patch.exe 解压到根目录<br>
请确保 <strong>没有</strong> 运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行<br>
在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！<br>
此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，稍等一会<br>
在根目录出现 FalloutNV.exe.Backup 之后点击 OK 退出</p>
<p class="has-line-data" data-line-start="77" data-line-end="82"><strong>验证NVSE和4GBpatch是否运行：</strong><br>
打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行<br>
进入游戏主菜单后，按 ~ 键打开控制台<br>
将getnvseversion输入控制台并按Enter键<br>
控制台应报告 NVSE version: 5</p>
<ul>
<li class="has-line-data" data-line-start="82" data-line-end="84">如果没有，请检查NVSE是否已正确安装并重试</li>
</ul>
<p class="has-line-data" data-line-start="84" data-line-end="86">将getislaa输入控制台并按Enter键<br>
控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="86" data-line-end="87">如果控制台报告 GetisLAA &gt;&gt; 0.0000，则说明补丁未正确安装</li>
<li class="has-line-data" data-line-start="87" data-line-end="88">如果控制台报告 GetisLAA &gt;&gt; 1.0000，则修补程序已正确安装但无法正常运行</li>
<li class="has-line-data" data-line-start="88" data-line-end="90">如果控制台报告错误消息，则表示未正确安装JIP LN NVSE</li>
</ul>
<p class="has-line-data" data-line-start="90" data-line-end="91"><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="91" data-line-end="92">通过Steam或GOG验证您的游戏文件将撤消4GBpatch补丁</p>
</blockquote>
<p class="has-line-data" data-line-start="93" data-line-end="94">以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
