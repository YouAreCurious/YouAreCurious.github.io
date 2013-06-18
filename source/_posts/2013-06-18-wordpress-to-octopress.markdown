---
layout: post
title: "Moved from Wordpress to Octopress! Simple, Faster and More Reliable!"
date: 2013-06-18 08:07
comments: true
categories: Technology
tags:
- Blogging
- Technology
- Web
- Programming
description: "I moved to Octopress because its fast, customizable and simple! You write posts and customize the site on your own machine. Then you generate static.."
---

![Octopress](/images/post-images/2013/06/octopress.jpg"Octopress")

I just moved this blog to a more simpler, faster, more customizable and a reliable blogging platform! Octopress ... Its built on [Jekyll](http://jekyllrb.com/) which use [Ruby](http://www.ruby-lang.org/en/) to create a simple blogging framework that work with [Markdown](http://daringfireball.net/projects/markdown/). You write posts and customize the site on your own machine. Then you generate static HTML files using the Octopress framework and push them to your web host. Any simple host will do! You can even get free hosting on Github! How cool is that?

<!-- more -->

I used Wordpress since 2009. Currently, its the most widely used blogging platform in the world. Its full of features. You can use plugins to add more additional features. But, sometimes, you can get lost with these features. Too much of everything is good for nothing. Wordpress is not simple. Now its very complex. There are a lot of features that I don't need. But I can't remove them and they keep slowing down my site. Wordpress is a dynamic website. When a person visit your website, the server will execute php scripts to generate the website and then give it to the user. We can use caching plugins to reduce the server load but still it can get slow! Normally, Wordpress websites need more resources from the server. You constantly need to upgrade your server in order to keep the blog alive.

### How Octopress work?

As I said earlier, Octopress runs on your own machine. Not in the web server. You need to setup the site, customize it and write the posts in your machine. To write posts, you just have to place a Markdown file in the **_posts** folder with the content of the post. After you are done, you have to issue two commands. ```rake generate``` will use the customizations you added, the settings, the plugins, the layouts, the posts and pages you added and build the whole site with static HTML files in a separate folder. That folder doesn't have any serverside language. Next, ```rake deploy``` will send the website to a remote server. If you use Git, it will automatically prepare separate branches that you can deploy and push to the right server. The server will have a static website which will be extremely fast! If you want, you can even preview a live version of the blog on your own machine before pushin with ```rake preview```

### Octopress doesn't have a lot of complicated features but you can add them...

Octopress doesn't have a lot of complicated features. But its higly customizable and you can add the features you need. The source files are easy to understand. Doesn't have complicated php scripts like in Wordpress. Have some ruby bits but not too much.

### Its easy to customize...

You have the source for the website on your local machine. No need to edit files and upload to test them like many people do in Wordpress. You can run a live preview on your own machine and deploy it to the real web server only when its ready.

### Octopress is really fast...

Its extremely fast. Because there is nothing to generate dynamically, the server doesn't get a big load like in Wordpress. The server just have to serve the HTML files to the user.

### Its easy to find a good host and Github will host your site for free!

A simple basic host will be enough to host an Octopress website. Every basic webserver have the ability to serve HTML files. So, you don't have to pay large amounts. If you are ok with open sourcing your site, then you can use Github to host your website! Its completely free and highly reliable!

### You don't need to keep backups and its really easy to migrate to a new host...

You have the website on your local machine. You only generate and push the HTML files to the server. If you go to a new web server, you just have to push them again to the new address. No need to setup databases and run installation scripts. You also don't need to keep backups because you already have everything on your machine. If you use Git, you can push everything to Github or Bitbucket.

Some people move to Octopress because they love to blog in Markdown. I have only used Markdown to write readme files of several projects. I moved to Octopress because its fast, customizable and simple. Still there are some websites which need dynamic stuff. But a normal blog won't need them. So, I think I can use it for You Are Curious. Octopress is a bit geeky. They say its for hackers. But normal people who have some brains can figure it out. Im already a Rails developer and its not hard for me.

### Will I Move [Tech Hamlet](http://techhamlet.com/) to Octopress?

That might not happen. TH is a heavy site and its not easy to convert everything to Octopress. I might develop my own blogging platform with [Rails](http://techhamlet.com/2013/05/install-ruby-on-rails-in-ubuntu/) or something better for TH. If I do that, I will open source it and let everyone use it. It will be something big! You'll love it! So for now, just try [Octopress](http://octopress.org/) and see whether you can get used to it!