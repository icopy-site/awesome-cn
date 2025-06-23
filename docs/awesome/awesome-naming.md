<div class="github-widget" data-repo="gruhn/awesome-naming"></div>
## Awesome Naming [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- lint disable no-repeat-punctuation -->
Famously...
<!-- lint enable no-repeat-punctuation -->

> There are only two hard things in Computer Science: cache invalidation and naming things.
> 
> ― Phil Karlton

Concepts in computer science are usually nothing tangible so it's no surprise that naming things is hard.
Nevertheless, we _do_ come up with clever, creative and funny names.
Some of them so established, we never pause and admire.

This is a curated list for when naming things is done right.


- [Theoretical Computer Science](#theoretical-computer-science) 

---

## Data Structures and Algorithms

- [Backtracking](https://de.wikipedia.org/wiki/Backtracking) - When you explore a search space and you reach a dead end, you follow your *tracks* back to the last crossroad and try the other way. 
- [Brute force](https://en.m.wikipedia.org/wiki/Brute-force_search) - Violence is actually almost always a solution but not a very clever one.
- [Greedy algorithm](https://en.wikipedia.org/wiki/Greedy_algorithm) - An algorithm that finds a solution by always picking the currently best looking option without thinking too much about past and future decisions.
- [Hill climbing](https://en.wikipedia.org/wiki/Hill_climbing) - Starting somewhere in the hilly "landscape" of solutions you go in the direction of steepest ascent until reaching the top of a hill. You might miss higher hills though. 
- [Israeli Queue](https://rapidapi.com/blog/israeli-queues-exploring-a-bizarre-data-structure/) - A type of priority queue and a reference to the infamously unorganized queues in Israel. Here items can *cut in line* when they *have already waiting friends*.
- [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) - Like with a stack of pancakes you can only add and remove items from the top of this data structure.
- [Tree](https://en.wikipedia.org/wiki/Tree_(data_structure)) - A hierarchically organized data structure. From the _root_ item the other items _branch out_ into _nodes_ and _leaves_. A collection of trees is often called a *forest*.
- [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) - In this data structure items are always added at the end and removed at the front as if the items were waiting in line.

## Design Patterns and Anti Patterns

- [Adapter](https://en.wikipedia.org/wiki/Adapter_pattern) - Allows classes with incompatible interfaces to work together by wrapping its own interface around that of an already existing class.
- [Facade](https://en.wikipedia.org/wiki/Facade_pattern) - Analogous to a facade in architecture, a facade is an object that serves as a front-facing interface masking more complex underlying structure.
- [Promise](https://en.wikipedia.org/wiki/Futures_and_promises) - A representation of a result that is available in the future, unless there are errors. Like in reality, promises are broken sometimes.
- [Shotgun surgery](https://en.wikipedia.org/wiki/Shotgun_surgery) - A programming antipattern where in a single change you wildly add code everywhere in your codebase.
- [Spaghetti Code](https://en.wikipedia.org/wiki/Spaghetti_code) - A program with a tangled and hard-to-follow stucture.

## Functions

- [fold](https://en.wikipedia.org/wiki/Fold_(higher-order_function)) - Like a blanket being folded up, this function iterates a collection and in each step combines the current item with everything that has already been folded.
- [munch](https://hackage.haskell.org/package/base-4.19.0.0/docs/Text-ParserCombinators-ReadP.html#v:munch) - Parser function that greedily consumes an input stream until it's satisfied.
- [trampoline](https://clojuredocs.org/clojure.core/trampoline) - Continuously runs functions which itself return functions. Like a child on a trampoline that _returns_ and bounces back up. 
- [zip](https://hackage.haskell.org/package/base-4.12.0.0/docs/Prelude.html#v:zip) - Merges two lists into one list of pairs like the interlocking teeth of a zipper.

## IT Security

- [Backdoor](https://en.wikipedia.org/wiki/Backdoor_(computing)) - A method of bypassing normal authentication in a computer system.
- [Computer virus](https://en.wikipedia.org/wiki/Computer_virus) - A computer program that self replicates by _infecting_ other computer programs similar to the behavior of biological viruses.
- [Cyber hygiene](https://digitalguardian.com/blog/what-cyber-hygiene-definition-cyber-hygiene-benefits-best-practices-and-more) - Steps and practices that users should take to maintain system health and improve online security.
- [Honeypot](https://en.wikipedia.org/wiki/Honeypot_(computing)) - Part of a system meant to look like an attractive target but actually helps detect and deflect attackers.
- [Phoning home](https://en.wikipedia.org/wiki/Phoning_home) - When a system (e.g. stolen computer) secretly reports back to a third party other than the current possessor. The name is a reference to the movie E.T.
- [Sandbox](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) - A safe and isolated environment to test unverified programs that may contain malicious code.
- [Trojan horse](https://en.wikipedia.org/wiki/Trojan_horse_(computing)) - Malware which misleads users of its true intent. The term is derived from the Ancient Greek story of the deceptive Trojan Horse. 

## Machine Learning and Artificial Intelligence

- [Confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix) - A tabular summary of a classifiers "confusion", i.e. how often it thought to make correct predictions when it actually didn't.
- [Decision boundary](https://en.wikipedia.org/wiki/Decision_boundary) - A boundary dividing the space of possible data points. Here you decide, everything on this side is SPAM, everything on that side is not.
- [Gradient descent](https://en.wikipedia.org/wiki/Gradient_descent) - Minimizing a cost function by iteratively computing the gradient and moving in the direction of steepest descent. 
- [Hallucination](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)) - A confident response by an AI that does not seem to be justified by its training data.
- [Training](https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets) - The process of showing the machine a bunch of examples, until it learns what we want from it.

## Programming Languages and Programming Language Theory

- [Choreographic programming](https://en.wikipedia.org/wiki/Choreographic_programming) - A programming paradigm where programs are compositions of interactions among multiple concurrent participants.
- [Clojure](https://clojure.org/) - A functional language making extensive use of **closures** but with a **j** because it's running on the Java virtual machine.
- [C++](https://en.wikipedia.org/wiki/C%2B%2B#External_links) - Although C was certainly a bad name, C++ was quite clever. The iconic increment operator **++** indicates that **C++** is the successor.
- [Garbage Collector](https://en.m.wikipedia.org/wiki/Garbage_collection_(computer_science)) - Part of a program that attempts to find and reclaim garbage pieces of memory not used anymore.
- [Lazy evaluation](https://en.wikipedia.org/wiki/Lazy_evaluation) - An evaluation stategy which suspends evaluation until it's absolutely necessary and then never does it again.
- [Syntactic sugar](https://en.wikipedia.org/wiki/Syntactic_sugar) - Syntax that makes the language "sweeter" for human use. Usually a shorthand for common operations that can also be expressed in a more verbose form.

## User Interface Design

- [Bento layout](https://www.saasframe.io/blog/the-bento-layout-trend) - A grid based layout resembling the compartmentation of bento boxes.
- [Breadcrumb](https://en.wikipedia.org/wiki/Breadcrumb_(navigation)) - Navigational aid allowing users to keep track of their location within programs, documents, or websites. The term is a reference to the fairy tale _Hansel and Gretel_.
- [Carousel](https://www.nngroup.com/articles/designing-effective-carousels/) - A kind of animated slideshow looping back on itself.
- [Clipboard](https://en.wikipedia.org/wiki/Clipboard_(computing)) - Where you temporarily put _files_ you are working with (i.e. the copy & paste buffer).
- [Desktop](https://en.wikipedia.org/wiki/Desktop_metaphor) - The metaphorical top of the user's desk, upon which objects such as documents and folders of documents can be placed.
- [Hamburger button](https://en.wikipedia.org/wiki/Hamburger_button) - A button to toggle a menu. The associated icon resembles a hamburger.
- [Optimistic UI](https://uxplanet.org/optimistic-1000-34d9eefe4c05) - User interfaces that assume expensive operations will complete successfully thereby improving the perceived performance.
- [Scrolling](https://en.wikipedia.org/wiki/Scrolling) - Screen content is often less like a book with discrete pages and more like a continuous roll of parchment, i.e. a scroll.

## Theoretical Computer Science

- [Busy Beaver](https://en.wikipedia.org/wiki/Busy_beaver) - Turing machines that produce numbers so insanly large, no other algorithm can keep up with them.
- [Clique problem](https://en.wikipedia.org/wiki/Clique_problem) - The problem of finding groups of mutual friends in a network of people with friendship relations. Or more general, finding complete subgraphs.
- [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) - A game world that showcases how astonishing complexity can arise from very simple ingredients.
- [Oracle](https://en.wikipedia.org/wiki/Oracle_machine) - A black box that magically gives answers even to undeciable questions like the halting problem. 
- [Pumping lemma](https://en.wikipedia.org/wiki/Pumping_lemma) - The fact that in some formal languages any sufficiently long string can be _pumped_ with repetitions of its substring and the result stays in the same formal language.

## Tools, Applications, Libraries, Frameworks

- [clooney](https://github.com/GoogleChromeLabs/clooney) - A JavaScript library implementing the actor model for concurrent computation. The term is a reference to George Clooney who is also an actor.
- [CockroachDB](https://web.archive.org/web/20150514123425/http://www.wired.co.uk/news/archive/2014-07/22/cockroachdb) - Database application, that is marketed as being so fault tolerant and resilient as a cockroach.
- [corrosion](https://github.com/corrosion-rs/corrosion) - The process that turns metal into rust (literally) but also a tool that "turns" C++ into Rust.
- [horcrux](https://github.com/jesseduffield/horcrux) - Splits a file into encrypted fragments that only together can be decrypted again. In the Harry Potter universe, Horcruxes are fragments of a persons soul. To kill the person, all fragments must be destroyed.
- [Puppeteer](https://github.com/puppeteer/puppeteer) - A browser automation library. If the browser is the puppet, this is the puppeteer.
- [Safari](https://en.wikipedia.org/wiki/Safari_(web_browser)) - Web browser developed by Apple.
- [tldr](https://tldr.sh/) - Simplified man pages with practical examples.
- [Uglify](https://github.com/mishoo/UglifyJS) - A JavaScript minifier. Removes everything that makes the code readable and pretty to make it smaller.
- [uppy](https://github.com/transloadit/uppy) - A dog themed uploader component. The name is a blend of _upload_ and _puppy_. It even comes with a crash recovery plugin called _Golden Retriever_.
- [Webpack](https://webpack.js.org/) - A bundler for JavaScript and other *web* assets with a short and descriptive name that also somewhat rhymes.
- [yarn](https://yarnpkg.com/) - NodeJS dependency manager.

## Other

- [a11y, i18n, k8s, ...](https://en.wikipedia.org/wiki/Numeronym) - Abbreviating long words by keeping the first and last letter and writing the number of omitted letters in between. 
- [ACID vs. BASE](https://www.johndcook.com/blog/2009/07/06/brewer-cap-theorem-base/) - Acronyms describing competing database ideologies (aka. SQL vs. NoSQL). Note that acid and base are also opposites in chemistry.
- [Bottleneck](https://en.wikipedia.org/wiki/Bottleneck#Computing) - A central part of a network/application that significantly limits throughput/performance and should ideally be eliminated.
- [Brick](https://en.m.wikipedia.org/wiki/Brick_(electronics)) - When your device is so corrupted it virtually turns into a brick.
- [camelCase, snake_case, kebab-case](https://en.wikipedia.org/wiki/Letter_case#Use_within_programming_languages) - Different case styles where the name illustrates its appearance.
- [Code golf](https://en.wikipedia.org/wiki/Code_golf) - Writing a program in as few characters as possible. Just like how Golf players try to win in the fewest club strokes.
- [Cookie licking](https://devblogs.microsoft.com/oldnewthing/20091201-00/?p=15843) - E.g. claiming a GitHub issue, then not working on it.
- [Easter egg](https://en.wikipedia.org/wiki/Easter_egg_(media)) - A hidden feature especially in video games in reference to the Easter egg hunt.
- [Firmware](https://en.wikipedia.org/wiki/Firmware) - The _ware_ between _software_ and _hardware_.
- [Floating point number](https://floating-point-gui.de/formats/fp/) - This representation can encode numbers at very different magnitudes with limited amount of digits by letting the radix point _float_ instead of being fixed in place.
- [Framework](https://en.wikipedia.org/wiki/Software_framework) - In software architecture (like in actual architecture) frameworks provide basic structure to  build upon that guide and constrain the further development.
- [Glue Code](https://en.wikipedia.org/wiki/Glue_code) - Jenga and LEGO bricks don't share the same interface but you can always glue them together.
- [Heisenbug](https://en.wikipedia.org/wiki/Heisenbug) - A bug that seems to disappear or change when one tries to study it. It's a pun on Werner Heisenberg who discovered that the act of observing quantum systems inevitably alters their state.
- [Hydra](https://computer-dictionary-online.org/definitions-h/hydra-code) - A bug that, when an attempt to fix is made, introduces multiple new bugs. It's a bug that cannot be fixed.
- [Magic](https://en.wikipedia.org/wiki/Magic_(programming)) - A magic program/piece of code is doing it's job but nobody knows how. Like in reality, magic doesn't actually exist. Once you understand it, it's not magic anymore.
- [Process starvation](https://en.wikipedia.org/wiki/Starvation_(computer_science)) - A problem where a process is perpetually denied resources to do its work.
- [Time travel debugging](https://en.wikipedia.org/wiki/Time_travel_debugging) - Stepping back in time through source code to understand execution and sometimes even to change history.
- [Tree shaking](https://en.wikipedia.org/wiki/Tree_shaking) - Shake the dependency tree until all the dead parts are falling off and you end up with a nice lean tree.
- [Unfair enumeration](https://www.youtube.com/watch?v=CvLsVfq6cks&t=835s) - A program that outputs all even numbers and then all odd numbers generates an unfair enumeration of the natural numbers because some numbers are never reached. 
- [Yoda condition](https://eslint.org/docs/latest/rules/yoda) - When you write `if ("red" === color) {` instead of `if (color === "red") {` because it reads as, “if red equals the color”, similar to the way the Star Wars character Yoda speaks.
