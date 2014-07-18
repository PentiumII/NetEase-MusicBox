NetEase-MusicBox
=================

高品质网易云音乐命令行版本，简洁优雅，丝般顺滑，基于Python编写。

![NetEase-MusicBox](http://i.imgur.com/J5353vK.gif)

### 功能特性

1. 320kps的高品质音乐，根据网络情况自动切换码率
2. 歌曲，艺术家，专辑检索
3. 网易热门歌曲排行榜
4. 网易新碟推荐
5. 网易精选歌单
6. 网易DJ节目
7. 私人歌单
8. 随心打碟
9. 本地收藏（不提供下载）
10. Vi快捷键让操作丝般顺滑

### 键盘快捷键

<table>
	<tr> <td>j</td> <td>Down</td> <td>下移</td> </tr>
	<tr> <td>k</td> <td>Up</td> <td>上移</td> </tr>
	<tr> <td>h</td> <td>Back</td> <td>后退</td> </tr>
	<tr> <td>l</td> <td>Forword</td> <td>前进</td> </tr>
	<tr> <td>u</td> <td>Prev page</td> <td>上一页</td> </tr>
	<tr> <td>d</td> <td>Next page</td> <td>下一页</td> </tr>
	<tr> <td>f</td> <td>Search</td> <td>快速搜索</td> </tr>
	<tr> <td>[</td> <td>Prev song</td> <td>上一曲</td> </tr>
	<tr> <td>]</td> <td>Next song</td> <td>下一曲</td> </tr>
	<tr> <td>Space</td> <td>Play/Pause</td> <td>播放/暂停</td> </tr>
	<tr> <td>m</td> <td>Menu</td> <td>主菜单</td> </tr>
	<tr> <td>p</td> <td>Present</td> <td>当前播放列表</td> </tr>
	<tr> <td>a</td> <td>Add</td> <td>添加曲目到打碟</td> </tr>
	<tr> <td>A</td> <td>Add page</td> <td>添加页面所有曲目到打碟</td> </tr>
	<tr> <td>z</td> <td>DJ list</td> <td>打碟列表</td> </tr>
	<tr> <td>s</td> <td>Star</td> <td>添加到收藏</td> </tr>
	<tr> <td>c</td> <td>Collection</td> <td>收藏列表</td> </tr>
	<tr> <td>r</td> <td>Remove</td> <td>删除当前条目</td> </tr>
	<tr> <td>R</td> <td>Remove page</td> <td>删除当前页面所有条目</td> </tr>
	<tr> <td>q</td> <td>Quit</td> <td>退出</td> </tr>
</table>


### Mac安装

	$ sudo pip install netease-musicbox

	$ brew install mpg123

### Linux安装

	$ sudo pip install netease-musicbox
##### Ubuntu
	$ sudo apt-get install mpg123
##### Fedora (rpmfusion needed)
	$ sudo yum install mpg123
	
### 使用

	$ musicbox

Enjoy it !


### 错误处理

##### pkg_resources.DistributionNotFound: requests  

	$ sudo pip install requests

如果是运行 $ musicbox 出错  

	$ sudo pip install --upgrade setuptools

##### pip: Command not found  

	$ sudo apt-get install python-pip

##### locale.Error: unsupported locale setting, 以及中文乱码

    $ sudo apt-get install language-pack-en-base
    $ sudo dpkg-reconfigure locales

如果使用zsh, `vim ~/.zshrc`,添加

    export LC_ALL=en_US.UTF-8
    export LANG=en_US.UTF-8

`$ source ~/.zshrc`

### About Music CopyRight
    NetEase-MusicBox would never provide music download in any form, and this shall 
    be included in all copies or substantial portions of the Software.   

### The MIT License (MIT)

CopyRight (c) 2014 vellow  &lt;<a href="mailto:i@vellow.net">i@vellow.net</a>&gt;

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

