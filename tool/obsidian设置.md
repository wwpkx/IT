# 缺陷
- markdown 换行不统一
- 严格的markdown格式使用 **两个空格+回车** 换行
- obsidian 和 typora 直接使用回车 换行

# 优势
- 双链，文件+标签
- 目录结构，符合习惯

# 设置
## 设置快捷键
命令面板中的命令都可以设置为快捷键
![](../photo/Pasted%20image%2020240628191924.png)


**把文件删除到.trash文件夹**
![Pasted image 20220926100655](../photo/Pasted%20image%2020220926100655.png)

**use wikilink关掉，这样会自动转换成通用的md链接格式**
文件和图片链接使用 markdonw格式，在git中也能查看
![Pasted image 20220926100913](../photo/Pasted%20image%2020220926100913.png)

**文件路径 和 图片路径**
文件路径使用 相对路径，可以更好的组织文件
图片存储路径使用 绝对路径/photo
1. 如果使用图片存储使用相对路径，文件转移时，图片可能没有转移；而绝对路径，则不需要改动图片位置
2. 可以直接在git中正确显示文件或者图片
3. 无法快速分享md格式的文件给别人，可以导出pdf格式的

![](../photo/Pasted%20image%2020220926113639.png)
![](../photo/Pasted%20image%2020220926151026.png)

# 插件
不需要VPN与翻墙，完美解决obsidian无法加载第三方插件 
https://github.com/juqkai/obsidian-proxy-github
https://gitee.com/juqkai/obsidian-proxy-github

Annotator
It allows you to open and annotate PDF and EPUB files.

PDF to Markdown
https://github.com/akaalias/obsidian-extract-pdf
是一个好用的PDF转换文本工具，可以直接将PDF转化为markdown文件，你可以直接在原文上做笔记了。

Note Refactor插件
是一个很好用的**拆书工具**，可以让你用不同方式拆解一本书，打造自己的知识网络。

template
是一个很好用的快捷写作工具，可以让你用不同的模板写论文、写文献笔记，提高你的写作效率。  

Obsidian的PDF高亮插件
- annotator 感觉不好用

![](../photo/Pasted%20image%2020240517095613.png)

# 思维导图
- mind map
	- 数学公式显示有问题
	- 根据 [markmap](https://markmap.js.org/) 实现
		- 还有vscode插件版本,markmind
- [MarkMindCkm (mark) (github.com)](https://github.com/MarkMindCkm/)
	- 设置快捷键 ctrl+alt+h 切换 markdown 和 脑图
		- 通过设置 -- 快捷键
	- markmind
		- 支持图片
			- 在脑图中直接复制图片，**会使用 wiki 绝对路径 链接**
			- 在md中，则都ok
	- enhance mind
		- 在脑图中，可以显示图片
		- 在脑图中，不能直接插入图片

# git
- git 菜单不见了
	- 使用命令，然后执行 Open source control view