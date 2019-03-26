---
title: Back to building the website
author: Jinyi
date: '2019-03-26'
slug: back-to-building-the-website
categories: []
tags: []
---

Back to building my own website using Rstudio. It has been a shawshank redemption for me for the past two years. I cannot say it's going to be great now but I will keep working on it.

Anyway, there are many changes including a new laptop. I then ran into the question regarding "clone a GIT repository into a non-empty directory."  I copied my r project files from my old laptop and now I want to continue to build the website. Here are the steps I did to make it worked:

(1) before doing so, I created a new SSH key for my new laptop:

create SSH key
https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account
Generating a new SSH key and adding it to the ssh-agent
https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
test SSH connection
https://help.github.com/en/articles/testing-your-ssh-connection

(2) then following these two websites, I was able to finally push my commits:

https://gist.github.com/davisford/5039064
https://stackoverflow.com/questions/10904339/github-fatal-remote-origin-already-exists

I only do the following steps:
$ git remote set-url origin git@github.com:githubaccount/githubrepo.git
$ git add -A
$ git commit -m 'first commit'
$ git push

During this process, I was prompted to enter my passphrase. Then, it worked well for me~

