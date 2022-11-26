---
title: "Colophon"
excerpt: "Notes on how, where, and why this website is made."
category: "Meta"
---
This is a personal website, designed, built, and maintained by me, Zinzy.

### About this space
- This website is casual, unpretentious, and unassuming.
- On here, you'll find soft stances, lived experiences, and critical notes on the things I hold dear. 
- It's organized as a casual collection of unfinished thoughts.
- This website lacks an archive or central index. Instead, it's a collection of linked files. I like that this is essentially a scavenger hunt.
- I use this website to participate in the IndieWeb, a great community of people who enjoy tinkering on personal websites, as well as independence while they do so.

### Technical details
- This website is built in [Jekyll](https://jekyllrb.com/), a flat-file content management system I've been using for years. I like my familiarity with the platform, as well as the light-weight nature of flat-file systems.
- I've taken [Maxime Vaillancourt](https://github.com/maximevaillancourt/digital-garden-jekyll-template) digital garden template for Jekyll as my starting point. I continue to change it on an almost daily basis.
- The font you're looking at is whatever is native to your operating system.
- I've borrowed elements from [Clay Harmon](https://www.clayharmon.com/)'s [Tufte Jekyll theme](https://github.com/clayh53/tufte-jekyll/tree/4bee109052ce50ac97f03efd41d4988a43f4a456) to achieve a particular style of sidenotes originating from the work of [Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte).

### To do on this website
- Proper case handling of note titles
- Github commit ID
- https://www.a11ywebsites.com/about/
- Optional POSSE to Mastodon
- Frontmatter Boolean for Implied Reader, TBC and others
- Tooltips for external/internal links
- [Automatically add tag and category pages ](https://github.com/sverrirs/jekyll-paginate-v2)


### Changelog
- 2022-11-19:
	- Added Indieweb post types article, note, and reply
	- Added outgoing webmentions
- 2022-11-20: added cross-post type support for bidirectional links (thanks to [this](https://github.com/florhizome/digital-garden-jekyll-template/commit/5ac71e7dd1d45bead5784936ca854ef62ba50437))
- 2022-11-21:
	- Added git submodule for Obsidian content
	- Added Netlify hook to check content submodule for updates on build