---
layout: post
title: "Hello_Rake"
date: 2015-04-16 22:11:20 -0400
comments: true
categories: "Flatiron&nbsp;School"
---

I recently got my first taste of Rake, a powerful build language developed by Jim Weirich, a famous developer and contributor to the Ruby language. In addition to creating Rake, he was part of a team of developers who built RubyGems in 2003. 

Rake tops the list as the most downloaded gem of all time with current download numbers within striking distance of [70 million](https://rubygems.org/stats). It is a ubiquitous file management tool. Since I am new to Ruby and even newer to Rake, I thought it would be useful to provide a quick introduction to Rake. 

My first encounter with Rake was in my installation of this Octopress blog. I had no idea that I was also in such esteemed company as [Martin Fowler](http://martinfowler.com/articles/rake.html), who builds his website with Rake and wrote an extensive [blog post](http://martinfowler.com/articles/rake.html) about why he likes it. It's worth checking out. 

For starters Rake is a DSL. No, we aren't talking about an old-fashioned Internet connection. A DSL is a Domain Specific Language, which is essentially a computer language that's targeted to a specific purpose. CSS, regular expressions, and SQL are three other examples of DSLs that I have encountered so far. 

####Dependencies

One of the most useful aspects of using Rake is that it can track and group your programs dependencies. Every program has files that it requires to run and a Rake file is the perfect way of managing all of the files that make up your environment. 

####Namespaces 

For example, you can group different dependencies based on if you are working in a ``development`` or ``production`` environment. You aren't going to need your ``rspec`` testing files in a production environment or for your deployed web application. In theory, by the time its live, you have already tested things out. 

####Tasks

This is where Rake gets and gives instructions about how to run your program. You can describe or ``desc`` your tasks as well as give them ``prerequisites`` detailing other tasks to run before your task. 

####Arguments

A Rake task can also take arguments.  I won't go over the syntax here, but will point you to this very comprehensive guide. 

####Scheduling your scripts

As you get more comfortable creating and running your tasks with Rake, you might find that there are some you want to do outside of the regular testing cycle. Perhaps you want to test an email server in the middle of the night. Or schedule a monthly report. With Rake, you can do that! 

``cron`` is a Unix utility for scheduling and executing commands. You can access it from the command line by typing ``crontab -e`` called ``cron`` to use Rake to schedule your tasks. You might have a program that you want to test in the middle of the night (while you are sleeping). You can use rake to test it. 

You can read more about using ``cron`` to schedule command line [here](http://tutorials.jumpstartlab.com/topics/systems/automation.html). 


Rake is at the heart of a programmer's workflow. I will leave you with more thoughtful works from Martin Fowler: 

>Scripts are a natural for building stuff in many ways, and rake adds just enough features to provide a really good build system on top of a fine language. We also have the advantage that ruby is an open source language that runs on all the platforms that I need.

As my programs get more and more complex in terms of environment, function, testing, and dependencies, I'm looking forward to delving even deeper into its syntax and uses.  

You might have noticed that the title of this post is Hello_Rake... Well, that underscore wasn't my way of being "programmery". Octopress didn't like having Rake in the title of the post. I'm sure there was a way around that by escaping the characters properly, but I figured that's something for another day. 

Happy Raking. 





