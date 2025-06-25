# kim-1

I was playing with [the KimUno simulator](http://obsolescence.wix.com/obsolescence#!kim-uno-summary/c1uuh) 
for the old KIM-1
microcomputer, and started playing with the source code a bit, and 
ended up deciding that I'd really like to have the source code
for the monitor itself.  A little bit of digging found a variety
of sources for the ROM: I found [ROM dumps and some slightly
mangled source here](http://zimmers.net/anonftp/pub/cbm/src/kim-1/index.html) and perhaps a [more authoritative
source from Commodore here](http://www.commodore.ca/wp-content/uploads/2013/02/manual-kim1_mon.txt).

The source code from the first link was in a slightly bad state 
in terms of formatting and syntax.  I wanted to use the
[assembler from cc65](http://cc65.github.io/cc65/) and so the 
code needed a bit of cleanup.  I spent an hour realigning the 
source code, fixing comments, and adding a config file for 
ld65. If you have cc65, you can recompile the source using the
commands in the file "assembleit".  You can compare the hexdumps
of the original roms with the output to make sure it's compiled
the code properly.

I've added no special restrictions to this, feel free to use 
it for any purpose consistent with any pre-existing licensing
on a 50ish year old computer.
