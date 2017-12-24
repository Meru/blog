---
layout: post
title: "Konosora Patch History"
date: 2017-12-24 00:00:00
img: 2017-12-24-konosora-patch-history.png
description: Duke Nukem Forever of VN translations
hidden: false
---

The Beginning
-------------

It all started back in 2013. I noticed an article on Sankaku about Moenovel
appearing out of nowhere and preparing Konosora for a release. I was excited
cause story about a crippled girl was exactly what I wanted.  

In the end, I was disappointed by this VN's story and not sure if I would finish
reading all the routes if I wasn't working on a patch for it. I expected way
more _pain and suffering_ caused by Kotori's disability, but received pretty
much generic setting with forced drama that didn't have anything to do with the
disability at all. And that fucking Tobioka-sensei... He deserves a special
mention. He was so annoying that I almost dropped this VN just because of him.
Konosora is set is a non-fantasy world so I can't help but to think what would
happen to Tobioka-sensei in real life. And IRL he wouldn't be able to walk away
from that runway field without the help of some medics...  
I liked Kazato-imoutos though. They weren't anything special either, but their
route(s) had everything you would expect from twins (っ´▽｀)っ  

Back to the topic. I think it was known that localization is not gonna be 18+
and a team quickly formed with the aim to restore removed content. But it was
more than that. Back then, things like VNs on Steam weren't a thing yet, but
everyone knew that we'll see more stuff coming out, many of which may be
butchered as well. So it was also a kind of movement to show that people are
against this. This is when _Restoration Patch 1.0_ was born.

Alternative Patch
-----------------

Back then I wasn't yet involved, not counting some random discussions in IRC.
But when _Restoration Patch 1.0_ got released, it turned out that an average
user is too stupid to apply it correctly. I also thought that the way patching
is performed is suboptimal and a pain to deal with, even if you know exactly
what to do and how it works.  
This is when I made my first patch for Japanese Konosora. It wasn't doing
anything fancy, it just converted Japanese version to an exact copy of a patched
English version. But I made it in a much more user-friendly way. Also there was
a small mod that was preventing Konosora from disabling DWM/Aero on Windows
Vista/7 - a stupid and extremely annoying feature that only Pulltop knows why it
even exists.  

