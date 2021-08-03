---
layout: single
permalink: /credits/
title: Credits
author_profile: false
classes: wide
date: August 1, 2021
icon: fas fa-info
order: 4
sidebar:
  nav: "about"
---

Obviously, [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme by Michael Rose. There is a lot to read/learn here, but then you get 'ah hah' moments as in 2+2= the sidebar for this page is comprised of this in the _pages/credits.md :

```yaml
---
sidebar:
  nav: "about"
---
```

and this in _data/navigation.yml

```yaml
---
about:
  - title: "About"
    url: /about/  
    children:
      - title: "CV/Resume"
        url: /assets/docs/Garth_Lancaster-Resume-2021Q2.pdf
  - title: "Credits"
    url: /credits/
---
```

... (note how the 'about' in the sidebar 'nav' matches the 'about:' yaml tag in the navigation)

Katerina Bosco's site [Cross-Validated](https://www.cross-validated.com/Personal-website-with-Minimal-Mistakes-Jekyll-Theme-HOWTO-Part-I/) has a lot of customisations and 4 pages of notes on 'how' she set things up.

## Tools

I use [Markdown Monster](https://markdownmonster.west-wind.com/) to edit the posts & pages. Markdown Monster has a Git client built-in, else;

I use [GitKraken](https://www.gitkraken.com/) for Git(Hub) Repository management.

I use [Sublime Text](https://www.sublimetext.com/) for editing text files - eg .yml configs .. check out Sublime Merge if you're interested in a great merge tool.
