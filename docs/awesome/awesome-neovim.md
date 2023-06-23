<div class="github-widget" data-repo="rockerBOO/awesome-neovim"></div>
<!-- lint ignore awesome-git-repo-age -->

<img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" />

## Awesome Neovim [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- Uncomment the awesome badge when the repository is added to awesome main list.
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
-->

 &gt; 很棒的 Neovim 插件集合. 主要针对 Neovim 特定功能.

[Neovim](https://neovim.io/) 是一个基于 Vim 的文本编辑器，旨在提高可扩展性和可用性，以鼓励新的应用程序和贡献.



## Wishlist

有插件可以解决的问题吗？ 将其添加到 [nvim-lua wishlist](https://github.com/nvim-lua/wishlist).

## UI

Neovim 支持多种 UI.
您可以在以下列表中找到它们 [Neovim wiki](https://github.com/neovim/neovim/wiki/Related-projects#gui)

## Starter Templates

- [tokiory/neovim-boilerplate](https://github.com/tokiory/neovim-boilerplate) - 用于进行新配置的入门样板.
- [frans-johansson/lazy-nvim-starter](https://github.com/frans-johansson/lazy-nvim-starter) - 带有惰性插件管理器的入门样板.

## Plugin

### Plugin Manager

- [wbthomason/packer.nvim](https://github.com/wbthomason/packer.nvim)  - 受使用包启发的插件管理器. 使用本机包，支持 Luarocks 依赖项，用 Lua 编写，允许表达配置.
- [savq/paq-nvim](https://github.com/savq/paq-nvim) - 用 Lua 编写的 Neovim 包管理器.
- [NTBBloodbath/cheovim](https://github.com/NTBBloodbath/cheovim)  - 用 Lua 编写的 Neovim 配置切换器. 灵感来自化学.
- [chiyadev/dep](https://github.com/chiyadev/dep) - An alternative to packer.nvim. It was built to be even better and easier to use. Context can be found [here](https://chiya.dev/posts/2021-11-27-why-package-manager).
- [folke/lazy.nvim](https://github.com/folke/lazy.nvim) - 一个现代的插件管理器，具有图形界面、异步执行、锁定文件等.

### LSP

#### (requires Neovim 0.5)

- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - LSP 客户端的快速启动配置.
- [nvim-lua/lsp-status.nvim](https://github.com/nvim-lua/lsp-status.nvim) - 这是一个插件/库，用于从内置 LSP 客户端生成状态行组件.
- [RishabhRD/nvim-lsputils](https://github.com/RishabhRD/nvim-lsputils) - nvim-lsp 操作的更好默认值.
- [glepnir/lspsaga.nvim](https://github.com/glepnir/lspsaga.nvim) - 基于 Neovim 内置 LSP 的轻量级 LSP 插件，具有高性能的 UI.
- [kosayoda/nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb) - 只要“textDocument/codeAction”在当前光标位置可用，该插件就会在符号栏中显示一个灯泡.
- [onsails/lspkind.nvim](https://github.com/onsails/lspkind.nvim) - 该插件将类似 vscode 的图标添加到 Neovim LSP 补全中.
- [ojroques/nvim-lspfuzzy](https://github.com/ojroques/nvim-lspfuzzy) - 一个让 LSP 客户端使用 FZF 的小插件.
- [gfanto/fzf-lsp.nvim](https://github.com/gfanto/fzf-lsp.nvim) - 为 LSP 内置的 Neovim 启用 FZF 模糊搜索功能.
- [ray-x/lsp_signature.nvim](https://github.com/ray-x/lsp_signature.nvim) - 输入时的 LSP 签名提示.
- [smjonas/inc-rename.nvim](https://github.com/smjonas/inc-rename.nvim) - 提供基于 Neovim 的命令预览功能的增量 LSP 重命名命令.
- [rmagatti/goto-preview](https://github.com/rmagatti/goto-preview) - 在浮动窗口中预览本机 LSP 的 goto 定义调用.
- [jubnzv/virtual-types.nvim](https://github.com/jubnzv/virtual-types.nvim) - 将类型注释显示为虚拟文本.
- [jose-elias-alvarez/typescript.nvim](https://github.com/jose-elias-alvarez/typescript.nvim) - 用于改善 Neovim 内置 LSP 客户端的 TypeScript 开发体验的实用程序.
- [ray-x/navigator.lua](https://github.com/ray-x/navigator.lua)  - 快速学习现有代码并轻松浏览代码. 一把瑞士军刀让探索 LSP 和 Treesitter 符号成为一种乐趣.
- [simrat39/symbols-outline.nvim](https://github.com/simrat39/symbols-outline.nvim)  - 使用语言服务器协议的符号树状视图. 支持所有您喜欢的语言.
- [stevearc/aerial.nvim](https://github.com/stevearc/aerial.nvim) - 用于浏览和快速导航的代码大纲窗口.
- [SmiteshP/nvim-navbuddy](https://github.com/SmiteshP/nvim-navbuddy) - 一个简单的弹出显示，使用 LSP 提供面包屑等导航功能.
- [tamago324/nlsp-settings.nvim](https://github.com/tamago324/nlsp-settings.nvim) - 使用 JSON 或 YAML 文件设置 LSP.
- [jose-elias-alvarez/null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim) - 使用 Neovim 作为语言服务器，通过 Lua 注入 LSP 诊断、代码操作等.
- [jakewvincent/texmagic.nvim](https://github.com/jakewvincent/texmagic.nvim) - 通过定义任意数量的自定义 LaTeX 构建引擎并使用神奇注释选择它们，增强 Texlab 的 lspconfig 设置.
- [nanotee/nvim-lsp-basics](https://github.com/nanotee/nvim-lsp-basics) - LSP 功能的基本包装器.
- [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu) - 代码操作的浮动弹出菜单，用于显示代码操作信息和差异预览.
- [mfussenegger/nvim-lint](https://github.com/mfussenegger/nvim-lint) - 异步 linter 插件，对内置语言服务器协议支持的补充.
- [b0o/SchemaStore.nvim](https://github.com/b0o/SchemaStore.nvim) - 提供对 [SchemaStore](https://github.com/SchemaStore/schemastore) 目录.
- [ldelossa/litee.nvim](https://github.com/ldelossa/litee.nvim) - Neovim 缺少 IDE 功能.
- [j-hui/fidget.nvim](https://github.com/j-hui/fidget.nvim) - 用于 LSP 进度的独立 UI.
- [scalameta/nvim-metals](https://github.com/scalameta/nvim-metals) - Metals 的 Neovim 插件，Scala 语言服务器，使用 Neovim 的内置 LSP.
- [junnplus/nvim-lsp-setup](https://github.com/Junnplus/nvim-lsp-setup) - nvim-lspconfig 和 nvim-lsp-installer 的简单包装器，可轻松设置 LSP 服务器.
- [amrbashir/nvim-docs-view](https://github.com/amrbashir/nvim-docs-view) - 在侧面板中显示 LSP 悬停文档.
- [mfussenegger/nvim-jdtls](https://github.com/mfussenegger/nvim-jdtls) - 对 eclipse.jdt.ls 的内置 LSP 支持的扩展.
- [Kasama/nvim-custom-diagnostic-highlight](https://github.com/Kasama/nvim-custom-diagnostic-highlight) - 内联诊断弹出突出显示与 coc-nvim 非常相似，但基于“vim.diagnostic”.
- [MrcJkb/haskell-tools.nvim](https://github.com/MrcJkb/haskell-tools.nvim) - Neovim 与 Haskell 开发工具（如 haskell-language-server 和 Hoogle）的无缝集成.
- [ranjithshegde/ccls.nvim](https://github.com/ranjithshegde/ccls.nvim) - 使用 ccls LSP 的不合规格扩展并浏览 AST.
- [idanarye/nvim-buffls](https://github.com/idanarye/nvim-buffls) - 将 LSP 功能添加到特定 Neovim 缓冲区.
- [DNLHC/glance.nvim](https://github.com/DNLHC/glance.nvim) - 用于预览、导航和编辑 LSP 位置的漂亮窗口.
- [linrongbin16/lsp-progress.nvim](https://github.com/linrongbin16/lsp-progress.nvim) - Neovim 的另一个 lsp 进度状态.
- [jinzhongjia/LspUI.nvim](https://github.com/jinzhongjia/LspUI.nvim) - 包装 LSP 操作的现代且有用的 UI.
- [VidocqH/lsp-lens.nvim](https://github.com/VidocqH/lsp-lens.nvim) - 在函数定义上方显示函数引用，如 IDEA codelens.
- [chrisgrieser/nvim-dr-lsp](https://github.com/chrisgrieser/nvim-dr-lsp) - 状态行组件显示LSP定义的数量和光标下令牌的引用.

##### LSP Installer

- [anott03/nvim-lspinstall](https://github.com/anott03/nvim-lspinstall) - 易于安装语言服务器.
- [alexaandru/nvim-lspupdate](https://github.com/alexaandru/nvim-lspupdate) - 更新已安装（或自动安装，如果缺少）LSP 服务器.
- [williamboman/mason.nvim](https://github.com/williamboman/mason.nvim)  - 可在 Neovim 运行的任何地方运行的便携式包管理器. 轻松安装和管理 LSP 服务器、DAP 服务器、linter 和格式化程序.

##### Diagnostics

- [andrewferrier/textobj-diagnostic](https://github.com/andrewferrier/textobj-diagnostic.nvim) - 用于诊断的文本对象（例如由 LSP 服务器生成的文本对象）.
- [~whynothugo/lsp_lines.nvim](https://git.sr.ht/~whynothugo/lsp_lines.nvim) - 使用真实代码行之上的虚拟行呈现诊断.
- [onsails/diaglist.nvim](https://github.com/onsails/diaglist.nvim) - Quickfix 中的实时渲染工作区诊断，loclist 中的缓冲区诊断.
- [folke/trouble.nvim](https://github.com/folke/trouble.nvim) - 一个漂亮的诊断列表，可以帮助您解决代码引起的所有问题.
- [folke/lsp-colors.nvim](https://github.com/folke/lsp-colors.nvim) - 一个插件，可为尚不支持内置 LSP 客户端的配色方案添加缺失的 LSP 诊断突出显示组.

### Completion

- [ms-jpq/coq_nvim](https://github.com/ms-jpq/coq_nvim)  - 快得像他妈的 Neovim 一样完成.  SQLite，并发调度程序，数百小时的优化.
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp)  - 用 Lua 编写的补全插件. 新版本的 nvim-compe.
  - [lukas-reineke/cmp-under-comparator](https://github.com/lukas-reineke/cmp-under-comparator) - nvim-cmp 函数可实现更好的排序.
- [echasnovski/mini.nvim#mini.completion](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-completion.md)  - 用于异步两阶段完成的“mini.nvim”模块. 支持显示完成项信息和独立函数签名.
- [noib3/nvim-compleet](https://github.com/noib3/nvim-compleet) - 用 Rust 编写的 Neovim 自动完成框架.
- [vigoux/complementree.nvim](https://github.com/vigoux/complementree.nvim) - 基于树守护者和功能编程接口的轻型同步完成插件.
- [simrat39/rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - 使用 Neovim 的内置 LSP 更好地开发 Rust 的工具.
- [zbirenbaum/copilot.lua](https://github.com/zbirenbaum/copilot.lua) - 功能齐全的 Lua 替代品 [GitHub/copilot.vim](https://github.com/github/copilot.vim).

### Programming Languages Support

- [Julian/lean.nvim](https://github.com/Julian/lean.nvim) - Neovim 支持 [Lean Theorem Prover](https://leanprover.github.io/).
- [akinsho/flutter-tools.nvim](https://github.com/akinsho/flutter-tools.nvim) - 使用原生 LSP 构建 Flutter 和 Dart 应用程序.
- [gbprod/phpactor.nvim](https://github.com/gbprod/phpactor.nvim) - Lua 版本的 Phpactor Vim 插件可以利用最新的 Neovim 功能.
- [brendalf/mix.nvim](https://github.com/brendalf/mix.nvim) - Mix（来自 Elixir）包装插件.
- [AckslD/swenv.nvim](https://github.com/AckslD/swenv.nvim) - 无需重新启动即可快速切换 Python 虚拟环境的小插件.
- [gennaro-tedesco/nvim-jqx](https://github.com/gennaro-tedesco/nvim-jqx) - JSON 文件的交互界面.
- [nanotee/sqls.nvim](https://github.com/nanotee/sqls.nvim) - SQL数据库连接插件+LSP客户端.
- [dmmulroy/tsc.nvim](https://github.com/dmmulroy/tsc.nvim) - 使用 TypeScript 编译器 (TSC) 进行异步项目范围的 TypeScript 类型检查，并将结果加载到快速修复列表中.

#### Golang

- [ray-x/go.nvim](https://github.com/ray-x/go.nvim) - 基于 lsp 和 Treesitter 的 Golang 插件.
- [crusj/structrue-go.nvim](https://github.com/crusj/structrue-go.nvim) - 更好地结构化显示 Golang 符号信息.
- [crispgm/nvim-go](https://github.com/crispgm/nvim-go) - Golang 开发插件的最小实现.
- [edolphin-ydf/goimpl.nvim](https://github.com/edolphin-ydf/goimpl.nvim) - 为类型生成接口存根.
- [olexsmir/gopher.nvim](https://github.com/olexsmir/gopher.nvim/) - 使 Golang 开发变得最简单的插件.
- [rafaelsq/nvim-goc.lua](https://github.com/rafaelsq/nvim-goc.lua) - 使用 Golang 代码覆盖率突出显示您的缓冲区.
- [crusj/hierarchy-tree-go.nvim](https://github.com/crusj/hierarchy-tree-go.nvim) - Golang 的 Neovim 插件，callHierarchy UI 树.

#### YAML

- [someone-stole-my-name/yaml-companion.nvim](https://github.com/someone-stole-my-name/yaml-companion.nvim) - 获取、设置和自动检测缓冲区中的 YAML 架构.
- [cuducos/yaml.nvim](https://github.com/cuducos/yaml.nvim) - 处理 YAML 文件的实用程序.

#### Web Development

- [NTBBloodbath/rest.nvim](https://github.com/NTBBloodbath/rest.nvim) - 用 Lua 编写的快速 Neovim HTTP 客户端.
- [ray-x/web-tools.nvim](https://github.com/ray-x/web-tools.nvim) - 启动本地开发服务器，具有静态和动态页面的实时重新加载功能，以及使用 LSP 重命名 HTML 和 CSS 标签.

#### Markdown and LaTeX

- [ellisonleao/glow.nvim](https://github.com/ellisonleao/glow.nvim) - 使用发光进行 Markdown 预览.
- [iamcco/markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim) - 通过同步滚动和灵活的配置在现代浏览器上预览 Markdown.
- [davidgranstrom/nvim-markdown-preview](https://github.com/davidgranstrom/nvim-markdown-preview) - 通过 Neovim 的作业控制 API 使用 pandoc 和 live-server 在浏览器中进行 Markdown 预览.
- [jghauser/auto-pandoc.nvim](https://github.com/jghauser/auto-pandoc.nvim) - 利用 yaml 块轻松进行 pandoc 转换.
- [jghauser/follow-md-links.nvim](https://github.com/jghauser/follow-md-links.nvim) - 按 Enter 键可跟踪内部 Markdown 链接.
- [jubnzv/mdeval.nvim](https://github.com/jubnzv/mdeval.nvim) - 评估 Markdown 文档中的代码块.
- [kdheepak/panvimdoc](https://github.com/kdheepak/panvimdoc) - pandoc 到 vimdoc GitHub 操作.
- [frabjous/knap](https://github.com/frabjous/knap) - 用于为 Markdown、LaTeX 和其他文档创建自动更新预览的插件.
- [jbyuki/carrot.nvim](https://github.com/jbyuki/carrot.nvim) - Markdown 评估器 Lua 代码块.
- [AckslD/nvim-FeMaco.lua](https://github.com/AckslD/nvim-FeMaco.lua) - 促进您的 Fenced Markdown 代码块编辑.
- [NFrid/markdown-togglecheck](https://github.com/NFrid/markdown-togglecheck) - 简单的 Neovim 插件，用于使用 Treesitter 切换复选框.
- [toppair/peek.nvim](https://github.com/toppair/peek.nvim) - 在网络视图窗口中预览 Markdown.
- [yaocccc/nvim-hl-mdcodeblock.lua](https://github.com/yaocccc/nvim-hl-mdcodeblock.lua) - 使用 Tree-sitter 突出显示 Markdown 代码块.
- [kiran94/edit-markdown-table.nvim](https://github.com/kiran94/edit-markdown-table.nvim) - 使用 Tree-sitter 编辑 Markdown 表.

### Language

- [potamides/pantran.nvim](https://github.com/potamides/pantran.nvim) - 使用交互式翻译窗口翻译您的文本.
- [niuiic/translate.nvim](https://github.com/niuiic/translate.nvim) - 通过 shell 命令调用任何翻译引擎.

### Syntax

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Treesitter 配置和抽象层.
- [nvim-treesitter/nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - 使用树保姆查询创建您自己的文本对象.
- [RRethy/nvim-treesitter-textsubjects](https://github.com/RRethy/nvim-treesitter-textsubjects) - 位置和语法感知文本对象_做你的意思_.
- [kylechui/nvim-surround](https://github.com/kylechui/nvim-surround) - 用于添加/更改/删除周围分隔符对的插件.
- [echasnovski/mini.nvim#mini.surround](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-surround.md)  - 用于处理文本环境的“mini.nvim”模块（添加、删除、替换、查找、突出显示）. 支持点重复、不同的搜索方法、“上一个”/“下一个”扩展映射、树保护集成等.
- [m-demare/hlargs.nvim](https://github.com/m-demare/hlargs.nvim) - 使用 Treesitter 突出显示参数的定义和用法.
- [LhKipp/nvim-nu](https://github.com/LhKipp/nvim-nu) - 对 nushell 语言的基本编辑器支持.
- [desdic/agrolens.nvim](https://github.com/desdic/agrolens.nvim) - 使用望远镜通过树保姆节点进行导航.

### Snippet

- [norcalli/snippets.nvim](https://github.com/norcalli/snippets.nvim) - Lua 中的片段.
- [L3MON4D3/LuaSnip](https://github.com/L3MON4D3/LuaSnip) - 用 Lua 编写的片段引擎.
- [smjonas/snippet-converter.nvim](https://github.com/smjonas/snippet-converter.nvim) - 在最常见的代码片段格式之间转换代码片段，并使用几行 Lua 代码对其进行修改.
- [dcampos/nvim-snippy](https://github.com/dcampos/nvim-snippy) - 用 Lua 编写的片段插件，支持 [vim-snippets](https://github.com/honza/vim-snippets).
- [ellisonleao/carbon-now.nvim](https://github.com/ellisonleao/carbon-now.nvim) - 直接从 Neovim 创建漂亮的代码片段.
- [TobinPalmer/rayso.nvim](https://github.com/TobinPalmer/rayso.nvim) - 使用 Neovim 创建代码片段 [ray.so](https://ray.so).

### Register

- [gennaro-tedesco/nvim-peekup](https://github.com/gennaro-tedesco/nvim-peekup) - 与 Vim 寄存器动态交互.
- [tversteeg/registers.nvim](https://github.com/tversteeg/registers.nvim) - Vim 寄存器的非侵入式最小预览.
- [acksld/nvim-neoclip.lua](https://github.com/AckslD/nvim-neoclip.lua) - Clipboard manager Neovim plugin with telescope integration.
- [tenxsoydev/karen-yank.nvim](https://github.com/tenxsoydev/karen-yank.nvim) - 通过删除、剪切和复制映射进行更有意的寄存器处理.

### Marks

- [cbochs/grapple.nvim](https://github.com/cbochs/grapple.nvim) - 提供标记、光标跟踪以及对重要项目文件的即时导航.
- [chentoast/marks.nvim](https://github.com/chentoast/marks.nvim) - 更好的用户查看 Vim 标记并与之交互的体验.
- [ThePrimeagen/harpoon](https://github.com/ThePrimeagen/harpoon) - 每个项目的自动更新和可编辑标记实用程序，用于快速文件导航.
- [ofirgall/open.nvim](https://github.com/ofirgall/open.nvim) - 使用自定义开启器打开当前单词，例如 GitHub 速记.
- [LeonHeidelbach/trailblazer.nvim](https://github.com/LeonHeidelbach/trailblazer.nvim) - TrailBlazer 引入了基于堆栈的标记系统，该系统使用项目范围标记实现全新的动态且超快速的工作流程.
- [tomasky/bookmarks.nvim](https://github.com/tomasky/bookmarks.nvim) - 带有全局文件存储的书签，用 Lua 编写.

### Search

- [kevinhwang91/nvim-hlslens](https://github.com/kevinhwang91/nvim-hlslens) - 帮助您更好地浏览搜索到的信息，无缝跳转匹配的实例.
- [rktjmp/highlight-current-n.nvim](https://github.com/rktjmp/highlight-current-n.nvim)  - 突出显示当前/，？ 或 \* 在按 n 或 N 时在光标下匹配，然后退出.
- [gaborvecsei/memento.nvim](https://github.com/gaborvecsei/memento.nvim)  - 缓冲区关闭后跟踪您访问的文件历史记录. 更轻松地重新打开文件.
- [ray-x/sad.nvim](https://github.com/ray-x/sad.nvim)  - neovim 中的太空时代 seD. 批处理文件编辑工具，包装器 [sad](https://github.com/ms-jpq/sad)
- [s1n7ax/nvim-search-and-replace](https://github.com/s1n7ax/nvim-search-and-replace) - 从当前工作目录同时搜索和替换多个文件.
- [roobert/search-replace.nvim](https://github.com/roobert/search-replace.nvim) - 为本机搜索和替换体验带来更好的功能.
- [AckslD/muren.nvim](https://github.com/AckslD/muren.nvim/) - 通过交互式用户界面进行多次替换.

### Fuzzy Finder

- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim 是一个高度 [extendable](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) 列表上的模糊查找器. 基于 Neovim 核心的最新强大功能构建.  Telescope 以模块化为中心，可以轻松定制.
- [vijaymarupudi/nvim-fzf](https://github.com/vijaymarupudi/nvim-fzf)  - 用于使用 FZF 的 Lua API (Neovim &gt;= 0.5). 允许 UI 速度和可用性完全异步.
- [camspiers/snap](https://github.com/camspiers/snap)  - 可扩展的模糊查找器. 与 Telescope 类似，并针对性能进行了优化，尤其是在大型代码库中进行 grep 时.
- [ibhagwan/fzf-lua](https://github.com/ibhagwan/fzf-lua)  - Lua 版本的“fzf.vim”，高性能且完全异步，支持“nvim-web-devicons”、git 指示器、LSP、quickfix/位置列表等. 还支持 [`skim`](https://github.com/lotabout/skim) 作为它的 fzf 二进制文件.
- [jvgrootveld/telescope-zoxide](https://github.com/jvgrootveld/telescope-zoxide) - 望远镜集成 [zoxide](https://github.com/ajeetdsouza/zoxide)，一个跟踪您的使用情况的智能目录选择器.
- [echasnovski/mini.nvim#mini.fuzzy](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-fuzzy.md) - `mini.nvim` 模块，具有执行一个字符串与其他字符串的模糊匹配以及快速望远镜排序器的功能.
- [axkirillov/easypick.nvim](https://github.com/axkirillov/easypick.nvim) - Easypick 可让您通过任意控制台命令轻松创建 Telescope 选择器.

### File Explorer

- [kyazdani42/nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - 一个简单快速的文件浏览器树.
- [luukvbaal/nnn.nvim](https://github.com/luukvbaal/nnn.nvim) - 文件浏览器由 [nnn](https://github.com/jarun/nnn) 和卢阿.
- [tamago324/lir.nvim](https://github.com/tamago324/lir.nvim) - 简单的文件浏览器.
- [TimUntersberger/neofs](https://github.com/TimUntersberger/neofs) - 用 Lua 编写的文件管理器.
- [kevinhwang91/rnvimr](https://github.com/kevinhwang91/rnvimr) - 一个简单但令人惊叹的文件浏览器.
- [Xuyuanp/yanil](https://github.com/Xuyuanp/yanil) - Lua 中的另一个书呆子树.
- [ms-jpq/chadtree](https://github.com/ms-jpq/chadtree)  - 文件管理器. 比 NERDTree 更好.
- [is0n/fm-nvim](https://github.com/is0n/fm-nvim) - Neovim 插件可让您使用您最喜欢的终端文件管理器（和模糊查找器）.
- [nvim-neo-tree/neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim) - Neo-tree 是一个 Neovim 插件，可以以任何适合您的风格浏览文件系统和其他树状结构，包括侧边栏、浮动窗口、netrw 分割样式或同时使用所有样式.
- [elihunter173/dirbuf.nvim](https://github.com/elihunter173/dirbuf.nvim) - 一个文件管理器，可让您像编辑文本一样编辑文件系统.
- [theblob42/drex.nvim](https://github.com/TheBlob42/drex.nvim) - 用 Lua 编写的简单且可配置的文件浏览器.
- [SidOfc/carbon.nvim](https://github.com/SidOfc/carbon.nvim) - 用 Lua 编写的简单目录树查看器.
- [dinhhuy258/sfm.nvim](https://github.com/dinhhuy258/sfm.nvim) - Nvim-tree 的替代方案，设计为可扩展且简约.
- [kiran94/s3edit.nvim](https://github.com/kiran94/s3edit.nvim) - 直接从 Neovim 编辑来自 Amazon S3 的文件.
- [stevearc/oil.nvim](https://github.com/stevearc/oil.nvim) - 像缓冲区一样编辑文件系统.
- [kelly-lin/ranger.nvim](https://github.com/kelly-lin/ranger.nvim) - [Ranger](https://github.com/ranger/ranger) neovim 的集成.
- [echasnovski/mini.nvim#mini.files](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-files.md)  - `mini.nvim` 模块提供文件浏览器，具有能够通过编辑文本来操作文件系统的列视图. 可以在目录内部和目录之间创建/删除/重命名/复制/移动文件/目录.

### Project

- [pluffie/neoproj](https://github.com/pluffie/neoproj) - 小而强大的项目（和会话）经理.
- [shaeinst/penvim](https://github.com/shaeinst/penvim) - 项目的根目录和文档缩进检测器以及基于项目的配置加载器.
- [nyngwang/NeoRoot.lua](https://github.com/nyngwang/NeoRoot.lua) - 将当前工作目录更改为光标所在的缓冲区，并尝试向上移动 2 级，但在遇到您定义的项目根目录之一后停止.
- [windwp/nvim-projectconfig](https://github.com/windwp/nvim-projectconfig) - 根据项目目录加载 Neovim 配置.
- [windwp/nvim-spectre](https://github.com/windwp/nvim-spectre) - 搜索和替换面板.
- [ahmedkhalf/project.nvim](https://github.com/ahmedkhalf/project.nvim) - 一款一体化 Neovim 插件，提供卓越的项目管理.
- [klen/nvim-config-local](https://github.com/klen/nvim-config-local) - 从工作目录安全加载本地配置文件.
- [cljoly/telescope-repo.nvim](https://cj.rs/telescope-repo-nvim/) - 望远镜选择器可跳转到文件系统上的任何存储库（git 或其他）.
- [MunifTanjim/exrc.nvim](https://github.com/MunifTanjim/exrc.nvim) - 安全项目本地配置.
- [otavioschwanck/telescope-alternate.nvim](https://github.com/otavioschwanck/telescope-alternate.nvim) - 使用望远镜在常见文件之间交替.
- [natecraddock/workspaces.nvim](https://github.com/natecraddock/workspaces.nvim) - 管理工作区目录.
- [gnikdroy/projections.nvim](https://github.com/gnikdroy/projections.nvim) - 小型项目+会话管理器.
- [nyngwang/suave.lua](https://github.com/nyngwang/suave.lua) - 多选项卡项目会话自动化.
- [desdic/telescope-rooter.nvim](https://github.com/desdic/telescope-rooter.nvim) - 确保始终从项目/根目录启动望远镜（并且仅启动望远镜）.
- [jinzhongjia/PS_manager.nvim](https://github.com/jinzhongjia/PS_manager.nvim) - 多项目管理，自动切换密码.

### Color

- [NvChad/nvim-colorizer.lua](https://github.com/NvChad/nvim-colorizer.lua) - 高性能彩色荧光笔，没有外部依赖性！.
- [sunjon/Shade.nvim](https://github.com/sunjon/Shade.nvim) - Shade 是一个 Neovim 插件，可以使非活动窗口变暗，使活动窗口一目了然.
- [winston0410/range-highlight.nvim](https://github.com/winston0410/range-highlight.nvim) - 一个非常轻量级的插件（〜120loc），突出显示您在命令行中输入的范围.
- [xiyaowong/nvim-transparent](https://github.com/xiyaowong/nvim-transparent) - 让你的 Neovim 透明.
- [folke/twilight.nvim](https://github.com/folke/twilight.nvim) - 使用 TreeSitter 调暗您正在编辑的代码的非活动部分.
- [koenverburg/peepsight.nvim](https://github.com/koenverburg/peepsight.nvim) - 仅聚焦光标所在的功能.
- [uga-rosa/ccc.nvim](https://github.com/uga-rosa/ccc.nvim) - 超级强大的颜色选择器/着色器插件.
- [ziontee113/color-picker.nvim](https://github.com/ziontee113/color-picker.nvim) - 允许用户在 Neovim 中选择和修改 RGB/HSL/HEX 颜色的插件.
- [lcheylus/overlength.nvim](https://github.com/lcheylus/overlength.nvim) - 一个小插件，用于突出显示太长的行.
- [brenoprata10/nvim-highlight-colors](https://github.com/brenoprata10/nvim-highlight-colors) - 使用 Neovim 突出显示颜色的插件.
- [nvim-colortils/colortils.nvim](https://github.com/nvim-colortils/colortils.nvim) - 一个插件，提供在 Neovim 内处理颜色（选择器、转换）的实用程序.
- [Mr-LLLLL/interestingwords.nvim](https://github.com/Mr-LLLLL/interestingwords.nvim) - 同时突出显示多个单词并平滑滚动导航光标下的单词，在虚拟文本中显示搜索计数.
- [echasnovski/mini.nvim#mini.hipatterns](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-hipatterns.md)  - `mini.nvim` 模块，用于使用可配置的荧光笔突出显示文本中的模式. 与可配置的去抖延迟异步工作.

### Colorscheme

#### Tree-sitter Supported Colorscheme

 Tree-sitter 是 Neovim 0.5 中引入的一个新系统，它可以将您的代码增量解析为一个可以工作的树，即使语法中有错误也是如此. 这些配色方案专门为树上高亮组设置了颜色.  Vim 颜色方案将与开箱即用的新组一起使用.

- [shaeinst/roshnivim-cs](https://github.com/shaeinst/roshnivim-cs) - 用 Lua 编写的 Colorscheme，专为 roshnivim 制作，并支持 Tree-sitter.
- [rafamadriz/neon](https://github.com/rafamadriz/neon)  - 可定制的配色方案，具有出色的斜体和粗体支持、深色和浅色变体. 与 Tree-sitter 一起使用且美观.
- [tomasiser/vim-code-dark](https://github.com/tomasiser/vim-code-dark) - 深色配色方案很大程度上受到 Visual Studio Code 的 Dark+ 方案外观的启发.
- [Mofiqul/vscode.nvim](https://github.com/Mofiqul/vscode.nvim) - vim-code-dark colorcheme 的 Lua 端口，带有 vscode 浅色和深色主题.
- [marko-cerovac/material.nvim](https://github.com/marko-cerovac/material.nvim) - Material.nvim 是一个用 Lua 编写并基于材质调色板的高度可配置的配色方案.
- [bluz71/vim-nightfly-colors](https://github.com/bluz71/vim-nightfly-colors) - 黑暗的午夜配色方案，具有现代 Neovim 支持，包括 Tree-sitter.
- [bluz71/vim-moonfly-colors](https://github.com/bluz71/vim-moonfly-colors) - 深木炭配色方案，具有现代 Neovim 支持，包括 Tree-sitter.
- [ChristianChiarulli/nvcode-color-schemes.vim](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - Nvcode、onedark、nord 颜色方案，支持 Tree-sitter.
- [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - 用 Lua 编写的干净、深色和浅色 Neovim 主题，支持 LSP、Tree-sitter 和大量插件.
- [sainnhe/sonokai](https://github.com/sainnhe/sonokai) - 基于 Monokai Pro 的高对比度和鲜艳的配色方案.
- [nyoom-engineering/oxocarbon.nvim](https://github.com/nyoom-engineering/oxocarbon.nvim) - 受 IBM Carbon 启发，用茴香编写的深色和浅色 Neovim 主题.
- [kyazdani42/blue-moon](https://github.com/kyazdani42/blue-moon) - 源自palenight 和carbonight 的深色配色方案.
- [mhartington/oceanic-next](https://github.com/mhartington/oceanic-next) - 海洋下一个主题.
- [glepnir/zephyr-nvim](https://github.com/glepnir/zephyr-nvim) - 带有树保姆支持的深色配色方案.
- [rockerBOO/boo-colorscheme-nvim](https://github.com/rockerBOO/boo-colorscheme-nvim) - 手工制作的支持 LSP、Tree-sitter 的配色方案.
- [jim-at-jibba/ariake-vim-colors](https://github.com/jim-at-jibba/ariake-vim-colors)  - 伟大的 Atom 主题的移植. 黑暗和光明，有树保姆的支持.
- [Th3Whit3Wolf/onebuddy](https://github.com/Th3Whit3Wolf/onebuddy) - 光明与黑暗原子同一个主题.
- [ishan9299/modus-theme-vim](https://github.com/ishan9299/modus-theme-vim) - 这是 Protesilaos Stavrou 为 emacs 开发的配色方案.
- [sainnhe/edge](https://github.com/sainnhe/edge) - 干净优雅的配色方案，灵感来自 Atom One 和 Material.
- [theniceboy/nvim-deus](https://github.com/theniceboy/nvim-deus) - Vim-deus 与 Tree-sitter 支持.
- [bkegley/gloombuddy](https://github.com/bkegley/gloombuddy) - 忧郁的主题.
- [Th3Whit3Wolf/one-nvim](https://github.com/Th3Whit3Wolf/one-nvim) - 受 Atom One 启发的深色和浅色配色方案.
- [PHSix/nvim-hybrid](https://github.com/PHSix/nvim-hybrid) - 用 Lua 编写的 Neovim 配色方案.
- [Th3Whit3Wolf/space-nvim](https://github.com/Th3Whit3Wolf/space-nvim) - 受 spacemacs 启发的深色和浅色配色方案.
- [yonlu/omni.vim](https://github.com/yonlu/omni.vim) - Omni color scheme for Vim.
- [ray-x/aurora](https://github.com/ray-x/aurora) - 24 位深色主题，支持 Tree-sitter 和 LSP.
- [ray-x/starry.nvim](https://github.com/ray-x/starry.nvim) - 现代 Neovim 配色方案的集合：材质、月光、德古拉（血）、monokai、玛丽安娜、翡翠、初夏、午夜蓝、暗太阳能.
- [tanvirtin/monokai.nvim](https://github.com/tanvirtin/monokai.nvim) - 用 Lua 编写的 Monokai 主题.
- [ofirgall/ofirkai.nvim](https://github.com/ofirgall/ofirkai.nvim) - Monokai 主题，旨在感觉像 Sublime Text.
- [savq/melange-nvim](https://github.com/savq/melange-nvim) - 用 Lua 编写的暖色方案，支持各种终端模拟器.
- [RRethy/nvim-base16](https://github.com/RRethy/nvim-base16)  - 用于构建 base16 颜色方案的 Neovim 插件. 包括对 Treesitter 和 LSP 高亮组的支持.
- [fenetikm/falcon](https://github.com/fenetikm/falcon) - 终端、Vim 和朋友的配色方案.
- [andersevenrud/nordic.nvim](https://github.com/andersevenrud/nordic.nvim) - 北欧风格的配色方案.
- [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) - 基于 Nord 调色板的 Neovim 主题.
- [svrana/neosolarized.nvim](https://github.com/svrana/neosolarized.nvim) - 使用 colorbuddy 的深色日光配色方案，可轻松定制.
- [ishan9299/nvim-solarized-lua](https://github.com/ishan9299/nvim-solarized-lua) - Lua 中的曝光配色方案 (Neovim &gt;= 0.5).
- [shaunsingh/moonlight.nvim](https://github.com/shaunsingh/moonlight.nvim) - VSCode 的 Moonlight colorcheme 的端口，用 Lua 编写，内置对本机 LSP、Tree-sitter 和更多插件的支持.
- [navarasu/onedark.nvim](https://github.com/navarasu/onedark.nvim) - 基于 Atom 的 One Dark 主题，用 Lua 编写的 One Dark 主题 (Neovim &gt;= 0.5).
- [lourenci/github-colors](https://github.com/lourenci/github-colors) - GitHub 颜色利用 Tree-sitter 获得 100% 的准确性.
- [sainnhe/gruvbox-material](https://github.com/sainnhe/gruvbox-material) - Gruvbox 修改具有更柔和的对比度和 Tree-sitter 支持.
- [sainnhe/everforest](https://github.com/sainnhe/everforest) - 以绿色为基础的配色方案，旨在温暖、柔和且养眼.
- [neanias/everforest-nvim](https://github.com/neanias/everforest-nvim) - Everforest 配色方案的 Lua 端口.
- [NTBBloodbath/doom-one.nvim](https://github.com/NTBBloodbath/doom-one.nvim) - doom-emacs 的 doom-one 的 Lua 端口.
- [dracula/vim](https://github.com/dracula/vim) - 著名的美丽黑暗动力主题.
- [Mofiqul/dracula.nvim](https://github.com/Mofiqul/dracula.nvim) - 用 Lua 编写的 Neovim 德古拉配色方案.
- [yashguptaz/calvera-dark.nvim](https://github.com/yashguptaz/calvera-dark.nvim) - 一个港口 [VSCode Calvara Dark](https://github.com/saurabhdaware/vscode-calvera-dark) Neovim 主题，支持 Tree-sitter 和许多其他插件.
- [nxvu699134/vn-night.nvim](https://github.com/nxvu699134/vn-night.nvim)  - 用 Lua 编写的深色 Neovim 配色方案. 支持内置LSP和Tree-sitter.
- [adisen99/codeschool.nvim](https://github.com/adisen99/codeschool.nvim) - 用 Lua 编写的 Codeschool colorcheme，具有 Tree-sitter 和内置 lsp 支持.
- [projekt0n/github-nvim-theme](https://github.com/projekt0n/github-nvim-theme)  - 一个 GitHub 主题，kitty，用 Lua 编写的 alacritty. 支持内置LSP和Tree-sitter.
- [kdheepak/monochrome.nvim](https://github.com/kdheepak/monochrome.nvim) - 16 位单色配色方案，使用 hsluv 实现感知上不同的灰色，并支持 Tree-sitter 和其他常用插件.
- [rose-pine/neovim](https://github.com/rose-pine/neovim) - 全天然松木、人造毛皮和一点 soho 氛围，适合优雅的极简主义者.
- [mcchrish/zenbones.nvim](https://github.com/mcchrish/zenbones.nvim) - Vim/Neovim 颜色方案的集合，旨在使用对比度和字体变化突出显示代码.
- [catppuccin/nvim](https://github.com/catppuccin/nvim)  - 温暖的中色调深色主题，展现充满活力的自我！ 支持本机 LSP、Tree-sitter 等！
- [FrenzyExists/aquarium-vim](https://github.com/FrenzyExists/aquarium-vim) - 深色但充满活力的配色方案.
- [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) - 柔和的深色、完全可定制的 Neovim 主题，支持 lsp、treesitter 和各种插件.
- [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim) - 用 Lua 编写的冷暗配色方案，移植自 [arzg/vim-substrata](https://github.com/arzg/vim-substrata) 主题.
- [ldelossa/vimdark](https://github.com/ldelossa/vimdark)  - 适合夜间的最小 Vim 主题. 松散地基于 vim-monotonic 和 chrome 的深色阅读器扩展. 白天还包括浅色主题.
- [Everblush/everblush.nvim](https://github.com/Everblush/everblush.nvim) - 用 Lua 编写的深色、充满活力且美丽的配色方案.
- [adisen99/apprentice.nvim](https://github.com/adisen99/apprentice.nvim) - 基于Lua编写的Colorscheme [Apprentice](https://github.com/romainl/Apprentice) 带有 Tree-sitter 和内置 lsp 支持的颜色模式.
- [olimorris/onedarkpro.nvim](https://github.com/olimorris/onedarkpro.nvim)  - One Dark Pro 主题，用 Lua 编写，基于 VS Code 主题. 包括深色和浅色主题以及完全可定制的颜色、样式和亮点.
- [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim) - Neovim 主题结合了 Nord 和 Atom One Dark 调色板，带来更加生动的编程体验.
- [RishabhRD/gruvy](https://github.com/RishabhRD/gruvy) - Gruvbuddy 没有使用 Lush 的 colorbuddy.
- [echasnovski/mini.nvim#colorschemes](https://github.com/echasnovski/mini.nvim#plugin-colorschemes)  - `mini.nvim` 插件中包含的配色方案. 它们都优先考虑高对比度，以便在感知统一的色彩空间中读取文本和计算调色板.
- [luisiacc/gruvbox-baby](https://github.com/luisiacc/gruvbox-baby) - 现代 gruvbox 主题，提供全面的树木保护支持.
- [titanzero/zephyrium](https://github.com/titanzero/zephyrium) - zephyr 风格的主题，用 Lua 编写，有 TreeSitter 支持.
- [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) - Neovim dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.
- [tiagovla/tokyodark.nvim](https://github.com/tiagovla/tokyodark.nvim) - 用 Lua (Neovim &gt;= 0.5) 及以上版本编写的干净的深色主题.
- [cpea2506/one_monokai.nvim](https://github.com/cpea2506/one_monokai.nvim) - 一个用 Lua 编写的 Monokai 主题.
- [phha/zenburn.nvim](https://github.com/phha/zenburn.nvim) - 低对比度深色方案，支持各种插件.
- [kvrohit/rasmus.nvim](https://github.com/kvrohit/rasmus.nvim) - 用 Lua 编写的深色配色方案移植自 [rsms/sublime-theme](https://github.com/rsms/sublime-theme) 主题.
- [chrsm/paramount-ng.nvim](https://github.com/chrsm/paramount-ng.nvim)  - 使用 Lush 编写的深色配色方案. 护树人支持.
- [kaiuri/nvim-juliana](https://github.com/kaiuri/nvim-juliana) - 将 Sublime 的 Mariana 主题移植到 Neovim，以供短期注意力集中的开发人员使用 Tree-sitter 支持.
- [lmburns/kimbox](https://github.com/lmburns/kimbox)  - 具有深色背景和以棕色为中心的充满活力的前景的配色方案. 的修改 [Kimbie Dark](https://marketplace.visualstudio.com/items?itemName=dnamsons.kimbie-dark-plus).
- [rockyzhang24/arctic.nvim](https://github.com/rockyzhang24/arctic.nvim) - 从 VSCode Dark+ 主题移植的 Neovim 颜色方案，为编辑器和 UI 提供严格而精确的颜色选择.
- [ramojus/mellifluous.nvim](https://github.com/ramojus/mellifluous.nvim) - 令人愉快且富有成效的配色方案.
- [Yazeed1s/minimal.nvim](https://github.com/yazeed1s/minimal.nvim) - 两个树木保护者支持的配色方案，灵感来自于 base16-tomorrow-night 和 monokai-pro.
- [lewpoly/sherbet.nvim](https://github.com/lewpoly/sherbet.nvim) - 舒缓的配色方案，支持流行的插件和树保姆.
- [Mofiqul/adwaita.nvim](https://github.com/Mofiqul/adwaita.nvim) - 基于 GNOME Adwaita 语法的颜色方案，支持流行的插件.
- [olivercederborg/poimandres.nvim](https://github.com/olivercederborg/poimandres.nvim) - Neovim 港口 [poimandres VSCode theme](https://github.com/drcmda/poimandres-theme) 具有 Tree-sitter 支持，用 Lua 编写.
- [kvrohit/mellow.nvim](https://github.com/kvrohit/mellow.nvim) - 舒缓的深色配色方案，有护树人的支持.
- [gbprod/nord.nvim](https://github.com/gbprod/nord.nvim) - 北极、北蓝色、干净优雅的 Neovim 主题，基于 Nord Palette.
- [Yazeed1s/oh-lucy.nvim](https://github.com/yazeed1s/oh-lucy.nvim) - 两个树木保护者支持的颜色方案，灵感来自 vscode 中的 oh-lucy.
- [embark-theme/vim](https://github.com/embark-theme/vim) - 深墨紫色主题利用明亮的色彩.
- [nyngwang/nvimgelion](https://github.com/nyngwang/nvimgelion) - 新世纪福音战士但针对维默斯.
- [maxmx03/FluoroMachine.nvim](https://github.com/maxmx03/FluoroMachine.nvim) - Synthwave x Fluoromachine 端口.
- [dasupradyumna/midnight.nvim](https://github.com/dasupradyumna/midnight.nvim) - 现代黑色 Neovim 主题，具有舒适的色彩对比，带来愉悦的视觉体验，并支持 LSP 和 Tree-sitter.
- [sonjiku/yawnc.nvim](https://github.com/sonjiku/yawnc.nvim) - 使用 pywal 进行主题化，并带有 Base16 风格.

#### Lua Colorscheme

这些颜色方案可能并不直接专门针对 Tree-sitter，而是用 Lua 编写的.

- [tjdevries/gruvbuddy.nvim](https://github.com/tjdevries/gruvbuddy.nvim) - 矿箱颜色.
- [ellisonleao/gruvbox.nvim](https://github.com/ellisonleao/gruvbox.nvim) - Gruvbox 社区 colorcheme Lua 端口.
- [metalelf0/jellybeans-nvim](https://github.com/metalelf0/jellybeans-nvim) - 软心豆粒糖配色方案的端口.
- [lalitmee/cobalt2.nvim](https://github.com/lalitmee/cobalt2.nvim) - 使用 colorbuddy 的 cobalt2 颜色方案的端口.

#### Colorscheme Creation

- [tjdevries/colorbuddy.nvim](https://github.com/tjdevries/colorbuddy.nvim)  - 配色方案助手. 用Lua写的！ 快速简单的配色方案.
- [norcalli/nvim-base16.lua](https://github.com/norcalli/nvim-base16.lua) - 用于设置 base16 主题的编程 Lua 库.
- [rktjmp/lush.nvim](https://github.com/rktjmp/lush.nvim) - 将 Neovim 主题定义为 Lua 中的 DSL，并提供实时反馈.
- [Iron-E/nvim-highlite](https://github.com/Iron-E/nvim-highlite) - 一个颜色方案生成器，对开发人员来说逻辑“精简”.
- [echasnovski/mini.nvim#mini.base16](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-base16.md) - `mini.nvim` 模块，可快速实现手动提供的调色板的 base16 主题.
- [ThemerCorp/themer.lua](https://github.com/themercorp/themer.lua)  - Neovim 的简单荧光笔插件. 它有大量的配色方案. 它还能够为 Vim/Neovim 和其他支持的应用程序（例如 kitty 和 alacritty）创建颜色方案.
- [echasnovski/mini.nvim#mini.colors](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-colors.md)  - `mini.nvim` 模块用于调整和保存任何配色方案. 还可以对某些颜色空间之间的过渡和转换进行动画处理.
- [echasnovski/mini.nvim#mini.hues](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-hues.md)  - `mini.nvim` 模块用于生成可配置的配色方案. 仅将背景和前景色作为必需参数. 可以调整非基色、饱和度、强调色、插件集成的色调数量.

#### Colorscheme Switchers

- [4e554c4c/darkman.nvim](https://github.com/4e554c4c/darkman.nvim) - 遵循 Linux 上的系统暗模式设置.
- [f-person/auto-dark-mode.nvim](https://github.com/f-person/auto-dark-mode.nvim) - 遵循 macOS 上的系统外观.

### Bars and Lines

- [Bekaboo/deadcolumn.nvim](https://github.com/Bekaboo/deadcolumn.nvim) - 动态显示您的颜色列.
- [ecthelionvi/NeoColumn.nvim](https://github.com/ecthelionvi/NeoColumn.nvim) - 可切换的颜色列突出显示特定字符​​.
- [m4xshen/smartcolumn.nvim](https://github.com/m4xshen/smartcolumn.nvim) - 不需要时隐藏您的颜色列.
- [utilyre/barbecue.nvim](https://github.com/utilyre/barbecue.nvim) - 像 winbar 这样的 VS Code.
- [Bekaboo/dropbar.nvim](https://github.com/Bekaboo/dropbar.nvim) - 类似 IDE 的面包屑，开箱即用.
- [SmiteshP/nvim-navic](https://github.com/SmiteshP/nvim-navic) - A simple statusline/winbar component that uses LSP to show your current code context.
- [luukvbaal/statuscol.nvim](https://github.com/luukvbaal/statuscol.nvim) - 可配置的“状态列”，带有内置段和点击处理程序.

#### Statusline

- [NTBBloodbath/galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim)  - Galaxyline 通过为每个文本区域提供一个提供程序来组件化 Vim 的状态行. 这意味着您可以使用 Galaxyline 提供的 api 轻松创建您想要的状态行.
- [tjdevries/express_line.nvim](https://github.com/tjdevries/express_line.nvim) - 支持协同例程、功能和作业.
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) - 速度极快且易于配置 Neovim 状态行.
- [adelarsq/neoline.vim](https://github.com/adelarsq/neoline.vim) - 使用 Lua 的轻量状态行/选项卡插件.
- [ojroques/nvim-hardline](https://github.com/ojroques/nvim-hardline)  - 状态线/缓冲线. 它的灵感来自于 [vim-airline](https://github.com/vim-airline/vim-airline) 但目标是尽可能轻量和简单.
- [beauwilliams/statusline.lua](https://github.com/beauwilliams/statusline.lua) - 用 Lua 编写的零配置最小状态行，具有出色的集成和惊人的速度！
- [tamton-aquib/staline.nvim](https://github.com/tamton-aquib/staline.nvim)  - Lua 中的现代轻量级状态栏. 主要使用unicode符号来显示信息.
- [freddiehaddad/feline.nvim](https://github.com/freddiehaddad/feline.nvim) - 用 Lua 编写的简约、时尚且可定制的状态栏.
- [windwp/windline.nvim](https://github.com/windwp/windline.nvim)  - 下一代状态栏. 动画状态线.
- [konapun/vacuumline.nvim](https://github.com/konapun/vacuumline.nvim) - 受航空公司启发的 Galaxyline 配置.
- [echasnovski/mini.nvim#mini.statusline](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-statusline.md)  - `mini.nvim` 模块用于最小且快速的状态行. 支持根据窗口宽度改变内容.
- [b0o/incline.nvim](https://github.com/b0o/incline.nvim) - 轻量级浮动状态线，旨在与 Neovim 的新全局状态线一起使用.
- [rebelot/heirline.nvim](https://github.com/rebelot/heirline.nvim) - Heirline.nvim 是一个严肃的 Neovim Statusline 插件，围绕递归继承而设计，速度非常快且用途广泛.
- [yaocccc/nvim-lines.lua](https://github.com/yaocccc/nvim-lines.lua) - 一个快速、轻便、可定制的 Neovim 状态行和选项卡（缓冲区）插件.

#### Tabline

- [romgrk/barbar.nvim](https://github.com/romgrk/barbar.nvim) - Neovim tabline 插件.
- [akinsho/bufferline.nvim](https://github.com/akinsho/bufferline.nvim) - 使用 Lua 构建的时髦缓冲线.
- [crispgm/nvim-tabline](https://github.com/crispgm/nvim-tabline) - Tabline.vim 与 Lua 的 Neovim 移植.
- [alvarosevilla95/luatab.nvim](https://github.com/alvarosevilla95/luatab.nvim) - 用 Lua 编写的简单表格.
- [johann2357/nvim-smartbufs](https://github.com/johann2357/nvim-smartbufs) - 智能缓冲区管理.
- [kdheepak/tabline.nvim](https://github.com/kdheepak/tabline.nvim) - “缓冲区和选项卡”选项卡.
- [noib3/cokeline.nvim](https://github.com/noib3/cokeline.nvim) - 针对上瘾性格人士的 Neovim 缓冲线.
- [echasnovski/mini.nvim#mini.tabline](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-tabline.md) - 用于最小选项卡的“mini.nvim”模块，在只有一个选项卡的情况下显示列出的缓冲区，否则返回默认值.
- [rafcamlet/tabline-framework.nvim](https://github.com/rafcamlet/tabline-framework.nvim) - 用户友好的框架，只需几行代码即可构建您梦想的选项卡.
- [nanozuki/tabby.nvim](https://github.com/nanozuki/tabby.nvim)  - 一个最小的、可配置的、Neovim 风格的选项卡. 使用 Neovim 选项卡作为工作区多路复用器.

#### Cursorline

- [yamatsum/nvim-cursorline](https://github.com/yamatsum/nvim-cursorline) - 一个突出显示光标单词和行的插件.
- [xiyaowong/nvim-cursorword](https://github.com/xiyaowong/nvim-cursorword)  - nvim-cursorline 的一部分. 突出显示光标下的单词.
- [RRethy/vim-illuminate](https://github.com/RRethy/vim-illuminate)  - 突出显示光标下的单词.  Neovim内置LSP可用，可以更智能地突出显示.
- [echasnovski/mini.nvim#mini.cursorword](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-cursorword.md) - `mini.nvim` 模块，用于自动突出显示光标下的单词（在可定制的延迟后显示）.
- [mawkler/modicator.nvim](https://github.com/mawkler/modicator.nvim)  - 光标行号模式指示器. 根据 Vim 模式更改 `CursorLineNr` 高亮显示.
- [nyngwang/murmur.lua](https://github.com/nyngwang/murmur.lua) - 包括超快速光标单词突出显示和回调（我称之为杂音）.

### Startup

- [glepnir/dashboard-nvim](https://github.com/glepnir/dashboard-nvim) - 极简主义仪表板，灵感来自 doom-emacs.
- [goolord/alpha-nvim](https://github.com/goolord/alpha-nvim) - 快速且高度可定制的问候语，例如 [vim-startify](https://github.com/mhinz/vim-startify)/dashboard-nvim.
- [echasnovski/mini.nvim#mini.starter](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-starter.md)  - 用于启动屏幕的“mini.nvim”模块. 显示的项目是完全可定制的，可以使用带有即时视觉反馈的前缀查询来完成项目选择.
- [henriquehbr/nvim-startup.lua](https://sr.ht/~henriquehbr/nvim-startup.lua) - 显示 Neovim 启动时间.
- [startup-nvim/startup.nvim](https://github.com/startup-nvim/startup.nvim) - 完全可定制的 neovim 问候语.
- [willothy/veil.nvim](https://github.com/willothy/veil.nvim) - 速度极快、动画且可无限定制的启动/仪表板插件.

### Icon

- [kyazdani42/nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons) - Lua 的一个分支 [vim-devicons](https://github.com/ryanoasis/vim-devicons).
- [yamatsum/nvim-nonicons](https://github.com/yamatsum/nvim-nonicons) - nvim-web-devicons 的配置集合.
- [ziontee113/icon-picker.nvim](https://github.com/ziontee113/icon-picker.nvim) - 帮助您挑选字体字符、符号 Σ、书呆子字体图标  和表情符号 ✨.

### Media

- [ekickx/clipboard-image.nvim](https://github.com/ekickx/clipboard-image.nvim) - Neovim Lua 插件用于从剪贴板粘贴图像.
- [niuiic/cp-image.nvim](https://github.com/niuiic/cp-image.nvim) - 从剪贴板粘贴图像并插入参考代码.
- [askfiy/nvim-picgo](https://github.com/askfiy/nvim-picgo) - 基于 picgo 核心的 Neovim 插件，用 Lua 编写，允许您将图像上传到图像床，这意味着您可以从互联网上的任何地方查看图像.
- [gwatcha/reaper-keys](https://github.com/gwatcha/reaper-keys) - Reaper DAW 的模式键绑定.
- [madskjeldgaard/reaper-nvim](https://github.com/madskjeldgaard/reaper-nvim) - Neovim 远程控制 Reaper DAW.
- [davidgranstrom/scnvim](https://github.com/davidgranstrom/scnvim) - SuperCollider 的 Neovim 前端.
- [andweeb/presence.nvim](https://github.com/andweeb/presence.nvim) - 用 Lua 编写的快速且精简的 Discord Rich Presence 插件.
- [Chaitanyabsrip/present.nvim](https://github.com/Chaitanyabsprip/present.nvim) - 用 Lua 编写的演示插件.
- [krady21/compiler-explorer.nvim](https://github.com/krady21/compiler-explorer.nvim) - 用于交互的异步 Lua 插件 [compiler-explorer](https://godbolt.org/).
- [samodostal/image.nvim](https://github.com/samodostal/image.nvim) - 图像查看器作为 ASCII 艺术.
- [adelarsq/image_preview.nvim](https://github.com/adelarsq/image_preview.nvim) - 基于终端图像协议支持的图像预览.

### Note Taking

- [0styx0/abbreinder.nvim](https://github.com/0styx0/abbreinder.nvim) - 缩写提醒（Neovim &gt;= 0.5）.
- [jakewvincent/mkdnflow.nvim](https://github.com/jakewvincent/mkdnflow.nvim) - 流畅的 Markdown 笔记本导航和管理（创建链接、关注链接、创建和管理待办事项列表、参考书目文件等）.
- [oberblastmeister/neuron.nvim](https://github.com/oberblastmeister/neuron.nvim) - 与 Telegram.nvim 集成的神经元笔记插件.
- [jbyuki/nabla.nvim](https://github.com/jbyuki/nabla.nvim) - 记下你的科学笔记.
- [nvim-neorg/neorg](https://github.com/nvim-neorg/neorg)  - 现代性与疯狂的可扩展性相遇. 组织您生活的未来.
- [nvim-orgmode/orgmode](https://github.com/nvim-orgmode/orgmode) - 用 Lua 编写的 Orgmode 克隆 (Neovim &gt;= 0.5).
- [NFrid/due.nvim](https://github.com/NFrid/due.nvim) - 将到期日期字符串显示为虚拟文本.
- [jbyuki/venn.nvim](https://github.com/jbyuki/venn.nvim) - 绘制 ASCII 图表.
- [stevearc/gkeep.nvim](https://github.com/stevearc/gkeep.nvim) - 谷歌保持集成.
- [renerocksai/telekasten.nvim](https://github.com/renerocksai/telekasten.nvim) - 一个 Neovim (lua) 插件，用于处理基于文本的 markdown zettelkasten / wiki 并将其与基于望远镜.nvim 的日记混合.
- [mickael-menu/zk-nvim](https://github.com/mickael-menu/zk-nvim) - zk 的 Neovim 扩展，纯文本笔记助手.
- [chrsm/impulse.nvim](https://github.com/chrsm/impulse.nvim) - 阅读 Notion.so 注释.
- [epwalsh/obsidian.nvim](https://github.com/epwalsh/obsidian.nvim) - Obsidian 插件，用 Lua 编写.
- [jghauser/papis.nvim](https://github.com/jghauser/papis.nvim) - 在您最喜欢的编辑器中管理您的参考书目.
- [ostralyan/scribe.nvim](https://github.com/ostralyan/scribe.nvim) - 轻松做笔记.
- [phaazon/mind.nvim](https://github.com/phaazon/mind.nvim) - 树木的力量触手可及.
- [RutaTang/quicknote.nvim](https://github.com/RutaTang/quicknote.nvim) - 快速就地做笔记.

### Utility

- [jghauser/mkdir.nvim](https://github.com/jghauser/mkdir.nvim) - 保存文件时自动创建丢失的目录.
- [matbme/JABS.nvim](https://github.com/matbme/JABS.nvim) - 漂亮且最小的缓冲区切换器窗口.
- [j-morano/buffer_manager.nvim](https://github.com/j-morano/buffer_manager.nvim) - 添加一个或多个缓冲区，对它们重新排序，将它们保存在文件中，或者从一个小的浮动窗口中轻松删除它们.
- [clojure-vim/jazz.nvim](https://github.com/clojure-vim/jazz.nvim) - 酸 + 即兴 = 爵士乐.
- [sudormrfbin/cheatsheet.nvim](https://github.com/sudormrfbin/cheatsheet.nvim) - 可搜索的备忘单.
- [code-biscuits/nvim-biscuits](https://github.com/code-biscuits/nvim-biscuits)  - 什锦饼干的 Neovim 端口. 最终也得到了更多支持的语言.
- [Pocco81/AbbrevMan.nvim](https://github.com/Pocco81/AbbrevMan.nvim) - 管理 Vim 缩写.
- [kazhala/close-buffers.nvim](https://github.com/kazhala/close-buffers.nvim) - 根据不同情况删除多个Vim缓冲区.
- [rktjmp/paperplanes.nvim](https://github.com/rktjmp/paperplanes.nvim) - 将选择或缓冲区发布到在线粘贴箱.
- [rcarriga/nvim-notify](https://github.com/rcarriga/nvim-notify) - 一个精美的、可配置的通知管理器.
- [folke/noice.nvim](https://github.com/folke/noice.nvim) - 高度实验性的插件，完全取代消息、命令行和弹出菜单的 UI.
- [sQVe/bufignore.nvim](https://github.com/sQVe/bufignore.nvim) - 取消列出与指定忽略源匹配的隐藏缓冲区.
- [saifulapm/chartoggle.nvim](https://github.com/saifulapm/chartoggle.nvim) - 切换行尾的任何字符.
- [stevearc/dressing.nvim](https://github.com/stevearc/dressing.nvim) - 改进内置 `vim.ui` 与望远镜、fzf 等的界面.
- [gaborvecsei/cryptoprice.nvim](https://github.com/gaborvecsei/cryptoprice.nvim) - 检查定义的加密货币的价格.
- [jghauser/fold-cycle.nvim](https://github.com/jghauser/fold-cycle.nvim) - 循环折叠打开或关闭.
- [rgroli/other.nvim](https://github.com/rgroli/other.nvim) - 打开当前缓冲区的替代文件.
- [toppair/reach.nvim](https://github.com/toppair/reach.nvim) - 缓冲区、标记、标签页切换器.
- [axieax/urlview.nvim](https://github.com/axieax/urlview.nvim) - 浏览当前缓冲区中的所有 URL.
- [nkakouros-original/numbers.nvim](https://github.com/nkakouros-original/numbers.nvim) - 每当有意义时切换相对数字.
- [ghillb/cybu.nvim](https://github.com/ghillb/cybu.nvim) - 循环缓冲区时显示带有上下文的通知窗口.
- [crusj/bookmarks.nvim](https://github.com/crusj/bookmarks.nvim) - 记住文件位置并按时间和频率排序.
- [xiyaowong/virtcolumn.nvim](https://github.com/xiyaowong/virtcolumn.nvim) - 将一条线显示为颜色列.
- [m-demare/attempt.nvim](https://github.com/m-demare/attempt.nvim) - 管理和运行临时缓冲区.
- [kevinhwang91/nvim-ufo](https://github.com/kevinhwang91/nvim-ufo) - 超折叠，具有现代外观和性能提升.
- [xiyaowong/link-visitor.nvim](https://github.com/xiyaowong/link-visitor.nvim) - 让我帮你打开链接.
- [sitiom/nvim-numbertoggle](https://github.com/sitiom/nvim-numbertoggle) - Neovim 插件可自动在相对行号和绝对行号之间切换.
- [anuvyklack/fold-preview](https://github.com/anuvyklack/fold-preview.nvim) - 无需打开即可预览闭合折叠.
- [nguyenvukhang/nvim-toggler](https://github.com/nguyenvukhang/nvim-toggler) - 反转文本，例如在“true”和“false”之间切换.
- [CosmicNvim/cosmic-ui](https://github.com/CosmicNvim/cosmic-ui)  - Cosmic-UI 是特定 Vim 功能的简单包装. 旨在提供一种快速、简单的方法来使用 Neovim 创建 Cosmic UI 体验！
- [AckslD/messages.nvim](https://github.com/AckslD/messages.nvim) - 捕获并显示可自定义（浮动）缓冲区中的任何消息.
- [jbyuki/instant.nvim](https://github.com/jbyuki/instant.nvim) - 用 Lua 编写的协作编辑插件，无依赖项.
- [numToStr/BufOnly.nvim](https://github.com/numToStr/BufOnly.nvim) - BufOnly.vim 的 Lua/Neovim 端口有一些更改.
- [zbirenbaum/neodim](https://github.com/zbirenbaum/neodim) - 调暗未使用的函数、变量、参数等的亮点.
- [bfredl/nvim-miniyank](https://github.com/bfredl/nvim-miniyank) - 类似killring 的插件，没有默认映射.
- [chrisgrieser/nvim-genghis](https://github.com/chrisgrieser/nvim-genghis) - 方便的文件操作，用Lua编写.
- [chrisgrieser/nvim-recorder](https://github.com/chrisgrieser/nvim-recorder) - 简化和改进与宏交互的方式.
- [echasnovski/mini.nvim#mini.animate](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-animate.md) - `mini.nvim` 模块为常见的内置操作（光标移动、滚动、调整大小、窗口打开/关闭）添加开箱即用的动画.
- [figsoda/nix-develop.nvim](https://github.com/figsoda/nix-develop.nvim) - 运行“nixdevelop”而不重新启动 Neovim.
- [yaocccc/nvim-foldsign](https://github.com/yaocccc/nvim-foldsign) - 在标志栏上显示折叠.
- [tenxsoydev/nx.nvim](https://github.com/tenxsoydev/nx.nvim) - Neovim API 实用程序包装器通过 Lua 键盘映射、突出显示、自动命令和选项提供更多便利.
- [zdcthomas/yop.nvim](https://github.com/zdcthomas/yop.nvim) - 轻松创建您自己的运算符（如“d”和“y”）.
- [cpea2506/relative-toggle.nvim](https://github.com/cpea2506/relative-toggle.nvim) - 数字与相对数字之间平滑切换，支持多种数字组合，高度可定制.
- [nvim-early-retirement](https://github.com/chrisgrieser/nvim-early-retirement) - 通过在 x 分钟不活动后自动关闭缓冲区，将缓冲区送入提前退休状态.
- [hbac.nvim](https://github.com/axkirillov/hbac.nvim) - 自动关闭您不使用的缓冲区.
- [ecthelionvi/NeoComposer.nvim](https://github.com/ecthelionvi/NeoComposer.nvim) - 简化宏观管理，提高生产力，创建和谐的工作流程.
- [LukasPietzschmann/telescope-tabs](https://github.com/LukasPietzschmann/telescope-tabs) - 使用望远镜在选项卡之间快速导航.
- [RutaTang/compter.nvim](https://github.com/RutaTang/compter.nvim)  - 增强和扩展`的能力<C-a> ` 和 `<C-x>  ` 具有定制图案.
- [reggie/licenses.nvim](https://git.sr.ht/~reggie/licenses.nvim) - 插入并写入许可证标头和/或文件.
- [yagiziskirik/AirSupport.nvim](https://github.com/yagiziskirik/AirSupport.nvim) - 用于自定义快捷方式和命令的可搜索提醒窗口.

### Terminal Integration

- [LoricAndre/OneTerm.nvim](https://github.com/LoricAndre/OneTerm.nvim) - 用于在终端中运行命令的插件框架.
- [nikvdp/neomux](https://github.com/nikvdp/neomux) - 从 Neovim 内运行的 shell 控制 Neovim.
- [willothy/flatten.nvim](https://github.com/willothy/flatten.nvim) - 从当前 Neovim 实例中的终端缓冲区打开文件，而不是启动嵌套实例.
- [akinsho/nvim-toggleterm.lua](https://github.com/akinsho/nvim-toggleterm.lua) - Neovim Lua 插件可帮助轻松管理多个终端窗口.
- [norcalli/nvim-terminal.lua](https://github.com/norcalli/nvim-terminal.lua) - 高性能文件类型模式，利用正确的颜色代码隐藏和突出显示缓冲区.
- [numToStr/FTerm.nvim](https://github.com/numToStr/FTerm.nvim) - 没有用 Lua 编写的废话浮动终端.
- [pianocomposer321/consolation.nvim](https://github.com/pianocomposer321/consolation.nvim) - 通用终端包装器和管理插件，用 Lua 编写.
- [jghauser/kitty-runner.nvim](https://github.com/jghauser/kitty-runner.nvim)  - 穷人的 REPL. 轻松将缓冲线和命令发送到 kitty 终端.
- [jlesquembre/nterm.nvim](https://github.com/jlesquembre/nterm.nvim) - 通过通知与终端交互.
- [s1n7ax/nvim-terminal](https://github.com/s1n7ax/nvim-terminal) - 一个简单易用的多终端插件.
- [m00qek/baleia.nvim](https://github.com/m00qek/baleia.nvim) - 使用 ANSI 转义序列（8、16、256 或 TrueColor）对文本进行着色.
- [samjwill/nvim-unception](https://github.com/samjwill/nvim-unception) - 从终端缓冲区开始自动解除 Neovim 会话的嵌套.
- [nyngwang/NeoTerm.lua](https://github.com/nyngwang/NeoTerm.lua) - 为每个**缓冲区**连接一个终端，现在具有稳定的切换和惊人的光标恢复功能.
- [idanarye/nvim-channelot](https://github.com/idanarye/nvim-channelot) - 从 Lua 协程操作 Neovim 作业.
- [chomosuke/term-edit.nvim](https://github.com/chomosuke/term-edit.nvim) - 允许您像任何其他缓冲区一样在终端中编辑命令.

### Debugging

- [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap) - 调试适配器协议客户端实现.
- [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) - GDB、LLDB、PDB/PDB++ 和 BashDB 的瘦包装器.
- [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) - nvim-dap 的用户界面.
- [Pocco81/DAPInstall.nvim](https://github.com/Pocco81/DAPInstall.nvim) - 管理 nvim-dap 的多个调试器.
- [Weissle/persistent-breakpoints.nvim](https://github.com/Weissle/persistent-breakpoints.nvim) - nvim-dap 的持久断点.
- [ofirgall/goto-breakpoints.nvim](https://github.com/ofirgall/goto-breakpoints.nvim) - 在 nvim-dap 的断点之间循环.
- [andrewferrier/debugprint.nvim](https://github.com/andrewferrier/debugprint.nvim) - 调试 print() 方式.
- [t-troebst/perfanno.nvim](https://github.com/t-troebst/perfanno.nvim)  - 使用调用图分析数据注释您的代码. 对 perf、flamegraph 和 LuaJit 分析器的本机支持.

#### Quickfix

- [kevinhwang91/nvim-bqf](https://github.com/kevinhwang91/nvim-bqf) - nvim-bqf 的目标是使 Neovim 的快速修复窗口变得更好.
- [gitlab.com/yorickpeterse/nvim-pqf](https://gitlab.com/yorickpeterse/nvim-pqf) - 更漂亮的快速修复/位置列表窗口.
- [nyngwang/NeoWell.lua](https://github.com/nyngwang/NeoWell.lua)  - 有时您会想要稍后修复某些线路. 将行存储到 qf 中并附上一些注释，这样当您真正想要修复它时就知道该怎么做.

### Test

- [David-Kunz/jester](https://github.com/David-Kunz/jester) - 轻松运行和调试 Jest 测试.
- [klen/nvim-test](https://github.com/klen/nvim-test) - 用于运行测试的 Neovim 包装器.
- [nvim-neotest/neotest](https://github.com/nvim-neotest/neotest) - 用于与 Neovim 内的测试交互的可扩展框架.
- [andythigpen/nvim-coverage](https://github.com/andythigpen/nvim-coverage) - 在标志栏中显示覆盖范围信息.

### Code Runner

- [michaelb/sniprun](https://github.com/michaelb/sniprun) - 直接从 Neovim 运行任何语言的部分代码.
- [pianocomposer321/yabs.nvim](https://github.com/pianocomposer321/yabs.nvim) - 另一个构建系统，用 Lua 编写.
- [CRAG666/code_runner.nvim](https://github.com/CRAG666/code_runner.nvim) - 你可以拥有的最好的代码运行者，具有超能力.
- [is0n/jaq-nvim](https://github.com/is0n/jaq-nvim) - 只是 Lua 中的另一个 Quickrun 插件.
- [jedrzejboczar/toggletasks.nvim](https://github.com/jedrzejboczar/toggletasks.nvim) - 具有 JSON/YAML 配置的任务运行器，使用toggleterm.nvim 和 Telescope.nvim.
- [EthanJWright/vs-tasks.nvim](https://github.com/EthanJWright/vs-tasks.nvim) - 用于 VSCode 风格任务的望远镜选择器.
- [stevearc/overseer.nvim](https://github.com/stevearc/overseer.nvim) - 任务运行器和作业管理插件.
- [smzm/hydrovim](https://github.com/smzm/hydrovim) - 在 Neovim 中运行 python 代码.
- [desdic/greyjoy.nvim](https://github.com/desdic/greyjoy.nvim) - 用于 Makefile、vscode 任务、厨房等的模块化任务运行器.
- [Shatur/neovim-tasks](https://github.com/Shatur/neovim-tasks) - 专注于与构建系统集成的有状态任务管理器.
- [milanglacier/yarepl.nvim](https://github.com/milanglacier/yarepl.nvim) - 另一个 REPL，灵活，支持多种范例与 REPL 交互，并且原生点重复，无需其他依赖项.
- [hkupty/iron.nvim](https://github.com/hkupty/iron.nvim) - 嵌入 30 多种语言的交互式 REPL.
- [Civitasv/cmake-tools.nvim](https://github.com/Civitasv/cmake-tools.nvim) - CMake 集成.
- [idanarye/nvim-moonicipal](https://github.com/idanarye/nvim-moonicipal) - 任务运行者专注于快速变化的个人任务.
- [MarcHamamji/runner.nvim](https://github.com/MarcHamamji/runner.nvim) - 可定制的 Lua 代码运行器.
- [google/executor.nvim](https://github.com/google/executor.nvim) - 允许您在后台运行命令行任务并收到结果通知.

### Neovim Lua Development

- [folke/neodev.nvim](https://github.com/folke/neodev.nvim) - init.lua 的开发设置和插件开发，包括 Neovim Lua API 的完整签名帮助、文档和完成.
- [nvim-neorocks/luarocks-tag-release](https://github.com/nvim-neorocks/luarocks-tag-release) - 将 Neovim 插件发布到 LuaRocks 的 GitHub 操作.
- [svermeulen/vimpeccable](https://github.com/svermeulen/vimpeccable) - 帮助用 Lua 或任何基于 Lua 的语言编写 .vimrc 的命令.
- [nanotee/nvim-lua-guide](https://github.com/nanotee/nvim-lua-guide) - 在 Neovim 中使用 Lua 的指南.
- [rafcamlet/nvim-luapad](https://github.com/rafcamlet/nvim-luapad) - 用于嵌入式 Lua 引擎的交互式实时 Neovim 便笺本 - 键入并观看！
- [nvim-lua/plenary.nvim](https://github.com/nvim-lua/plenary.nvim)  - 全体会议：全体会议； 完全的; 全部的; 绝对; 不合格. 所有的Lua函数我都不想写两次.
- [nvim-lua/popup.nvim](https://github.com/nvim-lua/popup.nvim) - Vim 的 Popup API 的实现.
- [tjdevries/vlog.nvim](https://github.com/tjdevries/vlog.nvim) - 单个文件，无依赖性，轻松复制和粘贴日志文件以添加到您的 Neovim Lua 插件中.
- [bfredl/nvim-luadev](https://github.com/bfredl/nvim-luadev)  - REPL/调试控制台 Lua 插件.  `:Luadev` 命令将打开一个草稿窗口，其中显示执行 Lua 代码的输出.
- [jbyuki/one-small-step-for-vimkind](https://github.com/jbyuki/one-small-step-for-vimkind)  - Neovim Lua 语言的适配器. 它允许您调试在 Neovim 实例中运行的任何 Lua 代码（可以调试 Neovim Lua 插件的 Lua 插件）.
- [kkharji/sqlite.lua](https://github.com/kkharji/sqlite.lua) - Lua 和 Neovim 的 SQLite/LuaJIT 绑定.
- [MunifTanjim/nui.nvim](https://github.com/MunifTanjim/nui.nvim) - UI 组件库.
- [echasnovski/mini.nvim#mini.doc](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-doc.md)  - `mini.nvim` 模块，用于从类似 EmmyLua 的注释生成帮助文件. 允许通过钩子函数灵活定制输出.
- [nanotee/luv-vimdocs](https://github.com/nanotee/luv-vimdocs) - The luv docs in vimdoc format.
- [milisims/nvim-luaref](https://github.com/milisims/nvim-luaref) - 内置 Lua 函数的参考.
- [echasnovski/mini.nvim#mini.test](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-test.md)  - `mini.nvim` 模块，带有用于编写广泛 Neovim 插件测试的框架. 支持分层测试、挂钩、参数化、过滤、屏幕测试、“busted-style”仿真、可定制报告器等.
- [miversen33/import.nvim](https://github.com/miversen33/import.nvim) - 保险箱需要更换，但要精致.
- [ray-x/guihua.lua](https://github.com/ray-x/guihua.lua)  - Lua UI 库. 包括 fzy 搜索栏、列表视图和树视图模块.
- [anuvyklack/animation.nvim](https://github.com/anuvyklack/animation.nvim) - 创建动画.
- [NFrid/treesitter-utils](https://github.com/NFrid/treesitter-utils) - 一些有用的树保姆方法.

### Fennel

- [Olical/aniseed](https://github.com/Olical/aniseed) - 使用 Fennel 配置和扩展 Neovim（Lisp 到 Lua）.
- [Olical/conjure](https://github.com/Olical/conjure) - 交互式评估（Clojure、Fennel、Janet、Racket、Hy、MIT Scheme、Guile）.
- [rktjmp/hotpot.nvim](https://github.com/rktjmp/hotpot.nvim) - Neovim 内无缝、透明的茴香.
- [udayvir-singh/tangerine.nvim](https://github.com/udayvir-singh/tangerine.nvim) - 甜：橘子：茴香整合，目标是尽可能快.
- [udayvir-singh/hibiscus.nvim](https://github.com/udayvir-singh/hibiscus.nvim) - 风味：木槿：茴香宏库.

### Dependency Management

- [vuki656/package-info.nvim](https://github.com/vuki656/package-info.nvim) - 在 package.json 中将最新的包版本显示为虚拟文本.
- [Saecki/crates.nvim](https://github.com/Saecki/crates.nvim) - `Cargo.toml` 的 Rust 依赖管理.

### Git

- [f-person/git-blame.nvim](https://github.com/f-person/git-blame.nvim) - 显示 git Blame 信息.
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Git 集成：标志、大块动作、责备等.
- [TimUntersberger/neogit](https://github.com/TimUntersberger/neogit) - Magit 克隆，可能会改变一些东西以适应 Vim 哲学.
- [tveskag/nvim-blame-line](https://github.com/tveskag/nvim-blame-line) - 一个小插件，使用 neovims 虚拟文本在当前行末尾打印 git Blame 信息.
- [ruifm/gitlinker.nvim](https://github.com/ruifm/gitlinker.nvim)  - 为多个 git 主机生成可共享文件永久链接. 受到 tpope/vim-fugitive 的 :GBrowse 的启发.
- [tanvirtin/vgit.nvim](https://github.com/tanvirtin/vgit.nvim) - 可视化 Git 插件，增强您的 git 体验.
- [sindrets/diffview.nvim](https://github.com/sindrets/diffview.nvim) - 单选项卡界面，可轻松循环浏览任何 git rev 的所有修改文件的差异.
- [kdheepak/lazygit.nvim](https://github.com/kdheepak/lazygit.nvim) - 用于调用lazygit的插件.
- [AckslD/nvim-gfold.lua](https://github.com/AckslD/nvim-gfold.lua) - Plugin using [gfold](https://github.com/nickgerace/gfold) 切换存储库并拥有状态行组件.
- [akinsho/git-conflict.nvim](https://github.com/akinsho/git-conflict.nvim) - 用于可视化和解决合并冲突的插件.
- [aaronhallaert/advanced-git-search.nvim](https://github.com/aaronhallaert/advanced-git-search.nvim) - 使用 Telescope 按提交内容、消息和作者搜索您的 git 历史记录.
- [linrongbin16/gitlinker.nvim](https://github.com/linrongbin16/gitlinker.nvim) - 为 git 主机网站生成可共享文件永久链接（带有行范围），这是“ruifm 的 gitlinker”的一个分支，使用基于模式的规则引擎、Windows 支持和其他增强功能进行了重构.

#### GitHub

- [pwntester/octo.nvim](https://github.com/pwntester/octo.nvim)  - 处理来自 Neovim 的 GitHub 问题和 PR. 只需编辑问题描述即可.
- [pwntester/codeql.nvim](https://github.com/pwntester/codeql.nvim) - Neovim 插件可帮助编写和测试 CodeQL 查询.
- [ldelossa/gh.nvim](https://github.com/ldelossa/gh.nvim) - 用于执行代码审查的功能齐全的 GitHub 集成.
- [topaxi/gh-actions.nvim](https://github.com/topaxi/gh-actions.nvim) - 查看和调度 GitHub Actions 工作流程运行.

### Motion

- [phaazon/hop.nvim](https://github.com/phaazon/hop.nvim) - Hop 是一个类似 EasyMotion 的插件，允许您用尽可能少的击键跳转到文档中的任何位置.
- [ggandor/lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim) - 类似 Sneak 的插件，通过提前显示的标签提供无与伦比的导航速度，消除输入搜索模式和选择目标之间的停顿.
- [ggandor/leap.nvim](https://github.com/ggandor/leap.nvim) - Lightspeed 的精致继承者，旨在建立一个广泛接受的标准接口扩展，以便在类似 Vim 的编辑器中移动.
- [echasnovski/mini.nvim#mini.jump](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump.md) - `mini.nvim` 模块，用于更智能地跳转到单个字符.
- [echasnovski/mini.nvim#mini.jump2d](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump2d.md)  - `mini.nvim` 模块，通过迭代标签过滤在可见行内更智能地跳转. 支持自定义跳转目标（点）、标签、挂钩、允许的窗口和线条等.
- [rlane/pounce.nvim](https://github.com/rlane/pounce.nvim) - 类似 EasyMotion 的插件，可使用模糊搜索快速移动光标.
- [gen740/SmoothCursor.nvim](https://github.com/gen740/SmoothCursor.nvim) - 将精美的子光标添加到符号列以显示滚动或跳转方向.
- [edluffy/specs.nvim](https://github.com/edluffy/specs.nvim) - 一个快速、轻量级的 Neovim Lua 插件，用于监视光标跳跃的位置.
- [abecodes/tabout.nvim](https://github.com/abecodes/tabout.nvim) - 跳出括号、引号、对象等.
- [linty-org/readline.nvim](https://github.com/linty-org/readline.nvim) - Readline 键盘快捷键.
- [woosaaahh/sj.nvim](https://github.com/woosaaahh/sj.nvim) - 基于搜索的导航与快速跳转功能相结合.
- [Weissle/easy-action](https://github.com/Weissle/easy-action) - 在您能看到的地方轻松执行操作.
- [cbochs/portal.nvim](https://github.com/cbochs/portal.nvim)  - 建立并增强现有的跳转列表动议（即`<c-i>  ` 和 `<c-o>  `）.
- [echasnovski/mini.nvim#mini.bracketed](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-bracketed.md) - `mini.nvim` 模块用方括号前进/后退.
- [liangxianzhe/nap.nvim](https://github.com/liangxianzhe/nap.nvim) - 使用一个键在下一个/上一个缓冲区、选项卡、诊断等之间跳转.
- [chrisgrieser/nvim-spider](https://github.com/chrisgrieser/nvim-spider)  - 像蜘蛛一样使用 w、e、b 动作. 考虑驼峰命名法并跳过无关紧要的标点符号.

#### Treesitter Based

- [mfussenegger/nvim-ts-hint-textobject](https://github.com/mfussenegger/nvim-ts-hint-textobject) - 区域选择，带有有关由 Treesitter 提供支持的文档 AST 节点的提示.
- [ziontee113/syntax-tree-surfer](https://github.com/ziontee113/syntax-tree-surfer)  - 导航并交换 Treesitter 的 AST 节点. 走进、走出、跨过、后退.
- [drybalka/tree-climber.nvim](https://github.com/drybalka/tree-climber.nvim) - 在 Treesitter 的树上轻松导航，在多语言文件和正常模式下工作.

### Keybinding

- [folke/which-key.nvim](https://github.com/folke/which-key.nvim) - Neovim 插件显示一个弹出窗口，其中包含您开始输入的命令的可能的键绑定.
- [mrjones2014/legendary.nvim](https://github.com/mrjones2014/legendary.nvim) - 将键盘映射、命令和自动命令定义为简单的 Lua 表，同时为它们创建图例（如 VS Code 的命令面板），与“which-key.nvim”集成.
- [Iron-E/nvim-cartographer](https://github.com/Iron-E/nvim-cartographer) - Lua 环境更方便的 `:map`ping 语法.
- [b0o/mapx.nvim](https://github.com/b0o/mapx.nvim)  - 一个更简单的按键映射 API，模仿 Neovim 的 `:map` 系列命令. 与which-key.nvim 集成.
- [LionC/nest.nvim](https://github.com/LionC/nest.nvim)  - Lua 实用程序使用级联树简洁地映射键. 还允许将 Lua 函数绑定到键.
- [LinArcX/telescope-command-palette.nvim](https://github.com/LinArcX/telescope-command-palette.nvim) - Lua 插件，用于创建键绑定并用望远镜观看它们.
- [slugbyte/unruly-worker](https://github.com/slugbyte/unruly-worker) - 一个非常有趣的替代键盘映射，适用于工人键盘布局，具有 Neovim 功能，如 LSP 支持，使用 Lua 构建和配置.
- [FeiyouG/command_center.nvim](https://github.com/FeiyouG/command_center.nvim) - 以更有组织的方式创建和管理按键绑定和命令，并通过 Telescope 快速搜索它们.
- [linty-org/key-menu.nvim](https://github.com/linty-org/key-menu.nvim) - 浮动窗口中的按键映射提示.
- [anuvyklack/hydra.nvim](https://github.com/anuvyklack/hydra.nvim)  - 创建自定义子模式和菜单.  Emacs Hydra 端口.
- [anuvyklack/keymap-amend.nvim](https://github.com/anuvyklack/keymap-amend.nvim) - 修改现有的键盘映射.
- [max397574/better-escape.nvim](https://github.com/max397574/better-escape.nvim) - 创建快捷方式以退出插入模式而不会造成延迟.
- [Nexmean/caskey.nvim](https://github.com/Nexmean/caskey.nvim) - Utility to keymappings configuration using declarative cascading trees, optionally integrates with `which-key`.
- [Wansmer/langmapper.nvim](https://github.com/Wansmer/langmapper.nvim) - 自动翻译非英语输入法的映射.

### Mouse

- [notomo/gesture.nvim](https://github.com/notomo/gesture.nvim) - 鼠标手势插件.

### Scrolling

- [karb94/neoscroll.nvim](https://github.com/karb94/neoscroll.nvim) - 平滑滚动.
- [declancm/cinnamon.nvim](https://github.com/declancm/cinnamon.nvim) - 任何移动命令的平滑滚动.

#### Scrollbar

- [Xuyuanp/scrollbar.nvim](https://github.com/Xuyuanp/scrollbar.nvim) - 滚动条.
- [dstein64/nvim-scrollview](https://github.com/dstein64/nvim-scrollview) - 显示交互式滚动条.
- [petertriho/nvim-scrollbar](https://github.com/petertriho/nvim-scrollbar) - 显示诊断和搜索结果的可扩展滚动条.
- [echasnovski/mini.nvim#mini.map](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-map.md) - `mini.nvim` 模块，用于显示带有缓冲区文本概述、滚动条和突出显示的浮动窗口.
- [gorbit99/codewindow.nvim](https://github.com/gorbit99/codewindow.nvim) - Minimap插件，与treesitter和内置LSP紧密集成，向用户显示更多信息.
- [lewis6991/satellite.nvim](https://github.com/lewis6991/satellite.nvim) - 装饰滚动条.

### Editing Support

- [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag) - 使用 treesitter 自动关闭和自动重命名 xml、html、jsx 标签.
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs) - Lua 编写的极简主义自动配对.
- [ZhiyuanLck/smart-pairs](https://github.com/ZhiyuanLck/smart-pairs) - Lua 编写的终极智能对.
- [echasnovski/mini.nvim#mini.pairs](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-pairs.md) - 用于自动配对的“mini.nvim”模块，具有最小的默认值和执行每个键映射的功能.
- [m4xshen/autoclose.nvim](https://github.com/m4xshen/autoclose.nvim) - 用 Lua 编写的极简自动关闭插件.
- [altermo/ultimate-autopair.nvim](https://github.com/altermo/ultimate-autopair.nvim) - 与扩展自动配对.
- [utilyre/sentiment.nvim](https://github.com/utilyre/sentiment.nvim) - 增强的匹配对.
- [monaqa/dial.nvim](https://github.com/monaqa/dial.nvim) - 扩展的增量/减量.
- [mrjones2014/nvim-ts-rainbow](https://github.com/mrjones2014/nvim-ts-rainbow) - Rainbow :rainbow: 使用 tree-sitter :rainbow: 分隔符.
- [AckslD/nvim-revJ.lua](https://github.com/AckslD/nvim-revJ.lua) - Neovim Lua 插件，用于对参数执行与连接线 (J) 相反的操作.
- [Pocco81/TrueZen.nvim](https://github.com/Pocco81/TrueZen.nvim) - 干净优雅、无干扰的写作.
- [Pocco81/HighStr.nvim](https://github.com/Pocco81/HighStr.nvim) - 像在普通文档编辑器中一样突出显示视觉选择！
- [Pocco81/AutoSave.nvim](https://github.com/Pocco81/AutoSave.nvim) - 在世界崩溃或输入 :qa! 之前保存您的工作
- [tmillr/sos.nvim](https://github.com/tmillr/sos.nvim) - 根据预定义的超时值自动保存所有修改的缓冲区.
- [folke/zen-mode.nvim](https://github.com/folke/zen-mode.nvim) - 无干扰的编码.
- [haringsrob/nvim_context_vt](https://github.com/haringsrob/nvim_context_vt) - 显示当前上下文的虚拟文本.
- [nvim-treesitter/nvim-treesitter-context](https://github.com/nvim-treesitter/nvim-treesitter-context) - 显示当前函数/块上下文的浮动悬停.
- [mizlan/iswap.nvim](https://github.com/mizlan/iswap.nvim)  - 交互式选择和交换函数参数、列表元素等. 由树保姆提供动力.
- [Wansmer/sibling-swap.nvim](https://github.com/Wansmer/sibling-swap.nvim) - 与树保姆交换争论和其他兄弟姐妹的不同方式.
- [Wansmer/binary-swap.nvim](https://github.com/Wansmer/binary-swap.nvim) - 交换二进制表达式中的操作数和运算符：比较和数学运算.
- [nacro90/numb.nvim](https://github.com/nacro90/numb.nvim) - 以不显眼的方式查看线条.
- [ethanholz/nvim-lastplace](https://github.com/ethanholz/nvim-lastplace) - 在上次编辑位置重新打开文件.
- [Allendang/nvim-expand-expr](https://github.com/AllenDang/nvim-expand-expr) - 将表达式扩展并重复到多行.
- [h-hg/fcitx.nvim](https://github.com/h-hg/fcitx.nvim) - 分别切换和恢复每个缓冲区的 fcitx 状态.
- [keaising/im-select.nvim](https://github.com/keaising/im-select.nvim) - 自动切换和恢复输入法取决于 Neovim 的编辑模式.
- [echasnovski/mini.nvim#mini.trailspace](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-trailspace.md) - `mini.nvim` 模块，用于自动突出显示尾随空白并具有删除它的功能.
- [smjonas/live-command.nvim](https://github.com/smjonas/live-command.nvim) - 具有即时视觉反馈的文本编辑：预览命令，例如 `:norm`、`:g`、宏等.
- [filipdutescu/renamer.nvim](https://github.com/filipdutescu/renamer.nvim) - 类似 VS Code 的重命名 UI，用 Lua 编写.
- [gbprod/cutlass.nvim](https://github.com/gbprod/cutlass.nvim) - 添加与“删除”分开的“剪切”操作的插件.
- [gbprod/substitute.nvim](https://github.com/gbprod/substitute.nvim) - Neovim 插件引入了新的操作员动作来快速替换和交换文本.
- [gbprod/yanky.nvim](https://github.com/gbprod/yanky.nvim) - 改进了 Yank 和 Put 功能.
- [sQVe/sort.nvim](https://github.com/sQVe/sort.nvim) - 智能支持按行和分隔符排序的排序插件.
- [booperlv/nvim-gomove](https://github.com/booperlv/nvim-gomove) - 一个完整的插件，用于移动和复制块和线，一次性完成折叠处理、重新缩进和撤消.
- [willothy/moveline.nvim](https://github.com/willothy/moveline.nvim)  - 轻松上下移动线条和块，移动时会自动处理缩进. 用 Rust 编写.
- [echasnovski/mini.nvim#mini.move](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-move.md)  - `mini.nvim` 模块可在任何方向移动任何选择（按字符、按行、按块、正常模式下的当前行）. 处理“v:count”和撤消历史记录.
- [anuvyklack/pretty-fold.nvim](https://github.com/anuvyklack/pretty-fold.nvim) - 折叠文本定制.
- [bennypowers/nvim-regexplainer](https://github.com/bennypowers/nvim-regexplainer) - 解释光标下的正则表达式.
- [gbprod/stay-in-place.nvim](https://github.com/gbprod/stay-in-place.nvim) - Neovim 插件可防止光标在使用移位和过滤操作时移动.
- [echasnovski/mini.nvim#mini.ai](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-ai.md)  - 用于扩展和创建“a”/“i”文本对象的“mini.nvim”模块. 它增强了一些内置文本对象，创建了一组广泛的新文本对象（如“a*”、“a<Space>  `、`a？` 等），并允许用户创建自己的（通过 Lua 模式或函数）. 支持点重复、不同的搜索方式、连续应用等.
- [Wansmer/treesj](https://github.com/Wansmer/treesj)  - 使用 Tree-Sitter 拆分/连接代码块，如数组、散列、语句、对象、字典等. 受到最伟大的 splitjoin.vim 的启发.
- [bennypowers/splitjoin.nvim](https://github.com/bennypowers/splitjoin.nvim) - 拆分和连接各种语法结构.
- [echasnovski/mini.nvim#mini.splitjoin](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-splitjoin.md)  - 用于拆分和连接参数的“mini.nvim”模块. 具有可定制的前钩和后钩. 在评论中起作用.
- [shortcuts/no-neck-pain.nvim](https://github.com/shortcuts/no-neck-pain.nvim) - 将当前聚焦的缓冲区置于终端的中间.
- [debugloop/telescope-undo.nvim](https://github.com/debugloop/telescope-undo.nvim) - 一个望远镜扩展，可以可视化您的撤消树和其中的模糊搜索变化.
- [chrisgrieser/nvim-various-textobjs](https://github.com/chrisgrieser/nvim-various-textobjs) - 大约十几个自定义文本对象的捆绑包.
- [XXiaoA/ns-textobject.nvim](https://github.com/XXiaoA/ns-textobject.nvim) - 很棒的文本对象插件可与 nvim-surround 配合使用.
- [~nedia/auto-save.nvim](https://git.sr.ht/~nedia/auto-save.nvim)  - 在“InsertLeave”和“TextChanged”上极其简单的自动保存. 基于 Pocco81/AutoSave 但更轻.
- [echasnovski/mini.nvim#mini.basics](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-basics.md) - `mini.nvim` 模块，具有用于常见选项、映射和自动命令的可自定义配置预设.
- [niuiic/part-edit.nvim](https://github.com/niuiic/part-edit.nvim) - 单独编辑文件的一部分.
- [niuiic/divider.nvim](https://github.com/niuiic/divider.nvim) - 自定义代码分隔线.
- [chrisgrieser/nvim-alt-substitute](https://github.com/chrisgrieser/nvim-alt-substitute)  - vim 的 `:substitute` 的替代品，使用 Lua 模式而不是 vim 正则表达式. 支持增量预览.
- [ckolkey/ts-node-action](https://github.com/ckolkey/ts-node-action) - 用于在 Tree-sitter 节点上执行功能转换的框架 - 具有许多用于转换文本的内置操作.

#### Comment

- [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim)  - 智能而强大的评论插件. 支持评论字符串、动作、点重复等.
- [b3nj5m1n/kommentary](https://github.com/b3nj5m1n/kommentary) - 用 Lua 编写的评论插件.
- [gennaro-tedesco/nvim-commaround](https://github.com/gennaro-tedesco/nvim-commaround) - 用 Lua 编写的快速、轻便的评论插件.
- [folke/todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - 突出显示、列出和搜索项目中的待办事项评论.
- [terrortylor/nvim-comment](https://github.com/terrortylor/nvim-comment) - 使用内置注释字符串选项切换注释.
- [winston0410/commented.nvim](https://github.com/winston0410/commented.nvim) - 一个评论插件，支持计数和多种评论模式等等.
- [s1n7ax/nvim-comment-frame](https://github.com/s1n7ax/nvim-comment-frame) - 在源文件的基础上添加注释框.
- [danymat/neogen](https://github.com/danymat/neogen)  - 更好的注释生成器. 支持多种语言和注释约定.
- [echasnovski/mini.nvim#mini.comment](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-comment.md)  - 用于每行注释的“mini.nvim”模块. 完全支持点重复.
- [LudoPinelli/comment-box.nvim](https://github.com/LudoPinelli/comment-box.nvim) - 使用方框和线条澄清和美化您的评论.
- [JoosepAlviste/nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)  - 根据文件中的光标位置设置“commentstring”选项. 通过树木管理员查询来检查位置.
- [LucasTavaresA/SingleComment.nvim](https://github.com/LucasTavaresA/SingleComment.nvim) - 始终单行，注释敏感，保留注释缩进.

### Formatting

- [gpanders/editorconfig.nvim](https://github.com/gpanders/editorconfig.nvim) - 用 Fennel 编写的 EditorConfig 插件.
- [mhartington/formatter.nvim](https://github.com/mhartington/formatter.nvim) - 用 Lua 编写的格式运行程序.
- [lukas-reineke/lsp-format.nvim](https://github.com/lukas-reineke/lsp-format.nvim) - Neovims 原生 LSP 格式的包装.
- [sbdchd/neoformat](https://github.com/sbdchd/neoformat) - 用于格式化代码的 (Neo)vim 插件.
- [cappyzawa/trim.nvim](https://github.com/cappyzawa/trim.nvim) - 该插件修剪尾随空白和线条.
- [mcauley-penney/tidy.nvim](https://github.com/mcauley-penney/tidy.nvim) - 每次保存时清除文件末尾的尾随空格和空行.
- [MunifTanjim/prettier.nvim](https://github.com/MunifTanjim/prettier.nvim) - 更漂亮的集成.
- [echasnovski/mini.nvim#mini.align](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-align.md) - 用于交互式对齐文本的“mini.nvim”模块（带或不带即时预览）.
- [emileferreira/nvim-strict](https://github.com/emileferreira/nvim-strict) - Strict, native code style formatting which exposes deep nesting, overlong lines, trailing whitespace, trailing empty lines, todos and inconsistent indentation.
- [~nedia/auto-format.nvim](https://git.sr.ht/~nedia/auto-format.nvim) - 本身不进行格式化，但设置自动命令以在保存时进行格式化，与 LSP 客户端格式化相比，更喜欢 null-ls.
- [tenxsoydev/tabs-vs-spaces.nvim](https://github.com/tenxsoydev/tabs-vs-spaces.nvim) - 提示并修复偏离的缩进.
- [bennypowers/svgo.nvim](https://github.com/bennypowers/svgo.nvim) - 优化 SVG 文件.

#### Indent

- [nvimdev/indentmini.nvim](https://github.com/nvimdev/indentmini.nvim) - 使用 nvim_set_decoration_provide api 的最小且快速的缩进插件.
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim) - Lua 中的 IndentLine 替换，具有更多功能和树木管理员支持.
- [LucasTavaresA/simpleIndentGuides.nvim](https://github.com/LucasTavaresA/simpleIndentGuides.nvim) - 使用内置变量的缩进指南.
- [echasnovski/mini.nvim#mini.indentscope](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-indentscope.md)  - 用于在缩进范围内可视化和操作的“mini.nvim”模块. 支持自定义去抖延迟、动画风格以及范围计算算法的不同粒度选项.
- [NMAC427/guess-indent.nvim](https://github.com/NMAC427/guess-indent.nvim) - 自动压痕样式检测.
- [Darazaki/indent-o-matic](https://github.com/Darazaki/indent-o-matic) - 用 Lua 编写的愚蠢的自动快速缩进检测.
- [Abstract-IDE/penvim](https://github.com/Abstract-IDE/penvim) - 项目的根目录和文档带有基于项目的配置加载器的缩进检测器.
- [yaocccc/nvim-hlchunk](https://github.com/yaocccc/nvim-hlchunk) - 突出显示“{}”块.
- [shellRaining/hlchunk.nvim](https://github.com/shellRaining/hlchunk.nvim) - `nvim-hlchunk` 的 Lua 实现，包含更多功能，例如突出显示 `{}` 块、缩进、空格等.

### Command Line

- [notomo/cmdbuf.nvim](https://github.com/notomo/cmdbuf.nvim) - 替代命令行窗口插件.
- [gelguy/wilder.nvim](https://github.com/gelguy/wilder.nvim) - 模糊命令行自动完成的插件.

### Session

- [rmagatti/auto-session](https://github.com/rmagatti/auto-session) - 一个小型自动化会话管理器.
- [echasnovski/mini.nvim#mini.sessions](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-sessions.md) - 用于会话管理的“mini.nvim”模块（读、写、删除）.
- [gennaro-tedesco/nvim-possession](https://github.com/gennaro-tedesco/nvim-possession) - 严肃的会话管理器.
- [olimorris/persisted.nvim](https://github.com/olimorris/persisted.nvim) - 简单的会话管理，具有 git 分支、自动保存/自动加载和 Telescope 支持.
- [Shatur/neovim-session-manager](https://github.com/Shatur/neovim-session-manager) - 围绕 :mksession 的简单包装.
- [jedrzejboczar/possession.nvim](https://github.com/jedrzejboczar/possession.nvim) - 灵活的会话管理，任意持久数据存储为 JSON.
- [niuiic/multiple-session.nvim](https://github.com/niuiic/multiple-session.nvim) - 提供多会话管理功能.
- [RutaTang/spectacle.nvim](https://github.com/RutaTang/spectacle.nvim) - 通过望远镜集成轻松管理多个会话.

### Remote Development

- [chipsenkbeil/distant.nvim](https://github.com/chipsenkbeil/distant.nvim) - 在舒适的本地环境中编辑文件、运行程序并在远程计算机上使用 LSP.
- [jamestthompson3/nvim-remote-containers](https://github.com/jamestthompson3/nvim-remote-containers) - 在 docker 容器内进行开发，就像 VSCode 一样.
- [esensar/nvim-dev-container](https://github.com/esensar/nvim-dev-container) - Neovim devcontainer.json 和一般开发容器支持.
- [miversen33/netman.nvim](https://github.com/miversen33/netman.nvim) - Lua 驱动的网络资源管理器.
- [OscarCreator/rsync.nvim](https://github.com/OscarCreator/rsync.nvim) - 使用 rsync 自动将上/下项目同步到远程.

### Split and Window

- [~henriquehbr/ataraxis.lua](https://sr.ht/~henriquehbr/ataraxis.lua) - 用于提高 Neovim 上代码可读性的禅宗模式.
- [gitlab.com/yorickpeterse/nvim-window](https://gitlab.com/yorickpeterse/nvim-window) - 在 Neovim 窗口之间轻松跳转.
- [sindrets/winshift.nvim](https://github.com/sindrets/winshift.nvim) - 轻松重新排列您的窗口.
- [beauwilliams/focus.nvim](https://github.com/beauwilliams/focus.nvim)  - 用 Lua 编写的自动聚焦和自动调整分割/窗口大小！  Vim 在类固醇的帮助下分裂了.
- [anuvyklack/windows.nvim](https://github.com/anuvyklack/windows.nvim)  - 自动扩展当前窗口的宽度. 最大化并恢复它. 所有这一切都带有精美的动画！
- [nvim-zh/colorful-winsep.nvim](https://github.com/nvim-zh/colorful-winsep.nvim) - 可配置的颜色分割线.
- [nyngwang/NeoNoName.lua](https://github.com/nyngwang/NeoNoName.lua) - 布局保留缓冲区删除.
- [famiu/bufdelete.nvim](https://github.com/famiu/bufdelete.nvim) - 删除 Neovim 缓冲区而不丢失窗口布局.
- [echasnovski/mini.nvim#mini.bufremove](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-bufremove.md) - `mini.nvim` 模块，用于在保存窗口布局时删除缓冲区（取消显示、删除、擦除）.

#### Tmux

- [aserowy/tmux.nvim](https://github.com/aserowy/tmux.nvim) - Tmux 集成具有窗格移动和大小调整功能.
- [danielpieper/telescope-tmuxinator.nvim](https://github.com/danielpieper/telescope-tmuxinator.nvim) - tmuxinator 与 Telescope.nvim 集成.
- [hkupty/nvimux](https://github.com/hkupty/nvimux) - Neovim 作为 tmux 的替代品.
- [numToStr/Navigator.nvim](https://github.com/numToStr/Navigator.nvim) - 在 Neovim 拆分和 Tmux 窗格之间平滑导航.
- [declancm/windex.nvim](https://github.com/declancm/windex.nvim) - 窗口功能集合，包括在 Neovim 分割和 Tmux 窗格之间移动、关闭和最大化.
- [otavioschwanck/tmux-awesome-manager.nvim](https://github.com/otavioschwanck/tmux-awesome-manager.nvim) - 运行您的工作流程命令，例如yarn install、rails console、yarn add、bundle install等.

### Game

- [ThePrimeagen/vim-be-good](https://github.com/ThePrimeagen/vim-be-good) - Vim-be-good 是一个 Neovim 插件，旨在让您更好地掌握 Vim 动作.
- [alec-gibson/nvim-tetris](https://github.com/alec-gibson/nvim-tetris) - 将 emacs 的最大功能引入 Neovim - 俄罗斯方块！.
- [seandewar/nvimesweeper](https://github.com/seandewar/nvimesweeper) - 在您最喜欢的文本编辑器中玩扫雷.
- [seandewar/killersheep.nvim](https://github.com/seandewar/killersheep.nvim) - 杀人羊的 Neovim 端口.
- [rktjmp/shenzhen-solitaire.nvim](https://github.com/rktjmp/shenzhen-solitaire.nvim) - Shenzhen I/O Solitaire port.
- [Eandrju/cellular-automaton.nvim](https://github.com/Eandrju/cellular-automaton.nvim) - 它可以让您根据 Neovim 缓冲区的内容执行美观的细胞自动机动画.
- [alanfortlink/blackjack.nvim](https://github.com/alanfortlink/blackjack.nvim) - 经典的黑杰克游戏.
- [jim-fx/sudoku.nvim](https://github.com/jim-fx/sudoku.nvim) - 经典数独谜题.

#### Competitive Programming

- [p00f/cphelper.nvim](https://github.com/p00f/cphelper.nvim) - Neovim 助手，用于用 Lua 编写的竞争性编程.
- [xeluxee/competitest.nvim](https://github.com/xeluxee/competitest.nvim) - 用于自动化测试用例管理和检查竞争性编程竞赛的插件.
- [Dhanus3133/Leetbuddy.nvim](https://github.com/Dhanus3133/Leetbuddy.nvim) - 解决 Neovim 中的 Leetcode 问题.

### Workflow

- [m4xshen/hardtime.nvim](https://github.com/m4xshen/hardtime.nvim) - 帮助您建立良好的指挥流程和习惯.
- [antonk52/bad-practices.nvim](https://github.com/antonk52/bad-practices.nvim) - 帮助您放弃 Vim 中的不良做法.

### Preconfigured Configuration

- [Abstract-IDE/Abstract](https://github.com/Abstract-IDE/Abstract) - 摘要，Neovim 配置实现了现代 IDE 的强大功能.
- [SpaceVim/SpaceVim](https://spacevim.org) - 社区驱动的模块化 Vim/Neovim 发行版，类似于 spacemacs，但适用于 Vim/Neovim.
- [CosmicNvim/CosmicNvim](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim is a lightweight and opinionated Neovim config for web development, specifically designed to provide a 💫 COSMIC programming experience!
- [artart222/CodeArt](https://github.com/artart222/CodeArt) - 完全用 Lua 编写的快速通用 IDE，带有适用于 Linux/Windows/macOS 的安装程序，并内置“:CodeArtUpdate”命令用于更新它.
- [LazyVim/LazyVim](https://github.com/LazyVim/LazyVim) - 由 **lazy.nvim** 提供支持的成熟 IDE，可轻松自定义和扩展您的配置.
- [NTBBloodbath/doom-nvim](https://github.com/NTBBloodbath/doom-nvim) - doom-emacs 框架的端口，其目标是向 Neovim 添加有用的功能，以便开始在稳定高效的开发环境中工作，而无需花费大量时间配置所有内容.
- [crivotz/nv-ide](https://github.com/crivotz/nv-ide) - Neovim 自定义配置，面向全栈开发人员（rails、ruby、php、html、css、SCSS、JavaScript）.
- [LunarVim/LunarVim](https://github.com/LunarVim/LunarVim) - 该项目旨在帮助人们从 VSCode 过渡到卓越的文本编辑体验.
- [hackorum/VapourNvim](https://github.com/hackorum/VapourNvim) - Neovim 配置，可实现类似 Vim IDE 的终极体验.
- [vi-tality/neovitality](https://github.com/vi-tality/neovitality) - 功能齐全的 Neovim 发行版，与 Nix Flake 打包在一起，易于安装和再现.
- [siduck76/NvChad](https://github.com/siduck76/NvChad) - 尝试使 Neovim cli 与 IDE 一样功能，同时非常美观且不那么臃肿.
- [nvoid-lua/nvoid](https://github.com/nvoid-lua/nvoid) - 用 Lua 编写的简单 Neovim 配置，具有任何 **IDE** 中可用的所有现代功能
- [cstsunfu/.sea.nvim](https://github.com/cstsunfu/.sea.nvim) - 模块化 Neovim 配置，具有漂亮的 UI 和一些有用的功能（番茄钟、窗口编号）.
- [shaeinst/roshnivim](https://github.com/shaeinst/roshnivim) - Roshnivim，可以称为 neovim 的发行版，是一个预定义的配置，因此您不需要 1000 小时将 neovim 设置为 IDE.
- [AstroNvim/AstroNvim](https://github.com/AstroNvim/AstroNvim) - AstroNvim 是一个美观且功能丰富的 Neovim 配置，可扩展且易于使用一组出色的插件.
- [shaunsingh/nyoom.nvim](https://github.com/shaunsingh/nyoom.nvim)  - 用 Fennel 编写的速度极快、可配置、最小且 lispy neovim 配置. 供用户扩展和添加的基本配置，带来更独特的编辑体验.
- [OxygeNvim/OxygeNvim](https://github.com/OxygeNvim/OxygeNvim) - 适用于各种开发的配置，具有坚如磐石的默认值.
- [jrychn/moduleVim](https://github.com/jrychn/ModuleVim) - 非常容易使用
  对于后端和前端，自动安装 lsp.
- [askfiy/nvim](https://github.com/askfiy/nvim) - 优秀的 Neovim 配置，与 Vscode 一样强大，快如闪电⚡️.
- [imbacraft/dusk.nvim](https://github.com/imbacraft/dusk.nvim) - Dusk 是一个轻量级、美观最小的 Neovim 配置，用 Lua 编写，能够提供 Web 和 Java 开发.
- [nvim-lua/kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) - 您个人 Neovim 配置的启动点.
- [cunderw/nvim](https://github.com/cunderw/nvim)  - Neovim 自定义配置，专注于 JS/TS、Go 和 Java 开发. 非常喜欢 IDE.
- [otavioschwanck/mood-nvim](https://github.com/otavioschwanck/mood-nvim) - Ruby on Rails、JavaScript 和 Typescript 的现成配置.
- [ldelossa/nvim-ide](https://github.com/ldelossa/nvim-ide) - 受 VSCode 启发的全功能 IDE 层.
- [jonathandion/web-dev.nvim](https://github.com/jonathandion/web-dev.nvim) - 用于 Web 开发的小型、简单且灵活的配置✨.
- [linrongbin16/lin.nvim](https://github.com/linrongbin16/lin.nvim) - 受 spf13-vim 启发，高度配置的 Neovim 发行版集成了大量用于开发的实用程序.
- [doctorfree/nvim-lazyman](https://github.com/doctorfree/nvim-lazyman) - Neovim 配置管理器和模块化配置，支持 40 多种预配置配置.

## External

这些工具在 Neovim 外部使用，以增强体验.

### Version Manager

- [MordechaiHadad/bob](https://github.com/MordechaiHadad/bob) - 跨平台且易于使用的 Neovim 版本管理器.
- [NTBBloodbath/nvenv](https://github.com/NTBBloodbath/nvenv) - 轻量级且速度极快的 Neovim 版本管理器.
- [shohi/neva](https://github.com/shohi/neva) - 用 Lua 编写的 Neovim 版本管理器.

### Boilerplate

- [gennaro-tedesco/boilit](https://github.com/gennaro-tedesco/boilit) - 创建样板结构插件.
- [m00qek/plugin-template.nvim](https://github.com/m00qek/plugin-template.nvim) - 设置测试基础设施和 GitHub Actions 的插件模板.
- [ellisonleao/nvim-plugin-template](https://github.com/ellisonleao/nvim-plugin-template) - 另一个neovim插件模板，使用GitHub的模板功能.

## Vim

- [Vimawesome](https://vimawesome.com/) - 展示 Vim 的各种插件，并有一个 [neovim tag](https://vimawesome.com/?q=tag:neovim) 对于其他针对 Neovim 的插件.
- [awesome-vim](https://github.com/akrawchyk/awesome-vim#tools) - Vim 插件和有用指南的简短列表.
- [vim-plugin-list](https://github.com/altermo/vim-plugin-list) - Vim 和 Neovim 插件列表.

## Resource

- [Neovimcraft](https://neovimcraft.com) - 一个专门搜索特定插件和在 Lua 中构建插件的指南的网站.
- [TWiN](https://this-week-in-neovim.org) - TWiN (this-week-in-neovim.org) 致力于提供有关 Neovim 及其生态系统的每周新闻.
- [Dotfyle](https://dotfyle.com) - Dotfyle 是一个用于共享和发现 Neovim 配置和插件的网站.
