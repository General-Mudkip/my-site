---
layout: "../../../layouts/MarkdownPostLayout.astro"
title: "learning neovim"
description: "a recount of my attempts to learn neovim"
pubDate: "2023-07-11"
---

## The Beginning
I started off coding using good ol' VSCode, the "IDE" that seemingly every beginner downloads when they start off. Downloaded my extensions, selected a pretty theme, and installed FiraCode Mono. All was good in life, and I could code in peace. In fact, this site was made using VSCode.


## The ThePrimeagen Incident
As a programmer you're bound to here about this fabled "Vim" editor every now and then. Memes of people struggling to quit it, posts about people who treat it like the second coming of Christ, etc. But to be honest, all of those things dissuaded me from trying it. Then, I came across this man known as "ThePrimeagen". <br><br>
Seeing his blazing fast skills and the familiarity he had with his code editor was very impressive, as someone who just downloaded VSCode and ran with it. He had turned NeoVim into something that was *his*. I was just using some opiniated editor that another person had designed for me.


## Research
So then I began to research. Looked up "NeoVim", hit the download button, skimmed the GitHub page (as all good programmers should do) and downloaded the release file. Exported it, opened up the NeoVim.exe file, and thought "Surely there's a better way to do this?" I of course ignored that though, and began the tutorial. It was a horrific experience to be perfectly honest, my navigation skills using the H, J, K, and L keys were not amazing. But I pushed through, and I could see those tiny *glimpses* of efficiency. Those moments where things just clicked and I flew along the keyboard. So, I pushed forward.


It was then that I stumbled across r/NeoVim, and by extension, LazyVim.


## LazyVim
Well, it's kind of in the name isn't it? I was feeling *particularly* lazy and decided that instead of spending 12 hours configuring my init.lua file and searching for plugins, I'd just use LazyVim. I had to install C compilers, Choco, Scoop, treesitter, LazyGit, and all sorts of things that at some point I gave up trying to put up a front of knowing what I was doing and copy+pasting random powershell commands in hope of it working. <br><br>
After having the install fail for the 6th time, I did the smart thing for once and looked up a tutorial. Upon opening it, the first step was to install Ubuntu. Huh?


## Ubuntu and WSL
So apparently there's a whole "Windows Subsystem for Linux" thing that I had never realised existed? In any case, I spent the next 2 hours trying to get the damn terminal to work, one of the steps included booting into BIOS, realising I had XMP turned off, and wasting a solid 30 minutes trying to find the "Enable Virtualisation" option only to realise it was already on. Well, I did get it working eventually.

## Getting Started With LazyVim
From there, it was pretty much smoothsailing. I downloaded some packages, installed NeoVim, realised it was version 6.2, went through 4 methods of installing it until I found some "FlatPak" thing which allowed me to download the latest stable version. At that point I was desperate so I just went with it. I entered the "nvim" command, and lo and behold, it actually loaded without throwing some random error! 

## Polishing My Skills 
After spending the better part of 6 hours installing Ubuntu, Vim, Choco, and 1.6GB of god knows what, I was able to start up and use NeoVim. I reckon that I've currently got about 23 tabs of just NeoVim-related stuff. I still don't know the difference between a tab, window, and buffer, but at least I know how to kind of switch between the two. I'm glossing over a fair amount of the trials and tribulationsI encountered along the way, but now that I'm here it actually feels *good* to code. I don't think I've ever had such a satisfying experience programming. 


## Now 
Now all that's left to do is just get used to it I suppose. My remaps may not work, the Astro LSP isn't really doing anything, Tailwind seems to hate me, and my markdown files aren't formatting properly, but at my code looks good. (Sans the lack of syntax highlighting.) I also need to figure out how to actually commit and push this thing. Welp.
