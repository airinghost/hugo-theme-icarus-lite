
<div align="center"><img width="48" height="48" src="https://hugo-theme-icarus-lite.netlify.app/favicon.svg">
<br><h2>Icarus-Lite</h2>
</div>

<p align="center">
	A single-column Hugo theme based on the <a href="https://github.com/ppoffice/hexo-theme-icarus/">Hexo theme Icarus</a>'s card style
</p>
<p align="center">
	<a href="https://github.com/airinghost/hugo-theme-icarus-lite/blob/main/README.zh-CN.md">中文（简体）说明</a>
</p>

![](https://hugo-theme-icarus-lite.netlify.app/images/tn.png)



## Features

Card style - Every post or note can be a card.

Single HTML file - Fully inline or internal Style Sheet and JavaScript.



## Demo

Site Status:

[![Netlify Status](https://hugo-theme-icarus-lite.netlify.app/images/netlify.success.svg)](https://hugo-theme-icarus-lite.netlify.app/)

Site Repo: 

[hugo-blog-demo](https://github.com/airinghost/hugo-blog-demo/)



## Documentation

No Docs now.

Please don't hesitate to start [Discussions](https://github.com/airinghost/hugo-theme-icarus-lite/discussions) in this repo if any questions or problems.

[Issues](https://github.com/airinghost/hugo-theme-icarus-lite/issues) also welcomed if any bugs found.



## Tips

### (1) Front Matter

Set `hidden: true` (YAML) / `hidden = true` (TOML) to hide the file from the index (homepage) view (i.e. posts using index.html template).

Set `date_hidden: true` to remove the date text & structure from the top left-hand of the article card in index, list and single views.

Set `read_more: true` to add a button at the bottom left-hand of the article card in index or list views; the button text is set at [Params] section in Config file, you can change it globally.

Set `read_more_txt: customText` to overwrite the text for the read-more button mentioned above.

Set `link_go: http://example.com` and `link_txt: customText` to add a button at the bottom left-hand of the article card in index or list views; it would open the link you set in a new tab in the browser.

### (2) Body Text

Don't forget to insert &lt;!--more--&gt; manually to your post or page file to generate the preview of the article, and it would look better.



## Acknowledgments

- PPOffice's awesome work on building such a beautiful theme for Hexo.

- Pedro Lopez's [*Creating a Hugo Theme From Scratch*](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/) guided me to the basic structure of a Hugo theme.

- Janne Kemppainen's [*Implemement Hugo List and Taxonomy Pages*](https://pakstech.com/blog/hugo-list-page/) helped me a lot on pagination.

- Tencent's [404 project](https://wj.qq.com/s2/9163450/732e/).

- Jeremy Thomas's [minireset.css](https://github.com/jgthms/minireset.css/).

- Cai Jimmy's [Stack](https://github.com/CaiJimmy/hugo-theme-stack/), a great card-style Hugo theme I like very much. And I made a use of some codes from his work, such as the main section at index template.

- Gimo's [futu](https://github.com/masakichi/futu/). I made a use of some codes from his work at navbar template.

- Oursky's [mockups generator](https://mockuphone.com/).



## P.S.

Hugo's `list.html` template enables us to build a list page in index(homepage) view. So if you are searching for the way to make Hexo generate pages like Hugo's list template, then I would like to recommend Jamling's work [`hexo-generator-index2`](https://github.com/Jamling/hexo-generator-index2).



## Repo Stats

[![HITS Unavailable](https://hits.dwyl.com/airinghost/hugo-theme-icarus-lite.svg?style=flat)](https://github.com/dwyl/hits)

