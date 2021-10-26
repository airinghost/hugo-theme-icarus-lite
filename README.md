
# <div align="center"><img align="center" width="48" height="48" src="https://cdn.jsdelivr.net/gh/airinghost/hugo-theme-icarus-lite/static/favicon.png">&nbsp;Icarus-Lite</div>

<p align="center">
	A one-column and card-style Hugo theme based on the Hexo theme<a href="https://github.com/ppoffice/hexo-theme-icarus"> Icarus</a>
</p>
<p align="center">
	<a href="README.zh-CN.md">中文（简体）说明</a>
</p>



## 1. Documentation

No Docs now.

Please don't hesitate to start [Discussions](https://github.com/airinghost/hugo-theme-icarus-lite/discussions) in this repo if any questions or problems.

[Issues](https://github.com/airinghost/hugo-theme-icarus-lite/issues) also welcomed if any bugs found.



## 2. Tips

### 2.1 Front Matter

Set `hidden: true` (YAML) / `hidden = true` (TOML) to hide the file from the index (homepage) view (i.e. posts using index template).

Set `date_hidden: true` to remove the date text & structure from the top left-hand of the article card in index, list and single views.

Set `read_more: true` to add a button at the bottom left-hand of the article card in index or list views; the button text is set in Site Config - Params, you can change it globally.

Set `read_more_txt: customText` to overwrite the text for the read-more button mentioned above.

Set `link_go: http://example.com` and `link_txt: customText` to add a button at the bottom left-hand of the article card in index or list views; it would open the link you set in a new tab in the browser.

### 2.2 Body Text

Insert `<!--more-->` manually to your post or page file and it would look better. Or Set `summaryLength: 1000` or more in Site Config and then insert `<!--more-->` at the end of the `.md` file if you would not like to make a summary of your posts or pages. 



## 3. Acknowledgments

PPOffice's awesome work on building such a beautiful theme for Hexo.

Pedro Lopez's [*Creating a Hugo Theme From Scratch*](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/) guided me to the basic structure of a Hugo theme.

Janne Kemppainen's [*Implemement Hugo List and Taxonomy Pages*](https://pakstech.com/blog/hugo-list-page/) helped me a lot on pagination.

Cai Jimmy's [Stack](https://github.com/CaiJimmy/hugo-theme-stack), a great card-style Hugo theme I likes very much. And I made a use of some codes from his work, such as the main section at index template.

Jeremy Thomas's [minireset.css](https://github.com/jgthms/minireset.css).

filament group's [*The Simplest Way to Load CSS Asynchronously*](https://www.filamentgroup.com/lab/load-css-simpler/) and Sukka's [*Improve FCP for My Blog*](https://blog.skk.moe/post/improve-fcp-for-my-blog/). I learnt a way of loading CSS files asynchronously from their posts.

Tencent's [404 project](https://wj.qq.com/s2/9163450/732e/).



## P.S.

Hugo's `list.html` template enables us to build a list page in index(homepage) view. So if you are searching for the way to make Hexo generate pages like Hugo's list template, then I would like to recommend Jamling's work [`hexo-generator-index2`](https://github.com/Jamling/hexo-generator-index2).


