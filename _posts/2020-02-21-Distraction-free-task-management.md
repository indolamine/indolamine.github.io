---
layout: post
title: "Distraction-free-task-management"
description: "The way to an extremely distraction-free task management solution"
date: 2020-02-21
tags: gtd focus distraction todoist task-management purist
comments: true
---

*This is the first in a series of blog posts, documenting the thinking process behind the philosophy and design of an extremely distraction-free task management system I'm building.*

Like any good GTD enthusiast, I've experimented with a plethora of different tools and workflows to facilitate my GTD processess. In the process I've came to realize that the good old "simplicity is key to focus" principle is true, and especially true in the context of managing your "tasks".

David Allen's notion of the threefold nature of work doesn't get as much attention as some other parts of his work. Still, I believe it's fundamental to figuring out what tooling / workflow works for you in these "folds".

## The three folds

- Doing predefined work
- Doing work as it shows up
- Defining future work

Whatever work you do at any point in time, it falls into one of the three categories. All of these require very specific states of mind. 

## Doing predefined work
Doing predefined work is when you want to be in the flow, with laser-sharp focus on what you need to achieve. Anything you do should be about the task at hand, with the occassional quick capture of "stuff"/ideas that come up in the process and that you don't want to forget. Even then, once you get that spark out of your mind by taking a note of it, you'll want to focus back at the task at hand, not letting anything else penetrate your mind in the process.

Imagine the scenario when you're working on a document/presentation/codebase/whatever, and need to take a quick note. To keep distraction lowest, in a physical setup you reach out to grab a pen, grab an _empty_ piece of paper, write a good enough reminder for yourself and toss it in your inbox / in-tray, hopefully getting it completely out of sight and out of mind. This requires some (but not a lot of) discipline. You need the pen at hand. You need empty papers at hand. You need an inbox. That's it. 

Imagine an alternative workflow, still in a physical space setup.

- You have the thought
- You start looking at a pencil/pen holder and choose a pen (the first hit to your focus)
- You try to find a piece of paper to use (the second hit)
- The paper you find might have some writing on it, you just quickly skim it to see if it's something you should scribble on (boom, you're in a heavy context switch, good luck finding your way back to focus)
- You try to put that piece of paper somewhere where hopefully you'll pay attention to it later, but still have that weird feeling (ok, is it in the right place? Will I remember to check it?) - you're doomed

Let's jump into the software world. You need to create a quick reminder. 

- You pull up your note-taking software, immediately staring at a lot of your previous notes - boom, you're gone. 
- You pull up a text editor, adding a line to your plain-text organization thingy - a lot of lines staring at you. Some syntax highlighting catches your eye - boom.
- If you're lucky, you have a "quick add" feature in your whatever app. It brings up an entry field- it might display stuff that lets you "conviniently" set tags/labels/priorities/deadlines/project associations/whatever. Boom.

You're pushed out of "taking a quick note while focusing on predefined work" mode, and pulled right into "define future work" space. That's not what you're there for. You want to take a note, not think about it. You want it to be safe. You want to look at it later. But not now. Anything else is a distraction.

There are some beautiful workflow solutions, e.g. for Alfred, that are really minimal. You get a text entry field, you type your note, you press enter. You hope it ends up in your system. Good. Except if it's some wanky script that takes care of saving that you don't trust 100%. That will create some anxiety about where it ends up if anywhere. Also, Alfred might show you a quick and small "Alfred update available" message, that again might put your thought on something you don't want to deal with right now.

Same deal with all the "natural language processing" features of some of these quick-add solutions. You don't want to end up taking a note like "Pay mark 2199 bucks for the Mac" and end up having it scheduled to 1st January, 2199 , maybe even disappearing from your inbox (true story).

I'm not saying it's a bad thing to have this kind of processing. It's extremely useful in a lot of situations (especially when your intention is to put something in its right place in your system). But using them during this "dump it and refocus" scenario won't help, instead it will put the burden of making sure this feature won't mess it up on you - extra focus required. I found myself sabotaging these features intentionally, like by typing date-like things incorrectly (like "Pay Mark z199 bucks") just to protect against all the good intentions and remove this micro-anxiety from this quick note taking process.

So, doing predefined work should be about doing predefined work while having a trivial ability to dump stuff. Dump. Not think about.

Back to doing predefined work. My experience is that it's simply best to have one single thing in front of you that you're working on, and nothing else. Also, if you need any support material, they should be close at hand and you should be able to grab them without any distractions. 

Now that is though. Real though. 

We're living in an attention economy, and it shows. Try finding some attachment on Slack without getting distracted. Try digging up something in Dropbox without getting recommended your "recently opened" stuff you just don't care about at all. Try opening something in Office 365 without being shown what your colleagues have been up to. Even though a lot of editors on and offline have great focus mode features by now, the way to get there is full of distractions. 

Be aware, prepare work in a way that makes it frictionless to get to what you need, and don't get anything else. You typically don't want to see what cell your boss is editing in a shared Google Spreadheet. Distractions everywhere.

Unfortunately, even if you've prepared well, and have all your relevant docs linked or attached to the task in your system, getting them out might be tricky. If you need to pull up any view of your task management system, it will most probably list other projects/tasks/filter/saved searches/whatever. They might even notify you about how many tasks you've completed this week (Yay! You might as well have a champagne - your flow is probably gone anyway).

## Doing work as it shows up

Doing work as it shows up is something we all need to do time to time. Not much to add, maybe one thing.

Whether you're a "browse for stuff" person, keeping a nice set of nested folders for your stuff online or physically - or a "search for stuff" person, using queries of some kind to get to the stuff you need, you better make sure your tools are in a good shape and won't distract you. Don't rely on stuff like Delve to find stuff on an O365 workspace - be aware that it's an attention grabbing toy, not a browsing/searching tool. Same applies to a lot of "pull up your stuff" solutions. I find that staying in a terminal in the command line and relying on grep / ripgrep / fzf and similars for finding files is maybe the least distracting. On the other hand, good luck being undistracted while in your browser. Just take a look at all those shiny icons on your tab bar. Maybe some have little red badges as well. Noooo... don't click - boom, you did it again.
If you need to do work as it shows up, your goal still has to be to jump on it and get it done or move it forward in a meaningful way. 

*Now, defining future work is a completely different beast. But let's keep that for a next blog post.*
