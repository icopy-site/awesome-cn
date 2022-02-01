<div class="github-widget" data-repo="rockerBOO/awesome-neovim"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!-- lint ignore awesome-git-repo-age -->

<img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" />

## Awesome Neovim [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- Uncomment the awesome badge when the repository is added to awesome main list.
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
-->

 &gt; 很棒的 Neovim 插件集合. 主要针对 Neovim 的特定功能.

[Neovim](https://neovim.io/) is a Vim-based text editor engineered for extensibility and usability, to encourage new applications and contributions.



## Wishlist

Have a problem a plugin can solve? Add it to the [nvim-lua wishlist](https://github.com/nvim-lua/wishlist).

## UI

Neovim supports a wide variety of UI's.

- [CosmicNvim/cosmic-ui](https://github.com/CosmicNvim/cosmic-ui)  - Cosmic-UI 是对特定 vim 功能的简单封装. 旨在提供一种快速简便的方法来使用 Neovim 创建 Cosmic UI 体验！
- [yatli/fvim](https://github.com/yatli/fvim) - Cross platform Neovim front-end UI, built with F# + Avalonia.
- [smolck/uivonim](https://github.com/smolck/uivonim) - 目标：利用最新 Neovim 功能的功能丰富的跨平台 GUI.
- [qvacua/vimr](https://github.com/qvacua/vimr) - Swift 中用于 macOS 的 Neovim GUI.
- [vhakulinen/gnvim](https://github.com/vhakulinen/gnvim) - Neovim 的 GUI，没有任何网络膨胀.
- [Kethku/neovide](https://github.com/Kethku/neovide) - Rust 中没有废话 Neovim 客户端.
- [beeender/glrnvim](https://github.com/beeender/glrnvim) - A terminal wrapper that launches Neovim inside of alacritty.
- [akiyosi/goneovim](https://github.com/akiyosi/goneovim) - Neovim GUI written in Golang, using a Golang qt backend.
- [DinVim](http://dinvim.com/) - DinVim for macOS 是一个安全可靠的工作 macOS 沙箱环境，为 Vim 用户提供真正的 macOS 体验.
- [RMichelsen/Nvy](https://github.com/RMichelsen/Nvy) - C++ 中的 Neovim 客户端.
- [asvetliakov/vscode-neovim](https://github.com/asvetliakov/vscode-neovim) - Neovim integration for Visual Studio Code.
- [equalsraf/neovim-qt](https://github.com/equalsraf/neovim-qt) - Neovim client library and GUI, in Qt5.
- [lunixbochs/actualvim](https://github.com/lunixbochs/actualvim) - Sublime Text 3 input mode using Neovim.
- [vv-vim/vv](https://github.com/vv-vim/vv)  - 适用于 macOS 的 Neovim 客户端. 具有良好 macOS 集成的纯粹、快速、简约的 Vim 体验. 针对速度和漂亮的字体渲染进行了优化.
- [jebberjeb/javafx-neovimpane](https://github.com/jebberjeb/javafx-neovimpane) - 由 Neovim 支持的 JavaFX 文本窗格，使用 Clojure 创建.
- [rohit-px2/nvui](https://github.com/rohit-px2/nvui) - Neovim 的现代前端.
- [Lyude/neovim-gtk](https://github.com/Lyude/neovim-gtk) - 一个用 Rust 编写的 GTK3+ 客户端，与原始 vim-gtk3 非常相似，支持连字.

## Plugin

### Plugin Manager

- [wbthomason/packer.nvim](https://github.com/wbthomason/packer.nvim) - A use-package inspired plugin manager for Neovim. Uses native packages, supports Luarocks dependencies, written in Lua, allows for expressive config.
- [savq/paq-nvim](https://github.com/savq/paq-nvim) - 用 Lua 编写的 Neovim 包管理器.
- [NTBBloodbath/cheovim](https://github.com/NTBBloodbath/cheovim) - Neovim configuration switcher written in Lua. Inspired by chemacs.

### LSP

#### (requires Neovim 0.5)

- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the Neovim LSP client.
- [nvim-lua/lsp-status.nvim](https://github.com/nvim-lua/lsp-status.nvim) - This is a Neovim plugin/library for generating statusline components from the built-in LSP client.
- [nvim-lua/lsp_extensions.nvim](https://github.com/nvim-lua/lsp_extensions.nvim) - Repo to hold a bunch of info & extension callbacks for built-in LSP.
- [RishabhRD/nvim-lsputils](https://github.com/RishabhRD/nvim-lsputils) - nvim-lsp 操作的更好的默认值.
- [tami5/lspsaga.nvim](https://github.com/tami5/lspsaga.nvim) - 基于 Neovim 内置 lsp 的轻量级 lsp 插件，具有高性能 UI.
- [onsails/diaglist.nvim](https://github.com/onsails/diaglist.nvim) - quickfix 中的实时渲染工作区诊断，loclist 中的缓冲区诊断.
- [folke/trouble.nvim](https://github.com/folke/trouble.nvim) - 一个漂亮的诊断列表，可帮助您解决代码造成的所有问题.
- [folke/lsp-colors.nvim](https://github.com/folke/lsp-colors.nvim) - A plugin that adds missing LSP diagnostics highlight groups for color schemes that don't yet support the builtin LSP client.
- [kosayoda/nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb) - 只要在当前光标位置有 `textDocument/codeAction` 可用，插件就会在符号列中显示一个灯泡.
- [onsails/lspkind-nvim](https://github.com/onsails/lspkind-nvim) - The plugin adds vscode-like icons to Neovim lsp completions.
- [ojroques/nvim-lspfuzzy](https://github.com/ojroques/nvim-lspfuzzy) - 一个让 LSP 客户端使用 FZF 的小插件.
- [gfanto/fzf-lsp.nvim](https://github.com/gfanto/fzf-lsp.nvim) - 为 lsp 内置的 Neovim 启用 fzf 模糊搜索的功能.
- [ray-x/lsp_signature.nvim](https://github.com/ray-x/lsp_signature.nvim) - 键入时的 Lsp 签名提示.
- [rmagatti/goto-preview](https://github.com/rmagatti/goto-preview) - 在浮动窗口中预览本地 LSP 的 goto 定义调用.
- [nanotee/sqls.nvim](https://github.com/nanotee/sqls.nvim) - Neovim 的 Sqls（sql 数据库连接插件 + LSP 客户端）插件.
- [jubnzv/virtual-types.nvim](https://github.com/jubnzv/virtual-types.nvim) - Neovim 插件，将类型注释显示为虚拟文本.
- [jose-elias-alvarez/nvim-lsp-ts-utils](https://github.com/jose-elias-alvarez/nvim-lsp-ts-utils) - 用于改进 Neovim 内置 LSP 客户端的 TypeScript 开发体验的实用程序.
- [ray-x/navigator.lua](https://github.com/ray-x/navigator.lua) - Learn existing code quickly and navigate code like a breeze. A swiss army knife makes exploring LSP and 🌲Treesitter symbols a piece of 🍰.
- [liuchengxu/vista.vim](https://github.com/liuchengxu/vista.vim) - 在当前文件的窗口中列出所有函数和变量.
- [simrat39/symbols-outline.nvim](https://github.com/simrat39/symbols-outline.nvim) - A tree like view for symbols in Neovim using the Language Server Protocol. Supports all your favourite languages.
- [tamago324/nlsp-settings.nvim](https://github.com/tamago324/nlsp-settings.nvim) - 使用 JSON 文件设置 Neovim LSP 的插件.
- [simrat39/rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - 使用 Neovim 的内置 LSP 更好地开发 rust 的工具.
- [stevearc/aerial.nvim](https://github.com/stevearc/aerial.nvim) - 用于浏览和快速导航的代码大纲窗口.
- [jose-elias-alvarez/null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim) - 使用 Neovim 作为语言服务器，通过 Lua 注入 LSP 诊断、代码操作等.
- [jakewvincent/texmagic.nvim](https://github.com/jakewvincent/texmagic.nvim) - 通过定义任意数量的自定义 LaTeX 构建引擎并使用魔术注释选择它们来增强 Texlab 的 lspconfig 设置.
- [nanotee/nvim-lsp-basics](https://github.com/nanotee/nvim-lsp-basics) - Basic wrappers for LSP features.
- [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu) - A floating pop-up menu for code actions to show code action information and a diff preview.
- [mfussenegger/nvim-lint](https://github.com/mfussenegger/nvim-lint) - Neovim (&gt;= 0.5) 的异步 linter 插件补充内置的语言服务器协议支持.
- [b0o/SchemaStore.nvim](https://github.com/b0o/SchemaStore.nvim) - A Neovim Lua plugin providing access to the [SchemaStore](https://github.com/SchemaStore/schemastore) 目录.
- [ldelossa/litee.nvim](https://github.com/ldelossa/litee.nvim) - Neovim 缺少的 IDE 功能.

##### LSP Installer

- [anott03/nvim-lspinstall](https://github.com/anott03/nvim-lspinstall) - 易于安装语言服务器.
- [alexaandru/nvim-lspupdate](https://github.com/alexaandru/nvim-lspupdate) - 更新安装（或自动安装，如果缺少）LSP 服务器.
- [williamboman/nvim-lsp-installer](https://github.com/williamboman/nvim-lsp-installer) - 轻松安装超过 50 台 LSP 服务器 - 完全支持 Windows.

### Completion

- [ms-jpq/coq_nvim](https://github.com/ms-jpq/coq_nvim)  - 快到他妈的 Neovim 完成.  SQLite，并发调度器，数百小时的优化.
- [jameshiew/nvim-magic](https://github.com/jameshiew/nvim-magic) - 集成 AI 代码辅助的框架.
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp) - A completion plugin for Neovim written in Lua. New version of nvim-compe.
  - [hrsh7th/cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) - A nvim-cmp source for Neovim builtin LSP client.
  - [saadparwaiz1/cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip) - 用于 luasnip 完成的 nvim-cmp 源.
  - [quangnguyen30192/cmp-nvim-ultisnips](https://github.com/quangnguyen30192/cmp-nvim-ultisnips) - UltiSnips 的 nvim-cmp 源.
  - [hrsh7th/cmp-path](https://github.com/hrsh7th/cmp-path) - 文件系统路径的 nvim-cmp 源.
  - [petertriho/cmp-git](https://github.com/petertriho/cmp-git) - A nvim-cmp source for Git.
  - [hrsh7th/cmp-buffer](https://github.com/hrsh7th/cmp-buffer) - 用于缓冲字的 nvim-cmp 源.
  - [tzachar/cmp-tabnine](https://github.com/tzachar/cmp-tabnine) - TabNine 的 nvim-cmp 源.
  - [hrsh7th/cmp-nvim-lua](https://github.com/hrsh7th/cmp-nvim-lua) - A nvim-cmp source for the Neovim Lua API.
  - [lukas-reineke/cmp-rg](https://github.com/lukas-reineke/cmp-rg) - Ripgrep 的 nvim-cmp 源.
  - [f3fora/cmp-spell](https://github.com/f3fora/cmp-spell) - vim 的法术建议的 nvim-cmp 源.
  - [andersevenrud/compe-tmux](https://github.com/andersevenrud/compe-tmux) - Tmux 的 nvim-cmp 源.
  - [David-Kunz/cmp-npm](https://github.com/David-Kunz/cmp-npm) - A nvim-cmp source for NPM.
  - [lukas-reineke/cmp-under-comparator](https://github.com/lukas-reineke/cmp-under-comparator) - A nvim-cmp function for better sorting.
  <!--lint ignore double-link-->
- [mini.completion](https://github.com/echasnovski/mini.nvim#minicompletion) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于异步两阶段完成. 支持显示完成项信息和独立函数签名.

### Markdown

- [ellisonleao/glow.nvim](https://github.com/ellisonleao/glow.nvim) - 使用发光的 Markdown 预览.
- [davidgranstrom/nvim-markdown-preview](https://github.com/davidgranstrom/nvim-markdown-preview) - Markdown preview in the browser using pandoc and live-server through Neovim's job-control API.
- [jghauser/auto-pandoc.nvim](https://github.com/jghauser/auto-pandoc.nvim) - Easy pandoc conversion leveraging yaml blocks.
- [jghauser/follow-md-links.nvim](https://github.com/jghauser/follow-md-links.nvim) - 按回车键跟随内部降价链接.
- [jakewvincent/mkdnflow.nvim](https://github.com/jakewvincent/mkdnflow.nvim) - Markdown 笔记本导航（跟踪内部和外部 Markdown 链接、创建链接、跳转到链接等）
- [jubnzv/mdeval.nvim](https://github.com/jubnzv/mdeval.nvim) - A Neovim plugin that evaluates code blocks inside markdown documents.
- [mjlbach/babelfish.nvim](https://github.com/mjlbach/babelfish.nvim) - A Neovim plugin to convert Markdown to vimdoc using Treesitter.
- [kdheepak/panvimdoc](https://github.com/kdheepak/panvimdoc) - A pandoc to vimdoc GitHub action.

### Syntax

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Treesitter configurations and abstraction layer.
- [nvim-treesitter/nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - Create your own textobjects using tree-sitter queries.
- [RRethy/nvim-treesitter-textsubjects](https://github.com/RRethy/nvim-treesitter-textsubjects) - Location and syntax aware text objects which _do what you mean_.
- [blackCauldron7/surround.nvim](https://github.com/blackCauldron7/surround.nvim) - 用 Lua 编写的 Neovim 环绕文本对象插件.
<!--lint ignore double-link-->
- [mini.surround](https://github.com/echasnovski/mini.nvim#minisurround) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于处理文本环境（添加、删除、替换、查找、突出显示）. 完全支持点重复.

### Terminal integration

- [LoricAndre/OneTerm.nvim](https://github.com/LoricAndre/OneTerm.nvim) - 用于在终端中运行命令的插件框架.
- [nikvdp/neomux](https://github.com/nikvdp/neomux) - Control Neovim from shells running inside Neovim.
- [akinsho/nvim-toggleterm.lua](https://github.com/akinsho/nvim-toggleterm.lua) - Neovim Lua 插件，帮助轻松管理多个终端窗口.
- [norcalli/nvim-terminal.lua](https://github.com/norcalli/nvim-terminal.lua) - Neovim 的高性能文件类型模式，利用正确的颜色代码隐藏和突出显示缓冲区.
- [numToStr/FTerm.nvim](https://github.com/numToStr/FTerm.nvim) - 没有用 Lua 编写的废话浮动终端.
- [oberblastmeister/termwrapper.nvim](https://github.com/oberblastmeister/termwrapper.nvim) - Neovim 终端功能的包装器，使它们更加用户友好.
- [pianocomposer321/consolation.nvim](https://github.com/pianocomposer321/consolation.nvim) - A general-purpose terminal wrapper and management plugin for Neovim, written in Lua.
- [jghauser/kitty-runner.nvim](https://github.com/jghauser/kitty-runner.nvim)  - 穷人的REPL. 轻松将缓冲线和命令发送到 kitty 终端.
- [jlesquembre/nterm.nvim](https://github.com/jlesquembre/nterm.nvim) - A Neovim plugin to interact with the terminal, with notifications.
- [s1n7ax/nvim-terminal](https://github.com/s1n7ax/nvim-terminal) - 一个简单易用的多终端插件.

### Snippet

- [norcalli/snippets.nvim](https://github.com/norcalli/snippets.nvim) - Snippets in Lua.
- [hrsh7th/vim-vsnip](https://github.com/hrsh7th/vim-vsnip) - Snippet plugin for vim/nvim that supports LSP/VSCode's snippet format.
- [rafamadriz/friendly-snippets](https://github.com/rafamadriz/friendly-snippets) - Snippets collection for all kind of programming languages that integrates really well with vim-vsnip.
- [L3MON4D3/LuaSnip](https://github.com/L3MON4D3/LuaSnip) - A snippet engine for Neovim written in Lua.
- [dcampos/nvim-snippy](https://github.com/dcampos/nvim-snippy) - Snippet plugin written in Lua with support for [vim-snippets](https://github.com/honza/vim-snippets).

### Register

- [gennaro-tedesco/nvim-peekup](https://github.com/gennaro-tedesco/nvim-peekup) - 与 vim 寄存器动态交互.
- [tversteeg/registers.nvim](https://github.com/tversteeg/registers.nvim) - vim 寄存器的非侵入式最小预览.
- [acksld/nvim-neoclip.lua](https://github.com/AckslD/nvim-neoclip.lua) - 带有望远镜集成的剪贴板管理器 Neovim 插件.

### Marks

- [chentau/marks.nvim](https://github.com/chentau/marks.nvim) - 查看和与 vim 标记交互的更好的用户体验.

### Fuzzy Finder

- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim is a highly [extendable](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) fuzzy finder over lists. Built on the latest awesome features from Neovim core. Telescope is centered around modularity, allowing for easy customization.
- [vijaymarupudi/nvim-fzf](https://github.com/vijaymarupudi/nvim-fzf)  - 在 `Neovim` (&gt;= 0.5) 中使用 fzf 的 Lua API. 允许 UI 速度和可用性的完全异步.
- [amirrezaask/fuzzy.nvim](https://github.com/amirrezaask/fuzzy.nvim) - Fuzzy.nvim 提供了一个简单的机制和管道来在 Neovim 中创建模糊匹配.
- [camspiers/snap](https://github.com/camspiers/snap) - An extensible fuzzy finder. Similar to Telescope, and optimized for performance, especially when grepping in large codebases.
- [ibhagwan/fzf-lua](https://github.com/ibhagwan/fzf-lua)  - `fzf.vim` 的 Lua 版本，高性能和完全异步，支持 `nvim-web-devicons`、git 指标、LSP、快速修复/位置列表等. 还支持 [`skim`](https://github.com/lotabout/skim) 作为其 fzf 二进制文件.
- [jvgrootveld/telescope-zoxide](https://github.com/jvgrootveld/telescope-zoxide) - Telescope integration for [zoxide](https://github.com/ajeetdsouza/zoxide), a smart directory picker that tracks your usage.
<!--lint ignore double-link-->
- [mini.fuzzy](https://github.com/echasnovski/mini.nvim#minifuzzy) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 具有执行一个字符串与其他字符串的模糊匹配的功能以及快速望远镜分拣器.

### Note Taking

- [0styx0/abbreinder.nvim](https://github.com/0styx0/abbreinder.nvim) - Abbreviation reminders for Neovim 0.5+.
- [oberblastmeister/neuron.nvim](https://github.com/oberblastmeister/neuron.nvim) - 与望远镜.nvim 集成的神经元笔记插件.
- [jbyuki/nabla.nvim](https://github.com/jbyuki/nabla.nvim) - 在 Neovim 中记录您的科学笔记.
- [nvim-neorg/neorg](https://github.com/nvim-neorg/neorg)  - 现代性与疯狂的可扩展性相遇. 在 Neovim 中组织您的生活的未来.
- [nvim-orgmode/orgmode](https://github.com/nvim-orgmode/orgmode) - 用 Lua 为 Neovim 0.5+ 编写的 Orgmode 克隆.
- [NFrid/due.nvim](https://github.com/NFrid/due.nvim) - 将日期字符串的到期日期显示为虚拟文本.
- [jbyuki/venn.nvim](https://github.com/jbyuki/venn.nvim) - Draw ASCII diagrams in Neovim.
- [stevearc/gkeep.nvim](https://github.com/stevearc/gkeep.nvim) - Neovim 的 Google Keep 集成.
- [renerocksai/telekasten.nvim](https://github.com/renerocksai/telekasten.nvim) - Neovim (lua) 插件，用于处理基于文本的 Markdown zettelkasten / wiki 并将其与基于望远镜.nvim 的期刊混合.

### Color

- [norcalli/nvim-colorizer.lua](https://github.com/norcalli/nvim-colorizer.lua) - A high-performance color highlighter for Neovim which has no external dependencies!.
- [sunjon/Shade.nvim](https://github.com/sunjon/Shade.nvim) - Shade 是一个 Neovim 插件，它可以让你的非活动窗口变暗，让你更容易一目了然地看到活动窗口.
- [winston0410/range-highlight.nvim](https://github.com/winston0410/range-highlight.nvim) - 一个非常轻量级的插件（~ 120loc），突出显示您在命令行中输入的范围.
- [xiyaowong/nvim-transparent](https://github.com/xiyaowong/nvim-transparent) - Make your Neovim transparent.
- [folke/twilight.nvim](https://github.com/folke/twilight.nvim) - Dim inactive portions of the code you're editing using TreeSitter.

### Colorscheme Creation

- [tjdevries/colorbuddy.nvim](https://github.com/tjdevries/colorbuddy.nvim)  - Neovim 的配色方案助手. 用Lua写的！ 快速简单的配色方案.
- [norcalli/nvim-base16.lua](https://github.com/norcalli/nvim-base16.lua) - 用于在 Neovim 中设置 base16 主题的程序化 Lua 库.
- [rktjmp/lush.nvim](https://github.com/rktjmp/lush.nvim) - Define Neovim themes as a DSL in Lua, with real-time feedback.
- [Iron-E/nvim-highlite](https://github.com/Iron-E/nvim-highlite) - 为开发人员提供逻辑上“精简”的配色方案模板。
<!--lint ignore double-link-->
- [mini.base16](https://github.com/echasnovski/mini.nvim#minibase16) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) with fast implementation of base16 theme for manually supplied palette.

### Colorscheme

#### Tree-sitter Supported Colorscheme

 Tree-sitter 是 Neovim 0.5 中的一个新系统，它可以将你的代码增量解析成一个可以工作的树，即使你的语法有错误. 这些配色方案专门为 Tree-sitter 高亮组设置了颜色.  Vim 配色方案将与开箱即用的新组一起使用.

- [shaeinst/roshnivim-cs](https://github.com/shaeinst/roshnivim-cs) - 用 Lua 编写的 Neovim 配色方案，专为 roshnivim 制作，支持 Tree-sitter.
- [rafamadriz/neon](https://github.com/rafamadriz/neon) - Customizable colorscheme with excellent italic and bold support, dark and light variants. Made to work and look good with Tree-sitter.
- [tomasiser/vim-code-dark](https://github.com/tomasiser/vim-code-dark) - A dark color scheme heavily inspired by the look of the Dark+ scheme of Visual Studio Code.
- [Mofiqul/vscode.nvim](https://github.com/Mofiqul/vscode.nvim) - 带有 vscode 浅色和深色主题的 Neovim 的 vim-code-dark 颜色方案的 Lua 端口.
- [marko-cerovac/material.nvim](https://github.com/marko-cerovac/material.nvim) - Material.nvim 是一个高度可配置的配色方案，用 Lua 编写并基于材质调色板.
- [bluz71/vim-nightfly-guicolors](https://github.com/bluz71/vim-nightfly-guicolors) - Nightfly 是一个深色 GUI 配色方案，灵感来自 Sarah Drasner 的夜猫子主题.
- [bluz71/vim-moonfly-colors](https://github.com/bluz71/vim-moonfly-colors) - Moonfly 是一种深色配色方案，支持护树.
- [ChristianChiarulli/nvcode-color-schemes.vim](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - Nvcode, onedark, nord colorschemes with Tree-sitter support.
- [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - 用 Lua 编写的干净、深色和浅色的 Neovim 主题，支持 LSP、Tree-sitter 和许多插件.
- [sainnhe/sonokai](https://github.com/sainnhe/sonokai) - 基于 Monokai Pro 的高对比度和生动的配色方案.
- [kyazdani42/blue-moon](https://github.com/kyazdani42/blue-moon) - Neovim 的深色配色方案源自palenight 和carbonight.
- [mhartington/oceanic-next](https://github.com/mhartington/oceanic-next) - Oceanic Next theme for Neovim.
- [glepnir/zephyr-nvim](https://github.com/glepnir/zephyr-nvim) - 带有树保姆支持的深色配色方案.
- [rockerBOO/boo-colorscheme-nvim](https://github.com/rockerBOO/boo-colorscheme-nvim) - Neovim 的配色方案，具有对 LSP、Tree-sitter 的手工支持.
- [jim-at-jibba/ariake-vim-colors](https://github.com/jim-at-jibba/ariake-vim-colors)  - 伟大的 Atom 主题的一个端口. 黑暗和光明与树保姆的支持.
- [Th3Whit3Wolf/onebuddy](https://github.com/Th3Whit3Wolf/onebuddy) - 明暗原子一个主题.
- [RishabhRD/nvim-rdark](https://github.com/RishabhRD/nvim-rdark) - 用 Lua 编写的 Neovim 的深色方案.
- [ishan9299/modus-theme-vim](https://github.com/ishan9299/modus-theme-vim) - 这是 Protesilaos Stavrou 为 emacs 开发的配色方案.
- [sainnhe/edge](https://github.com/sainnhe/edge) - Clean & Elegant Color Scheme inspired by Atom One and Material.
- [theniceboy/nvim\-deus](https://github.com/theniceboy/nvim-deus) - 支持树人的 Vim-deus.
- [bkegley/gloombuddy](https://github.com/bkegley/gloombuddy) - Neovim 的 Gloom 主题.
- [Th3Whit3Wolf/one-nvim](https://github.com/Th3Whit3Wolf/one-nvim) - Neovim 的 Atom One 启发了深色和浅色配色方案.
- [PHSix/nvim-hybrid](https://github.com/PHSix/nvim-hybrid) - 用 Lua 编写的 Neovim 配色方案.
- [Th3Whit3Wolf/space-nvim](https://github.com/Th3Whit3Wolf/space-nvim) - A spacemacs inspired dark and light colorscheme for Neovim.
- [yonlu/omni.vim](https://github.com/yonlu/omni.vim) - Omni color scheme for Vim.
- [ray-x/aurora](https://github.com/ray-x/aurora) - 支持 Tree-sitter 和 LSP 的 24 位深色主题.
- [novakne/kosmikoa.nvim](https://github.com/novakne/kosmikoa.nvim) - Colorscheme for Neovim.
- [tanvirtin/monokai.nvim](https://github.com/tanvirtin/monokai.nvim) - 用 Lua 编写的 Neovim 的 Monokai 主题.
- [nekonako/xresources-nvim](https://github.com/nekonako/xresources-nvim) - 基于您的 xresources 颜色的 Neovim 颜色方案.
- [savq/melange](https://github.com/savq/melange) - Dark color scheme for Neovim and Vim 🗡️.
- [RRethy/nvim-base16](https://github.com/RRethy/nvim-base16)  - 用于构建 base16 颜色方案的 Neovim 插件. 包括对 Treesitter 和 LSP 高亮组的支持.
- [fenetikm/falcon](https://github.com/fenetikm/falcon) - 终端、Vim 和朋友的配色方案.
- [andersevenrud/nordic.nvim](https://github.com/andersevenrud/nordic.nvim) - 北欧风格的配色方案.
- [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) - 基于 Nord 调色板的 Neovim 主题.
- [MordechaiHadad/nvim-papadark](https://github.com/MordechaiHadad/nvim-papadark) - My own Neovim colorscheme.
- [ishan9299/nvim-solarized-lua](https://github.com/ishan9299/nvim-solarized-lua) - Solarized colorscheme in Lua for Neovim 0.5.
- [shaunsingh/moonlight.nvim](https://github.com/shaunsingh/moonlight.nvim) - 用于 NeoVim 的 VSCode 月光配色方案的端口，用 Lua 编写，内置支持原生 LSP、Tree-sitter 和更多插件.
- [navarasu/onedark.nvim](https://github.com/navarasu/onedark.nvim) - 基于 Atom 的 One Dark Theme 用 Lua 编写的 Neovim 0.5 的 One Dark 主题.
- [lourenci/github-colors](https://github.com/lourenci/github-colors) - GitHub colors leveraging Tree-sitter to get 100% accuracy.
- [sainnhe/gruvbox-material](https://github.com/sainnhe/gruvbox-material) - Gruvbox 修改具有更柔和的对比度和 Tree-sitter 支持.
- [sainnhe/everforest](https://github.com/sainnhe/everforest) - A green based colorscheme designed to be warm, soft and easy on the eyes.
- [NTBBloodbath/doom-one.nvim](https://github.com/NTBBloodbath/doom-one.nvim) - 用于 Neovim 的 doom-emacs 的 doom-one 的 Lua 端口.
- [dracula/vim](https://github.com/dracula/vim) - 著名的美丽黑暗动力主题.
- [Mofiqul/dracula.nvim](https://github.com/Mofiqul/dracula.nvim) - 用 Lua 编写的 neovim 的 Dracula 配色方案.
- [yashguptaz/calvera-dark.nvim](https://github.com/yashguptaz/calvera-dark.nvim) - A port of [VSCode Calvara Dark](https://github.com/saurabhdaware/vscode-calvera-dark) Theme to Neovim with Tree-sitter and many other plugins support.
- [nxvu699134/vn-night.nvim](https://github.com/nxvu699134/vn-night.nvim)  - 用 Lua 编写的深色 Neovim 配色方案. 支持内置 LSP 和 Tree-sitter.
- [adisen99/codeschool.nvim](https://github.com/adisen99/codeschool.nvim) - 用 Lua 编写的 Neovim 的 Codeschool 配色方案，具有 Tree-sitter 和内置 lsp 支持.
- [projekt0n/github-nvim-theme](https://github.com/projekt0n/github-nvim-theme)  - 用 Lua 编写的 Neovim、kitty、alacritty 的 GitHub 主题. 支持内置 LSP 和 Tree-sitter.
- [kdheepak/monochrome.nvim](https://github.com/kdheepak/monochrome.nvim) - A 16 bit monochrome colorscheme that uses hsluv for perceptually distinct gray colors, with support for Tree-sitter and other commonly used plugins.
- [rose-pine/neovim](https://github.com/rose-pine/neovim) - All natural pine, faux fur and a bit of soho vibes for the classy minimalist.
- [mcchrish/zenbones.nvim](https://github.com/mcchrish/zenbones.nvim) - vim/neovim 配色方案的集合，旨在使用对比和字体变化来突出显示代码.
- [catppuccin/nvim](https://github.com/catppuccin/nvim) - Warm mid-tone dark theme to show off your vibrant self! with support for native LSP, Tree-sitter, and more 🍨!
- [FrenzyExists/aquarium-vim](https://github.com/FrenzyExists/aquarium-vim) - A dark, yet vibrant colorscheme for Neovim.
- [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) - 一个柔和的深色、完全可定制的 Neovim 主题，支持 lsp、treesitter 和各种插件.
- [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim) - 用 Lua 编写的 Neovim 冷色、深色配色方案，移植自 [arzg/vim-substrata](https://github.com/arzg/vim-substrata) 主题.
- [ldelossa/vimdark](https://github.com/ldelossa/vimdark)  - 适用于夜间的最小 Vim 主题. 松散地基于 vim-monotonic 和 chrome 的深色阅读器扩展. 白天也包括一个轻主题.
- [mangeshrex/uwu.vim](https://github.com/Mangeshrex/uwu.vim) - A beautiful and dark vim colorscheme written in vimscript.
- [adisen99/apprentice.nvim](https://github.com/adisen99/apprentice.nvim) - Colorscheme for Neovim written in Lua based on the [Apprentice](https://github.com/romainl/Apprentice) 具有 Tree-sitter 和内置 lsp 支持的颜色模式.
- [olimorris/onedarkpro.nvim](https://github.com/olimorris/onedarkpro.nvim) - One Dark Pro theme for Neovim, written in Lua and based on the VS Code theme. Includes dark and light themes with completely customisable colors, styles and highlights.
- [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim) - Neovim 主题结合了 Nord 和 Atom One Dark 调色板，带来更生动的编程体验.
- [RishabhRD/gruvy](https://github.com/RishabhRD/gruvy) - Gruvbuddy without colorbuddy using Lush.
<!--lint ignore double-link-->
- [minischeme](https://github.com/echasnovski/mini.nvim#plugin-colorscheme) - Color scheme of [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 它是 base16 的变体，具有根据最佳感知均匀性选择的强调色.
- [luisiacc/gruvbox-baby](https://github.com/luisiacc/gruvbox-baby) - 一个现代的 gruvbox 主题，具有完整的 treesitter 支持.
- [titanzero/zephyrium](https://github.com/titanzero/zephyrium) - 一个 zephyr 风格的主题，用 Lua 编写，支持 TreeSitter.
- [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) - NeoVim 深色配色方案灵感来自葛饰北斋的名画色彩.
- [tiagovla/tokyodark.nvim](https://github.com/tiagovla/tokyodark.nvim) - 一个干净的黑暗主题，用 lua 编写，用于 neovim 0.5 及更高版本.

#### Lua Colorscheme

These colorschemes may not specialize in Tree-sitter directly but are written in Lua.

- [tjdevries/gruvbuddy.nvim](https://github.com/tjdevries/gruvbuddy.nvim) - 我的盒子颜色.
- [ellisonleao/gruvbox.nvim](https://github.com/ellisonleao/gruvbox.nvim) - Gruvbox 社区配色方案 Lua 端口.
- [metalelf0/jellybeans-nvim](https://github.com/metalelf0/jellybeans-nvim) - Neovim 的软糖配色方案端口.

### Utility

- [famiu/bufdelete.nvim](https://github.com/famiu/bufdelete.nvim) - Delete Neovim buffers without losing your window layout.
<!--lint ignore double-link-->
- [mini.bufremove](https://github.com/echasnovski/mini.nvim#minibufremove) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) for buffer removing (unshow, delete, wipeout) while saving window layout.
- [jghauser/mkdir.nvim](https://github.com/jghauser/mkdir.nvim) - Automatically create missing directories when saving files.
- [matbme/JABS.nvim](https://github.com/matbme/JABS.nvim) - 漂亮和最小的缓冲区切换器窗口.
- [clojure-vim/jazz.nvim](https://github.com/clojure-vim/jazz.nvim) - Acid + Impromptu = Jazz.
- [sudormrfbin/cheatsheet.nvim](https://github.com/sudormrfbin/cheatsheet.nvim) - Searchable cheatsheet.
- [code-biscuits/nvim-biscuits](https://github.com/code-biscuits/nvim-biscuits)  - 各种饼干的 Neovim 端口. 最终得到更多支持的语言.
- [Pocco81/AbbrevMan.nvim](https://github.com/Pocco81/AbbrevMan.nvim) - A NeoVim plugin for managing vim abbreviations.
- [kazhala/close-buffers.nvim](https://github.com/kazhala/close-buffers.nvim) - 根据不同条件删除多个vim缓冲区.
- [rktjmp/paperplanes.nvim](https://github.com/rktjmp/paperplanes.nvim) - Post selections or buffers to online paste bins.
- [max397574/better-escape.nvim](https://github.com/max397574/better-escape.nvim) - 创建快捷方式以退出插入模式而不会延迟.
- [rcarriga/nvim-notify](https://github.com/rcarriga/nvim-notify) - A fancy, configurable, notification manager for NeoVim.
- [saifulapm/chartoggle.nvim](https://github.com/saifulapm/chartoggle.nvim) - 为 Neovim 切换行尾的任何字符.
- [stevearc/dressing.nvim](https://github.com/stevearc/dressing.nvim) - 改进内置的 `vim.ui` 接口与望远镜、fzf 等.

### Icon

- [kyazdani42/nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons) - 一个 Lua 分支 [vim-devicons](https://github.com/ryanoasis/vim-devicons).
- [yamatsum/nvim-nonicons](https://github.com/yamatsum/nvim-nonicons) - nvim-web-devicons 的配置集合.

### Debugging

- [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap) - Neovim 的调试适配器协议客户端实现.
- [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) - Thin wrapper for GDB, LLDB, PDB/PDB++ and BashDB.
- [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) - 用户界面是 nvim-dap.
- [Pocco81/DAPInstall.nvim](https://github.com/Pocco81/DAPInstall.nvim) - 一个 NeoVim 插件，用于管理 Nvim-dap 的多个调试器.

### Spellcheck

- [lewis6991/spellsitter.nvim](https://github.com/lewis6991/spellsitter.nvim) - 使用 tree-sitter 启用 Neovim 的拼写检查器.

### Neovim Lua Development

- [tjdevries/nlua.nvim](https://github.com/tjdevries/nlua.nvim) - Neovim 的 Lua 开发.
- [svermeulen/vimpeccable](https://github.com/svermeulen/vimpeccable) - Commands to help write your .vimrc in Lua or any Lua based language.
- [nanotee/nvim-lua-guide](https://github.com/nanotee/nvim-lua-guide) - A guide to using Lua in Neovim.
- [rafcamlet/nvim-luapad](https://github.com/rafcamlet/nvim-luapad) - 用于嵌入式 Lua 引擎的交互式实时 Neovim 暂存器 - 输入并观看！
- [nvim-lua/plenary.nvim](https://github.com/nvim-lua/plenary.nvim) - Plenary: full; complete; entire; absolute; unqualified. All the Lua functions I don't want to write twice.
- [nvim-lua/popup.nvim](https://github.com/nvim-lua/popup.nvim) - Neovim 中来自 vim 的 Popup API 的实现.
- [tjdevries/vlog.nvim](https://github.com/tjdevries/vlog.nvim) - 单个文件，无依赖性，轻松复制和粘贴日志文件以添加到您的 Neovim Lua 插件.
- [bfredl/nvim-luadev](https://github.com/bfredl/nvim-luadev)  - Neovim Lua 插件的 REPL/调试控制台.  `:Luadev` 命令将打开一个临时窗口，该窗口将显示执行 Lua 代码的输出.
- [jbyuki/one-small-step-for-vimkind](https://github.com/jbyuki/one-small-step-for-vimkind) - An adapter for the Neovim Lua language. It allows you to debug any Lua code running in a Neovim instance (A Lua plugin that can debug Neovim Lua plugins).
- [tami5/sqlite.lua](https://github.com/tami5/sqlite.lua) - SQLite/LuaJIT binding for Lua and Neovim.
- [folke/lua-dev.nvim](https://github.com/folke/lua-dev.nvim) - 用于 init.Lua 和插件开发的开发设置，带有完整的签名帮助、文档和 Neovim Lua API 的完成.
- [MunifTanjim/nui.nvim](https://github.com/MunifTanjim/nui.nvim) - Neovim 的 UI 组件库。
- [m00qek/plugin-template.nvim](https://github.com/m00qek/plugin-template.nvim) - 设置测试基础设施和 GitHub 操作的插件模板.
<!--lint ignore double-link-->
- [mini.doc](https://github.com/echasnovski/mini.nvim#minidoc) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 从类似 EmmyLua 的注释中生成帮助文件. 允许通过钩子函数灵活定制输出.

### Fennel

- [Olical/aniseed](https://github.com/Olical/aniseed) - 使用 Fennel 配置和扩展 Neovim（从 Lisp 到 Lua）.
- [rktjmp/hotpot.nvim](https://github.com/rktjmp/hotpot.nvim) - Neovim 内无缝、透明的茴香.

### Tabline

- [romgrk/barbar.nvim](https://github.com/romgrk/barbar.nvim) - The Neovim tabline plugin.
- [akinsho/bufferline.nvim](https://github.com/akinsho/bufferline.nvim) - A snazzy buffer line for Neovim built using Lua.
- [crispgm/nvim-tabline](https://github.com/crispgm/nvim-tabline) - 带有 Lua 的 tabline.vim 的 Neovim 端口.
- [alvarosevilla95/luatab.nvim](https://github.com/alvarosevilla95/luatab.nvim) - 一个用 Lua 编写的简单表格.
- [johann2357/nvim-smartbufs](https://github.com/johann2357/nvim-smartbufs) - Neovim 中的智能缓冲区管理.
- [kdheepak/tabline.nvim](https://github.com/kdheepak/tabline.nvim) - “缓冲区和制表符”表行.
- [noib3/cokeline.nvim](https://github.com/noib3/cokeline.nvim) - Neovim 缓冲线，适合具有成瘾性格的人.
<!--lint ignore double-link-->
- [mini.tabline](https://github.com/echasnovski/mini.nvim#minitabline) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于在一个选项卡的情况下显示列出的缓冲区的最小选项卡，否则回退到默认值.
- [rafcamlet/tabline-framework.nvim](https://github.com/rafcamlet/tabline-framework.nvim) - 用户友好的框架，只需几行代码即可构建您的梦想表格.

### Statusline

- [NTBBloodbath/galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim) - Galaxyline componentizes Vim's statusline by having a provider for each text area. This means you can use the api provided by galaxyline to create the statusline that you want, easily.
- [tjdevries/express_line.nvim](https://github.com/tjdevries/express_line.nvim) - 支持协程、函数和作业.
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) - 快速且易于配置的 Neovim 状态栏.
- [adelarsq/neoline.vim](https://github.com/adelarsq/neoline.vim) - 使用 Lua 的 Neovim 的轻量级状态栏/表格插件.
- [ojroques/nvim-hardline](https://github.com/ojroques/nvim-hardline)  - 状态线/缓冲线. 它的灵感来自 [vim-airline](https://github.com/vim-airline/vim-airline) 但目标是尽可能轻巧简单.
- [datwaft/bubbly.nvim](https://github.com/datwaft/bubbly.nvim) - Bubbly status line for Neovim.
- [beauwilliams/statusline.lua](https://github.com/beauwilliams/statusline.lua) - 用 Lua 编写的 Neovim 零配置最小状态栏，具有出色的集成和超快的速度！
- [tamton-aquib/staline.nvim](https://github.com/tamton-aquib/staline.nvim)  - Lua 中 Neovim 的现代轻量级状态栏. 主要使用 unicode 符号来显示信息.
- [Famiu/feline.nvim](https://github.com/Famiu/feline.nvim) - 用 Lua 编写的 Neovim 最小、时尚和可定制的状态栏.
- [windwp/windline.nvim](https://github.com/windwp/windline.nvim)  - Neovim 的下一代状态栏. 动画状态栏.
- [konapun/vacuumline.nvim](https://github.com/konapun/vacuumline.nvim) - 受航空公司启发的星系线配置.
<!--lint ignore double-link-->
- [mini.statusline](https://github.com/echasnovski/mini.nvim#ministatusline) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于最小和快速的状态行. 支持根据窗口宽度更改内容.

### Statusline component

- [SmiteshP/nvim-gps](https://github.com/SmiteshP/nvim-gps) - 简单的状态栏组件，显示您在其中工作的范围.

### Cursorline

- [yamatsum/nvim-cursorline](https://github.com/yamatsum/nvim-cursorline) - Neovim 插件，突出光标词和行.
- [xiyaowong/nvim-cursorword](https://github.com/xiyaowong/nvim-cursorword) - Part of nvim-cursorline. Highlight the word under the cursor.
- [RRethy/vim-illuminate](https://github.com/RRethy/vim-illuminate)  - 突出显示光标下的单词.  Neovim 的内置 LSP 可用，它可以用来更智能地突出显示.
<!--lint ignore double-link-->
- [mini.cursorword](https://github.com/echasnovski/mini.nvim#minicursorword) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) for automatic highlighting of word under cursor (displayed after customizable delay).

### Startup

- [glepnir/dashboard-nvim](https://github.com/glepnir/dashboard-nvim) - Neovim 的简约仪表板，灵感来自 doom-emacs.
- [goolord/alpha-nvim](https://github.com/goolord/alpha-nvim) - A fast and highly customizable greeter like [vim-startify](https://github.com/mhinz/vim-startify)/dashboard-nvim 用于 Neovim.
<!--lint ignore double-link-->
- [mini.starter](https://github.com/echasnovski/mini.nvim#ministarter) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 对于开始屏幕. 显示的项目是完全可定制的，项目选择可以使用带有即时视觉反馈的前缀查询来完成.
- [henriquehbr/nvim-startup.lua](https://github.com/henriquehbr/nvim-startup.lua) - 显示 Neovim 启动时间.
- [startup-nvim/startup.nvim](https://github.com/startup-nvim/startup.nvim) - Neovim 的完全可定制的问候语.

### Indent

- [glepnir/indent-guides.nvim](https://github.com/glepnir/indent-guides.nvim) - Indent plugin.
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim) - IndentLine replacement in Lua with more features and treesitter support.

### Game

- [ThePrimeagen/vim-be-good](https://github.com/ThePrimeagen/vim-be-good) - Vim-be-good is a Neovim plugin designed to make you better at Vim Movements.
- [ThePrimeagen/vim-apm](https://github.com/ThePrimeagen/vim-apm) - Vim APM，Actions per minute，是自 vim-slicedbread 以来最棒的插件.
- [alec-gibson/nvim-tetris](https://github.com/alec-gibson/nvim-tetris) - 将 emacs 的最大功能引入 Neovim - 俄罗斯方块！.
- [seandewar/nvimesweeper](https://github.com/seandewar/nvimesweeper) - 在您最喜欢的文本编辑器中玩扫雷.

### File explorer

- [kyazdani42/nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - Neovim 的简单快速的文件浏览器树！
- [luukvbaal/nnn.nvim](https://github.com/luukvbaal/nnn.nvim) - 文件资源管理器由 [nnn](https://github.com/jarun/nnn) 和卢阿.
- [tamago324/lir.nvim](https://github.com/tamago324/lir.nvim) - Simple file explorer.
- [TimUntersberger/neofs](https://github.com/TimUntersberger/neofs) - 用 Lua 编写的 Neovim 文件管理器.
- [kevinhwang91/rnvimr](https://github.com/kevinhwang91/rnvimr) - A simple yet amazing file explorer for Neovim.
- [Xuyuanp/yanil](https://github.com/Xuyuanp/yanil) - Lua 中的又一棵书呆子树.
- [ms-jpq/chadtree](https://github.com/ms-jpq/chadtree)  - Neovim 的文件管理器. 比NERDTree好.
- [is0n/fm-nvim](https://github.com/is0n/fm-nvim) - Neovim 插件，可让您在 Neovim 中使用您最喜欢的终端文件管理器（和模糊查找器）.

### Dependency management

- [akinsho/dependency-assist.nvim](https://github.com/akinsho/dependency-assist.nvim) - 搜索并添加新的依赖项（飞镖，现在但很快就会生锈）.
- [vuki656/package-info.nvim](https://github.com/vuki656/package-info.nvim) - 在 package.json 中将最新的包版本显示为虚拟文本.

### Git

- [f-person/git-blame.nvim](https://github.com/f-person/git-blame.nvim) - 显示 git blame 信息.
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Git 集成：标志、大块动作、责备等.
- [TimUntersberger/neogit](https://github.com/TimUntersberger/neogit) - Neovim 的 Magit 克隆，可能会改变一些东西以适应 Vim 哲学.
- [tveskag/nvim-blame-line](https://github.com/tveskag/nvim-blame-line) - A small plugin that uses neovims virtual text to print git blame info at the end of the current line.
- [ruifm/gitlinker.nvim](https://github.com/ruifm/gitlinker.nvim)  - 为多个 git 主机生成可共享的文件永久链接. 受 tpope/vim-fugitive 的 :GBrowse 启发.
- [tanvirtin/vgit.nvim](https://github.com/tanvirtin/vgit.nvim) - Neovim 的可视化 Git 插件，可增强您的 git 体验.
- [sindrets/diffview.nvim](https://github.com/sindrets/diffview.nvim) - 单个标签页界面，可轻松循环浏览任何 git rev 的所有修改文件的差异.
- [kdheepak/lazygit.nvim](https://github.com/kdheepak/lazygit.nvim) - 从 Neovim 中调用lazygit 的插件.

### Programming languages support

- [go.nvim](https://github.com/ray-x/go.nvim) - 基于 lsp 和 Treesitter 的 Golang 插件.
- [akinsho/flutter-tools.nvim](https://github.com/akinsho/flutter-tools.nvim) - Build flutter and dart applications in Neovim using the native lsp.
- [crispgm/nvim-go](https://github.com/crispgm/nvim-go) - Neovim 的 Golang 开发插件的最小实现.
- [gennaro-tedesco/nvim-jqx](https://github.com/gennaro-tedesco/nvim-jqx) - json 文件的交互界面.
- [edolphin-ydf/goimpl.nvim](https://github.com/edolphin-ydf/goimpl.nvim) - Generate interface stubs for a type.
- [lean.nvim](https://github.com/Julian/lean.nvim) - Neovim support for the [Lean Theorem Prover](https://leanprover.github.io/).
- [rafaelsq/nvim-goc.lua](https://github.com/rafaelsq/nvim-goc.lua) - Highlight your buffer with Golang Code Coverage.

### Comment

- [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim)  - Neovim 的智能和强大的评论插件. 支持注释字符串、动作、点重复等.
- [b3nj5m1n/kommentary](https://github.com/b3nj5m1n/kommentary) - 用 Lua 编写的评论插件.
- [glepnir/prodoc.nvim](https://github.com/glepnir/prodoc.nvim) - 评论和支持生成注释.
- [gennaro-tedesco/nvim-commaround](https://github.com/gennaro-tedesco/nvim-commaround) - 用 Lua 编写的快速轻便的评论插件.
- [folke/todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - Highlight, list and search todo comments in your projects.
- [terrortylor/nvim-comment](https://github.com/terrortylor/nvim-comment) - 使用内置的评论字符串选项在 Neovim 中切换评论.
- [winston0410/commented.nvim](https://github.com/winston0410/commented.nvim) - A commenting plugin that supports counts and multiple comment patterns and much more.
- [s1n7ax/nvim-comment-frame](https://github.com/s1n7ax/nvim-comment-frame) - Adds a comment frame based on the source file.
- [danymat/neogen](https://github.com/danymat/neogen)  - 更好的注释生成器. 支持多种语言和注释约定.
<!--lint ignore double-link-->
- [mini.comment](https://github.com/echasnovski/mini.nvim#minicomment) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于每行评论. 完全支持点重复.

### Collaborative Editing

- [jbyuki/instant.nvim](https://github.com/jbyuki/instant.nvim) - 一个用 Lua 编写的 Neovim 协作编辑插件，没有依赖关系.

### Quickfix

- [kevinhwang91/nvim-bqf](https://github.com/kevinhwang91/nvim-bqf) - nvim-bqf 的目标是让 Neovim 的 quickfix 窗口更好.
- [gitlab.com/yorickpeterse/nvim-pqf](https://gitlab.com/yorickpeterse/nvim-pqf) - Prettier quickfix/location list windows for Neovim.
- [stevearc/qf_helper.nvim](https://github.com/stevearc/qf_helper.nvim) - Neovim quickfix 的一系列改进.

### Motion

- [tjdevries/train.nvim](https://github.com/tjdevries/train.nvim) - Train yourself with vim motions and make your own train tracks.
- [phaazon/hop.nvim](https://github.com/phaazon/hop.nvim) - Hop is an EasyMotion-like plugin allowing you to jump anywhere in a document with as few keystrokes as possible.
- [ggandor/lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim) - A Sneak-like plugin offering unparalleled navigation speed via ahead-of-time displayed labels, that eliminate the pause between entering the search pattern and selecting the target.
<!--lint ignore double-link-->
- [mini.jump](https://github.com/echasnovski/mini.nvim#minijump) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) for smarter jumping to a single character.
- [mfussenegger/nvim-ts-hint-textobject](https://github.com/mfussenegger/nvim-ts-hint-textobject) - Region selection with hints on the AST nodes of a document powered by treesitter.
- [rlane/pounce.nvim](https://github.com/rlane/pounce.nvim) - 一个类似于 EasyMotion 的插件，用于使用模糊搜索快速移动光标.

### Code Runner

- [michaelb/sniprun](https://github.com/michaelb/sniprun) - Run parts of code of any language directly from Neovim.
- [pianocomposer321/yabs.nvim](https://github.com/pianocomposer321/yabs.nvim) - Neovim 的另一个构建系统，用 Lua 编写.
- [CRAG666/code_runner.nvim](https://github.com/CRAG666/code_runner.nvim) - 拥有超能力的最佳代码运行程序.
- [is0n/jaq-nvim](https://github.com/is0n/jaq-nvim) - Lua 中 Neovim 的另一个 Quickrun 插件.

### GitHub

- [pwntester/octo.nvim](https://github.com/pwntester/octo.nvim)  - 处理来自 Neovim 的 GitHub 问题和 PR. 只需编辑问题描述.
- [pwntester/codeql.nvim](https://github.com/pwntester/codeql.nvim) - Neovim plugin to help writing and testing CodeQL queries.

### Search

- [kevinhwang91/nvim-hlslens](https://github.com/kevinhwang91/nvim-hlslens) - 帮助您更好地浏览搜索到的信息，无缝跳转匹配的实例.
- [rktjmp/highlight-current-n.nivm](https://github.com/rktjmp/highlight-current-n.nvim)  - 突出显示当前的 /, ? 或 \* 在按 n 或 N 时在光标下匹配，然后让开.

### Scrollbar

- [Xuyuanp/scrollbar.nvim](https://github.com/Xuyuanp/scrollbar.nvim) - Scrollbar for Neovim.
- [dstein64/nvim-scrollview](https://github.com/dstein64/nvim-scrollview) - 显示交互式滚动条的 Neovim 插件.
- [petertriho/nvim-scrollbar](https://github.com/petertriho/nvim-scrollbar) - 显示诊断和搜索结果的可扩展滚动条.

### Scrolling

- [karb94/neoscroll.nvim](https://github.com/karb94/neoscroll.nvim) - Neovim 的平滑滚动.

### Mouse

- [notomo/gesture.nvim](https://github.com/notomo/gesture.nvim) - Neovim 的鼠标手势插件.

### Project

- [nyngwang/NeoRoot.lua](https://github.com/nyngwang/NeoRoot.lua) - 将您当前的工作目录更改为光标所在的缓冲区，并尝试上升 2 级，但在遇到您定义的项目根目录之一后停止.
- [windwp/nvim-projectconfig](https://github.com/windwp/nvim-projectconfig) - Load Neovim config depend on project directory.
- [windwp/nvim-spectre](https://github.com/windwp/nvim-spectre) - Search and replace panel for Neovim.
- [ahmedkhalf/project.nvim](https://github.com/ahmedkhalf/project.nvim) - 一个多合一的 Neovim 插件，提供卓越的项目管理.
- [klen/nvim-config-local](https://github.com/klen/nvim-config-local) - 从工作目录安全加载本地配置文件.

### Browser integration

- [glacambre/firenvim](https://github.com/glacambre/firenvim) - 将 Neovim 直接嵌入您的浏览器，无需任何问题.

### Editing support

- [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag) - 使用 treesitter 自动关闭和自动重命名 xml、html、jsx 标签.
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs) - A minimalist autopairs for Neovim written by Lua.
- [steelsojka/pears.nvim](https://github.com/steelsojka/pears.nvim) - Auto pair plugin for Neovim.
<!--lint ignore double-link-->
- [mini.pairs](https://github.com/echasnovski/mini.nvim#minipairs) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) for autopairs which has minimal defaults and functionality to do per-key mapping.
- [monaqa/dial.nvim](https://github.com/monaqa/dial.nvim) - Extended increment/decrement.
- [p00f/nvim-ts-rainbow](https://github.com/p00f/nvim-ts-rainbow) - Rainbow :rainbow: Neovim 的括号，使用 tree-sitter :rainbow:.
- [AckslD/nvim-revJ.lua](https://github.com/AckslD/nvim-revJ.lua) - Neovim Lua 插件，用于与连接线（J）相反的参数.
- [edluffy/specs.nvim](https://github.com/edluffy/specs.nvim) - 一个快速、轻量级的 Neovim Lua 插件，可以密切关注光标的跳跃位置.
- [JoosepAlviste/nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)  - Neovim 插件，用于根据文件中的光标位置设置 `commentstring` 选项. 该位置通过treesitter 查询进行检查.
- [Pocco81/TrueZen.nvim](https://github.com/Pocco81/TrueZen.nvim) - NeoVim 的简洁优雅的无干扰写作.
- [Pocco81/HighStr.nvim](https://github.com/Pocco81/HighStr.nvim) - 一个 NeoVim 插件，用于突出显示视觉选择，就像在普通文档编辑器中一样！
- [Pocco81/AutoSave.nvim](https://github.com/Pocco81/AutoSave.nvim) - A NeoVim plugin for saving your work before the world collapses or you type :qa!
- [folke/zen-mode.nvim](https://github.com/folke/zen-mode.nvim) - Neovim 的无干扰编码.
- [haringsrob/nvim_context_vt](https://github.com/haringsrob/nvim_context_vt) - 显示当前上下文的虚拟文本.
- [romgrk/nvim-treesitter-context](https://github.com/romgrk/nvim-treesitter-context) - 使用当前功能/块上下文显示浮动悬停.
- [mizlan/iswap.nvim](https://github.com/mizlan/iswap.nvim)  - 交互式选择和交换函数参数、列表元素等. 由保姆提供支持.
- [nacro90/numb.nvim](https://github.com/nacro90/numb.nvim) - 以不突兀的方式窥视线条.
- [abecodes/tabout.nvim](https://github.com/abecodes/tabout.nvim) - 跳出括号、引号、对象等.
- [ethanholz/nvim-lastplace](https://github.com/ethanholz/nvim-lastplace) - 在您上次编辑的位置重新打开文件.
- [Allendang/nvim-expand-expr](https://github.com/AllenDang/nvim-expand-expr) - 将表达式扩展并重复到多行.
- [h-hg/fcitx.nvim](https://github.com/h-hg/fcitx.nvim) - 分别切换和恢复每个缓冲区的 fcitx 状态.
- [McAuleyPenney/tidy.nvim](https://github.com/McAuleyPenney/tidy.nvim) - Clear trailing whitespace and empty lines at end of file on every save.
<!--lint ignore double-link-->
- [mini.trailspace](https://github.com/echasnovski/mini.nvim#minitrailspace) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于自动突出显示尾随空格并具有删除它的功能.
- [filipdutescu/renamer.nvim](https://github.com/filipdutescu/renamer.nvim) - VS Code-like renaming UI for Neovim, writen in Lua.
- [gbprod/cutlass.nvim](https://github.com/gbprod/cutlass.nvim) - Plugin that adds a 'cut' operation separate from 'delete'.
- [gbprod/substitute.nvim](https://github.com/gbprod/substitute.nvim) - Neovim 插件引入了新的操作员动作来快速替换文本.
- [sQVe/sort.nvim](https://github.com/sQVe/sort.nvim) - Sorting plugin that intelligently supports line-wise and delimiter sorting.
- [booperlv/nvim-gomove](https://github.com/booperlv/nvim-gomove) - A complete plugin for moving and duplicating blocks and lines, with complete fold handling, reindenting, and undoing in one go.
- [anuvyklack/pretty-fold.nvim](https://github.com/anuvyklack/pretty-fold.nvim) - 折叠文本自定义和折叠区域预览.

### Formatting

- [mhartington/formatter.nvim](https://github.com/mhartington/formatter.nvim) - A format runner for Neovim written in Lua.
- [lukas-reineke/format.nvim](https://github.com/lukas-reineke/format.nvim)  - Neovim 的快速异步格式化. 支持格式化嵌入的代码块.
- [sbdchd/neoformat](https://github.com/sbdchd/neoformat) - A (Neo)vim plugin for formatting code.

### Web development

- [NTBBloodbath/rest.nvim](https://github.com/NTBBloodbath/rest.nvim) - A fast Neovim http client written in Lua.

### Media

- [ekickx/clipboard-image.nvim](https://github.com/ekickx/clipboard-image.nvim) - Neovim Lua plugin to paste image from clipboard.
- [gwatcha/reaper-keys](https://github.com/gwatcha/reaper-keys) - Reaper DAW 的模态键绑定.
- [madskjeldgaard/reaper-nvim](https://github.com/madskjeldgaard/reaper-nvim) - Remote control Reaper DAW from Neovim.
- [davidgranstrom/scnvim](https://github.com/davidgranstrom/scnvim) - SuperCollider 的 Neovim 前端.

### Discord Rich Presence

- [andweeb/presence.nvim](https://github.com/andweeb/presence.nvim) - 用 Lua 编写的 Neovim 的快速和精简的 Discord Rich Presence 插件.

### Command Line

- [notomo/cmdbuf.nvim](https://github.com/notomo/cmdbuf.nvim) - 替代命令行窗口插件.
- [gelguy/wilder.nvim](https://github.com/gelguy/wilder.nvim) - 用于模糊命令行自动完成的插件.

### Session

- [rmagatti/auto-session](https://github.com/rmagatti/auto-session) - Neovim 的小型自动化会话管理器.
<!--lint ignore double-link-->
- [mini.sessions](https://github.com/echasnovski/mini.nvim#minisessions) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于会话管理（读取、写入、删除）.

### Test

- [rcarriga/vim-ultest](https://github.com/rcarriga/vim-ultest) - The ultimate testing plugin for NeoVim.
- [David-Kunz/jester](https://github.com/David-Kunz/jester) - A Neovim plugin to easily run and debug Jest tests.

### Competitive Programming

- [p00f/cphelper.nvim](https://github.com/p00f/cphelper.nvim) - 用 Lua 编写的用于竞争性编程的 Neovim 助手.
- [xeluxee/competitest.nvim](https://github.com/xeluxee/competitest.nvim) - 自动化测试用例管理和检查竞争性编程竞赛的插件.

### Preconfigured Configuration

- [SpaceVim/SpaceVim](https://spacevim.org) - A community-driven modular vim/neovim distribution, like spacemacs but for vim/neovim.
- [CosmicNvim/CosmicNvim](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim 是用于 Web 开发的轻量级和自以为是的 Neovim 配置，专为提供 COSMIC 编程体验而设计！
- [artart222/CodeArt](https://github.com/artart222/CodeArt) - 一个完全用 Lua 编写的快速通用 IDE，带有适用于 Linux/Windows/macOS 的安装程序，并内置用于更新它的 `:CodeArtUpdate` 命令.
- [NTBBloodbath/doom-nvim](https://github.com/NTBBloodbath/doom-nvim) - Port of the doom-emacs framework, its goal is to add useful functions to Neovim to start working in a stable and efficient development environment without spending a lot of time configuring everything.
- [crivotz/nv-ide](https://github.com/crivotz/nv-ide) - Neovim custom configuration, oriented for full stack developers (rails, ruby, php, html, css, SCSS, JavaScript).
- [ChristianChiarulli/LunarVim](https://github.com/ChristianChiarulli/LunarVim) - 该项目旨在帮助人们从 VSCode 过渡到卓越的文本编辑体验.
- [hackorum/VapourNvim](https://github.com/hackorum/VapourNvim) - A NeoVim config for THE ULTIMATE vim IDE-like experience.
- [vi-tality/neovitality](https://github.com/vi-tality/neovitality) - 一个功能齐全的 NeoVim 发行版，与 Nix Flake 一起打包，便于安装和重现性.
- [siduck76/NvChad](https://github.com/siduck76/NvChad) - 尝试使 Neovim cli 像 IDE 一样功能，同时非常漂亮且不那么臃肿.
- [ashincoder/StarVim](https://github.com/ashincoder/StarVim) - 一个超越月亮和星星的 IDE 包装器⭐.
- [mjlbach/defaults.nvim](https://github.com/mjlbach/defaults.nvim) - 一个极小、单个文件和带注释的配置模板，演示 LSP 集成、自动完成、片段、treesitter 等.
- [cstsunfu/.sea.nvim](https://github.com/cstsunfu/.sea.nvim) - 具有漂亮 UI 和一些有用功能（番茄钟、窗口编号）的模块化 NeoVim 配置.
- [shaeinst/roshnivim](https://github.com/shaeinst/roshnivim) - Roshnivim，可以称为neovim 的发行版，是一个预定义的配置，因此您不需要1000 小时来将neovim 设置为IDE.

### Keybinding

- [AckslD/nvim-whichkey-setup.lua](https://github.com/AckslD/nvim-whichkey-setup.lua) - 包装 vim-which-key 的插件以简化 Lua 中的设置.
- [folke/which-key.nvim](https://github.com/folke/which-key.nvim) - Neovim 插件，显示一个弹出窗口，其中包含您开始输入的命令的可能键绑定.
- [Iron-E/nvim-cartographer](https://github.com/Iron-E/nvim-cartographer) - Lua 环境更方便的`:map`ping 语法.
- [b0o/mapx.nvim](https://github.com/b0o/mapx.nvim)  - 一个更简单的键映射 API，它模仿 Neovim 的 `:map` 系列命令. 与 which-key.nvim 集成.
- [LionC/nest.nvim](https://github.com/LionC/nest.nvim)  - Lua 实用程序使用级联树简洁地映射键. 还允许将 Lua 函数绑定到键.
- [LinArcX/telescope-command-palette.nvim](https://github.com/LinArcX/telescope-command-palette.nvim) - Lua plugin to create key-bindings and watch them with telescope.

### Tmux

- [aserowy/tmux.nvim](https://github.com/aserowy/tmux.nvim) - Neovim 的 Tmux 集成具有窗格移动和在 Neovim 内调整大小的功能.
- [danielpieper/telescope-tmuxinator.nvim](https://github.com/danielpieper/telescope-tmuxinator.nvim) - Integration for tmuxinator with telescope.nvim.
- [hkupty/nvimux](https://github.com/hkupty/nvimux) - Neovim 作为 tmux 的替代品.
- [numToStr/Navigator.nvim](https://github.com/numToStr/Navigator.nvim) - 在 Neovim 拆分和 Tmux 窗格之间平滑导航.

### Remote Development

- [chipsenkbeil/distant.nvim](https://github.com/chipsenkbeil/distant.nvim) - Edit files, run programs, and work with LSP on a remote machine from the comfort of your local environment.
- [jamestthompson3/nvim-remote-containers](https://github.com/jamestthompson3/nvim-remote-containers) - Develop inside docker containers, just like VSCode.

### Split and Window

- [henriquehbr/ataraxis.lua](https://github.com/henriquehbr/ataraxis.lua) - 一种用于提高 Neovim 代码可读性的禅宗模式.
- [gitlab.com/yorickpeterse/nvim-window](https://gitlab.com/yorickpeterse/nvim-window) - 在 Neovim 窗口之间轻松跳转.
- [sindrets/winshift.nvim](https://github.com/sindrets/winshift.nvim) - 轻松重新排列您的窗户.
- [beauwilliams/focus.nvim](https://github.com/beauwilliams/focus.nvim)  - 用 Lua 编写的 Neovim 的自动对焦和自动调整分割/窗口大小！  Vim 在类固醇上分裂.
- [luukvbaal/stabilize.nvim](https://github.com/luukvbaal/stabilize.nvim) - 窗口打开/关闭事件的稳定窗口内容.

## External

这些工具在 Neovim 外部使用以增强体验.

### Version Manager

- [NTBBloodbath/nvenv](https://github.com/NTBBloodbath/nvenv) - 一个轻量级且速度极快的 Neovim 版本管理器.
- [shohi/neva](https://github.com/shohi/neva) - A Neovim version manager written in Lua.

### Boilerplate

- [gennaro-tedesco/boilit](https://github.com/gennaro-tedesco/boilit) - 为 Neovim 插件创建样板结构.

## Vim

- [Vimawesome](https://vimawesome.com/) - 展示 vim 的各种插件，并有一个 [neovim tag](https://vimawesome.com/?q=tag:neovim) for other plugins targeting Neovim.
- [awesome-vim](https://github.com/akrawchyk/awesome-vim#tools) - Short list of vim plugins and helpful guides.

## Resource

- [Neovimcraft](https://neovimcraft.com) - A site dedicated to searching for Neovim specific plugins and guides for building plugins in Lua.
