Fontfile syntaxes
=================

A collection of the keywords, regular expressions, general structural
patterns, and short human-readable definitions for an assortment of
different font-related file formats.

I started assembling this data when I was working on my second
syntax-highlighting package for the Adobe ``.fea`` format and realized
(relatively) quickly that leveraging the amount of repetition involved
would speed up the process of doing more of them (targetting other
outputs).

Orthogonally to that, it was clear that there are quite a few names,
tags, and other strings that end up getting duplicated across many of
the file formats (such as OpenType feature tags or embedded TrueType
instructions), so I started adding those as well.

The data in this repository does not generate any code (although I
might determine that it's useful to generate some of regular
expressions on-the-fly). It just gets pulled in by other code
elsewhere.

I'll make a list of where at some point in the future and provide some
links.

In the meantime, you're welcome to pull it in yourself.
