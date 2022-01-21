---
title: Basic Instaloader recipes
layout: page
parent: Instaloader
nav_order: 2
---
# Instaloader

Here are a few basic “recipes” that you can copy/paste to do different things in Instaloader. These commands are all executed in your Terminal (see [Installing Instaloader](https://yvonneng.github.io/instagram-collecting/ for more on using Terminal). 

Note that in the code examples, notes in \[BRACKETS\] mean you need to subsitute with the specific username or ID you want.

## Login
You’ll probably need to login to Instagram to access the content.
```
instaloader --login=[YOUR-USERNAME]
```
> You will then get an interactive prompt to enter your password. Type it in. (You won’t see the password on the screen as you’re typing). 

## Set the folder where you want Instaloader downloads to go:
```
cd [DRAG AND DROP THE FOLDER ONTO THE TERMINAL WINDOW]
```
> When you drag and drop the folder, Terminal will type out the file path. Then hit enter. 

## To download a single post (photo/video, caption, Instagram metadata):
```
instaloader -- -[POST-ID]
```
> Note the syntax: two dashes, space, one dash and  post id (with no space).

## To download a single post, as above, but also with geotags and comments:
```
instaloader --geotags --comments -- -[POST-ID]
```

## To download ALL pictures and videos of a profile, as well as the profile picture:
```
instaloader profile [PROFILE-ID]
```





