+++
title = "Why You Should Use Vim"
date = "2026-01-27T08:25:48Z"
author = "Leo"
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["vim"]
keywords = ["vim", "tutorial"]
description = "Why You Should Use Vim?"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++

# Vim: The Most Powerful Text Editor

## What is Vim?
Vim is a highly configurable and efficient text editor that runs mainly in the terminal. It is an improved version of the classic **vi** editor and is widely used by programmers, system administrators, and power users. Vim focuses on keyboard-based editing, allowing you to navigate and modify text quickly without using a mouse.

## Pros and Cons

### Pros
- **Very fast editing** once you get used to it
- **Lightweight** and starts instantly
- **Available almost everywhere** (Linux, macOS, servers, SSH)
- **Highly customizable** with configs and plugins
- **Powerful text manipulation** (macros, regex, bulk edits)
- **Number + command** feature saves you a lot of time

### Cons
- **Steep learning curve** for beginners
- **Modal editing** can feel confusing at first
- **Not very intuitive** without a tutorial
- **Hard to quit** (yes, the meme is real)

## Why you should use Vim?
Vim is a powerful editor. Once you get used to it, you will edit files quickly and efficiently. It reduces mouse usage, keeps your hands on the keyboard, and helps you think in actions rather than individual keystrokes. Vim also shines when working on remote machines or low-resource systems where full IDEs are unavailable.

## Is it hard to learn how to use Vim?
It's not really as hard as you think. At first, Vim may feel strange because of its modes and shortcuts, but after some practice, everything starts to make sense. Instead of memorizing everything at once, you learn Vim gradually, and your speed improves naturally over time.

If you have time and your English is not bad, try running `vimtutor` in the shell. It is an interactive tutorial built into Vim and is one of the best ways to learn the basics.

Here are some basics from it:

### Navigation
Use **h, j, k, l** to move left, down, up, and right.
Note: Arrow keys also work in Vim, but these keys are faster once you get used to them.

- **w** → jump to the next word  
- **b** → jump to the previous word  
- **gg** → go to the top of the file  
- **G** → go to the bottom of the file  

### Commands
- **i** → enter insert mode (start typing)
- **Esc** → return to normal mode
- `:w` → save the file
- `:q` → quit Vim
- `:wq` → save and quit Vim
- `:q!` → quit without saving

If you don’t know what you typed or feel stuck, just press **Esc** to return to normal mode.  
If you want to leave immediately without saving, press **Esc** and type `:q!`.

## Is it worth using Vim, or even just the hjkl movement?
Yes, absolutely. Even if Vim doesn’t become your main editor, learning **hjkl** movement is still useful. Many tools and editors support Vim-style navigation, such as `less`, `tmux`, and even modern editors like VS Code. Vim teaches you to edit text efficiently and think differently about how you work with files — a skill that stays valuable long-term.

---

## Vim Cheat Sheet

### Modes
- **Normal mode** → default mode for commands and navigation
- **Insert mode** → typing text (`i`)
- **Visual mode** → select text (`v`, `V`, `Ctrl+v`)

### Basic Movement
- **h j k l** → left, down, up, right
- **w / b** → next / previous word
- **0 / $** → start / end of line
- **gg / G** → top / bottom of file

### Editing
- **i** → insert before cursor
- **a** → insert after cursor
- **o** → new line below
- **dd** → delete line
- **yy** → copy (yank) line
- **p** → paste

### File Commands
- `:w` → save
- `:q` → quit
- `:wq` → save and quit
- `:q!` → quit without saving

### Useful Tips
- Use **number + command** to repeat the command times, eg, `3j` moves down three lines. This will save you a lot of time.
- Press **Esc** anytime to return to normal mode
- Use `u` to undo and `Ctrl+r` to redo
- Type `/text` to search for text

---

*Tip: You don’t need to memorize everything. Learn a few commands, use them daily, and Vim will slowly become natural.*
