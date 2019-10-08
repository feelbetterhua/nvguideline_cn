<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="2019_0"></a>2019年新维加斯入门指南</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3"><a href="http://github.com/feelbetterhua/nvguideline_cn">github.com/feelbetterhua/nvguideline_cn</a></p>
<hr>
<p class="has-line-data" data-line-start="6" data-line-end="7"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/intro_pic.jpg?raw=true" alt="intro" title="intro"></p>
<p class="has-line-data" data-line-start="8" data-line-end="9"><strong>2019年了，新维加斯不应该是这个游戏体验</strong></p>
<p class="has-line-data" data-line-start="10" data-line-end="11">本指南旨在建立一种一站式的入门指导，帮助你了解游玩新维加斯需要的准备工作。并整合最新的优化配置选项，使你以最丝滑的方式体验废土的旅程。本指南内容主要基于外网一个MOD指南Viva New Vegas，根据中文补丁的安装修改一些流程。原指南地址：_ <a href="http://vivanewvegas.github.io">vivanewvegas.github.io</a>_</p>
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
<p class="has-line-data" data-line-start="30" data-line-end="31">本指南专门为汉化编写了相关内容，中文补丁使用民间汉化第5版，这是目前最完善的一个版本。 <strong>注意它只支持终极版或者安装了所有dlc的版本。</strong></p>
<p class="has-line-data" data-line-start="32" data-line-end="33">对于本指南你需要了解的信息有：</p>
<p class="has-line-data" data-line-start="34" data-line-end="35">入门指南只针对原版游戏进行优化，不会添加或修改游戏内容，后续可能会编写其他部分内容。</p>
<p class="has-line-data" data-line-start="36" data-line-end="37">该指南的目的是让所人都可以快速上手，所以用纯操作指南的方式编写，只要<strong>按照顺序</strong>执行步骤即可以达到效果。</p>
<p class="has-line-data" data-line-start="38" data-line-end="39">本指南完成所需的时间并不漫长，强烈建议完整读一遍指南，或至少读完整个步骤后再开始安装和设置。</p>
<p class="has-line-data" data-line-start="40" data-line-end="41">虽然本指南不需要太多相关经验即可上手，但一些基础常识如Windows文件系统、解压缩以及INI文件的编辑修改等还是建议有所了解。</p>
<p class="has-line-data" data-line-start="42" data-line-end="43">如果你是第一次使用本指南，<strong>建议你每进行完一个大步骤后简单的测试游戏</strong>，这样可以在出错误后更快找到问题所在。</p>
<p class="has-line-data" data-line-start="44" data-line-end="45">二、系统设置</p>
<p class="has-line-data" data-line-start="46" data-line-end="47">如果你使用Win10，建议你更新到较新的版本。Win10可以设置优化的选项很多，这里主要说三点影响较大的：</p>
<ul>
<li class="has-line-data" data-line-start="48" data-line-end="49">关闭系统自带的游戏模式，对于新维加斯来说该模式会造成不稳定，具体方法请自行寻找。</li>
<li class="has-line-data" data-line-start="49" data-line-end="50">Win10自带的输入法十分影响游戏，请单独添加英语作为第二键盘，并在游戏前按alt+shift切换到英语键盘。</li>
<li class="has-line-data" data-line-start="50" data-line-end="52">关掉通知，以及其他可能在后台弹出对话框/提示的软件。新维加斯在切回桌面时会卡死，如果必须要频繁切回桌面，后面会有解决方法，但建议在游玩过程中不要切换窗口。</li>
</ul>
<p class="has-line-data" data-line-start="52" data-line-end="53">对于笔记本电脑，请确保电源选项选择正确，如高性能或卓越性能。而对于所用用户，请更新到较新的显卡驱动，并保证有足够的硬盘空间。</p>
<p class="has-line-data" data-line-start="54" data-line-end="55"><strong>如果你之前安装过新维加斯后卸载，为保证本指南的能正常安装，请确保删除所有游戏文件、相关存档及注册表残余。</strong> 方法是卸载后再搜索Fallout NV相关的文件及文件夹并删除，运行注册表清理工具删除相关残余条目。</p>
<blockquote>
<p class="has-line-data" data-line-start="56" data-line-end="57">注册表清理工具推荐 Wise Registry Cleaner 和 CCleaner</p>
</blockquote>
<p class="has-line-data" data-line-start="58" data-line-end="59">三、游戏安装</p>
<p class="has-line-data" data-line-start="60" data-line-end="61">1.安装参数：</p>
<p class="has-line-data" data-line-start="62" data-line-end="63">所有modding工具必须安装在所有默认Windows文件夹之外（例如Program Files，Program Files（x86）和Documents）。Fallout New Vegas和Mod Organizer 2必须安装在同一个盘上，但不要将Mod Organizer 2和mod文件夹安装在Fallout New Vegas根目录下。</p>
<p class="has-line-data" data-line-start="64" data-line-end="65">2.常用术语：</p>
<p class="has-line-data" data-line-start="66" data-line-end="67">根文件夹(根目录)： <em>Steam / steamapps / common / Fallout New Vegas</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas</em></p>
<p class="has-line-data" data-line-start="68" data-line-end="69">Data文件夹： <em>Steam / steamapps / common / Fallout New Vegas / Data</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas / Data</em></p>
<p class="has-line-data" data-line-start="70" data-line-end="71">MO2：Mod Organizer 2（将很快安装）</p>
<p class="has-line-data" data-line-start="72" data-line-end="73"><strong>3.禁用叠加层：</strong></p>
<p class="has-line-data" data-line-start="74" data-line-end="75">需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<p class="has-line-data" data-line-start="76" data-line-end="77">如Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。这一步会使你无法使用Steam自带的截图功能，完成成就时也不会有右下角弹窗，但是还是非常建议你不要启动这一项，新维加斯游戏内有成就提示，后面也会介绍其他截图方式。</p>
<p class="has-line-data" data-line-start="78" data-line-end="79">4.设置Fallout New Vegas Modding文件夹：</p>
<p class="has-line-data" data-line-start="80" data-line-end="81">您的modding文件夹将充当您安装的所有工具的主目录，以及任何备份/屏幕截图等。从现在开始，此文件夹将被称为Modding文件夹。</p>
<p class="has-line-data" data-line-start="82" data-line-end="83">在与Fallout New Vegas安装相同的盘上的默认Windows文件夹之外的所选位置创建一个新文件夹，注意在根文件夹夹之外。将它命名为任何你喜欢的，如 <em>Fallout NV Modding</em>，并创建两个子文件夹名为 _Backups_和 <em>Tools</em></p>
<p class="has-line-data" data-line-start="84" data-line-end="85">备份整个游戏，将 Fallout New Vegas 文件夹复制到刚才创建的 Backups 中</p>
<p class="has-line-data" data-line-start="86" data-line-end="87">5.生成新鲜的.INI文件：</p>
<p class="has-line-data" data-line-start="88" data-line-end="89">从根文件夹运行 FalloutNVLauncher.exe</p>
<p class="has-line-data" data-line-start="90" data-line-end="91">弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="92" data-line-end="94">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li>
</ul>
<p class="has-line-data" data-line-start="94" data-line-end="95">选择 Options</p>
<p class="has-line-data" data-line-start="96" data-line-end="97">确认游戏检测到并正确使用你的GPU，并选择了合适画质。如果没有正确识别GPU，请手动选择并调整画质选项，最好以Medium或High为初始选项。</p>
<p class="has-line-data" data-line-start="98" data-line-end="99">根据你的偏好设置分辨率（启动器通常将其设置为低于最大分辨率的一个）</p>
<p class="has-line-data" data-line-start="100" data-line-end="101">注意 Antiailiasing 项可以设置为8 Samples（启动器最多将其设置为4 Samples）</p>
<p class="has-line-data" data-line-start="102" data-line-end="103">单击 OK，然后单击 PLAY 进入游戏。进入主菜单后点击 Quit 然后 Exit Game 退出游戏。</p>
<ul>
<li class="has-line-data" data-line-start="104" data-line-end="106">如果无法正常进入游戏，请参照步骤五为exe文件添加排除数据执行保护，再进行尝试</li>
</ul>
<p class="has-line-data" data-line-start="106" data-line-end="107">四、一些工具</p>
<p class="has-line-data" data-line-start="108" data-line-end="109">1.Microsoft VC ++ 2013</p>
<p class="has-line-data" data-line-start="110" data-line-end="111"><a href="http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe">http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe</a></p>
<p class="has-line-data" data-line-start="112" data-line-end="113">特别安装说明：</p>
<p class="has-line-data" data-line-start="114" data-line-end="115">运行安装程序并按照给定的说明操作</p>
<p class="has-line-data" data-line-start="116" data-line-end="117">如果您收到已安装该程序的消息，请退出安装程序</p>
<ul>
<li class="has-line-data" data-line-start="118" data-line-end="120">FNV和4GB Patcher所需的库</li>
</ul>
<p class="has-line-data" data-line-start="120" data-line-end="121">2.Microsoft VC ++ 2015,2017,2019</p>
<p class="has-line-data" data-line-start="122" data-line-end="123"><a href="https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads">https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads</a></p>
<p class="has-line-data" data-line-start="124" data-line-end="125">特别安装说明：</p>
<p class="has-line-data" data-line-start="126" data-line-end="127">单击Visual Studio 2017标题下的x86：vc_redist.x86.exe和x64：vc_redist.x64.exe链接</p>
<p class="has-line-data" data-line-start="128" data-line-end="129">运行两个.exe文件并按照说明安装它们</p>
<p class="has-line-data" data-line-start="130" data-line-end="131">如果您收到已安装该程序的消息，请退出安装程序</p>
<p class="has-line-data" data-line-start="132" data-line-end="133">如果您不在Windows 10上，则可能还需要遵循以下说明</p>
<p class="has-line-data" data-line-start="134" data-line-end="135"><a href="https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows">https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows</a></p>
<ul>
<li class="has-line-data" data-line-start="136" data-line-end="138">Mod Organizer 2和NVGE所需的库</li>
</ul>
<p class="has-line-data" data-line-start="138" data-line-end="139">3.Mod Organizer 2</p>
<p class="has-line-data" data-line-start="140" data-line-end="141"><a href="https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg">https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg</a> 提取码: hh7g</p>
<p class="has-line-data" data-line-start="142" data-line-end="143">特别安装说明：</p>
<p class="has-line-data" data-line-start="144" data-line-end="145">下载 Mod Organizer 2 (Archive) 主文件</p>
<p class="has-line-data" data-line-start="146" data-line-end="147">在之前Fallout NV Modding文件夹下的Tools文件夹新建一个文件夹命名为Mod Organizer 2</p>
<p class="has-line-data" data-line-start="148" data-line-end="149">解压缩所有文件到 Mod Organizer 2 文件夹，进入目录右键单击 ModOrganizer.exe 并选择 属性</p>
<p class="has-line-data" data-line-start="150" data-line-end="151">导航到 兼容性 选项卡，然后选中 以管理员身份运行此程序</p>
<p class="has-line-data" data-line-start="152" data-line-end="153">选择 应用 然后单击确定退出</p>
<p class="has-line-data" data-line-start="154" data-line-end="155">退出后暂时不要打开ModOrganizer.exe，后面会在配置时打开</p>
<ul>
<li class="has-line-data" data-line-start="156" data-line-end="158">迄今为止所有Bethesda游戏的最佳mod管理器，利用虚拟文件系统保持您的Data文件夹完全干净</li>
</ul>
<p class="has-line-data" data-line-start="158" data-line-end="159">4.MO2插件</p>
<p class="has-line-data" data-line-start="160" data-line-end="161"><a href="https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA">https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA</a> 提取码: 28pm</p>
<p class="has-line-data" data-line-start="162" data-line-end="163">特别安装说明：</p>
<p class="has-line-data" data-line-start="164" data-line-end="165">将压缩包中的以下文件夹和文件解压至 Mod Organizer 2/plugins 文件夹：</p>
<ul>
<li class="has-line-data" data-line-start="166" data-line-end="167">/data</li>
<li class="has-line-data" data-line-start="167" data-line-end="168"><a href="http://pySyncModOrder.py">pySyncModOrder.py</a></li>
<li class="has-line-data" data-line-start="168" data-line-end="170"><a href="http://pyMergePluginsHide.py">pyMergePluginsHide.py</a></li>
</ul>
<p class="has-line-data" data-line-start="170" data-line-end="171">5.正确更新Mod Organizer 2</p>
<p class="has-line-data" data-line-start="172" data-line-end="173">当发布新版本的Mod Organizer 2时：</p>
<p class="has-line-data" data-line-start="174" data-line-end="175">将新版压缩包解压到Mod Organizer 2文件夹中，并在出现提示时覆盖</p>
<p class="has-line-data" data-line-start="176" data-line-end="177">按照上述相同说明以管理员身份运行程序</p>
<p class="has-line-data" data-line-start="178" data-line-end="179">从上面重新下载并安装MO2插件</p>
<p class="has-line-data" data-line-start="180" data-line-end="181">五、汉化安装</p>
<p class="has-line-data" data-line-start="182" data-line-end="183">首先将下载好的汉化补丁放入游戏根目录</p>
<p class="has-line-data" data-line-start="184" data-line-end="185"><a href="https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw">https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw</a> 提取码: ecdg</p>
<p class="has-line-data" data-line-start="186" data-line-end="187">双击汉化补丁进行安装，一路点击下一步，在 选择组件 界面停下，反选所有选项，也就是只选择 汉化必须文件</p>
<p class="has-line-data" data-line-start="188" data-line-end="189">点击下一步进行安装(<strong>请注意目标位置是否为游戏所在目录</strong>)，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1</p>
<p class="has-line-data" data-line-start="190" data-line-end="191">点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置</p>
<p class="has-line-data" data-line-start="192" data-line-end="193"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="194" data-line-end="195">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="195" data-line-end="196">然后勾选 2 所有的框 ， <strong>保持 3 中的三个数字为默认</strong> (下面的优化会涉及此项)</li>
<li class="has-line-data" data-line-start="196" data-line-end="198">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="198" data-line-end="199">为exe文件添加排除数据执行保护：</p>
<p class="has-line-data" data-line-start="200" data-line-end="201">右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>
<p class="has-line-data" data-line-start="202" data-line-end="203">此时汉化已完成，Steam版可以直接双击FalloutNV.exe进入游戏，GOG版本需要下载破解的steam_api.dll放入根目录才能进入游戏。</p>
<blockquote>
<p class="has-line-data" data-line-start="204" data-line-end="205">汉化补丁替换了FalloutNV.exe，并且替换的exe来自Steam版。而GOG版与Steam版最大的区别是GOG版对exe文件进行了优化。所以如果想玩中文版的话建议直接买Steam版。</p>
</blockquote>
<p class="has-line-data" data-line-start="206" data-line-end="207">进入游戏，主界面和菜单应该都显示汉化。点击 选项-显示 ，滚轮滑倒最下，将 一般字幕 设置为开启。后退到主菜单，开始新游戏测试游戏内容及汉化是否有问题。</p>
<p class="has-line-data" data-line-start="208" data-line-end="209">六、Mod Organizer 2配置及INI优化</p>
<p class="has-line-data" data-line-start="210" data-line-end="211">1.配置Mod Organizer 2：</p>
<p class="has-line-data" data-line-start="212" data-line-end="213">运行ModOrganizer.exe</p>
<p class="has-line-data" data-line-start="214" data-line-end="215">从名为 Choose Instance 的弹出窗口中，选择 Portable</p>
<p class="has-line-data" data-line-start="216" data-line-end="217">从弹出窗口 Please select the game to manage，选择 New Vegas</p>
<p class="has-line-data" data-line-start="218" data-line-end="219">如果未显示New Vegas选项，请选择 Browse…，然后导航到根文件夹并选择FalloutNV.exe</p>
<p class="has-line-data" data-line-start="220" data-line-end="221">如果有一个名为 INI file is read-only 的窗口，请选择 Yes</p>
<p class="has-line-data" data-line-start="222" data-line-end="223">从弹出窗口 Show Tutorial?，选择 No</p>
<p class="has-line-data" data-line-start="224" data-line-end="225">从弹出窗口 Register?，选择 Yes</p>
<p class="has-line-data" data-line-start="226" data-line-end="227">进入主界面</p>
<p class="has-line-data" data-line-start="228" data-line-end="229">点击顶部的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic">，在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)</p>
<p class="has-line-data" data-line-start="230" data-line-end="231">点击 OK 软件切换成中文</p>
<p class="has-line-data" data-line-start="232" data-line-end="233">如果未选中右栏中的所有插件，请右键单击右栏空白处并选择 全部启用</p>
<p class="has-line-data" data-line-start="234" data-line-end="235">按照下图中的顺序改变左栏和右栏中的加载顺序</p>
<p class="has-line-data" data-line-start="236" data-line-end="237"><img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/order_pic.jpg?raw=true" alt="order_pic" title="order_pic"></p>
<ul>
<li class="has-line-data" data-line-start="238" data-line-end="240">如果您的游戏是GOG版本，则加载顺序中可能存在FalloutNV_lang.esp ，请导航到/Data文件夹并将其删除</li>
</ul>
<p class="has-line-data" data-line-start="240" data-line-end="241">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic">，导航到&quot; 路径&quot;选项卡</p>
<p class="has-line-data" data-line-start="242" data-line-end="243">如果您使用SSD或空间很小的HDD，请将 下载 路径设置为具有足够空间的某个位置</p>
<p class="has-line-data" data-line-start="244" data-line-end="245">以下选项只在你有Nexus账户时才设置，没有的可以跳过</p>
<ul>
<li class="has-line-data" data-line-start="246" data-line-end="247">在 N网 选项卡中，单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面</li>
<li class="has-line-data" data-line-start="247" data-line-end="248">选择 Authorise</li>
<li class="has-line-data" data-line-start="248" data-line-end="250">等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器</li>
</ul>
<p class="has-line-data" data-line-start="250" data-line-end="251">点击 OK 退出MO2中的设置菜单，如果MO2提示你重启，你应该选择 Yes</p>
<p class="has-line-data" data-line-start="252" data-line-end="253">2.在Mod Organizer 2中创建新配置文件：</p>
<p class="has-line-data" data-line-start="254" data-line-end="255">Mod Organizer 2的配置文件功能允许在不同的mod配置之间轻松切换，可以通过左栏上方的下拉菜单选择配置文件。</p>
<p class="has-line-data" data-line-start="256" data-line-end="257">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2profile_pic.jpg?raw=true" alt="profile_pic" title="profile_pic"></p>
<p class="has-line-data" data-line-start="258" data-line-end="259">单击Default配置文件，然后选择重命名</p>
<p class="has-line-data" data-line-start="260" data-line-end="261">输入Vanilla作为新名称</p>
<p class="has-line-data" data-line-start="262" data-line-end="263">选中 Vanilla 配置文件，选择复制</p>
<p class="has-line-data" data-line-start="264" data-line-end="265">输入Core作为新名称，然后单击 OK</p>
<p class="has-line-data" data-line-start="266" data-line-end="267">选择 Core 配置文件并选中下方的 使用特定的ini (第二项，应该已经选中) 和 自动档案无效化</p>
<p class="has-line-data" data-line-start="268" data-line-end="269">关闭配置文件窗口，可能会报错提示缺少ini文件，点击 OK 即可</p>
<p class="has-line-data" data-line-start="270" data-line-end="271">3.调整FalloutCustom.ini：</p>
<p class="has-line-data" data-line-start="272" data-line-end="273">确保目前选择的配置文件为 Core</p>
<p class="has-line-data" data-line-start="274" data-line-end="275">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器</p>
<p class="has-line-data" data-line-start="276" data-line-end="277">导航到 falloutcustom.ini 选项卡，该选项卡应为空白</p>
<p class="has-line-data" data-line-start="278" data-line-end="279">将以下内容粘贴到框中：</p>
<p class="has-line-data" data-line-start="280" data-line-end="281">[General]</p>
<p class="has-line-data" data-line-start="282" data-line-end="283">bUseThreadedAI=1</p>
<p class="has-line-data" data-line-start="284" data-line-end="285">INumHWThreads=4</p>
<p class="has-line-data" data-line-start="286" data-line-end="287">bPreemptivelyUnloadCells=1</p>
<p class="has-line-data" data-line-start="288" data-line-end="289">[BackgroundLoad]</p>
<p class="has-line-data" data-line-start="290" data-line-end="291">bBackgroundCellLoads=1</p>
<p class="has-line-data" data-line-start="292" data-line-end="293">bSelectivePurgeUnusedOnFastTravel=1</p>
<p class="has-line-data" data-line-start="294" data-line-end="295">[Display]</p>
<p class="has-line-data" data-line-start="296" data-line-end="297">fLightLODDefaultStartFade=10240.0</p>
<p class="has-line-data" data-line-start="298" data-line-end="299">fLightLODRange=10240.0</p>
<p class="has-line-data" data-line-start="300" data-line-end="301">fLightLODMinStartFade=10240.0</p>
<p class="has-line-data" data-line-start="302" data-line-end="303">fLightLODMaxStartFade=10240.0</p>
<p class="has-line-data" data-line-start="304" data-line-end="305">fShadowLODDefaultStartFade=200.0</p>
<p class="has-line-data" data-line-start="306" data-line-end="307">fShadowLODRange=200.0</p>
<p class="has-line-data" data-line-start="308" data-line-end="309">fShadowLODMinStartFade=100.0</p>
<p class="has-line-data" data-line-start="310" data-line-end="311">fShadowLODMaxStartFade=1000.0</p>
<p class="has-line-data" data-line-start="312" data-line-end="313">fSpecularLODDefaultStartFade=10240.0</p>
<p class="has-line-data" data-line-start="314" data-line-end="315">fSpecularLODRange=10240.0</p>
<p class="has-line-data" data-line-start="316" data-line-end="317">fSpecularLODMinStartFade=10240.0</p>
<p class="has-line-data" data-line-start="318" data-line-end="319">fSpecularLODMaxStartFade=10240.0</p>
<p class="has-line-data" data-line-start="320" data-line-end="321">iPresentInterval=0</p>
<p class="has-line-data" data-line-start="322" data-line-end="323">[Controls]</p>
<p class="has-line-data" data-line-start="324" data-line-end="325">fForegroundMouseAccelBase=0</p>
<p class="has-line-data" data-line-start="326" data-line-end="327">fForegroundMouseAccelTop=0</p>
<p class="has-line-data" data-line-start="328" data-line-end="329">fForegroundMouseBase=0</p>
<p class="has-line-data" data-line-start="330" data-line-end="331">fForegroundMouseMult=0</p>
<p class="has-line-data" data-line-start="332" data-line-end="333">fXenonVertLookSpeed=1200.0000</p>
<p class="has-line-data" data-line-start="334" data-line-end="335">fXenonHorizLookSpeed=1500.0000</p>
<p class="has-line-data" data-line-start="336" data-line-end="337">[Grass]</p>
<p class="has-line-data" data-line-start="338" data-line-end="339">fGrassStartFadeDistance=17000</p>
<p class="has-line-data" data-line-start="340" data-line-end="341">[Audio]</p>
<p class="has-line-data" data-line-start="342" data-line-end="343">iAudioCacheSize=8192</p>
<p class="has-line-data" data-line-start="344" data-line-end="345">iMaxSizeForCachedSound=2048</p>
<ul>
<li class="has-line-data" data-line-start="346" data-line-end="347">将INumHWThreads更改为CPU所具有的线程数，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="347" data-line-end="351">如果你不以16：9的宽高比运行游戏，可以删除<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</li>
</ul>
<p class="has-line-data" data-line-start="351" data-line-end="352">完成后点击 保存 ，然后关闭INI编辑器。</p>
<p class="has-line-data" data-line-start="353" data-line-end="354">七、使用BethINI优化管理INI文件</p>
<p class="has-line-data" data-line-start="355" data-line-end="356">BethINI试图统一管理由Bethesda创建的游戏的INI配置文件，同时优化您的游戏设置以获得最佳图形保真度和性能。它目前支持Oblivion，Skyrim，Skyrim特别版，Fallout 3，Fallout New Vegas和Fallout 4.</p>
<p class="has-line-data" data-line-start="357" data-line-end="358"><a href="https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw">https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw</a> 提取码: jw7j</p>
<p class="has-line-data" data-line-start="359" data-line-end="360">用BethINI的优点：</p>
<ul>
<li class="has-line-data" data-line-start="361" data-line-end="362">它会自动将您的INI文件重新排序为合理的顺序，使其更容易导航以进行手动调整。</li>
<li class="has-line-data" data-line-start="362" data-line-end="363">它自动修复常见错误，包括一些可能导致CTD的错误。</li>
<li class="has-line-data" data-line-start="363" data-line-end="364">它会自动检测您已安装的mod并在适当的情况下进行mod作者推荐的更改。</li>
<li class="has-line-data" data-line-start="364" data-line-end="365">它的预设在图形保真度和性能方面（95％的时间）优于通过游戏启动器创建的官方预设。</li>
<li class="has-line-data" data-line-start="365" data-line-end="366">它允许修改比通过本机游戏设置可访问的更多设置，并提供每个设置及其功能的说明。</li>
<li class="has-line-data" data-line-start="366" data-line-end="368">它会自动备份您的INI文件。</li>
</ul>
<p class="has-line-data" data-line-start="368" data-line-end="369">注意事项：</p>
<p class="has-line-data" data-line-start="370" data-line-end="371">BethINI standalone是一个便携式应用程序。你可以在任何地方运行它，简单的解压并运行。不幸的是，独立版本很容易被防病毒软件标记为误报，所以最好请其添加到将杀毒软件的白名单中。</p>
<p class="has-line-data" data-line-start="372" data-line-end="373"><strong>请注意，不要通过Mod Organizer 2运行，也不要在Mod Organizer 2打开时运行BethINI。</strong></p>
<p class="has-line-data" data-line-start="374" data-line-end="375">安装使用说明：</p>
<ol>
<li class="has-line-data" data-line-start="376" data-line-end="377">运行前请确保已运行过FalloutNVLauncher.exe并生成了相应的INI文件</li>
<li class="has-line-data" data-line-start="377" data-line-end="378"><strong>请确保Mod Organizer 2关闭</strong>，解压缩文件到 <em>/Fallout NV Modding/Tools</em> 文件夹，进入并运行 BethINI.exe</li>
<li class="has-line-data" data-line-start="378" data-line-end="379">在弹出的窗口中下拉选择 Fallout New Vegas ，等待进入程序。</li>
<li class="has-line-data" data-line-start="379" data-line-end="380">进入程序后导航到 Setup 选项卡， <strong>取消选择</strong>下方的全部选项方框。之后在 Mod Organizer 一栏下拉菜单中选择 Browse ,在弹出的框中导航到 Mod Organizer 2 文件夹并双击选择 ModOrganizer.exe</li>
<li class="has-line-data" data-line-start="380" data-line-end="381">在 INI Path 一栏下拉菜单中选择您现在使用的Mod Organizer 2配置文件，如 ModOrganizer&gt;Core 。在弹出对话框中选择 确定 。此时会弹出对话框提示BethINI要重新启动，点击 确定 。重启后会弹出名为 Modify Custom INIs? 对话框， <strong>此时选择 否</strong> 。重新进入BethINI后导航到 Setup 选项卡，请确保全部5个选择框都没有选择。</li>
<li class="has-line-data" data-line-start="381" data-line-end="382">导航到 Basic 选项卡，在 Presets 栏中选择 BethINI Presets ，再选择 Recommended Tweaks ，程序会自动优化相应的INI文件，之后请根据配置在 Poor 到 Ultra 中选择合适的画质选项。</li>
<li class="has-line-data" data-line-start="382" data-line-end="383">选择完画质后在 Display 一栏中选择合适的分辨率，如果没有需要的分辨率则可以手动输入。可以自行选择 Antialiasing 和 Anisotropic Filtering 倍数。在右边选择 Allow 3.0 Shaders ，其他保持不变。最后选择最下方的 Enable File Selection (如果已经选择则不用管)，确定一切选择正确后点击 Save and Exit 退出。</li>
<li class="has-line-data" data-line-start="383" data-line-end="385">等待程序关闭后导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，查看下方 Shader Package 后的数字。如果是19，则不需要进一步修改。如果不是19，请导航到游戏根目录下 <em>data/Shaders</em> 文件夹找到对应Shader Package后数字的文件，如 shaderpackage013.sdp ，将其命名为shaderpackage013.sdp.backup。之后把 shaderpackage019.sdp 复制一份到其他位置，将其重命名为shaderpackage013.sdp，再剪切回原文件夹。</li>
</ol>
<blockquote>
<p class="has-line-data" data-line-start="385" data-line-end="386">强制启用shaderpackage019以打开Shaders 3.0，这应该会增加游戏帧数及稳定性。</p>
</blockquote>
<p class="has-line-data" data-line-start="387" data-line-end="388"><strong>在使用了BethINI之后，请不要再运行FalloutNVLauncher.exe，也不要在Steam中启动新维加斯。如果在以后的游戏流程中需要修改画质及其他选项，请阅读指南最后有关BethINI的说明。</strong></p>
<p class="has-line-data" data-line-start="389" data-line-end="390">八、重要前置</p>
<p class="has-line-data" data-line-start="391" data-line-end="392">在原指南中这部分使用的是MO2安装这些前置MOD，但这些MOD一般来说非常重要，且比较稳定，较少更新。如果你的MO2的配置不对或无意间没有激活这些MOD，有可能导致这些补丁失效。为了防止这种情况发生，该指南使用直接安装的方式，这些MOD都是一些nvse插件，不会修改或覆盖游戏本体的文件。</p>
<p class="has-line-data" data-line-start="393" data-line-end="394">还有要声明的是，曾经新维加斯的四大前置：NVSE NVSR NVAC Zan AutoPurge Crash Protector，这四个中的 NVSR 和 Zan AutoPurge Crash Protector 已经废弃。这两个插件被证实会对游戏稳定性产生负面影响，因此如果你是老玩家，看到本指南中没有安装以上两个插件，请不要疑惑。下面开始安装指南：</p>
<p class="has-line-data" data-line-start="395" data-line-end="396">NVSE</p>
<p class="has-line-data" data-line-start="397" data-line-end="398"><a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a></p>
<p class="has-line-data" data-line-start="399" data-line-end="400">特别安装说明：</p>
<p class="has-line-data" data-line-start="401" data-line-end="402">单击 Download (stable version 5.1b4) 旁边的链接进行下载</p>
<p class="has-line-data" data-line-start="403" data-line-end="404">将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录</p>
<ul>
<li class="has-line-data" data-line-start="405" data-line-end="407">扩展引擎的脚本功能，对于大多数mod来说都是必不可少的</li>
</ul>
<p class="has-line-data" data-line-start="407" data-line-end="408">NVSE_Config.ini</p>
<p class="has-line-data" data-line-start="409" data-line-end="410">链接: <a href="https://pan.baidu.com/s/1XsU5AdULOq4PatVUIQZnfw">https://pan.baidu.com/s/1XsU5AdULOq4PatVUIQZnfw</a> 提取码: smnf</p>
<p class="has-line-data" data-line-start="411" data-line-end="412">要安装的文件：</p>
<p class="has-line-data" data-line-start="413" data-line-end="414">将压缩包内 nvse_config.ini 解压到 Fallout New Vegas/Data/nvse/</p>
<ul>
<li class="has-line-data" data-line-start="415" data-line-end="417">增加堆分配以帮助卡顿/崩溃</li>
</ul>
<p class="has-line-data" data-line-start="417" data-line-end="418">JIP LN NVSE插件</p>
<p class="has-line-data" data-line-start="419" data-line-end="420"><a href="https://pan.baidu.com/s/19VAfxdJi1IfEJhvTagLbsQ">https://pan.baidu.com/s/19VAfxdJi1IfEJhvTagLbsQ</a> 提取码: ykx5</p>
<p class="has-line-data" data-line-start="421" data-line-end="422">要安装的文件：</p>
<p class="has-line-data" data-line-start="423" data-line-end="424">将压缩包内的 plugins 文件夹解压到 Fallout New Vegas/Data/nvse/</p>
<ul>
<li class="has-line-data" data-line-start="425" data-line-end="427">具有800多种新功能的NVSE扩展</li>
</ul>
<p class="has-line-data" data-line-start="427" data-line-end="428">4GBpatch</p>
<p class="has-line-data" data-line-start="429" data-line-end="430"><a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h</p>
<p class="has-line-data" data-line-start="431" data-line-end="432">特殊安装说明：</p>
<p class="has-line-data" data-line-start="433" data-line-end="434">将压缩包内的 4gb_patch.exe 解压到根目录</p>
<p class="has-line-data" data-line-start="435" data-line-end="436">请确保 <strong>没有</strong>运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行</p>
<p class="has-line-data" data-line-start="437" data-line-end="438">在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！</p>
<p class="has-line-data" data-line-start="439" data-line-end="440">此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，之后点击 OK 退出。</p>
<ul>
<li class="has-line-data" data-line-start="441" data-line-end="443">使游戏能够识别大地址，这意味着它可以使用4GB RAM而不是2GB</li>
</ul>
<p class="has-line-data" data-line-start="443" data-line-end="444"><strong>验证NVSE和4GBpatch是否运行：</strong></p>
<p class="has-line-data" data-line-start="445" data-line-end="446">打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行</p>
<p class="has-line-data" data-line-start="447" data-line-end="448">进入游戏主菜单后，按 ~ 键打开控制台</p>
<p class="has-line-data" data-line-start="449" data-line-end="450">将getnvseversion输入控制台并按Enter键</p>
<p class="has-line-data" data-line-start="451" data-line-end="452">控制台应报告 NVSE version: 5</p>
<ul>
<li class="has-line-data" data-line-start="453" data-line-end="455">如果没有，请检查NVSE是否已正确安装并重试</li>
</ul>
<p class="has-line-data" data-line-start="455" data-line-end="456">将getislaa输入控制台并按Enter键</p>
<p class="has-line-data" data-line-start="457" data-line-end="458">控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="459" data-line-end="460">如果控制台报告 GetisLAA &gt;&gt; 0.0000，则说明补丁未正确安装</li>
<li class="has-line-data" data-line-start="460" data-line-end="461">如果控制台报告 GetisLAA &gt;&gt; 1.0000，则修补程序已正确安装但无法正常运行，尝试以管理员身份运行</li>
<li class="has-line-data" data-line-start="461" data-line-end="463">如果控制台报告错误消息，则表示您未正确安装JIP LN NVSE</li>
</ul>
<p class="has-line-data" data-line-start="463" data-line-end="464"><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="465" data-line-end="466">通过Steam或GOG验证您的游戏文件将撤消补丁，因此您必须在验证游戏文件之后重新安装</p>
</blockquote>
<p class="has-line-data" data-line-start="467" data-line-end="468">New Vegas Anti-Crash</p>
<p class="has-line-data" data-line-start="469" data-line-end="470"><a href="https://pan.baidu.com/s/1QUI5GdNWxUjqbY9He8bV7Q">https://pan.baidu.com/s/1QUI5GdNWxUjqbY9He8bV7Q</a> 提取码: 4tv2</p>
<p class="has-line-data" data-line-start="471" data-line-end="472">要安装的文件：</p>
<p class="has-line-data" data-line-start="473" data-line-end="474">将压缩包内的 nvac.dll 解压到 Fallout New Vegas/Data/nvse/plugins/</p>
<ul>
<li class="has-line-data" data-line-start="475" data-line-end="477">实现结构化异常处理和健全性检查，以减少崩溃的数量</li>
</ul>
<p class="has-line-data" data-line-start="477" data-line-end="478">New Vegas Tick Fix</p>
<p class="has-line-data" data-line-start="479" data-line-end="480"><a href="https://pan.baidu.com/s/1MPn1m5UEAvuLy7BaS4WVUQ">https://pan.baidu.com/s/1MPn1m5UEAvuLy7BaS4WVUQ</a> 提取码: b8v1</p>
<p class="has-line-data" data-line-start="481" data-line-end="482">特殊安装说明：</p>
<p class="has-line-data" data-line-start="483" data-line-end="484">将压缩包内的所有文件解压到 Fallout New Vegas/Data/nvse/plugins/</p>
<p class="has-line-data" data-line-start="485" data-line-end="486">进入到刚才解压的目录，打开 FastExitnTickCountReplace.ini</p>
<p class="has-line-data" data-line-start="487" data-line-end="488">将 bFastResolution 设置为 1 并保存。</p>
<ul>
<li class="has-line-data" data-line-start="489" data-line-end="491">专为Windows 10而设计的NVSR版本</li>
</ul>
<p class="has-line-data" data-line-start="491" data-line-end="492">Console Paste Support</p>
<p class="has-line-data" data-line-start="493" data-line-end="494"><a href="https://pan.baidu.com/s/1mGahxA4tm9shVhugZe5tJw">https://pan.baidu.com/s/1mGahxA4tm9shVhugZe5tJw</a> 提取码: vmbn</p>
<p class="has-line-data" data-line-start="495" data-line-end="496">要安装的文件：</p>
<p class="has-line-data" data-line-start="497" data-line-end="498">将压缩包内的 nvse_console_clipboard.dll 解压到 Fallout New Vegas/Data/nvse/plugins/</p>
<ul>
<li class="has-line-data" data-line-start="499" data-line-end="501">允许您将文本粘贴到控制台中，以及其他一些键盘快捷键</li>
</ul>
<p class="has-line-data" data-line-start="501" data-line-end="502">Ogg Vorbis Libraries</p>
<p class="has-line-data" data-line-start="503" data-line-end="504"><a href="https://pan.baidu.com/s/1z458lr3DmM_8gPuk9b8_ug">https://pan.baidu.com/s/1z458lr3DmM_8gPuk9b8_ug</a> 提取码: pr2c</p>
<p class="has-line-data" data-line-start="505" data-line-end="506">特别安装说明：</p>
<p class="has-line-data" data-line-start="507" data-line-end="508">将压缩包内的文件解压到根目录，并在出现提示时选择覆盖</p>
<ul>
<li class="has-line-data" data-line-start="509" data-line-end="511">最新编译的Ogg Vorbis库，允许游戏播放某些.ogg文件，否则将无法播放</li>
</ul>
<p class="has-line-data" data-line-start="511" data-line-end="512">New Vegas Reloaded - NVGE</p>
<p class="has-line-data" data-line-start="513" data-line-end="514"><a href="https://pan.baidu.com/s/1IbE4zoBnNe-P92BGe97cYA">https://pan.baidu.com/s/1IbE4zoBnNe-P92BGe97cYA</a> 提取码: t1hg</p>
<p class="has-line-data" data-line-start="515" data-line-end="516">特别安装说明：</p>
<p class="has-line-data" data-line-start="517" data-line-end="518">手动提取压缩包 Data 文件夹中除 Music 文件夹以外的所有内容到 Fallout New Vegas/Data/</p>
<p class="has-line-data" data-line-start="519" data-line-end="520">压缩包中 binkw32.dll 可以忽略</p>
<ul>
<li class="has-line-data" data-line-start="521" data-line-end="523">添加新的渲染管道，更新默认着色器，并添加内存管理。 *<em>有关NVGE的说明请参阅指南最后</em></li>
</ul>
<p class="has-line-data" data-line-start="523" data-line-end="524">NVGE Custom .INI</p>
<p class="has-line-data" data-line-start="525" data-line-end="526">链接: <a href="https://pan.baidu.com/s/1vRs_zpNPfDX5mookpC3Pwg">https://pan.baidu.com/s/1vRs_zpNPfDX5mookpC3Pwg</a> 提取码: xxsf</p>
<p class="has-line-data" data-line-start="527" data-line-end="528">要安装的文件：</p>
<p class="has-line-data" data-line-start="529" data-line-end="530">将压缩包内的 NewVegasReloaded.ini 解压到 Fallout New Vegas/Data/nvse/plugins/ 在出现提示时选择覆盖</p>
<ul>
<li class="has-line-data" data-line-start="531" data-line-end="533">.INI文件用于NVGE，关闭所有视觉增强功能，只是保持性能和稳定性的改进。</li>
</ul>
<p class="has-line-data" data-line-start="533" data-line-end="534">九、显示设置</p>
<p class="has-line-data" data-line-start="535" data-line-end="536"><strong>仅适用于具有NVIDIA GPU的用户：NVIDIA Profile Inspector</strong></p>
<p class="has-line-data" data-line-start="537" data-line-end="538"><a href="https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA">https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA</a> 提取码: qwfa</p>
<p class="has-line-data" data-line-start="539" data-line-end="540">特别安装说明：</p>
<p class="has-line-data" data-line-start="541" data-line-end="542">将压缩包解压到根目录以外的安全位置</p>
<p class="has-line-data" data-line-start="543" data-line-end="544">运行 NVidiaProfileInspectorDmWPortable.exe</p>
<p class="has-line-data" data-line-start="545" data-line-end="546">如果有弹出窗口，请单击是</p>
<p class="has-line-data" data-line-start="547" data-line-end="548">从左上角的Profiles：下拉列表中，选择Fallout - New Vegas</p>
<p class="has-line-data" data-line-start="549" data-line-end="550">在 2. - Sync and Refresh 部分中，更改以下内容：</p>
<ul>
<li class="has-line-data" data-line-start="551" data-line-end="552">Frame Rate Limiter - 58 FPS</li>
<li class="has-line-data" data-line-start="552" data-line-end="553">Maximum pre-rendered frames - 1</li>
<li class="has-line-data" data-line-start="553" data-line-end="555">Vertical Sync - Force on</li>
</ul>
<p class="has-line-data" data-line-start="555" data-line-end="556">如果您使用G-Sync或Freesync，请不要启用 Vertical Sync</p>
<p class="has-line-data" data-line-start="557" data-line-end="558">在5. - Common部分中，更改以下内容：</p>
<ul>
<li class="has-line-data" data-line-start="559" data-line-end="561">Power management mode - Prefer maximum performance</li>
</ul>
<p class="has-line-data" data-line-start="561" data-line-end="562">单击右上角的 Apply changes 按钮，然后退出</p>
<p class="has-line-data" data-line-start="563" data-line-end="564"><strong>仅适用于使用AMD GPU的用户：调整AMD Radeon设置</strong></p>
<p class="has-line-data" data-line-start="565" data-line-end="566">(注：本人使用NVIDIA GPU，这一步没有亲自验证，翻译仅供参考)</p>
<p class="has-line-data" data-line-start="567" data-line-end="568">右键单击桌面并选择AMD Radeon Settings</p>
<p class="has-line-data" data-line-start="569" data-line-end="570">在&quot; 游戏&quot;选项卡中，选择 Fallout New Vegas 配置文件</p>
<p class="has-line-data" data-line-start="571" data-line-end="572">在&quot; 配置文件图形&quot;选项卡中，更改以下内容</p>
<p class="has-line-data" data-line-start="573" data-line-end="574">等待垂直刷新 - 增强同步</p>
<p class="has-line-data" data-line-start="575" data-line-end="576">如果不能选择增强型同步，请选择始终开启</p>
<p class="has-line-data" data-line-start="577" data-line-end="578">如果使用Freesync，请不要启用等待垂直刷新</p>
<p class="has-line-data" data-line-start="579" data-line-end="580">启用 冷却（FPS）</p>
<p class="has-line-data" data-line-start="581" data-line-end="582">将Chill Min和Chill Max设置为58</p>
<p class="has-line-data" data-line-start="583" data-line-end="584">点击左下角的主页按钮（设置应自动保存），并确保在配置文件名称下方显示&quot;已启用 &quot;字样</p>
<p class="has-line-data" data-line-start="585" data-line-end="586">如果没有，请单击配置文件名称右侧的三个垂直点，然后选择启用配置文件</p>
<blockquote>
<p class="has-line-data" data-line-start="587" data-line-end="588">关于限制FPS的注意事项:由于Gamebryo的物理特性与帧速率相关，因此FPS 必须上限为60或更低。该指南使用58FPS，因为如果不使用V-Sync，它应该可以防止屏幕撕裂</p>
</blockquote>
<p class="has-line-data" data-line-start="589" data-line-end="590">伪全屏设置：</p>
<p class="has-line-data" data-line-start="591" data-line-end="592">该步骤可以使你的游戏运行在窗口模式下，此时切入切出窗口应该不会再卡死，但游戏帧数可能会降低，请根据自己的需要选择是否设置。</p>
<p class="has-line-data" data-line-start="593" data-line-end="594">方法一：</p>
<p class="has-line-data" data-line-start="595" data-line-end="596">确保已安装前置 New Vegas Reloaded - NVGE</p>
<p class="has-line-data" data-line-start="597" data-line-end="598">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器</p>
<p class="has-line-data" data-line-start="599" data-line-end="600">导航到 falloutcustom.ini 选项卡</p>
<p class="has-line-data" data-line-start="601" data-line-end="602">在 [Display] 部分下添加以下内容</p>
<ul>
<li class="has-line-data" data-line-start="603" data-line-end="605">bFull Screen=0</li>
</ul>
<blockquote>
<p class="has-line-data" data-line-start="605" data-line-end="606">有些用户报告此调整需要在 FalloutPrefs.ini 选项卡中进行</p>
</blockquote>
<p class="has-line-data" data-line-start="607" data-line-end="608">如果此方法不起作用，则使用方法二 OneTweak：</p>
<p class="has-line-data" data-line-start="609" data-line-end="610"><a href="https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg">https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg</a> 提取码: m3b3</p>
<p class="has-line-data" data-line-start="611" data-line-end="612">要安装的文件：</p>
<p class="has-line-data" data-line-start="613" data-line-end="614">将压缩包内的 plugins 文件夹解压到 Fallout New Vegas/Data/nvse/</p>
<p class="has-line-data" data-line-start="615" data-line-end="616">十、最终测试</p>
<p class="has-line-data" data-line-start="617" data-line-end="618">至此基础游戏的设置及优化已全部完成，请按照以下步骤进行测试：</p>
<p class="has-line-data" data-line-start="619" data-line-end="620">通过MO2运行游戏</p>
<p class="has-line-data" data-line-start="621" data-line-end="622">启动一个新存档，快速通过Doc Mitchell所在的教程</p>
<p class="has-line-data" data-line-start="623" data-line-end="624">离开医生的房间后，打开pipboy检查各个选项是否有问题</p>
<p class="has-line-data" data-line-start="625" data-line-end="626">在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</p>
<ul>
<li class="has-line-data" data-line-start="627" data-line-end="628">如果你按照本指南完整做到了每一个步骤，并选择了合适的画质与分辨率，此时你的游戏应没有卡顿并可以长时间运行不跳出。</li>
<li class="has-line-data" data-line-start="628" data-line-end="629">如果你有任何问题，尝试先判断是否完全按本指南进行安装设置。如果确定步骤没有问题，请先调低画质及分辨率再进行测试(但尽量不要以最低画质运行)。</li>
<li class="has-line-data" data-line-start="629" data-line-end="631">如果问题依旧存在，可以回复进行询问，我尽可能回答。</li>
</ul>
<p class="has-line-data" data-line-start="631" data-line-end="632">以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
<hr>
<p class="has-line-data" data-line-start="635" data-line-end="636">有关BethINI的说明：</p>
<p class="has-line-data" data-line-start="637" data-line-end="638">BethINI相当于一个第三方的FalloutNVLauncher，但拥有更好的预设及更多的选项，它们的共同点是都通过修改INI文件来工作。而Mod Organizer 2会为每一个配置文件单独创建&quot;虚拟&quot;的INI文件，这时FalloutNVLauncher修改原生INI文件就对从MO2中启动的游戏不起作用。</p>
<p class="has-line-data" data-line-start="639" data-line-end="640">通过将BethINI与Mod Organizer 2链接，BethINI可以直接管理MO2中某个配置文件的INI，不再修改原生INI。 <strong>所以今后的游戏过程中如需改变画质就直接使用BethINI，只要确保选择了正确的MO2配置文件即可(一定不要同时运行BethINI和MO2)。</strong></p>
<p class="has-line-data" data-line-start="641" data-line-end="642">有关ENB与NVGE的说明：</p>
<p class="has-line-data" data-line-start="643" data-line-end="644">使用4GBpatch时正常安装ENB，如果你在使用NVGE-New Vegas Reload的同时使用ENB，请打开根目录下的 enblocal.ini 并将其中的 SpeedHack=true 改为 SpeedHack=false ，以保证两者相互兼容。</p>
<p class="has-line-data" data-line-start="645" data-line-end="646">NVGE自带截图功能，并且截图不包含UI，快捷键是F11。如需带UI截图，可以按 PrtScr 键截取。NVGE的截图保存在根目录下的 Screenshots 文件夹，带UI的截图保存在游戏根目录。</p>