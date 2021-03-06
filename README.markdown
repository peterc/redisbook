The Redis Book (as yet otherwise unnamed)
=========================================

What?
-----

The Redis book is an attempt at creating the definitive tutorial and reference guide to [Redis](http://code.google.com/p/redis/), an open-source, 
memory based, persistent, key-value data storage system built by Salvatore Sanfilippo of VMware.

This repository contains a [nanoc](http://nanoc.stoneship.org/) project that builds an HTML version of the book, based
upon content in HTML files found in the `content/` directory. The book's source HTML files are nanoc-style [Markdown](http://daringfireball.net/projects/markdown/)
documents that also contain special book-specific directives that I'm currently calling "Pebo" syntax. [ASCIIDoc](http://www.methods.co.nz/asciidoc/)
is being considered as a destination format, however.

Key ambitions for the book are to be transparent (public GitHub repo with latest content), open (non-commercial Creative Commons license and allowing changes via GitHub forks),
and to make for good reading and learning (including SVG figures - some interactive, hopefully). I will be 
selling an attractive PDF and print book later on down the line while having the same content available online for free, rather
like Michael Hartl's [RailsTutorial.org.](http://railstutorial.org/)

Status
------

The project has only just been started after a little offline planning. There is nothing to see yet. *August 6, 2010*

Building The Book For Yourself
------------------------------

* Install the `kramdown`, `nanoc`, and `nokogiri` gems
* Install [Pygments](http://pygments.org/download/) for syntax highlighting - `sudo easy_install Pygments` may get you there on OS X and Linux.
* Run `rake` to compile book and assets into `output/`
* Run `rake serve` to build the book and serve it at [http://127.0.0.1:3000/](http://127.0.0.1:3000/)

Credits
-------

The primary author, so far, is Peter Cooper. Contributors (either in code or writing) include:

* Jim Remsik ([bigtiger](http://github.com/bigtiger))