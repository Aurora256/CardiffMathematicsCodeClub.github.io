---
layout: languages
title: C
categories: inspiration languages
---

### Overview

C is one the oldest languages still in active use today, first created 1972 by
Dennis Ritchie at [Bell Labs][bell-labs] and has gone through many revisions as the
years have progressed with the most recent edition [C11][c11] released early in 2011.

However due to the way C is developed, where a commitee drafts a standard with C's rules
and deatures and it's up to the compiler developres to implement them. This mean that
many of the more recent features are still not available for certain compilers/platforms
so many people try to adhere to the C99 or even AINSI (the original release) standards to increase
portability.

C has been a hugely influencial language and has inspired the design of many of newer languages
including C++, Java, Go, Python and many, many more. C has and still is so popular due
to the fact it is extremely portable, chances are a compiler exists for almost any processor
arcitecture out there and produces extremely fast executables.

But that speed comes at a cost, anything but the simplest of tasks are left to the programmer.
This means when programming in C you have to manage your own memory, perform bound checks on arrays
and more. If you forget to ensure you don't actually access memory you have to right to at best you
can introduce a bug that will crash your program, however a hacker can exploit this and inject malicious
code into your program and basically hi-jacking you or your clients' machine...

If you would like more information about the history or evolution of this language
then you can follow [this][cwiki] link

### Applications

C is heavily used for working with hardware, so many device drivers and operating systems such as
Linux are implemented in C. It's performance means it's a popular choice for real-time systems and
applications such as video games. Also languages such as Python, Perl and PHP all have their interpreters
written in C.

Below is a list of applications that use C:

- [Blender][blender]
- [GameBoy Games][gba]
- [The Linux Kernel][kernel]
- [Vim][vim]
- Pretty much any linux command line tool (ls, cd, wget, curl, grep, sed, etc.)
- And many more!

### Some Code

Hello World:
{% gist alcarney/249466469521937d78c8 %}

A little program that will count the number of lines in a file
{% gist alcarney/aae3b583a956d92861b1 %}

### Some Useful Libraries/Tools

- [GCC Compiler][gcc]
- [CLang Compiler][clang] also provides static analysis tools
- [GDB Debugger][gdb]
- [Valgrind][valgrind] a tool to help debug/optimise C code helps spot memory leaks, race conditions also includes heap, cache and branch predicion profilers
- [Check][check] a unit testing library for C

[bell-labs]: http://en.wikipedia.org/wiki/Bell_Labs
[blender]: https://www.blender.org
[c11]: http://en.wikipedia.org/wiki/C11_(C_standard_revision)
[check]: http://check.sourceforge.net
[clang]: http://clang.llvm.org
[cwiki]: http://en.wikipedia.org/wiki/C_(programming_language)
[gba]: http://www.coranac.com/tonc/text/toc.htm
[gcc]: https://gcc.gnu.org
[gdb]: http://www.gnu.org/software/gdb
[kernel]: https://kernel.org
[valgrind]: http://valgrind.org
[vim]: http://www.vim.org