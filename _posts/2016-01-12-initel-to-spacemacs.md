---
layout: post
title: From init.el to .spacemacs
tags: [Emacs, Spacemacs, Editor]
---

[V]: http://www.vim.org/
[E]: https://www.gnu.org/software/emacs/
[G]: https://www.gnu.org/software/gdb/
[S]: https://github.com/syl20bnr/spacemacs
[P]: https://github.com/purcell/emacs.d

I was a [Vim][V] user for two days before converting to [Emacs][E].
(No troll intended; I have nothing against Vim; it's just I couldn't get GDB to work in Vim after spending two unproductive days.)

Like many Emacs users, my `init.el` is highly customized:
at first it was just a collection of snippets from the internet.
Later it grew so large that I decided to use `org-babel` to organize my settings.

I was quite happy with my `init.org`: thanks to org-mode, my elips snippets are structured nicely with well-formatted documentation.
However, it would take a minute to start Emacs with my configuration.
This is annoying.
So I took [redguardtoo's advice](https://github.com/redguardtoo/mastering-emacs-in-one-year-guide) and forked [purcell's configuration][P] as my base configuration.

purcell's configuration is loaded with lots of high quality configurations.
Not only that, he constantly updates and maintains his settings so I don't have to.
It's great to have a very knowledgeable expert optimizing my configuration.
I can also add customization by putting my stuffs in `init-local.el` and `init-preload-local.el`.

Although I am pretty satisfied with purcell's settings, I am still actively seeking good configurations.
Then I met [Spacemacs][S]. 
It's a crowd-configured Emacs configuration with insanely good settings that you can be productive from day one.
If you already know either Emacs or Vim, you can pick up [Spacemacs][S] quite easily.

[Spacemacs][S] is actively developed by hundreds of users around the world.
Thanks to [Sylvain Benner](https://github.com/syl20bnr), who made this possible by creating a consistent and well-designed framework so that [Spacemacs][S] can grow organically in the community.

If you are not convinced yet, have a look at John Stevenson's nicely written [blog post](http://jr0cket.co.uk/2015/08/spacemacs-first-impressions-from-an-emacs-driven-developer.html) about [Spacemacs][S].
I'll see you on the ship of [Spacemacs][S]!
