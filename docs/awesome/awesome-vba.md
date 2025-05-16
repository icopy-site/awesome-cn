<div class="github-widget" data-repo="sancarn/awesome-vba"></div>

Visual Basic for Applications (VBA) is an implementation of Microsoft's event-driven programming language Visual Basic 6.0 (VB6) built into most desktop Microsoft Office applications.

This is a curated list of Libraries and Resources for both VBA and VB6.

Because of the nature of VBA, many libraries do not work on all Operating Systems, in all Office Applications or on all architectures(x64/x86), therefore we use symbology. [Read more about this here](#symbology).



---

## Frameworks

- [![p_win]](#-) [![p_nom]](#-)  [![a_all]](#-) [stdVBA](http://github.com/sancarn/stdVBA) - A framework containing numerous classes for automation and utility. Focuses on code compactness and long-term maintainability.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [VbCorLib](https://github.com/kellyethridge/VBCorLib) - A framework which brings many powerful .NET classes to VBA/VB6.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Hidennotare](https://github.com/RelaxTools/Hidennotare) - A framework by Japanese author RelaxTools. Contains numerous classes, interfaces and forms.

## Libraries

### Data Formats

#### JSON

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-FastJSON](https://github.com/cristianbuse/VBA-FastJSON) - Fast, cross-platform, native json parser and serializer. Memory efficient (non-recursive), RFC 8259 compliant, UTF8 support
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-JSON](https://github.com/VBA-tools/VBA-JSON) - JSON conversion and parsing.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [mdJSON](https://www.vbforums.com/showthread.php?871695-VB6-VBA-JSON-parsing-to-built-in-VBA-Collections-with-JSON-Path-support) - JSON library with dot-notation for extracting paths.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [JSONBag](https://www.vbforums.com/showthread.php?738845-VB6-JsonBag-Another-JSON-Parser-Generator) - Uses shebang notation to extract keys from JSON strings. Can also build JSON with this library.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdJSON` - As above.

#### CSV

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-CSV-interface](https://github.com/ws-garcia/VBA-CSV-interface) - Powerful, fast and comprehensive RFC-4180 compliant CSV/TSV/DSV data management library.
- From Frameworks:
  - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `Hidennotare` find `csvWriter` and `csvReader`.

#### XML

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-XML](https://github.com/VBA-tools/VBA-XML) - XML conversion and parsing.

#### ZIP

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Excel-ZipTools](https://github.com/cristianbuse/Excel-ZipTools/tree/master) - Parse and Read Zip files.

### Data Structures

#### Array-List

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [Better array](https://github.com/Senipah/VBA-Better-Array/tree/master/src) - An array class providing features found in more modern languages.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) In `VbCorLib` find `ArrayList` - As above.
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdArray` - As above. Also includes methods to search the array or perform checks from a callback.


#### Dictionary

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-FastDictionary](https://github.com/cristianbuse/VBA-FastDictionary) - Fast, cross-platform, native Dictionary. Replacement for scripting dictionary.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-Dictionary](https://github.com/VBA-tools/VBA-Dictionary) - A dictionary object which stores key-value pairs.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VBA-ExtendedDictionary](https://github.com/SSlinky/VBA-ExtendedDictionary) - A dictionary object using Scripting.Dictionary but exposes some additional useful functionality.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [cHashList](https://www.vbforums.com/showthread.php?834515-Simple-and-fast-lightweight-HashList-Class-(no-APIs)) - Simple, Fast and lightweight HashList class with no use of Win32 API. Requires string keys however.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [CollectionEx](https://www.vbforums.com/showthread.php?834579-Wrapper-for-VB6-Collections) - Extends the default VBA(/VB6) collection with methods to retrieve and check for key existence. <!--TODO: This is listed as p_win, but honestly this might work on mac given the correct API declarations. Would be worth testing, see MemoryTools for Copy Memory declares-->
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [clsTrickHashTable](https://www.vbforums.com/showthread.php?788247-VB6-Hash-table) - A hash table using machine code injected at runtime. Full replacement for scripting dictionary, with bonus features.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) In `VbCorLib` find `HashTable` - As above.
    <!-- Hidennotare, though it simply wraps Scripting.Dictioanry... -->

### Math libraries

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-Math-Objects](https://github.com/Beakerboy/VBA-Math-Objects) - A matrix and vector library.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA Float](https://github.com/ws-garcia/VBA-float ) - An utility to perform computations over big integers and rational numbers with thousands digits.

### Database tools

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [SQL Library](https://github.com/Beakerboy/VBA-SQL-Library) - An OOP SQL Library for psql, mssql, mysql databases.

### Userform tools

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Task Dialog](https://github.com/fafalone/cTaskDialog64) - A huge amount of UI functionality from this 1 class, in a strictly dynamic and modular way. Great for data input forms. Also see [vbforums](https://www.vbforums.com/showthread.php?777021-VB6-TaskDialogIndirect-Complete-class-implementation-of-Vista-Task-Dialogs) post for more information.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_dll]](#- 'Requires external OCX') [ucSimplePlayer](https://github.com/fafalone/ucSimplePlayer) - Simple video player user control.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_dll]](#- 'Requires external OCX') [ucWebView2](https://github.com/fafalone/ucWebView2) - WebView2 user control.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_dll]](#- 'Requires external OCX') [ucAniGifEx](https://github.com/fafalone/ucAniGifEx) - Animated GIF user control.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Material UI](https://github.com/todar/VBA-Material-Design) - Make your userform feel modern with Material UI.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [Easy EventListener](https://github.com/todar/VBA-Userform-EventListener) - Consolidate all event handling of a userform into 1 callback.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Pseudo Control Arrays](http://addinbox.sakura.ne.jp/Breakthrough_P-Ctrl_Arrays_Eng.htm) - Optimal means of Consolidating all event handling of a userform. Demonstrates usage of `ConnectToConnectionPoint` API. Also worth looking at [this class](https://stackoverflow.com/questions/61855925/reducing-withevent-declarations-and-subs-with-vba-and-activex#answer-61893857) too.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_dll]](#- 'Requires external DLLs') [Modern UI Components](https://github.com/krishKM/Modern-UI-Components-for-VBA) - Custom modern looking controls.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [MVVM](https://github.com/rubberduck-vba/MVVM) - Model-View-ViewModel Infrastructure for maintainable userform development.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VBA Userform Transitions and Animations](https://github.com/todar/VBA-Userform-Animations) - An excellent library for implementing animation easings into the Userform.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Trick's Timer](https://github.com/thetrik/VbTrickTimer) - If you need to run a piece of code continuously and don't have access to `Application.OnTime` (and/or you need to run it faster than once per second), this is the class for you! Also check out the [forum post](https://www.vbforums.com/showthread.php?875635-VB6-VBA-Timer-class) for more information. Limitation: Requires a modal form.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VBA-SafeTimer](https://github.com/cristianbuse/VBA-SafeTimer) - Reliable, no-crash timer for VBA. Code can be debugged and stopped safely. Works with or without a form.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Drag and Drop filepaths](https://www.mrexcel.com/board/threads/vba-drag-drop-filepath.843330/page-6#post-5898495) - Allow your userform to handle drag-and-drop files.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Late-bound WebBrowser Control Events](https://www.vbforums.com/showthread.php?847773-VB6-elevated-IE-Control-usage-with-HTML5-elements-and-COM-Event-connectors) - A technique to latch onto WebBrowser events in a late-bound manner.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_paid]](#- '~£2 per control/application') [Mark's userform tools](https://www.kubiszyn.co.uk/) - Numerous UI tools and pretty userforms.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VBA-UserForm-MouseScroll](https://github.com/cristianbuse/VBA-UserForm-MouseScroll) - Allows Mouse Wheel Scrolling on MSForms Controls and Userforms.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [MSForms (Pure VBA) Treeview Control](https://jkp-ads.com/Articles/treeview.asp) - A treeview control replacement by JKP and Peter Thornton coded entirely in VBA.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [MSForms (Pure VBA) ListBox Control](https://app.monstercampaigns.com/c/fxzxd8wfvl4mnf4zmnp3/) - Featured in [this video](https://www.youtube.com/watch?v=QYW1SlKfKdM). It has tons of useful features like sorting, filtering, single or multi-selection with select and deselect all, page navigation and hover highlight,
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Custom Userform TitleBar color](https://www.mrexcel.com/board/threads/using-winapi-to-change-the-color-on-the-title-bar-of-a-userform.1205894/page-2#post-5892050)
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Multi-color ListBox class](https://www.mrexcel.com/board/threads/multicolor-drag-n-drop-listbox-class-win32.1206334/)
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Use of GDIPlus in VBA](https://arkham46.developpez.com/articles/office/clgdiplus/) - GDIPlus can be used to create a `canvas` like element where any image can be drawn to. Additionally check out this [GDI32](https://arkham46.developpez.com/articles/office/clgdi32/) class from the same author.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Use of OpenGL in VBA](https://arkham46.developpez.com/articles/office/vbaopengl/?page=Page_1) - OpenGL is a cross-language, cross-platform application programming interface for rendering 2D and 3D vector graphics. In this article the authors of the GDIPlus class.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [VB6 Graph Control](https://vb6awards.blogspot.com/2017/11/vb6-graph-control.html) - Won't work natively in VBA without a `PictureBox` compatible substitute, but an extremely performant graph control regardless.

### Low level tools

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-MemoryTools](https://github.com/cristianbuse/VBA-MemoryTools) - Provides an ultra-fast, copy memory alternative.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Safe Subclassing](https://www.mrexcel.com/board/threads/intercepting-resetting-of-vba-editor-as-well-as-unhandled-errors-for-safe-subclassing.1024295/) - Provides the ability to subclass Excel/Word/PowerPoint window or Userforms to perform further automation. In the later threads there is also an example for subclassing other windows from other applications.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Calling private module functions](https://github.com/Greedquest/vbInvoke/tree/main) - You can also check out [Greedo's code review](https://codereview.stackexchange.com/questions/274532/low-level-vba-hacking-making-private-functions-public).
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [Universal DLL Calls](http://www.vbforums.com/showthread.php?781595-VB6-Call-Functions-By-Pointer-(Universall-DLL-Calls)) - A library which can be used to call functions of any function pointer, DLL or object in both `STDCALL` and `CDECL`.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [vbInvoke](https://github.com/Greedquest/vbInvoke) - `Application.Run` but COM based and can call private module methods.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA state-loss callback](https://github.com/cristianbuse/VBA-StateLossCallback) - A crash free detector for VBA state-loss. State loss can occur when: Someone clicks `end` in an unhandled error; You click the VBA stop button; You enter design mode; Application exits.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [vb2clr](https://github.com/jet2jet/vb2clr) - Use C# from VBA using the .NET CLR runtime.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdCOM` - A one stop shop for COM automation, from invoking interfaces by offsets to extracting type information.
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdReg` - Registry automation from searching to setting values.

### Parsers / Interpreters

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [vba-regex](https://github.com/sihlfall/vba-regex) - A native regex expression parser and runtime engine.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VbPeg](https://github.com/wqweto/VbPeg) - A parser generator for VBA. Converts PEG grammar like [this](https://github.com/wqweto/VbPeg/blob/master/test/Runner/peg/Kscope/grammar.peg) into [VBA code like this](https://github.com/wqweto/VbPeg/blob/master/test/Runner/peg/Kscope/cKscope.cls). Very useful if your implementing a new programming language in VBA. Wqweto has also included some math expression parsers as tests.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [Volpi's Math Expression Parser](https://web.archive.org/web/20100703220609/http://digilander.libero.it/foxes/mathparser/MathExpressionsParser.htm) - A fast math expression parser. Doesn't allow calls to objects, no callstack.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA Expressions](https://github.com/ws-garcia/VBA-Expressions) - A powerful string expression evaluator focussed on mathematics and data processing.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [ClooWrapperVBA](https://github.com/Excel-lent/ClooWrapperVBA) - Execute OpenCL from VBA, using either the GPU or CPU.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdLambda` - Full programming language including object manipulation, call stack, etc. 

### Web tools

- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-Web](https://github.com/VBA-tools/VBA-Web) - Connect VBA, Excel, Access, and Office for Windows and Mac to web services and the web.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [VBA-WebSocket](https://github.com/EagleAglow/vba-websocket) - Microsoft example code for a WebSocket client which can be used in conjunction with an echo server. There is also [a class](https://github.com/EagleAglow/vba-websocket-class) and an [async version](https://github.com/EagleAglow/vba-websocket-async) built by the discoverer of the microsoft code.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [vbAsyncSocket](https://github.com/wqweto/VbAsyncSocket) - Simple and thin WinSock API wrappers for VB6 loosely based on the original CAsyncSocket wrapper in MFC.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Edge Automation](https://www.codeproject.com/Tips/5307593/Automate-Chrome-Edge-using-VBA) - Automate Chromium Edge using devtools protocol. [GitHub backup here](https://github.com/sancarn/stdVBA-Inspiration/tree/master/ChromeEdgeAutomation).
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Chrome Automation (via devtools protocol)](https://github.com/PerditionC/VBAChromeDevProtocol) - Automate Chrome using chrome devtools protocol.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [SeleniumVBA](https://github.com/GCuser99/SeleniumVBA) - Drive selenium webdriver directly from VBA. If you don't have the driver installed, the library will attempt to download it for you and run it. However AV may restrict the running of this process.
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [webxcel](https://github.com/michaelneu/webxcel) - A webserver which runs a RESTful backend. The creator also made an [article](https://dev.to/michaelneu/to-vba-and-beyond---building-a-restful-backend-using-plain-microsoft-excel-macros-76n) on how it works on dev.to.
- From Frameworks:
    - [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) In `stdVBA` find `stdHTTP` - Connect to and query web services.


## Developer tools

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_inst]](#-) [Rubberduck](https://rubberduckvba.com/) - An open-source COM add-in project that integrates with the Visual Basic Editor to add modern-day features to the familiar IDE. Works in VBA6, VBA7.x (x86/x64), and yes, in VB6 too!
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [VBA-IDE-Code-Export](https://github.com/spences10/VBA-IDE-Code-Export) - Addin contains a code importer and exporter for use with git (or any VCS).
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [![a_wd]](#-) [![o_pass]](#-) - [RibbonX](https://www.andypope.info/vba/ribboneditor_2010.htm) - AndyPope's Visual Ribbon Editor.
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Custom UI XML Editor](https://yoursumbuddy.com/ribbon-customui-xml-editor/) - Addin for directly adding, editing and validating ribbon XML (Excel 2010+).
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_paid]](#- 'Costs upwards of $79') [MZ-Tools](https://www.mztools.com/) - VBE addin providing development tools.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VbPeg](https://github.com/wqweto/VbPeg) - A parser generator for VBA. Converts PEG grammar like [this](https://github.com/wqweto/VbPeg/blob/master/test/Runner/peg/Kscope/grammar.peg) into [VBA code like this](https://github.com/wqweto/VbPeg/blob/master/test/Runner/peg/Kscope/cKscope.cls). Very useful if you're implementing a new programming language in VBA.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [VBA Resource File Editor](http://leandroascierto.com/blog/vba-resource-file-editor/) - Store other files inside your excel/word/powerpoint files for later use with this handy tool.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_32]](#-) [vbRichClient](https://vbrichclient.com/#/en/About/) - An external client full of useful libraries.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [![o_paid]](#- '£170-£205 license per dev') [vbWatchDog](https://www.everythingaccess.com/vbwatchdog.asp) - `vbWatchdog` hacks the VBA runtime to provide module name, procedure name and line number where error occurred.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [DLL Function Viewer](https://www.mrexcel.com/board/threads/dll-export-viewer-vba-based.1220909/) - Allows the export of function names from DLLs.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Accessibility Inspector](https://github.com/sancarn/stdVBA-examples/tree/main/Examples/Inspector-Accessibility-v2) - An inspector/explorer for accessibility in applications. Useful for automation.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Running Object Table Inspector](https://github.com/sancarn/stdVBA-examples/tree/main/Examples/Inspector-RunningObjectTable) - An inspector for the running object table (ROT), a table of global running COM objects which can be obtained.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Clipboard Inspector](https://github.com/sancarn/stdVBA-examples/tree/main/Examples/Inspector-Clipboard) - Allows inspection of data held in the clipboard. Useful for reverse engineering clipboard usage in other applications.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Registry Inspector](https://github.com/sancarn/stdVBA-examples/tree/main/Examples/Inspector-Registry) - Allows inspection of the win32 registry. Equivalent of regedit basically, but implemented entirely in VBA.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [JSON Inspector](https://github.com/sancarn/stdVBA-examples/tree/main/Examples/Inspector-JSON) - An inspector for JSON data, can be called on demand too as a dev tool for inspecting API responses.


## Examples

### Algorithms, code optimisation, and performance testing

- [VBSpeed](http://www.xbeat.net/vbspeed/) - The Visual Basic Performance Site - focus on VB6 but transferrable across to VBA.

### UI Ribbon

- [Ron de Bruin - Ribbons/QAT](https://web.archive.org/web/20230806024653/https://www.rondebruin.nl/win/section2.htm) - A leading resource for information/samples on developing custom ribbons and context menus.
- [Office MSO Icons](http://www.spreadsheet1.com/office-excel-ribbon-imagemso-icons-gallery-page-01.html) - Ribbon icons can often use one of the 1500 (3 pages on this site) MSO icons wich pre-exist in Office applications.

### UI Userforms

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Drag and drop control](https://www.vbforums.com/showthread.php?888843-Load-image-into-STATIC-control-Win32&p=5496575&viewfull=1#post5496575) - Dragging and dropping image controls around a userform.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [EZPZMouseController](https://github.com/KallunWillock/EZPZMouseController/) - An example of using native Microsoft Ink Collector to detect mouse wheel and mouse move events.

### Low level examples

- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Iterating the ROT](https://www.mrexcel.com/board/threads/how-to-target-instances-of-excel.1118789/page-2#post-5395037) - An example of iterating the Running Object Table (ROT) to find Excel Workbook instances.
- [![p_win]](#-) [![p_nom]](#-) [![a_all]](#-) [Iterating Excel Instances via IAccessible](https://www.mrexcel.com/board/threads/how-to-target-instances-of-excel.1118789/page-2#post-5395519) - In some cases Excel instances aren't registered to the ROT. The Excel application however implements `IAccessible`, which not only can be used to automate the UI, but can also be used to obtain the Excel Instance from a hwnd.
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Excel Screen Reader](https://www.mrexcel.com/board/threads/excel-screen-reader-upon-navigating-with-the-mouse-with-vba-alone.1162338/) - Not only an example of UI Automation, but also an example of using SAPI to do text to speech.

<!-- ### VBE UI -->

### AddIns

- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [MenuRighter](https://yoursumbuddy.com/blog/menurighter/) - MenuRighter is an Excel addin that lets you modify right-click menus. You can add almost any control found in other right-click menus or Excel 2003's "classic" menus.
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Sam Rad's DatePicker](http://samradapps.com/datepicker/) - Visually impressive and professional DatePicker addin for Excel. Worksheet only / cannot be used with userforms.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [Excel Name Manager](https://jkp-ads.com/excel-name-manager.asp) - A treeview control replacement by JKP and Peter Thornton coded entirely in VBA.
- [![p_win]](#-) [![p_mac]](#-) [![a_all]](#-) [Excel Flex Find](https://jkp-ads.com/excel-flexfind.asp) - A treeview control replacement by JKP and Peter Thornton coded entirely in VBA.
- [![p_win]](#-) [![p_mac]](#-) [![a_wd]](#-) [Word VBA Syntax Highlighter](https://github.com/joey-melo/vba-syntax-higlight/tree/main) - Custom built Syntax Highlight tool for Word Documents.

### Games / Fun projects

- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [xlStudio](https://github.com/DylanTallchiefGit/xlStudio) - A DAW for Microsoft Excel. Also check out the awesome [video](https://youtu.be/RFdCM2kHL64).
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Cellivization](https://s0lly.itch.io/cellivization) - A cool RTS-like game created in Excel. Also check out the awesome [video](https://www.youtube.com/watch?v=PzETBRcr_i8).
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Arkanoid](http://leandroascierto.com/blog/juego-arkanoid-en-excel/) - Arkanoid, a retro arcade game, built in Excel. On some machines it runs faster than others.
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [Battleships](https://github.com/rubberduck-vba/Battleship)
- [![p_win]](#-) [![p_nom]](#-) [![a_ac]](#-) [Pacman](https://arkham46.developpez.com/articles/office/clgdiplus/tuto/tutoclgdiplusgame3/?page=Page_11#LXXIV)
- [![p_win]](#-) [![p_nom]](#-) [![a_xl]](#-) [ExcelCommodroid](https://github.com/raspberrypioneer/ExcelCommodroid/tree/main) - Commodore computer loader using MS Excel on Windows. VBA7 only.

## External tools

- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](# "Python") [oletools](https://github.com/decalage2/oletools) - Python tool which can be used to decode VBA P-Code (VBA's intermediate language).
- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](#- 'VBA planned but as of 2022-05-27 can only compile to exe') [twinBasic](https://twinbasic.com/) - A VBA compatible parser, evaluator and compiler.
- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](# "VSCode") [vscode-vba](https://github.com/serkonda7/vscode-vba) - Extension that adds VBA editor support to Visual Studio Code.
- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](# "VSCode") [VBA Pro](https://marketplace.visualstudio.com/items?itemName=NotisDataAnalytics.vba-lsp) - VSCode Extension that adds enhanced VBA support based on Language Service Protocol. The source is also [on GitHub](https://github.com/SSlinky/VBA-LanguageServer).
- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](# "Github") [VBA Build](https://github.com/DecimalTurn/VBA-Build) - Github action to automatically build a VBA project on commit.
- [![p_win]](#-) [![p_mac]](#-) [![a_misc]](# "Python") [VBA Project Compiler](https://github.com/Beakerboy/MS-OVBA) - A python library which can be utilised to compile VBA projects. There is also a built-in [Excel addin generator](https://github.com/Beakerboy/Excel-Addin-Generator) made by the same author! You can see a list of related projects by the author [here](https://github.com/sancarn/awesome-vba/issues/35).

## Style Guides

- [RubberDuck's style guide](https://rubberduckvba.wordpress.com/2021/05/29/rubberduck-style-guide/) - Has some great intermediate - advanced guidance.
- [VB6 Coding conventions](https://docs.microsoft.com/en-us/previous-versions/visualstudio/visual-basic-6/aa240822(v%3dvs.60)) - Variable/Class/Module naming conventions used in VBA. Greatly helps organisation in VBE (unless you have rubberduck).

## Information

- [Thunder - The birth of Visual Basic](http://www.forestmoon.com/birthofvb/birthofvb.html) - A little article about the birth of VB7/VBA.
- [My First Bill Gates Review](https://www.joelonsoftware.com/2006/06/16/my-first-billg-review/) - Joel Spolsky, program manager for the Excel team, recounts his first Bill Gates review. Joel got numerous features added e.g. `IDispatch`, `Variant`, `For each` and `With`. It also discusses the dreaded Date bug ported to Excel from Lotus 123.
- [Ruby, EB and DLL composition](https://github.com/sancarn/stdVBA-Inspiration/blob/master/_OtherDocumentation/VBA%20and%20VB6%20History%20-%20Eb%20and%20Ruby/VBA%20History.md) - Translated copy of [VBStreets article](http://bbs.vbstreets.ru/viewtopic.php?f=101&t=56551) created by Russian VBer `Хакер`. Details the composition of the VB6 and VBA dlls in amongst the history of the language.
- [PCode Internals](https://www.vbforums.com/showthread.php?884919-pcode-internals) - VBA is compiled to PCode. Understanding the lower level P-Code is a topic of heavy interest and research.
- [How many lines of code in EB](http://bbs.vbstreets.ru/viewtopic.php?f=101&t=56633) - Untranlated article by Russian VBer `Хакер` which estimates the number of lines of code in VB6/VBA.
- [SAFEARRAYS](https://www.vbforums.com/showthread.php?895566-RESOLVED-SAFEARRAY-Structure-for-an-Array) - The internal structure of arrays.
- [Articles by Sancarn](https://sancarn.github.io/vba-articles) - Various articles written by Sancarn about VBA including, performance, actual issues with VBA etc.

## Resources

### Win32 API Resources

- [JKP API Declarations](https://jkp-ads.com/Articles/apideclarations.asp)
- [Microsoft Office Code Compatibility Inspector](https://docs.microsoft.com/en-us/previous-versions/office/office-2010/ee833946(v=office.14)) - The Microsoft Office Code Compatibility Inspector was designed by Microsoft to troubleshoot compatibility issues with VBA code as when upgrading Office from 32-bit to 64-bit. MS has not maintained a link to the software for download from its servers, though versions of it are apparently available on the internet.

### VB6 / VBScript

- [Planet Source Code](https://github.com/Planet-Source-Code/PSCIndex) - A code repository GitHub which holds copious amounts of code. The site was closed down in 2023, but fortunately all VBA/VB6 samples were archived on GitHub today. Possibly not the entire collection (?) of projects/source code that was previously available at the PSC website.
- [vbAccelerator Archive](https://github.com/tannerhelland/vbAccelerator-Archive) - Archived copy of vbAccelerator site (articles, source code, etc.) that disappeared in 2015, reappeared in 2018, and anyone's guess what's going to next&hellip; Primarily VB6, but useful VBA resource.

### Websites

- [Excel Development Platform Blog](https://exceldevelopmentplatform.blogspot.com/) - Blog dealing with advanced topics/VBA.
- [MSDN VBA Documentation](https://msdn.microsoft.com/en-us/vba/office-vba-reference)
- [MS-VBAL Language Spec](https://docs.microsoft.com/en-gb/openspecs/microsoft_general_purpose_programming_languages/ms-vbal/d5418146-0bd2-45eb-9c7a-fd9502722c74)
- [Ron de Bruin](https://web.archive.org/web/20230806005811/https://www.rondebruin.nl/index.htm) - Simple-Intermediate topics. Note: Ron has archived all these sites, it will not be updated, and some information is out of date, yet it is still an incredible resource for VBA.
- [Bytecomb VBA Reference](https://bytecomb.com/vba-reference/) - Intermediate-advanced topics.
- [Chip Pearson's website](http://www.cpearson.com/excel) - Great resource for beginners-intermediate.
- [VBA for smarties](http://www.snb-vba.eu/inhoud_en.html) - A great reference to numerous data structures and mechanics.
- [Rubberduck Blog](https://rubberduckvba.wordpress.com/) - Intermediate-Advanced topics.
- [![a_ol]](#-) [Slipstick](https://www.slipstick.com/) - Website of Diane Poremsky (MVP) with focus on Outlook and VBA.
- [![a_ol]](#-) [TechnicLee](https://techniclee.wordpress.com/) - Outlook blog, many examples including code variations depending on user request.
- [![a_pp]](#-) [PowerPoint VBA](https://pptvba.com/) - A site devoted to teaching VBA through making games in PowerPoint.
- [MS KB Archive](https://github.com/jeffpar/kbarchive/tree/master/id/vbwin) - Massive archive of vb6/vba problems, solutions and tutorials.
- [Sancarn's vba-articles](https://sancarn.github.io/vba-articles/) - Sancarn's articles on various topics related to VBA.

### Books

- [Hard Core Visual Basic](https://classicvb.net/hardweb/mckinney.htm) - An advanced programmer's guide to the new 5.0 version of Visual Basic. Includes a core set of utilities, shortcuts, and solutions to problems to achieve a wide range of functional programs. A hard book also exists. Also check out the [Comments and corrections](https://jeffpar.github.io/kbarchive/kb/173/Q173840/).
- [The VBA Developer's Handbook](https://www.academia.edu/29801473/VBA_Developers_Handbook_Second_Edition) - Write bulletproof VBA code for any situation. This book is the essential resource for developers working with any of the more than 300 products that employ the "Visual Basic for Applications" programming language. Hardbacks also available elsewhere.
- [Advanced Visual Basic 6](https://pdfcoffee.com/advanced-visual-basic-6-power-techniques-for-everyday-programs978020170712024922-pdf-free.html) - Power Techniques for Everyday Programs Matthew Curland. Hardbacks also available elsewhere.
- [Professional Excel Development](https://oiipdf.com/download/professional-excel-development-the-definitive-guide-to-developing-applications-using-microsoft-excel-vba-and-net) - In this book, four world-class Microsoft® Excel developers offer start-to-finish guidance for building powerful, robust, and secure applications with Excel. Hardbacks also available.
- [![o_paid]](#- '~$6') [Excel VBA Programming For Dummies](https://www.google.com/search?q=Excel+VBA+Programming+For+Dummies+book) - It′s time to move to the next level—creating your own, customized Excel 2010 solutions using Visual Basic for Applications (VBA).Using step–by–step instruction and the accessible, friendly For Dummies style, this practical book shows you how to use VBA, write macros, customize your Excel apps to look and work the way you want, avoid errors, and more.
- [![o_paid]](#- '~$30') [Power Programming with VBA](https://www.wiley.com/en-us/Excel+2019+Power+Programming+with+VBA-p-9781119514916) - Excel 2019 Power Programming with VBA is fully updated to cover all the latest tools and tricks of Excel 2019. Encompassing an analysis of Excel application development and a complete introduction to Visual Basic for Applications (VBA), this comprehensive book presents all of the techniques you need to develop both large and small Excel applications.
- [(E-Book) VBA beginners](https://goalkicker.com/VBABook/)
- [(E-Book) Excel VBA beginners](https://goalkicker.com/ExcelVBABook/)

### YouTube

- [Excel Macro Mastery](https://www.youtube.com/c/Excelmacromastery) - Paul Kelly (MVP) - excelmacromastery.com.
- [Sigma Coding](https://www.youtube.com/c/SigmaCoding) - Large catalogue of tutorials - beginner through to advanced. Delves into interesting areas of VBA not explored by other content creators.
- [WiseOwl's VBA tutorials](https://www.youtube.com/playlist?list=PLNIs-AWhQzckr8Dgmgb3akx_gFMnpxTN5) - Great all-round resource for VBA. Perfect introduction for beginners. In-depth lessons into all aspects of VBA. Huge playlist that covers most types of VBA.
- [![o_paid]](#- 'Some libraries used are non-FOSS and created by VBA A2Z') [VBA A2Z](https://www.youtube.com/c/VBAA2Z) - Many tutorials, some paid content. Good array of interesting and different topics - in-depth tutorials into different parts of VBA, with some .NET/VSTO videos. Strong focus on UI development.
- [Excel VBA Is Fun](https://www.youtube.com/c/ExcelVbaIsFun)
- [Excel for Freelancers](https://www.youtube.com/c/ExcelForFreelancers) - Hands-on tutorials to developing specific applications from beginning through to end. All levels.
- [Leila Gharani](https://www.youtube.com/c/LeilaGharani) - Office-wide focus - useful for beginners.
- [![o_paid]](#- 'The video is from a consultant. Many of his videos are paid for.') [Get to know VBA](https://youtu.be/MFR_XARJjoY) - Some great applications presented and created with VBA.

### Forums

- [Reddit](http://reddit.co.uk/r/vba) - Daily VBA Q&A. Occasional Pro-Tip sharing and Show & Tell library publishing.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vba) - A great place to ask questions. Duplicate questions are flagged as duplicates and send the author to the correct place.
- [Chandoo](https://chandoo.org/wp/) - Forum for the Chandoo - the blog of Purna Duggirala (MVP). Very active.
- [Visual Basic Discord](https://discord.gg/gpcSue9f) - A chat room for VB.NET/VBA/VB6 fanatics.
- [Excel Discord](https://discord.gg/PU2vVDeb) - Discord server moderated by Tim Heng (Excel MVP) with focus on helping Excel users.
- [MrExcel](https://www.mrexcel.com/board/) - Mostly Excel generic, but a lot of VBA content can be found here also.
- [Excel Forum](https://www.excelforum.com/)
- [![a_ol]](#-) [Slipstick](https://www.forums.slipstick.com) - Excellent forum for the Slipstick website (Outlook VBA) of Diane Poremsky (MVP). Diane is quick to respond, and her answers are extremely helpful.
- [VBForums - Office Development](https://www.vbforums.com/forumdisplay.php?37-Office-Development) - Forum with focus on VB6/.NET with VBA section.

## Footnotes

### Symbology

Because of the nature of VBA, many libraries do not work on all Operating Systems, in all Office Applications or in all architectures(x64/x86). Some libraries may also require external resources (DLL, Addins, etc.) which can be difficult to use due to VBA's lack of a package manager. To help you in finding projects suitable for your needs, this awesome list uses the following symbology. The symbology also has tooltips which may provide more information.

#### Platform Compatibility

[p_all]: ./resources/Crown.svg 'Compatible on all platforms'
[p_mac]: ./resources/AppleLogo.svg 'macOS'
[p_win]: ./resources/WindowsLogo.svg 'Windows OS'
[p_now]: ./resources/NotApplicable.svg 'Not Windows OS'
[p_nom]: ./resources/NotApplicable.svg 'Not macOS'

- [![p_win]](#-) [![p_mac]](#-) - Available on all platforms
- [![p_win]](#-) [![p_nom]](#-) - Available on Windows OS only
- [![p_now]](#-) [![p_mac]](#-) - Available on Mac OS only

#### Application compatibility

[a_all]: ./resources/Star.svg 'All applications'
[a_wd]: ./resources/WordLogo.svg 'Word'
[a_xl]: ./resources/ExcelLogo.svg 'Excel'
[a_ac]: ./resources/AccessLogo.svg 'Access'
[a_ol]: ./resources/OutlookLogo.svg 'Outlook'
[a_pp]: ./resources/PowerPointLogo.svg 'PowerPoint'
[a_misc]: ./resources/Duck.svg

- [![a_all]](#-) - All applications
- [![a_wd]](#-) - Word
- [![a_xl]](#-) - Excel
- [![a_ac]](#-) - Access
- [![a_ol]](#-) - Outlook
- [![a_pp]](#-) - PowerPoint
- [![a_misc]](#- 'Misc') - Miscellaneous applications (MS Project, AutoCAD, etc.) - Specify in short description

#### Other important information

[o_32]: ./resources/32-Bit.svg '32-bit only'
[o_pass]: ./resources/Padlock.svg 'VBA is password protected'
[o_dll]: ./resources/Dependencies.svg
[o_inst]: ./resources/Installation.svg 'Requires installation'
[o_paid]: ./resources/Money.svg

- [![o_32]](#-) - 32-bit only
- [![o_pass]](#-) - Written in VBA but the code is password protected
- [![o_dll]](#- 'Requires external dependencies') - Requires external dependencies e.g. `.dll`, `.ocx`, `.o`, etc.
- [![o_inst]](#-) - Requires installation
- [![o_paid]](#- 'Link includes/leads to paid content') - Link includes/leads to paid content

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/sancarn/awesome-vba/blob/master/./Contributing.md) first.
