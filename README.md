# lucydot-hugo
Content for my personal website.
Static webpages [here](https://github.com/lucydot/lucydot.github.io).

Website built using [Hugo](https://gohugo.io/) using the [code editor theme](https://github.com/aubm/hugo-code-editor-theme) with tweaks.

Tweaks
---

* changed date format to dd-mm-yyyy ([list.html](layouts/_default/list.html),[single.html](layouts/_default/single.html)
* adapted the "most recent posts" menu drop-down so that "post" `Type` pages are only listed ([menu.html](layouts/partials/menu.html))
* changed the colour scheme ([\_variables.scss](static/css/\_variables.scss)):
 * cloned [bootstrap-sass](https://github.com/twbs/bootstrap-sass) 
 * installed [Sass](http://sass-lang.com/install) using gem
 * fixed easy bug on line 50 of theme.scss
 * compiled using 
> sass --watch theme.scss:theme.css
 * minified using 
> curl -X POST -s --data-urlencode 'input@theme.css' http://cssminifier.com/raw > theme.min.css

TODO
---

- [ ] Insert image at bottom of menu 
- [ ] Change favicon
- [ ] ...write some posts
