---
layout: project
title: "Animator"
date: 2020-4-15
categories: projects school
permalink: /:categories/:title
description: Final project for Object-Oriented Design. A Model-View-Controller architecture designed to animations.
stack: Java, Java Swing, JUnit
source: Only available upon request for prospective employers.
sourceurl: ""
picture: /assets/quaini/img/animator.png
---
As a final partner project for Northeastern's CS3500: Object-Oriented Design, my class was required to generate an animator that met various criteria. The goal of the project was to improve our understanding of design patterns, commenting for other maintainers, building large-scale projects, meeting changing requirements, comprehensive testing, and working with other's code. The animator follows the Model-View-Controller design pattern and features four views: text, svg, visual, and an editable view. The visual and editable views are built with Java Swing. After finishing our implemention of the animator, we were challenged to reimplement the project using our model/controller alongside another group's set of views. This experience opened my eyes to how easy it is to leak implementation details as well as the planning required to flesh out a project of this scale (3,000+ lines of test code and 3,000+ lines of project code). The project features 81 feature-unique unit tests written with JUnit 4. The source code for this project is kept hidden because this project is still occasionally used for the course.

Below is a video of our animator running in the editable view:

<video controls="controls" width="800" height="600" name="Animator in Action" src="/assets/quaini/img/big-bang-crunch.mov"></video>
