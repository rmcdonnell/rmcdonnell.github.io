---
layout: post
title: First Post - How I made the blog
---

The blog is served using [github pages](https://pages.github.com/). It's
been created using [jekyll](http://jekyllrb.com/). There are other choices
that seem good like [pelican](http://docs.getpelican.com/en/3.5.0/). Using
jekyll, I also added [poole](http://getpoole.com/) to help with the setup
and [lanyon](http://lanyon.getpoole.com/), an unassuming jekyll theme.

To install jekyll using [Fedora 21](https://getfedora.org/), I used the
following commands. Note that this approach will seem a little wonky
because I was trying to also work around a [jruby issue with fedora](https://bugzilla.redhat.com/show_bug.cgi?id=1174128). I'm not saying this is
the best way, it's just what worked for me.

{% highlight sh %}

$ sudo yum install jruby
$ sudo yum remove gem
$ sudo yum install gem
$ sudo yum install ruby-devel
$ gem install jekyll

{% endhighlight %}

Once the install has successfully completed, it's time to create a
new project. I did this by simply cloning the [lanyon github repo](https://github.com/poole/lanyon). I added the lanyon repository as [upstream](https://help.github.com/articles/syncing-a-fork/) using git; my github
pages repo was added as the origin.

After this initial setup, I just made smaller changes to fit my personal
preferences.

Thanks Ty!


