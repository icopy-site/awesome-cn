<div class="github-widget" data-repo="rockerBOO/awesome-neovim"></div>
<!-- lint ignore awesome-git-repo-age -->

<img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" />

## Awesome Neovim [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- Uncomment the awesome badge when the repository is added to awesome main list.
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
-->

 &gt; 很棒的 Neovim 插件集合. 主要针对 Neovim 特定功能.

[Neovim](https://neovim.io/) 是一个基于 Vim 的文本编辑器，专为可扩展性和可用性而设计，以鼓励新的应用程序和贡献.



## Wishlist

有插件可以解决的问题吗？ 将其添加到 [nvim-lua wishlist](https://github.com/nvim-lua/wishlist).

## UI

Neovim 支持多种 UI.
您可以在 [Neovim wiki](https://github.com/neovim/neovim/wiki/Related-projects#gui)

## Plugin

### Plugin Manager

- [wbthomason/packer.nvim](https://github.com/wbthomason/packer.nvim)  - 受使用包启发的插件管理器. 使用本机包，支持 Luarocks 依赖项，用 Lua 编写，允许进行富有表现力的配置.
- [savq/paq-nvim](https://github.com/savq/paq-nvim) - 用 Lua 编写的 Neovim 包管理器.
- [NTBBloodbath/cheovim](https://github.com/NTBBloodbath/cheovim)  - 用 Lua 编写的 Neovim 配置切换器. 灵感来自化学.
- [chiyadev/dep](https://github.com/chiyadev/dep)  - packer.nvim 的替代品. 它被构建为更好、更易于使用. 可以找到上下文 [here](https://chiya.dev/posts/2021-11-27-why-package-manager).
- [folke/lazy.nvim](https://github.com/folke/lazy.nvim) - 现代插件管理器，具有图形界面、异步执行、锁定文件等功能.

### LSP

#### (requires Neovim 0.5)

- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - LSP 客户端的快速启动配置.
- [nvim-lua/lsp-status.nvim](https://github.com/nvim-lua/lsp-status.nvim) - 这是一个用于从内置 LSP 客户端生成状态行组件的插件/库.
- [RishabhRD/nvim-lsputils](https://github.com/RishabhRD/nvim-lsputils) - nvim-lsp 操作的更好默认值.
- [glepnir/lspsaga.nvim](https://github.com/glepnir/lspsaga.nvim) - 基于 Neovim 内置 LSP 的轻量级 LSP 插件，具有高性能 UI.
- [kosayoda/nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb) - 只要当前光标位置有“textDocument/codeAction”可用，插件就会在符号栏中显示一个灯泡.
- [onsails/lspkind.nvim](https://github.com/onsails/lspkind.nvim) - 该插件向 Neovim LSP 补全添加了类似 vscode 的图标.
- [ojroques/nvim-lspfuzzy](https://github.com/ojroques/nvim-lspfuzzy) - 使 LSP 客户端使用 FZF 的小插件.
- [gfanto/fzf-lsp.nvim](https://github.com/gfanto/fzf-lsp.nvim) - 为 LSP 内置的 Neovim 启用 FZF 模糊搜索的功能.
- [ray-x/lsp_signature.nvim](https://github.com/ray-x/lsp_signature.nvim) - 键入时 LSP 签名提示.
- [smjonas/inc-rename.nvim](https://github.com/smjonas/inc-rename.nvim) - 提供基于 Neovim 的命令预览功能的增量 LSP 重命名命令.
- [rmagatti/goto-preview](https://github.com/rmagatti/goto-preview) - 在浮动窗口中预览本机 LSP 的 goto 定义调用.
- [jubnzv/virtual-types.nvim](https://github.com/jubnzv/virtual-types.nvim) - 将类型注释显示为虚拟文本.
- [jose-elias-alvarez/typescript.nvim](https://github.com/jose-elias-alvarez/typescript.nvim) - 用于改善 Neovim 内置 LSP 客户端的 TypeScript 开发体验的实用程序.
- [ray-x/navigator.lua](https://github.com/ray-x/navigator.lua)  - 快速学习现有代码并轻而易举地浏览代码. 瑞士军刀使探索 LSP 和 Treesitter 符号成为 .
- [simrat39/symbols-outline.nvim](https://github.com/simrat39/symbols-outline.nvim)  - 使用语言服务器协议的树状视图符号. 支持所有您喜欢的语言.
- [stevearc/aerial.nvim](https://github.com/stevearc/aerial.nvim) - 用于略读和快速导航的代码大纲窗口.
- [SmiteshP/nvim-navbuddy](https://github.com/SmiteshP/nvim-navbuddy) - 一个简单的弹出式显示，使用 LSP 提供类似导航功能的面包屑.
- [tamago324/nlsp-settings.nvim](https://github.com/tamago324/nlsp-settings.nvim) - 使用 JSON 或 YAML 文件设置 LSP.
- [jose-elias-alvarez/null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim) - 使用 Neovim 作为语言服务器，通过 Lua 注入 LSP 诊断、代码操作等.
- [jakewvincent/texmagic.nvim](https://github.com/jakewvincent/texmagic.nvim) - 通过定义任意数量的自定义 LaTeX 构建引擎并使用魔术注释选择它们来增强 Texlab 的 lspconfig 设置.
- [nanotee/nvim-lsp-basics](https://github.com/nanotee/nvim-lsp-basics) - LSP 功能的基本包装器.
- [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu) - 用于代码操作的浮动弹出菜单，用于显示代码操作信息和差异预览.
- [mfussenegger/nvim-lint](https://github.com/mfussenegger/nvim-lint) - 一个异步 linter 插件，与内置的语言服务器协议支持相辅相成.
- [b0o/SchemaStore.nvim](https://github.com/b0o/SchemaStore.nvim) - 提供对 [SchemaStore](https://github.com/SchemaStore/schemastore) 目录.
- [ldelossa/litee.nvim](https://github.com/ldelossa/litee.nvim) - Neovim 缺少的 IDE 功能.
- [j-hui/fidget.nvim](https://github.com/j-hui/fidget.nvim) - 用于 LSP 进度的独立 UI.
- [scalameta/nvim-metals](https://github.com/scalameta/nvim-metals) - 用于 Metals 的 Neovim 插件，Scala 语言服务器，使用 Neovim 的内置 LSP.
- [junnplus/nvim-lsp-setup](https://github.com/Junnplus/nvim-lsp-setup) - nvim-lspconfig 和 nvim-lsp-installer 的简单包装器，可轻松设置 LSP 服务器.
- [amrbashir/nvim-docs-view](https://github.com/amrbashir/nvim-docs-view) - 在侧面板中显示 LSP 悬停文档.
- [mfussenegger/nvim-jdtls](https://github.com/mfussenegger/nvim-jdtls) - 对 eclipse.jdt.ls 的内置 LSP 支持的扩展.
- [Kasama/nvim-custom-diagnostic-highlight](https://github.com/Kasama/nvim-custom-diagnostic-highlight) - 内联诊断弹出突出显示很像 coc-nvim，但基于 `vim.diagnostic`.
- [MrcJkb/haskell-tools.nvim](https://github.com/MrcJkb/haskell-tools.nvim) - Neovim 与 Haskell 开发工具（如 haskell-language-server 和 Hoogle）的无缝集成.
- [ranjithshegde/ccls.nvim](https://github.com/ranjithshegde/ccls.nvim) - 使用 ccls LSP 的非规范扩展并浏览 AST.
- [idanarye/nvim-buffls](https://github.com/idanarye/nvim-buffls) - 将 LSP 功能添加到特定的 Neovim 缓冲区.
- [DNLHC/glance.nvim](https://github.com/DNLHC/glance.nvim) - 用于预览、导航和编辑 LSP 位置的漂亮窗口.
- [linrongbin16/lsp-progress.nvim](https://github.com/linrongbin16/lsp-progress.nvim) - Neovim 的另一个 lsp 进度状态.
- [jinzhongjia/LspUI.nvim](https://github.com/jinzhongjia/LspUI.nvim) - 包装 LSP 操作的现代且有用的 UI.

##### LSP Installer

- [anott03/nvim-lspinstall](https://github.com/anott03/nvim-lspinstall) - 易于安装语言服务器.
- [alexaandru/nvim-lspupdate](https://github.com/alexaandru/nvim-lspupdate) - 更新安装（或自动安装，如果缺少）LSP 服务器.
- [williamboman/mason.nvim](https://github.com/williamboman/mason.nvim)  - 可在 Neovim 运行的任何地方运行的便携式包管理器. 轻松安装和管理 LSP 服务器、DAP 服务器、linter 和格式化程序.

##### Diagnostics

- [andrewferrier/textobj-diagnostic](https://github.com/andrewferrier/textobj-diagnostic.nvim) - 用于诊断的文本对象（例如由 LSP 服务器生成的文本对象）.
- [~whynothugo/lsp_lines.nvim](https://git.sr.ht/~whynothugo/lsp_lines.nvim) - 在真实代码行之上使用虚拟行呈现诊断.
- [onsails/diaglist.nvim](https://github.com/onsails/diaglist.nvim) - quickfix 中的实时渲染工作区诊断，loclist 中的缓冲区诊断.
- [folke/trouble.nvim](https://github.com/folke/trouble.nvim) - 一个漂亮的诊断列表，可帮助您解决代码引起的所有问题.
- [folke/lsp-colors.nvim](https://github.com/folke/lsp-colors.nvim) - 为尚不支持内置 LSP 客户端的配色方案添加缺少的 LSP 诊断突出显示组的插件.

### Completion

- [ms-jpq/coq_nvim](https://github.com/ms-jpq/coq_nvim)  - 快如他妈的 Neovim 完成.  SQLite，并发调度程序，数百小时的优化.
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp)  - 用 Lua 编写的完成插件. 新版本的 nvim-compe.
  - [lukas-reineke/cmp-under-comparator](https://github.com/lukas-reineke/cmp-under-comparator) - 用于更好排序的 nvim-cmp 函数.
- [echasnovski/mini.nvim#mini.completion](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-completion.md)  - 用于异步两阶段完成的 `mini.nvim` 模块. 支持显示完成项信息和独立函数签名.
- [noib3/nvim-compleet](https://github.com/noib3/nvim-compleet) - 用 Rust 编写的 Neovim 自动完成框架.
- [vigoux/complementree.nvim](https://github.com/vigoux/complementree.nvim) - 基于 tree-sitter 和功能编程接口的轻型同步完成插件.
- [simrat39/rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - 使用 Neovim 的内置 LSP 在 Rust 中更好地开发的工具.
- [zbirenbaum/copilot.lua](https://github.com/zbirenbaum/copilot.lua) - 功能齐全的 Lua 替代品 [GitHub/copilot.vim](https://github.com/github/copilot.vim).

### Programming Languages Support

- [Julian/lean.nvim](https://github.com/Julian/lean.nvim) - Neovim 支持 [Lean Theorem Prover](https://leanprover.github.io/).
- [akinsho/flutter-tools.nvim](https://github.com/akinsho/flutter-tools.nvim) - 使用原生 LSP 构建 Flutter 和 Dart 应用程序.
- [gbprod/phpactor.nvim](https://github.com/gbprod/phpactor.nvim) - Lua 版本的 Phpactor Vim 插件可利用最新的 Neovim 功能.
- [brendalf/mix.nvim](https://github.com/brendalf/mix.nvim) - 混合（来自 Elixir）包装器插件.
- [AckslD/swenv.nvim](https://github.com/AckslD/swenv.nvim) - 无需重启即可快速切换 Python 虚拟环境的微型插件.
- [gennaro-tedesco/nvim-jqx](https://github.com/gennaro-tedesco/nvim-jqx) - JSON 文件的交互界面.
- [nanotee/sqls.nvim](https://github.com/nanotee/sqls.nvim) - SQL 数据库连接插件 + LSP 客户端.

#### Golang

- [ray-x/go.nvim](https://github.com/ray-x/go.nvim) - 基于 lsp 和 Treesitter 的 Golang 插件.
- [crusj/structrue-go.nvim](https://github.com/crusj/structrue-go.nvim) - 更好地结构化显示 Golang 符号信息.
- [crispgm/nvim-go](https://github.com/crispgm/nvim-go) - Golang 开发插件的最小实现.
- [edolphin-ydf/goimpl.nvim](https://github.com/edolphin-ydf/goimpl.nvim) - 为类型生成接口存根.
- [olexsmir/gopher.nvim](https://github.com/olexsmir/gopher.nvim/) - 使 Golang 开发最简单的插件.
- [rafaelsq/nvim-goc.lua](https://github.com/rafaelsq/nvim-goc.lua) - 使用 Golang 代码覆盖率突出显示您的缓冲区.
- [crusj/hierarchy-tree-go.nvim](https://github.com/crusj/hierarchy-tree-go.nvim) - Golang 的 Neovim 插件，调用层次结构 UI 树.

#### YAML

- [someone-stole-my-name/yaml-companion.nvim](https://github.com/someone-stole-my-name/yaml-companion.nvim) - 获取、设置和自动检测缓冲区中的 YAML 架构.
- [cuducos/yaml.nvim](https://github.com/cuducos/yaml.nvim) - 用于处理 YAML 文件的实用程序.

#### Web Development

- [NTBBloodbath/rest.nvim](https://github.com/NTBBloodbath/rest.nvim) - 用 Lua 编写的快速 Neovim HTTP 客户端.
- [ray-x/web-tools.nvim](https://github.com/ray-x/web-tools.nvim) - 启动具有静态和动态页面实时重新加载功能的本地开发服务器，使用 LSP 重命名 HTML 和 CSS 标签.

#### Markdown and LaTeX

- [ellisonleao/glow.nvim](https://github.com/ellisonleao/glow.nvim) - 使用发光的 Markdown 预览.
- [iamcco/markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim) - 通过同步滚动和灵活配置在您的现代浏览器上预览降价.
- [davidgranstrom/nvim-markdown-preview](https://github.com/davidgranstrom/nvim-markdown-preview) - 通过 Neovim 的作业控制 API 使用 pandoc 和 live-server 在浏览器中进行 Markdown 预览.
- [jghauser/auto-pandoc.nvim](https://github.com/jghauser/auto-pandoc.nvim) - 利用 yaml 块轻松进行 pandoc 转换.
- [jghauser/follow-md-links.nvim](https://github.com/jghauser/follow-md-links.nvim) - 按回车键进入内部降价链接.
- [jubnzv/mdeval.nvim](https://github.com/jubnzv/mdeval.nvim) - 评估降价文档中的代码块.
- [kdheepak/panvimdoc](https://github.com/kdheepak/panvimdoc) - 从 pandoc 到 vimdoc GitHub 操作.
- [frabjous/knap](https://github.com/frabjous/knap) - 用于为 markdown、LaTeX 和其他文档创建自动更新的插件预览.
- [jbyuki/carrot.nvim](https://github.com/jbyuki/carrot.nvim) - Markdown 评估器 Lua 代码块.
- [AckslD/nvim-FeMaco.lua](https://github.com/AckslD/nvim-FeMaco.lua) - 促进您的 Fenced Markdown 代码块编辑.
- [NFrid/markdown-togglecheck](https://github.com/NFrid/markdown-togglecheck) - 使用 Treesitter 切换复选框的简单 Neovim 插件.
- [toppair/peek.nvim](https://github.com/toppair/peek.nvim) - 在 webview 窗口中预览降价.

### Language

- [potamides/pantran.nvim](https://github.com/potamides/pantran.nvim) - 使用交互式翻译窗口翻译您的文本.
- [niuiic/translate.nvim](https://github.com/niuiic/translate.nvim) - 通过 shell 命令调用任何翻译引擎.

### Syntax

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Treesitter 配置和抽象层.
- [nvim-treesitter/nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - 使用树保姆查询创建您自己的文本对象.
- [RRethy/nvim-treesitter-textsubjects](https://github.com/RRethy/nvim-treesitter-textsubjects) - 位置和语法感知文本对象，_do what you mean_.
- [kylechui/nvim-surround](https://github.com/kylechui/nvim-surround) - 用于添加/更改/删除周围分隔符对的插件.
- [echasnovski/mini.nvim#mini.surround](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-surround.md)  - 用于处理文本环境（添加、删除、替换、查找、突出显示）的 `mini.nvim` 模块. 支持点重复、不同的搜索方法、“last”/“next”扩展映射、tree-sitter 集成等.
- [m-demare/hlargs.nvim](https://github.com/m-demare/hlargs.nvim) - 使用 Treesitter 突出显示参数的定义和用法.
- [LhKipp/nvim-nu](https://github.com/LhKipp/nvim-nu) - 对 nushell 语言的基本编辑器支持.
- [desdic/agrolens.nvim](https://github.com/desdic/agrolens.nvim) - 使用 Telescope 通过 Tree-sitter 节点导航.

### Snippet

- [norcalli/snippets.nvim](https://github.com/norcalli/snippets.nvim) - Lua 中的片段.
- [L3MON4D3/LuaSnip](https://github.com/L3MON4D3/LuaSnip) - 用 Lua 编写的片段引擎.
- [smjonas/snippet-converter.nvim](https://github.com/smjonas/snippet-converter.nvim) - 在最常见的代码片段格式之间转换代码片段，并使用几行 Lua 代码修改它们.
- [dcampos/nvim-snippy](https://github.com/dcampos/nvim-snippy) - 用 Lua 编写的代码片段插件，支持 [vim-snippets](https://github.com/honza/vim-snippets).
- [ellisonleao/carbon-now.nvim](https://github.com/ellisonleao/carbon-now.nvim) - 直接从 Neovim 创建漂亮的代码片段.

### Register

- [gennaro-tedesco/nvim-peekup](https://github.com/gennaro-tedesco/nvim-peekup) - 与 Vim 寄存器动态交互.
- [tversteeg/registers.nvim](https://github.com/tversteeg/registers.nvim) - Vim 寄存器的非干扰性最小预览.
- [acksld/nvim-neoclip.lua](https://github.com/AckslD/nvim-neoclip.lua) - 带有望远镜集成的剪贴板管理器 Neovim 插件.
- [tenxsoydev/karen-yank.nvim](https://github.com/tenxsoydev/karen-yank.nvim) - 使用删除、剪切和抽取映射进行更多有意的寄存器处理.

### Marks

- [cbochs/grapple.nvim](https://github.com/cbochs/grapple.nvim) - 提供标记、光标跟踪和对重要项目文件的即时导航.
- [chentoast/marks.nvim](https://github.com/chentoast/marks.nvim) - 更好的用户体验来查看 Vim 标记并与之交互.
- [ThePrimeagen/harpoon](https://github.com/ThePrimeagen/harpoon) - 每个项目、自动更新和可编辑标记实用程序，用于快速文件导航.
- [ofirgall/open.nvim](https://github.com/ofirgall/open.nvim) - 使用自定义开启器打开当前单词，例如 GitHub 速记.
- [LeonHeidelbach/trailblazer.nvim](https://github.com/LeonHeidelbach/trailblazer.nvim) - TrailBlazer 引入了基于堆栈的标记系统，该系统使用项目范围标记实现全新的动态和超快速工作流程.
- [tomasky/bookmarks.nvim](https://github.com/tomasky/bookmarks.nvim) - 带有全局文件存储的书签，用 Lua 编写.

### Search

- [kevinhwang91/nvim-hlslens](https://github.com/kevinhwang91/nvim-hlslens) - 帮助您更好地浏览搜索到的信息，无缝跳转匹配的实例.
- [rktjmp/highlight-current-n.nvim](https://github.com/rktjmp/highlight-current-n.nvim)  - 突出显示当前 /, ? 或 \* 在按 n 或 N 时匹配光标下的内容，然后让开.
- [gaborvecsei/memento.nvim](https://github.com/gaborvecsei/memento.nvim)  - 在缓冲区关闭后跟踪您访问过的文件历史记录. 更轻松地重新打开文件.
- [ray-x/sad.nvim](https://github.com/ray-x/sad.nvim)  - neovim 中的太空时代 seD. 批处理文件编辑工具，一个包装器 [sad](https://github.com/ms-jpq/sad)
- [s1n7ax/nvim-search-and-replace](https://github.com/s1n7ax/nvim-search-and-replace) - 从当前工作目录同时搜索和替换多个文件.
- [roobert/search-replace.nvim](https://github.com/roobert/search-replace.nvim) - 为原生搜索和替换体验带来更好的功能.

### Fuzzy Finder

- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim 是一个高度 [extendable](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) 列表上的模糊查找器. 基于 Neovim 核心的最新强大功能构建.  Telescope 以模块化为中心，允许轻松定制.
- [vijaymarupudi/nvim-fzf](https://github.com/vijaymarupudi/nvim-fzf)  - 一个用于使用 FZF (Neovim &gt;= 0.5) 的 Lua API. 允许 UI 速度和可用性的完全异步.
- [camspiers/snap](https://github.com/camspiers/snap)  - 一个可扩展的模糊查找器. 类似于 Telescope，并针对性能进行了优化，尤其是在大型代码库中进行 grepping 时.
- [ibhagwan/fzf-lua](https://github.com/ibhagwan/fzf-lua)  - `fzf.vim` 的 Lua 版本，高性能和完全异步，支持 `nvim-web-devicons`、git 指标、LSP、quickfix/位置列表等. 还支持 [`skim`](https://github.com/lotabout/skim) 作为它的 fzf 二进制文件.
- [jvgrootveld/telescope-zoxide](https://github.com/jvgrootveld/telescope-zoxide) - 望远镜整合 [zoxide](https://github.com/ajeetdsouza/zoxide)，一个跟踪您的使用情况的智能目录选择器.
- [echasnovski/mini.nvim#mini.fuzzy](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-fuzzy.md) - `mini.nvim` 模块，具有执行一个字符串与其他字符串的模糊匹配以及快速 Telescope 排序器的功能.
- [axkirillov/easypick.nvim](https://github.com/axkirillov/easypick.nvim) - Easypick 可让您从任意控制台命令轻松创建望远镜拾取器.

### File Explorer

- [kyazdani42/nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - 一个简单快速的文件浏览器树.
- [luukvbaal/nnn.nvim](https://github.com/luukvbaal/nnn.nvim) - 文件浏览器由 [nnn](https://github.com/jarun/nnn) 和路亚.
- [tamago324/lir.nvim](https://github.com/tamago324/lir.nvim) - 简单的文件浏览器.
- [TimUntersberger/neofs](https://github.com/TimUntersberger/neofs) - 用 Lua 编写的文件管理器.
- [kevinhwang91/rnvimr](https://github.com/kevinhwang91/rnvimr) - 一个简单但令人惊叹的文件浏览器.
- [Xuyuanp/yanil](https://github.com/Xuyuanp/yanil) - Lua 中的另一个 Nerdtree.
- [ms-jpq/chadtree](https://github.com/ms-jpq/chadtree)  - 文件管理器. 比 NERDTree 更好.
- [is0n/fm-nvim](https://github.com/is0n/fm-nvim) - Neovim 插件，可让您使用自己喜欢的终端文件管理器（和模糊查找器）.
- [nvim-neo-tree/neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim) - Neo-tree 是一个 Neovim 插件，用于以适合您的任何样式浏览文件系统和其他树状结构，包括侧边栏、浮动窗口、netrw 拆分样式，或同时浏览所有这些.
- [elihunter173/dirbuf.nvim](https://github.com/elihunter173/dirbuf.nvim) - 一个文件管理器，可让您像编辑文本一样编辑文件系统.
- [theblob42/drex.nvim](https://github.com/TheBlob42/drex.nvim) - 一个用 Lua 编写的简单且可配置的文件浏览器.
- [SidOfc/carbon.nvim](https://github.com/SidOfc/carbon.nvim) - 用 Lua 编写的简单目录树查看器.
- [dinhhuy258/sfm.nvim](https://github.com/dinhhuy258/sfm.nvim) - Nvim-tree 的替代品，设计为可扩展和极简主义.
- [kiran94/s3edit.nvim](https://github.com/kiran94/s3edit.nvim) - 直接从 Neovim 编辑来自 Amazon S3 的文件.
- [stevearc/oil.nvim](https://github.com/stevearc/oil.nvim) - 像缓冲区一样编辑你的文件系统.
- [EdvinVikstrom/filetree.nvim](https://github.com/EdvinVikstrom/filetree.nvim) - 一个漂亮且快速的文件管理器，易于定制.

### Project

- [pluffie/neoproj](https://github.com/pluffie/neoproj) - 小而强大的项目（和会议）经理.
- [shaeinst/penvim](https://github.com/shaeinst/penvim) - 项目的根目录和文档缩进检测器，带有基于项目的配置加载器.
- [nyngwang/NeoRoot.lua](https://github.com/nyngwang/NeoRoot.lua) - 将当前工作目录更改为光标所在的缓冲区，并尝试上升 2 个级别，但在遇到您定义的项目根目录之一后停止.
- [windwp/nvim-projectconfig](https://github.com/windwp/nvim-projectconfig) - 根据项目目录加载 Neovim 配置.
- [windwp/nvim-spectre](https://github.com/windwp/nvim-spectre) - 搜索和替换面板.
- [ahmedkhalf/project.nvim](https://github.com/ahmedkhalf/project.nvim) - 提供卓越项目管理的多合一 Neovim 插件.
- [klen/nvim-config-local](https://github.com/klen/nvim-config-local) - 从工作目录安全加载本地配置文件.
- [cljoly/telescope-repo.nvim](https://cj.rs/telescope-repo-nvim/) - 望远镜选择器跳转到文件系统上的任何存储库（git 或其他）.
- [MunifTanjim/exrc.nvim](https://github.com/MunifTanjim/exrc.nvim) - 保护项目本地配置.
- [otavioschwanck/telescope-alternate.nvim](https://github.com/otavioschwanck/telescope-alternate.nvim) - 使用望远镜在普通文件之间交替.
- [natecraddock/workspaces.nvim](https://github.com/natecraddock/workspaces.nvim) - 管理工作区目录.
- [gnikdroy/projections.nvim](https://github.com/gnikdroy/projections.nvim) - 小型项目 + 会话管理器.
- [nyngwang/suave.lua](https://github.com/nyngwang/suave.lua) - 多标签项目会话自动化.
- [desdic/telescope-rooter.nvim](https://github.com/desdic/telescope-rooter.nvim) - 确保始终从项目/根目录启动望远镜（并且仅启动望远镜）.
- [jinzhongjia/PS_manager.nvim](https://github.com/jinzhongjia/PS_manager.nvim) - 多项目管理，自动切换密码.

### Color

- [NvChad/nvim-colorizer.lua](https://github.com/NvChad/nvim-colorizer.lua) - 没有外部依赖性的高性能彩色荧光笔！
- [sunjon/Shade.nvim](https://github.com/sunjon/Shade.nvim) - Shade 是一个 Neovim 插件，可以使非活动窗口变暗，使活动窗口一目了然.
- [winston0410/range-highlight.nvim](https://github.com/winston0410/range-highlight.nvim) - 一个非常轻量级的插件 (~ 120loc)，突出显示您在命令行中输入的范围.
- [xiyaowong/nvim-transparent](https://github.com/xiyaowong/nvim-transparent) - 让你的 Neovim 透明.
- [folke/twilight.nvim](https://github.com/folke/twilight.nvim) - 使用 TreeSitter 淡化您正在编辑的代码的非活动部分.
- [koenverburg/peepsight.nvim](https://github.com/koenverburg/peepsight.nvim) - 仅关注光标所在的功能.
- [uga-rosa/ccc.nvim](https://github.com/uga-rosa/ccc.nvim) - 超级强大的颜色选择器/着色器插件.
- [ziontee113/color-picker.nvim](https://github.com/ziontee113/color-picker.nvim) - 允许用户在 Neovim 中选择和修改 RGB/HSL/HEX 颜色的插件.
- [lcheylus/overlength.nvim](https://github.com/lcheylus/overlength.nvim) - 一个小插件来突出显示太长的行.
- [brenoprata10/nvim-highlight-colors](https://github.com/brenoprata10/nvim-highlight-colors) - 使用 Neovim 突出显示颜色的插件.
- [nvim-colortils/colortils.nvim](https://github.com/nvim-colortils/colortils.nvim) - 一个提供实用程序的插件，用于在 Neovim 中处理颜色（选择器、转换）.

### Colorscheme

#### Tree-sitter Supported Colorscheme

 Tree-sitter 是 Neovim 0.5 中引入的一个新系统，它可以逐步将你的代码解析成一棵可以工作的树，即使你的语法有错误. 这些配色方案专门为 Tree-sitter 高亮组设置了颜色.  Vim colorschemes 将开箱即用地与新组一起使用.

- [shaeinst/roshnivim-cs](https://github.com/shaeinst/roshnivim-cs) - 用 Lua 编写的 Colorscheme，专为 roshnivim 制作，支持 Tree-sitter.
- [rafamadriz/neon](https://github.com/rafamadriz/neon)  - 可定制的配色方案，具有出色的斜体和粗体支持、深色和浅色变体. 与 Tree-sitter 一起工作并看起来很棒.
- [tomasiser/vim-code-dark](https://github.com/tomasiser/vim-code-dark) - 深色配色方案深受 Visual Studio Code 深色+ 方案外观的启发.
- [Mofiqul/vscode.nvim](https://github.com/Mofiqul/vscode.nvim) - 带有 vscode 浅色和深色主题的 vim-code-dark colorscheme 的 Lua 端口.
- [marko-cerovac/material.nvim](https://github.com/marko-cerovac/material.nvim) - Material.nvim 是一个高度可配置的配色方案，用 Lua 编写，基于材质调色板.
- [bluz71/vim-nightfly-colors](https://github.com/bluz71/vim-nightfly-colors) - 深色午夜配色方案，支持包括 Tree-sitter 在内的现代 Neovim.
- [bluz71/vim-moonfly-colors](https://github.com/bluz71/vim-moonfly-colors) - 具有现代 Neovim 支持（包括 Tree-sitter）的深色木炭配色方案.
- [ChristianChiarulli/nvcode-color-schemes.vim](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - 具有 Tree-sitter 支持的 Nvcode、onedark、nord 配色方案.
- [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - 一个用 Lua 编写的干净、深色和浅色的 Neovim 主题，支持 LSP、Tree-sitter 和许多插件.
- [sainnhe/sonokai](https://github.com/sainnhe/sonokai) - 基于 Monokai Pro 的高对比度和生动的配色方案.
- [nyoom-engineering/oxocarbon.nvim](https://github.com/nyoom-engineering/oxocarbon.nvim) - 受 IBM Carbon 启发，用茴香编写的深色和浅色 Neovim 主题.
- [kyazdani42/blue-moon](https://github.com/kyazdani42/blue-moon) - 源自 palenight 和 carbonight 的深色配色方案.
- [mhartington/oceanic-next](https://github.com/mhartington/oceanic-next) - 海洋下一个主题.
- [glepnir/zephyr-nvim](https://github.com/glepnir/zephyr-nvim) - 支持树保姆的深色配色方案.
- [rockerBOO/boo-colorscheme-nvim](https://github.com/rockerBOO/boo-colorscheme-nvim) - 手工支持 LSP、Tree-sitter 的配色方案.
- [jim-at-jibba/ariake-vim-colors](https://github.com/jim-at-jibba/ariake-vim-colors)  - 伟大的 Atom 主题的端口. 有 Tree-sitter 支持的黑暗和光明.
- [Th3Whit3Wolf/onebuddy](https://github.com/Th3Whit3Wolf/onebuddy) - 光暗原子同一个主题.
- [ishan9299/modus-theme-vim](https://github.com/ishan9299/modus-theme-vim) - 这是 Protesilaos Stavrou 为 emacs 开发的配色方案.
- [sainnhe/edge](https://github.com/sainnhe/edge) - 干净优雅的配色方案，灵感来自 Atom One 和 Material.
- [theniceboy/nvim-deus](https://github.com/theniceboy/nvim-deus) - 支持 Tree-sitter 的 Vim-deus.
- [bkegley/gloombuddy](https://github.com/bkegley/gloombuddy) - Gloom 启发主题.
- [Th3Whit3Wolf/one-nvim](https://github.com/Th3Whit3Wolf/one-nvim) - 受原子一号启发的深色和浅色配色方案.
- [PHSix/nvim-hybrid](https://github.com/PHSix/nvim-hybrid) - 用 Lua 编写的 Neovim 配色方案.
- [Th3Whit3Wolf/space-nvim](https://github.com/Th3Whit3Wolf/space-nvim) - 受 spacemacs 启发的深色和浅色配色方案.
- [yonlu/omni.vim](https://github.com/yonlu/omni.vim) - Vim 的 Omni 配色方案.
- [ray-x/aurora](https://github.com/ray-x/aurora) - 支持 Tree-sitter 和 LSP 的 24 位深色主题.
- [ray-x/starry.nvim](https://github.com/ray-x/starry.nvim) - 现代 Neovim 配色方案的集合：材料、月光、德古拉（血）、莫诺凯、马里亚纳、祖母绿、早夏、午夜蓝、暗太阳.
- [tanvirtin/monokai.nvim](https://github.com/tanvirtin/monokai.nvim) - 用 Lua 编写的 Monokai 主题.
- [ofirgall/ofirkai.nvim](https://github.com/ofirgall/ofirkai.nvim) - 旨在感觉像 Sublime Text 的 Monokai 主题.
- [savq/melange-nvim](https://github.com/savq/melange-nvim) - 用 Lua 编写的暖色方案，支持各种终端仿真器.
- [RRethy/nvim-base16](https://github.com/RRethy/nvim-base16)  - 用于构建 base16 配色方案的 Neovim 插件. 包括对 Treesitter 和 LSP 高亮组的支持.
- [fenetikm/falcon](https://github.com/fenetikm/falcon) - 终端、Vim 和朋友的配色方案.
- [andersevenrud/nordic.nvim](https://github.com/andersevenrud/nordic.nvim) - 一个 nord-esque colorscheme.
- [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) - 基于 Nord 调色板的 Neovim 主题.
- [svrana/neosolarized.nvim](https://github.com/svrana/neosolarized.nvim) - 使用 colorbuddy 的深色日光配色方案，便于定制.
- [ishan9299/nvim-solarized-lua](https://github.com/ishan9299/nvim-solarized-lua) - Lua 中的曝光配色方案（Neovim &gt;= 0.5）.
- [shaunsingh/moonlight.nvim](https://github.com/shaunsingh/moonlight.nvim) - VSCode 的 Moonlight 配色方案的端口，用 Lua 编写，内置支持原生 LSP、Tree-sitter 和更多插件.
- [navarasu/onedark.nvim](https://github.com/navarasu/onedark.nvim) - 基于 Atom 的 One Dark Theme 用 Lua 编写的 One Dark Theme (Neovim &gt;= 0.5).
- [lourenci/github-colors](https://github.com/lourenci/github-colors) - GitHub 颜色利用 Tree-sitter 获得 100% 的准确性.
- [sainnhe/gruvbox-material](https://github.com/sainnhe/gruvbox-material) - Gruvbox 修改具有更柔和的对比度和 Tree-sitter 支持.
- [sainnhe/everforest](https://github.com/sainnhe/everforest) - 以绿色为基础的配色方案，旨在营造温暖、柔和且舒适的视觉效果.
- [neanias/everforest-nvim](https://github.com/neanias/everforest-nvim) - Everforest 配色方案的 Lua 端口.
- [NTBBloodbath/doom-one.nvim](https://github.com/NTBBloodbath/doom-one.nvim) - 厄运 emacs 的厄运一号的 Lua 端口.
- [dracula/vim](https://github.com/dracula/vim) - 著名的美丽黑暗动力主题.
- [Mofiqul/dracula.nvim](https://github.com/Mofiqul/dracula.nvim) - 用 Lua 编写的 neovim 的 Dracula colorscheme.
- [yashguptaz/calvera-dark.nvim](https://github.com/yashguptaz/calvera-dark.nvim) - 一个端口 [VSCode Calvara Dark](https://github.com/saurabhdaware/vscode-calvera-dark) 带有 Tree-sitter 和许多其他插件支持的 Neovim 主题.
- [nxvu699134/vn-night.nvim](https://github.com/nxvu699134/vn-night.nvim)  - 用 Lua 编写的深色 Neovim 配色方案. 支持内置 LSP 和 Tree-sitter.
- [adisen99/codeschool.nvim](https://github.com/adisen99/codeschool.nvim) - 用 Lua 编写的 Codeschool colorscheme，具有 Tree-sitter 和内置 lsp 支持.
- [projekt0n/github-nvim-theme](https://github.com/projekt0n/github-nvim-theme)  - 用 Lua 编写的 GitHub 主题、kitty、alacritty. 支持内置 LSP 和 Tree-sitter.
- [kdheepak/monochrome.nvim](https://github.com/kdheepak/monochrome.nvim) - 一种 16 位单色配色方案，使用 hsluv 来呈现明显不同的灰色，支持 Tree-sitter 和其他常用插件.
- [rose-pine/neovim](https://github.com/rose-pine/neovim) - 纯天然松木、人造毛皮和一些适合优雅极简主义者的 Soho 氛围.
- [mcchrish/zenbones.nvim](https://github.com/mcchrish/zenbones.nvim) - 一组 Vim/Neovim 配色方案，旨在使用对比和字体变化来突出显示代码.
- [catppuccin/nvim](https://github.com/catppuccin/nvim) - Warm mid-tone dark theme to show off your vibrant self! with support for native LSP, Tree-sitter, and more 🍨!
- [FrenzyExists/aquarium-vim](https://github.com/FrenzyExists/aquarium-vim) - 深色但充满活力的配色方案.
- [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) - 柔和的深色、完全可定制的 Neovim 主题，支持 lsp、treesitter 和各种插件.
- [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim) - 用 Lua 编写的冷暗配色方案，移植自 [arzg/vim-substrata](https://github.com/arzg/vim-substrata) 主题.
- [ldelossa/vimdark](https://github.com/ldelossa/vimdark)  - 夜间的最小 Vim 主题. 松散地基于 vim-monotonic 和 chrome 的黑暗阅读器扩展. 白天也包括一个浅色主题.
- [Everblush/everblush.nvim](https://github.com/Everblush/everblush.nvim) - 用 Lua 编写的深色、充满活力和美丽的配色方案.
- [adisen99/apprentice.nvim](https://github.com/adisen99/apprentice.nvim) - 基于 Lua 编写的配色方案 [Apprentice](https://github.com/romainl/Apprentice) color pattete with Tree-sitter and built-in lsp support.
- [olimorris/onedarkpro.nvim](https://github.com/olimorris/onedarkpro.nvim)  - 一个 Dark Pro 主题，用 Lua 编写并基于 VS Code 主题. 包括具有完全可定制的颜色、样式和亮点的深色和浅色主题.
- [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim) - A Neovim theme that combines the Nord and Atom One Dark color palettes for a more vibrant programming experience.
- [RishabhRD/gruvy](https://github.com/RishabhRD/gruvy) - 没有使用 Lush 的 colorbuddy 的 Gruvbuddy.
- [echasnovski/mini.nvim#minischeme](https://github.com/echasnovski/mini.nvim#plugin-colorschemes) - `mini.nvim` 的配色方案，它是 base16 的变体，根据最佳感知均匀性选择强调色.
- [luisiacc/gruvbox-baby](https://github.com/luisiacc/gruvbox-baby) - 现代 gruvbox 主题，具有完整的 treesitter 支持.
- [titanzero/zephyrium](https://github.com/titanzero/zephyrium) - 和风风格的主题，用 Lua 编写，支持 TreeSitter.
- [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) - Neovim 深色配色方案的灵感来自葛饰北斋的名画色彩.
- [tiagovla/tokyodark.nvim](https://github.com/tiagovla/tokyodark.nvim) - 用 Lua (Neovim &gt;= 0.5) 及更高版本编写的干净的深色主题.
- [cpea2506/one_monokai.nvim](https://github.com/cpea2506/one_monokai.nvim) - 一个用 Lua 编写的 Monokai 主题.
- [phha/zenburn.nvim](https://github.com/phha/zenburn.nvim) - 支持各种插件的低对比度深色配色方案.
- [kvrohit/rasmus.nvim](https://github.com/kvrohit/rasmus.nvim) - 一个用 Lua 编写的深色配色方案移植自 [rsms/sublime-theme](https://github.com/rsms/sublime-theme) 主题.
- [chrsm/paramount-ng.nvim](https://github.com/chrsm/paramount-ng.nvim)  - 使用 Lush 编写的深色配色方案.  Treesitter 支持.
- [kaiuri/nvim-juliana](https://github.com/kaiuri/nvim-juliana) - 将 Sublime 的 Mariana 主题移植到 Neovim，以短期关注具有 Tree-sitter 支持的开发人员.
- [lmburns/kimbox](https://github.com/lmburns/kimbox)  - 具有深色背景和以棕色为中心的充满活力的前景的配色方案. 的修改 [Kimbie Dark](https://marketplace.visualstudio.com/items?itemName=dnamsons.kimbie-dark-plus).
- [rockyzhang24/arctic.nvim](https://github.com/rockyzhang24/arctic.nvim) - 从 VSCode Dark+ 主题移植的 Neovim 配色方案，对编辑器和 UI 进行了严格而精确的颜色选择.
- [ramojus/mellifluous.nvim](https://github.com/ramojus/mellifluous.nvim) - 愉快而富有成效的配色方案.
- [Yazeed1s/minimal.nvim](https://github.com/yazeed1s/minimal.nvim) - 受 base16-tomorrow-night 和 monokai-pro 启发的两个树保姆支持的配色方案.
- [lewpoly/sherbet.nvim](https://github.com/lewpoly/sherbet.nvim) - 一种舒缓的配色方案，支持流行的插件和树保姆.
- [Mofiqul/adwaita.nvim](https://github.com/Mofiqul/adwaita.nvim) - 基于 GNOME Adwaita 语法的配色方案，支持流行的插件.
- [olivercederborg/poimandres.nvim](https://github.com/olivercederborg/poimandres.nvim) - Neovim 端口 [poimandres VSCode theme](https://github.com/drcmda/poimandres-theme) 在 Tree-sitter 支持下，用 Lua 编写.
- [kvrohit/mellow.nvim](https://github.com/kvrohit/mellow.nvim) - 具有树保姆支持的舒缓深色配色方案.
- [gbprod/nord.nvim](https://github.com/gbprod/nord.nvim) - 基于 Nord Palette 的北极、北蓝色干净优雅的 Neovim 主题.
- [Yazeed1s/oh-lucy.nvim](https://github.com/yazeed1s/oh-lucy.nvim) - 两个树保姆支持的配色方案，灵感来自 vscode 中的 oh-lucy.
- [embark-theme/vim](https://github.com/embark-theme/vim) - 深墨紫色主题利用鲜艳的色彩.

#### Lua Colorscheme

这些配色方案可能不直接专门针对 Tree-sitter，而是用 Lua 编写的.

- [tjdevries/gruvbuddy.nvim](https://github.com/tjdevries/gruvbuddy.nvim) - Minebox 颜色.
- [ellisonleao/gruvbox.nvim](https://github.com/ellisonleao/gruvbox.nvim) - Gruvbox 社区配色方案 Lua 端口.
- [metalelf0/jellybeans-nvim](https://github.com/metalelf0/jellybeans-nvim) - 软心豆粒糖配色方案的端口.
- [lalitmee/cobalt2.nvim](https://github.com/lalitmee/cobalt2.nvim) - 使用 colorbuddy 的 cobalt2 colorscheme 端口.

#### Colorscheme Creation

- [tjdevries/colorbuddy.nvim](https://github.com/tjdevries/colorbuddy.nvim)  - 配色方案助手. 用 Lua 写的！ 快速简单的配色方案.
- [norcalli/nvim-base16.lua](https://github.com/norcalli/nvim-base16.lua) - 用于设置 base16 主题的程序化 Lua 库.
- [rktjmp/lush.nvim](https://github.com/rktjmp/lush.nvim) - 将 Neovim 主题定义为 Lua 中的 DSL，并提供实时反馈.
- [Iron-E/nvim-highlite](https://github.com/Iron-E/nvim-highlite) - 对开发人员来说逻辑上“精简版”的配色方案模板.
- [echasnovski/mini.nvim#mini.base16](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-base16.md) - `mini.nvim` 模块，为手动提供的调色板快速实现 base16 主题.
- [ThemerCorp/themer.lua](https://github.com/themercorp/themer.lua)  - 一个简单的 neovim 荧光笔插件. 它有大量的配色方案. 它还能够为 Vim/Neovim 和其他支持的应用程序（例如 kitty 和 alacritty）创建配色方案.

#### Colorscheme Switchers

- [4e554c4c/darkman.nvim](https://github.com/4e554c4c/darkman.nvim) - 遵循 Linux 上的系统暗模式设置.
- [f-person/auto-dark-mode.nvim](https://github.com/f-person/auto-dark-mode.nvim) - 遵循 macOS 上的系统外观.

### Bars and Lines

- [Bekaboo/deadcolumn.nvim](https://github.com/Bekaboo/deadcolumn.nvim) - 动态显示您的颜色列.
- [ecthelionvi/NeoColumn.nvim](https://github.com/ecthelionvi/NeoColumn.nvim) - 可切换的颜色列突出显示特定字符​​.
- [m4xshen/smartcolumn.nvim](https://github.com/m4xshen/smartcolumn.nvim) - 在不需要时隐藏您的颜色列.
- [utilyre/barbecue.nvim](https://github.com/utilyre/barbecue.nvim) - 像 winbar 这样的 VS 代码.
- [SmiteshP/nvim-navic](https://github.com/SmiteshP/nvim-navic) - 一个简单的 statusline/winbar 组件，它使用 LSP 来显示您当前的代码上下文.

#### Statusline

- [NTBBloodbath/galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim)  - Galaxyline 通过为每个文本区域提供一个提供程序来组件化 Vim 的状态行. 这意味着您可以使用 galaxyline 提供的 api 轻松创建您想要的状态栏.
- [tjdevries/express_line.nvim](https://github.com/tjdevries/express_line.nvim) - 支持协程、函数和作业.
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) - 快速且易于配置的 Neovim 状态行.
- [adelarsq/neoline.vim](https://github.com/adelarsq/neoline.vim) - 使用 Lua 的轻型状态栏/标签栏插件.
- [ojroques/nvim-hardline](https://github.com/ojroques/nvim-hardline)  - 状态线/缓冲线. 它的灵感来自 [vim-airline](https://github.com/vim-airline/vim-airline) 但旨在尽可能轻便和简单.
- [beauwilliams/statusline.lua](https://github.com/beauwilliams/statusline.lua) - 用 Lua 编写的零配置最小状态行，具有出色的集成和惊人的速度！
- [tamton-aquib/staline.nvim](https://github.com/tamton-aquib/staline.nvim)  - Lua 中的现代轻量级状态线. 主要使用 unicode 符号来显示信息.
- [freddiehaddad/feline.nvim](https://github.com/freddiehaddad/feline.nvim) - 用 Lua 编写的最小、时尚和可定制的状态栏.
- [windwp/windline.nvim](https://github.com/windwp/windline.nvim)  - 下一代状态线. 动画状态线.
- [konapun/vacuumline.nvim](https://github.com/konapun/vacuumline.nvim) - 受航空公司启发的 galaxyline 配置.
- [echasnovski/mini.nvim#mini.statusline](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-statusline.md)  - `mini.nvim` 模块用于最小和快速的状态行. 支持根据窗口宽度更改内容.
- [b0o/incline.nvim](https://github.com/b0o/incline.nvim) - 轻量级浮动状态行，旨在与 Neovim 的新全局状态行一起使用.
- [rebelot/heirline.nvim](https://github.com/rebelot/heirline.nvim) - Heirline.nvim 是一个严肃的 Neovim Statusline 插件，围绕递归继承而设计，非常快速和通用.
- [yaocccc/nvim-lines.lua](https://github.com/yaocccc/nvim-lines.lua) - 一个快速、轻便、可定制的 Neovim 状态栏和 tabline（缓冲区）插件.

#### Tabline

- [romgrk/barbar.nvim](https://github.com/romgrk/barbar.nvim) - Neovim tabline 插件.
- [akinsho/bufferline.nvim](https://github.com/akinsho/bufferline.nvim) - 使用 Lua 构建的时髦缓冲线.
- [crispgm/nvim-tabline](https://github.com/crispgm/nvim-tabline) - 带有 Lua 的 tabline.vim 的 Neovim 端口.
- [alvarosevilla95/luatab.nvim](https://github.com/alvarosevilla95/luatab.nvim) - 一个用 Lua 编写的简单的 tabline.
- [johann2357/nvim-smartbufs](https://github.com/johann2357/nvim-smartbufs) - 智能缓冲区管理.
- [kdheepak/tabline.nvim](https://github.com/kdheepak/tabline.nvim) - “缓冲区和选项卡”标语.
- [noib3/cokeline.nvim](https://github.com/noib3/cokeline.nvim) - 为具有令人上瘾的个性的人提供的 Neovim 缓冲线.
- [echasnovski/mini.nvim#mini.tabline](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-tabline.md) - `mini.nvim` 的模块，用于在一个选项卡的情况下显示列出的缓冲区的最小选项卡行，否则回退到默认值.
- [rafcamlet/tabline-framework.nvim](https://github.com/rafcamlet/tabline-framework.nvim) - 用户友好的框架，用于在几行代码中构建您梦想中的标签.
- [nanozuki/tabby.nvim](https://github.com/nanozuki/tabby.nvim)  - 一个最小的、可配置的、Neovim 风格的标题栏. 使用您的 Neovim 选项卡作为工作区多路复用器.

#### Cursorline

- [yamatsum/nvim-cursorline](https://github.com/yamatsum/nvim-cursorline) - 突出显示光标单词和行的插件.
- [xiyaowong/nvim-cursorword](https://github.com/xiyaowong/nvim-cursorword)  - nvim-cursorline 的一部分. 突出显示光标下的单词.
- [RRethy/vim-illuminate](https://github.com/RRethy/vim-illuminate)  - 突出显示光标下的单词.  Neovim 的内置 LSP 可用，它可以用于更智能地突出显示.
- [echasnovski/mini.nvim#mini.cursorword](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-cursorword.md) - `mini.nvim` 模块，用于自动突出显示光标下的单词（在可定制的延迟后显示）.
- [mawkler/modicator.nvim](https://github.com/mawkler/modicator.nvim)  - 光标行号模式指示器. 根据 Vim 模式更改 `CursorLineNr` 突出显示.
- [nyngwang/murmur.lua](https://github.com/nyngwang/murmur.lua) - 包括带有回调（我称之为杂音）的超快速光标词突出显示.

### Startup

- [glepnir/dashboard-nvim](https://github.com/glepnir/dashboard-nvim) - 受 doom-emacs 启发的极简仪表板.
- [goolord/alpha-nvim](https://github.com/goolord/alpha-nvim) - 一个快速且高度可定制的欢迎程序，例如 [vim-startify](https://github.com/mhinz/vim-startify)/dashboard-nvim.
- [echasnovski/mini.nvim#mini.starter](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-starter.md)  - 用于启动屏幕的 `mini.nvim` 模块. 显示的项目是完全可定制的，项目选择可以使用带有即时视觉反馈的前缀查询来完成.
- [henriquehbr/nvim-startup.lua](https://sr.ht/~henriquehbr/nvim-startup.lua) - 显示 Neovim 启动时间.
- [startup-nvim/startup.nvim](https://github.com/startup-nvim/startup.nvim) - neovim 的完全可定制的问候语.
- [willothy/veil.nvim](https://github.com/willothy/veil.nvim) - 一个极快的、动画的、可无限定制的启动/仪表板插件.

### Icon

- [kyazdani42/nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons) - 一个 Lua 分支 [vim-devicons](https://github.com/ryanoasis/vim-devicons).
- [yamatsum/nvim-nonicons](https://github.com/yamatsum/nvim-nonicons) - nvim-web-devicons 的配置集合.
- [ziontee113/icon-picker.nvim](https://github.com/ziontee113/icon-picker.nvim) - 帮助您挑选字体字符、符号 Σ、书呆子字体图标  和表情符号 ✨.

### Media

- [ekickx/clipboard-image.nvim](https://github.com/ekickx/clipboard-image.nvim) - 用于从剪贴板粘贴图像的 Neovim Lua 插件.
- [niuiic/cp-image.nvim](https://github.com/niuiic/cp-image.nvim) - 从剪贴板粘贴图像并插入参考代码.
- [askfiy/nvim-picgo](https://github.com/askfiy/nvim-picgo) - 基于 picgo-core 的 Neovim 插件，用 Lua 编写，允许您将图像上传到图像床，这意味着您可以从互联网上的任何地方查看图像.
- [gwatcha/reaper-keys](https://github.com/gwatcha/reaper-keys) - Reaper DAW 的模态键绑定.
- [madskjeldgaard/reaper-nvim](https://github.com/madskjeldgaard/reaper-nvim) - 来自 Neovim 的远程控制 Reaper DAW.
- [davidgranstrom/scnvim](https://github.com/davidgranstrom/scnvim) - Neovim frontend for SuperCollider.
- [andweeb/presence.nvim](https://github.com/andweeb/presence.nvim) - 用 Lua 编写的快速而精简的 Discord Rich Presence 插件.
- [Chaitanyabsrip/present.nvim](https://github.com/Chaitanyabsprip/present.nvim) - 用 Lua 编写的演示插件.
- [krady21/compiler-explorer.nvim](https://github.com/krady21/compiler-explorer.nvim) - 用于交互的异步 Lua 插件 [compiler-explorer](https://godbolt.org/).
- [samodostal/image.nvim](https://github.com/samodostal/image.nvim) - 作为 ASCII 艺术的图像查看器.
- [adelarsq/image_preview.nvim](https://github.com/adelarsq/image_preview.nvim) - 基于终端图像协议支持的图像预览.

### Note Taking

- [0styx0/abbreinder.nvim](https://github.com/0styx0/abbreinder.nvim) - 缩写提醒（Neovim &gt;= 0.5）.
- [jakewvincent/mkdnflow.nvim](https://github.com/jakewvincent/mkdnflow.nvim) - 流畅的 Markdown 笔记本导航和管理（创建链接、跟踪链接、创建和管理待办事项列表、参考书目文件等）.
- [oberblastmeister/neuron.nvim](https://github.com/oberblastmeister/neuron.nvim) - 注意与 telescope.nvim 集成的神经元插件.
- [jbyuki/nabla.nvim](https://github.com/jbyuki/nabla.nvim) - 记下你的科学笔记.
- [nvim-neorg/neorg](https://github.com/nvim-neorg/neorg)  - 现代性与疯狂的可扩展性相遇. 组织生活的未来.
- [nvim-orgmode/orgmode](https://github.com/nvim-orgmode/orgmode) - 用 Lua (Neovim &gt;= 0.5) 编写的 Orgmode 克隆.
- [NFrid/due.nvim](https://github.com/NFrid/due.nvim) - 将日期字符串显示为虚拟文本.
- [jbyuki/venn.nvim](https://github.com/jbyuki/venn.nvim) - 绘制 ASCII 图.
- [stevearc/gkeep.nvim](https://github.com/stevearc/gkeep.nvim) - 谷歌保持整合.
- [renerocksai/telekasten.nvim](https://github.com/renerocksai/telekasten.nvim) - 一个 Neovim (lua) 插件，用于处理基于文本的降价 zettelkasten / wiki，并将其与基于 telescope.nvim 的期刊混合.
- [mickael-menu/zk-nvim](https://github.com/mickael-menu/zk-nvim) - zk 的 Neovim 扩展，纯文本笔记助手.
- [chrsm/impulse.nvim](https://github.com/chrsm/impulse.nvim) - 阅读 Notion.so 笔记.
- [epwalsh/obsidian.nvim](https://github.com/epwalsh/obsidian.nvim) - 黑曜石插件，用 Lua 编写.
- [jghauser/papis.nvim](https://github.com/jghauser/papis.nvim) - 从您最喜欢的编辑器中管理您的书目.
- [ostralyan/scribe.nvim](https://github.com/ostralyan/scribe.nvim) - 轻松做笔记.
- [phaazon/mind.nvim](https://github.com/phaazon/mind.nvim) - 树木的力量触手可及.
- [RutaTang/quicknote.nvim](https://github.com/RutaTang/quicknote.nvim) - 就地快速做笔记.

### Utility

- [jghauser/mkdir.nvim](https://github.com/jghauser/mkdir.nvim) - 保存文件时自动创建丢失的目录.
- [matbme/JABS.nvim](https://github.com/matbme/JABS.nvim) - 漂亮且最小的缓冲区切换器窗口.
- [j-morano/buffer_manager.nvim](https://github.com/j-morano/buffer_manager.nvim) - 添加一个或多个缓冲区，对它们重新排序，将它们保存在一个文件中，或者只是从一个小的浮动窗口中非常容易地删除它们.
- [clojure-vim/jazz.nvim](https://github.com/clojure-vim/jazz.nvim) - Acid + 即兴曲 = 爵士乐.
- [sudormrfbin/cheatsheet.nvim](https://github.com/sudormrfbin/cheatsheet.nvim) - 可搜索备忘单.
- [code-biscuits/nvim-biscuits](https://github.com/code-biscuits/nvim-biscuits)  - 什锦饼干的 Neovim 端口. 最终也有更多支持的语言.
- [Pocco81/AbbrevMan.nvim](https://github.com/Pocco81/AbbrevMan.nvim) - 管理 Vim 缩写.
- [kazhala/close-buffers.nvim](https://github.com/kazhala/close-buffers.nvim) - 根据不同条件删除多个 Vim 缓冲区.
- [rktjmp/paperplanes.nvim](https://github.com/rktjmp/paperplanes.nvim) - 将选择或缓冲区发布到在线粘贴箱.
- [rcarriga/nvim-notify](https://github.com/rcarriga/nvim-notify) - 一个奇特的、可配置的、通知管理器.
- [folke/noice.nvim](https://github.com/folke/noice.nvim) - 高度实验性的插件，完全取代了消息、命令行和弹出菜单的 UI.
- [sQVe/bufignore.nvim](https://github.com/sQVe/bufignore.nvim) - 取消列出被 git 忽略的隐藏缓冲区.
- [saifulapm/chartoggle.nvim](https://github.com/saifulapm/chartoggle.nvim) - 切换行尾的任何字符.
- [stevearc/dressing.nvim](https://github.com/stevearc/dressing.nvim) - 使用望远镜、fzf 等改进内置的 `vim.ui` 界面.
- [gaborvecsei/cryptoprice.nvim](https://github.com/gaborvecsei/cryptoprice.nvim) - 检查定义的加密货币的价格.
- [jghauser/fold-cycle.nvim](https://github.com/jghauser/fold-cycle.nvim) 循环折叠打开或关闭.
- [rgroli/other.nvim](https://github.com/rgroli/other.nvim) - 打开当前缓冲区的替代文件.
- [toppair/reach.nvim](https://github.com/toppair/reach.nvim) - 缓冲、标记、标签页切换器.
- [axieax/urlview.nvim](https://github.com/axieax/urlview.nvim) - 浏览当前缓冲区中的所有 URL.
- [nkakouros-original/numbers.nvim](https://github.com/nkakouros-original/numbers.nvim) - 只要有意义就切换相对编号.
- [ghillb/cybu.nvim](https://github.com/ghillb/cybu.nvim) - 在循环缓冲区时显示带有上下文的通知窗口.
- [crusj/bookmarks.nvim](https://github.com/crusj/bookmarks.nvim) - 记住文件位置并按时间和频率排序.
- [xiyaowong/virtcolumn.nvim](https://github.com/xiyaowong/virtcolumn.nvim) - 显示一条线作为colorcolumn.
- [m-demare/attempt.nvim](https://github.com/m-demare/attempt.nvim) - 管理和运行临时缓冲区.
- [kevinhwang91/nvim-ufo](https://github.com/kevinhwang91/nvim-ufo) - 具有现代外观和性能提升的超折叠.
- [xiyaowong/link-visitor.nvim](https://github.com/xiyaowong/link-visitor.nvim) - 让我帮你打开链接.
- [sitiom/nvim-numbertoggle](https://github.com/sitiom/nvim-numbertoggle) - Neovim 插件可在相对行号和绝对行号之间自动切换.
- [anuvyklack/fold-preview](https://github.com/anuvyklack/fold-preview.nvim) - 预览关闭的折叠而不打开它.
- [nguyenvukhang/nvim-toggler](https://github.com/nguyenvukhang/nvim-toggler) - 反转文本，例如在“true”和“false”之间切换.
- [CosmicNvim/cosmic-ui](https://github.com/CosmicNvim/cosmic-ui)  - Cosmic-UI 是对特定 Vim 功能的简单包装. 旨在提供一种快速简便的方法来使用 Neovim 创建 Cosmic UI 体验！
- [AckslD/messages.nvim](https://github.com/AckslD/messages.nvim) - 捕获并显示可自定义（浮动）缓冲区中的任何消息.
- [jbyuki/instant.nvim](https://github.com/jbyuki/instant.nvim) - 一个用 Lua 编写的协作编辑插件，没有依赖性.
- [numToStr/BufOnly.nvim](https://github.com/numToStr/BufOnly.nvim) - BufOnly.vim 的 Lua/Neovim 端口有一些变化.
- [zbirenbaum/neodim](https://github.com/zbirenbaum/neodim) - 调暗未使用的函数、变量、参数等的高亮显示.
- [bfredl/nvim-miniyank](https://github.com/bfredl/nvim-miniyank) - 没有默认映射的 killring-like 插件.
- [chrisgrieser/nvim-genghis](https://github.com/chrisgrieser/nvim-genghis) - 方便的文件操作，用Lua编写.
- [chrisgrieser/nvim-recorder](https://github.com/chrisgrieser/nvim-recorder) - 简化和改进您与宏的交互方式.
- [echasnovski/mini.nvim#mini.animate](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-animate.md) - `mini.nvim` 模块为常见的内置操作（光标移动、滚动、调整大小、窗口打开/关闭）添加开箱即用的动画.
- [figsoda/nix-develop.nvim](https://github.com/figsoda/nix-develop.nvim) - 在不重启 Neovim 的情况下运行 `nix develop`.
- [yaocccc/nvim-foldsign](https://github.com/yaocccc/nvim-foldsign) - 在标志栏上显示折叠.
- [tenxsoydev/nx.nvim](https://github.com/tenxsoydev/nx.nvim) - Neovim API 实用程序包装器，使用 Lua 键盘映射、高亮显示、自动命令和选项更加方便.
- [zdcthomas/yop.nvim](https://github.com/zdcthomas/yop.nvim) - 轻松创建您自己的运算符（如 `d` 和 `y`）.
- [cpea2506/relative-toggle.nvim](https://github.com/cpea2506/relative-toggle.nvim) - 在数字和相对数字之间平滑切换，支持各种数字组合，高度可定制.
- [nvim-early-retirement](https://github.com/chrisgrieser/nvim-early-retirement) - 通过在 x 分钟不活动后自动关闭缓冲区来提前退休.

### Terminal Integration

- [LoricAndre/OneTerm.nvim](https://github.com/LoricAndre/OneTerm.nvim) - 用于在终端中运行命令的插件框架.
- [nikvdp/neomux](https://github.com/nikvdp/neomux) - 从运行在 Neovim 内部的 shell 控制 Neovim.
- [willothy/flatten.nvim](https://github.com/willothy/flatten.nvim) - 从当前 Neovim 实例中的终端缓冲区打开文件，而不是启动嵌套实例.
- [akinsho/nvim-toggleterm.lua](https://github.com/akinsho/nvim-toggleterm.lua) - 一个 Neovim Lua 插件，可帮助轻松管理多个终端窗口.
- [norcalli/nvim-terminal.lua](https://github.com/norcalli/nvim-terminal.lua) - 一种高性能文件类型模式，它利用正确的颜色代码隐藏和突出显示您的缓冲区.
- [numToStr/FTerm.nvim](https://github.com/numToStr/FTerm.nvim) - 没有用 Lua 编写的废话浮动终端.
- [pianocomposer321/consolation.nvim](https://github.com/pianocomposer321/consolation.nvim) - 用 Lua 编写的通用终端包装器和管理插件.
- [jghauser/kitty-runner.nvim](https://github.com/jghauser/kitty-runner.nvim)  - 穷人的 REPL. 轻松将缓冲行和命令发送到 kitty 终端.
- [jlesquembre/nterm.nvim](https://github.com/jlesquembre/nterm.nvim) - 通过通知与终端互动.
- [s1n7ax/nvim-terminal](https://github.com/s1n7ax/nvim-terminal) - 一个简单易用的多终端插件.
- [m00qek/baleia.nvim](https://github.com/m00qek/baleia.nvim) - 使用 ANSI 转义序列（8、16、256 或 TrueColor）为文本着色.
- [samjwill/nvim-unception](https://github.com/samjwill/nvim-unception) - 从终端缓冲区开始自动取消嵌套 Neovim 会话.
- [nyngwang/NeoTerm.lua](https://github.com/nyngwang/NeoTerm.lua) - 为每个 **缓冲区** 附加一个终端，现在具有稳定的切换和惊人的光标恢复.
- [idanarye/nvim-channelot](https://github.com/idanarye/nvim-channelot) - 从 Lua 协同程序操作 Neovim 作业.
- [chomosuke/term-edit.nvim](https://github.com/chomosuke/term-edit.nvim) - 允许您像任何其他缓冲区一样在终端中编辑命令.

### Debugging

- [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap) - 调试适配器协议客户端实现.
- [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) - 用于 GDB、LLDB、PDB/PDB++ 和 BashDB 的精简包装器.
- [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) - nvim-dap 的用户界面.
- [Pocco81/DAPInstall.nvim](https://github.com/Pocco81/DAPInstall.nvim) - 为 nvim-dap 管理多个调试器.
- [Weissle/persistent-breakpoints.nvim](https://github.com/Weissle/persistent-breakpoints.nvim) - nvim-dap 的永久断点.
- [ofirgall/goto-breakpoints.nvim](https://github.com/ofirgall/goto-breakpoints.nvim) - 在 nvim-dap 的断点之间循环.
- [andrewferrier/debugprint.nvim](https://github.com/andrewferrier/debugprint.nvim) - 调试 print() 方式.
- [t-troebst/perfanno.nvim](https://github.com/t-troebst/perfanno.nvim) - Annotate your code with callgraph profiling data. Native support for perf, flamegraph and the LuaJit profiler.

#### Quickfix

- [kevinhwang91/nvim-bqf](https://github.com/kevinhwang91/nvim-bqf) - nvim-bqf 的目标是让 Neovim 的 quickfix 窗口更好.
- [gitlab.com/yorickpeterse/nvim-pqf](https://gitlab.com/yorickpeterse/nvim-pqf) - 更漂亮的快速修复/位置列表窗口.
- [nyngwang/NeoWell.lua](https://github.com/nyngwang/NeoWell.lua)  - 有时你会想稍后修复一些线路. 将行存储到 qf 中，并附上一些注释，这样当你真的想修复它时，你就知道该怎么做.

### Test

- [David-Kunz/jester](https://github.com/David-Kunz/jester) - 轻松运行和调试 Jest 测试.
- [klen/nvim-test](https://github.com/klen/nvim-test) - 用于运行测试的 Neovim 包装器.
- [nvim-neotest/neotest](https://github.com/nvim-neotest/neotest) - 一个可扩展的框架，用于与 Neovim 中的测试进行交互.
- [andythigpen/nvim-coverage](https://github.com/andythigpen/nvim-coverage) - 在符号栏中显示覆盖信息.

### Code Runner

- [michaelb/sniprun](https://github.com/michaelb/sniprun) - 直接从 Neovim 运行任何语言的部分代码.
- [pianocomposer321/yabs.nvim](https://github.com/pianocomposer321/yabs.nvim) - 另一个构建系统，用 Lua 编写.
- [CRAG666/code_runner.nvim](https://github.com/CRAG666/code_runner.nvim) - 你可以拥有的最好的代码运行器，具有超能力.
- [is0n/jaq-nvim](https://github.com/is0n/jaq-nvim) - Lua 中的另一个 Quickrun 插件.
- [jedrzejboczar/toggletasks.nvim](https://github.com/jedrzejboczar/toggletasks.nvim) - 带有 JSON/YAML 配置的任务运行器，使用 toggleterm.nvim 和 telescope.nvim.
- [EthanJWright/vs-tasks.nvim](https://github.com/EthanJWright/vs-tasks.nvim) - 用于 VSCode 风格任务的望远镜选择器.
- [stevearc/overseer.nvim](https://github.com/stevearc/overseer.nvim) - 任务运行器和作业管理插件.
- [smzm/hydrovim](https://github.com/smzm/hydrovim) - 在 Neovim 中运行 python 代码.
- [desdic/greyjoy.nvim](https://github.com/desdic/greyjoy.nvim) - 用于 Makefile、vscode 任务、厨房等的模块化任务运行器.
- [Shatur/neovim-tasks](https://github.com/Shatur/neovim-tasks) - 专注于与构建系统集成的有状态任务管理器.
- [hkupty/iron.nvim](https://github.com/hkupty/iron.nvim) - 嵌入了 30 多种语言的交互式 REPL.
- [Civitasv/cmake-tools.nvim](https://github.com/Civitasv/cmake-tools.nvim) -CMake 集成.
- [idanarye/nvim-moonicipal](https://github.com/idanarye/nvim-moonicipal) - 专注于快速变化的个人任务的任务运行器.
- [MarcHamamji/runner.nvim](https://github.com/MarcHamamji/runner.nvim) - 可定制的 Lua 代码运行器.

### Neovim Lua Development

- [folke/neodev.nvim](https://github.com/folke/neodev.nvim) - init.lua 的开发设置和插件开发，具有完整的签名帮助、文档和 Neovim Lua API 的完成.
- [nvim-neorocks/luarocks-tag-release](https://github.com/nvim-neorocks/luarocks-tag-release) - 将您的 Neovim 插件发布到 LuaRocks 的 GitHub 操作.
- [svermeulen/vimpeccable](https://github.com/svermeulen/vimpeccable) - 帮助用 Lua 或任何基于 Lua 的语言编写 .vimrc 的命令.
- [nanotee/nvim-lua-guide](https://github.com/nanotee/nvim-lua-guide) - 在 Neovim 中使用 Lua 的指南.
- [rafcamlet/nvim-luapad](https://github.com/rafcamlet/nvim-luapad) - 用于嵌入式 Lua 引擎的交互式实时 Neovim 暂存器 - 输入并观看！.
- [nvim-lua/plenary.nvim](https://github.com/nvim-lua/plenary.nvim)  - 全体会议：满员； 完全的; 全部的; 绝对; 不合格. 所有我不想写两次的 Lua 函数.
- [nvim-lua/popup.nvim](https://github.com/nvim-lua/popup.nvim) - 来自 Vim 的 Popup API 的实现.
- [tjdevries/vlog.nvim](https://github.com/tjdevries/vlog.nvim) - 单个文件，无依赖性，轻松复制和粘贴日志文件以添加到您的 Neovim Lua 插件.
- [bfredl/nvim-luadev](https://github.com/bfredl/nvim-luadev)  - REPL/调试控制台 Lua 插件.  `:Luadev` 命令将打开一个临时窗口，显示执行 Lua 代码的输出.
- [jbyuki/one-small-step-for-vimkind](https://github.com/jbyuki/one-small-step-for-vimkind)  - Neovim Lua 语言的适配器. 它允许您调试在 Neovim 实例中运行的任何 Lua 代码（A Lua plugin that can debug Neovim Lua plugins）.
- [kkharji/sqlite.lua](https://github.com/kkharji/sqlite.lua) - Lua 和 Neovim 的 SQLite/LuaJIT 绑定.
- [MunifTanjim/nui.nvim](https://github.com/MunifTanjim/nui.nvim) - 用户界面组件库.
- [echasnovski/mini.nvim#mini.doc](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-doc.md)  - `mini.nvim` 模块，用于从类似 EmmyLua 的注释生成帮助文件. 允许通过挂钩函数灵活定制输出.
- [nanotee/luv-vimdocs](https://github.com/nanotee/luv-vimdocs) - vimdoc 格式的 luv 文档.
- [milisims/nvim-luaref](https://github.com/milisims/nvim-luaref) - 内置 Lua 函数的参考.
- [echasnovski/mini.nvim#mini.test](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-test.md)  - `mini.nvim` 模块，带有用于编写广泛的 Neovim 插件测试的框架. 支持分层测试、挂钩、参数化、过滤、屏幕测试、“busted-style”仿真、可定制的记者等.
- [miversen33/import.nvim](https://github.com/miversen33/import.nvim) - 保险箱需要更换为精致物品.
- [ray-x/guihua.lua](https://github.com/ray-x/guihua.lua)  - 一个 Lua UI 库. 包括模糊搜索栏、列表视图和树视图模块.
- [anuvyklack/animation.nvim](https://github.com/anuvyklack/animation.nvim) - 创建动画.
- [NFrid/treesitter-utils](https://github.com/NFrid/treesitter-utils) - 一些有用的 Treesitter 方法.

### Fennel

- [Olical/aniseed](https://github.com/Olical/aniseed) - 使用茴香配置和扩展 Neovim（Lisp 到 Lua）.
- [Olical/conjure](https://github.com/Olical/conjure) - 交互式评估（Clojure、Fennel、Janet、Racket、Hy、MIT Scheme、Guile）.
- [rktjmp/hotpot.nvim](https://github.com/rktjmp/hotpot.nvim) - Neovim 内的无缝、透明茴香.
- [udayvir-singh/tangerine.nvim](https://github.com/udayvir-singh/tangerine.nvim) - Sweet :tangerine: 茴香整合，旨在尽可能快.
- [udayvir-singh/hibiscus.nvim](https://github.com/udayvir-singh/hibiscus.nvim) - Flavored :hibiscus: 茴香宏库.

### Dependency Management

- [vuki656/package-info.nvim](https://github.com/vuki656/package-info.nvim) - 在 package.json 中将最新的包版本显示为虚拟文本.
- [Saecki/crates.nvim](https://github.com/Saecki/crates.nvim) - `Cargo.toml` 的 Rust 依赖管理.

### Git

- [f-person/git-blame.nvim](https://github.com/f-person/git-blame.nvim) - 显示 git 责备信息.
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Git 集成：标志、大块动作、责备等.
- [TimUntersberger/neogit](https://github.com/TimUntersberger/neogit) - 一个 Magit 克隆，可能会改变一些东西以适应 Vim 哲学.
- [tveskag/nvim-blame-line](https://github.com/tveskag/nvim-blame-line) - 一个使用 neovims 虚拟文本在当前行末尾打印 git blame 信息的小插件.
- [ruifm/gitlinker.nvim](https://github.com/ruifm/gitlinker.nvim)  - 为多个 git 主机生成可共享的文件永久链接. 受 tpope/vim-fugitive 的 :GBrowse 启发.
- [tanvirtin/vgit.nvim](https://github.com/tanvirtin/vgit.nvim) - Visual Git Plugin to enhance your git experience.
- [sindrets/diffview.nvim](https://github.com/sindrets/diffview.nvim) - 单一标签页界面，可轻松循环浏览任何 git 版本的所有修改文件的差异.
- [kdheepak/lazygit.nvim](https://github.com/kdheepak/lazygit.nvim) - 用于调用 lazygit 的插件.
- [AckslD/nvim-gfold.lua](https://github.com/AckslD/nvim-gfold.lua) - 插件使用 [gfold](https://github.com/nickgerace/gfold) 切换 repo 并具有状态行组件.
- [akinsho/git-conflict.nvim](https://github.com/akinsho/git-conflict.nvim) - 一个可视化和解决合并冲突的插件.
- [aaronhallaert/advanced-git-search.nvim](https://github.com/aaronhallaert/advanced-git-search.nvim) - 通过使用 Telescope 提交内容、消息和作者来搜索您的 git 历史记录.

#### GitHub

- [pwntester/octo.nvim](https://github.com/pwntester/octo.nvim)  - 处理来自 Neovim 的 GitHub 问题和 PR. 只需编辑问题描述.
- [pwntester/codeql.nvim](https://github.com/pwntester/codeql.nvim) - 帮助编写和测试 CodeQL 查询的 Neovim 插件.
- [ldelossa/gh.nvim](https://github.com/ldelossa/gh.nvim) - 用于执行代码审查的功能齐全的 GitHub 集成.

### Motion

- [phaazon/hop.nvim](https://github.com/phaazon/hop.nvim) - Hop 是一个类似 EasyMotion 的插件，允许您以尽可能少的击键跳转到文档中的任何位置.
- [ggandor/lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim) - 一个类似 Sneak 的插件，通过提前显示的标签提供无与伦比的导航速度，消除了输入搜索模式和选择目标之间的停顿.
- [ggandor/leap.nvim](https://github.com/ggandor/leap.nvim) - Lightspeed 的精致继承者，旨在建立一个广泛接受的标准界面扩展，以便在类似 Vim 的编辑器中移动.
- [echasnovski/mini.nvim#mini.jump](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump.md) - `mini.nvim` 模块，用于更智能地跳转到单个字符.
- [echasnovski/mini.nvim#mini.jump2d](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump2d.md)  - `mini.nvim` 模块，用于通过迭代标签过滤在可见行内更智能地跳跃. 支持自定义跳转目标（点）、标签、挂钩、允许的窗口和线等.
- [rlane/pounce.nvim](https://github.com/rlane/pounce.nvim) - 一个类似 EasyMotion 的插件，用于使用模糊搜索快速移动光标.
- [gen740/SmoothCursor.nvim](https://github.com/gen740/SmoothCursor.nvim) - 向符号栏添加精美的子光标以显示您的滚动或跳跃方向.
- [edluffy/specs.nvim](https://github.com/edluffy/specs.nvim) - 一个快速、轻量级的 Neovim Lua 插件，可以密切关注光标跳到的位置.
- [abecodes/tabout.nvim](https://github.com/abecodes/tabout.nvim) - 跳出括号、引号、对象等.
- [linty-org/readline.nvim](https://github.com/linty-org/readline.nvim) - Readline 键盘快捷键.
- [woosaaahh/sj.nvim](https://github.com/woosaaahh/sj.nvim) - 基于搜索的导航与快速跳转功能相结合.
- [Weissle/easy-action](https://github.com/Weissle/easy-action) - 轻松地在您可以看到的地方执行操作.
- [cbochs/portal.nvim](https://github.com/cbochs/portal.nvim)  - 建立并增强现有的跳转列表动作（即`<c-i>  ` 和 `<c-o>  `）.
- [echasnovski/mini.nvim#mini.bracketed](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-bracketed.md) - `mini.nvim` 模块用方括号前进/后退.
- [liangxianzhe/nap.nvim](https://github.com/liangxianzhe/nap.nvim) - 使用单个键在下一个/上一个缓冲区、选项卡、诊断等之间跳转.
- [chrisgrieser/nvim-spider](https://github.com/chrisgrieser/nvim-spider)  - 像蜘蛛一样使用 w、e、b 动作. 考虑 camelCase 并跳过无关紧要的标点符号.

#### Treesitter Based

- [mfussenegger/nvim-ts-hint-textobject](https://github.com/mfussenegger/nvim-ts-hint-textobject) - 在由 Treesitter 提供支持的文档的 AST 节点上提示区域选择.
- [ziontee113/syntax-tree-surfer](https://github.com/ziontee113/syntax-tree-surfer)  - 导航和交换 Treesitter 的 AST 节点. 踏进，踏出，跨过，退后.
- [drybalka/tree-climber.nvim](https://github.com/drybalka/tree-climber.nvim) - 轻松导航 Treesitter 的树，适用于多语言文件和正常模式.

### Keybinding

- [folke/which-key.nvim](https://github.com/folke/which-key.nvim) - Neovim 插件显示一个弹出窗口，其中包含您开始输入的命令的可能键绑定.
- [mrjones2014/legendary.nvim](https://github.com/mrjones2014/legendary.nvim) - 将您的键映射、命令和自动命令定义为简单的 Lua 表，并同时为它们创建图例（如 VS Code 的命令面板），与 `which-key.nvim` 集成.
- [Iron-E/nvim-cartographer](https://github.com/Iron-E/nvim-cartographer) - Lua 环境更方便的 `:map`ping 语法.
- [b0o/mapx.nvim](https://github.com/b0o/mapx.nvim)  - 一个更简单的键映射 API，模仿 Neovim 的 `:map` 命令系列. 与 which-key.nvim 集成.
- [LionC/nest.nvim](https://github.com/LionC/nest.nvim)  - Lua 实用程序使用级联树简洁地映射键. 还允许将 Lua 函数绑定到键.
- [LinArcX/telescope-command-palette.nvim](https://github.com/LinArcX/telescope-command-palette.nvim) - 用于创建键绑定并用望远镜观察它们的 Lua 插件.
- [slugbyte/unruly-worker](https://github.com/slugbyte/unruly-worker) - 一个非常有趣的替代键盘映射，用于 workman 键盘布局，具有 Neovim 功能，如 LSP 支持，使用 Lua 构建和配置.
- [FeiyouG/command_center.nvim](https://github.com/FeiyouG/command_center.nvim) - 以更有条理的方式创建和管理键绑定和命令，并通过 Telescope 快速搜索它们.
- [linty-org/key-menu.nvim](https://github.com/linty-org/key-menu.nvim) - 浮动窗口中的键映射提示.
- [anuvyklack/hydra.nvim](https://github.com/anuvyklack/hydra.nvim)  - 创建自定义子模式和菜单.  Emacs Hydra 端口.
- [anuvyklack/keymap-amend.nvim](https://github.com/anuvyklack/keymap-amend.nvim) - 修改现有的键盘映射.
- [max397574/better-escape.nvim](https://github.com/max397574/better-escape.nvim) - 创建快捷方式以立即退出插入模式.
- [Nexmean/caskey.nvim](https://github.com/Nexmean/caskey.nvim) - 使用声明性级联树的键映射配置实用程序，可选择与“which-key”集成.
- [Wansmer/langmapper.nvim](https://github.com/Wansmer/langmapper.nvim) - 自动翻译非英语输入法的映射.

### Mouse

- [notomo/gesture.nvim](https://github.com/notomo/gesture.nvim) - 鼠标手势插件.

### Scrolling

- [karb94/neoscroll.nvim](https://github.com/karb94/neoscroll.nvim) - 平滑滚动.
- [declancm/cinnamon.nvim](https://github.com/declancm/cinnamon.nvim) - 平滑滚动任何移动命令.

#### Scrollbar

- [Xuyuanp/scrollbar.nvim](https://github.com/Xuyuanp/scrollbar.nvim) - 滚动条.
- [dstein64/nvim-scrollview](https://github.com/dstein64/nvim-scrollview) - 显示交互式滚动条.
- [petertriho/nvim-scrollbar](https://github.com/petertriho/nvim-scrollbar) - 显示诊断和搜索结果的可扩展滚动条.
- [echasnovski/mini.nvim#mini.map](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-map.md) - `mini.nvim` 模块显示带有缓冲区文本概览、滚动条和高亮显示的浮动窗口.
- [gorbit99/codewindow.nvim](https://github.com/gorbit99/codewindow.nvim) - Minimap 插件，与 treesitter 和内置 LSP 紧密集成，以向用户显示更多信息.
- [lewis6991/satellite.nvim](https://github.com/lewis6991/satellite.nvim) - 装饰滚动条.

### Editing Support

- [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag) - 使用 treesitter 自动关闭和自动重命名 xml、html、jsx 标签.
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs) - 由 Lua 编写的极简自动配对.
- [ZhiyuanLck/smart-pairs](https://github.com/ZhiyuanLck/smart-pairs) - 由 Lua 编写的终极智能对.
- [echasnovski/mini.nvim#mini.pairs](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-pairs.md) - 用于自动配对的 `mini.nvim` 模块，它具有最小的默认值和进行每个键映射的功能.
- [m4xshen/autoclose.nvim](https://github.com/m4xshen/autoclose.nvim) - 用 Lua 编写的极简自动关闭插件.
- [altermo/ultimate-autopair.nvim](https://github.com/altermo/ultimate-autopair.nvim) - 与扩展自动配对.
- [utilyre/sentiment.nvim](https://github.com/utilyre/sentiment.nvim) - 增强匹配对.
- [monaqa/dial.nvim](https://github.com/monaqa/dial.nvim) - 扩展增量/减量.
- [mrjones2014/nvim-ts-rainbow](https://github.com/mrjones2014/nvim-ts-rainbow) - 彩虹 :rainbow: 使用 tree-sitter :rainbow: 分隔符.
- [AckslD/nvim-revJ.lua](https://github.com/AckslD/nvim-revJ.lua) - Neovim Lua 插件，用于对参数执行与连接线 (J) 相反的操作.
- [Pocco81/TrueZen.nvim](https://github.com/Pocco81/TrueZen.nvim) - 干净优雅的无干扰写作.
- [Pocco81/HighStr.nvim](https://github.com/Pocco81/HighStr.nvim) - 像在普通文档编辑器中一样突出显示视觉选择！
- [Pocco81/AutoSave.nvim](https://github.com/Pocco81/AutoSave.nvim) - 在世界崩溃或您输入 :qa 之前保存您的工作！
- [tmillr/sos.nvim](https://github.com/tmillr/sos.nvim) - 根据预定义的超时值自动保存所有修改的缓冲区.
- [folke/zen-mode.nvim](https://github.com/folke/zen-mode.nvim) - 无干扰编码.
- [haringsrob/nvim_context_vt](https://github.com/haringsrob/nvim_context_vt) - 显示当前上下文的虚拟文本.
- [nvim-treesitter/nvim-treesitter-context](https://github.com/nvim-treesitter/nvim-treesitter-context) - 显示带有当前功能/块上下文的浮动悬停.
- [mizlan/iswap.nvim](https://github.com/mizlan/iswap.nvim)  - 交互式选择和交换函数参数、列表元素等. 由 tree-sitter 提供支持.
- [Wansmer/sibling-swap.nvim](https://github.com/Wansmer/sibling-swap.nvim) - 与 Tree-Sitter 交换参数和其他兄弟姐妹的不同方式.
- [Wansmer/binary-swap.nvim](https://github.com/Wansmer/binary-swap.nvim) - 交换二进制表达式中的操作数和运算符：比较和数学运算.
- [nacro90/numb.nvim](https://github.com/nacro90/numb.nvim) - 以不显眼的方式查看线条.
- [ethanholz/nvim-lastplace](https://github.com/ethanholz/nvim-lastplace) - 在您上次编辑的位置重新打开文件.
- [Allendang/nvim-expand-expr](https://github.com/AllenDang/nvim-expand-expr) - 将表达式扩展并重复到多行.
- [h-hg/fcitx.nvim](https://github.com/h-hg/fcitx.nvim) - 分别为每个缓冲区切换和恢复 fcitx 状态.
- [keaising/im-select.nvim](https://github.com/keaising/im-select.nvim) - 自动切换和恢复输入法取决于 Neovim 的编辑模式.
- [echasnovski/mini.nvim#mini.trailspace](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-trailspace.md) - `mini.nvim` 模块，用于自动突出显示尾随空格，并具有删除它的功能.
- [smjonas/live-command.nvim](https://github.com/smjonas/live-command.nvim) - 具有即时视觉反馈的文本编辑：预览命令，如 `:norm`、`:g`、宏等.
- [filipdutescu/renamer.nvim](https://github.com/filipdutescu/renamer.nvim) - 类似 VS Code 的重命名 UI，用 Lua 编写.
- [gbprod/cutlass.nvim](https://github.com/gbprod/cutlass.nvim) - 添加与“删除”分开的“剪切”操作的插件.
- [gbprod/substitute.nvim](https://github.com/gbprod/substitute.nvim) - Neovim 插件引入了一个新的操作员动作来快速替换和交换文本.
- [gbprod/yanky.nvim](https://github.com/gbprod/yanky.nvim) - 改进了 Yank 和 Put 功能.
- [sQVe/sort.nvim](https://github.com/sQVe/sort.nvim) - 智能支持按行和定界符排序的排序插件.
- [booperlv/nvim-gomove](https://github.com/booperlv/nvim-gomove) - 一个用于移动和复制块和线的完整插件，具有完整的折叠处理、重新缩进和一次性撤消.
- [willothy/moveline.nvim](https://github.com/willothy/moveline.nvim)  - 轻松上下移动行和块，移动时自动处理缩进. 用 Rust 编写.
- [echasnovski/mini.nvim#mini.move](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-move.md)  - `mini.nvim` 的模块可以在任何方向移动任何选择（charwise，linewise，blockwise，普通模式下的当前行）. 处理 `v:count` 和撤消历史.
- [anuvyklack/pretty-fold.nvim](https://github.com/anuvyklack/pretty-fold.nvim) - 折叠文本定制.
- [bennypowers/nvim-regexplainer](https://github.com/bennypowers/nvim-regexplainer) - 解释光标下的正则表达式.
- [gbprod/stay-in-place.nvim](https://github.com/gbprod/stay-in-place.nvim) - Neovim 插件可防止光标在使用 shift 和 filter 操作时移动.
- [echasnovski/mini.nvim#mini.ai](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-ai.md)  - 用于扩展和创建 `a`/`i` 文本对象的 `mini.nvim` 模块. 它增强了一些内置文本对象，创建了大量新对象（如 `a*`、`a<Space>  `、`a?` 等），并允许用户创建自己的（通过 Lua 模式或函数）. 支持点重复、不同的搜索方法、连续应用等.
- [Wansmer/treesj](https://github.com/Wansmer/treesj)  - 拆分/合并代码块，如数组、散列、语句、对象、字典等.使用 Tree-Sitter. 受最伟大的 splitjoin.vim 启发.
- [bennypowers/splitjoin.nvim](https://github.com/bennypowers/splitjoin.nvim) - 拆分和加入各种语法结构.
- [echasnovski/mini.nvim#mini.splitjoin](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-splitjoin.md)  - 用于拆分和连接参数的 `mini.nvim` 模块. 具有可定制的前挂钩和后挂钩. 在评论中工作.
- [shortcuts/no-neck-pain.nvim](https://github.com/shortcuts/no-neck-pain.nvim) - 将当前聚焦的缓冲区居中到终端的中间.
- [debugloop/telescope-undo.nvim](https://github.com/debugloop/telescope-undo.nvim) - 一个望远镜扩展，用于可视化您的撤消树和其中的模糊搜索更改.
- [chrisgrieser/nvim-various-textobjs](https://github.com/chrisgrieser/nvim-various-textobjs) - 捆绑了大约十几个自定义文本对象.
- [XXiaoA/ns-textobject.nvim](https://github.com/XXiaoA/ns-textobject.nvim) - Awesome textobject plugin works with nvim-surround.
- [~nedia/auto-save.nvim](https://git.sr.ht/~nedia/auto-save.nvim)  - 在 `InsertLeave` 和 `TextChanged` 上极其简单的自动保存. 基于 Pocco81/AutoSave 但更轻.
- [echasnovski/mini.nvim#mini.basics](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-basics.md) - `mini.nvim` 模块，具有可自定义的配置预设，用于常用选项、映射和自动命令.
- [niuiic/part-edit.nvim](https://github.com/niuiic/part-edit.nvim) - 单独编辑文件的一部分.
- [niuiic/divider.nvim](https://github.com/niuiic/divider.nvim) - 自定义代码分隔线.
- [chrisgrieser/nvim-alt-substitute](https://github.com/chrisgrieser/nvim-alt-substitute)  - 替代 vim 的 `:substitute`，它使用 Lua 模式而不是 vim 正则表达式. 支持增量预览.

#### Comment

- [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim)  - 智能和强大的评论插件. 支持评论字符串、动作、点重复等.
- [b3nj5m1n/kommentary](https://github.com/b3nj5m1n/kommentary) - 用 Lua 编写的评论插件.
- [gennaro-tedesco/nvim-commaround](https://github.com/gennaro-tedesco/nvim-commaround) - 用 Lua 编写的快速轻便的评论插件.
- [folke/todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - 突出显示、列出和搜索项目中的待办事项评论.
- [terrortylor/nvim-comment](https://github.com/terrortylor/nvim-comment) - Toggle comments using the built-in commentstring option.
- [winston0410/commented.nvim](https://github.com/winston0410/commented.nvim) - 支持计数和多种评论模式等的评论插件.
- [s1n7ax/nvim-comment-frame](https://github.com/s1n7ax/nvim-comment-frame) - 添加基于源文件的注释框.
- [danymat/neogen](https://github.com/danymat/neogen)  - 更好的注释生成器. 支持多种语言和注释约定.
- [echasnovski/mini.nvim#mini.comment](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-comment.md)  - 用于每行注释的 `mini.nvim` 模块. 完全支持点重复.
- [LudoPinelli/comment-box.nvim](https://github.com/LudoPinelli/comment-box.nvim) - 使用方框和线条澄清和美化您的评论.
- [JoosepAlviste/nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)  - 根据光标在文件中的位置设置 `commentstring` 选项. 通过 treesitter 查询检查位置.

### Formatting

- [gpanders/editorconfig.nvim](https://github.com/gpanders/editorconfig.nvim) - 用茴香编写的 EditorConfig 插件.
- [mhartington/formatter.nvim](https://github.com/mhartington/formatter.nvim) - 用 Lua 编写的格式运行程序.
- [lukas-reineke/lsp-format.nvim](https://github.com/lukas-reineke/lsp-format.nvim) - 围绕 Neovims 原生 LSP 格式的包装器.
- [sbdchd/neoformat](https://github.com/sbdchd/neoformat) - 用于格式化代码的 (Neo)vim 插件.
- [cappyzawa/trim.nvim](https://github.com/cappyzawa/trim.nvim) - 此插件修剪尾随空格和行.
- [mcauley-penney/tidy.nvim](https://github.com/mcauley-penney/tidy.nvim) - 每次保存时清除文件末尾的尾随空格和空行.
- [MunifTanjim/prettier.nvim](https://github.com/MunifTanjim/prettier.nvim) - 更漂亮的整合.
- [echasnovski/mini.nvim#mini.align](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-align.md) - 用于交互式对齐文本的 `mini.nvim` 模块（有或没有即时预览）.
- [emileferreira/nvim-strict](https://github.com/emileferreira/nvim-strict) - 严格的本机代码样式格式，可暴露深层嵌套、超长行、尾随空格、尾随空行、待办事项和不一致的缩进.
- [~nedia/auto-format.nvim](https://git.sr.ht/~nedia/auto-format.nvim) - 本身不格式化，但设置一个 autocmd 以在保存时格式化，更喜欢 null-ls 而不是 LSP 客户端格式化.

#### Indent

- [glepnir/indent-guides.nvim](https://github.com/glepnir/indent-guides.nvim) - 缩进插件.
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim) - Lua 中的 IndentLine 替换具有更多功能和 treesitter 支持.
- [LucasTavaresA/simpleIndentGuides.nvim](https://github.com/LucasTavaresA/simpleIndentGuides.nvim) - 使用内置变量的缩进指南.
- [echasnovski/mini.nvim#mini.indentscope](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-indentscope.md)  - `mini.nvim` 模块，用于缩进范围的可视化和操作. 支持自定义debounce delay、动画风格、范围计算算法选项的不同粒度.
- [NMAC427/guess-indent.nvim](https://github.com/NMAC427/guess-indent.nvim) - 自动压痕风格检测.
- [Darazaki/indent-o-matic](https://github.com/Darazaki/indent-o-matic) - 用 Lua 编写的愚蠢的自动快速缩进检测.
- [Abstract-IDE/penvim](https://github.com/Abstract-IDE/penvim) - 项目的根目录和文档缩进检测器，带有基于项目的配置加载器.
- [yaocccc/nvim-hlchunk](https://github.com/yaocccc/nvim-hlchunk) - 突出显示一个 `{}` 块.
- [shellRaining/hlchunk.nvim](https://github.com/shellRaining/hlchunk.nvim) - `nvim-hlchunk` 的 Lua 实现，包含更多功能，例如突出显示 `{}` 块、缩进线、空格等.

### Command Line

- [notomo/cmdbuf.nvim](https://github.com/notomo/cmdbuf.nvim) - 替代命令行窗口插件.
- [gelguy/wilder.nvim](https://github.com/gelguy/wilder.nvim) - 用于模糊命令行自动完成的插件.

### Session

- [rmagatti/auto-session](https://github.com/rmagatti/auto-session) - 一个小型的自动化会话管理器.
- [echasnovski/mini.nvim#mini.sessions](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-sessions.md) - 用于会话管理（读取、写入、删除）的 `mini.nvim` 模块.
- [gennaro-tedesco/nvim-possession](https://github.com/gennaro-tedesco/nvim-possession) - 严肃的会话管理器.
- [olimorris/persisted.nvim](https://github.com/olimorris/persisted.nvim) - 使用 git 分支、自动保存/自动加载和 Telescope 支持的简单会话管理.
- [Shatur/neovim-session-manager](https://github.com/Shatur/neovim-session-manager) - 一个简单的包装器：mksession.
- [jedrzejboczar/possession.nvim](https://github.com/jedrzejboczar/possession.nvim) - 灵活的会话管理，任意持久数据存储为 JSON.
- [niuiic/multiple-session.nvim](https://github.com/niuiic/multiple-session.nvim) - 提供多会话管理能力.

### Remote Development

- [chipsenkbeil/distant.nvim](https://github.com/chipsenkbeil/distant.nvim) - 在舒适的本地环境中在远程计算机上编辑文件、运行程序和使用 LSP.
- [jamestthompson3/nvim-remote-containers](https://github.com/jamestthompson3/nvim-remote-containers) - 在 docker 容器内开发，就像 VSCode 一样.
- [esensar/nvim-dev-container](https://github.com/esensar/nvim-dev-container) - Neovim devcontainer.json 和通用开发容器支持.
- [miversen33/netman.nvim](https://github.com/miversen33/netman.nvim) - Lua 驱动的网络资源管理器.

### Split and Window

- [~henriquehbr/ataraxis.lua](https://sr.ht/~henriquehbr/ataraxis.lua) - 用于提高 Neovim 代码可读性的禅宗模式.
- [gitlab.com/yorickpeterse/nvim-window](https://gitlab.com/yorickpeterse/nvim-window) - 在 Neovim 窗口之间轻松跳转.
- [sindrets/winshift.nvim](https://github.com/sindrets/winshift.nvim) - 轻松重新排列您的窗口.
- [beauwilliams/focus.nvim](https://github.com/beauwilliams/focus.nvim)  - 用 Lua 编写的自动对焦和自动调整分割/窗口大小！  Vim 在类固醇上分裂.
- [luukvbaal/stabilize.nvim](https://github.com/luukvbaal/stabilize.nvim) - 窗口打开/关闭事件的稳定窗口内容.
- [anuvyklack/windows.nvim](https://github.com/anuvyklack/windows.nvim)  - 自动扩展当前窗口的宽度. 最大化并恢复它. 所有这一切都带有漂亮的动画！
- [nvim-zh/colorful-winsep.nvim](https://github.com/nvim-zh/colorful-winsep.nvim) - 可配置的颜色分割线.
- [nyngwang/NeoNoName.lua](https://github.com/nyngwang/NeoNoName.lua) - 保留缓冲区删除的布局.
- [famiu/bufdelete.nvim](https://github.com/famiu/bufdelete.nvim) - 在不丢失窗口布局的情况下删除 Neovim 缓冲区.
- [echasnovski/mini.nvim#mini.bufremove](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-bufremove.md) - `mini.nvim` 模块，用于在保存窗口布局时删除缓冲区（取消显示、删除、擦除）.

#### Tmux

- [aserowy/tmux.nvim](https://github.com/aserowy/tmux.nvim) - Tmux 集成具有窗格移动和调整大小的功能.
- [danielpieper/telescope-tmuxinator.nvim](https://github.com/danielpieper/telescope-tmuxinator.nvim) - tmuxinator 与 telescope.nvim 的集成.
- [hkupty/nvimux](https://github.com/hkupty/nvimux) - Neovim 作为 tmux 的替代品.
- [numToStr/Navigator.nvim](https://github.com/numToStr/Navigator.nvim) - 在 Neovim 拆分和 Tmux 窗格之间平滑导航.
- [declancm/windex.nvim](https://github.com/declancm/windex.nvim) - 窗口函数集合，包括在 Neovim 拆分和 Tmux 窗格之间移动、关闭和最大化.
- [otavioschwanck/tmux-awesome-manager.nvim](https://github.com/otavioschwanck/tmux-awesome-manager.nvim) - 运行您的工作流命令，如 yarn install、rails console、yarn add、bundle install 等.

### Game

- [ThePrimeagen/vim-be-good](https://github.com/ThePrimeagen/vim-be-good) - Vim-be-good 是一个 Neovim 插件，旨在让你更好地掌握 Vim Movements.
- [alec-gibson/nvim-tetris](https://github.com/alec-gibson/nvim-tetris) - 将 emacs 的最大功能引入 Neovim - 俄罗斯方块！.
- [seandewar/nvimesweeper](https://github.com/seandewar/nvimesweeper) - 在您最喜欢的文本编辑器中玩扫雷.
- [seandewar/killersheep.nvim](https://github.com/seandewar/killersheep.nvim) - Killersheep 的 Neovim 端口.
- [rktjmp/shenzhen-solitaire.nvim](https://github.com/rktjmp/shenzhen-solitaire.nvim) - Shenzhen I/O Solitaire port.
- [Eandrju/cellular-automaton.nvim](https://github.com/Eandrju/cellular-automaton.nvim) - 它可以让您根据 Neovim 缓冲区的内容执行美观的元胞自动机动画.
- [alanfortlink/blackjack.nvim](https://github.com/alanfortlink/blackjack.nvim) - 经典黑杰克游戏.
- [jim-fx/sudoku.nvim](https://github.com/jim-fx/sudoku.nvim) - 经典数独游戏.

#### Competitive Programming

- [p00f/cphelper.nvim](https://github.com/p00f/cphelper.nvim) - 用于用 Lua 编写的竞争性编程的 Neovim 助手.
- [xeluxee/competitest.nvim](https://github.com/xeluxee/competitest.nvim) - 一个用于自动化测试用例管理和检查竞争性编程竞赛的插件.

### Preconfigured Configuration

- [Abstract-IDE/Abstract](https://github.com/Abstract-IDE/Abstract) - 摘要，Neovim 配置实现了现代 IDE 的强大功能.
- [SpaceVim/SpaceVim](https://spacevim.org) - 社区驱动的模块化 Vim/Neovim 发行版，类似于 spacemacs，但适用于 Vim/Neovim.
- [CosmicNvim/CosmicNvim](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim 是用于 Web 开发的轻量级和自以为是的 Neovim 配置，专门设计用于提供 COSMIC 编程体验！
- [artart222/CodeArt](https://github.com/artart222/CodeArt) - 一个完全用 Lua 编写的快速通用 IDE，带有适用于 Linux/Windows/macOS 的安装程序，并内置用于更新它的 `:CodeArtUpdate` 命令.
- [LazyVim/LazyVim](https://github.com/LazyVim/LazyVim) - 由 **lazy.nvim** 提供支持的成熟 IDE，可以轻松自定义和扩展您的配置.
- [NTBBloodbath/doom-nvim](https://github.com/NTBBloodbath/doom-nvim) - doom-emacs 框架的端口，其目标是向 Neovim 添加有用的功能，以在稳定高效的开发环境中开始工作，而无需花费大量时间配置所有内容.
- [crivotz/nv-ide](https://github.com/crivotz/nv-ide) - Neovim custom configuration, oriented for full stack developers (rails, ruby, php, html, css, SCSS, JavaScript).
- [LunarVim/LunarVim](https://github.com/LunarVim/LunarVim) - 该项目旨在帮助人们从 VSCode 过渡到卓越的文本编辑体验.
- [hackorum/VapourNvim](https://github.com/hackorum/VapourNvim) - 用于获得类似 Vim IDE 的终极体验的 Neovim 配置.
- [vi-tality/neovitality](https://github.com/vi-tality/neovitality) - 功能齐全的 Neovim 发行版，与 Nix Flake 打包在一起，便于安装和重现.
- [siduck76/NvChad](https://github.com/siduck76/NvChad) - 尝试使 Neovim cli 像 IDE 一样实用，同时非常漂亮且不那么臃肿.
- [nvoid-lua/nvoid](https://github.com/nvoid-lua/nvoid) - 用 Lua 编写的简单 Neovim 配置，具有任何 **IDE** 中可用的所有现代功能
- [cstsunfu/.sea.nvim](https://github.com/cstsunfu/.sea.nvim) - 一个模块化的 Neovim 配置，具有漂亮的 UI 和一些有用的功能（Pomodoro Clock、Window Number）.
- [shaeinst/roshnivim](https://github.com/shaeinst/roshnivim) - Roshnivim，可以称为 neovim 的发行版，是一个预定义的配置，因此您不需要 1000hr 来将 neovim 设置为 IDE.
- [AstroNvim/AstroNvim](https://github.com/AstroNvim/AstroNvim) - AstroNvim 是一种美观且功能丰富的 Neovim 配置，可扩展且易于使用大量插件.
- [shaunsingh/nyoom.nvim](https://github.com/shaunsingh/nyoom.nvim)  - 用 Fennel 编写的快速、可配置、最小和 lispy neovim 配置. 供用户扩展和添加的基本配置，带来更独特的编辑体验.
- [CanKolay3499/CNvim](https://github.com/CanKolay3499/CNvim) - 用于 Web 开发的轻量级 Neovim 配置.
- [jrychn/moduleVim](https://github.com/jrychn/ModuleVim) - 一个非常容易使用
  对于后端和前端，自动安装 lsp.
- [askfiy/nvim](https://github.com/askfiy/nvim) - 一个优秀的 Neovim 配置，与 Vscode 一样强大，快如闪电 ⚡️.
- [imbacraft/dusk.nvim](https://github.com/imbacraft/dusk.nvim) - Dusk 是一个轻量级、极简美学的 Neovim 配置，用 Lua 编写，能够提供 Web 和 Java 开发.
- [nvim-lua/kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) - 个人 Neovim 配置的启动点.
- [cunderw/nvim](https://github.com/cunderw/nvim)  - Neovim 自定义配置，专注于 JS/TS、Go 和 Java 开发. 非常喜欢IDE.
- [otavioschwanck/mood-nvim](https://github.com/otavioschwanck/mood-nvim) - 准备好使用 Ruby on Rails、JavaScript 和 Typescript 的配置.
- [ldelossa/nvim-ide](https://github.com/ldelossa/nvim-ide) - 深受 VSCode 启发的全功能 IDE 层.
- [jonathandion/web-dev.nvim](https://github.com/jonathandion/web-dev.nvim) - 用于 Web 开发的小型、简单和灵活的配置 ✨.
- [linrongbin16/lin.nvim](https://github.com/linrongbin16/lin.nvim) - 受 spf13-vim 启发，高度配置的 Neovim 发行版集成了大量开发实用程序.

## External

这些工具在 Neovim 外部使用以增强体验.

### Version Manager

- [MordechaiHadad/bob](https://github.com/MordechaiHadad/bob) - 跨平台且易于使用的 Neovim 版本管理器.
- [NTBBloodbath/nvenv](https://github.com/NTBBloodbath/nvenv) - 轻量级且速度极快的 Neovim 版本管理器.
- [shohi/neva](https://github.com/shohi/neva) - 用 Lua 编写的 Neovim 版本管理器.

### Boilerplate

- [gennaro-tedesco/boilit](https://github.com/gennaro-tedesco/boilit) - 创建样板结构插件.
- [m00qek/plugin-template.nvim](https://github.com/m00qek/plugin-template.nvim) - 设置测试基础设施和 GitHub 操作的插件模板.
- [ellisonleao/nvim-plugin-template](https://github.com/ellisonleao/nvim-plugin-template) - 另一个 neovim 插件模板，使用 GitHub 的模板功能.

## Vim

- [Vimawesome](https://vimawesome.com/) - 展示 Vim 的各种插件，并有一个 [neovim tag](https://vimawesome.com/?q=tag:neovim) 对于其他针对 Neovim 的插件.
- [awesome-vim](https://github.com/akrawchyk/awesome-vim#tools) - Vim 插件和有用指南的简短列表.
- [vim-plugin-list](https://github.com/altermo/vim-plugin-list) - Vim 和 Neovim 插件列表.

## Resource

- [Neovimcraft](https://neovimcraft.com) - 一个专门搜索特定插件和在 Lua 中构建插件的指南的站点.
- [TWiN](https://this-week-in-neovim.org) - TWiN (this-week-in-neovim.org) 致力于提供有关 Neovim 及其生态系统的每周新闻.
- [Dotfyle](https://dotfyle.com) - Dotfyle 是一个用于共享和发现 Neovim 配置和插件的站点.
