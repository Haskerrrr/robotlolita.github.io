---
layout: post
title:  Meeting Enlightenment
snip:   Why you should be using e17 as your Window Manager
---

I've used quite a few Window Managers in the past: IceWM, KDE, Gnome-Shell,
Metacity, Fluxbox, etc. but they either looked plain horrible, were bloated
like hell — yeah, KDE, take that — or were just plain and irritatingly slow.

I've always liked lightweight and tiling window managers — which is one of the
reasons I love Emacs — but they all felt too plain to my likings. As an art
lover, I need some spark and beauty on my desktop, rather than strictly
functional things.

So, here am I ranting about about the features of e17 that got me hooked, and
*why* **you** *should give it a try*.


## Table of Contents
 *  TOC
{:toc}


## 1. Why you should try it

You probably heard elsewhere that enlightenment is lightweight and
sparkles. But I don't think that is enough reason to switch to a Window
Manager — all the more when it hasn't seen a stable release yet.

So, here's my little list of reasons:


### 1.1. Lightweight and FAST

I have a kinda old PC with an on-board graphic card, which means that not even
OpenGL gets some love here, thus being lightweight is a must for me. Not only
this, but Enlightenment manages to be a lot faster than any other window
manager I've tried so far — taking the delicious amount of eye-candiness into
account, obviously.

I also have a [MacPup](http://macpup.org) that runs directly from my
thumb-drive. The distro is bundled with IceWM, Enlightenment and another window
manager I can't remember the name for life, still it fits nicely in less than
228MB, and runs entirely on the RAM, leaving all the remaining space on my
thumb-drive for **actual data**.

It doesn't makes much of a difference if you have a bleeding-edge PC, or use
any KDE application out there — I try to stay clear of them, by the way.



### 1.2. Fully configurable

Which is one of the reasons I use Linux in the first place. I like configuring
everything to fit my workflow, and Enlightenment lets me do so quite easily
with the settings GUI.

Most of this configuration is quite straight forward, but some of the UI are
not that good.

![settings](/files/2011/03/settings.jpg)

You can also configure everything from the command line, or editing the
configuration files — though in this case you have to decompile them and
recompile when you're done.

Another good thing about Enlightenment's configuration is the profiles. This
allows you to have as many different configurations as you need, and allows you
to safely test stuff away, while having your previous configuration safely
stored.

For example, I use three different profiles for my MacPup: Netbook, Notebook
and Desktop. Each providing a slight different set of keybindings, mouse
adjustments and screen/modules. So any time I plug it in a different computer,
I just have to select a suitable profile instead of reconfiguring everything.


### 1.3. Modularity

Since Enlightenment is built up on a modular structure, you can choose exactly
which features you use instead of wasting RAM on useless stuff. This also means
that plugins blend in really nice with the entire Window Manager, which is
always a good thing.

Alongside with the configuration profiles, this lets you test modules away
without having to worry about breaking the Window Manager — since you can
always go back to your previous sane profile.


### 1.4. Shelves and Gadgets

Metacity has `desklets` and `panels`, Enlightenment has `shelves` and
`gadgets`. Gadgets are just small applications you can use on your desktop, and
shelves are a way to group a collection of gadgets.

Shelves also have a few interesting features that I like. The most important of
them is the ability of hiding a shelf until I actually **need it** — by either
moving my mouse over the edge of the screen, or clicking on it. I just hate
clutter and think my screen space is better used to hold the windows of the
applications I use, instead of a taskbar or dock.

Another interesting stuff about shelves is that, aside of the screen position,
you can also specify the stacking position. So shelves can be placed above or
below everything. You can also configure whether the shelves' space should be
available for windows or not.

![desktop](/files/2011/02/desktop.jpg)

> Top, top-left and bottom-right are shelves. The other ones are plain gadgets
> placed over the desktop.



### 1.5. Charmingly beautiful

Even if you don't have a powerful enough computer to run the compositing stuff
(Enlightenment ships with Ecomorph, which is a port of Compiz), there are still
plenty of eye-candy for you, including animated backgrounds, animated icons and
transitions.

Better still, everything is theme-able, including the third-party modules. And
you can build your own theme with parts of various other themes.

For Gtk applications you'll need to install a suitable Gtk theme though.

![themes](/files/2011/03/themes.jpg)

Currently, I'm using **Detour** as my base Enlightenment theme, which parts of
Simply White, Imago and a few others. For the Gtk part, the Orta theme blends
in quite nicely and looks hella sweet :3

To **feel** the beauty of Enlightenment you have to try it though. It's not
something that can be portrayed easily with images. You can have a go at some
youtube videos, though.


### 1.6. Everything a few keystrokes away

I **loathe** going through *xyz* menus just to launch an application — I hate
most menus, actually. Enlightenment comes with a nice QuickSilver-like launcher
though, called Everything. If you're not familiar with the Mac world, it's
something like Gnome-Do, but with far more levels of awesomeness — and frankly,
I've always found Gnome-Do frustrating.

Everything follows the modularity structure of Enlightenment, so you can add
any plugin to it to make doing some tasks faster and easier.

![Everything](/files/2011/03/everything.jpg)

You can have a quick calculator, spell checker, web search, file search and any
other thing you want with a plugin. It's **really** handy (even for someone who
almost uses Emacs as his OS).


