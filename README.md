# lucydot-hugo
Content for my personal website.
Static webpages [here](https://github.com/lucydot/lucydot.github.io).

Website built using [Hugo](https://gohugo.io/) using the [code editor theme](https://github.com/aubm/hugo-code-editor-theme) with tweaks.

Tweaks
---

* changed date format to dd-mm-yyyy ([list.html](layouts/_default/list.html),[single.html](layouts/_default/single.html))
* adapted the "most recent posts" menu drop-down so that "post" `Type` pages are only listed ([menu.html](layouts/partials/menu.html)). Archetype [blog.md](archetypes/blog.md) sets `Type` "post" for all in `content/blog` as hack so that `content/blog` is not also listed. 
* changed the colour scheme ([\_variables.scss](static/css/\_variables.scss)):
 * cloned [bootstrap-sass](https://github.com/twbs/bootstrap-sass) 
 * installed [Sass](http://sass-lang.com/install) using gem
 * fixed easy bug on line 50 of theme.scss
 * compiled using 
``` sass --watch theme.scss:theme.css```
 * minified using 
``` curl -X POST -s --data-urlencode 'input@theme.css' http://cssminifier.com/raw > theme.min.css```
* changed code highlighting by linking to highlight.js library of choice ([highlightjs.html](layouts/partials/highlightjs.html))


TODO
---

- [ ] Insert image at bottom of menu 
- [x] Change favicon
- [ ] ...write some posts
- [x] Change background colour of code block in markdown
