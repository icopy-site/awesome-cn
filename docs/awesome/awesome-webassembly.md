<div class="github-widget" data-repo="idematos/awesome-webassembly"></div>
## Awesome WebAssembly [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
<a href="https://webassembly.org/"><img src="https://raw.githubusercontent.com/idematos/awesome-webassembly/master/media/wasm-logo.png" alt="Wasm Logo" align="right" style="height: 120px; width: 120px"></a>
A curation of WebAssembly resources, projects, and communities. 
> [WebAssembly](https://webassembly.org/) (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine. Wasm is designed as a portable compilation target for programming languages, enabling deployment on the web for client and server applications.



## Resources

### Basics

- [WebAssembly MDN](https://developer.mozilla.org/en-US/docs/WebAssembly)
- [WebAssembly Specification](https://webassembly.github.io/spec/)

### Articles

- [What is WebAssembly?](https://medium.com/javascript-scene/what-is-webassembly-the-dawn-of-a-new-era-61256ec5a8f6) - Eric Elliott, 2015.
- [7 Things You Should Know About WebAssembly](https://auth0.com/blog/7-things-you-should-know-about-web-assembly/) - Sebastian Peyrott, 2015.
- [WebAssembly Demystified](https://floooh.github.io/2017/06/09/webassembly-demystified.html) - Andre Weissflog, 2017.
- [Why WebAssembly?](https://medium.com/dfinity/why-webassembly-f21967076e4) - Andreas Rossberg, 2018.
- [The world's easiest introduction to WebAssembly](https://medium.com/free-code-camp/webassembly-with-golang-is-fun-b243c0e34f02) - Martin Olsansky, 2019.
- [The Future of Programming: WebAssembly & Life After JavaScript](https://www.sitepoint.com/future-programming-webassembly-life-after-javascript/) - Eric Elliott, 2024.
- [The Web Assembles](https://blog.scottlogic.com/ceberhardt/assets/white-papers/the-web-assembles.pdf) - Chris Price and Colin Eberhardt, 2017.
- [An Empirical Study of Real-World WebAssembly Binaries](https://dlehmann.eu/publications/WasmBench-www2021.pdf) - Aaron Hilbig, Daniel Lehmann, and Michael Pradel, 2021.
- [Not So Fast: Analyzing the Performance of WebAssembly vs. Native Code](https://www.usenix.org/system/files/atc19-jangda.pdf) - Abhinav Jangda, Bobby Powers, Emery D. Berger, and Arjun Guha, 2019.
- [Provably-Safe Multilingual Software Sandboxing using WebAssembly](https://www.usenix.org/system/files/sec22-bosamiya.pdf) - Jay Bosamiya, Wen Shih Lim, and Bryan Parno, 2022.
- [Wasabi: A Framework for Dynamically Analyzing WebAssembly](https://software-lab.org/publications/asplos2019_Wasabi.pdf) - Daniel Lehmann and Michael Pradel, 2019.
- [Bringing the Web up to Speed with WebAssembly](https://github.com/WebAssembly/spec/blob/main/papers/pldi2017.pdf) - Andreas Haas, Andreas Rossberg, Derek L. Schuff, Ben L. Titzer, Michael Holman, Dan Gohman, Luke Wagner, Alon Zakai, JF Bastien, 2017.

### Books

- [Rust and WebAssembly](https://rustwasm.github.io/docs/book/) - Open-source book describing how to use Rust and WebAssembly together.
- [Programming WebAssembly with Rust](https://pragprog.com/titles/khrust/programming-webassembly-with-rust/) - Kevin Hoffman, 2019.
- [The Art of WebAssembly](https://nostarch.com/art-webassembly) - Rick Battagline, 2021.

### Videos

- [WebAssembly](https://www.youtube.com/watch?v=NhAPPQqKCi8) - Nick Bray, 2015.
- [What is WebAssembly?](https://www.youtube.com/watch?v=HktWin_LPf4) - Lin Clark, 2017.
- [Get Going with WebAssembly](https://www.youtube.com/watch?v=iTrx0BbUXI4) - Johan Brandhorst, 2018.
- [WebAssembly and the Death of JavaScript](https://www.youtube.com/watch?v=pBYqen3B2gc) - Colin Eberhardt, 2018.

## Projects

### Compilers

- [Emscripten](https://emscripten.org/) - Compile C and C++ to WebAssembly.
- [AssemblyScript](https://www.assemblyscript.org/) - TypeScript-like language compiled to WebAssembly.
- [Binaryen](https://github.com/WebAssembly/binaryen) - Compiler infrastructure for WebAssembly.
- [TinyGo](https://tinygo.org/) - Go compiler for WebAssembly.

### Runtimes

- [Wasmtime](https://wasmtime.dev/) - Standalone WebAssembly runtime.
- [WasmEdge](https://github.com/WasmEdge/WasmEdge) - High-performance WebAssembly runtime.
- [WAVM](https://github.com/WAVM/WAVM) - WebAssembly virtual machine.
- [Wasm3](https://github.com/wasm3/wasm3) - Small, fast WebAssembly interpreter.
- [Wasmer](https://wasmer.io/) - WebAssembly runtime for desktop, cloud, and edge.

### Libraries

- [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) - Interoperability between Rust and JavaScript.
- [wasmer-js](https://github.com/wasmerio/wasmer-js) - WebAssembly runtime for JavaScript.
- [wasm-pack](https://github.com/rustwasm/wasm-pack) - Build, test, and publish Rust-generated Wasm.
- [Wabt](https://github.com/WebAssembly/wabt) - WebAssembly binary tolkit.
- [WASI](https://github.com/WebAssembly/WASI) - WebAssembly system interface.

### Tools

- [Wasm Explorer](https://mbebenita.github.io/WasmExplorer/) - Visualize and debug WebAssembly binaries.
- [wasm2c](https://github.com/WebAssembly/wabt/tree/main/wasm2c) - Convert WebAssembly binaries to C.
- [Cross-Origin Isolation Checker](https://app.cinevva.com/tools/cross-origin-isolation-checker) - Check whether a page is cross-origin isolated (COOP/COEP), the requirement for SharedArrayBuffer and multithreaded WebAssembly.

### Frameworks

- [Blazor](https://blazor.net/) - .NET web framework running on WebAssembly.
- [Yew](https://yew.rs/) - Rust framework for building web applications using WebAssembly.
- [Leptos](https://github.com/leptos-rs/leptos) - Full-stack Rust framework for WebAssembly web apps.

## Communities

- [WebAssembly GitHub Organization](https://github.com/WebAssembly)
- [W3C WebAssembly Group](https://www.w3.org/wasm/)
- [WebAssembly Subreddit](https://www.reddit.com/r/webassembly/)


## Contributing

Contributions are welcome. Please read the [contribution guidelines](https://github.com/idematos/awesome-webassembly/blob/main/contributing.md) before submitting your changes.
