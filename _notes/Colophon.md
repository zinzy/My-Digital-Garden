---
excerpt: "Notes on how, where, and why this website is made."
---
This is a personal website, designed, built, and maintained by [[About|me, Zinzy Waleson Geene]].

### Technical details
A full overview of the technical implementation of this website can be found in my [`humans.txt` file](/humans.txt).

### Copyright
Unless otherwise stated, everything on this website is licensed under [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode), which means: share (and change) my work but say it's mine, don't use it for profit, and use the same license.

### Philosophical
This website is a vastly personal project. It contains soft stances, lived experiences, and critical notes on the things I hold dear. I use this website to participate in the [[IndieWeb]]. I believe in [[Think in public]], and having it be an act of [[Anti-marketing]]. This space isn't allowed to pressure me to be smart, funny, insightful or anything else that I am not on a permanent basis. I don't pretend to be involved in current events, and because of that you may find me discover things you've known about for ages already.

### Content
On this website, I mostly share two types of content: dated posts, sorted chronically in a [[Blog]], and my [[Notes|working notes]], which are updated frequently as I learn and develop my unfinished thoughts. If you spot anything that you think is wrong, [[Hello|let me know]].

### Design
This website is a text-mostly website, meaning it is designed to focus on the written word. I hope it provides a comfortable reading experience regardless of the screen you have. There's a color theme for light mode, as well as dark mode. I'm in the process of making my website fully accessible.

### To do on this website
- Proper case handling of note titles
- https://www.a11ywebsites.com/about/
- ~~Optional POSSE to Mastodon~~ (doesn't work with my [[Slow web]] approach)
- Frontmatter Boolean for Implied Reader, TBC and others
- Tooltips for external/internal links
- ~~[Automatically add tag and category pages ](https://github.com/sverrirs/jekyll-paginate-v2)~~ (opted for densely-linked materials)
- Letting posts and working notes use the same tags

### Changelog
- 2022-11-19:
	- Added Indieweb post types article, note, and reply
	- Added outgoing webmentions
- 2022-11-20: added cross-post type support for bidirectional links (thanks to [this](https://github.com/florhizome/digital-garden-jekyll-template/commit/5ac71e7dd1d45bead5784936ca854ef62ba50437))
- 2022-11-21:
	- Added git submodule for Obsidian content
	- Added Netlify hook to check content submodule for updates on build
- 2022-11-26:
	- Initiated singular Obsidian vault that automatically pushes relevant content to Netlify
- 2022-12-02: got incoming webmentions fired up 🥳
- 2022-12-02: added [styled RSS feed](https://www.zinzy.website/feed.xml)
- 2022-12-04: added [humans.txt](humans.txt)
