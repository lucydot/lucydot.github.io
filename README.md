# lucydot-hugo
Content for my personal website.
Static webpages [here](https://github.com/lucydot/lucydot.github.io).

Website built using [Hugo](https://gohugo.io/) using the [code editor theme](https://github.com/aubm/hugo-code-editor-theme) with tweaks.

Tweaks
---

* changed date format to dd-mm-yyyy ([list.html](layouts/_default/list.html),[single.html](layouts/_default/single.html)) and removed time of post
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
* created an (almost empty) index.html for a blank landing page as I don't like the lack of markdown formatting in the list.html used previously.

How to clone the repo to a new 'puter
---

This is for future Lucy. She will thank me for it. 

Clone the repo with content (not the repo with the generated content).
```  
git clone https://github.com/lucydot/lucydot-hugo/edit/master/README.md
```

Add the public submodule. This has the static repo set as upstream.
``` 
git submodule add -b master git@github.com:lucydot/lucydot.github.io.git public
```

Add the themes submodule.
```
git submodule add https://github.com/aubm/hugo-code-editor-theme themes/code-editor
```

How to add a new post
---

Create a new entry
``` 
hugo new blog/<blogname>.md
```

Edit the post
``` 
vim ./blog/<blogname>.md
```

Inspect changes locally (optional)
``` 
hugo server
```

Deploy 
```
bash deploy.sh
```


TODO
---


- [x] Change favicon
- [ ] write webpages
- [x] Change background colour of code block in markdown
- [ ] remove date of posts
- [ ] change index heading to filesystem
