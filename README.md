# tcltkResources
List of links for tcl/tk packages and resources

Major sources:

  * Tcl/Tk sources
      * Core repositories of Tcl/Tk
      * [Core repository](https://core.tcl-lang.org/index.html) 
        [Official download page](https://www.tcl-lang.org/software/tcltk/download.html) 
        [Tk github mirror](https://github.com/tcltk/tk) 
        [Tcl github mirror](https://github.com/tcltk/tcl)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Tcl/Tk8.6](https://www.tcl-lang.org/man/tcl8.6/contents.htm)
        [Tcl/Tk9.0](https://www.tcl-lang.org/man/tcl9.0/)
  * Tcllib
      * Official Tcl-only collection of packages
      * [Core repository](https://core.tcl-lang.org/tcllib/doc/trunk/embedded/index.md)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Table of content](https://core.tcl-lang.org/tcllib/doc/trunk/embedded/md/toc.md)
  * Tklib
      * Official Tcl-only collection of packages for Tk GUI toolkit
      * [Core repository](https://core.tcl-lang.org/tklib/doc/trunk/embedded/index.md)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [Table of content](https://core.tcl-lang.org/tklib/doc/trunk/embedded/md/toc.md)
  * Tcl/Tk for Windows
      * Batteries included distribution of prebuild Tcl/Tk binaries for Windows
      * [Magicsplat](https://www.magicsplat.com/tcl-installer/index.html)
  * TEA3 (Tcl extension architecture)
      * A set of guidelines and techniques for the distribution, configuration, compilation, and installation of Tcl 
        extensions. TEA also provides a set of utilities that operate accordingly. 
      * [Latest version of sample extension](https://core.tcl-lang.org/sampleextension)
        [Latest version on github with additional helper scripts](https://github.com/apnadkarni/tcl-extension-template)
      * License: MIT-compatible
      * Tcl/Tk version: 8.6/9.0
      * Documentation: [tclwiki page](https://wiki.tcl-lang.org/page/TEA)
        [sample extension wiki page](https://wiki.tcl-lang.org/page/SampleExtension)
        [latest version 3 of TEA wiki page](https://wiki.tcl-lang.org/page/TEA3)

Packages/extensions/libraries/tools outside the official sources:

  * Console enchancement:
      * TkCon
          * Interactive console written in pure Tcl, replacement for tclsh and wish.
          * [Latest version](https://github.com/bohagan1/TkCon)
          * License: MIT-compatible
          * Tcl/Tk version: 8.6/9.0
          * Type: pure Tcl
          * Documentaion: [Original docs](https://tkcon.sourceforge.net/docs/index.html)
            [tclwiki page](https://wiki.tcl-lang.org/page/Tkcon)
      * tclreadline
          * GNU readline for tcl
          * [Latest version](https://github.com/flightaware/tclreadline)
          * License: MIT-compatible
          * Tcl/Tk version: 8.6/9.0
          * Type: C extension
          * Documentation: see README
  
  * Configuration files reader/writer:
      * tclyaml
          * A binding to the C-based libyaml parser library for YAML Ain't Markup Language.
          * [tclyaml](https://core.tcl-lang.org/akupries/tclyaml/doc/trunk/doc/README.md)
          * License: BSD license
          * Tcl/Tk version: 8.6/9.0
          * Type: C extension
          * Documentation: [commands reference](https://core.tcl-lang.org/akupries/tclyaml/doc/trunk/embedded/md/doc/files/tclyaml.md)
          
      * rl_json
          * Extends Tcl with a json value type and a command to manipulate json values directly.
          * [rl_json](https://github.com/RubyLane/rl_json)
          * License: Same as Tcl core
          * Tcl/Tk version: 8.6
          * Type: C extension
          * Documentation: see README

  
  * Documentation tools:
      * Ruff!
          * Documentation generator from the Tcl source code
          * [Source code](https://github.com/apnadkarni/ruff) 
            [Distribution download](https://sourceforge.net/projects/magicsplat/files/ruff/)
          * License: BSD-2-Clause license 
          * Tcl/Tk version: 8.6/9.0
          * Type: pure Tcl
          * Documentation: [Ruff!](https://ruff.magicsplat.com/)
      * tmdoc
          * Literate programming with Tcl - embed Tcl code into Markdown or LaTeX documents with code evaluation.
          * [Source code](https://github.com/mittelmark/tmdoc)
          * License: BSD-3-Clause license
          * Tcl/Tk version: 8.6/9.0
          * Type: pure Tcl
          * Documentation: [Package manual](http://htmlpreview.github.io/?https://github.com/mittelmark/tmdoc/blob/master/modules/tmdoc/tmdoc.html)
            [Package tutorial](http://htmlpreview.github.io/?https://github.com/mittelmark/tmdoc/blob/master/modules/tmdoc/tmdoc-tutorial.html)
  
  * Arguments processing:
      * argparse
          * A feature-heavy argument parser
          * [argparse.tcl](https://core.tcl.tk/tcllib/raw/argparse.tcl?filename=modules/argparse/argparse.tcl&ci=amg-argparse)
            [pkgIndex.tcl](https://core.tcl.tk/tcllib/raw/pkgIndex.tcl?filename=modules/argparse/pkgIndex.tcl&ci=amg-argparse)
          * License: Same as Tcl core
          * Tcl/Tk version: 8.6/9.0(modify `package require` in argparse.tcl)
          * Type: pure Tcl
          * Documentation: [tclwiki](https://wiki.tcl-lang.org/page/argparse)
      * parse_args
          * A fast argument parser based on the patterns established by core Tcl.
          * [Source repository](https://github.com/RubyLane/parse_args)
          * License: Same as Tcl core
          * Tcl/Tk version: 8.6
          * Type: C extension
          * Documentation: see README
   
  * Plotting:
      * ticklecharts
          * Tcl wrapper around Apache ECharts. 
          * [Source repository](https://github.com/nico-robert/ticklecharts)
          * License: MIT
          * Tcl/Tk version: 8.6/9.0
          * Type: pure Tcl (could be speed up with critcl)
          * Documentation: see README
      * implotTk
          * Tcl bindings for Implot.
          * [Source repository](https://github.com/nico-robert/implottk)
          * License: MIT
          * Tcl/Tk version: 8.6
          * Type: pure Tcl
          * Documentation: see README
      * tko::graph
          * 2D graph for plotting X-Y coordinate data
          * [Source repository](https://chiselapp.com/user/rene/repository/tko/index)
          * License: BSD
          * Tcl/Tk version: 8.6/9.0
          * Type: C extension
          * Documentation: [tko::graph](https://chiselapp.com/user/rene/repository/tko/doc/trunk/doc/tko_graph.md)
      * Plotchart
          * Simple plotting and charting package
          * Part of Tcllib
          * License: Same as Tcllib
          * Tcl/Tk version: 8.6/9.0
          * Type: pure Tcl
          * Documentation: [plotchart](https://core.tcl-lang.org/tklib/doc/trunk/embedded/md/tklib/files/modules/plotchart/plotchart.md)
          
  * Misc:
      * Github workflows for Tcl
          * Github action workflows for testing Tcl extensions.
          * [tcl-setup](https://github.com/apnadkarni/tcl-setup)
            [tcl-build-extension](https://github.com/apnadkarni/tcl-build-extension)
          * License: MIT-compatible
          * Tcl/Tk version: 8.6/9.0
          * Documentation: see README
