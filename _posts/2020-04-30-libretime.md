---
title: "Libretime Radio Automation"
date: 2020-04-30T12:33:46+10:00
layout: post
category: multimedia
img: /images/libretime-schedule-show.png
caption: A screenshot from the Libretime interface, from scheduling a Webstream in a show (Zachary Klosko)
excerpt: A platform is sometimes only as good as its user guide. I aimed to improve that for the Libretime Project.
---

Libretime is an open-source radio automation and playout software, designed for internet radio stations but increasingly used by low-power FM stations during the Coronavirus pandemic.

![](/images/libretime-header.png)
> Before (left) and after (right) screenshots of a website redesign for the Libretime project.

# Objectives 

1. **To give the project more control over our website.** The Libretime website was run using mkdocs, a documentation site builder, and was hosted by the project's Github repository. Mkdocs is relatively simple, but is directly designed for making documentation websites.
2. **To make our website more approachable.** One of the project's contributers had built out a custom splash page for us, but we couldn't publish it with mkdocs.
3. **To keep all materials for the project within one repository.** A move to Wordpress was considered, but would require us to spread out resources and make contributing to the documentation more difficult for volunteers.

[Jekyll](https://www.jekyllrb.com), a static site generator with native  Github Pages integration, helped us meet all of our goals with our website.

![](/images/libretime-docs.png)
> The main documentation page

![](/images/libretime-article.png)
> Layout and theming for the article pages

# Tools

- Jekyll, the static site generator
- Bootstrap, a theming framework using CSS and SASS
- Github Pages, for free hosting!