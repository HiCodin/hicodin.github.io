---
layout: post
title: Things I added to my Vim
---

These few days, I've been installing/removing plugins from my vimrc and so I thought I might share some good stuffs that I found over the past few days.

# fzf

I have always wondered what **fzf** can offer me despite watching youtube videos about it, reading articles about it and so on. But after reading the things fzf can do in a [post](https://medium.com/@crashybang/supercharge-vim-with-fzf-and-ripgrep-d4661fc853d2#.ew80ipb9l){:target="blank"} by [Otis Wright](https://medium.com/@crashybang){:target="blank"}, I was completely blown away.

Whether or not you know about fzf, it can provide some cool new ideas as to how you go about improving your development environment. Head over to [fzf](https://github.com/junegunn/fzf){:target="blank"} repo and learn more about how you can customize fzf.

# ale (or) Asynchronous Lint Engine

There are [A](https://github.com/ramele/agrep){:target="blank"} [few](https://github.com/mhinz/vim-grepper){:target="blank"} [plugins](https://github.com/skywind3000/asyncrun.vim){:target="blank"} that are now using `Vim 8` new feature, **Async**, and among them, I find [ale](https://github.com/w0rp/ale){:target="blank"} to be a really nice plugin.

Basically, it does the same thing as [Syntastic](https://github.com/vim-syntastic/syntastic){:target="blank"} but *asynchronously*. It uses **linters** or **checkers**, as called by Syntastic, to check against your codes and provides you with the errors and warnings in **real time**. Go to [ale](https://github.com/w0rp/ale){:target="blank"} and see what it can offer you. 

You might be wondering why change to **ale** when _Syntastic_ is already a good plugin. I for one like to test new plugins to see whether they can improve my workflow or not and ale has been great. When I was using Syntastic, I'll have to wait around **1-3 secs** for the errors and warnings to show up but with ale, I can just continue to code while it will run the linters in the background and gives feedbacks. 

I am not saying that I will completely ditch Syntastic, I'll just be using ale while waiting for Syntastic to have **Async** feature. Will it be a long time? I don't know. The current maintainer, lcd047, has stated [here](https://github.com/vim-syntastic/syntastic/issues/699#issuecomment-254729032){:target="blank"} that it will be coming to Syntastic in the future so one can only wait.

# Conclusion

I hope my sharing gives you some new cool things or ideas about Vim. Thanks for reading!
