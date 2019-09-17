---
layout: post
title: "Github Page with Jekyll"
date: 2019-07-20
---
If you want to set up a personal page with several your social media links and some posts, Github Page with Jekyll might be the best combo.

Using Jekyll to set up a Github Page is extremely easy, you don't need to care any back-end stuff, no server, no database and no domain name. What you need to learn are the Jekyll usage and front-end knowledge such as html and css, and you write posts in markdown.

Behind the scenes, Jekyll generates the static site (html files), and Github Page hosts that generated site for you. Both of them are totally **free**.

I'm listing the tutorials I took, which help me build my personal page, and I believe they are also helpful to you.

- [jekyllrb.com](https://jekyllrb.com/): This is the official website of Jekyll, you can learn some key features of Jekyll and do a simple demo in 4 lines.
- [Step by Step Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/): It's the official detailed tutorial, which gets you familiar with Jekyll.
- [Jekyll Themes](http://jekyllthemes.org/): This is a website where you can find a lot of jekyll themes. After getting familiar with Jekyll, you may need to look for a theme you like. A theme can give a basic layout and save you lots of time. After downloading the theme you like, you start modify it in your way. I would recommand you to use git to track your modification.
- [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll): To make sure Github Page publishs your site just like you did locally, you need to use certain plugins for Github Page. Specifically, add `gem 'github-pages', group: :jekyll_plugins` to you Gemfile and run `bundle install`. Then, Github-Page-related plugins will be installed.
- [Deploying Jekyll to GitHub Pages](https://jekyllrb.com/docs/github-pages/#deploying-jekyll-to-github-pages): After your site is ready for publishing, create a github repository named `<your-github-account-name>.github.io` (for me, it's `luoos.github.io`), then push your project to remote master branch. After several seconds, you can navigate to `https://<your-github-account-name>.github.io/` to check your page.
- When you want to add a post, creat a markdown file under `_posts` folder, the filename should be under specific rule: `<yyyy>-<mm>-<dd>-<A-title>.markdown`.

In addition to above steps, there is another way you can set up your page quickly. You can just fork someone's Jekyll github repository, change forked repository name to `<you-github-account-name>.github.io`. Then open `https://<your-github-account-name>.github.io/`, you will find everything is done. After that, you could start to build your own page based on it.

You could try to fork my reposity - [sfwu.github.io](https://github.com/sfwu/sfwu.github.io) to do a test :-)
