---
title: "Notes on my web mastery"
date: 2022-11-21
tags:
- IndieWeb
- Web development
- Tinkering
---
Recently, I've been making some great progress with my personal website. While I normally don't engage in elaborate technical descriptions of my online life, I feel it's relevant to document what I've learnt and done, if only for posterity.

### The setup of this website
- This website runs on [Jekyll](https://jekyllrb.com/), an open source flat-file content management system. This means, among other things, that I don't need a database to access my files. I like to have my work sit in a folder that I can move around because I believe [[Tools don't matter]]. Jekyll allows me to do just this.
- Its code lives on Github, and 

### Writing
Many of the things I write are not for public consumption, but they are closely linked to things that *are*. Currently, I have one [Obsidian](https://obsidian.md/) with two folders: one for private use, and one that contains what essentially is my [[Digital garden]]. 

### Publishing
- The Obsidian plugin [obsidian-git](https://github.com/denolehov/obsidian-git) manages the version control of my vault
- The Github action [Push git subdirectory as branch](https://github.com/marketplace/actions/push-git-subdirectory-as-branch) publishes the public contents of my vault to a separate repository
- The public contents are pulled into my code base as a submodule, and [Netlify looks for updates before a build](https://mtsknn.fi/blog/netlify-updating-private-git-submodule/)