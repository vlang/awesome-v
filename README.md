<!--lint disable no-dead-urls-->

<p align="center"><img src="media/awesome-v-logo.svg" width="400"/></p>

# Awesome V [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome V frameworks, libraries, software and resources.

[V](https://vlang.io/) is a simple, fast, safe, compiled language for developing maintainable software.

## Contents

- [Applications](#applications)
  - [Interpreters/Compilers](#interpreterscompilers)
  - [Operating systems/Kernels](#operating-systemskernels)
  - [Package managers](#package-managers)
  - [Editors](#editors)
  - [Web](#web)
  - [Graphics](#graphics)
  - [Games](#games)
  - [Command-line](#command-line)
  - [Project management](#project-management)
  - [Serialization](#serialization)
- [Libraries](#libraries)
  - [Command line interface (CLI) / Terminal / Shell](#command-line-interface-cli--terminal--shell)
  - [Text processing](#text-processing)
  - [Graphics](#graphics-1)
  - [Game development](#game-development)
  - [Web](#web-1)
  - [Database clients](#database-clients)
  - [Audio](#audio)
  - [Operating system](#operating-system)
  - [Automation](#automation)
  - [Telegram](#telegram)
  - [Discord](#discord)
  - [IRC](#irc)
  - [Files](#files)
  - [Eventing](#eventing)
  - [User Interface toolkits](#user-interface-toolkits)
  - [Scientific computing](#scientific-computing)
  - [Utility](#utility)
- [Other](#other)
  - [Syntax highlighting](#syntax-highlighting)
  - [Editor plugins](#editor-plugins)
  - [GitHub actions](#github-actions)
  - [Videos](#videos)
  - [Programming contests](#programming-contests)
  - [Tutorials](#tutorials)
  - [Online IDEs with V](#online-ides-with-v)
  - [Articles](#articles)
  - [Communities](#communities)
  - [Forums](#forums)

## Applications

### Interpreters/Compilers

- [v](https://github.com/vlang/v) - V itself. Simple, fast, safe, compiled language for developing maintainable software.
- [vbf](https://github.com/vpervenditti/vbf) - A brainfuck interpreter/compiler.
- [monkey_v](https://github.com/Delta456/monkey_v) - Implementation of [Thorsten Ball's Monkey Language](https://interpreterbook.com/) in V.
- [vcc](https://github.com/lemoncmd/vcc) - A C compiler written in V.
- [Vork](https://github.com/Itay2805/Vork) - Alternative V compiler/interpreter written in Python.
- [Foxil](https://github.com/StunxFS/foxil) - An intermediate language designed to facilitate compiler code generation.


### Operating systems/Kernels

- [Vinix](https://github.com/vlang/vinix) - Small and simple OS in V. Runs bash.

### Package managers

- [vpm](https://github.com/yue-best-practices/vpm) - The V language package management tool written in V.

### Editors

- [ved](https://github.com/vlang/ved) - 1 MB text editor written in V with hardware accelerated text rendering. Compiles in <1s.

### Web

- [vorum](https://github.com/vlang/vorum) - Open-source blogging/forum software written in V.
- [vblog](https://github.com/scurty-labs/vblog) - A simple, fast and responsive blogging system.
- [Heroku Buildpack for V](https://github.com/louis77/heroku-buildpack-v) - Deploy V apps on Heroku.

### Graphics

- [vRayTracer](https://github.com/ali-raheem/vraytracer) - A simple ray tracer written in V.

### Games

- [Boundstone](https://github.com/organization/boundstone) - High Performance / Fast Compilation / Lightweight Minecraft: Bedrock Edition Server.
- [v-pong](https://github.com/thebigsmileXD/v-pong) - A classic paddle game brought back to life through the power of V.
- [flappylearning-v](https://github.com/uxnow/flappylearning-v) - A simple flappy learning demo in v. ( Archived )

### Command-line

- [HN-top](https://github.com/BafS/hn-top) - A simple command to list most recent news from hacker-news.
- [vast](https://github.com/lydiandy/vast) - A simple tool for vlang, generate v source file to AST json file.
- [symlinker](https://github.com/serkonda7/symlinker) - A small Linux tool to manage symlinks.
- [runner](https://github.com/Naheel-Azawy/runner) - A tool that automates running/compiling code written in various programming languages.
- [vcredits](https://github.com/zakuro9715/vcredits) - A tool that creates CREDITS from LICENSE files of dependencies.
- [vspect](https://github.com/zakuro9715/vspect) - A tool to inspect vlang source file.
- [vinit](https://github.com/pranavbaburaj/vinit) - A tool to generate v projects.

### Project management

- [vset](https://github.com/mulh8377/vset) - A project setup and configuration tool for V projects.

### Serialization

- [vproto](https://github.com/emily33901/vproto) - Protobuf compiler and runtime in V.
- [v-toxml](https://github.com/radare/v-toxml) - XML Serialization library for V.
- [vlang-yaml](https://github.com/jdonnerstag/vlang-yaml) - A V-native YAML reader, incl. YAML-to-JSON converter.

## Libraries

### Command line interface (CLI) / Terminal / Shell

- [boxx](https://github.com/thecodrr/boxx) - Create highly customizable terminal boxes that also look great! 📦
- [lol](https://github.com/0xLeif/lol) - V version of lolcat (text/character rainbowizer).
- [progressbar](https://github.com/Waqar144/progressbar) - An easy to use V library for creating progress bars in cli.
- [termtable](https://github.com/serkonda7/termtable) - V Terminal Tables: Simple and highly customizable library to display tables in the terminal.
- [vargs](https://github.com/nedpals/vargs) - V library for parsing arguments from argv-like arrays. ( Archived )

### Text processing

- [v-regex](https://github.com/spytheman/v-regex) - A simple regex library for V.
- [chalk](https://github.com/etienne-napoleone/chalk) - Colorize strings in the terminal.
- [crayon](https://github.com/thecodrr/crayon) - Paint your terminal output like Picasso. 🖍️🎨
- [cjson](https://github.com/lydiandy/cjson) - Wrap cJSON for vlang.
- [ascii_robot](https://github.com/Delta456/ascii_robot) - ASCII Robot generator written in V.
- [iconv](https://github.com/fanlia/iconv) - Wrap iconv for vlang.
- [Rosie-RPL](https://github.com/jdonnerstag/vlang-rosie) - A Rosie Pattern Language (RPL) implementation.

### Graphics

- [vgl](https://github.com/justicesuh/vgl) - Low-level graphics API access.
- [viup](https://github.com/kjlaw89/viup) - V wrapper for the C-based cross-platform UI library, IUP.
- [vsdl](https://github.com/kjlaw89/vsdl) - V wrapper for the C-based SDL library.
- [vsdl2](https://github.com/nsauzede/vsdl2) - A libSDL2 wrapper.
- [V Earcut](https://github.com/Larpon/earcut) - fast (real-time) polygon triangulation library based on [mapbox/Earcut](https://github.com/mapbox/earcut) to handle holes, twisted polygons, degeneracies and self-intersections.

### Game development

- [raylib.v](https://github.com/irishgreencitrus/raylib.v) - Updated V bindings for [raylib](https://www.raylib.com) with plans for complete cross-platform support.
- [vraylib](https://github.com/MajorHard/vraylib) - V wrapper (bindings) for raylib, the C game development framework.

### Web

- [vex](https://github.com/nedpals/vex) - Web framework written on V inspired by Express and Sinatra.
- [vweb](https://github.com/vlang/v/tree/master/vlib/vweb) - V's built-in web framework. Used by Vorum.
- [validate](https://github.com/endeveit/v-validate) - A simple library to validate strings in V.
- [valval](https://github.com/taojy123/valval) - Web framework written in V, improved by vweb.
- [v-jsonrpc](https://github.com/nedpals/v-jsonrpc) - Basic JSON-RPC 2.0-compliant server written on V.
- [pico.v](https://github.com/S-YOU/pico.v) - A web server in V based on picoev and picohttpparser.
- [vxbloauth](https://github.com/WolvesFortress/vxbl-oauth) - A minimalistic Xbox Live authenticator for vweb.
- [vcurrency](https://github.com/mehtaarn000/vcurrency) - API wrapper (written in V) for [https://api.exchangeratesapi.io](https://api.exchangeratesapi.io).

### Database clients

- [redis](https://github.com/patrickpissurno/vredis) - Redis client for V, written in V.
- [vsql](https://github.com/lydiandy/vsql) - A sql query builder for V.
- [vmemcached](https://github.com/blacktrub/vmemcached) - Memcached client for V, written in V.

### Audio

- [vave](https://github.com/thecodrr/vave) - A crazy simple library for reading/writing WAV files in V. 🌊
- [vspeech](https://github.com/thecodrr/vspeech) - Complete V bindings for Mozilla's DeepSpeech TensorFlow based Speech-to-Text library. 📢📜
- [v-miniaudio](https://github.com/Larpon/v-miniaudio) - Bindings for the excellent miniaudio C audio library.

### Operating system

- [clipboard](https://github.com/vlang/v/tree/master/vlib/clipboard) - V module for interacting with the OS clipboard. Fully cross-platform.
- [vlipboard](https://github.com/asvvvad/vlipboard) - An easy to use wrapper of clipboard with Wayland and Termux support.
- [mmap](https://github.com/jdonnerstag/vlang-mmap) - Provide native V-lang support for memory-mapping on Linux and Windows.

### Automation

- [vrobot](https://github.com/eioo/vrobot) - Desktop automation for V. Only supports Windows.

### Telegram

- [vgram](https://github.com/dariotarantini/vgram) - Telegram bot library.

### Discord

- [viscord](https://github.com/vlang/viscord) - Pretty basic library for connecting to the Discord gateway.
- [discord.v](https://github.com/Terisback/discord.v) - User-friendly Discord bot library.

### IRC

- [vitric](https://github.com/m-242/vitric) - A transparent IRC library.

### Files

- [v-mime](https://github.com/nedpals/v-mime) - MIME detection library for V.

### Eventing

- [eventbus](https://github.com/vlang/v/tree/master/vlib/eventbus) - A simple event bus system for V.

### User Interface toolkits

- [V UI](https://github.com/vlang/ui) - Integrated cross platform UI toolkit for Windows, macOS, Linux, Android, iOS and the web.
- [vgtk3](https://github.com/vgtk/vgtk3) - A wrapper for GTK3 in V.
- [vig](https://github.com/nsauzede/vig) - Bindings for [Dear ImGui](https://github.com/ocornut/imgui) GUI toolkit.
- [vnk](https://github.com/nsauzede/vnk) - Bindings for [Nuklear](https://github.com/vurtun/nuklear) GUI toolkit.

### Scientific computing

- [vsl](https://github.com/vlang/vsl) - A pure-V scientific library with a great variety of functions.
- [vtl](https://github.com/vlang/vtl) - Numerical computing library supporting n-dimensional data structure, backed by LAPACKE and OpenBLAS.

### Utility

- [range](https://github.com/Delta456/range) - Functionality of Python's range() in V.
- [random](https://github.com/Delta456/random) - An all purpose random library written in V.
- [vdotenv](https://github.com/zztkm/vdotenv) - Support for .env files which loads environment variables.

## Other

### Syntax highlighting

- [v-vim](https://github.com/ollykel/v-vim) - Support for V syntax highlighting in Vim.
- [vim-v](https://github.com/cheap-glitch/vim-v) - Quality syntax highlighting for the V programming language.
- [vscode-vlang](https://github.com/0x9ef/vscode-vlang) - V Language extension for Visual Studio Code.
- [kate-syntax-highlight-v](https://github.com/Larpon/kate-syntax-highlight-v) - V syntax highlighting for [Kate](https://kate-editor.org/).
- [scite-v-support](https://github.com/sunnylcw/scite-v-support) - V syntax highlighting for [SciTE](https://www.scintilla.org/SciTE.html).
- [language-v](https://github.com/Cutlery-Drawer/language-v) - V language support for Atom (port of vscode-vlang).
- [vlang-mode.el](https://github.com/Naheel-Azawy/vlang-mode.el) - Emacs major mode for the V programming language.
- [v-mode](https://github.com/damon-kwok/v-mode) - Emacs major mode for the V programming language.
- [vlang-sublime](https://github.com/oversoul/vlang-sublime) - Sublime text 3 Support for the Vlang Programming Language.

### Editor plugins

- [vim-vtools](https://github.com/zakuro9715/vim-vtools) - V tools for Vim, including auto formatting.
- [sublime-v](https://github.com/onerbs/sublime-v) - Fully-featured Sublime Text 3 package for the V Programming Language.

### GitHub actions

- [setup-v-action](https://github.com/marketplace/actions/setup-v-environment) - GitHub action automation to use V in your workflow.
- [action-create-v-docs](https://github.com/marketplace/actions/create-documentation-for-v-modules) - GitHub action to create documentation for V modules.

### Videos

- [V Programming Tutorials](https://www.youtube.com/watch?v=BVCuZ7z7GMY&list=PLEPMhdsq-gNpFr40A-ZnX-Hu9l-Sp5Oc_)
- [The V Programming Language](https://www.youtube.com/channel/UCLZIElNyubHOvbfudT7KS1A)

### Programming contests

- [Rosetta Code V](https://github.com/RustemB/rosetta-code-v) - Solutions for Rosetta Code in V.
- [Advent of Code 2019](https://github.com/mvlootman/aoc2019) - Solution of Advent of Code 2019 in V.
- [SoloLearn Coding Challenges](https://github.com/Serkonda/v-sololearn-coding-challenges) - Implementation of the SoloLearn coding challenges in V.

### Tutorials

- [Learn V in Y Minutes](https://github.com/v-community/learn_v_in_y_minutes)
- [V by Example](https://github.com/v-community/v_by_example) - V book as [GitBook](https://v-community.gitbook.io/v-by-example/).
- [V learning notes](https://github.com/lydiandy/vlang_note) - Personal learning notes in Chinese.

### Online IDEs with V

- [V Playground](https://v-wasm.now.sh/)

### Articles

- [An introduction to V](https://simonknott.de/articles/VLang.html)
- [The Book of V](https://github.com/KeyWeeUsr/the-book-of-v/)

### Communities

- [V Community](https://github.com/v-community)

### Forums

- [r/vlang](https://www.reddit.com/r/vlang)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vlang)
