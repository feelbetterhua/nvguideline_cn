<p>一、游戏安装</p>

<p>安装后首次运行游戏以初始化ini文件：</p>

<p>从根文件夹运行 FalloutNVLauncher.exe</p>

<p>弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>

<ul><li>如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li></ul>

<p>选择 Options</p>

<p>确认游戏检测到并正确使用你的GPU，并选择了合适画质。</p>

<ul><li>如果没有正确识别GPU，请手动选择并调整画质选项</li></ul>

<p>根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。</p>

<p>单击 OK，然后单击 PLAY 进入游戏，进入主菜单后检查后没有异常就退出游戏。</p>

<blockquote><p>常用术语：</p><p>根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em></p><p>Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></p></blockquote>

<p>二、汉化安装</p>

<p>首先请确保可以正常进入游戏，下载汉化补丁</p>

<p><a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv</p>

<p>双击汉化补丁进行安装，一路点击下一步。</p>

<p><strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。</p>

<p>在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简介安装，<strong>只需要汉化必须文件</strong>。</p>

<p>点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1</p>

<p><img alt="fnvtools_full" title="fnvtools_full" src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/fnvtools_full.jpg"/></p>

<ul><li>点击FNVTools中的 INI设置和优化 ，然后勾选和图中 2 一样的选项</li><li>在 3 中选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭INI设置和优化。</li><li>点击 MOD管理 在弹出的框中勾选 5 所示的插件，并调整到和图中一样的顺序，调整完成后关闭MOD管理，最后退出FNVTools。</li></ul>

<p><strong>为exe文件添加排除数据执行保护：</strong></p>

<p>右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>

<p>GOG版汉化后必需文件：</p>

<p><a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7</p>

<p>安装说明：</p>

<p>将压缩包内的文件解压到根目录</p>

<p>（文件来源于网络，没有GOG版无法验证是否起作用）</p>

<blockquote><p>汉化补丁使用Steam版的exe文件替换了原文件，因此打上补丁的GOG版就相当于Steam版</p></blockquote>

<p>此时汉化安装完成，进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。</p>

<ul><li>如果汉化完成后进入游戏闪退，尝试先关闭数据执行保护，即在上面的步骤中选择 仅为基本Windows程序和服务启动DEP，重启后查看游戏是否能正常打开，可以则重新为exe文件添加排除数据执行保护。</li></ul>

<p>三、重要前置</p>

<p>NVSE</p>

<p><a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a></p>

<p>特别安装说明：</p>

<p>单击 Download (stable version 5.1b4) 旁边的链接进行下载</p>

<p>将压缩包内 nvse<em>5</em>1_beta4 文件夹中的所有内容解压到根目录</p>

<p>前置补丁包</p>

<p><a href="https://pan.baidu.com/s/1yvHtlDNZk2h1nghIrApj9Q">https://pan.baidu.com/s/1yvHtlDNZk2h1nghIrApj9Q</a> 提取码: 9cma</p>

<p>特别安装说明：</p>

<p>将压缩包内的所有内容解压到Data文件夹</p>

<p>FalloutCustom.ini优化</p>

<p>[https://pan.baidu.com/s/1tDoZ7RVdOKm9<em>eztzCff-Q](https://pan.baidu.com/s/1tDoZ7RVdOKm9</em>eztzCff-Q) 提取码: zg5k</p>

<p>特别安装说明：</p>

<p>将压缩包内 FalloutCustom.ini 解压到 <em>文档/My Games/FalloutNV</em></p>

<p>解压完成后导航到 <em>文档/My Games/FalloutNV</em> ，打开刚解压的 FalloutCustom.ini</p>

<p>将 INumHWThreads 后面的数字修改为CPU所具有的线程数，如果不清楚则打开同目录下的 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</p>

<p>修改完成后保存并退出</p>

<p>4GBpatch</p>

<p><a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h</p>

<p>特殊安装说明：</p>

<p>将压缩包内的 4gb_patch.exe 解压到根目录</p>

<p>请确保 <strong>没有</strong> 运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行</p>

<p>在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！</p>

<p>此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，等待根目录出现 FalloutNV.exe.Backup 之后点击 OK 退出</p>

<p><strong>验证NVSE和4GBpatch是否运行：</strong></p>

<p>打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行</p>

<p>进入游戏主菜单后，按 ~ 键打开控制台</p>

<p>将getnvseversion输入控制台并按Enter键</p>

<p>控制台应报告 NVSE version: 5</p>

<ul><li>如果没有，请检查NVSE是否已正确安装并重试</li></ul>

<p>将getislaa输入控制台并按Enter键</p>

<p>控制台应该报告 GetisLAA &amp;gt;&amp;gt; 2.0000</p>

<ul><li>如果控制台报告 GetisLAA &amp;gt;&amp;gt; 0.0000，则说明补丁未正确安装</li><li>如果控制台报告 GetisLAA &amp;gt;&amp;gt; 1.0000，则修补程序已正确安装但无法正常运行</li><li>如果控制台报告错误消息，则表示未正确安装JIP LN NVSE</li></ul>

<p><strong>验证完成，之后都使用NVSE进行游戏</strong></p>

<blockquote><p>通过Steam或GOG验证游戏文件完整性将撤消4GBpatch补丁</p></blockquote>

<p>四、最终测试及可选选项</p>

<p>至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：</p>

<ul><li>确保选择了合适的画质选项，之后使用NVSE进行游戏</li><li>启动一个新存档，快速通过医生的教程</li><li>离开医生的房间后，打开pipboy检查各个选项是否有问题</li><li>在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</li></ul>

<p>这里是一些 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/md/display.md" title="可选选项">可选选项</a></strong> ，根据需求找到相应部分设置：</p>

<ul><li>如果游戏时有画面撕裂的问题，参照<strong>防撕裂设置</strong></li><li>如果需要游戏以无边框全屏的方式运行(防止切出游戏时卡死)，参照<strong>伪全屏设置</strong></li><li>如果要以超过60帧运行游戏，参照<strong>高帧率设置</strong></li><li>如果要使用ENB以及NVR的截图功能，阅读<strong>有关ENB与NVR的说明</strong></li></ul>

<p>正常按指南完整做到了每一个步骤，并选择了合适的画质与分辨率，游戏应没有卡顿并可以长时间运行不跳出。如果遇到任何问题，尝试先判断是否完全按指南进行设置。指南无法解决的问题，请先尝试百度解决方法，也可以回复进行询问，我尽可能回答。</p>

<hr/>

<p>以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
