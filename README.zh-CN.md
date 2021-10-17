
# <div align="center"><img align="center" width="50" height="50" src="https://cdn.jsdelivr.net/gh/airinghost/hugo-theme-icarus-lite/static/favicon.png">Icarus-Lite</div>

<p align="center">
	这是一个基于 Hexo 主题<a href="https://github.com/ppoffice/hexo-theme-icarus"> Icarus </a>的样式制作的单栏、卡片式的 Hugo 主题。
</p>
<p align="center">
	<a href="README.md">English</a>
</p>



## 1. 使用指南

目前没写。

使用前或使用过程中如有任何疑问或问题，不要犹豫，请点击上方的 [Discussions](https://github.com/airinghost/hugo-theme-icarus-lite/discussions) 栏目发帖。

如果发现模板文件内的代码有任何不妥之处，也欢迎提出 [Issues](https://github.com/airinghost/hugo-theme-icarus-lite/issues)。



## 2. 小小的用法

### 2.1 Front Matter 区域

输入 `hidden: true`（YAML格式）或 `hidden = true`（TOML格式，下同）以隐藏该文章于首页视图（即使用了 index.html 模板的视图）中。

输入 `date_hidden: true` 以隐藏该文章卡片左上角的发布时间及其结构所占用的空间。

输入 `read_more: true` 以添加“阅读更多”的按钮于文章卡片左下角。该按钮的文字可在站点配置文件中的 `Params` 区域进行全局修改。

输入 `read_more_txt: 自定义文字` 以覆盖上面提到的全局设置。

输入 `link_go: 网址` 和 `link_txt: 自定义文字` 以添加一按钮于文章卡片左下角，点击该按钮可在浏览器新标签页中打开你填入的网址。

### 2.2 正文区域

手动在正文部分插入 `<!--more-->` 可以让文章的摘要在列表视图中更美观。若不想为文章设置摘要，那么你可以在站点配置文件中设置 `summaryLength: 1000` 或更大的数值，然后再在 `.md` 文件的末尾手动插入 `<!--more-->`。



## 3. 致谢

感谢 PPOffice 为 Hexo 制作的如此美观的主题.

感谢 Pedro Lopez 的教程 《[Creating a Hugo Theme From Scratch](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/)》，该文指导我初步了解了 Hugo 主题模板的基本结构。

感谢 Janne Kemppainen 的教程 《[Implemement Hugo List and Taxonomy Pages](https://pakstech.com/blog/hugo-list-page/)》，该文帮助了我完成 pagination 分页模板。

感谢 Cai Jimmy 的 [Stack](https://github.com/CaiJimmy/hugo-theme-stack) 项目，这是我非常喜欢的一款卡片式 Hugo 主题。我在 index 模板的主体部分中采用了他的一些代码。

感谢 Jeremy Thomas 的 [minireset.css](https://github.com/jgthms/minireset.css) 项目。

感谢 filament group 的文章 《[The Simplest Way to Load CSS Asynchronously](https://www.filamentgroup.com/lab/load-css-simpler/)》和苏卡卡的《[再快一点，再快一点 —— 优化博客白屏时间的实践](https://blog.skk.moe/post/improve-fcp-for-my-blog/)》。我从他们的文章中学到了如何异步加载 CSS 文件及其原理。

感谢 thepeer's [答疑](https://stackoverflow.com/questions/796087/make-a-div-into-a-link/3494108#3494108)，该回答的方法帮我实现了我解决不了的“将超链接覆盖至整个容器内”这一难点。

感谢腾讯的[404公益](https://wj.qq.com/s2/9163450/732e/)项目



## P.S.

得益于 Hugo 的 `list.html` 模板，我们可以很方便地在处了主页外的其他目录也用上主页布局。但如果你在使用 Hexo 的同时也想要实现这项功能，那么我推荐 Jamling 的这个项目：[`hexo-generator-index2`](https://github.com/Jamling/hexo-generator-index2)。