Hovewer, _Restoration Patch 1.0_ had various problems. There were bugs, some
things were just broken. Naturally my patch inherited all of these problems.
Then I realized that Moenovel version is a total disaster and trying to fix
anything about it is just a waste of resources. So after confirming that Aaeru
(she was an admin back in the day when Fuwanovel wasn't a totally useless shit)
is ok with me using her (more or less) translation I decided to make my own
patch from scratch.
It was titled _English Translation Patch 1.2_. Not _2.0_ as it probably should
have been. On the outside there weren't much obvious changes, so assigning this
big milestone number didn't feel right. But it was a complete rewrite
nonetheless.  

Back then I was working alone and never tested things much, so a couple more
versions of the patch appeared over the years. Then things finally settled (or
so I thought) at _English Translation Patch v1.2.6_. It is by no means bug-free,
but by the most part good enough.

New Development
---------------

While I was making my patch, it seems people's interest in fixing horrible
Moenovel version died down. But Pabloc was still working on TLC for Moenovel's
horribad translation, that eventually started to be referred to as
_re-translation_.  
This is when Pabloc asked if we could join forces, meaning adding his script to
my patch.  
I expected that this might happen so I agreed pretty quickly.  

Initially I expected to receive a ready-to-use compiled scripts that I just have
to add to my patch and be done with it. Unfortunately, it turned out that
there is no such thing and all I have is a text version of the scripts stuffed
into the horrible google sheets with pretty much nothing else. I was _really_
unsure if I want to go forward with that. But then, overnight I hacked together
a buggy parser+compiler for the scripts that can take stuff from dreaded google
sheets and decided that I will make this project happen. 

Steamy Drama
------------

Of course there was drama. Big and small. It wouldn't be a fan TL project
without one (´−｀) ﾝｰ Small one is not worth mentioning, so let's get to the
more juicy stuff.

It all started after Moenovel released Konosora on Steam.  
Some dude with a name something like _stalinchan_ (if my memory serves me right)
contacted me about making a patch for Steam version. But the thing is, me and
Pabloc weren't really interested in supporting Steam. In fact, personally I
don't really like Steam. This includes it as a platform as well as community.
Additionally, that _stalinchan_ dude was completely clueless about what is
required to support Steam or how to actually do it. So his proposal to "help"
was rejected. To me it looked like he expected to become a (useless) part of the
project for the sake of bragging rights or something. Not to mention that I had
a hard time understanding what he is saying at all due to his English being on
google-translate level or below.  
He got extremely pissy about it though and ended up making a guide, where he
seemingly explained how to patch Steam version of the Konosora and provided some
patch files.  

One part of the files was a copy of the _Restoration Patch 1.0_, but obviously
you can't apply it to the Steam version as is, even he knew that (I think?). So
he came up with a thing called something like _Sweet Love UI Patch_, implying
that he made it and that it's gonna fix a shitload of issues that users
experienced. Of course it had nothing to do with UI and was actually a
collection of assorted files taken from all sorts of places. These are
irrelevant files taken from Japanese Konosora torrent release, random files from
Japanese DVD, including unpacked DirectX setup and the actual Japanese installer
(yep his cluelessness is absolute, it seems). _And_, most importantly, there
were files from my _English Translation Patch 1.2.6_
My files are the only useful thing in that pile of garbage and this it what
makes the end-result at least somewhat usable. But even here he failed and among
other problems, patched Steam version no longer works on non-JP locale - an
inconvenience that properly patched Japanese version doesn't have. He tried to
solve the issue by adding an old crap called NTLEA, that should not be used for
any purpose at all.

But, since I didn't really care about Steam, I just ignored it.  
Time went by, users kept complaining about his so-called patch, he couldn't do
anything about it so he went quiet.  

Some time later - another dude named _HARKI_ appeared to continue where previous
guy left off. Just as clueless. He even messaged me asking about Steam version.
His last message included the following:
> I wish I knew something about hacking at all.

This, however, didn't stop him from making yet another Steam guide with all the
same content, without having any kind of permission to use my stuff and
providing no credits whatsoever, implying that he made this.  
Though, I should say, I am not 100% positive that both of these guys are not the
same person.

I couldn't care less about _HARKI_'s "guiding" endeavors on Steam but you should
know that he maybe guiding you into a pit.  
From his guide it may seem like his so-called patches are more legal than
downloading Japanese Konosora from torrents and applying my patch to it, but
in truth, it is exactly the same. JP and EN Konosora versions are not considered
to be the same VNs so using his patches you are illegitimately acquiring assets
from JP version. The only thing that's different is the way you do it.

Mowing Forward
--------------
In general, this project had its ups and downs, regardless of all the drama.  
Years went by, but this project still sits on my shoulders without a clear
conclusion in sight.  
At some point me (and I think Pabloc as well) lost interest in this project.
Sometimes I thought it would be cool if Pabloc gave up on it. Other times I
thought that it would be stupid to leave things unfinished. After all we already
went this far.  

One way or another, we are still alive and kicking and the project, albeit
slowly, is still moving forward. On my part I have completed everything I have
planned and way more than I ever expected, but then I started to set some
additional goals for myself, implementing various QoL stuff and whatnot. So at
this moment there are still things I would like to implement before the release.
But if not, maybe it will be added a bit later.

As for old Moenovel version as well as Steam one... My main focus is to deliver
a patch for JP version - the only thing that I promised. Other versions are
different. Not only they need to be a re-translation patch but a restoration
patch as well. I will likely support these too, but don't want to give any
promises. If some unexpected stuff will come up, I don't want to feel guilty for
letting people down. Yes, I mean these two or three people who still care about
this VN (^ _ ^)/

The Cliffhanger
---------------
Here I was gonna fast-forward to the second half of the year 2017, but seeing
that this post is already so big (even though I tried to make a TL;DR version)
and this project is still a work-in-progress, I will keep the rest of the story
for the next time.  

From the looks of it, _Konosora English Translation patch 2.0_ will not see a
release in 2017. Luckily, we got a nice QC guy who really helped to move things
forward so Q1 of 2018 seems possible.

To be continued...
