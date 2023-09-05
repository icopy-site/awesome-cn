<div class="github-widget" data-repo="GustavBertram/awesome-common-lisp-learning"></div>
## Awesome Common Lisp Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="https://raw.githubusercontent.com/GustavBertram/awesome-common-lisp-learning/master/LISP_logo_mid.png">
</div>

This list focuses on resources for learning Common Lisp, especially resources that I've found useful.

There are other Awesome Common Lisp lists that focus on other topics:
- [Libraries](https://github.com/CodyReichert/awesome-cl)
  - [Curated Libraries](https://github.com/vindarel/curated-awesome-cl) - Forked and updated from the above list.
- [Software](https://github.com/azzamsa/awesome-cl-software)

Contributions are welcome. Please read the [contribution guidelines](https://github.com/GustavBertram/awesome-common-lisp-learning/blob/master/contributing.md) for details.



## How To Use
1. Get a Lisp environment.
2. Bookmark the [The Common Lisp Hyperspec](http://www.lispworks.com/documentation/common-lisp.html).
3. Download and work through a Lisp book of an appropriate level. Type the examples and play with the code. Feel free to switch books and try a different one.
4. Try out [Exercism](https://exercism.org/tracks/common-lisp).
5. If you get stuck, find an online community and [ask smart questions](http://www.catb.org/esr/faqs/smart-questions.html).
6. Learn about [Quicklisp](https://www.quicklisp.org/beta/).
7. At some point, read your Lisp implementation's manual.

## Lisp Environments
You can run a Lisp implementation directly, but an editing environment makes the experience easier.
- Prepackaged environments
  - [Portacle](https://shinmera.github.io/portacle/) - A portable and multiplatform Common Lisp environment. It ships a slightly customized Emacs with SLIME, SBCL (a popular Common Lisp implementation), Quicklisp and Git. No installation needed, so it's a very quick and easy way to get going.
  - [Lispbox](https://common-lisp.net/project/lispbox/) - An IDE (Emacs + SLIME), Common Lisp implementation (Clozure Common Lisp) and library manager (Quicklisp), pre-packaged as archives for Windows, macOS and Linux. Descendant of "Lisp in a Box" [mentioned](http://www.gigamonkeys.com/book/lather-rinse-repeat-a-tour-of-the-repl.html) in Practical Common Lisp.
  - [Lispworks Personal Edition](http://www.lispworks.com/downloads/) - A non-Emacs based IDE for LispWorks Lisp, with some restrictions.
  - [Allegro Common Lisp](https://franz.com/products/allegrocl/) - Has a free [Express Edition](https://franz.com/downloads/clp/survey) IDE, and [training videos on YouTube](https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw).
- For advanced users
  - [Articulate Common Lisp](http://articulate-lisp.com) - A HOWTO for putting together a Lisp environment, and has information on [useful libraries](http://articulate-lisp.com/project/abcs.html) and how to [structure projects](http://articulate-lisp.com/project/new-project.html).
  - If you're an experienced [Emacs](https://www.gnu.org/software/emacs/) user, you can just install [SLIME](https://common-lisp.net/project/slime/) and a [supported Common Lisp implementation](https://common-lisp.net/project/slime/doc/html/Platforms.html#Platforms). See the [SLIME manual](https://common-lisp.net/project/slime/doc/html/) for more details.
  - The Common Lisp Cookbook has more information about [installing an implementation](https://lispcookbook.github.io/cl-cookbook/getting-started.html) using an implementation manager like [Roswell](https://github.com/roswell/roswell/wiki), or on Docker.

## Online References
- [The Common Lisp Hyperspec (CLHS)](http://www.lispworks.com/documentation/common-lisp.html) - *The* language reference document for Common Lisp. Bookmark it now.
  - [Chapter 7](http://www.lispworks.com/documentation/HyperSpec/Body/07_.htm) - Covers the Common Lisp Object System (CLOS).
- [The ANSI Common Lisp Standard Draft](http://cberr.us/tech_writings/notes/common_lisp_standard_draft.html) - The last draft version of the ANSI INCITS 226-1994 (previously ANSI X3.226-1994) standard.
  - The draft is free, the standard isn't.
  - It's pretty much the same as the official standard, and some people prefer it to the CLHS.
- [The Common Lisp Cookbook](http://lispcookbook.github.io/cl-cookbook/) - A list of useful Lisp recipes. Also contains a list of other online sources of CL information.
- [Common Lisp the Language (2nd Edition) by Guy L. Steele](https://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - A description of the Common Lisp language from just before it was standardized by ANSI. Don't use it as a reference.
  - [Cliki on CLtL2](https://cliki.net/Getting+Started) - Claims it has more useful descriptions of [LOOP](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node235.html#SECTION003000000000000000000) and [FORMAT](http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/html/cltl/clm/node200.html) than the CLHS does.
  - [Stack Overflow on CLtL2](https://stackoverflow.com/questions/108537/what-are-the-main-differences-between-cltl2-and-ansi-cl) - Some recommend using CLtL2 for insight and inspiration, but to use the CLHS when programming.
  - [A list of differences between CLtL2 and the ANSI Common Lisp specification.](http://linuxfinances.info/info/commonlisp.html#AEN9679)
  - [Chapter 28](https://www.cs.cmu.edu/Groups/AI/html/cltl/clm/node260.html#SECTION003200000000000000000) - Covers the Common Lisp Object System.

## Online Books
These books that are freely accessible online, arranged roughly in order from basic to advanced:
- [Common Lisp: A Gentle Introduction to Symbolic Computation by David S. Touretzky](http://www.cs.cmu.edu/~dst/LispBook/) - a good introduction for people new to programming. Contains code for really useful utilities like [DTRACE](http://www.cs.cmu.edu/~dst/Lisp/dtrace/) and [SDRAW](http://www.cs.cmu.edu/~dst/Lisp/sdraw/).
- [Common Lisp: An interactive approach by Stuart C. Shapiro](https://www.cse.buffalo.edu/~shapiro/Commonlisp/) - A textbook that teaches mainly through the use of exercises.
- [Practical Common Lisp by Peter Seibel](http://www.gigamonkeys.com/book/) - A great introduction for experienced programmers, and tries to highlight from the very beginning what makes CL different to other languages.
- [Common Lisp Koans](https://github.com/google/lisp-koans) - Not exactly a book, but a set of koans to help you learn the language.
- [On Lisp by Paul Graham](http://www.paulgraham.com/onlisp.html) - A great book for intermediately experienced Lispers.
- [Let Over Lambda by Doug Hoyte](https://letoverlambda.com) - An advanced book on Lisp Macros.
  - The first six chapters are available online.
  - [Comments on Let Over Lambda](https://www.reddit.com/r/lisp/comments/3actsc/let_over_lambda/) - Several people recommend that you be comfortable with On Lisp before reading this book, and that the start is slow.
  - [The chapter on closures](https://letoverlambda.com/index.cl/guest/chap2.html) - Has several non-trivial examples, and demonstrates the power of this feature.
- [Paradigms of Artificial Intelligence Programming by Peter Norvig](https://github.com/norvig/paip-lisp) - Has many interesting applications of Lisp, but is no longer a good reference for AI.

## Offline Books
These are books that you'll have to buy, or borrow from a library.
- [Land of Lisp by Conrad Barski, MD](http://landoflisp.com) - A fun introduction to Lisp that uses comics and has you writing games.
  - Available as an [ebook](https://www.nostarch.com/lisp.htm). 
  - A couple of the LOOP macros are written `for x for y...` which you can change to `for x from 0 for y...` to make them work in SBCL.
  - Has an [errata page](http://landoflisp.com/errata.html).
  - Most of the book is entertaining and fairly easy, but gets hairy from about Chapter 18. It doesn't feel like later chapters introduce much, so I recommend switching to a different book at that point.
  - The Web server example in Ch 13, 19 and 20 will only work on CLISP, and needs the addition of HTTP response headers to render the HTML properly.
- [ANSI Common Lisp by Paul Graham](http://www.paulgraham.com/acl.html) - Good as a reference, covers CLOS, and has several example program implementations.
  - Plaintext versions of [Chapter 1](http://lib.store.yahoo.net/lib/paulgraham/acl1.txt) and [Chapter 2](http://lib.store.yahoo.net/lib/paulgraham/acl2.txt) are available online.
- [Common Lisp Recipes by Edmund Weitz](http://weitz.de/cl-recipes/) - A great set of Common Lisp patterns.
- [Object-Oriented Programming in Common Lisp by Sonya E. Keene](https://www.amazon.com/Object-Oriented-Programming-COMMON-LISP-Programmers/dp/0201175894) - An in-depth description of the CLOS, and shows how to use it with example applications.
- [The Art of the Metaobject Protocol by Gregor Kiczales, Jim des Rivieres, and Daniel G. Bobrow](https://www.amazon.com/Art-Metaobject-Protocol-Gregor-Kiczales/dp/0262610744/) - Describes the CLOS Metaobject Protocol (MOP).
  - [Chapters 5 and 6 (available online)](http://metamodular.com/CLOS-MOP/) - The specification of a metaobject protocol extension to CLOS, by Robert Strandh.
    - Superseded by the [modern public domain CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) by Jean-Philippe Paradis ([Hexstream](https://github.com/Hexstream)).
  - [Adam Tornhill on AMOP](http://www.adamtornhill.com/reviews/amop.htm) - Recommends reading Practical Common Lisp, then  Object-Oriented Programming in Common Lisp, and then AMOP.

## Online Community
- The [Cliki](http://cliki.net) - The Common Lisp Wiki. A great resource for all things CL. Has a great [Getting Started](http://cliki.net/Getting+Started) page and an extensive list of [Lisp books](http://cliki.net/Lisp%20books).
- The #clschool, #lisp, #ccl, #sbcl and [other rooms](https://www.cliki.net/IRC) on the [Libera.Chat](https://libera.chat/) network are great places for learning about Common Lisp. ([Freenode should be avoided.](https://gist.github.com/joepie91/df80d8d36cd9d1bde46ba018af497409))
- [Lisp Subreddit](http://www.reddit.com/r/lisp/) - An active community, and has loads of useful links and reference documents in the sidebar.
  - [Common Lisp Subreddit](https://www.reddit.com/r/Common_Lisp) - The Subreddit for Common Lisp.
- [Exercism's Common Lisp track](http://exercism.io/languages/common-lisp/about) - An excellent way to learn the language through practice, have your code reviewed, and to discuss solutions with other people.
- [Lisp Discord server](https://discord.gg/7tSq5EaA6Z) - Is a Discord for Lisp. Has a channel dedicated to Common Lisp and will happily answer questions.


## Library Management
These aren't libraries, but can help you find and install other libraries.
- [Quicklisp](https://www.quicklisp.org/beta) - A package management platform for Lisp libraries.
- [Quickdocs](http://quickdocs.org) - Documentation for projects in Quicklisp.
- [State of the Common Lisp Ecosystem, 2015](http://borretti.me/article/common-lisp-sotu-2015) - Article about what libraries you should use, and why.
- [Articulate Common Lisp](http://articulate-lisp.com/project/abcs.html) - Lists some useful libraries.


## Common Lisp Implementations
This section lists some common CL implementations and their manuals in alphabetical order. Unless otherwise noted, these are free software implementations. See also the Cliki's list of [free software Common Lisp Implementations](https://www.cliki.net/Common%20Lisp%20implementation).
- [Allegro Common Lisp (ACL)](https://franz.com/products/allegrocl/) - Commercial, but has a free [Express Edition](https://franz.com/downloads/clp/survey).
  - [ACL manual](https://franz.com/support/documentation/)
  - [Training videos on YouTube](https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw)
- [CLISP](https://clisp.sourceforge.io)
  - [CLISP Manual](https://clisp.sourceforge.io/impnotes.html)
- [Clozure Common Lisp (CCL)](https://ccl.clozure.com)
  - [CCL manual](https://ccl.clozure.com/manual/)
- [Carnegie Mellon University Common Lisp (CMUCL)](https://www.cons.org/cmucl/)
  - [CMUCL manual and other useful information](https://www.cons.org/cmucl/doc/index.html)
- [Embeddable Common Lisp (ECL)](https://common-lisp.net/project/ecl/)
  - [ECL manual](https://common-lisp.net/project/ecl/static/manual/)
- [LispWorks](http://www.lispworks.com/products/index.html) - Commercial, but as mentioned previously, has a [Personal Edition](http://www.lispworks.com/downloads/index.html) with minor limitations.
  - [LispWorks manual](http://www.lispworks.com/documentation/index.html)
- [Steel Bank Common Lisp (SBCL)](http://www.sbcl.org) - My personal favorite.
  - [SBCL manual](http://www.sbcl.org/manual/index.html)
- [Scieneer Common Lisp (SCL)](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/) - A commercial Linux and Unix implementation, but has an unrestricted free evaluation and non-commercial use version.
  - [SCL manual](http://web.archive.org/web/20171014210404/http://www.scieneer.com/scl/doc/)

## Credit
I got a lot of the information from [Rainer Joswig's Stack Overflow answer on learning Common Lisp](https://stackoverflow.com/a/7224914/1005039), and from the now-defunct Stack Overflow Documents site. The [Cliki's Getting Started](https://cliki.net/Getting%20Started) page was also invaluable.
