---
layout: post
title: Blogging with Jekyll and Github Pages
tags: [Jekyll, Github]
---

[J]: http://jekyllrb.com/
[G]: https://pages.github.com/
[L]: http://lanyon.getpoole.com/
[M]: https://twitter.com/mdo

I am planing to migrate my blog to [Github Pages][G].

After seeing [@mdo][M]'s nicely designed [Jekyll][J] theme [Lanyon][L], I decided to give it a try.

The theme [Lanyon][L] is based on [@mdo][M]'s [Poole](http://getpoole.com/).
It's well documented and easy to setup.
However, there is one important function that I miss: tags.

Since the author [@mdo][M] didn't seem to be [interested in tags](https://github.com/poole/lanyon/pull/85#issuecomment-94250149), I did some search and realized that it's [not obvious](http://www.minddust.com/post/tags-and-categories-on-github-pages/) how to get tags working without using [Jekyll][J]'s plugin (because [Github Pages][G] have [limited available plugins](https://pages.github.com/versions/)).

After some trial and error, I managed to get a very primitive [tags page](/tags/) to work.
I should document what I did in case I forgot how I made it.
