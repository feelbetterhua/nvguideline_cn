<p><strong>防撕裂设置</strong>：</p>

<p>仅适用于具有<strong>NVIDIA GPU</strong>的用户：NVIDIA Profile Inspector</p>

<p><a href="https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA">https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA</a> 提取码: qwfa</p>

<p>特别安装说明：</p>

<p>将压缩包解压到根目录以外的安全位置</p>

<p>运行 NVidiaProfileInspectorDmWPortable.exe</p>

<p>如果有弹出窗口，请单击是</p>

<p>从左上角的Profiles：下拉列表中，选择Fallout - New Vegas</p>

<p>在 2. - Sync and Refresh 部分中，更改以下内容：</p>

<ul><li>Frame Rate Limiter - 60 FPS</li><li>Vertical Sync - Force on</li></ul>

<p>单击右上角的 Apply changes 按钮，然后退出</p>

<p>仅适用于使用<strong>AMD GPU</strong>的用户：调整AMD Radeon设置</p>

<p>(注：没有亲自验证，翻译仅供参考)</p>

<p>右键单击桌面并选择AMD Radeon Settings</p>

<p>在&amp;quot; 游戏&amp;quot;选项卡中，选择 Fallout New Vegas 配置文件</p>

<p>在&amp;quot; 配置文件图形&amp;quot;选项卡中，更改以下内容</p>

<ul><li>启用 冷却（FPS），将 Chill Min 和 Chill Max 设置为60</li><li>将 等待垂直刷新 一项设置为 增强同步。如果不能选择增强同步，请选择 始终开启</li></ul>

<p>点击左下角的主页按钮（设置应自动保存），并确保在配置文件名称下方显示&amp;quot;已启用 &amp;quot;字样</p>

<p>如果没有，请单击配置文件名称右侧的三个垂直点，然后选择启用配置文件</p>

<blockquote><p>如果以上设置没有作用，请恢复默认设置，并尝试下面的高帧率设置(以60FPS为显示帧率)</p></blockquote>

<p><strong>伪全屏设置</strong>：</p>

<p>对于完整版：</p>

<p>单击MO2顶部栏上的按钮<img alt="inieditor_pic" title="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"/> ，然后选择 INI编辑器 ，导航到 falloutcustom.ini 选项卡</p>

<p>在 [Display] 部分下添加以下内容</p>

<ul><li>bFull Screen=0</li></ul>

<p>点击 保存 ，然后关闭INI编辑器</p>

<p>双击MO2左栏的 Utilities，在弹出的页面导航到 INI Files，选择 NVSE\plugins\OneTweak.ini</p>

<ul><li>将 BorderlessWindow 后的 false 改为 true</li></ul>

<p>点击<img alt="MO2_save" title="MO2_save" src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/MO2_save.PNG"/>保存修改，然后关闭</p>

<p>对于简化版：</p>

<p>导航到 文档/My Games/FalloutNV，打开 FalloutCustom.ini</p>

<p>在 [Display] 部分下添加以下内容</p>

<ul><li>bFull Screen=0</li></ul>

<p>保存修改并退出</p>

<p>导航到 <em>Data\nvse\plugins</em> 文件夹，打开 OneTweak.ini</p>

<ul><li>将 BorderlessWindow 后的 false 改为 true</li></ul>

<p>保存修改并退出</p>

<p><strong>BSA Decompressor修复</strong>：</p>

<p>单击MO2顶部栏上的按钮<img alt="inieditor_pic" title="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"/> ，选择 INI编辑器</p>

<p>导航到 Fallout.ini 选项卡，在 [Archive] 下找到 SArchiveList</p>

<p>用以下内容替换整行（所有内容都应该在一行上）：</p>

<ul><li>SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa</li></ul>

<p>点击 保存 然后退出</p>

<blockquote><p>如果还未开始Mod Organizer 2设置，则导航到 <em>文档/My Games/FalloutNV</em> ，打开 Fallout.ini 进行相同操作</p></blockquote>

<p><strong>有关BethINI的说明</strong>：</p>

<p>BethINI相当于一个第三方的FalloutNVLauncher，但拥有更好的预设及更多的选项，它们的共同点是都通过修改INI文件来工作。而Mod Organizer 2会为每一个配置文件单独创建&amp;quot;虚拟&amp;quot;的INI文件，这时FalloutNVLauncher修改原生INI文件就对从MO2中启动的游戏不起作用。</p>

<p>通过将BethINI与Mod Organizer 2链接，BethINI可以直接管理MO2中某个配置文件的INI，不再修改原生INI。 所以今后的游戏过程中如需改变画质就直接使用BethINI，确保选择了正确的MO2配置文件即可(一定不要同时运行BethINI和MO2)。</p>

<p>如果需要修改中文字体等要手动编辑INI文件的选项，具体方法为：</p>

<p>打开Mod Organizer2，单击MO2顶部栏上的按钮<img alt="inieditor_pic" title="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"/> ，然后选择 INI编辑器。导航到 fallout.ini 或 falloutprefs.ini 选项卡，修改其中相应内容并保存即可。</p>

<p>以修改字体的方法为例，打开INI编辑器 ，导航到 fallout.ini 选项卡，找到 [Fonts] ，更改以下内容</p>

<p>微软雅圆：</p>

<p>sFontFile<em>1=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>2=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>3=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>4=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>5=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>6=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>7=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>8=Textures\Fonts\karl</em>gb.fnt</p>

<p>sFontFile<em>9=Textures\Fonts\karl</em>gb.fnt</p>

<p>宋体：</p>

<p>sFontFile<em>1=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>2=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>3=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>4=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>5=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>6=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>7=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>8=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>sFontFile<em>9=Textures\Fonts\fixedsys</em>kar.fnt</p>

<p>修改完成后点击 保存 ，然后关闭INI编辑器</p>

<p><strong>有关ENB与NVR的说明</strong>：</p>

<p>在使用NVR的同时使用ENB，两者都需要修改一定设置：</p>

<ul><li><p>ENB部分：打开根目录下的 enblocal.ini 并将其中的 SpeedHack=true 改为 SpeedHack=false</p></li><li><p>NVR部分：</p><p>对于完整版：双击MO2左栏的 Utilities，在弹出的页面导航到 INI Files，选择 NVSE\Plugins\NewVegasReloaded.ini ，在 [Main] 部分下找到 ShaderModel3 ，将其后面的1改为0</p><p>点击<img alt="MO2_save" title="MO2_save" src="https://raw.githubusercontent.com/feelbetterhua/nvguideline_cn/master/MO2_save.PNG"/>保存修改，然后关闭</p><p>对于简化版：导航到 <em>Data\nvse\plugins</em> 文件夹，打开 NewVegasReloaded.ini</p><p>在 [Main] 部分下找到 ShaderModel3 ，将其后面的1改为0，保存修改并退出</p></li></ul>

<p>NVR的截图功能：</p>

<p>NVR自带截图功能，但要注意NVR截图不包含UI，快捷键是F11。如需带UI截图，可以按 PrtScr 键截取。</p>

<p>NVR的截图保存在根目录下的 Screenshots 文件夹，PrtScr键的截图保存在游戏根目录。</p>
