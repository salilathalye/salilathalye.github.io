---
layout: post
date: 2025-03-01T11:41:20 -0500
title: 'A new plugin for nvim to create jekyll posts'
categories: [Bespoke] 
tags: [nvim] 
---

After setting up this github.io SSG page using cotes2020's [jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) (thanks cotes2020!) theme and following all the documentation to get DNS and https setup, I started to search for an easier way to edit posts. My recent foray into crafting a bespoke nvim setup led me to search for a lua plugin that might help ease the creation of markdown posts. One has to use specific front-matter in the markdown (which immediately reminded me of Obsidian and Logseq). My search led me to kanedo and his jekyll.nvim plugin which I immediately downloaded and put to use to create this post. With my lazy nvim setup it should be straightforward to update the plugin to keep up with kanedo's great work! You can find the plugin on github [jekyll.nvim](https://github.com/kanedo/jekyll.nvim). Follow the instructions to add the plugin and then there are a few commands such as :JekyllPost which will ask for a title and then create a markdown file with the timestamp and add the front matter. I found this to be a real timesaver. Thank you kanedo!
