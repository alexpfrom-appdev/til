---
layout: post
title: Three things I learned from The Ruby Koans
---

Here are (at least) three things I learned from [The Ruby Koans](http://rubykoans.com/):


1.	Error monitoring service. Create an assert_raise() and enter a type of key for the user to see. 
2.	Begin Rescue: If you don’t have a key in your hash that a user is trying to fetch, put in a begin and rescue to make the program work. 
3.	Only use begin and rescue when you HAVE to deal with exceptions. It is not good practice to just let issues be swept under the rug. 






Git Commits:

Git status          --  this shows you what you have committed 
Git branch -v    -- show all the branches you have
Git checkout main  -- this would take you back to main branch
Git checkout hello-world  -- these takes you to a specific branch (branches can only be one word)
Git checkout -b “name of new branch”   -- this is to create a new branch. You don’t need the quotes
Git add .   -   adds everything you just saved from all files
Git add ruby/acronym/acronym_test.rb  -- commits only the specific rb file
Git stash    -- takes you back to level before all of your commits
Git stash pop    -- if you decide you don’t want to “git stash” this moves you forward to the changes you made
