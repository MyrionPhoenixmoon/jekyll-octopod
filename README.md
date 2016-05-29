# Jekyll - Octopod

![logo](assets/img/logo.jpg)

A Podcasting publishing extension for the static site generator [Jekyll](https://jekyllrb.com/).

## tl;dr

You generate a static web site for your podcast on your own computer and sync it to your web space. So no Wordpress, PHP, Ruby, Perl, etc. is needed on your server.

## Tell me more!

If you want to take a look: See (and listen to) Stefan's podcast [Aua-Uff-Code!](https://aua-uff-co.de) or find a screenshot below.

Technically Jekyll-Octopod is a Jekyll plugin and a Ruby Gem. It contains of
scripts, templates, helpers and extensions to deliver your podcasts the cool text file lover's way.

If you are not afraid of the command line of your computer and text files are the stuff to heat up your geeky little heart, Octopod may be worth a trial to publish your podcasts.

The underlying assumptions of Octopod are that static content should be delivered statically and text files are the perfect way to handle podcast metadata. So Octopod makes it easy to generate and deploy a website and feeds for your podcast out of one textfile and at least one audio file per episode.


## Features

Jekyll-Octopod brings innately:
* iTunes ready episode feeds for different file formats (e.g. mp3, ogg, m4a)
* a ready to use [Bootflat](http://bootflat.github.io/) and  [Twitter Bootstrap](http://twitter.github.com/bootstrap/) based, responsible (i.e. mobile friendly) layout modifiable to your heart's desire.
* [Flattr](https://flattr.com/) support on the website and in the episode feed
* [Twitter](https://twitter.com) integration on the website
* comments via [Disqus](http://disqus.com/)
* [Podlove Web Player](http://podlove.org/podlove-web-player/) in it's current version 3.0
* Static player pages that are embeddable in iframes at your other or affiliates' sites
* [Podlove Alternate Feeds](http://podlove.org/alternate-feeds/)
* [Podlove Simple Chapters](http://podlove.org/simple-chapters/)
* [Podlove Subscribe Button](http://podlove.org/podlove-subscribe-button/) for easy podcast subscription on any operating system, including mobile phones.
* https compatibilty
* Google search integration
* easy creation of shownotes

***Is this production ready? *** We use it in production and believe it is.
But it is very likely, that it still contains bugs. Hopefully you are brave enough to play with this cute little toy anyway.

This project is absolutely in a non 1.0 status. This means that there is no guarantee that behavior will change with the next update.

## Prerequesites

The [Ruby programming language](http://www.ruby-lang.org/) and it's package manager [Bundler](http://gembundler.com/).

Nice installation guides for the different operating systems can be found at
the [Rails Girls Website](http://guides.railsgirls.com/install). You can stop
right before installing Rails, because we do not depend on Ruby on Rails here.

You can check, if you succeeded, by entering
```
$ ruby -v
$ gem -v
```
at the command prompt. Both commands should return version greater or equal 2.0 .

## Documentation

is provided in the Wiki. Start with the [[Home]].
You will find a link on each page to continue reading as suggested.
Or jump to the individual topics directly:

* [[Installation]]
* [[Demo]]
* [[Usage]]
* [[Contributions]]
* [[Credits]]
* [[License]]

## Maintainer

Stefan Haslinger <mailto:stefan.haslinger@informatom.com>
