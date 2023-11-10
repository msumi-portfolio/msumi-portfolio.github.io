{% raw %}

## sitenotes

## setup new site
- create github repository and enable pages
- update github desktop account/publisher
- install jekyll in local directory https://jekyllrb.com/docs/
- copy over relevant files (ex: layouts, includes, data, sass, assets)
- cleanup _config.yml: add info, remove irrelevant items (ex: theme)

## new steps
- cleaning up layout (removed indexmain/side), includes (header/footer/nav), and main.scss
- fixing up flex gallery

## 2 column layout
- ✅ 1 data list, each item has 1st/2nd variable, alternating
  - 2 column: print column if var matches
  - 1 column: print straight through regardless of var
- change layouts based on screen width: show/hide entire layout
- having duplicate checkbox/lightbox code in both shown and hidden sections caused problems, so i moved it to its own separate for loop 👍

## item types
- header and normal text

(all images can click to expand)
- standard image gallery: 2 column responsive
- full width image
- video/storyboard presenter
  - google slides
  - convert pdf to ppt https://www.adobe.com/acrobat/online/pdf-to-ppt.html

{% endraw %}
