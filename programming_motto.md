---
created: '7-17-2017'
tags: ['technology', 'thoughts']
license: 'public-domain'
---
# How Should We Understand The Mottos In Programming
There are no shortage of principle and motto in the world of computing. KISS, DRY, Worse is Better, etc. One problem that occurs though, is how should we understand each of these principles. By shortening a principle into bite-size, consumable piece of information, we lose some nuances, and misunderstanding occurs within the tech world.

## The UNIX Way: Write Programs That Do One Thing And Do It Well
Easily the principle that causes the most wars between people in the tech world. One example, I have heard proponents of vi/vim claim that vi should be the preferred editor for code, because it adheres to the UNIX way: it focuses solely on text/code editing and does it extremely well. It does not try to do refactoring, debugging, building, things that should be included in other specialized tools like debugger, compiler, and build system. Any IDE which tries to do all of those tasks are considered bloated.

But then you could easily argue the other way: IDEs in the vein of Visual Studio or IntelliJ do one thing extremely well, that is software developing. You could find anything you need to develop a software from an IDE: text editor, intellisense, documentation, refactoring tool, debugger, compiler & build system. It eliminates the need to wield ten different tools to build a software, reduces friction and makes programmers' life easier.

So there seems to be a black (good old Notepad), a white (Visual Studio), and a huge area of gray: from advanced editor like Vim or Sublime, to pseudo-IDE like VSCode, to monsters like emacs, which cannot really be classified. And as long as the tool do what you want and you feel comfortable with it, it's fine. I personally use a combination of VSCode, a cross-platform code editor from Microsoft, and emacs (in the form of spacemacs). They do what I need without much configuring and stay out of my way.

(Of course, there are always softwares that simply fail: the numerous programs that fail to do anything of any quality that you could find with abundance in the market, and the huge programs that try to much on its own. Yes I'm looking at you iTunes, you music player/media manager/music store/movie store/podcast and radio player/app store for whole operating system)

## KISS Principle: Keep it Simple Stupid