### 1.7. Shortcuts for anything

Another thing that I dislike are mouses. I just can't get used to them and
feel that they get too much on my way. Well, when using Enlightenment I
don't need it most of the time, because there's keybindings for almost
everything.

The input dialogues allows for shortcuts for usual system commands, as you
would expect, but also to manipulate virtual desktops and windows. And when
I say *manipulate windows* I mean you can resize, position and switch
between these windows using your keyboard in a sane way.

I have almost all possible cute mnemonic combinations with the useless Super
key (Super+key, Ctrl+Super+key, Shift+Super+key, Alt+Super+key, ...) to do
some actual useful stuff, so I guess you can get an idea of the
awesomeness :3


### 1.8. Tiling

I believe this is bundled in e17 in the Illume2, but since the Illume stuff
is for embed and mobile systems, I haven't dig into this. Instead I use the
tiling module that's on the SVN.

The module isn't perfect, but I don't have that many complaints against it.


### 1.9. Handling errors gracefully

Yes, the Enlightenment's window manager (e17) is still in pre-alpha, so it's
not all **that** stable — although I've been using it for months now without
much trouble.

However, you're likely to experience some segfaults if you play around too
much:

![E17 Segfault](/files/2011/03/esegvd.jpg)

It's not something you should worry that much though, only the window manager
is affected, not your data. And it gracefully recovers itself to the previous
state in less than a second, which is a pretty nice thing.


## 2. The drawbacks

Yeah, Enlightenment is great and all, but it has its drawbacks. The worst issue
is really stability. Not that it will crash each minute, but you're likely to
experience a few minor issues: like an auto-hide shelf that won't hide and
stuff like that.

This can all be solved by restarting the Window Manager — and I mean the WM not
your DM, which means that your application state won't be affected. You can
restart e17 from the main menu in `Enlightenment → Restart`.  I personally
prefer binding a shortcut to it (`Super-r`) and using that.

You may also miss some features. I think the modules have a great coverage of
the features **I** need — even though the tiling isn't perfect — but they may
not cover well your use case.


## 3. Getting it up and running

There are quite some ways to try Enlightenment out now. You don't need to
compile it out yourself if you don't want to, or are just to lazy to do so.


### 3.1. The easy way

You can grab any Linux distro that comes with Enlightenment as their default
Window Manager and run from the LiveCD or install it on a spare HDD partition
or a VM. Just get any of the following and try it away:

