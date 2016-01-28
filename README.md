# Django Starters

This repository contains a series Django starter templates.  Each template can be used as a starting point for your project.  The first template is an almost exact replica of the `django-admin startproject` template.  Each subsequent template adds additional configurations to `startproject`.  

### The Optimal Django Setup Environment

The idea of starting my projects with a well thought out, flexible and robust django development environment has always been a focus of mine.  A big part of this is having a solid beginning:  the template.  As I was developing my own templates, I looked at what <a href="https://www.djangopackages.com/grids/g/project-templates/" target="_blank">others were doing in the django community</a> and  reading through whatever I could find.  Fortunately, I was turned onto  <a href="https://www.twoscoopspress.com/products/two-scoops-of-django-1-8" target="_blank"> Two Scoops of Django</a> early on.  

Through a combination of building my own projects and reading projects written by others, I was able to develop my own templates that suited my needs.  Along the way, conscious of the sometimes steep learning curve and lack of practical, step-by-step outlines of how and why people organize their projects the way they do, I made some notes.     

This project takes those notes and seeks to illustrate the process that goes into creating a Django template.   

### The Structure

Each repository is a Django template that can be used as is.  Each template has a guide that outlines the changes made and why I made them.  All of these templates will work for Linux and OSX.  I will bring out a Windows version soon.  The reason why they won't work, out of the box, on Windows is because Vagrant requires some extra configuration to work on Windows. I will go over this at a future date. 

### Who this is for

At the moment, this project is geared towards <a href="http://zedshaw.com/2015/06/16/early-vs-beginning-coders/" target="_blank">early</a> to intermediate Django developers.  What is an early Django developer? At this point, you have already completed some tutorials like the <a href="https://docs.djangoproject.com/en/1.9/intro/tutorial01/" target="_blank">official Django tutorial</a> or <a href="http://tutorial.djangogirls.org/en/index.html" target="_blank">something similar</a> and maybe completed a small sized project with Django - like a blog.  Still don't know if you are an early Django developer?  Can you describe, with ease and clarity, what the `startproject` command does without referencing the Django documentation?  Yes?  You are good to go.

**NOTE:** Even if you haven't done anything with Django, this can still be a useful read.  Just because your a beginner does not mean you won't get anything out of it.  Give it a try!

### Goals

If this helps someone learn Django a little better, mission accomplished.  Thus, I am hoping that I can add something to the Django community and in support of this goal, I have tried to focus on a few things.

1.  One of my aims for this is objectivity.  I believe it is important to choose tools that work for you and your project.  With this in mind, there comes a point where you have to make a decision.  You, the reader, might not agree with some of the choices I have made.  Thus, in the name of objectivity and transparency, I have tried to flag as many sections where other choices could have been made.  When I come across these sections, I like to have a little discussion about why I did what I did and some of the alternatives available to you.

2.  I would like to keep this project well maintained.  In support of this effort, I will be setting up an automated process that will be able to test these templates on my behalf so they continue to be useful to the Django community.    

### Community Support

I am a believer in the community creating things together.  If you are reading through anything I have written here and find that it is incorrect, outdated or lacking in proper documentation, please feel free to make a PR.





