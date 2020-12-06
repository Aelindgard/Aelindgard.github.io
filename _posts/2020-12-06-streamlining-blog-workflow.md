---
layout: post
title: “Streamlining my workflow”
excerpt: “Streamlining my blogging and development workflow so that I am motivated to actually do them.”
comments: false
share: true
categories: [blog]
tags: [workflow, life]
---
One of my aims for this year's "Devember" is to blog more regularly and work on my projects more.

One of the reason I have not been blogging or working on my projects, or one that I keep telling myself, is that I don't always have my laptop with me cause it's bulky. 

But a more realistic reason is because I have poor habits, like not pushing to GitHub after every change and having merge conflicts everywhere I have a local copy. And upon seeing all of the conflicts, honestly I can't be bother to deal with it leading to another project being abandoned.

So to motivate myself to actually blog more and work on my projects, I decided to streamline my workflow.

So with this in mind and as part of "Devember" 2020 I have decided to do the following.
1. Setup a working environment in a cloud instance
2. Setup connection to the environment from all my devices
3. Finally learn how to use VIM properly

For the working environment, I decided on the smallest Linode instance which costs about SGD$10 per month. The choice of operating system is Ubuntu without desktop environment.

In this instance I then proceeded to set up my working environment.
1. Setup zsh, oh-my-zsh, powelevel10k
2. Byobu
3. SpaceVim

The first set of items don't really affect my workflow and are purely eye-candy. The second and third items on the other hand actually do affect my workflow.

Byobu was selected as my session manager for 2 reasons, 1 it looks nice but more importantly it has nicer keybindings. Yes I know I can redo the keybindings in plain Tmux but I'm lazy.

To help with my workflow, 2 sessions are created using Byobu, "Blogging" and "Development". The "Blogging" session is set up with 2 vertical panes, SpaceVim on the left and on the right is where the Markdown pages are previewed using Mdless. For the "Development" session, only a single pane is used and that contains SpaceVim with current project being worked on opened.

SpaceVim was selected as the editor of choice as one of my goals for this year was to learn and practice using Vim. SpaceVim is a community distribution of Vim with some useful plugins bundled. Link to [_SpaceVim_](https://spacevim.org)

The last part of this new workflow is adding SSH access to the environment from all my devices. Hopefully by being accessible at any time regardless of the device that's with me will encourage me to actually login and interact with it. 

The devices that I have setup for access are:
1. Pixel 4a mobile phone via Termux
2. iPad via Blink.sh
3. Laptop via WSL if in Windows and terminal if in Ubuntu.

Hopefully with this new workflow, the rate of my blogging and work on my projects will increase. Of course no amount of streamlined workflow will work unless I get over my procrastinating self, only time will tell if there's any improvement.

See you on the other side.

- Aelindgard
