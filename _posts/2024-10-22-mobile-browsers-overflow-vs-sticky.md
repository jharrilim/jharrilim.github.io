---
layout: single
title: "Mobile Browsers: Overflow vs Sticky"
date: 2024-10-22 00:0:00 -0400
tags:
  - css
  - mobile
---

A common thing you want on sites is to have a header that is always at the top,
so that users don't have to scroll all the way up the page to reach the header's
navigation.

One thing you can try is setting the body to `overflow: hidden`, and then
putting `overflow: auto` on the content under the header. This will make the
header stay in its spot, while the content underneath can be scrolled.

This works well on desktop browsers (including desktop browsers that are in
"mobile mode"), but on mobile browsers, it doesn't work as expected. Instead,
you can't scroll fully. This is because the mobile browser includes its own
header and footer in height calculations, so you can't actually scroll to see
the bottom of the page.

![](/assets/images/2024-10-22-mobile-browsers-overflow-vs-sticky/overflow.png)

If you instead use `position: sticky` on the header, it will stay in its spot,
and you can scroll to the bottom of the page.

![](/assets/images/2024-10-22-mobile-browsers-overflow-vs-sticky/sticky.png)
