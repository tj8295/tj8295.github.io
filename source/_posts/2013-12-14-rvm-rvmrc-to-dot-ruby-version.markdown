---
layout: post
title: "rvm rvmrc to [.]ruby-version"
date: 2013-12-14 03:40:23 -0500
comments: true 
categories: ruby
---

Today when I brought up Terminal and entered a folder with a .rvmrc file I got the following warning: 

*You are using '.rvmrc', it requires trusting, it is slower and it is not compatible with other ruby managers, you can switch to '.ruby-version' using 'rvm rvmrc to [.]ruby-version' or ignore this warning.*

After a quick check on stackoverflow I found the following:
external-url: http://stackoverflow.com/questions/15708916/use-rvmrc-or-ruby-version-file-to-set-a-project-gemset-with-rvm

It seems that when only the ruby version and gemset need to be specified for a project, the preferred method is to specify a .ruby-version file, and if a specific gemset is needed, a .ruby-gemset file. 


Notes:
I am using Ruby version 2.

The use of .ruby-version and .ruby-gemset may not be compatible with some programs.

Information about .rvmrc files: 
external-url: https://rvm.io/workflow/rvmrc
