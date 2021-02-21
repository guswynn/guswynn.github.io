Currently this repo relies on 
[overriding the minina theme][https://github.com/jekyll/minima#customizing-templates]
in 2 places. This requires keeping these up to date, and their patches, with upstream:
- `_include/header.html`
- `_layouts/home.html`

This is because I am using github pages which requires a jekyll root, but I want a custom html
index, and I want things to link a certain way. If I switch to a different provider, I will setup
nginx or whatever to make it so I can use the default theme and have jekyll as a sub-page entirely. 
