<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="2019_0"></a>2019年新维加斯入门指南</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3"><a href="http://github.com/feelbetterhua/nvguideline_cn">github.com/feelbetterhua/nvguideline_cn</a></p>
<hr>
<p class="has-line-data" data-line-start="6" data-line-end="7"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/intro_pic.jpg?raw=true" alt="intro" title="intro"></p>
<p class="has-line-data" data-line-start="8" data-line-end="9"><strong>2019年了，新维加斯不应该是这个游戏体验</strong></p>
<p class="has-line-data" data-line-start="10" data-line-end="11">本指南旨在建立一种一站式的入门指导，帮助你了解游玩新维加斯需要的准备工作。并整合最新的优化配置选项，使你以最丝滑的方式体验废土的旅程。本指南内容主要基于外网一个MOD指南Viva New Vegas，根据中文补丁的安装修改一些流程。原指南地址：<em><a href="http://vivanewvegas.github.io">vivanewvegas.github.io</a></em></p>
<p class="has-line-data" data-line-start="12" data-line-end="13">首先说一下结论，我使用一台笔记本电脑，配置为</p>
<ul>
<li class="has-line-data" data-line-start="14" data-line-end="15">CPU：I7-5500U</li>
<li class="has-line-data" data-line-start="15" data-line-end="16">内存：8GB 1666Mhz DDR3</li>
<li class="has-line-data" data-line-start="16" data-line-end="17">显卡：GTX950m 2G DDR3</li>
<li class="has-line-data" data-line-start="17" data-line-end="18">硬盘：128GB SATA3.0 SSD</li>
<li class="has-line-data" data-line-start="18" data-line-end="20">系统：Win10 LTSC 2019</li>
</ul>
<p class="has-line-data" data-line-start="20" data-line-end="21">设置优化后可以使原版游戏在1080P，最高画质下以60帧稳定运行。即使加了大量MOD后也可以在稍低分辨率下运行5~6个小时不跳出。<strong>对于网上流传新维加斯不适合在Win10上运行，以目前的情况看大部分问题都得到了解决。</strong></p>
<p class="has-line-data" data-line-start="22" data-line-end="23">一、一般信息</p>
<p class="has-line-data" data-line-start="24" data-line-end="25">关于游戏你需要了解的信息有：</p>
<p class="has-line-data" data-line-start="26" data-line-end="27">请先确保自己的电脑能够运行新维加斯，游戏运行不稳定也可能是硬件配置造成的。当然通过本指南，你可以最大化发挥硬件的资源。</p>
<p class="has-line-data" data-line-start="28" data-line-end="29">对于版本的问题，本指南只推荐Steam或GOG的正版终极版，也就是全DLC的版本。本指南测试用的版本为纯净的正版，其他版本不保证也有效果。</p>
<p class="has-line-data" data-line-start="30" data-line-end="31">本指南专门为汉化编写了相关内容，中文补丁使用民间汉化第6版，这是目前最完善的一个版本。 <strong>注意它只支持终极版或者安装了所有dlc的版本。</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="32" data-line-end="33">汉化补丁替换了FalloutNV.exe，替换的exe来自Steam版。而GOG版与Steam版的区别是GOG版对exe文件进行了优化，所以如果想玩中文的话Steam版更方便一些。</p>
</blockquote>
<p class="has-line-data" data-line-start="34" data-line-end="35">对于本指南你需要了解的信息有：</p>
<p class="has-line-data" data-line-start="36" data-line-end="37">入门指南只针对原版游戏进行优化，不会添加或修改游戏内容，后续可能会编写其他部分内容。</p>
<p class="has-line-data" data-line-start="38" data-line-end="39">该指南的目的是让所人都可以快速上手，所以用纯操作指南的方式编写，只要<strong>按照顺序</strong>执行步骤即可以达到效果。</p>
<p class="has-line-data" data-line-start="40" data-line-end="41">本指南完成所需的时间并不漫长，强烈建议完整读一遍指南，或至少读完整个步骤后再开始安装和设置。</p>
<p class="has-line-data" data-line-start="42" data-line-end="43">如果你是第一次使用本指南，<strong>建议你每进行完一个大步骤后简单的测试游戏</strong>，这样可以在出错误后更快找到问题所在。</p>
<blockquote>
<p class="has-line-data" data-line-start="44" data-line-end="45">虽然本指南不需要太多相关经验即可上手，但一些基础常识如Windows文件系统、解压缩以及INI文件的编辑修改等还是建议有所了解。</p>
</blockquote>
<p class="has-line-data" data-line-start="46" data-line-end="47">二、系统设置</p>
<p class="has-line-data" data-line-start="48" data-line-end="49">如果你使用Win10，建议你更新到较新的版本。Win10可以设置优化的选项很多，这里主要说三点影响较大的：</p>
<ul>
<li class="has-line-data" data-line-start="50" data-line-end="51">关闭系统自带的游戏模式，对于新维加斯来说该模式会造成不稳定，具体方法请自行寻找。</li>
<li class="has-line-data" data-line-start="51" data-line-end="52">Win10自带的输入法十分影响游戏，请单独添加英语作为第二键盘，并在游戏前按alt+shift切换到英语键盘。</li>
<li class="has-line-data" data-line-start="52" data-line-end="54">关掉通知，以及其他可能在后台弹出对话框/提示的软件。新维加斯在切回桌面时会卡死，如果必须要频繁切回桌面，后面会有解决方法，但建议在游玩过程中不要切换窗口。</li>
</ul>
<p class="has-line-data" data-line-start="54" data-line-end="55">对于笔记本电脑，请确保电源选项选择正确，如高性能或卓越性能。而对于所用用户，请更新到较新的显卡驱动，并保证有足够的硬盘空间。</p>
<p class="has-line-data" data-line-start="56" data-line-end="57"><strong>如果你之前安装过新维加斯后卸载，为保证本指南的能正常安装，请确保删除所有游戏文件、相关存档及注册表残余。</strong> 方法是卸载后再搜索Fallout NV相关的文件及文件夹并删除，运行注册表清理工具删除相关残余条目。</p>
<blockquote>
<p class="has-line-data" data-line-start="58" data-line-end="59">注册表清理工具推荐 Wise Registry Cleaner 和 CCleaner</p>
</blockquote>
<p class="has-line-data" data-line-start="60" data-line-end="61">三、游戏安装</p>
<p class="has-line-data" data-line-start="62" data-line-end="66">1.安装参数：<br>
<strong>游戏本体确保安装在Steam默认文件夹之外(C:/Program Files(x86)/Steam)</strong><br>
所有modding工具必须安装在默认Windows文件夹之外（如Program Files，Program Files（x86）和Documents）。<br>
Fallout New Vegas和Mod Organizer 2必须安装在同一个盘上，但不要将Mod Organizer 2和mod文件夹安装在游戏根目录下。</p>
<p class="has-line-data" data-line-start="67" data-line-end="68">2.常用术语：</p>
<p class="has-line-data" data-line-start="69" data-line-end="70">根文件夹(根目录)：<em>Steam / steamapps / common / Fallout New Vegas</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas</em></p>
<p class="has-line-data" data-line-start="71" data-line-end="72">Data文件夹：<em>Steam / steamapps / common / Fallout New Vegas / Data</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas / Data</em></p>
<p class="has-line-data" data-line-start="73" data-line-end="74">MO2：Mod Organizer 2（将很快安装）</p>
<p class="has-line-data" data-line-start="75" data-line-end="76"><strong>3.禁用叠加层：</strong></p>
<p class="has-line-data" data-line-start="77" data-line-end="78">需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<p class="has-line-data" data-line-start="79" data-line-end="80">如Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</p>
<p class="has-line-data" data-line-start="81" data-line-end="82">4.设置Fallout New Vegas Modding文件夹：</p>
<p class="has-line-data" data-line-start="83" data-line-end="84">modding文件夹将充当安装的所有工具的主目录，以及任何备份/屏幕截图等。从现在开始，此文件夹将被称为Modding文件夹。</p>
<p class="has-line-data" data-line-start="85" data-line-end="86">在与Fallout New Vegas相同盘上的默认Windows文件夹和游戏根目录之外创建一个新文件夹，将它命名_Fallout NV Modding_，创建两个子文件夹名为_Backups_和_Tools_</p>
<p class="has-line-data" data-line-start="87" data-line-end="88">备份整个游戏，将 Fallout New Vegas 文件夹复制到刚才创建的 Backups 中。</p>
<p class="has-line-data" data-line-start="89" data-line-end="90">5.生成新鲜的.INI文件：</p>
<p class="has-line-data" data-line-start="91" data-line-end="92">从根文件夹运行 FalloutNVLauncher.exe</p>
<p class="has-line-data" data-line-start="93" data-line-end="94">弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="95" data-line-end="97">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li>
</ul>
<p class="has-line-data" data-line-start="97" data-line-end="98">选择 Options</p>
<p class="has-line-data" data-line-start="99" data-line-end="100">确认游戏检测到并正确使用你的GPU，并选择了合适画质。如果没有正确识别GPU，请手动选择并调整画质选项，建议选择Medium。</p>
<p class="has-line-data" data-line-start="101" data-line-end="102">根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。</p>
<p class="has-line-data" data-line-start="103" data-line-end="104">单击 OK，然后单击 PLAY 进入游戏。进入主菜单后点击 Quit 然后 Exit Game 退出游戏。</p>
<ul>
<li class="has-line-data" data-line-start="105" data-line-end="107">如果无法正常进入游戏，请参照步骤五为exe文件添加排除数据执行保护，再进行尝试</li>
</ul>
<p class="has-line-data" data-line-start="107" data-line-end="108">四、一些工具</p>
<p class="has-line-data" data-line-start="109" data-line-end="110">1.Microsoft VC ++ 2013</p>
<p class="has-line-data" data-line-start="111" data-line-end="112"><a href="http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe">http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe</a></p>
<p class="has-line-data" data-line-start="113" data-line-end="114">特别安装说明：</p>
<p class="has-line-data" data-line-start="115" data-line-end="116">运行安装程序并按照给定的说明操作</p>
<p class="has-line-data" data-line-start="117" data-line-end="118">如果您收到已安装该程序的消息，请退出安装程序</p>
<ul>
<li class="has-line-data" data-line-start="119" data-line-end="121">FNV和4GB Patcher所需的库</li>
</ul>
<p class="has-line-data" data-line-start="121" data-line-end="122">2.Microsoft VC ++ 2015,2017,2019</p>
<p class="has-line-data" data-line-start="123" data-line-end="124"><a href="https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads">https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads</a></p>
<p class="has-line-data" data-line-start="125" data-line-end="126">特别安装说明：</p>
<p class="has-line-data" data-line-start="127" data-line-end="128">单击Visual Studio 2017标题下的x86：vc_redist.x86.exe和x64：vc_redist.x64.exe链接</p>
<p class="has-line-data" data-line-start="129" data-line-end="130">运行两个.exe文件并按照说明安装它们</p>
<p class="has-line-data" data-line-start="131" data-line-end="132">如果您收到已安装该程序的消息，请退出安装程序</p>
<p class="has-line-data" data-line-start="133" data-line-end="134">如果您不在Windows 10上，则可能还需要遵循以下说明</p>
<p class="has-line-data" data-line-start="135" data-line-end="136"><a href="https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows">https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows</a></p>
<ul>
<li class="has-line-data" data-line-start="137" data-line-end="139">Mod Organizer 2和NVGE所需的库</li>
</ul>
<p class="has-line-data" data-line-start="139" data-line-end="140">3.Mod Organizer 2</p>
<p class="has-line-data" data-line-start="141" data-line-end="142"><a href="https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg">https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg</a> 提取码: hh7g</p>
<p class="has-line-data" data-line-start="143" data-line-end="144">特别安装说明：</p>
<p class="has-line-data" data-line-start="145" data-line-end="146">下载 Mod Organizer 2 (Archive) 主文件</p>
<p class="has-line-data" data-line-start="147" data-line-end="148">在之前Fallout NV Modding文件夹下的Tools文件夹新建一个文件夹命名为Mod Organizer 2</p>
<p class="has-line-data" data-line-start="149" data-line-end="150">解压缩所有文件到 Mod Organizer 2 文件夹，进入目录右键单击 ModOrganizer.exe 并选择 属性</p>
<p class="has-line-data" data-line-start="151" data-line-end="152">导航到 兼容性 选项卡，然后选中 以管理员身份运行此程序</p>
<p class="has-line-data" data-line-start="153" data-line-end="154">选择 应用 然后单击确定退出</p>
<p class="has-line-data" data-line-start="155" data-line-end="156">退出后暂时不要打开ModOrganizer.exe，后面会在配置时打开</p>
<ul>
<li class="has-line-data" data-line-start="157" data-line-end="159">迄今为止新维加斯最佳mod管理器，利用虚拟文件系统保持Data文件夹干净</li>
</ul>
<p class="has-line-data" data-line-start="159" data-line-end="160">4.MO2插件</p>
<p class="has-line-data" data-line-start="161" data-line-end="162"><a href="https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA">https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA</a> 提取码: 28pm</p>
<p class="has-line-data" data-line-start="163" data-line-end="164">特别安装说明：</p>
<p class="has-line-data" data-line-start="165" data-line-end="166">将压缩包中的以下文件夹和文件解压至 Mod Organizer 2/plugins 文件夹：</p>
<ul>
<li class="has-line-data" data-line-start="167" data-line-end="168">/data</li>
<li class="has-line-data" data-line-start="168" data-line-end="169"><a href="http://pySyncModOrder.py">pySyncModOrder.py</a></li>
<li class="has-line-data" data-line-start="169" data-line-end="171"><a href="http://pyMergePluginsHide.py">pyMergePluginsHide.py</a></li>
</ul>
<blockquote>
<p class="has-line-data" data-line-start="171" data-line-end="172">当需要更新Mod Organizer 2时：将新版压缩包解压到Mod Organizer 2文件夹中，并在出现提示时覆盖。按照上述说明以管理员身份运行程序，重新下载并安装MO2插件。</p>
</blockquote>
<p class="has-line-data" data-line-start="173" data-line-end="174">五、汉化安装</p>
<p class="has-line-data" data-line-start="175" data-line-end="176">首先请确保可以正常进入游戏，汉化补丁请放在安全位置。</p>
<p class="has-line-data" data-line-start="177" data-line-end="178"><a href="https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw">https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw</a> 提取码: ecdg</p>
<p class="has-line-data" data-line-start="179" data-line-end="180">双击汉化补丁进行安装，一路点击下一步。</p>
<p class="has-line-data" data-line-start="181" data-line-end="182"><strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。</p>
<p class="has-line-data" data-line-start="183" data-line-end="184">在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简介安装，<strong>只需要汉化必须文件</strong>。</p>
<p class="has-line-data" data-line-start="185" data-line-end="186">点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1</p>
<p class="has-line-data" data-line-start="187" data-line-end="188">点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置</p>
<p class="has-line-data" data-line-start="189" data-line-end="190"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="191" data-line-end="192">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="192" data-line-end="193">然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong> (下面的优化会涉及此项)</li>
<li class="has-line-data" data-line-start="193" data-line-end="195">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="195" data-line-end="196">为exe文件添加排除数据执行保护：</p>
<p class="has-line-data" data-line-start="197" data-line-end="198">右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>
<p class="has-line-data" data-line-start="199" data-line-end="200">此时汉化已完成，Steam版可以直接双击FalloutNV.exe进入游戏，GOG版本需要下载破解的steam_api.dll放入根目录才能进入游戏。进入游戏，主界面和菜单应该都已汉化。**点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启。**后退到主菜单，开始新游戏测试游戏内容及汉化是否有问题。</p>
<p class="has-line-data" data-line-start="201" data-line-end="202">六、Mod Organizer 2配置及INI优化</p>
<p class="has-line-data" data-line-start="203" data-line-end="204">1.配置Mod Organizer 2：</p>
<p class="has-line-data" data-line-start="205" data-line-end="206">运行ModOrganizer.exe</p>
<p class="has-line-data" data-line-start="207" data-line-end="208">从名为 Choose Instance 的弹出窗口中，选择 Portable</p>
<p class="has-line-data" data-line-start="209" data-line-end="210">从弹出窗口 Please select the game to manage，选择 New Vegas</p>
<p class="has-line-data" data-line-start="211" data-line-end="212">如果未显示New Vegas选项，请选择 Browse…，然后导航到根文件夹并选择FalloutNV.exe</p>
<p class="has-line-data" data-line-start="213" data-line-end="214">如果有一个名为 INI file is read-only 的窗口，请选择 Yes</p>
<p class="has-line-data" data-line-start="215" data-line-end="216">从弹出窗口 Show Tutorial?，选择 No</p>
<p class="has-line-data" data-line-start="217" data-line-end="218">从弹出窗口 Register?，选择 Yes</p>
<p class="has-line-data" data-line-start="219" data-line-end="220">进入主界面</p>
<p class="has-line-data" data-line-start="221" data-line-end="222">点击顶部的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic">，在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)</p>
<p class="has-line-data" data-line-start="223" data-line-end="224">点击 OK 软件切换成中文</p>
<p class="has-line-data" data-line-start="225" data-line-end="226">如果未选中右栏中的所有插件，请右键单击右栏空白处并选择 全部启用</p>
<p class="has-line-data" data-line-start="227" data-line-end="228">按照下图中的顺序改变左栏和右栏中的加载顺序</p>
<p class="has-line-data" data-line-start="229" data-line-end="230"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/order_pic.jpg?raw=true" alt="order_pic" title="order_pic"></p>
<ul>
<li class="has-line-data" data-line-start="231" data-line-end="233">如果您的游戏是GOG版本，则加载顺序中可能存在FalloutNV_lang.esp ，请导航到/Data文件夹并将其删除</li>
</ul>
<p class="has-line-data" data-line-start="233" data-line-end="234">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic">，导航到&quot; 路径&quot;选项卡</p>
<p class="has-line-data" data-line-start="235" data-line-end="236">如果您使用SSD或空间很小的HDD，请将 下载 路径设置为具有足够空间的某个位置</p>
<p class="has-line-data" data-line-start="237" data-line-end="238">以下选项只在你有Nexus账户时才设置，没有的可以跳过</p>
<ul>
<li class="has-line-data" data-line-start="239" data-line-end="240">在 N网 选项卡中，单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面</li>
<li class="has-line-data" data-line-start="240" data-line-end="241">选择 Authorise</li>
<li class="has-line-data" data-line-start="241" data-line-end="243">等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器</li>
</ul>
<p class="has-line-data" data-line-start="243" data-line-end="244">点击 OK 退出MO2中的设置菜单，如果MO2提示你重启，你应该选择 Yes</p>
<p class="has-line-data" data-line-start="245" data-line-end="246">2.在Mod Organizer 2中创建新配置文件：</p>
<p class="has-line-data" data-line-start="247" data-line-end="248">Mod Organizer 2的配置文件功能允许在不同的mod配置之间轻松切换，可以通过左栏上方的下拉菜单选择配置文件。</p>
<p class="has-line-data" data-line-start="249" data-line-end="250">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2profile_pic.jpg?raw=true" alt="profile_pic" title="profile_pic"></p>
<p class="has-line-data" data-line-start="251" data-line-end="252">单击Default配置文件，然后选择重命名</p>
<p class="has-line-data" data-line-start="253" data-line-end="254">输入Vanilla作为新名称</p>
<p class="has-line-data" data-line-start="255" data-line-end="256">选中 Vanilla 配置文件，选择复制</p>
<p class="has-line-data" data-line-start="257" data-line-end="258">输入Core作为新名称，然后单击 OK</p>
<p class="has-line-data" data-line-start="259" data-line-end="260">选择 Core 配置文件并选中下方的 使用特定的ini (第二项，应该已经选中) 和 自动档案无效化</p>
<p class="has-line-data" data-line-start="261" data-line-end="262">关闭配置文件窗口，可能会报错提示缺少ini文件，点击 OK 即可</p>
<p class="has-line-data" data-line-start="263" data-line-end="264">3.调整FalloutCustom.ini：</p>
<p class="has-line-data" data-line-start="265" data-line-end="266">确保目前选择的配置文件为 Core</p>
<p class="has-line-data" data-line-start="267" data-line-end="268">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器</p>
<p class="has-line-data" data-line-start="269" data-line-end="270">导航到 falloutcustom.ini 选项卡，该选项卡应为空白</p>
<p class="has-line-data" data-line-start="271" data-line-end="276">将以下内容粘贴到框中：<br>
[General]<br>
bUseThreadedAI=1<br>
INumHWThreads=4<br>
bPreemptivelyUnloadCells=1</p>
<p class="has-line-data" data-line-start="277" data-line-end="280">[BackgroundLoad]<br>
bBackgroundCellLoads=1<br>
bSelectivePurgeUnusedOnFastTravel=1</p>
<p class="has-line-data" data-line-start="281" data-line-end="295">[Display]<br>
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
<p class="has-line-data" data-line-start="296" data-line-end="303">[Controls]<br>
fForegroundMouseAccelBase=0<br>
fForegroundMouseAccelTop=0<br>
fForegroundMouseBase=0<br>
fForegroundMouseMult=0<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</p>
<p class="has-line-data" data-line-start="304" data-line-end="306">[Grass]<br>
fGrassStartFadeDistance=17000</p>
<p class="has-line-data" data-line-start="307" data-line-end="310">[Audio]<br>
iAudioCacheSize=8192<br>
iMaxSizeForCachedSound=2048</p>
<ul>
<li class="has-line-data" data-line-start="311" data-line-end="312">将INumHWThreads更改为CPU所具有的线程数，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="312" data-line-end="316">如果你不以16：9的宽高比运行游戏，可以删除<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</li>
</ul>
<p class="has-line-data" data-line-start="316" data-line-end="317">完成后点击 保存 ，然后关闭INI编辑器。</p>
<p class="has-line-data" data-line-start="318" data-line-end="319">七、BethINI</p>
<p class="has-line-data" data-line-start="320" data-line-end="321">BethINI相当于一个第三方启动器，可以修改画质与其他选项，并带有INI优化。BethINI与Mod Organizer2联合使用可以方便的管理INI文件。</p>
<p class="has-line-data" data-line-start="322" data-line-end="323"><a href="https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw">https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw</a> 提取码: jw7j</p>
<p class="has-line-data" data-line-start="324" data-line-end="326">注意事项：<br>
BethINI容易被防病毒软件标记为误报，所以最好请其添加到将杀毒软件的白名单中。<strong>请注意，不要通过Mod Organizer 2运行，也不要在Mod Organizer 2打开时运行BethINI。</strong></p>
<p class="has-line-data" data-line-start="327" data-line-end="328">安装使用说明：</p>
<ol>
<li class="has-line-data" data-line-start="329" data-line-end="330">运行前请确保已运行过FalloutNVLauncher.exe并生成了相应的INI文件</li>
<li class="has-line-data" data-line-start="330" data-line-end="331"><strong>请确保Mod Organizer 2关闭</strong>，解压缩文件到 <em>/Fallout NV Modding/Tools</em> 文件夹，进入并运行 BethINI.exe</li>
<li class="has-line-data" data-line-start="331" data-line-end="332">在弹出的窗口中下拉选择 Fallout New Vegas ，等待进入程序。</li>
<li class="has-line-data" data-line-start="332" data-line-end="333">进入程序后导航到 Setup 选项卡， <strong>取消选择</strong>下方的全部选项方框。之后在 Mod Organizer 一栏下拉菜单中选择 Browse ,在弹出的框中导航到 Mod Organizer 2 文件夹并双击选择 ModOrganizer.exe</li>
<li class="has-line-data" data-line-start="333" data-line-end="334">在 INI Path 一栏下拉菜单中选择您现在使用的Mod Organizer 2配置文件，如 ModOrganizer&gt;Core 。在弹出对话框中选择 确定 。此时会弹出对话框提示BethINI要重新启动，点击 确定 。重启后会弹出名为 Modify Custom INIs? 对话框， <strong>此时选择 否</strong> 。重新进入BethINI后导航到 Setup 选项卡，请确保全部5个选择框都没有选择。</li>
<li class="has-line-data" data-line-start="334" data-line-end="335">导航到 Basic 选项卡，在 Presets 栏中选择 BethINI Presets ，再选择 Recommended Tweaks ，程序会自动优化相应的INI文件，之后请根据配置在 Poor 到 Ultra 中选择合适的画质选项。</li>
<li class="has-line-data" data-line-start="335" data-line-end="336">选择完画质后在 Display 一栏中选择合适的分辨率，如果没有需要的分辨率则可以手动输入。可以自行选择 Antialiasing 和 Anisotropic Filtering 倍数。最后选择最下方的 Enable File Selection (如果已经选择则不用管)，确定一切选择正确后点击 Save and Exit 退出。</li>
<li class="has-line-data" data-line-start="336" data-line-end="338">等待程序关闭后导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，查看下方 Shader Package 后的数字。如果是19，则不需要进一步修改。如果不是19，请导航到游戏根目录下 <em>data/Shaders</em> 文件夹找到对应Shader Package后数字的文件，如 shaderpackage013.sdp ，将其命名为shaderpackage013.sdp.backup。之后把 shaderpackage019.sdp 复制一份到其他位置，将其重命名为shaderpackage013.sdp，再剪切回原文件夹。</li>
</ol>
<p class="has-line-data" data-line-start="338" data-line-end="339"><strong>在使用了BethINI之后，请不要再运行FalloutNVLauncher.exe，也不要通过Steam启动新维加斯。如果在以后的游戏流程中需要修改画质及其他选项，请阅读指南最后有关BethINI的说明。</strong></p>
<p class="has-line-data" data-line-start="340" data-line-end="341">八、重要前置</p>
<p class="has-line-data" data-line-start="342" data-line-end="343">曾经新维加斯比较流行的前置NVSR 和 Zan AutoPurge Crash Protector 已经废弃。这两个插件会对游戏稳定性产生负面影响。如果你是老玩家，看到本指南中没有安装以上两个插件，请不要疑惑。下面开始安装指南：</p>
<p class="has-line-data" data-line-start="344" data-line-end="345">NVSE</p>
<p class="has-line-data" data-line-start="346" data-line-end="347"><a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a></p>
<p class="has-line-data" data-line-start="348" data-line-end="349">特别安装说明：</p>
<p class="has-line-data" data-line-start="350" data-line-end="351">单击 Download (stable version 5.1b4) 旁边的链接进行下载</p>
<p class="has-line-data" data-line-start="352" data-line-end="353">将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录</p>
<ul>
<li class="has-line-data" data-line-start="354" data-line-end="356">扩展引擎的脚本功能，对于大多数mod来说都是必不可少的</li>
</ul>
<p class="has-line-data" data-line-start="356" data-line-end="357">前置补丁包</p>
<p class="has-line-data" data-line-start="358" data-line-end="359"><a href="https://pan.baidu.com/s/1xGYFRKGcgazDRnmNru8-2w">https://pan.baidu.com/s/1xGYFRKGcgazDRnmNru8-2w</a> 提取码: ycvs</p>
<p class="has-line-data" data-line-start="360" data-line-end="361">特别安装说明：</p>
<p class="has-line-data" data-line-start="362" data-line-end="363">打开Mod Organizer2，单击顶栏的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2install_pic.PNG?raw=true" alt="install_pic" title="install_pic">，导航到下载好的压缩包，双击选择它。</p>
<p class="has-line-data" data-line-start="364" data-line-end="365">在弹出的窗口中确定名称为 Utilities ，点击 确定 安装补丁包。</p>
<p class="has-line-data" data-line-start="366" data-line-end="367">安装完成后该补丁会在左栏显示，选中 Utilities 前的方框以激活Mod。</p>
<ul>
<li class="has-line-data" data-line-start="368" data-line-end="370">个人制作的前置补丁包，包含必要前置补丁及修改好的优化文件。具体内容详见https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md</li>
</ul>
<p class="has-line-data" data-line-start="370" data-line-end="371">4GBpatch</p>
<p class="has-line-data" data-line-start="372" data-line-end="373"><a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h</p>
<p class="has-line-data" data-line-start="374" data-line-end="375">特殊安装说明：</p>
<p class="has-line-data" data-line-start="376" data-line-end="377">将压缩包内的 4gb_patch.exe 解压到根目录</p>
<p class="has-line-data" data-line-start="378" data-line-end="379">请确保 <strong>没有</strong>运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行</p>
<p class="has-line-data" data-line-start="380" data-line-end="381">在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！</p>
<p class="has-line-data" data-line-start="382" data-line-end="383">此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，之后点击 OK 退出。</p>
<ul>
<li class="has-line-data" data-line-start="384" data-line-end="386">使游戏能够识别大地址，这意味着它可以使用4GB RAM而不是2GB</li>
</ul>
<p class="has-line-data" data-line-start="386" data-line-end="387"><strong>验证NVSE和4GBpatch是否运行：</strong></p>
<p class="has-line-data" data-line-start="388" data-line-end="389">打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行</p>
<p class="has-line-data" data-line-start="390" data-line-end="391">进入游戏主菜单后，按 ~ 键打开控制台</p>
<p class="has-line-data" data-line-start="392" data-line-end="393">将getnvseversion输入控制台并按Enter键</p>
<p class="has-line-data" data-line-start="394" data-line-end="395">控制台应报告 NVSE version: 5</p>
<ul>
<li class="has-line-data" data-line-start="396" data-line-end="398">如果没有，请检查NVSE是否已正确安装并重试</li>
</ul>
<p class="has-line-data" data-line-start="398" data-line-end="399">将getislaa输入控制台并按Enter键</p>
<p class="has-line-data" data-line-start="400" data-line-end="401">控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="402" data-line-end="403">如果控制台报告 GetisLAA &gt;&gt; 0.0000，则说明补丁未正确安装</li>
<li class="has-line-data" data-line-start="403" data-line-end="404">如果控制台报告 GetisLAA &gt;&gt; 1.0000，则修补程序已正确安装但无法正常运行，尝试以管理员身份运行</li>
<li class="has-line-data" data-line-start="404" data-line-end="406">如果控制台报告错误消息，则表示您未正确安装JIP LN NVSE</li>
</ul>
<p class="has-line-data" data-line-start="406" data-line-end="407"><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="408" data-line-end="409">通过Steam或GOG验证您的游戏文件将撤消4GBpatch补丁</p>
</blockquote>
<p class="has-line-data" data-line-start="410" data-line-end="411">九、显示设置</p>
<p class="has-line-data" data-line-start="412" data-line-end="413">由于Gamebryo的物理特性与帧速率相关，因此FPS上限必须为60或更低。</p>
<p class="has-line-data" data-line-start="414" data-line-end="415"><strong>仅适用于具有NVIDIA GPU的用户：NVIDIA Profile Inspector</strong></p>
<p class="has-line-data" data-line-start="416" data-line-end="417"><a href="https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA">https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA</a> 提取码: qwfa</p>
<p class="has-line-data" data-line-start="418" data-line-end="419">特别安装说明：</p>
<p class="has-line-data" data-line-start="420" data-line-end="421">将压缩包解压到根目录以外的安全位置</p>
<p class="has-line-data" data-line-start="422" data-line-end="423">运行 NVidiaProfileInspectorDmWPortable.exe</p>
<p class="has-line-data" data-line-start="424" data-line-end="425">如果有弹出窗口，请单击是</p>
<p class="has-line-data" data-line-start="426" data-line-end="427">从左上角的Profiles：下拉列表中，选择Fallout - New Vegas</p>
<p class="has-line-data" data-line-start="428" data-line-end="429">在 2. - Sync and Refresh 部分中，更改以下内容：</p>
<ul>
<li class="has-line-data" data-line-start="430" data-line-end="431">Frame Rate Limiter - 59 FPS</li>
<li class="has-line-data" data-line-start="431" data-line-end="433">Maximum pre-rendered frames - 1</li>
</ul>
<blockquote>
<p class="has-line-data" data-line-start="433" data-line-end="434">如果遇到画面撕裂的问题，请将 Vertical Sync 一项设置为 Force on</p>
</blockquote>
<p class="has-line-data" data-line-start="435" data-line-end="436">在5. - Common部分中，更改以下内容：</p>
<ul>
<li class="has-line-data" data-line-start="437" data-line-end="439">Power management mode - Prefer maximum performance</li>
</ul>
<p class="has-line-data" data-line-start="439" data-line-end="440">单击右上角的 Apply changes 按钮，然后退出</p>
<p class="has-line-data" data-line-start="441" data-line-end="442"><strong>仅适用于使用AMD GPU的用户：调整AMD Radeon设置</strong></p>
<p class="has-line-data" data-line-start="443" data-line-end="444">(注：本人使用NVIDIA GPU，这一步没有亲自验证，翻译仅供参考)</p>
<p class="has-line-data" data-line-start="445" data-line-end="446">右键单击桌面并选择AMD Radeon Settings</p>
<p class="has-line-data" data-line-start="447" data-line-end="448">在&quot; 游戏&quot;选项卡中，选择 Fallout New Vegas 配置文件</p>
<p class="has-line-data" data-line-start="449" data-line-end="450">在&quot; 配置文件图形&quot;选项卡中，更改以下内容</p>
<p class="has-line-data" data-line-start="451" data-line-end="452">启用 冷却（FPS）</p>
<p class="has-line-data" data-line-start="453" data-line-end="454">将Chill Min和Chill Max设置为58</p>
<blockquote>
<p class="has-line-data" data-line-start="455" data-line-end="457">如果遇到画面撕裂的问题，请将 等待垂直刷新 一项设置为 增强同步<br>
如果不能选择增强同步，请选择 始终开启</p>
</blockquote>
<p class="has-line-data" data-line-start="458" data-line-end="459">点击左下角的主页按钮（设置应自动保存），并确保在配置文件名称下方显示&quot;已启用 &quot;字样</p>
<p class="has-line-data" data-line-start="460" data-line-end="461">如果没有，请单击配置文件名称右侧的三个垂直点，然后选择启用配置文件</p>
<p class="has-line-data" data-line-start="462" data-line-end="463">伪全屏设置(<strong>如无特殊要求建议跳过</strong>)：</p>
<p class="has-line-data" data-line-start="464" data-line-end="465">该步骤可以游戏运行在窗口模式下，此时切出游戏应该不会卡死。但游戏帧数会降低，请根据需要选择是否设置。</p>
<p class="has-line-data" data-line-start="466" data-line-end="467">OneTweak：</p>
<p class="has-line-data" data-line-start="468" data-line-end="469"><a href="https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg">https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg</a> 提取码: m3b3</p>
<p class="has-line-data" data-line-start="470" data-line-end="471">特别安装说明：</p>
<p class="has-line-data" data-line-start="472" data-line-end="473">使用Mod Organizer2安装OneTweak，方法同步骤八中前置补丁包的安装。</p>
<p class="has-line-data" data-line-start="474" data-line-end="475">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器</p>
<p class="has-line-data" data-line-start="476" data-line-end="477">导航到 falloutcustom.ini 选项卡，在 [Display] 部分下添加以下内容</p>
<ul>
<li class="has-line-data" data-line-start="478" data-line-end="480">bFull Screen=0</li>
</ul>
<p class="has-line-data" data-line-start="480" data-line-end="481">十、最终测试</p>
<p class="has-line-data" data-line-start="482" data-line-end="483">至此基础游戏的设置及优化已全部完成，请按照以下步骤进行测试：</p>
<p class="has-line-data" data-line-start="484" data-line-end="485">通过MO2运行游戏</p>
<p class="has-line-data" data-line-start="486" data-line-end="487">启动一个新存档，快速通过Doc Mitchell所在的教程</p>
<p class="has-line-data" data-line-start="488" data-line-end="489">离开医生的房间后，打开pipboy检查各个选项是否有问题</p>
<p class="has-line-data" data-line-start="490" data-line-end="491">在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</p>
<ul>
<li class="has-line-data" data-line-start="492" data-line-end="493">如果按指南完整做到了每一个步骤，并选择了合适的画质与分辨率，此时游戏应没有卡顿并可以长时间运行不跳出。</li>
<li class="has-line-data" data-line-start="493" data-line-end="494">如果有任何问题，尝试先判断是否完全按指南进行设置。如果确定步骤没有问题，请先调低画质及分辨率再进行测试(但尽量不要以最低画质运行)。</li>
<li class="has-line-data" data-line-start="494" data-line-end="496">如果问题依旧存在，请尝试百度解决方法。也可以回复进行询问，我尽可能回答。</li>
</ul>
<p class="has-line-data" data-line-start="496" data-line-end="497">以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
<hr>
<p class="has-line-data" data-line-start="500" data-line-end="503">有关BethINI的说明：<br>
BethINI相当于一个第三方的FalloutNVLauncher，但拥有更好的预设及更多的选项，它们的共同点是都通过修改INI文件来工作。而Mod Organizer 2会为每一个配置文件单独创建&quot;虚拟&quot;的INI文件，这时FalloutNVLauncher修改原生INI文件就对从MO2中启动的游戏不起作用。<br>
通过将BethINI与Mod Organizer 2链接，BethINI可以直接管理MO2中某个配置文件的INI，不再修改原生INI。 <strong>所以今后的游戏过程中如需改变画质就直接使用BethINI，只要确保选择了正确的MO2配置文件即可(一定不要同时运行BethINI和MO2)。</strong></p>
<p class="has-line-data" data-line-start="504" data-line-end="507">有关ENB与NVGE的说明：<br>
使用4GBpatch时正常安装ENB，如果你在使用NVGE-New Vegas Reload的同时使用ENB，请打开根目录下的 enblocal.ini 并将其中的 SpeedHack=true 改为 SpeedHack=false ，以保证两者相互兼容。<br>
NVGE自带截图功能，并且截图不包含UI，快捷键是F11。如需带UI截图，可以按 PrtScr 键截取。NVGE的截图保存在根目录下的 Screenshots 文件夹，带UI的截图保存在游戏根目录。</p>