NetEase-MusicBox
=================


#### Thanks vellow, hbprotoss, Catofes, 尘埃, chaserhkj, Ma233, 20015jjw, mchome, stkevintan, ayanamimcy

高品质网易云音乐命令行版本，简洁优雅，丝般顺滑，基于Python编写。

[![](https://img.shields.io/pypi/dm/NetEase-MusicBox.svg)](https://pypi.python.org/pypi/NetEase-MusicBox/)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.txt) 
[![versions](https://img.shields.io/pypi/v/NetEase-MusicBox.svg)](https://pypi.python.org/pypi/NetEase-MusicBox/)
[![platform](https://img.shields.io/badge/python-2.7-green.svg)]()

[![NetEase-MusicBox](http://7j1yv3.com1.z0.glb.clouddn.com/preview.gif)](https://www.python.org/downloads/)

### 功能特性

1. 320kbps的高品质音乐
2. 歌曲，艺术家，专辑检索
3. 网易22个歌曲排行榜
4. 网易新碟推荐
5. 网易精选歌单
6. 网易DJ节目
7. 私人歌单，每日推荐
8. 随心打碟
9. 本地收藏，随时加❤
10. 播放进度及播放模式显示
11. Vimer式快捷键让操作丝般顺滑
12. 可使用数字快捷键

### 键盘快捷键

<table>
	<tr> <td>J</td> <td>Down</td> <td>下移</td> </tr>
	<tr> <td>K</td> <td>Up</td> <td>上移</td> </tr>
	<tr> <td>H</td> <td>Back</td> <td>后退</td> </tr>
	<tr> <td>L</td> <td>Forword</td> <td>前进</td> </tr>
	<tr> <td>U</td> <td>Prev page</td> <td>上一页</td> </tr>
	<tr> <td>D</td> <td>Next page</td> <td>下一页</td> </tr>
	<tr> <td>F</td> <td>Search</td> <td>快速搜索</td> </tr>
	<tr> <td>[</td> <td>Prev song</td> <td>上一曲</td> </tr>
	<tr> <td>]</td> <td>Next song</td> <td>下一曲</td> </tr>
	<tr> <td>=</td> <td>Volume +</td> <td>音量增加</td> </tr>
	<tr> <td>-</td> <td>Volume -</td> <td>音量减少</td> </tr>
	<tr> <td>Space</td> <td>Play/Pause</td> <td>播放/暂停</td> </tr>
    <tr> <td>?</td> <td>Shuffle</td> <td>手气不错</td> </tr>
	<tr> <td>M</td> <td>Menu</td> <td>主菜单</td> </tr>
	<tr> <td>P</td> <td>Present/History</td> <td>当前/历史播放列表</td> </tr>
	<tr> <td>⇧+P</td> <td>Playing Mode</td> <td>播放模式切换</td> </tr>
	<tr> <td>A</td> <td>Add</td> <td>添加曲目到打碟</td> </tr>
	<tr> <td>Z</td> <td>DJ list</td> <td>打碟列表</td> </tr>
	<tr> <td>S</td> <td>Star</td> <td>添加到收藏</td> </tr>
	<tr> <td>C</td> <td>Collection</td> <td>收藏列表</td> </tr>
	<tr> <td>R</td> <td>Remove</td> <td>删除当前条目</td> </tr>
	<tr> <td>⇧+J</td> <td>Move Down</td> <td>向下移动当前项目</td> </tr>
	<tr> <td>⇧+K</td> <td>Move Up</td> <td>向上移动当前项目</td> </tr>
	<tr> <td>,</td> <td>Like</td> <td>喜爱</td> </tr>
	<tr> <td>.</td> <td>Trash FM</td> <td>删除 FM</td> </tr>
	<tr> <td>/</td> <td>Next FM</td> <td>下一FM</td> </tr>
	<tr> <td>Q</td> <td>Quit</td> <td>退出</td> </tr>
	<tr> <td>W</td> <td>Quit&Clear</td> <td>退出并清除用户信息</td> </tr>
</table>

	


### Mac安装
	
	$ sudo pip install NetEase-MusicBox

	$ brew install mpg123

### Linux安装
	
	$ sudo pip install NetEase-MusicBox

	$ sudo apt-get install mpg123		

#### 已测试的系统兼容列表

<table>
	<tr> <td>OS X</td> <td>10.11 / 10.10 / 10.9</td> </tr>
	<tr> <td>Ubuntu</td> <td>14.04</td> </tr>
	<tr> <td>Kali</td> <td>1.1.0 / 2.0</td> </tr>
	<tr> <td>CentOS</td> <td>7</td> </tr>
	<tr> <td>openSUSE</td> <td>13.2</td> </tr>
	<tr> <td>Fedora</td> <td>22</td> </tr>
</table>


#### 错误处理

1. pkg_resources.DistributionNotFound: requests
	
	$ sudo pip install requests

    如果是运行 $ musicbox 出错

	$ sudo pip install --upgrade setuptools

2. pip: Command not found

	$ sudo apt-get install python-pip

3. ImportError: No module named setuptools
    
    $ sudo easy_install pip
    
    $ sudo apt-get install python-setuptools
	
### 使用

	$ musicbox


Enjoy it !

### 更新日志

2015-09-25 版本 0.1.9.4    修复部分列表无法暂停问题

2015-09-25 版本 0.1.9.2    新增版本检查和更新提醒功能

2015-09-24 版本 0.1.9.0    优化登陆逻辑，修复每日推荐的登陆问题

2015-09-23 版本 0.1.8.5    优化电台FM功能逻辑

2015-09-22 版本 0.1.8.4    修复未开启缓存功能无法加❤的问题

2015-09-22 版本 0.1.8.2    新增加❤功能

2015-09-21 版本 0.1.8.1    隐藏不常用的收藏功能，新增电台FM功能

2015-09-20 版本 0.1.8.0    隐藏不常用的打碟功能，新增每日推荐功能

2015-08-29 版本 0.1.7.6    使用SSL登录

2015-08-17 版本 0.1.7.5    新增用户配置文件

2015-08-09 版本 0.1.7.1    修正无法暂停错误

2015-08-08 版本 0.1.7.0    新增歌词显示,优化本地信息

2015-08-02 版本 0.1.6.5    新增播放模式切换

2015-08-02 版本 0.1.6.2    新增显示播放进度

2015-07-30 版本 0.1.6.0    修复由于接口更换导致的用户登陆问题

2015-06-17 版本 0.1.5.6    优化对过长歌曲信息的显示

2015-05-26 版本 0.1.5.5    修复海外用户无法搜索的问题

2015-05-05 版本 0.1.5.4    优化log文件路径

2015-04-02 版本 0.1.5.3    修复个别歌单崩溃错误

2015-03-31 版本 0.1.5.2    新增22个歌曲排行榜

2015-03-30 版本 0.1.5.1    新增一键 P 回到历史播放列表功能 (感谢Catofes提交)

2015-03-27 版本 0.1.5.0    使用全新动态UI绘制方法,提高稳定性 (感谢Will Jiang提交)

2015-03-25 版本 0.1.4.0    优先使用320kbps音源,优化线路,显示当前音乐音质 (感谢chaserhkj反馈)

2015-03-24 版本 0.1.3.4    增加向上/向下移动项目功能 (感谢chaserhkj提交)

2015-03-18 版本 0.1.3.3    修复Ubuntu等系统SSL登录报错问题

2015-02-28 版本 0.1.3.2    修复170等新增号段手机用户无法登陆的问题

2015-02-05 版本 0.1.3.1    修复登录无法保存的问题

2015-01-30 版本 0.1.3.0    修复UI调整后就Crash的问题，修改登录UI (感谢尘埃提交)

2015-01-28 版本 0.1.2.4    修改搜索UI (感谢尘埃提交)

2015-01-08 版本 0.1.2.3    增加手气不错,微调音量控制

2015-01-08 版本 0.1.2.0    增加音量控制

2015-01-03 版本 0.1.1.1    修复部分仅手机注册用户登录无法登陆 (感谢Catofes反馈)

2015-01-02 版本 0.1.1.0    新增退出并清除用户信息功能

### The MIT License (MIT) 

CopyRight (c) 2015 omi  &lt;<a href="4399.omi@gmail.com">4399.omi@gmail.com</a>&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


