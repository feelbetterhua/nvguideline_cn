<p class="has-line-data" data-line-start="0" data-line-end="1"><strong>防撕裂设置</strong>：</p>
<p class="has-line-data" data-line-start="2" data-line-end="10">仅适用于具有<strong>NVIDIA GPU</strong>的用户：NVIDIA Profile Inspector<br>
<a href="https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA">https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA</a> 提取码: qwfa<br>
特别安装说明：<br>
将压缩包解压到根目录以外的安全位置<br>
运行 NVidiaProfileInspectorDmWPortable.exe<br>
如果有弹出窗口，请单击是<br>
从左上角的Profiles：下拉列表中，选择Fallout - New Vegas<br>
在 2. - Sync and Refresh 部分中，更改以下内容：</p>
<ul>
<li class="has-line-data" data-line-start="10" data-line-end="11">Frame Rate Limiter - 60 FPS</li>
<li class="has-line-data" data-line-start="11" data-line-end="13">Vertical Sync - Force on</li>
</ul>
<p class="has-line-data" data-line-start="13" data-line-end="14">单击右上角的 Apply changes 按钮，然后退出</p>
<p class="has-line-data" data-line-start="15" data-line-end="20">仅适用于使用<strong>AMD GPU</strong>的用户：调整AMD Radeon设置<br>
(注：没有亲自验证，翻译仅供参考)<br>
右键单击桌面并选择AMD Radeon Settings<br>
在&quot; 游戏&quot;选项卡中，选择 Fallout New Vegas 配置文件<br>
在&quot; 配置文件图形&quot;选项卡中，更改以下内容</p>
<ul>
<li class="has-line-data" data-line-start="20" data-line-end="21">启用 冷却（FPS），将 Chill Min 和 Chill Max 设置为60</li>
<li class="has-line-data" data-line-start="21" data-line-end="23">将 等待垂直刷新 一项设置为 增强同步。如果不能选择增强同步，请选择 始终开启</li>
</ul>
<p class="has-line-data" data-line-start="23" data-line-end="25">点击左下角的主页按钮（设置应自动保存），并确保在配置文件名称下方显示&quot;已启用 &quot;字样<br>
如果没有，请单击配置文件名称右侧的三个垂直点，然后选择启用配置文件</p>
<blockquote>
<p class="has-line-data" data-line-start="26" data-line-end="27">如果以上设置没有作用，请恢复默认设置，并尝试下面的高帧率设置(以60FPS为显示帧率)</p>
</blockquote>
<p class="has-line-data" data-line-start="28" data-line-end="29"><strong>伪全屏设置</strong>：</p>
<p class="has-line-data" data-line-start="30" data-line-end="33">对于完整版：<br>
单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器 ，导航到 falloutcustom.ini 选项卡<br>
在 [Display] 部分下添加以下内容</p>
<ul>
<li class="has-line-data" data-line-start="33" data-line-end="35">bFull Screen=0</li>
</ul>
<p class="has-line-data" data-line-start="35" data-line-end="37">点击 保存 ，然后关闭INI编辑器<br>
双击MO2左栏的 Utilities，在弹出的页面导航到 INI Files，选择 NVSE\plugins\OneTweak.ini</p>
<ul>
<li class="has-line-data" data-line-start="37" data-line-end="39">将 BorderlessWindow 后的 false 改为 true</li>
</ul>
<p class="has-line-data" data-line-start="39" data-line-end="40">点击<img src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/MO2_save.PNG" alt="MO2_save" title="MO2_save">保存修改，然后关闭</p>
<p class="has-line-data" data-line-start="41" data-line-end="44">对于简化版：<br>
导航到 文档/My Games/FalloutNV，打开 FalloutCustom.ini<br>
在 [Display] 部分下添加以下内容</p>
<ul>
<li class="has-line-data" data-line-start="44" data-line-end="46">bFull Screen=0</li>
</ul>
<p class="has-line-data" data-line-start="46" data-line-end="48">保存修改并退出<br>
导航到 <em>Data\nvse\plugins</em> 文件夹，打开 OneTweak.ini</p>
<ul>
<li class="has-line-data" data-line-start="48" data-line-end="50">将 BorderlessWindow 后的 false 改为 true</li>
</ul>
<p class="has-line-data" data-line-start="50" data-line-end="51">保存修改并退出</p>
<p class="has-line-data" data-line-start="52" data-line-end="53"><strong>BSA Decompressor修复</strong>：</p>
<p class="has-line-data" data-line-start="54" data-line-end="57">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，选择 INI编辑器<br>
导航到 Fallout.ini 选项卡，在 [Archive] 下找到 SArchiveList<br>
用以下内容替换整行（所有内容都应该在一行上）：</p>
<ul>
<li class="has-line-data" data-line-start="57" data-line-end="59">SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa</li>
</ul>
<p class="has-line-data" data-line-start="59" data-line-end="60">点击 保存 然后退出</p>
<blockquote>
<p class="has-line-data" data-line-start="60" data-line-end="61">如果还未开始Mod Organizer 2设置，则导航到 <em>文档/My Games/FalloutNV</em> ，打开 Fallout.ini 进行相同操作</p>
</blockquote>
<p class="has-line-data" data-line-start="62" data-line-end="63"><strong>有关BethINI的说明</strong>：</p>
<p class="has-line-data" data-line-start="64" data-line-end="65">BethINI相当于一个第三方的FalloutNVLauncher，但拥有更好的预设及更多的选项，它们的共同点是都通过修改INI文件来工作。而Mod Organizer 2会为每一个配置文件单独创建&quot;虚拟&quot;的INI文件，这时FalloutNVLauncher修改原生INI文件就对从MO2中启动的游戏不起作用。</p>
<p class="has-line-data" data-line-start="66" data-line-end="67">通过将BethINI与Mod Organizer 2链接，BethINI可以直接管理MO2中某个配置文件的INI，不再修改原生INI。 所以今后的游戏过程中如需改变画质就直接使用BethINI，确保选择了正确的MO2配置文件即可(一定不要同时运行BethINI和MO2)。</p>
<p class="has-line-data" data-line-start="68" data-line-end="70">如果需要修改中文字体等要手动编辑INI文件的选项，具体方法为：<br>
打开Mod Organizer2，单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器。导航到 fallout.ini 或 falloutprefs.ini 选项卡，修改其中相应内容并保存即可。</p>
<p class="has-line-data" data-line-start="71" data-line-end="82">以修改字体的方法为例，打开INI编辑器 ，导航到 fallout.ini 选项卡，找到 [Fonts] ，更改以下内容<br>
微软雅圆：<br>
sFontFile_1=Textures\Fonts\karl_gb.fnt<br>
sFontFile_2=Textures\Fonts\karl_gb.fnt<br>
sFontFile_3=Textures\Fonts\karl_gb.fnt<br>
sFontFile_4=Textures\Fonts\karl_gb.fnt<br>
sFontFile_5=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_6=Textures\Fonts\karl_gb.fnt<br>
sFontFile_7=Textures\Fonts\karl_gb.fnt<br>
sFontFile_8=Textures\Fonts\karl_gb.fnt<br>
sFontFile_9=Textures\Fonts\karl_gb.fnt</p>
<p class="has-line-data" data-line-start="83" data-line-end="93">宋体：<br>
sFontFile_1=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_2=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_3=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_4=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_5=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_6=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_7=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_8=Textures\Fonts\fixedsys_kar.fnt<br>
sFontFile_9=Textures\Fonts\fixedsys_kar.fnt</p>
<p class="has-line-data" data-line-start="94" data-line-end="95">修改完成后点击 保存 ，然后关闭INI编辑器</p>
<p class="has-line-data" data-line-start="96" data-line-end="97"><strong>有关ENB与NVR的说明</strong>：</p>
<p class="has-line-data" data-line-start="98" data-line-end="99">在使用NVR的同时使用ENB，两者都需要修改一定设置：</p>
<ul>
<li class="has-line-data" data-line-start="99" data-line-end="100">ENB部分：打开根目录下的 enblocal.ini 并将其中的 SpeedHack=true 改为 SpeedHack=false</li>
<li class="has-line-data" data-line-start="100" data-line-end="104">NVR部分：<br>
对于完整版：双击MO2左栏的 Utilities，在弹出的页面导航到 INI Files，选择 NVSE\Plugins\NewVegasReloaded.ini ，在 [Main] 部分下找到 ShaderModel3 ，将其后面的1改为0<br>
点击<img src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/MO2_save.PNG" alt="MO2_save" title="MO2_save">保存修改，然后关闭</li>
</ul>
<p class="has-line-data" data-line-start="104" data-line-end="106">对于简化版：导航到 <em>Data\nvse\plugins</em> 文件夹，打开 NewVegasReloaded.ini<br>
在 [Main] 部分下找到 ShaderModel3 ，将其后面的1改为0，保存修改并退出</p>
<p class="has-line-data" data-line-start="107" data-line-end="110">NVR的截图功能：<br>
NVR自带截图功能，但要注意NVR截图不包含UI，快捷键是F11。如需带UI截图，可以按 PrtScr 键截取。<br>
NVR的截图保存在根目录下的 Screenshots 文件夹，PrtScr键的截图保存在游戏根目录。</p>
