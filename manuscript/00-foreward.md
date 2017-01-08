 
{frontmatter}

# Foreward 

Most of my friends swear by tmux. I remember going out at night
for drinks with friends and we would take a seat at a favorite restaurant and 
take out our phones. It was back in the days when phones still had
physical "QWERTY" keyboards.  We had just planned 2 hours earlier, on IRC, to use
Oleg's car and drive into the city.

Despite our home computers sleeping or being off, our usernames in the channel
persisted in the chatroom list. Our screens were lit by a kaleidoscope of colors
on a black background. We ssh'd with ConnectBot into our cloud servers and
ireattached [`screen(1)`](https://en.wikipedia.org/wiki/GNU_Screen). Just as it
hit 2 a.m. our Turkish coffee arrived and the `|away` trailing our online nicknames
fell off one by one.

Oddly, even though we knew each other by our real names, we sometimes opted to
rcall each other by our nicks. It's something about how the personal
relationships, formed completely through text, persists in real life.

sIt seemed as if it were orchestrated, but each of us fell into the same ebb and
flow of operating our lives. No one told us to do it, but inch by inch we
incrementally optimized our lifestyles personally and professionally to arrive
at destinations that felt eerily alike.  Like many things in life, when we act on 
autopilot, we sometimes arrive at similar destinations completely unplanned.

So when I go off and write a learning book on a computer application, I hope
oto write it for human beings. Not to sell you on tmux, not to make you like
it, or hate it, but to tell you what it is, how some people use it and leave 
the rest up to you.

## About this book

This book is written for tmux 2.3 and is currently under development. It's available to read for
[free on the web](https://leanpub.com/the-tao-of-tmux/read).

You don't need a book to use or understand tmux; but if you choose to use a book, let
this be the one.

I am not slipshod in the work I perform.  If I'm going to take the time to write a book, 
I'm giving it 100%.

tmux to me is a tool I find incredibly helpful. It's been part of my daily life for years.
've helped thousands of people learn tmux through my free resource under the same name
[The Tao of tmux](https://tmuxp.readthedocs.io/en/latest/about_tmux.html). I've
written a [popular tmux starter configuration](https://github.com/tony/tmux-config),
a [pythonic tmux library](https://github.com/tony/libtmux) and a
[tmux session manager](https://github.com/tony/tmuxp) as well. You might think I'm trying
to build this big thing around tmux, but the reality of it is, tmux is just that useful.

I am writing this from vim in a tmux pane, inside a window, in a session, on
the server, through a client.  It's not that I don't care about accuracy, but
if you want a technical manual, the manpage for tmux is quite sufficient for 
the purpose.

A word to absolute beginners, do not feel like you need to grasp the concepts
of command line and terminal multiplexing in a single sitting. You have the
choice of picking out the concepts of tmux you want to learn according to your
needs or curiosities. If you do not have it installed, please view the
[Installation section](#appendix-installation) in the Appendix of the book.

## How this book is structured

First, anything involving installation and hard technical details are in the
appendix at the back of this book. 

I have added screenshots for those whose learning preference leans to a visual 
approach or users of Windows 10.

[*Thinking Tmux*](#thinking-tmux), goes over a breakdown of what
tmux does and how it relates to the GUI desktops we already use on our
computers.  You will get to wrap your brain around what tmux is and how it can
make your life easier.

[*Terminal Fundamentals*](#terminal-fundamentals), reviews the common
systems you'll be dealing with in the realm of the text-based console. It's
great for those new to tmux, but also to put some technical backing for
developers who learned the ropes through examples and osmosis. You'll be more
confident and secure in the fundamental underpinnings of using multiplexers
and shells.

[*Practical Usage*](#practical-usage), covers common bread and
butter cases for you to start using tmux daily starting now.

[*Server*](#server) gives life to the unseen workhorse that powers tmux behind
the scenes. You'll think of tmux in a different way and may be impressed to see
a client-server architecture that could be implemented so seamlessly to end users.

[*Session*](#sessions) drops you into the world of tmux.  You'll learn what a session 
is and how it helps you organize your workspace in the terminal. You'll learn how you 
can manipulate and rename your session, providing a fine stepping stone to the next destination.

[*Window*](#windows) is what you see when tmux is open right in front
of you. You'll learn to rename and move windows, to create, delete, move between
and copy and paste been panes.

[*Panes*](#panes) A pane is a terminal in a terminal. This is where we'll leave you to
get to work and do your own magic!

[*Configuration*](#config) discusses customization of tmux, via keybindings,
status line and behavior. You'll even learn how to show your CPU usage and
memory via the status line.

[*Technical Stuff*](#technical-stuff) is intensive, "nice to know"
stuff about the internals of tmux. You may learn enough to be able to 
impress friends who currently use tmux daily. If you like programming on
POSIX-like systems, this section is for you.

[*Recipes*](#recipes) wraps it up with a whirlwind of a customized tmux
configuration, a yaml file to launch tmux sessions using
[tmuxp](https://github.com/tony/tmuxp). In addition, we'll cover a Python API
for tmux called [libtmux](https://github.com/tony/libtmux). You'll get to see
some tricked out tmux examples.

## Donations

I do offer my learning material for free on the internet, as well as maintain
several open source projects. If you'd like to support my day-to-day open
source participation please check out <http://www.git-pull.com/support.html>
for ways to contribute.

## Available Formats

This book is available for sale on [Leanpub](https://leanpub.com/the-tao-of-tmux), [Amazon Kindle](https://www.amazon.com/gp/product/B01MG342KU/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01MG342KU&linkCode=as2&tag=gitpull-20&linkId=e6d3f08ad92bfea1cf62d735b6a90bdf) and [Apple iBooks](https://geo.itunes.apple.com/us/book/the-tao-of-tmux/id1168912720?mt=11&at=1001lrwP).

It's also available for free to [free on the web](https://leanpub.com/the-tao-of-tmux/read).

## Errata

If you find errors in this book please submit them to me at tao.of.tmux <AT>
nospam git-pull.com. I will update digital versions of the book with the 
changes where applicable.

## Book Updates and tmux changes

tmux does intermittently have updates. I've shepherded many of them over
the past 5 years or so on my personal configurations as well as software
libraries.

Refer to tmux's [`CHANGES`](https://github.com/tmux/tmux/blob/master/CHANGES)
file for updates on what changes have been  made and when.

As of November 2016, only minor changes have been made on Leanpub, Amazon and iTunes, 
so don't worry about having to pay unless tmux makes radical changes.
