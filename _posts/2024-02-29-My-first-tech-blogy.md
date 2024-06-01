---
layout: post
title: My first tech blog
date: 2024-02-26
tags: [tech, python]
author: Kingsley Godwin
category: Tech
---

Welcome to my first tech blog. Thank you
## Unreleased version
- BREAKING CHANGE: Allow changing the order of the social network links that appear in the footer (#1152)
- BREAKING CHANGE: `google-scholar` social network link no longer requires the prefix `citations?user=`; if you previously set this parameter, it needs to be updated (#1189)
- Added `mathjax` YAML parameter to allow support for MathJax, used to write LaTeX expressions (#195)
- Added explicit support for favicons, you only need to add a `favicon.ico` file to the root directory
- The footer of a page always sticks to the bottom, even on short pages (#576)
- Added `author` YAML parameter to allow specifying the author(s) of a post (#1220)
- Fixed bug where hovering over search results showed the text "{desc}" (#1156)
- Added social network links for GitLab, Bluesky, Whatsapp, Untappd (#1168, #1218, #1299, #1307)
- Use CSS variables (#661)
- Added instructions and example on how to fix image links in project sites (#1171)
- Pagination buttons: use nicer arrows, and don't show text on small screens (#1221)
- Updated Yelp URL format - if you previously used the `yelp` social network config parameter, you might need to update the config value (#1259)
- Added `title-on-all-pages` config setting, that adds the website title to all page titles (#1272)
