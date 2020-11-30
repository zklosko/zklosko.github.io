---
title: "Libretime Radio Automation"
date: 2020-04-30T12:33:46+10:00
featured: false
layout: post
category: multimedia
img: /images/multimedia/libretime-schedule-show.png
caption: A screenshot from the Libretime interface, from scheduling a Webstream in a show (Zachary Klosko)
excerpt: A platform is sometimes only as good as its user guide. I aimed to improve that for the Libretime Project.
---

Libretime is an open-source radio automation and playout software, designed for internet radio
stations but has been increasingly by low-power FM stations during the Coronavirus pandemic.
While setting up a Libretime instance for WRIR, I noticed the instructions were hard to follow.

<!--more-->

I finally came across a video which explained an extra step the documentation left out.
I had been taking notes during the installation process and wondered if other stations had
been struggling too.

The documentation site included "Help edit this page" on each page, so I did.

![](/images/multimedia/libretime-header.png)
> Before (left) and after (right) screenshots of a website redesign for the Libretime project.

# Objectives 

1. **To give the project more control over our website.** The Libretime website was run using mkdocs, a documentation site builder, and was hosted by the project's Github repository. Mkdocs is relatively simple, but is directly designed for making documentation websites.
2. **To make our website more approachable.** One of the project's contributers had built out a custom splash page for us, but we couldn't publish it with mkdocs.
3. **To keep all materials for the project within one repository.** A move to Wordpress was considered, but would require us to spread out resources and make contributing to the documentation more difficult for volunteers.

One solution that would take care of all three objectives would be to use [Jekyll](https://www.jekyllrb.com),
a static site generator that was supported by Github Pages (our repository is hosted by Github).

# Tools

- Jekyll, the static site generator
- Bootstrap, a flexible theming template using CSS and SASS
- Github Pages, for free hosting!

![](/images/multimedia/libretime-docs.png)
> The main documentation page

![](/images/multimedia/libretime-article.png)
> How a documentation article displays