<div class="github-widget" data-repo="coq-community/awesome-coq"></div>
## Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/coq-community/awesome-coq/master/coq-logo.svg?sanitize=true" align="right" width="100" alt="coq-community logo" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

> A curated list of awesome Coq libraries, plugins, tools, and resources.

The [Coq proof assistant](https://coq.inria.fr) provides a formal language to write mathematical definitions, executable algorithms, and theorems, together with an environment for semi-interactive development of machine-checked proofs.

Contributions welcome! Read the [contribution guidelines](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) first.



---

## Projects

### Frameworks

- [ConCert](https://github.com/AU-COBRA/ConCert) - Framework for smart contract testing and verification featuring a code extraction pipeline to several smart contract languages.
- [CoqEAL](https://github.com/CoqEAL/CoqEAL) - Framework to ease change of data representations in proofs.
- [FCF](https://github.com/adampetcher/fcf) - Framework for proofs of cryptography.
- [Fiat](https://github.com/mit-plv/fiat) - Mostly automated synthesis of correct-by-construction programs.
- [FreeSpec](https://github.com/lthms/FreeSpec) - Framework for modularly verifying programs with effects and effect handlers.
- [Hoare Type Theory](https://github.com/imdea-software/htt/) - A shallow embedding of sequential separation logic formulated as a type theory.
- [Hybrid](https://www.site.uottawa.ca/~afelty/HybridCoq/) - System for reasoning using higher-order abstract syntax representations of object logics.
- [Iris](https://iris-project.org) - Higher-order concurrent separation logic framework.
- [Q\*cert](https://github.com/querycert/qcert) - Platform for implementing and verifying query compilers.
- [SSProve](https://github.com/SSProve/ssprove) - Framework for modular cryptographic proofs based on the Mathematical Components library.
- [VCFloat](https://github.com/VeriNum/vcfloat) - Framework for verifying C programs with floating-point computations.
- [Verdi](https://github.com/uwplse/verdi) - Framework for formally verifying distributed systems implementations.
- [VST](https://vst.cs.princeton.edu) - Toolchain for verifying C code inside Coq in a higher-order concurrent, impredicative separation logic that is sound w.r.t. the Clight language of the CompCert compiler.

### User Interfaces

- [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - Standalone graphical tool for interacting with Coq.
- [Coqtail](https://github.com/whonore/Coqtail) - Interface for Coq based on the Vim text editor.
- [Coq LSP](https://github.com/ejgallego/coq-lsp) - Language server and extension for the Visual Studio Code and VSCodium editors with custom document checking engine.
- [Proof General](https://proofgeneral.github.io) - Generic interface for proof assistants based on the extensible, customizable text editor Emacs.
- [Company-Coq](https://github.com/cpitclaudel/company-coq) - IDE extensions for Proof General's Coq mode.
- [opam-switch-mode](https://github.com/ProofGeneral/opam-switch-mode) - IDE extension for Proof General to locally change or reset the opam switch from a menu or using a command.
- [jsCoq](https://github.com/jscoq/jscoq) - Port of Coq to JavaScript, which enables running Coq projects in a browser.
- [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) - Coq support for the Jupyter Notebook web environment.
- [VsCoq](https://github.com/coq-community/vscoq) - Language server and extension for the Visual Studio Code and VSCodium editors.
- [VsCoq Legacy](https://github.com/coq-community/vscoq/tree/vscoq1) - Backwards-compatible extension for the Visual Studio Code and VSCodium editors using Coq's legacy XML protocol.
- [Waterproof editor](https://github.com/impermeable/waterproof) - Educational environment for writing mathematical proofs in interactive notebooks.

### Libraries

- [ALEA](https://github.com/coq-community/alea) - Library for reasoning on randomized algorithms.
- [Algebra Tactics](https://github.com/math-comp/algebra-tactics) - Ring and field tactics for Mathematical Components.
- [Bignums](https://github.com/coq/bignums) - Library of arbitrarily large numbers.
- [Bedrock Bit Vectors](https://github.com/mit-plv/bbv) - Library for reasoning on fixed precision machine words.
- [CertiGraph](https://github.com/Salamari/CertiGraph) - Library for reasoning about directed graphs and their embedding in separation logic.
- [CoLoR](https://github.com/fblanqui/color) - Library on rewriting theory, lambda-calculus and termination, with sub-libraries on common data structures extending the Coq standard library.
- [coq-haskell](https://github.com/jwiegley/coq-haskell) - Library smoothing the transition to Coq for Haskell users.
- [Coq-Kruskal](https://github.com/DmxLarchey/Coq-Kruskal) - Collection of libraries related to rose trees and Kruskal's tree theorem.
- [CoqInterval](https://gitlab.inria.fr/coqinterval/interval/) - Tactics for performing proofs of inequalities on expressions of real numbers.
- [Coq record update](https://github.com/tchajed/coq-record-update) - Library which provides a generic way to update Coq record fields.
- [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Extended alternative standard library for Coq.
- [ExtLib](https://github.com/coq-community/coq-ext-lib) - Collection of theories and plugins that may be useful in other Coq developments.
- [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) - Formalization of partial commutative monoids as used in verification of pointer-manipulating programs.
- [Flocq](https://gitlab.inria.fr/flocq/flocq) - Formalization of floating-point numbers and computations.
- [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) - Library of undecidable problems and reductions between them.
- [Hahn](https://github.com/vafeiadis/hahn) - Library for reasoning on lists and binary relations.
- [Interaction Trees](https://github.com/DeepSpec/InteractionTrees) - Library for representing recursive and impure programs.
- [LibHyps](https://github.com/Matafou/LibHyps) - Library of Ltac tactics to manage and manipulate hypotheses in proofs.
- [MathComp Extra](https://github.com/thery/mathcomp-extra) - Extra material for the Mathematical Components library, including the AKS primality test and RSA encryption and decryption.
- [Mczify](https://github.com/math-comp/mczify) - Library enabling Micromega arithmetic solvers to work when using Mathematical Components number definitions.
- [Metalib](https://github.com/plclub/metalib) - Library for programming language metatheory using locally nameless variable binding representations.
- [Paco](http://plv.mpi-sws.org/paco/) - Library for parameterized coinduction.
- [Regular Language Representations](https://github.com/coq-community/reglang) - Translations between different definitions of regular languages, including regular expressions and automata.
- [Relation Algebra](https://github.com/damien-pous/relation-algebra) - Modular formalization of algebras with heterogeneous binary relations as models.
- [Simple IO](https://github.com/Lysxia/coq-simple-io) - Input/output monad with user-definable primitive operations.
- [TLC](https://github.com/charguer/tlc) - Non-constructive alternative to Coq's standard library.

### Package and Build Management

- [coq_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - Build tool distributed with Coq and based on generating a makefile.
- [Coq Nix Toolbox](https://github.com/coq-community/coq-nix-toolbox) - Nix helper scripts to automate local builds and continuous integration for Coq.
- [Coq Package Index](https://coq.inria.fr/opam/www/) - Collection of Coq packages based on opam.
- [Coq Platform](https://github.com/coq/platform) - Curated collection of packages to support Coq use in industry, education, and research.
- [coq-community Templates](https://github.com/coq-community/templates) - Templates for generating configuration files for Coq projects.
- [Debian Coq packages](https://people.debian.org/~jpuydt/coq_platform.html) - Coq-related packages available in the testing distribution of Debian.
- [Docker-Coq](https://github.com/coq-community/docker-coq) - Docker images for many versions of Coq.
- [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) - Docker images for many combinations of versions of Coq and the Mathematical Components library.
- [Docker-Coq GitHub Action](https://github.com/marketplace/actions/docker-coq-action) - GitHub container action that can be used with Docker-Coq or Docker-MathComp.
- [Dune](https://dune.build) - Composable and opinionated build system for OCaml and Coq (former jbuilder).
- [Nix](https://nixos.org/nix/) - Package manager for Linux and other Unix systems, supporting atomic upgrades and rollbacks.
- [Nix Coq packages](https://search.nixos.org/packages?channel=unstable&query=coqPackages) - Collection of Coq-related packages for Nix.
- [opam](https://opam.ocaml.org) - Flexible and Git-friendly package manager for OCaml and Coq with multiple compiler support.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) - Tactics for rewriting universally quantified equations, modulo associativity and commutativity of some operator.
- [Coinduction](https://github.com/damien-pous/coinduction) - Plugin for doing proofs by enhanced coinduction.
- [Coq-Elpi](https://github.com/LPCIC/coq-elpi) - Extension framework based on λProlog providing an extensive API to implement commands and tactics.
- [CoqHammer](https://github.com/lukaszcz/coqhammer) - General-purpose automated reasoning hammer tool that combines learning from previous proofs with the translation of problems to automated provers and the reconstruction of found proofs.
- [Equations](https://github.com/mattam82/Coq-Equations) - Function definition package for Coq.
- [Gappa](https://gitlab.inria.fr/gappa/coq) - Tactic for discharging goals about floating-point arithmetic and round-off errors.
- [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder) - Collection of commands for declaring Coq hierarchies based on packed classes.
- [Itauto](https://gitlab.inria.fr/fbesson/itauto) - SMT-like tactics for combined propositional reasoning about function symbols, constructors, and arithmetic.
- [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - Experimental typed tactic language similar to Coq's classic Ltac language.
- [MetaCoq](https://github.com/MetaCoq/metacoq) - Project formalizing Coq in Coq and providing tools for manipulating Coq terms and developing certified plugins.
- [Mtac2](https://github.com/Mtac2/Mtac2) - Plugin adding typed tactics for backward reasoning.
- [Paramcoq](https://github.com/coq-community/paramcoq) - Plugin to generate parametricity translations of Coq terms.
- [QuickChick](https://github.com/QuickChick/QuickChick) - Plugin for randomized property-based testing.
- [SMTCoq](https://github.com/smtcoq/smtcoq) - Tool that checks proof witnesses coming from external SAT and SMT solvers.
- [Tactician](https://coq-tactician.github.io) - Interactive tool which learns from previously written tactic scripts across all the installed Coq packages and suggests the next tactic to be executed or tries to automate proof synthesis fully.
- [Unicoq](https://github.com/unicoq/unicoq) - Plugin that replaces the existing unification algorithm with an enhanced one.
- [Waterproof proof language](https://github.com/impermeable/coq-waterproof) - Plugin providing a language for writing proof scripts in a style that resembles non-mechanized mathematical proof.

### Puzzles and Games

- [Coqoban](https://github.com/coq-community/coqoban) - Coq implementation of Sokoban, the Japanese warehouse keepers' game.
- [Hanoi](https://github.com/thery/hanoi) - The Tower of Hanoi puzzle in Coq, including generalizations and theorems about configurations.
- [Mini-Rubik](https://github.com/thery/minirubik) - Coq formalization and solver of the 2x2x2 version of the Rubik's Cube puzzle.
- [Name the Biggest Number](https://github.com/codyroux/name-the-biggest-number) - Repository for submitting proven contenders for the title of biggest number in Coq.
- [Natural Number Game](https://github.com/uncomputable/natural-number-game) - Coq version of the natural number game developed for the Lean prover.
- [Sudoku](https://github.com/coq-community/sudoku) - Formalization and solver of the Sudoku number-placement puzzle in Coq.
- [T2048](https://github.com/thery/T2048) - Coq version of the 2048 sliding tile game.

### Tools

- [Alectryon](https://github.com/cpitclaudel/alectryon) - Collection of tools for writing technical documents that mix Coq code and prose.
- [Autosubst-ocaml](https://github.com/uds-psl/autosubst-ocaml) - Tool that generates Coq code for handling binders in syntax, such as for renaming and substitutions.
- [CFML](https://gitlab.inria.fr/charguer/cfml2) - Tool for proving properties of OCaml programs in separation logic.
- [coq2html](https://github.com/xavierleroy/coq2html) - Alternative HTML documentation generator for Coq.
- [coqdoc](https://coq.inria.fr/refman/using/tools/coqdoc.html) - Standard documentation tool that generates LaTeX or HTML files from Coq code.
- [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) - Tool for generating idiomatic Coq from OCaml code.
- [coq-dpdgraph](https://github.com/coq-community/coq-dpdgraph) - Tool for building dependency graphs between Coq objects.
- [coq-scripts](https://github.com/JasonGross/coq-scripts) - Scripts for dealing with Coq files, including tabulating proof times.
- [coq-tools](https://github.com/JasonGross/coq-tools) - Scripts for manipulating Coq developments.
  - [`find-bug.py`](https://github.com/JasonGross/coq-tools/blob/master/find-bug.py) - Automatically minimizes source files producing an error, creating small test cases for Coq bugs.
  - [`absolutize-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/absolutize-imports.py) - Processes source files to make loading of dependencies robust against shadowing of file names.
  - [`inline-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/inline-imports.py) - Creates stand-alone source files from developments by inlining the loading of all dependencies.
  - [`minimize-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/minimize-requires.py) - Removes loading of unused dependencies.
  - [`move-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/move-requires.py) - Moves all dependency loading statements to the top of source files.
  - [`move-vernaculars.py`](https://github.com/JasonGross/coq-tools/blob/master/move-vernaculars.py) - Lifts many vernacular commands and inner lemmas out of proof script blocks.
  - [`proof-using-helper.py`](https://github.com/JasonGross/coq-tools/blob/master/proof-using-helper.py) - Modifies source files to include proof annotations for faster parallel proving.
- [Cosette](https://github.com/uwdb/Cosette) - Automated solver for reasoning about SQL query equivalences.
- [hs-to-coq](https://github.com/plclub/hs-to-coq) - Converter from Haskell code to equivalent Coq code.
- [lngen](https://github.com/plclub/lngen) - Tool for generating locally nameless Coq definitions and proofs.
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - Parser generator that can output Coq code for verified parsers.
- [mCoq](https://github.com/EngineeringSoftware/mcoq) - Mutation analysis tool for Coq projects.
- [Ott](https://github.com/ott-lang/ott) - Tool for writing definitions of programming languages and calculi that can be translated to Coq.
- [PyCoq](https://github.com/ejgallego/pycoq) - Set of bindings and libraries for interacting with Coq from inside Python 3.
- [Roosterize](https://github.com/EngineeringSoftware/roosterize) - Tool for suggesting lemma names in Coq projects.
- [Sail](https://github.com/rems-project/sail) - Tool for specifying instruction set architecture (ISA) semantics of processors and generating Coq definitions.
- [SerAPI](https://github.com/ejgallego/coq-serapi) - Tools and OCaml library for (de)serialization of Coq code to and from JSON and S-expressions.
- [Trakt](https://github.com/ecranceMERCE/trakt) - Generic goal preprocessing tool for proof automation tactics.

### Type Theory and Mathematics

- [Analysis](https://github.com/math-comp/analysis) - Library for classical real analysis compatible with Mathematical Components.
- [Category Theory in Coq](https://github.com/jwiegley/category-theory) - Axiom-free formalization of category theory.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) - Soundness, completeness, and decidability for the logics K, K*, CTL, and PDL.
- [CoqPrime](https://github.com/thery/coqprime) - Library for certifying primality using Pocklington and Elliptic Curve certificates.
- [CoRN](https://github.com/coq-community/corn) - Library of constructive real analysis and algebra.
- [Coqtail Math](https://github.com/coq-community/coqtail-math) - Library of mathematical results ranging from arithmetic to real and complex analysis.
- [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - Formalization of classical real analysis compatible with the standard library and focusing on usability.
- [Finmap](https://github.com/math-comp/finmap) - Extension of Mathematical Components with finite maps, sets, and multisets.
- [Four Color Theorem](https://github.com/coq-community/fourcolor) - Formal proof of the Four Color Theorem, a landmark result of graph theory.
- [Gaia](https://github.com/coq-community/gaia) - Implementation of books from Bourbaki's Elements of Mathematics, including set theory and number theory.
- [GeoCoq](https://github.com/GeoCoq/GeoCoq) - Formalization of geometry based on Tarski's axiom system.
- [Graph Theory](https://github.com/coq-community/graph-theory) - Formalized graph theory results.
- [Homotopy Type Theory](https://github.com/HoTT/Coq-HoTT) - Development of homotopy-theoretic ideas.
- [Infotheo](https://github.com/affeldt-aist/infotheo) - Formalization of information theory and linear error-correcting codes.
- [Mathematical Components](http://math-comp.github.io) - Formalization of mathematical theories, focusing in particular on group theory.
- [Math Classes](https://github.com/coq-community/math-classes) - Abstract interfaces for mathematical structures based on type classes.
- [Monae](https://github.com/affeldt-aist/monae) - Monadic effects and equational reasoning.
- [Odd Order Theorem](https://github.com/math-comp/odd-order) - Formal proof of the Odd Order Theorem, a landmark result of finite group theory.
- [Puiseuxth](https://github.com/roglo/puiseuxth) - Proof of Puiseux's theorem and computation of roots of polynomials of Puiseux's series.
- [UniMath](https://github.com/UniMath/UniMath) - Library which aims to formalize a substantial body of mathematics using the univalent point of view.

### Verified Software

- [CompCert](http://compcert.inria.fr) - High-assurance compiler for almost all of the C language (ISO C99), generating efficient code for the PowerPC, ARM, RISC-V and x86 processors.
- [Ceramist](https://github.com/certichain/ceramist) - Verified hash-based approximate membership structures such as Bloom filters.
- [CertiCoq](https://github.com/CertiCoq/certicoq) - Verified compiler from Gallina, the internal language of Coq, down to CompCert's Clight language.
- [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) - Cryptographic primitive code generation.
- [Functional Algorithms Verified in SSReflect](https://github.com/clayrat/fav-ssr) - Purely functional verified implementations of algorithms for searching, sorting, and other fundamental problems.
- [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
- [Jasmin](https://github.com/jasmin-lang/jasmin) - Formalized language and verified compiler for high-assurance and high-speed cryptography.
- [JSCert](https://github.com/jscert/jscert) - Coq specification of ECMAScript 5 (JavaScript) with verified reference interpreter.
- [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Formal model of a Rust core language and type system, a logical relation for the type system, and safety proofs for some Rust libraries.
- [Prosa](https://gitlab.mpi-sws.org/RT-PROOFS/rt-proofs) - Definitions and proofs for real-time system schedulability analysis.
- [RISC-V Specification in Coq](https://github.com/mit-plv/riscv-coq) - Definition of the RISC-V processor instruction set architecture and extensions.
- [Stable sort algorithms in Coq](https://github.com/pi8027/stablesort) - Generic and modular proofs of correctness, including stability, of mergesort functions.
- [Tarjan and Kosaraju](https://github.com/math-comp/tarjan) - Verified implementations of algorithms for topological sorting and finding strongly connected components in finite graphs.
- [Vélus](http://velus.inria.fr) - Verified compiler for a Lustre/Scade-like dataflow synchronous language.
- [Verdi Raft](https://github.com/uwplse/verdi-raft) - Implementation of the Raft distributed consensus protocol, verified in Coq using the Verdi framework.
- [WasmCert-Coq](https://github.com/WasmCert/WasmCert-Coq/) - Formalization in Coq of the WebAssembly (aka Wasm) 1.0 specification.

## Resources

### Community

- [Official Coq website](https://coq.inria.fr)
- [Official Coq manual](https://coq.inria.fr/refman/)
- [Official Coq standard library](https://coq.inria.fr/stdlib/)
- [Official Coq Discourse forum](https://coq.discourse.group)
- [Official Coq Zulip chat](https://coq.zulipchat.com)
- [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
- [Official Coq wiki](https://github.com/coq/coq/wiki)
- [Official Coq X/Twitter](https://x.com/CoqLang)
- [Coq Zulip chat archive](https://coq.gitlab.io/zulip-archive/)
- [Coq subreddit](https://www.reddit.com/r/Coq/)
- [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
- [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
- [Coq tag on Proof Assistants Stack Exchange](https://proofassistants.stackexchange.com/questions/tagged/coq)
- [Coq keyword on Zenodo](https://zenodo.org/search?q=keywords%3A%22Coq%22)
- [Coq-community package maintenance project](https://github.com/coq-community/manifesto)
- [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki)
- [100 famous theorems proved using Coq](https://github.com/coq-community/coq-100-theorems)
- [Planet Coq link aggregator](https://coq.pl-a.net)

### Blogs

- [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
- [Gagallium](http://gallium.inria.fr/blog)
- [Gregory Malecha's blog](https://gmalecha.github.io)
- [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
- [Lysxia's blog](https://blog.poisson.chat)
- [MIT PLV blog posts on Coq](http://plv.csail.mit.edu/blog/category/coq.html)
- [PLClub Blog](https://www.seas.upenn.edu/~plclub/blog/)
- [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
- [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
- [Thomas Letan's blog posts on Coq](https://soap.coffee/~lthms/tags/coq.html)

### Books

- [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - The first book dedicated to Coq.
- [Software Foundations](https://softwarefoundations.cis.upenn.edu) - Series of Coq-based textbooks on logic, functional programming, and foundations of programming languages, aimed at being accessible to beginners.
  - [Volume 1: Logical Foundations](https://softwarefoundations.cis.upenn.edu/lf-current/index.html) - Introduction to functional programming, basic concepts of logic, and computer-assisted theorem proving.
  - [Volume 2: Programming Language Foundations](https://softwarefoundations.cis.upenn.edu/plf-current/index.html) - Introduction to the theory of programming languages, including operational semantics, Hoare logic, and static type systems.
  - [Volume 3: Verified Functional Algorithms](https://softwarefoundations.cis.upenn.edu/vfa-current/index.html) - Demonstration of how a variety of fundamental data structures can be specified and verified.
  - [Volume 4: QuickChick](https://softwarefoundations.cis.upenn.edu/qc-current/index.html) - Introduction to tools for combining randomized property-based testing with formal specification and proof.
  - [Volume 5: Verifiable C](https://softwarefoundations.cis.upenn.edu/vc-current/index.html) - An extended tutorial on specifying and verifying C programs using the Verified Software Toolchain.
  - [Volume 6: Separation Logic Foundations](https://softwarefoundations.cis.upenn.edu/slf-current/index.html) - An introduction to separation logic and how to build program verification tools on top of it.
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - Textbook about practical engineering with Coq which teaches advanced practical tricks and a very specific style of proof.
- [Program Logics for Certified Compilers](https://www.cs.princeton.edu/~appel/papers/plcc.pdf) - Book that explains how to construct program logics using separation logic, accompanied by a formal model in Coq which is applied to the Clight programming language and other examples.
- [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - Book that simultaneously provides a general introduction to formal logical reasoning about the correctness of programs and to using Coq for this purpose.
- [Programs and Proofs](https://ilyasergey.net/pnp/) - Book that gives a brief and practically-oriented introduction to interactive proofs in Coq which emphasizes the computational nature of inductive reasoning about decidable propositions via a small set of primitives from the SSReflect proof language.
- [Computer Arithmetic and Formal Proofs](https://www.sciencedirect.com/book/9781785481123/computer-arithmetic-and-formal-proofs) - Book that describes how to formally specify and verify floating-point algorithms in Coq using the Flocq library.
- [The Mathematical Components book](https://math-comp.github.io/mcb/) - Book oriented towards mathematically inclined users, focusing on the Mathematical Components library and the SSReflect proof language.
- [Modeling and Proving in Computational Type Theory](https://github.com/uds-psl/MPCTT) - Book covering topics in computational logic using Coq, including foundations, canonical case studies, and practical programming.
- [Hydras & Co.](https://github.com/coq-community/hydra-battles) - Continuously in-progress book and library on Kirby and Paris' hydra battles and other entertaining formalized mathematics in Coq, including a proof of the Gödel-Rosser first incompleteness theorem.

### Course Material

- [An Introduction to MathComp-Analysis](https://staff.aist.go.jp/reynald.affeldt/documents/karate-coq.pdf) - Lecture notes on getting started with the Mathematical Components library and using it for classical reasoning and real analysis.
- [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) - Introduction to using separation logic to reason about sequential imperative programs in Coq.
- [Floating-Point Numbers and Formal Proof](https://github.com/thery/FlocqLecture) - Introductory course on Coq real numbers and floating-point numbers from the Flocq library.
- [Introduction to the Theory of Computation](https://gitlab.com/umb-svl/turing) - Formalization to support an undergraduate course on the theory of computation, including languages and Turing machines.
- [Lectures on Software Foundations](https://github.com/clarksmr/sf-lectures) - Material on the Software Foundations series of textbooks, including a series of YouTube videos.
- [MathComp School](https://github.com/gares/math-comp-school-2022) - Coq sources for lessons and exercises that introduce the SSReflect proof language and the Mathematical Components library.
- [Mechanized Semantics](https://github.com/xavierleroy/cdf-mech-sem) - Companion Coq sources for a course on programming language semantics at Collège de France.
- [Program Logics](https://github.com/xavierleroy/cdf-program-logics) - Companion Coq sources for a course on program logics at Collège de France.
- [Program verification with types and logic](https://gitlab.science.ru.nl/program-verification/course-2023-2024) - Lectures and exercise material for a course in programming language semantics, type systems and program logics, using Coq, at Radboud University Nijmegen.
- [Proofs and Reliable Programming using Coq](https://team.inria.fr/stamp/proofs-and-reliable-programming-using-coq-2022/) - Introduction to developing and verifying programs with Coq.

### Tutorials and Hints

- [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) - Coq code and exercises from the Coq'Art book, including additional tutorials.
- [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - Introduction to how Coq can be used to define logical concepts and functions and reason about them.
- [Coq requirements in Common Criteria evaluations](https://inria.hal.science/hal-04452421) - Guide on how to write readable and reviewable Coq code in high assurance applications.
- [Coq Tactics in Plain English](https://charlesaverill.github.io/ctpe/) - Guide to Coq tactics with explanations and examples.
- [Learn X in Y minutes where X=Coq](https://learnxinyminutes.com/docs/coq/) - Whirlwind tour of Coq as a language.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - Demonstration of design patterns for programming and proving with canonical structures.
- [MathComp Tutorial Materials](https://github.com/math-comp/tutorial_material) - Source code for Mathematical Components tutorials.
- [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - Basics of using Coq to write formal proofs.
- [Tricks in Coq](https://github.com/coq-community/coq-tricks) - Tips, tricks, and features in Coq that are hard to discover.
