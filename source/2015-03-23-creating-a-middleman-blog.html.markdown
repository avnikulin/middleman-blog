---
title: Creating a Middleman Blog
date: 2015-03-23 17:56 PDT
tags: software, middleman
category: ruby
---

If you've ever wanted to publish a blog on the web, you've had to decide which blogging software to use, with the most popular choice being WordPress. In my opinion, if you don't need a lot of dynamic content, it's better to use a static blog generator. 

[Middleman](https://middlemanapp.com/) offers the most potential for a professional, feature rich, and highly customizable static blog. Middleman is a [Ruby](https://www.ruby-lang.org/) Gem that relies on [Sinatra](http://www.sinatrarb.com/). Unlike traditional CMSs like WordPress, Blogger, and Drupal, it doesn't need to dynamically serve the content because it renders web pages into static HTML files which are then uploaded to a server.

Note: Middleman requires [Ruby](https://www.ruby-lang.org/). If you don't have it yet, install it now with a ruby version control manager like rvm or rbenv. After you've installed Ruby we can now install Middleman!

First let's install the Middleman gem:

~~~shell
$ gem install middleman
~~~

Next we're going to run the 'middleman init' command to generate a basic site. Run the following command where 'my\_new_project' will be your root project folder.

~~~shell
$ middleman init my_new_project
~~~

That's it for now, but sometime soon this article will be finished.