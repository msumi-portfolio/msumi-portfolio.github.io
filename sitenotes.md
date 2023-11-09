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
  1. ✅ 1 data list, each item has 1st/2nd variable? alternate
    - 2 column: print column if var matches
    - 1 column: print straight through regardless of var (use different layout based on screen width)
  2. ❌ 2 data lists, 1st/2nd
    - 2 column: print one list per column
    - 1 column: they'd simply stack? don't think you could alternate

## item types
- header and normal text

(all images can click to expand)
- standard image gallery: 2 column responsive
- full width image
- video/storyboard presenter

{% endraw %}
