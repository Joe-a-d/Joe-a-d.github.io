---
layout: post
title: "Build Your Own Website"
description: "Detailed walkthrough on how to setup your own website"
comments: true
categories: Uncategorized
keywords: "jekyll, website, portfolio, thinkspace"
---

### Setting Up Github Pages

1. Fork my Github repository https://github.com/Joe-a-d/joe-a-d.github.io , or check the original here https://github.com/heiswayi/thinkspace

2. Change the name of your repository to <you_username>.github.io

3. Marvel at your new website

### Adding content

1. Create a new file with the following name <year>-<month>-<day>-<somename>.md

2. Start by adding the Front Matter within 2 pairs of 3 dashes (see image below, or open this post on Github) to the new file, this is important otherwise your page won't be formatted

![Home](https://github.com/Joe-a-d/joe-a-d.github.io/blob/master/assets/images/frontmatter.png "Homepage")

3. Write your content using Github flavoured [markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

### Basic Customising

You'll need to be somewhat familiar with CSS to change the style, the easiest way I think it would be to just run a search on the `main.css` file and change the properties of the desired elements from there directly. If it's not obvious what element needs changing I would suggest using "Inspect Element" on your browser and check the class name from there.

If you intend to create your own special layout you'll need to add the html file to the `_layouts` folder in your repository, and then use its name as the layout in the page's front matter. For an example of this see the difference between the `page` and `about_p` files in mine. I wanted the same default page layout, but I needed to add the contact form and categories list, so I've just duplicated the page layout and added those bits.
