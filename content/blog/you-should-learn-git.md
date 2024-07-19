+++
title = "You should learn Git"
date = 2024-07-18
+++

You should learn Git, especially if you're a programmer. I hope this post will inspire you to try it out!

Git is a VCS (Version Control Software) that maintains a history of changes made to your projects. These changes can be reverted, altered, and reviewed at any time. This is Git at its simplest — a lightweight and reliable record of your development progress. Oh yeah, and Git is totally free.

Combined with services like GitHub, you can even create cloud-based copies of your work that you can freely update, download, and share. GitHub safely hosts your projects and their Git data in case you drop your hard drive in the toilet. Oh yeah, and GitHub is totally free.

Whenever you make changes to a project, Git allows you to create a new _commit_ to record said changes. Git automatically maintains a timeline of all commits, which you can view at any time.

<img src="/blog/arcstat-git-log.png" alt="image of a Git log" />

> Above: a segment of the commit history for my Rust project, [arcstat](https://github.com/massivebird/arcstat).

I'm sure you know the dread of accidentally breaking your entire project. With Git, you don't have to worry anymore: commits allow you to restore project progress at will. This simple and consistent checkpoint system means no more annoying copy-paste backups of your entire codebase. Git makes it so easy.

Taking risks is the essence of self-improvement. Git will help you overcome the fear of failure and losing your valuable work. Git is a witness to your progress so that you can work looking forwards — never backwards.

## Getting started

Git is available for all platforms, and can be used in the command line or through a graphical interface. You can download Git [here](https://git-scm.com/).

I _must_ recommend learning Git in the command line. That's probably scary to you, but I promise you'll do just fine. If you're unfamiliar with the command line, I recommend following [Ubuntu's Bash shell tutorial](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview). Their tutorial is amazing, concise, and will catch you up to speed with the basics.

> Windows users can either install Microsoft's [WSL](https://ubuntu.com/desktop/wsl) (recommended) and/or opt for the Git Bash when installing Git.

Besides, Git's GUI is so ugly and clunky that I wouldn't wish it on anyone.

## Resources

__Start with [Pro Git](https://git-scm.com/book/en/v2)__, the free e-book hosted by the official Git website.

+ [Ubuntu's Bash shell tutorial](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview), for those unfamiliar with the command line.
+ [Git documentation](https://git-scm.com/docs) for cheat sheets, quick references, and command manuals.

### Downloads

+ [Git](https://git-scm.com/), the all-powerful VCS.
+ [WSL](https://ubuntu.com/desktop/wsl), or Microsoft's Windows Subsystem for Linux. This is an integrated Ubuntu Linux command line environment inside Windows, and is great for learning the Linux command line.
