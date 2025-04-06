# tcltkResources
List of links for tcl/tk packages and resources that I found useful.
Focus is mainly on maintainted tools and packages with Tcl/TK 9.0 support.

  - [Major sources](#major-sources)
  - [Packages/extensions/libraries/tools](#packagesextensionslibrariestools)
    - [Console enchancement](#console-enchancement)
    - [Static analyzers](#static-analyzers)
    - [Special format files readers/writers](#special-format-files-readers-writers)
    - [Network](#network)
    - [Documentation tools](#documentation-tools)
    - [Arguments processing](#arguments-processing)
    - [Plotting](#plotting)
    - [Megawidget collections, Tk frameworks, OO-like widget libraries, alternative geometry managers](#megawidget-collections-tk-frameworks-oo-like-widget-libraries-alternative-geometry-managers)
    - [Megawidgets](#megawidgets)
    - [Ttk themes](#ttk-themes)
    - [Math](#math)
    - [Foreign interface and wrapping of C functions](#foreign-interface-and-wrapping-of-c-functions)
    - [OS API](#os-api)
    - [Debugging](#debugging)
    - [PDF processing](#pdf-processing)
    - [Distribution](#distribution)
    - [Misc](#misc)
  - [IDEs/Editors](#ideseditors)
    - [alited](#alited)
 

## Major sources

  * **Tcl/Tk sources**
      * Core repositories of Tcl/Tk
      * [Core repository](https://core.tcl-lang.org/index.html), 
        [Official download page](https://www.tcl-lang.org/software/tcltk/download.html), 
        [Tk github mirror](https://github.com/tcltk/tk), 
        [Tcl github mirror](https://github.com/tcltk/tcl)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Tcl/Tk8.6](https://www.tcl-lang.org/man/tcl8.6/contents.htm), 
        [Tcl/Tk9.0](https://www.tcl-lang.org/man/tcl9.0/)
  * **Tcllib**
      * Official Tcl-only collection of packages
      * [Core repository](https://core.tcl-lang.org/tcllib/doc/trunk/embedded/index.md)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Table of content](https://core.tcl-lang.org/tcllib/doc/trunk/embedded/md/toc.md)
  * **Tklib**
      * Official Tcl-only collection of packages for Tk GUI toolkit
      * [Core repository](https://core.tcl-lang.org/tklib/doc/trunk/embedded/index.md)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Table of content](https://core.tcl-lang.org/tklib/doc/trunk/embedded/md/toc.md)
  * **Tcl/Tk for Windows**
      * Batteries included distribution of prebuild Tcl/Tk binaries for Windows
      * [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html)
  * **TEA3 (Tcl extension architecture)**
      * A set of guidelines and techniques for the distribution, configuration, compilation, and installation of Tcl 
        extensions. TEA also provides a set of utilities that operate accordingly. 
      * [Latest version of sample extension](https://core.tcl-lang.org/sampleextension), 
        [Latest version on github with additional helper scripts](https://github.com/apnadkarni/tcl-extension-template)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [tclwiki page](https://wiki.tcl-lang.org/page/TEA), 
        [sample extension wiki page](https://wiki.tcl-lang.org/page/SampleExtension), 
        [latest version 3 of TEA wiki page](https://wiki.tcl-lang.org/page/TEA3), 

## Packages/extensions/libraries/tools

### Console enchancement
  * **TkCon**
      * Interactive console written in pure Tcl, replacement for tclsh and wish.
      * [Latest version](https://github.com/bohagan1/TkCon)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentaion: [Original docs](https://tkcon.sourceforge.net/docs/index.html), 
        [tclwiki page](https://wiki.tcl-lang.org/page/Tkcon)
  * **tclreadline**
      * GNU readline for tcl
      * [Latest version](https://github.com/flightaware/tclreadline)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: see README

### Static analyzers
  * **nagelfar**
      * Static code analyzer, supports custom syntax databases and plugins, supports code coverage analysis.
      * [Latest version](https://sourceforge.net/projects/nagelfar/)
      * License: GPLv2
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentaion: [Original docs](https://nagelfar.sourceforge.net/), 
        [tclwiki page](https://wiki.tcl-lang.org/page/Nagelfar)

### Special format files readers/writers
  * **tclyaml**
      * A binding to the C-based libyaml parser library for YAML Ain't Markup Language.
      * [Source repository](https://core.tcl-lang.org/akupries/tclyaml/doc/trunk/doc/README.md)
      * License: BSD license
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [commands reference](https://core.tcl-lang.org/akupries/tclyaml/doc/trunk/embedded/md/doc/files/tclyaml.md)

  * **rl_json**
      * Extends Tcl with a json value type and a command to manipulate json values directly.
      * [Source repository](https://github.com/RubyLane/rl_json)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6
      * Type: C extension
      * Documentation: see README
  * **tclcsv**
      * Tclcsv is a binary extension for reading and writing CSV format files.
      * [Source repository](https://github.com/apnadkarni/tcl-csv)
      * License: Custom, see sources
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [tclcsv](https://tclcsv.magicsplat.com/)
      
### Network
  * **TclTLS**
      * Transport Layer Security (TLS) Extension
      * [Source repository](https://github.com/bohagan1/TclTLS), for prebuilt Windows binaries use 
        [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html) distribution.
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [TclTLS](https://core.tcl-lang.org/tcltls/wiki/Documentation)
  
### Documentation tools
  * **Ruff!**
      * Documentation generator from the Tcl source code
      * [Source repository](https://github.com/apnadkarni/ruff), 
        [Distribution download](https://sourceforge.net/projects/magicsplat/files/ruff/)
      * License: BSD-2-Clause license 
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [Ruff!](https://ruff.magicsplat.com/)
  * **tmdoc**
      * Literate programming with Tcl - embed Tcl code into Markdown or LaTeX documents with code evaluation.
      * [Source repository](https://github.com/mittelmark/tmdoc)
      * License: BSD-3-Clause license
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [Package manual](http://htmlpreview.github.io/?https://github.com/mittelmark/tmdoc/blob/master/modules/tmdoc/tmdoc.html), 
        [Package tutorial](http://htmlpreview.github.io/?https://github.com/mittelmark/tmdoc/blob/master/modules/tmdoc/tmdoc-tutorial.html)

### Arguments processing
  * **argparse**
      * A feature-heavy argument parser
      * [argparse.tcl](https://core.tcl.tk/tcllib/raw/argparse.tcl?filename=modules/argparse/argparse.tcl&ci=amg-argparse), 
        [pkgIndex.tcl](https://core.tcl.tk/tcllib/raw/pkgIndex.tcl?filename=modules/argparse/pkgIndex.tcl&ci=amg-argparse)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0(modify `package require` in argparse.tcl)
      * Type: pure Tcl
      * Documentation: [tclwiki](https://wiki.tcl-lang.org/page/argparse)
  * **parse_args**
      * A fast argument parser based on the patterns established by core Tcl.
      * [Source repository](https://github.com/RubyLane/parse_args)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6
      * Type: C extension
      * Documentation: see README
   
### Plotting
  * **ticklecharts**
      * Tcl wrapper around Apache ECharts. 
      * [Source repository](https://github.com/nico-robert/ticklecharts)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl (could be speed up with critcl)
      * Documentation: see README
  * **implotTk**
      * Tcl bindings for Implot.
      * [Source repository](https://github.com/nico-robert/implottk)
      * License: MIT
      * Tcl/Tk version: 8.6
      * Type: pure Tcl
      * Documentation: see README
  * **tko::graph**
      * 2D graph for plotting X-Y coordinate data
      * [Source repository](https://chiselapp.com/user/rene/repository/tko/index)
      * License: BSD
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [tko::graph](https://chiselapp.com/user/rene/repository/tko/doc/trunk/doc/tko_graph.md)
  * **Plotchart**
      * Simple plotting and charting package
      * Part of Tcllib
      * License: Same as Tcllib
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [plotchart](https://core.tcl-lang.org/tklib/doc/trunk/embedded/md/tklib/files/modules/plotchart/plotchart.md)

### Megawidget collections, Tk frameworks, OO-like widget libraries, alternative geometry managers
  * **tko**
      * oo class like widgets
      * [Source repository](https://chiselapp.com/user/rene/repository/tko/index)
      * License: BSD
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: See source repository
  * **apave (pave)**
      * Tcl/Tk library for GUI development
      * [Source repository](https://github.com/aplsimple/pave)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [apave](https://aplsimple.github.io/en/tcl/pave/)
  * **oowidgets**
      * Megawidget creation package using TclOO
      * [Source repository](https://github.com/mittelmark/oowidgets)
      * License: BSD-3-Clause license 
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [tutorial](https://htmlpreview.github.io/?https://raw.githubusercontent.com/mittelmark/oowidgets/master/tutorial.html), 
        [manual](https://htmlpreview.github.io/?https://raw.githubusercontent.com/mittelmark/oowidgets/master/oowidgets/oowidgets.html)
  * **BWidget**
      * BWidget is a mega-widget package 
      * [Source repository](https://core.tcl-lang.org/bwidget/home)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [BWidget](https://core.tcl-lang.org/bwidget/doc/bwidget/BWman/index.html), for prebuilt Windows 
        binaries use [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html) distribution.
  * **wob**
      * Create widgets with their own Tcl object and their own interpreter.
      * [Source repository](https://github.com/ambaker1/wob)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [wob](https://raw.githubusercontent.com/ambaker1/wob/main/doc/wob.pdf)
  * **TKproE**
      * Visual Tk designer
      * [Source repository](https://sourceforge.net/projects/tkproe/)
      * License: BSD
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [Documentation](https://tkproe.dengensys.com/)
### Megawidgets
  * **Tablelist**
      * The multi-column listbox and tree widget package.
      * [Source repository](https://www.nemethi.de/), also included into Tklib
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [Tablelist](https://www.nemethi.de/tablelist/index.html)
  * **TkTreeCtrl**
      * Multi-column hierarchical listbox widget for Tk.
      * [Mantained repository with tcl 9 support](https://chiselapp.com/user/egavilan/repository/Tktreectrl-Tk9/index), 
        [Original unmaintained source repository](https://tktreectrl.sourceforge.net/), for prebuilt Windows binaries use 
        [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html) distribution.
      * License: BSD License
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [TkTreeCtrl](https://tktreectrl.sourceforge.net/treectrl.html)
  * **TkTable**
      * TkTable is a full-featured 2D table widget for Tk.
      * [Latest updated version source repository](https://github.com/bohagan1/TkTable)
        [Original unmaintained source repository](https://sourceforge.net/projects/tktable/) for prebuilt Windows binaries
        use [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html) distribution.
      * License: BSD License
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [TkTable](https://tktable.sourceforge.net/tktable/doc/tkTable.html)
  * **bartabs**
      * Highly improved tab bar widget for Tcl/Tk.
      * [Source repository](https://github.com/aplsimple/bartabs)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [bartabs](https://aplsimple.github.io/en/tcl/bartabs/index.html)
  * **baltip**
      * Tcl/Tk package of tooltip and balloon.
      * [Source repository](https://github.com/aplsimple/baltip)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [baltip](https://aplsimple.github.io/en/tcl/baltip/baltip.html)
  * **playtkl**
      * Testing scenarios for Tcl/Tk applications & playing macros.
      * [Source repository](https://github.com/aplsimple/playtkl)
      * License: MIT
      * Tcl/Tk version: 8.6
      * Type: pure Tcl
      * Documentation: [playtkl](https://aplsimple.github.io/en/tcl/playtkl/playtkl.html)

### Ttk themes
  * **ale_themes**
      * It's a batch of Tcl/Tk themes.
      * [Source repository](https://github.com/aplsimple/ale_themes)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: see README

### Math
  * **VecTcl**
      * Provides a numerical array extension for Tcl with support for vectors, matrices and higher-rank tensors of 
        integers, floating point and complex numbers.
      * [Source repository](https://github.com/auriocus/VecTcl), 
        [Port to Tcl9](https://github.com/bgriffinfortytwo/VecTcl9/tree/abstractlist)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [VecTcl](http://auriocus.github.io/VecTcl/)
  * **ndlist**
      * A pure Tcl implementation of arbitrary rank tensors.
      * [Source repository](https://github.com/ambaker1/ndlist)
      * License: BSD-2-Clause license
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [ndlist](https://raw.githubusercontent.com/ambaker1/ndlist/main/doc/ndlist.pdf)
  * **tclinterp**
      * Tcl wrapper for C interpolation routines
      * [Source repository](https://github.com/georgtree/tclinterp)
      * License: LGPL-2.1 license
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [tclinterp](https://georgtree.github.io/tclinterp/)
     
### Foreign interface and wrapping of C functions
  * **SWIG**
      * SWIG is a software development tool that connects programs written in C and C++ with a variety of high-level 
        programming languages, including Tcl.
      * [Source repository](https://github.com/swig/swig), [Main website](https://www.swig.org/)
      * License: multiple licenses, including GPL. Code generated by SWIG, which is not governed by copyright.
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [SWIG](https://www.swig.org/Doc4.3/SWIGDocumentation.html)
  * **tcl-cffi**
      * A Foreign Function Interface extension for Tcl.
      * [Source repository](https://github.com/apnadkarni/tcl-cffi)
      * License: BSD-2-Clause license
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [tcl-cffi](https://cffi.magicsplat.com/)
  * **critcl**
      * C Runtime In Tcl, CriTcl for short, a system to build C extension packages for Tcl on the fly, from C code embedded within Tcl scripts.
      * [Source repository](https://github.com/andreas-kupries/critcl)
      * License: Same as Tcl core
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [critcl](https://andreas-kupries.github.io/critcl/)
  
### OS API
  * **twapi**
      * The Tcl Windows API (TWAPI) extension provides access to the Windows API from within the Tcl scripting language.
      * [Source repository](https://github.com/apnadkarni/twapi)
      * License: Custom, see sources.
      * Tcl/Tk version: 8.6/9.0
      * Type: C extension
      * Documentation: [twapi](https://twapi.magicsplat.com/)

### Debugging
  * **flytrap**
      * Tcl debugging tools.
      * [Source repository](https://github.com/ambaker1/flytrap)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [flytrap](https://raw.githubusercontent.com/ambaker1/flytrap/main/doc/flytrap.pdf)

### PDF processing
  * **tclfpdf**
      * Port of tFPDF (PHP) by by Ian Back and Tycho Veltmeijer (modified version of FPDF by Olivier Plathey) to TCL.
      * [Source repository](https://github.com/lamuzzachiodi/tclfpdf)
      * License: Custom
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
  * **pdf4tcl**
      * pdf4tcl is a tcl package for generating pdf files.
      * [Source repository](https://sourceforge.net/projects/pdf4tcl/)
      * License: BSD
      * Tcl/Tk version: 8.6/9.0
      * Type: pure Tcl
      * Documentation: [pdf4tcl](https://pdf4tcl.sourceforge.net/pdf4tcl.html)
      
### Distribution
  * **Freewrap**
      * Tool for wrapping Tcl application to single executable
      * [Source repository](https://sourceforge.net/projects/freewrap/) 
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Documentation](https://freewrap.dengensys.com/)

### Misc
  * **Github workflows for Tcl**
      * Github action workflows for testing Tcl extensions.
      * [tcl-setup](https://github.com/apnadkarni/tcl-setup), 
        [tcl-build-extension](https://github.com/apnadkarni/tcl-build-extension)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: see README

## IDEs/Editors
  * **alited**
      * Text editor with main focus on Tcl/Tk projects. Written in pure Tcl, ideally suited for Tcl/Tk development.
      * [Source repository](https://github.com/aplsimple/alited)
      * License: MIT
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [documentation](https://aplsimple.github.io/en/tcl/alited/)
