# minimald6

minimald6 RPGs

* Built with [Jekyll-db](https://github.com/rypan/jekyll-db), which uses [Jekyll](http://jekyllrb.com/), [ListJS](http://listjs.com/), and [Bootstrap](http://getbootstrap.com/).


## View RPGs
[Visit the website](https://yochaigal.github.io/minimald6/)

## Submit an RPG
[Create a new file here](https://github.com/yochaigal/minimald6/new/gh-pages/_posts) and submit a pull request.  
File name format is `{[currentyear}}-{{currentmonth}}-{{currentday}}-{{rpgname}}.md`.  
Example: `2018-01-18-minimald6-rpg-name.md`.

Verify that the chosen date is not in use for the RPG you want first.

### File Format
Example format below. Copy and paste and change for the playbook you're submitting. You can also choose an existing file as a template.

```yaml
---
layout: entry
link: http://www.game.url
author: ['Jane Doe', 'John Smith']
source: Where you Fond it
source-url: http://minimald6-game.url

excerpt: Put the description of the game here. Keep it short; no more than 200 characters
 will display.

categories:
- category (use an existing category please, otherwise you'll get a not-found)

license: cc-by, cc-by-sa, non-open, unknown
cost: paid, free, pwyw

tags:
- setting (if there is one)

---

  Any content you want shown on the individual entry page should go here. If you don't use an
  explicit excerpt field above, one will be generated here, using the first 200 characters.
  Note: Please use your own words or just a short quote from the product page.

```
