---
layout: post
title:  "Create a Website for Free Using Github with little to no coding experience"
date:   2021-08-21 14:40:02 +0300
image:  website-sample.jpg
tags:   tutorial
---


**_for a video tutorial, please see the video posted on my [YouTube Channel](https://www.youtube.com/watch?v=NX7KVlbViA4)_**

When applying for a job position you are often asked to provide a Github account, and optionally a site.

In this tutorial I will teach you how you can build a Github website like this one we are currently on, for free. The only difference is that the site name will me `username.github.io`. Recruiters know what having the `github.io` means to a webpage and they will trust it.

If you don’t need a website for job applying, but rather want to have a blog to talk about a range of topics, this tutorial is also for you. 


## Create a GitHub Account (it's free!)
Go to [GitHub Page](https://github.com/) and create an account. Login in the account and then let’s go and decide what theme to use.

## Choose a Jekyll Theme (free or paid)

Use either of these two websites to find a theme you like 

[Awesome Open Source](https://awesomeopensource.com/projects/jekyll-themes)

[Jekyll Themes](https://jekyllthemes.io/free)

Note: Make sure to check out the Live Demo for the site to make sure it is still working. Some of the themes from the second site are not working. 
I have used [Zolan](https://github.com/artemsheludko/zolan) for this tutorial, but you can use any other you'd like. The process and the files would be very similar.
A great theme for developers that you should checkout is [Particle](https://github.com/nrandecker/particle).

## Fork Theme (aka copy the repository)
In GitHub, a repository represents a folder. When someone wants to copy a repository, the process is called "forking". 

In the top right corner of the github page, you should be able to see the image below 

![fork-image](images/fork.png)

Make sure to press the star button (it let’s the developer know that you love that theme) and then fork the project. You should see something similar to this:

![forking](https://github.com/codingroses/codingroses/blob/master/images/forking-process.png)

You will notice you are in the the same repository, but you are in your own copy of the repository, you are not in the original one. How do you know this? In the top left corner of the page, you will be able to see your own username.

We are now ready to start personalizing the theme! 

## Design the site

### README file
First thing I do is change the README file. It should always explain what the repository is about, and the organization, but also have information regarding the author of the theme (just 1-2 lines would be perfect).

*Tip*: Make sure to keep a tab open with the original repository’s README file as it will walk you through all the steps you need to be doing to set up the site.

### Structure of the files 
**_Please note this structure might differ on themes. Do not erase files unless you know what you are doing and don’t need them._**
The general structure would be the following folders _includes, _layouts, _posts, assets and some other files.

## Change repository name
In this step let’s change the site name to point to yourusername.github.io and change the repository name
In the main tab, click on Settings

![Settings](https://github.com/codingroses/codingroses/blob/master/images/settings.png)

Change the repository name to be your **username.github.io** since this is the link your site will be at. 

![repository](https://github.com/codingroses/codingroses/blob/master/images/name-repo.png)

Confirm by clicking rename. Then go back to Settings (it will send you back to the code once you renamed it) and scroll towards the bottom of the page to see GitHub Pages to see  the confirmation of your site name: 

![GitHubPages](https://github.com/codingroses/codingroses/blob/master/images/gh-pages.png)

**Note: You can only have ONE website with GitHub. **

## Set the `_config.yml` file
To edit the file, click the pencil located in the top right corner.

![edit-files](https://github.com/codingroses/codingroses/blob/master/images/how-to-edit-files.png)

Each theme might be different, but they are all very similar. Please be careful about this step of modifying and deleted unnecessary comments.

For example, we don’t need google_analytics as this will be a personal site. If you are creating a site for a service, you can keep this variable, otherwise you can take it out.

This is how I edited my page information. The github variable only need the username, same with LinkedIn. The theme will automatically write linkedin.com/username. 

![my-file-example](https://github.com/codingroses/codingroses/blob/master/images/page-info.png)

## How to save a file in Github 
To save changes, write a title of the changes you have done (this helps you keep track and even go back if you ever need to) and commit the changes. 

Once the page reloads, if you wish to do any more changes, you’ll have to click on Edit once again (the pencil icon).

![commit-changes](https://github.com/codingroses/codingroses/blob/master/images/commit-changes.png)

To go back to the main folder, simply click **Code** on the top left corner. 

## Change Fonts and Colour
The theme Zolan has the fonts in the **_sass/0-settings/_variables.scss_** file.

![Zolan-font](https://github.com/codingroses/codingroses/blob/master/images/fonts-zolan.PNG)

To change the colour, make sure to get the HEX of the colour you'd like. It looks like this #AAA111 (it has a # then 6 characters that can be numbers or letters). 
You can find this line in the same file folder: _sass -> 0-settings -> _variables.scss _

![zolan colour](https://github.com/codingroses/codingroses/blob/master/images/change-colour.PNG)

Example:
pink:  #e28693
purple: #46045d
blue: #0a42db

### Other themes
In other themes, locate the `_fonts_` folder

![other-themes](https://github.com/codingroses/codingroses/blob/master/images/index-htmlfile.png)

To select a new font, look at [Google Fonts](https://fonts.google.com/) for free, beautiful fonts, to use for your site. My favourite is Playfair Display 
Once you open up a font, click on the top right corner. Onto the one with the red dot on it.

![Google Fonts](https://github.com/codingroses/codingroses/blob/master/images/google-fonts-tutorial.png)

It will open up a side bar which has this information:

![Google font info](https://github.com/codingroses/codingroses/blob/master/images/google-font-link.png)

Copy the code and replace the two lines into the highlighted one mentioned before. 

![replace google font](https://github.com/codingroses/codingroses/blob/master/images/change-google-font.png)


Commit changes and let’s move on to the next step. We are almost done! 

## Update your About Repository section

On the right-hand side of your repository you’ll see this:

![Zolan about](https://github.com/codingroses/codingroses/blob/master/images/zolan-about-section.PNG)

Let’s change it to represent information about your site, and also link your site.

![about-section](https://github.com/codingroses/codingroses/blob/master/images/finally-done.png)

## Try your new website now! 
