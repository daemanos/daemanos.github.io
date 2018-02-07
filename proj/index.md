---
layout: default
---

# Projects

## Personal

### Jet database engine

The Jet database engine grew out of a class project in which I collaborated
with three other team members to create a database for a fictional game with
Java and the H2 database engine.

Over the course of the project, there was so much duplicated code in the
creation of tables that I created a small utility class to abstract out some
of the details. Jet is the distillation and generalization of that and other
database utilities, enabling the rapid creation of sophisticated databases in
pure Java.

It is currently still in its early stages, but you can see it [on
Github](https://github.com/daemanos/jet).

### Pangloss

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

### Lexis

Lexis is a utility for generating dictionaries from Markdown source files. I
have developed it on-and-off over the course of several years for my own
personal use in conlanging, and recently decided to clean it up and release it
[on Github](https://github.com/daemanos/lexis).

### Flags

I am a hobbyist vexillologist and occasionally make flags; you can see some of
them [here](/proj/flags). I also have a personal flag which I explain in
detail on [its own page](/about/personalflag).

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
