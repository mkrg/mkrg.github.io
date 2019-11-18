---
layout: post
title:  "Assignment 1 questions"
date:   2019-11-18
categories: assignments
---
### What do you think of pre-compiling your CSS?
Although CSS is starting to offer alot of what a preprocessor like Sass is offering, I think for now it's still definitely helping keep the code shorter, less messy and more DRY, much thanks to being able to create mixins and use nesting.  
For this website, I used mixins, variables and nesting as much as I could. I really enjoyed being able to use mixins as this saves so much code. On the downside, Sass can be a bit trickier to understand and get used to. I quite like traditional CSS for how straightforward it is, whereas Sass is a bit more complex.

### What do you think of static site generators?
I think they're great and easy to work with for the right type of project. I think they work best for websites where you want to launch something quickly or perhaps a website with static content and not too much user interaction.

### What is robots.txt and how have you configured it for your site?
Robots.txt is a file that specifies which pages web robots are allowed to crawl.  
I've set mine to allow all robots to request any page.

### What is humans.txt and how have you configured it for your site?
Humans.txt is a file that contains information about the people behind the website.  
My humans.txt contains information about myself (name, email, git, location), a small thank you to the teachers, and information about the website (latest update, standards, components and software).

### How did you implement comments to blog posts?
I registered an account with disqus and set up comments for this website. I then added my disqus shortname to the config-file and copied my universal code to the disqus_comments-file.

### What is Open Graph and how do you make use of it?
Open Graph is a protocol where you can control what is displayed when your website is shared on for example facebook. This is done by using meta tags where the property is prefixed with "og:" and the content is what you would want to be visible for your website.  

```
<meta property="og:title" content="Malin's website">
```