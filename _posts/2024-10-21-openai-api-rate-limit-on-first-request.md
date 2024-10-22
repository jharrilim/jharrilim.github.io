---
layout: single
title: "OpenAI API Rate Limit on First Request"
date: 2024-10-21 00:0:00 -0400
tags:
  - ai
  - openai
  - rate limit
  - 429
---

I decided to try out OpenAI's API for the first time yesterday. From what I saw
within the developer dashboard, it seemed like I would be use it without paying
anything up until a certain token or request limit. It seems like this was not
the case. If you make an API request with the token you generate and you haven't
added any payment information and credits, you will always get a 429 error.

Ultimately it's cheap enough to start with so I don't mind, but worth sharing in
case anyone else runs into this.

---

If you want to see what I'm using it for, check out [total-thought]. In Total
Thought, users are able to write out topics to discuss, such as "Should I use
the gym or build my own home gym?", write the pros and cons of each (others can
also contribute!), and then crowdsource upvotes on each pro and con. I am using
gpt-4o-mini to summarize all of this data and try to give a reasonable
suggestion on which one to choose.

[total-thought]: https://total-thought.com

