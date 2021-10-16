

# Icarus-Lite

This is an one-column and card-style Hugo theme based on the Hexo theme [Icarus](https://github.com/ppoffice/hexo-theme-icarus).


## Documentation

No Docs.

Please don't hesitate to start a discussion in this repo if any questions or problems.


## Tips

Set `hidden: true`(YAML) / `hidden = true`(TOML) at `Front Matter` to hide it from the Homepage view (i.e. posts using index template).

Set `date_hidden: true` to remove the date text and its structure from the top left-hand of the article card in index or list views.

Set `link_go: http://example.com` and `link_txt: ButtonText` to add a Button at the bottom left-hand of the article card in index or list views; it would open the link you set in a new tab in the browser.

Insert `<!--more-->` manually to your post or page file and it would look better. Or Set `summaryLength: 1000` or more in Site Config and then insert `<!--more-->` at the end of the `.md` file if you would not like to make a summary of your posts or pages.

...


## Acknowledgments

PPOffice's awesome work on building such a beautiful theme for Hexo.

Pedro Lopez's [*Creating a Hugo Theme From Scratch*](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/) guided me to the basic structure of a Hugo theme.

Janne Kemppainen's [*Implemement Hugo List and Taxonomy Pages*](https://pakstech.com/blog/hugo-list-page/) helped me a lot on pagination.

Cai Jimmy's [Stack](https://github.com/CaiJimmy/hugo-theme-stack), a great card-style Hugo theme I likes very much. And I made a use of some codes from his work, such as the main section at index template.

Jeremy Thomas's [minireset.css](https://github.com/jgthms/minireset.css).

filament group's [*The Simplest Way to Load CSS Asynchronously*](https://www.filamentgroup.com/lab/load-css-simpler/) and Sukka's [*Improve FCP for My Blog*](https://blog.skk.moe/post/improve-fcp-for-my-blog/). I learnt a way of loading CSS files asynchronously from their posts.

thepeer's [solution](https://stackoverflow.com/questions/796087/make-a-div-into-a-link/3494108#3494108) for covering div with a link.


## P.S.

If you are searching for the way to make Hexo generate pages like Hugo's list template, then I would like to recommend Jamling's work [`hexo-generator-index2`](https://github.com/Jamling/hexo-generator-index2).


