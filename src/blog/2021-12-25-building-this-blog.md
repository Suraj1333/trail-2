---
title: Building this Blog.
date: 2021-12-25T06:25:45.965Z
tags:
  - post
image: /assets/cover-main.png
description: I am going to walkthrough about the steps, languages, and the
  software, that I have used to build this blog.
---
<!--StartFragment-->

**An Insight into the Blog Backend.**

~Suraj Kandlakunta[](https://github.com/kevin-powell/JAMStack-blog-starter)

The basic template for this blog is taken from the Kevin Powell [repository](https://github.com/kevin-powell/JAMStack-blog-starter), although the configurations and the code are written by me. This blog was a part of its website, but I have now linked this to my portfolio. The basic build of the blog starts with an idea using JAMStack, Eleventy Configuration, and Netlify CMS for the backend. The configuration of the Admin Panel is written in YAML. The blog build begins by building a template, and I have used Nunjucks to do it. I have created a base template for the blog structure and created individual .njk files featuring the header, footer, and other individual sections. As we type the blog in the admin section and we are done once doing that, as we hit publish, we see that the configurations in the CMS create a .md life locally on the server with the title, date, and time. And this .md file is pushed into the repo. The Netlify servers push these changes and deploy them onto the website, thereby creating a blog article later displayed on the website according to the templates we have mentioned before in the .njk files.

<!--EndFragment-->