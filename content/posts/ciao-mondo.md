---
weight: 1
title: "Getting started (and setting up Hugo)"
date: 2023-08-25T12:30:01
description: "A guide to getting your own blog setup with Hugo"
tags: ["hugo", "blog", "markdown"]
type: post
showTableOfContents: true
---
# Ciao mondo!


![hello world](https://media.tenor.com/mGgWY8RkgYMAAAAC/hello-world.gif "ciao mondo")

For a good while, I've been promising that I'll to setup a 'proper' personal blog site and claim my corner of the web 😄.

The intention is to start documenting and sharing some of the engineering work I'm doing and the things in life that I find interesting.

As a busy engineer, building things at [Deliveroo](https://www.deliveroo.co.uk) and a doggo parent, I had a few requirements for my new blogging platform:

- easy to get started;
- simple to add content over time;
- flexible and customisable;
- good documentation and community support.

So, the first step was choosing the appropriate tool for the job!

I've come across a few different static site generators before, including:
- [Gatsby](https://www.gatsbyjs.com/)
- [Jekyll](https://jekyllrb.com/)
- [Hugo](https://gohugo.io/)

In the end, I chose [Hugo](https://gohugo.io/), because I liked the promise of configuration-driven simplicity and fast build times. The promise lived up to expecation when I was - for example - able to add the 'typewriter' effect to the index page by simply injecting some custom CSS into the `config.toml`.

It took me less than an hour to get 80% of the way there. As always, YMMV with the other 20%, as you could spend as much or as little time as you want perfecting things!

# Getting started with Hugo

There are three easy steps that I'll signpost to in the [excellent documenation](https://gohugo.io/documentation/):

### (1) Hugo setup
For anyone wishing to setup a personal site with Hugo, you can check out their excellent installation guide [here](https://gohugo.io/getting-started/quick-start/).

### (2) Pick a theme
I chose the the Gokarna theme, partly because it's simple and looks great. It also stirred up some great memories of my travels in India 😁.

I won't rehash the install instructions already provided by the authors, but do check them out [here](https://gokarna-hugo.netlify.app/posts/theme-documentation-basics/).

### (3) Deploy

Lastly, you can deploy your built, static site to a bunch of different places.

I chose Github Pages for simplicity and no infrastructure management (and to replace a ghastly, old personal site I made). If you wanted, though, you could [serve the site from AWS S3](https://gohugo.io/hosting-and-deployment/hugo-deploy/), for instance.

If you'd like to do the same, you can follow the guide [here](https://gohugo.io/hosting-and-deployment/hosting-on-github/). I'd highly recommend setting up a deployment pipeline for your site, since it'll save you a lot of manual toil and help you focus on delivering content. For this kind of use-case, Github Actions is a great; a free option that lives alongside your code (assuming your SCM of choice is Github).

Hopefully that helps you get off the ground with your own site 🚀.

Here's to some future content!