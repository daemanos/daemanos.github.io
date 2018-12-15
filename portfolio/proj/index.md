---
layout: portfolio
---

# Projects

Here you can see a sample of my writing work, both as part of the Technical
Writing course and elsewhere as part of personal coding projects.

## Rhetorical Analysis Memo

The Rhetorical Analysis Memo involved an in-depth analysis of one particular
document in the field of computer science based on the principles of rhetoric I
learned as part of the Technical Writing course. For [my
document](rhetmem.pdf), I chose one particular entry in the popular
series [learnxinyminutes](https://learnxinyminutes.com), specifically, their
article on C.

This assignment forced me to think critically about rhetorical style as it
applies to a very common task in the world of computer science and software
engineering: writing tutorials. This also extends rather easily into writing
manuals and other kinds of introductory material. As such, the assignment
allowed me to improve my own writing by identifying the real-world
instantiations of the rhetorical techniques I have learned in the Technical
Writing course. It also gave me important practice in peer review, a crucial
task of any technical writer.

## Extended Definition

This assignment built on the earlier practice with writing and reviewing
introductory material by having me construct an *extended definition*, which is
a long-form discussion of one particular word or phrase, going beyond a typical
'dictionary definition' by also considering the rhetorical context and going
into far greater depth. For [my extended definition](extdef.pdf), I
chose to consider the topic of 'password safety'.

As part of this, I gained significant concrete experience in communicating
technical ideas to an audience that may not be well-versed in the relevant
field (which may be non-technical professionals or even just technical
professionals in other fields). This, of course, is a task which most computer
scientists must do at some point in their career, and so the experience was
quite worthwhile. Actually having to write the full definition elucidated many
things which I previously thought were simple or straightforward, but which
actually require some significant reflection and consideration of the
rhetorical, ethical, and technical context. As a result of this assignment, I
am thus now better equipped to be able to communicate technical ideas in a
succint and semi-non-technical manner.

## Proposal

This assignemnt explored another aspect of technical writing: proposals for
research projects. For [my proposal](proposal.pdf), I chose to draw
inspiration from work I have previously done on the [MLton
compiler](https://mlton.org) with my professor Matthew Fluet, who is the
principal maintainer of MLton.

This provided another opportunity to use skills learned as part of the
Technical Writing course, integrated with my own technical writing background,
to produce a fully realized document of a sort I may well have to produce as
part of my career. Because I intend to go into research, this was a
particularly relevant assignment for me, as writing in an academic domain can
be very different from other domains, and writing to propose a funded research
project even more different. The skills I learned in Technical Writing,
especially with regards to consideration of the rhetorical context and
audience, proved extremely helpful in the writing of this document and allowed
me to go far beyond my previous abilities.

## Manual

The final and most comprehensive assignment entailed writing a full manual on
the topic of undergraduate retention rates. The target audience consisted of
incoming students to RIT, and the goal was broad and open-ended: supply these
new students with everything they need in order to graduate from RIT. You can
see my final product [here](manual.pdf).

The construction of this manual required the integration of all the various
skills I learned as part of the course (consideration of rhetorical context,
ethics, professionalism, style, organization, and so on) as well as previous
skills I have learned over the course of my undergraduate career, including
my own experience of life at RIT (academically and otherwise), as well as my
knowledge of the LaTeX typesetting system to produce a fairly polished final
document with appropriate and consistent design elements throughout.

As such, this assignment provided an engaging opportunity to create a long-form
document, the construction of which flexed all of my technical writing muscles,
as it were. Knowing what elements of one's toolbox to draw from, and when, is a
skill in and of itself, which this assignment forced me to both use and
develop. For example, in the academic section it was very important to source
information reliably and present it in a clear, concise manner; consideration
of the rhetorical context here was important as well, but perhaps not quite as
important as it was in the other sections, where I drew primarily on my own
experience. In those sections it was paramount to take the rhetorical and
ethical context into account, whereas the 'research' aspect was fairly minimal.

## Pangloss

For most of my personal documents, I use the [pandoc](https://pandoc.org) tool
to convert Markdown sources into either PDF or HTML documents. Pandoc has its
own variety of Markdown that has broad support for almost any form of standard
document layout. However, as I am an avid conlanger I am often in the business
of writing grammars, and these tend to make heavy use of [interlinear
glosses][gloss], for which pandoc has no native support.

Luckily, pandoc provides a mechanism for filters. These are standalone programs
that receive a JSON-encoded version of the pandoc AST on standard input, modify
it, and write back the modified JSON encoding to be further processed by
pandoc. So, I wrote [pangloss](https://github.com/daemanos/pangloss), a pandoc
filter for converting interlinear glosses into interlinear glosses for PDF and
HTML output.

## Lexis

Lexis is a utility for generating dictionaries from Markdown source files. I
have developed it on-and-off over the course of several years for my own
personal use in conlanging, and recently decided to clean it up and release it
[on Github](https://github.com/daemanos/lexis).

## Flags

I am a hobbyist vexillologist and occasionally make flags; you can see some of
them [here](/proj/flags). I also have a personal flag which I explain in
detail on [its own page](/about/personalflag).

**Note:** these links go to my actual personal website, so the navigation
will change.

## School

Some smaller projects I've done as part of my courses include:

- A web-based checkers application with the [Spark
  microframework](sparkjava.com) and Java 8
- Dijkstra's algorithm in MIPS assembly
- Developed and wrote the reference implementation for a project involving the
  creation of an infix calculator in MIPS assembly
- Created plots for a research project in Science and Analytics of Speech
  using [Julia](julialang.org) and [Gadfly](gadflyjl.org)
- An ASCII wildfire simulator and a partial R2K object file parser in C

Where applicable, source code for the above projects is available upon request.


[gloss]: https://wikipedia.org/wiki/Interlinear_gloss
