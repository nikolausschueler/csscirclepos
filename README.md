# csscirclepos
Perl scipt that generates CSS for circular arrangment of links

# What is this?

A Perl script that writes out a CSS file (to stdout) which defines circular
positions. This allows you to arrange links on a circle. This is neat, for
example, for a start page that links to several topics.

The script has one argument, the number of links for which attributes have to be
written.

The file created by this script can be included into your existing CSS. The demo
shows how.

The CSS attributes are written for list elements that must have a class of c0 to
c(n-1).

I wrote this thing quite some years ago. This was split out from a bigger repo,
instead of starting a new repo, so that the ancient commits are preserved, with
date.
