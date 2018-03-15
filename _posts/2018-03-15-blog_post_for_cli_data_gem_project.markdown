---
layout: post
title:      "Blog post for CLI Data Gem Project"
date:       2018-03-15 16:03:14 +0000
permalink:  blog_post_for_cli_data_gem_project
---


For the most recent lesson in the Flatiron online curriculm, I have created a tiny program to read the calendar entries from the Des Moines Social Club's website. As usual, with Ruby, I am surpirsed at how easy this is to do using Nokogiri.

The assignment asked that we use good OO techniques.  So I created one class to read the calendar page and to display the information. In last lab these functions were split into two classes.  One to scrape a webpage of choice and one to display information found on that webpage.  Since this assignment has such a small scope, I have chosen to put both functions in the same class.

After completing this assignment I was reading the[ ruby style guide](https://github.com/bbatsov/ruby-style-guide/blob/master/README.md#document-annotations).  There is a suggestion to use modules when most l methods of an object are class level methods. This is the case with the program that I created.  If I were to improve the program I would change it to a module.

