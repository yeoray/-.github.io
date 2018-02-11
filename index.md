## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/yeoray/-.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
虚拟机的由来
CPU  内存 i/o 计算机的核心
创建虚拟机在物理机的基础上通过软件的方式虚拟或模拟出多个各自独立一套计算机的重要部件的平台
Cpu在主机和虚拟机之间的使用
Cpu本身的使用就是分时系统，拥有划分时间片的能力，将一个cpu分给多个虚拟机使用
内存：编址的存储单元。内存专门切断分给不同的虚拟机，每个虚拟机只能使用每个地址范围内的内存
host“宿主机
Guest：虚拟机
问题虚拟机互不干涉使用键盘：捕获
Vmware是我们自己创建虚拟机的一个软件 ，最重要的是磁盘和网卡
制定cpu，几个核心和硬盘，网卡使用模式。
创建完成后安装os
 
 建议使用custom高级的
 指定兼容版本
如何装操作系统，
 下一步安装操作系统的提示
选择guest类型 
不同操作系统对硬件要求不一样。
 上者不支持页面虚拟化，下者支持
 虚拟机的名称
硬盘虚拟化：磁盘映像文件 ，将文件当成磁盘来使用。支持稀疏格式：内外大小不一样，看起来很大，在物理硬盘上只占很小一部分空间。但非稀疏格式保证性能。但相比空间更重要。
虚拟磁盘映像文件存在地址 

