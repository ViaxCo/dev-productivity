---
path: "/tmux-3"
title: "Tmux - Using"
order: "33A"
section: "CLI - Beginning"
description: "More manageable terminals"
icon: "dumpster-fire"
---
### Warning
Some of my items will be slightly different than yours because I have a tmux rc
that has been refined.  You can have one too!  I'll even talk about it shortly,
but for the sake on less confusion, lets start with just tmux then we will get
to some of the rc

#### Why show you the commands
There may come a day when you want to write a little optimized script!
Everything has both the command and a key.  The command line interface for tmux
is very complete and you can do a lot of things.

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### Lets open a terminal and start tmux

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

```
tmux list-sessions

# If you got excited
tmux kill-server
```

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

```
tmux
```

### Do the drawing thing

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### The Prefix Key

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### Creating sessions

```
tmux new-session #errors
```

```
tmux new-session -d
```

```
tmux list-sessions
```

#### Navigation tip
I don't use this personal, but this is a thing that is good to know.

* to the next session `<prefix>-a (`
* to the prev session `<prefix>-a (`

#### Lets close our terminal
To get back to our session type in
```
tmux a #ttach
```

#### Navigation tip
Instead of closing our terminal, lets press `<prefix>-d`

#### Navigation tip
You can see all of the sessions and their windows by pressing `<prefix>-w`

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### Creating Windows
A session should contain *like* items.

```
tmux new-window
```

this is equivalent to `<prefix>-c`

#### Navigation tip
* `<prefix>-n` for next window
* `<prefix>-p` for prev window
* `<prefix>-#` for the # window

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

![Who does #2 work for?](./images/who-does-2-work-for.jpg)

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### You can name sessions and windows
```
tmux new-session -d -s "foofoo"
```
```
tmux new-window -n "fooooo"
```

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### There are panes
You can definitely look into panes to be able to split your view.  I just
haven't really got into that.  I find it a pane in the ass..
