---
layout: post
title:  "How I got my Jekyll page started!"
date:   2023-07-17 20:45:53 -0400
# categories: jekyll update
---

in commandline:
install Ruby, gem, jekyll

gem install jekyll bundler
jekyll -v 
jekyll new name_of_site
cd name_of_site

to serve first time:
bundle exec jekyll serve
after initial:
jekyll serve
navigate to local server (localhost:4000)
to serve with drafts:
jekyll serve --draft


want to add a different theme?
go to the "Gemfile" and add the line:
'gem name-of-theme' under the other gems already there
commandline: bundle install

in the config.yml, update the theme to:
theme: name-of-theme

re-run:
bundle exec jekyll serve
(some of the layout names may not be the same across different themse, will need to re-name those)