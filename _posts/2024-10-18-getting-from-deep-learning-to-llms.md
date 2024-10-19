---
layout: single
title: "Getting from Deep Learning to LLMs"
date: 2024-10-18 11:58:00 -0400
tags:
  - ai
  - llm
  - deep learning
---

5 years ago, I felt fairly in tune with the ML world. I understood how to solve
classification and clustering problems. I learned about neural networks and the
process of deep learning, and I tried writing my own feed-forward network to
showcase it. Of course this is a little bit ironic, because 2017 is when the
[Attention Is All You Need] paper was authored.

Fast track until now, and I'm completely behind. LLMs are a big change that
happened and I didn't know what led to its fruition. I wasn't sure how neural
networks fit into the picture anymore. Luckily I was recently recommended
[a 3b1b video] which explained this to me very well. This channel released many
useful videos which I watched those 5 years ago, and they taught me how key
concepts worked such as back-propagation. Early this year they
released follow up videos to connect the dots.

What I learned is that the feed-forward neural network is still relevant; it is
now the multilayer perceptron inside the transformer. In fact, there are
multiple multilayer perceptrons inside the transformer. The big new piece of the
puzzle is the attention block mechanism. Again, the 3b1b video explains it very
well, much better than I can do via markdown. To summarize anyway, it does some
mathematical tricks with dot products to find relevance from one word to
another, and this is represented via the dimensionality of the vector produced.

This bit of catch-up was a great relief. I feel primed to learn more, and
hopefully start developing with this stuff soon.


[a 3b1b video]: https://www.youtube.com/watch?v=eMlx5fFNoYc&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=6
[Attention Is All You Need]: https://en.wikipedia.org/wiki/Attention_Is_All_You_Need
