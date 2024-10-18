---
layout: single
title:  "Jekyll, to Gatsby, to Jekyll"
date:   2024-10-16 20:25:03 -0400
categories: jekyll update
author_profile: true
---

Originally I had used [Jekyll] to create my personal website. I wasn't acquainted
with Ruby at the time, and still, it was simple to learn and manage. Eventually
I discovered [Gatsby]. Gatsby fills a similar purpose. Both are static site
generators that make it easy to host a site through GitHub pages. Gatsby is
based on Node.js rather than Ruby, and lets you use React and GraphQL. This
sounded really good to me at the time since I was familiar with the stack, and
it was easy for me to add some code for page transitions and animations,
especially with [react-spring].

Fast-forward 4 years and my priorities have shifted. I wanted to update my site
again, however the maintenance cost was too high. I had an overwhelmingly large
amount of packages that needed major version updates, and it was overbearing to
look at. This isn't the type of project I wanted to have for my personal site,
so I switched back to Jekyll.

With Jekyll, I don't have to worry about this. Jekyll doesn't require many gems
to run, whereas Gatsby required multiple packages from all of the plugins.
Gatsby would of course have me install the world through node_modules, whereas
Jekyll requires very little. The Gemfile.lock is under 200 lines! For a casual
project with a low update frequency, this is far more bearable. I will happily
sacrifice my beloved TypeScript, React, GraphQL, Et Al for simplicity.

To my surprise, GitHub Pages can also now automatically deploy jekyll sites
without us needing to write any CI YAML files ourselves!


[Jekyll]: https://jekyllrb.com
[Gatsby]: https://www.gatsbyjs.com
[react-spring]: https://www.react-spring.dev
