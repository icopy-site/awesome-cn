<div class="github-widget" data-repo="pest-parser/awesome-pest"></div>
## Awesome Pest. The Elegant Parser [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://avatars.githubusercontent.com/u/26044607" align="right" width="100">](https://raw.githubusercontent.com/pest-parser/pest/)

> A curated list of resources, projects, and tools using or for the pest parser generator in Rust

pest is a general purpose parser written in Rust with a focus on accessibility, correctness, and performance. It uses parsing expression grammars (or [PEG](https://en.wikipedia.org/wiki/Parsing_expression_grammar)) as input, which are similar in spirit to regular expressions, but which offer the enhanced expressivity needed to parse complex languages.

Contributions welcome! Read the [contribution guidelines](https://github.com/pest-parser/awesome-pest/blob/master/contributing.md) first.



## Resources

- [Book](https://pest.rs/book) - The recommended way to start parsing with pest is to read this official book.
- [API reference on docs.rs](https://docs.rs/pest)
- [fiddle editor on pest.rs](https://pest.rs/#editor) - Play with grammars and share them on the official website (and format them!).
- [Gitter](https://gitter.im/pest-parser/pest)
- [Discord](https://discord.gg/XEGACtWpT2)
- [GitHub Discussions](https://github.com/pest-parser/pest/discussions)

## Projects

Here are some example projects using pest:

- [pest_meta](https://github.com/pest-parser/pest/blob/master/meta/src/grammar.pest) - The pest itself is bootstrapped using pest.
- [AshPaper](https://github.com/shnewto/ashpaper) - Rust Inpterpreter for Esopo language AshPaper conceived by William Hicks.
- [cicada](https://github.com/mitnk/cicada) - An old-school bash-like Unix shell written in Rust.
- [comrak](https://github.com/kivikakk/comrak) - CommonMark + GFM compatible Markdown parser and renderer.
- [elastic-rs](https://github.com/cch123/elastic-rs) - Convert bool expressions to Elasticsearch DSL in Rust.
- [handlebars-rust](https://github.com/sunng87/handlebars-rust) - Rust templating with Handlebars.
- [hexdino](https://github.com/Luz/hexdino) - A hex editor with vim like keybindings written in Rust.
- [insta](https://github.com/mitsuhiko/insta) - A snapshot testing library for rust.
- [jql](https://github.com/yamafaktory/jql) - A JSON Query Language CLI tool.
- [json5-rs](https://github.com/callum-oakley/json5-rs) - A Rust JSON5 serializer and deserializer which speaks Serde.
- [mt940](https://github.com/svenstaro/mt940-rs) - A MT940 parser in Rust.
- [py_literal](https://github.com/jturner314/py_literal) - Rust crate for parsing/formatting Python literals.
- [rouler](https://github.com/jarcane/rouler) - An easy to use dice rolling library for Rust.
- [RuSh](https://github.com/lwandrebeck/RuSh) - RuSh aims to be a bash compatible shell with candies, written in Rust.
- [rs_pbrt](https://github.com/wahn/rs_pbrt) - Rust crate to implement a counterpart to the PBRT book's (3rd edition) C++ code.
- [stache](https://github.com/dgraham/stache) - A Mustache template compiler.
- [tera](https://github.com/Keats/tera) - A template engine for Rust based on Jinja2/Django.
- [ZoKrates](https://github.com/ZoKrates/ZoKrates) - A toolbox for zkSNARKs on Ethereum.
- [Vector](https://github.com/timberio/vector) - A high-performance observability data pipeline.
- [AutoCorrect](https://github.com/huacnlee/autocorrect) - A linter and formatter to help you to improve copywriting, correct spaces, words, and punctuations between CJK (Chinese, Japanese, Korean).
- [yaml-peg](https://github.com/aofdev/yaml-peg) - PEG parser for YAML written in Rust.
- [qubit](https://github.com/abhimanyu003/qubit) - A handy calculator, based on Rust and WebAssembly.
- [caith](https://github.com/Geobert/caith) - A dice roller crate.
- [Melody](https://github.com/yoav-lavi/melody) - Melody is a language that compiles to regular expressions and aims to be more easily readable and maintainable.
- [PTA-Parser](https://github.com/AltaModaTech/pta-parser/) - A Plain Text Accounting parser built in Rust for [Beancount](https://github.com/beancount/beancount), [Ledger](https://github.com/ledger/ledger), and other PTA formats.

## Tooling

### IDE Support

- [pest IDE tools](https://github.com/pest-parser/pest-ide-tools) - A main repository with LSP server and VSCode extension.
- [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=pest.pest-ide-tools)
- [IntelliJ IDEA Plugin](https://plugins.jetbrains.com/plugin/12046-pest)
- [pest.vim](https://github.com/pest-parser/pest.vim)
- [pest-fmt](https://github.com/pest-parser/pest-fmt) - It can help to format
pest grammars.
- [pest web debugger](https://github.com/tomtau/pest-web-debug) - Try it [online](https://tomtau.github.io/pest-web-debug/).

### Boilerplate reduction and testing

- [pest-ast](https://github.com/pest-parser/ast) - It can help to reduce boilerplate when converting pest parse trees to abstract syntax trees.
- [pest_consume](https://crates.io/crates/pest_consume) - This crate can help with the parse tree traversing boilerplate.
- [pest-test](https://crates.io/crates/pest-test) - It is a testing framework for pest grammars.


### CLI Debugger

- [pest_debugger](https://docs.rs/pest_debugger/latest/pest_debugger/) - It is a crate for debugging pest grammars. It can be used as a CLI tool or as a library. [See instructions for using the CLI debugger](https://github.com/pest-parser/awesome-pest/blob/master/debugger.md).
