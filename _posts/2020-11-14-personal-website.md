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

To boost success with my co-op search, I found myself doing what many young programmers do, making a portfolio website. I owe a lot of my inspiration to the following sites: thume.ca, joelonsoftware.com, mrmoneymustache.com, and devoncrawford.io (none of which I have any personal connection to). All of these sites impressed me, and I found myself frequently returning. In the documentation for Spacemacs, I found Tristan Hume's site, and I owe special thanks to him for introducing me to Github Pages's integration with Jekyll. At this moment in time, my static website is powered by Jekyll and hosted with Github Pages.

Before building this site, I had no experience with HTML and CSS but found learning about these new tools to be quite enjoyable. In general, I believe the what-I-want first how-I-am-going-to-do-it second approach to programming projects is the best way to expand technical skills. That being said, I do want to shoutout Mike Dane's Jekyll - Static Site Generator Tutorial for giving me a starting point for creating a Jekyll site. I intentionally chose not to use a prebuilt Jekyll theme. I felt that doing so would take away a lot of the work required for this site and consequently remove some of the satisfaction from completing it.

The organization of the source code is driven by Jekyll. Here is some insight into the organization:
* _drafts stores my unpublished blog and project drafts
* _includes stores repeated code such as the navbar, footer, and social icons
* _layouts stores the HTML structure of different types of pages on this site
* _posts are where blog and project posts live
* assets stores my CSS, Bootstrap 4, icons, and pictures
* Gemfile stores Jekyll configurations
* _config.yml stores site variables and settings
* blog, experience, index, and projects are the code of the four root pages of my site
* remaining items are not of notable significance.

<img src="/assets/quaini/img/personal-website-layout.png" class="img-thumbnail"/>

I am now at the point with my site where I believe my focus should be on filling in its contents and prioritizing other projects. In the future, I plan to return for improvements. Some things that I think I should add to this site are:
1. RSS feed.xml capabilities
2. Jekyll-seo-tag plugin to add metadata tags for search engines and social networks 
3. Comment section for project and blog posts 
4. Mobile formatting
5. A top posts by popularity display on the home page

Licensing, source credits, and extra resources are located in the README file of the source code linked above. More about why I started my blog can be read [here](https://quaini.io/blog/2020-11-14-welcome-to-my-blog/).
