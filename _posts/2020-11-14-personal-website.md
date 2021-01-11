---
layout: project
title: "My Personal Website and Blog"
categories: projects personal
permalink: /:categories/:title
date: 2020-11-14
description: My personal website and blog. Built to serve as a developer portfolio and personal archive.
stack: HTML, CSS, Jekyll, Github Pages
source: personal-website
sourceurl: "https://github.com/quaini/personal-website"
picture: /assets/quaini/img/personal-website.png
---

To boost success with my co-op search, I created a personal portfolio and blog website, quaini.io. While reading the documentation for Spacemacs, I found Tristan Hume's [personal site](https://thume.ca/) where I first saw Github Pages's integration with Jekyll. At this moment in time, my static website is powered by Jekyll and hosted with Github Pages.

Before building this site, I had no experience with HTML and CSS but found learning about these new tools to be quite enjoyable. In general, I believe the "what-I-want first how-I-am-going-to-do-it second" approach to programming projects is the best way to expand technical skills. That being said, I do want to shoutout Mike Dane's [Jekyll - Static Site Generator Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) for giving me a starting point for creating my Jekyll-powered site. I intentionally chose not to use a prebuilt Jekyll theme; I felt that doing so would take away a lot of the work required for this site which would removce the learning opportunity and eventual satisfaction from completing it. Key resources used for this project are Bootstrap 4.5's framework and Zest Social Icons.

The organization of the source code is driven by Jekyll. Here is the folder structure:
* _drafts:		my unpublished blog and project posts
* _includes:	repeated page elements such as the navbar, footer, and social icons
* _layouts:		various page type formats
* _posts:		where my blog and project posts live
* assets: 		CSS, Bootstrap 4, icons, and images
* Gemfile:		Jekyll configurations
* _config.yml: 	site variables and settings
* blog, experience, index, and projects.html are the four root pages of my site

Remaining items are not of notable significance.

<img src="/assets/quaini/img/personal-website-layout.png" class="img-thumbnail"/>

At the time of writing this, I believe that this site does enough and that I should shift my focus to filling in the contents and prioritizing other projects. In the future, I plan to return for improvements. Some things that I think I should add to this site are:
1. RSS feed.xml capabilities
2. Jekyll-seo-tag plugin to add metadata tags for search engines and social networks 
3. Comment section for project and blog posts 
4. Mobile compatibility
5. A top-posts-by-popularity display on the home page

Licensing, source credits, and extra resources are located in the README file of the source code linked above. More about why I started my blog can be read [here](https://quaini.io/blog/2020-11-14-welcome-to-my-blog/).
