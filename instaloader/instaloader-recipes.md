---
title: Basic Instaloader recipes
layout: page
parent: Instaloader
nav_order: 7
permalink: /instaloader-recipe/
---
# Instaloader

Here are a few basic “recipes” that you can copy/paste to do different things in Instaloader. Anything written below in brackets, e.g. [post], means that you should substitute the actual post ID / username / profile / whatever in (without the brackets) before you hit enter. 

You’ll probably need to login to Instagram to access the content:
instaloader --login=[your_username]

* You will then get an interactive prompt to enter your password. Type it in. (Note that you won’t see it on the screen as you’re typing). 

To set the folder where you want Instaloader downloads to go:
cd [drag and drop the folder onto Terminal window]

* When you drag and drop the folder, Terminal will type out the file path. Then hit enter. 

To download a single post (photo/video, caption, Instagram metadata):
instaloader -- -[post_id]

* Note the syntax: two dashes, space, one dash and  post id (with no space).

To download a single post, as above, but also with geotags and comments:
instaloader --geotags --comments -- -[post_id]


To download ALL pictures and videos of a profile, as well as the profile picture:
instaloader profile [profile]






