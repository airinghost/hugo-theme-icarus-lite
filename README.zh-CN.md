
<div align="center"><img width="48" height="48" src="https://icarus-lite.zhangjet.com/logo.svg">
<br><h2>Icarus-Lite</h2>
</div>

<p align="center">
	一款基于<a href="https://github.com/ppoffice/hexo-theme-icarus/"> Hexo 主题 Icarus </a>的卡片样式制作的单栏 Hugo 主题
</p>
<p align="center">
	<a href="https://github.com/airinghost/hugo-theme-icarus-lite/">English Intro</a>
</p>

![](https://icarus-lite.zhangjet.com/images/tn.png)



## 特点

卡片 - 每一篇文章都以卡片状呈现。

单 HTML 文件 - CSS 或 JS 都内联在 HTML 文件中。



## 演示

https://icarus-lite.zhangjet.com/



## 使用指南

[点此阅读配置文件示例](https://github.com/airinghost/hugo-theme-icarus-lite/blob/main/exampleSite/config.yaml)。

使用前或使用过程中如有任何疑问或问题，不要犹豫，请点击上方的 [Discussions](https://github.com/airinghost/hugo-theme-icarus-lite/discussions) 栏目发帖。

如果发现模板文件内的代码有任何不妥之处，也欢迎提出 [Issues](https://github.com/airinghost/hugo-theme-icarus-lite/issues)。



## 小小的用法

### （1） Front Matter 区域

设置 `hidden: true`（YAML格式）或 `hidden = true`（TOML格式，下同）以隐藏该文章于首页视图（使用了 index.html 模板的页面）中。

设置 `date_hidden: true` 以隐藏该文章卡片左上角的发布时间及其结构所占用的空间。

设置 `read_more: true` 以添加“阅读更多”的按钮于文章卡片左下角。该按钮的文字可在站点配置文件中的 `Params` 区域进行全局修改。

设置 `read_more_txt: 自定义文字` 以覆盖上面提到的全局设置。

设置 `link_go: 网址` 和 `link_txt: 自定义文字` 以添加一按钮于文章卡片左下角，点击该按钮可在浏览器新标签页中打开你填入的网址。  
若不想在新标签页打开该链接，则可以设置 `link_same: true`。

设置 `no_summary: true` 可以单独为当前文章取消摘要，使文章完整内容全部显示于卡片上（config 配置文件中有此项功能的全局设置）。

### （2） 正文区域

不要忘了手动在正文部分插入 &lt;!--more--&gt; 以生成文章预览（摘要），这样看起来更美观。



## 致谢

感谢 PPOffice 为 Hexo 制作的如此美观的主题。

感谢 Pedro Lopez 的教程《[Creating a Hugo Theme From Scratch](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/)》，该文指导我初步了解了 Hugo 主题模板的基本结构。

感谢 Janne Kemppainen 的教程《[Implemement Hugo List and Taxonomy Pages](https://pakstech.com/blog/hugo-list-page/)》，该文帮助了我完成 pagination 分页模板。

感谢腾讯的 [404公益项目](https://www.qq.com/404/)。

感谢 Jeremy Thomas 的 [minireset.css](https://github.com/jgthms/minireset.css/) 项目。

感谢 Cai Jimmy 的 [Stack](https://github.com/CaiJimmy/hugo-theme-stack/) 项目，这是我非常喜欢的一款卡片式 Hugo 主题。我在 index 模板的主体部分中采用了他的一些代码。

感谢元吉先生的 [futu](https://github.com/masakichi/futu/) 主题。我在 navbar 模板中采用了他的一些代码。

感谢 GoHugo 官方的主题 [GoHugo Sites Theme](https://github.com/gohugoio/gohugoioTheme)。我引用了它 code 和 table 部分的 CSS。

感谢 filament group 的文章《[The Simplest Way to Load CSS Asynchronously](https://www.filamentgroup.com/lab/load-css-simpler/)》和苏卡卡的《[再快一点，再快一点 —— 优化博客白屏时间的实践](https://blog.skk.moe/post/improve-fcp-for-my-blog/)》。我从他们的文章中学到了如何异步加载 CSS 文件及其原理。

感谢 Aditya Telange 的 [PaperMod 主题](https://github.com/adityatelange/hugo-PaperMod) 提供的 Markdown Syntax 测试文件。

感谢 Oursky 提供的 [带壳截图工具](https://mockuphone.com/)。

感谢维基共享资源的 [外链图标](https://commons.m.wikimedia.org/w/load.php?modules=skins.minerva.content.styles.images&image=a.external%2C+.mw-parser-output+a.external) 和 Yoksel 的 [Url encoder for SVG](https://github.com/yoksel/url-encoder/)。



## 其他

得益于 Hugo 的 `list.html` 模板，我们可以很方便地在除了主页外的其他目录也用上主页布局。但如果你在使用 Hexo 的同时也想要实现这项功能，那么我推荐 Jamling 的这个项目：[`hexo-generator-index2`](https://github.com/Jamling/hexo-generator-index2)。