- [Unite17](http://www.unity-linux.hu/unite17) — Unity-based desktop distro
- [MacPup](http://macpup.org)  — Puppy linux distro (uses Ubuntu Lucid Lynx)
- [moonOS](http://moonos.org) — Ubuntu-based. Neak's main edition uses e17.
- [Bodhi](http://bodhilinux.com/index.html) — Minimalist Ubuntu 10.04-based distro.


### 3.2. The hard way

If you want to try your luck, you can grab the source from the SVN repository
and compile it yourself...  Okay, it's not so hard, it just takes a little bit
of time depending on your internet connection and computer resources.

I'll try to describe a little the steps to get e17 up and running, and while
these concepts should apply to any distro, bear in mind that I'm assuming an
Ubuntu one as basis for package list and specific commands.


#### 3.2.1. Before installing

e17 depends on quite a few libraries and tools. The
[SVN repository](http://svn.enlightenment.org) lists most of it, but depending
on your distro and the amount of C-coding/compiling you've done, it may
vary. At least, make sure you have all of the tools and libraries listed there.

If you happen to be using an Ubuntu distro, you can get away with getting the
following from apt (just copy/paste it on the terminal):

{% highlight sh %}
$ sudo apt-get install subversion gcc autoconf \
  autopoint automake libtool make gettext \
  libpam0g-dev libfreetype6-dev libpng-dev \
  libjpeg-dev zlib1g-dev libdbus-1-dev \
  liblua5.1-0-dev libx11-dev libxcursor-dev \
  libxrender-dev libxrandr-dev libxfixes-dev \
  libxdamage-dev libxcomposite-dev libxss-dev \
  libxp-dev libxext-dev libxinerama-dev \
  libxkbfile-dev libxtst-dev libtiff-dev \
  librsvg2-dev libgif-dev libcurl4-gnutls-dev \
  libgnutls-dev libxml2-dev libudev-dev
{% endhighlight %}


#### 3.2.2. Building it

You can just checkout from the svn repository and run `autogen.sh && make &&
sudo make install` for every project. BUT THERE ARE BAZILLIONS OF THEM. To
automate this annoying chore, I just use the `easy_e17.sh` script.

So, to get it the easy way:

{% highlight sh %}
$ wget http://omicron.homeip.net/projects/easy_e17/easy_e17.sh
$ chmod +x easy_e17.sh
$ sudo ./easy_e17.sh --install
{% endhighlight %}

This will install the the most basic functionality of e17 — the core EFL and
the WM.

If you want to get more power, you can install all of the extra modules, by
providing `--packagelist=half` to the installer, or simply everything, by
providing `--packagelist=full`. Be warned that some of these additional
features may not compile, or may be unmaintained and conflict with your stuff.

To peek on the things you can configure in the install script, just use
`--help`.

If you'd rather have control over all of the build process, or want a sane way
of getting the newest features of the repository, you can use the sample script
on the [SVN repository](http://svn.enlightenment.org) as basis and modify it as
you need.

> Note that for building the `ewheather` module you'll need to build and
> install the `libeweather` (on `trunk/PROTO`) first. For the `places` module
> you'll need `HAL` too.



#### 3.2.3. Setting the environment

If all goes well, you'll have enlightenment and its libraries (and perhaps a
few extra modules too) fully installed on your system. If you've used a
non-standard install path, which is probably the case with running the
`easy_e17.sh` script, you'll need to export the paths so your OS can find all
that stuff.

You can just copy the lines `easy_e17.sh` tells you and paste them in your
`.bashrc` file, then reload it:

{% highlight sh %}
$ nano ~/.bashrc
$ source ~/.bashrc
{% endhighlight %}


#### 3.2.4. Telling your OS to use e17

If you're using a Desktop Manager, you should probably look for how to add more
sessions to it. If you just don't care about all that, you can set a simple
`.xsession` file on your `$HOME` folder and restart X:

{% highlight sh %}
$ echo "exec `which enlightenment_start`" > ~/.xsession
{% endhighlight %}

> if you're using a Desktop Manager, you'll need to logout and select `User
> Defined Session`.



## 4. Wrapping it up

As you can see, there's much more to Enlightenment than the "**lightweight**"
or "**beauty at your fingertips**" stuff you hear everywhere, but most of the
nice things about it can't be easily (if at all) put into words. It's about the
UX — about how you feel while interacting with the system, — and as such it's
something you really have to try out to understand.

Don't forget to drop by `#e@irc.freenode.org` if you have any doubt or problems
with EFL or e17.
