---
title: Emmets and keyboard shortcuts.
sidebar: vscode-sidebar
label: article
disableTableOfContents: false
tableOfContentsDepth: 2
typora-copy-images-to: ./
---

Emmet is a plugin for many popular text editors which greatly improves HTML & CSS workflow. Good news is that it comes preinstalled in vscode.

As per documentation, Emmet abbreviation and snippet expansions are enabled by default in `html`, `haml`, `pug`, `slim`, `jsx`, `xml`, `xsl`, `css`, `scss`, `sass`, `less` and `stylus` files, as well as any language that inherits from any of the above like `handlebars` and `php`.


## Useful Emmet shortcuts

These shortcuts are very handy. Just type the shortcut and hit tab to complete.
e.g. .container will generate `<div class=container> </div>`

### ID and CLASS attributes

```
#header
    <div id="header"></div>
.title
    <div class="title"></div>
form#search.wide
    <form id="search" class="wide"></form>
p.class1.class2.class3
    <p class="class1 class2 class3"></p>
```

### Multiplication: `*`

```
ul>li*5
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
```

### Naming and numbering: `$`

```
ul>li.sample$*5
    <ul>
        <li class="sample1"></li>
        <li class="sample2"></li>
        <li class="sample3"></li>
        <li class="sample4"></li>
        <li class="sample5"></li>
    </ul>
h$[title=topic$]{Headline $}*3
    <h1 title="topic1">Headline 1</h1>
    <h2 title="topic2">Headline 2</h2>
    <h3 title="topic3">Headline 3</h3>
ul>li.item$$$*5
    <ul>
        <li class="item001"></li>
        <li class="item002"></li>
        <li class="item003"></li>
        <li class="item004"></li>
        <li class="item005"></li>
    </ul>
ul>li.item$@-*5
    <ul>
        <li class="item5"></li>
        <li class="item4"></li>
        <li class="item3"></li>
        <li class="item2"></li>
        <li class="item1"></li>
    </ul>
ul>li.item$@3*5
    <ul>
        <li class="item3"></li>
        <li class="item4"></li>
        <li class="item5"></li>
        <li class="item6"></li>
        <li class="item7"></li>
    </ul>
```

You should keep this cheatsheet handy as this has many more emmets shortcuts https://docs.emmet.io/cheat-sheet/

### Troubleshooting Emacs


## Useful keyboard shortcut

You will see the here the keyboard shortcut which is used everyday on vscode.

`Alt + tab` Switching windows. e.g. browser to vscode and vice versa.  
`Ctrl + tab` Switching tabs inside vscode. 

> 💡 Using external keyboard is beneficial when using laptop. I extensively use cursors of keyboard and `del` `end` `home` page up and down keys.

`Ctrl + Shift + P or F1` Open command palette to access all commands    
`Ctrl + P` Quick Open or Go to a file

`Ctrl + G`  Go to a line number  
`Ctrl + L`  Select current Line  
`Ctrl + D`  Find next match and add to selection  
`Ctrl + /`  Toggle Line comment

`Alt + Click`  Add multiple cursor
`Alt + Up Arrow`  Move line up  
`Alt + Down Arrow`  Move line down 

`Ctrl + F`  Find 
`Ctrl + Shift + F`  Search in Folder/Project
`Ctrl + H`  Replace

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf



