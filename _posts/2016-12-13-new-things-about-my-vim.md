---
layout: post
title: Things I added to my Vim
---

These few days, I've been installing/removing plugins from my vimrc and so I thought I might share some good stuffs that I found over the past few days.

# fzf

I have always wondered what `fzf` can offer me despite watching youtube videos about it, reading articles about it and so on. But after reading about the things `fzf` can do in a [post](https://medium.com/@crashybang/supercharge-vim-with-fzf-and-ripgrep-d4661fc853d2#.ew80ipb9l) by [Otis Wright](https://medium.com/@crashybang). 

I was completely blown away after reading it and you should read it too. Whether or not you know about `fzf`, it can provide some cool new ideas as to how you go about improving your development environment. Head over to [fzf repo](https://github.com/junegunn/fzf) and learn more about how you can customize `fzf`.

# ale (or) Asynchronous Lint Engine

Many plugins are now taking advantage of `Vim 8` new feature, async, and among them, I find [ale or Asynchronous Lint Engine](https://github.com/w0rp/ale) to be a really nice plugin. 

Basically, it does the same thing as [Syntastic](https://github.com/vim-syntastic/syntastic) but asynchronously. It uses the `linters` or `checkers` as called by `Syntastic` to check against your codes and provides you with the errors and warnings in real time. Async feature is coming to `Syntastic` as well but in the mean time, I'll be using `ale`.


# Conclusion

I hope my sharing gives you some new cool things or ideas about `Vim`. Thanks for reading!
