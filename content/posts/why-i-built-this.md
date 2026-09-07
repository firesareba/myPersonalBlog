---
title: Why I built this
slug: why-i-built-this
author: Simha
date: '2026-08-20'
tags:
  - meta
  - self-hosting
featuredImage: >-
  https://github.com/firesareba/myPersonalBlog/blob/63c087207f800aee8f2a238e71088150ec8c34e7/assets/1788758796294-Screenshot_2026-09-06_at_10.26.19___PM.png
published: true
excerpt: Every other blogging platform wanted to own my content. This one doesn't.
---
why i built this

so most blog platforms suck in one of two ways. either they own your content (wordpress db, wix, whatever, try leaving with everything intact, good luck with that) or they're technically yours but a pain in the ass to actually touch, like static site generators where changing one heading color means digging through a build config for 20 minutes.

and then there's the visual builder type platforms. those are fine i guess but you're still trapped, just in a nicer looking cage. you didn't actually gain control you just got a prettier form to fill out.

wanted something where the repo just IS the site. no database, nothing hidden, nothing exported into some proprietary format when you finally get sick of it. you edit stuff through a builder ui but under the hood it's all just writing to normal files. clone the folder and you have the entire thing. every post, every style change, all of it, sitting right there as plain text you can read without the tool at all.

how it works roughly:

- theme is just html with some extra tags marking what's editable
- builder reads that and gives you an actual editor instead of making you touch raw html
- edits get written to files, json or markdown depending on what it is
- publish spits out plain html/css at the end, nothing fancy, no react no build step, you could host the output literally anywhere

git handles all the history too so if i mess something up i can just go back, which honestly is half the reason i trust this more than clicking around in some dashboard.

still messing with themes. current one's fine but kinda plain, might build a couple more when i feel like it, might not.
