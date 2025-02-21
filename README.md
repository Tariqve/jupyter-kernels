
## Jupyter kernels 

Kernel Zero is [IPython](https://ipython.org), which you can get through [ipykernel](https://pypi.python.org/pypi/ipykernel), and is still a dependency of [jupyter](https://jupyter.org). The IPython kernel can be thought of as a reference implementation, as CPython is for Python.

Here is a list of available Jupyter kernels. If you are writing your own kernel, feel free to add it to the table!

<div style="display: block; min-width: 100%; overflow: visible; font-size: 7pt">

| Language(s) Version |Name| Jupyter/IPython Version | 3rd party dependencies | Example Notebooks | Notes |
|---------------------|----|-------------------------|------------------------|-------------------|-------|
| |[LFortran](https://lfortran.org/) | | | | Main repository at [GitHub](https://github.com/lfortran/lfortran) |
||[JupyterQ (KX Official Kernel)](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels)|Jupyter|kdb+ ≥ v3.5 64-bit, Python ≥ 3.6, embedPy|[Notebook Examples](https://github.com/KxSystems/jupyterq/blob/master/examples/q_widgets.ipynb)|
||[Calysto LC3](https://github.com/Calysto/calysto_lc3)||||Assembly Language for the [Little Computer 3](https://en.wikipedia.org/wiki/LC-3)|
||[elm-kernel](https://github.com/abingham/jupyter-elm-kernel)|Jupyter||[Examples](https://github.com/abingham/jupyter-elm-kernel/tree/master/examples)||
||[BeakerX](http://beakerx.com/)||Groovy, Java, Scala, Clojure, Kotlin, SQL|[example](https://github.com/twosigma/beakerx/blob/master/doc/StartHere.ipynb)|[docker image](https://hub.docker.com/r/beakerx/beakerx/)|
|*multiple*|[ICalico](http://wiki.roboteducation.org/ICalico)|IPython >= 2||[Index](http://nbviewer.jupyter.org/urls/bitbucket.org/ipre/calico/raw/master/notebooks/Index.ipynb)||
| 2.6.0 |[Agda kernel](https://github.com/lclem/agda-kernel) | | | https://mybinder.org/v2/gh/lclem/agda-kernel/master?filepath=example/LabImp.ipynb |  |
|APL (Dyalog)|[Dyalog Jupyter Kernel](https://github.com/Dyalog/dyalog-jupyter-kernel)| |[Dyalog](https://www.dyalog.com/download-zone.htm) >= 15.0|[Notebooks](https://github.com/Dyalog/dyalog-jupyter-notebooks)|Can also be run on [TryAPL](https://tryapl.org/)'s Learn tab|
|ARMv6 THUMB|[IArm](https://github.com/DeepHorizons/iarm)|Jupyter 4||[Examples](http://nbviewer.jupyter.org/github/DeepHorizons/iarm/tree/master/docs/examples/)|Based off of the ARM Cortex M0+ CPU|
|Aldor|[IAldor](https://github.com/mattpap/IAldor)|IPython >= 1||||
| Ansible 2.x | [Ansible Jupyter Kernel](https://github.com/ansible/ansible-jupyter-kernel) | Jupyter 5.6.0.dev0 | | [Hello World](https://github.com/ansible/ansible-jupyter-kernel/blob/master/notebooks/HelloWorld.ipynb) | |
|Any|[Juka](https://github.com/jukaLang/juka_kernel)|Jupyter 4|[Juka](https://jukalang.com/download)|[Example](https://github.com/jukaLang/juka_kernel/blob/main/JukaTest.ipynb)|Wrapper. Requires [Juka](https://jukalang.com/download) executable in PATH|
|Any|[SageMath](http://www.sagemath.org/)|Jupyter 4|many|||
|Babel|[jp-babel](https://www.npmjs.com/package/jp-babel)|Jupyter||||
|Bash|[SSH Kernel](https://github.com/NII-cloud-operation/sshkernel)|Jupyter|paramiko, metakernel|[Examples](https://github.com/NII-cloud-operation/sshkernel/tree/master/examples)|A Jupyter kernel specialized in executing commands remotely with paramiko SSH client.|
|Bash|[Bash](https://github.com/takluyver/bash_kernel)|IPython >= 3|||Wrapper|
|Bash|[Calysto Bash](https://github.com/Calysto/calysto_bash)||||MetaKernel|
|Basilisp|[basilisp-kernel](https://github.com/ikappaki/basilisp-kernel)|||[Examples](https://github.com/ikappaki/basilisp-kernel/tree/main/notebooks)|[Basilisp](https://github.com/basilisp-lang/basilisp) is a Python based Lisp implementation broadly compatible with Clojure|
|Brainfuck|[IBrainfuck](https://github.com/robbielynch/ibrainfuck)|||[Example](https://github.com/robbielynch/ibrainfuck/blob/master/notebooks/a-brief-look-at-brainfuck.ipynb)|Wrapper|
|C|[C](https://github.com/brendan-rius/jupyter-c-kernel)|Jupyter|`gcc`||||
|C|[jupyterC](https://github.com/XaverKlemenschits/jupyter-c-kernel)|Jupyter|`gcc>=3.0`||Supports `C89` to `C17`, Built for teaching C||
|C/C++|[c-kernel](https://c-kernel.readthedocs.io/en/latest/index.html)|Jupyter|||Automatic compilation, customisable kernel, interactive input and multi-file programs. Intended for easy teaching/learning of C/C++||
|C/C++|[jupyter-cpp-kernel](https://github.com/takinekotfs/jupyter-cpp-kernel)|Jupyter|`g++>=13.2`|[Document](https://github.com/takinekotfs/jupyter-cpp-kernel-doc)|C++ kernel for Jupyter. Easily adopt and deployment for testing environment.||
|C# 4.0+|[ICSharp](https://github.com/zabirauf/icsharp)|Jupyter 4.0|scriptcs|||
| C#, F#, Powershell|[.Net Interactive](https://github.com/dotnet/interactive/)|Jupyter 4| [.Net Core SDK](https://dotnet.microsoft.com/download) |[Binder Examples](https://github.com/dotnet/interactive/blob/main/docs/NotebooksOnBinder.md) |
|C++|[cling](https://github.com/root-mirror/cling)|Jupyter 4||[Example](https://github.com/root-mirror/cling/blob/master/tools/Jupyter/kernel/cling.ipynb)||
|C++|[xeus-cling](https://github.com/QuantStack/xeus-cling)|Jupyter >= 5.1||[Example](https://github.com/QuantStack/xeus-cling/tree/master/notebooks)|Supports Jupyter widgets|
|C++|[xeus-cpp](https://github.com/compiler-research/xeus-cpp)|||[Example](https://mybinder.org/v2/gh/compiler-research/xeus-cpp/main?urlpath=/lab/tree/notebooks/xeus-cpp.ipynb)|Supports Windows, unlike xeus-cling |
|C++/python|[ROOT](https://github.com/root-project/root/tree/master/bindings/jupyroot)|Jupyter|ROOT >= 6.05|||
|bc, C, C++, ngspice, Octave, PlantUML|[GPP](https://github.com/user1095108/jupyter-gpp-kernel)|Jupyter|`gcc`, `clang`|[Example](https://github.com/user1095108/jupyter-gpp-kernel/blob/master/example.ipynb)|MetaKernel||
|[Cadabra2](https://cadabra.science)|[Cadabra2](https://github.com/kpeeters/cadabra2/blob/master/JUPYTER.rst)|Jupyter 5||[Example notebook](https://github.com/kpeeters/cadabra2/blob/master/examples/schwarzschild.ipynb)||
|Cassandra CQL|[cqljupyter](https://github.com/bschoening/cqljupyter)|Jupyter||[CQL Examples](https://github.com/bschoening/cqljupyter/blob/master/Sample.ipynb)|
|[Chapel](https://github.com/chapel-lang/chapel/)|[jupyter_kernel_chapel](http://github.com/krishnadey30/jupyter_kernel_chapel)|Jupyter||||
|[CircuitPython](https://github.com/adafruit/circuitpython)|[circuitpython_kernel](https://github.com/adafruit/circuitpython_kernel)|Jupyter|USB| [Examples](https://github.com/adafruit/circuitpython_kernel/tree/master/examples)|
|ClickHouse SQL|[xeus-clickhouse](https://github.com/wangfenjin/xeus-clickhouse)||[xeus](https://github.com/jupyter-xeus/xeus)|[Example](https://github.com/wangfenjin/xeus-clickhouse/blob/master/examples/clickhouse.ipynb)|  |
|Clingo|[iclingo](https://github.com/thesofakillers/iclingo)|IPython 8|[clingo](https://pypi.org/project/clingo/)|[Basic Examples](https://github.com/thesofakillers/iclingo/tree/main/examples)||
|Clojure |[CLJ-Jupyter](https://github.com/achesnais/clj-jupyter)|Jupyter|||Abandoned as of 2017-02-12|
|Clojure 1.8|[jupyter-kernel-jsr223](https://github.com/fiber-space/jupyter-kernel-jsr223)|Jupyter>=4.0|[clojure-jrs223](https://github.com/ato/clojure-jsr223), Java>=7||Java based JSR223 compliant||
|Clojure >= 1.7|[CloJupyter](https://github.com/roryk/clojupyter)|Jupyter||||
|Coconut|[Coconut](http://coconut-lang.org/)|Jupyter|||||
|Coffeescript >= 1.7|[jpCoffeescript](https://github.com/n-riesco/jp-coffeescript)|||||
|Common Lisp|[common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)|Jupyter|Quicklisp|[About](https://github.com/fredokun/cl-jupyter/blob/master/examples/about.ipynb)||
|Coq|[coq_jupyter](https://github.com/EugeneLoy/coq_jupyter)|Jupyter 5|coq|[Binder online demo](https://mybinder.org/v2/gh/EugeneLoy/coq_jupyter_demo/master?filepath=demo.ipynb)||
|Cryptol|[ICryptol](https://github.com/GaloisInc/ICryptol)||CVC4|||
|Crystal|[ICrystal](https://github.com/RomainFranceschini/icrystal)|Jupyter|[IRC](https://github.com/crystal-community/icr)|||
|Crystal|[crystal_kernel](https://github.com/crystal-data/crystal_kernel)|Jupyter|||Python wrapper kernel [Crystal interpreter](https://crystal-lang.org/2021/12/29/crystal-i.html)|
|Dart|[jupyter-dart-kernel](https://github.com/vickumar1981/jupyter-dart-kernel)|Jupyter|dart||
|Deno|[jupyter-deno-kernel](https://docs.deno.com/runtime/manual/tools/jupyter)|Jupyter|Deno >= 1.37.0||
|Dg (Doge)|[idg](https://github.com/LeaveNhA/idg)|Jupyter||[Example Notebooks](https://github.com/LeaveNhA/UIST602-DG)||
|Dockerfile|[dockerfile-kernel](https://github.com/ssciwr/dockerfile-kernel)|JupyterLab|Docker||User should be in the docker group.|
|Dot/graphviz|[jupyter-dot-kernel](https://github.com/laixintao/jupyter-dot-kernel)|Jupyter >= 4.0|graphviz version 2.40.1| | | |
|ESP8266/ESP32|[MicroPython](https://github.com/goatchurchprime/jupyter_micropython_kernel/)|Jupyter|USB or Webrepl|[developer notebooks](https://github.com/goatchurchprime/jupyter_micropython_developer_notebooks)|relies on the micro-controller's paste-mode|
|Elixir >= 1.5|[IElixir](https://github.com/pprzetacznik/IElixir)|Jupyter >= 4.0|Erlang OTP >= 19.3, Rebar|[example](https://github.com/pprzetacznik/IElixir/blob/master/resources/example.ipynb), [Boyle package manager examples](https://github.com/pprzetacznik/IElixir/blob/master/resources/boyle%20example.ipynb), [Boyle examples with usage of Matrex library](https://github.com/pprzetacznik/IElixir/blob/master/resources/boyle%20example%20-%20matrex%20installation%20and%20usage.ipynb)|[IElixir Docker image](https://hub.docker.com/r/pprzetacznik/ielixir/), [IElixir Notebook in Docker](https://mattvonrocketstein.github.io/heredoc/ielixir-notebook-in-docker.html#sf-ielixir-notebook-in-docker-2-back)|
|Emacs Lisp|[ielisp](https://github.com/shwina/ielisp)|Jupyter|[emacs-zmq](https://github.com/nnicandro/emacs-zmq)|||
|Erlang|[IErlang](https://github.com/robbielynch/ierlang)|IPython 2.3|rebar|||
|Erlang >= 19, Elixir >= 1.4, LFE 1.2|[ierl](https://github.com/filmor/ierl)|Jupyter >= 4.0|Erlang, (optional) Elixir||
|F#|[IFSharp](https://github.com/fsprojects/IfSharp)|Jupyter 4||[Features](https://github.com/fsprojects/IfSharp/blob/master/FSharp_Jupyter_Notebooks.ipynb)||
|Forth|[IForth](https://github.com/jdfreder/iforth)|IPython >= 3||||
|Forth|[peforth](https://github.com/hcchengithub/peforth)|IPython 6/Jupyter 5||[Example](https://github.com/hcchengithub/peforth/wiki)|python debugger in FORTH syntax|
|Fortran 2008/2015|[Coarray-Fortran](https://github.com/sourceryinstitute/jupyter-CAF-kernel)|Jupyter 4.0|GFortran >= 7.1, [OpenCoarrays](https://github.com/sourceryinstitute/OpenCoarrays), [MPICH](https://mpich.org) >= 3.2|[Demo](https://nbviewer.jupyter.org/github/sourceryinstitute/jupyter-CAF-kernel/blob/master/index.ipynb), [Binder demo](https://beta.mybinder.org/v2/gh/sourceryinstitute/jupyter-CAF-kernel/master?filepath=index.ipynb)|[Docker image](https://hub.docker.com/r/sourceryinstitute/jupyter-caf-kernel/)|
|GAP >= 4.10|[GAP Kernel](https://gap-packages.github.io/JupyterKernel/)|Jupyter||[Binder demo](https://github.com/gap-system/try-gap-in-jupyter)|A Jupyter kernel for the computational algebra system [GAP](https://www.gap-system.org/).|
|Galileo >= 0.1.3|[iGalileo](https://github.com/cascala/igalileo)|Jupyter >= 4, JupyterLab|||[Docker image](https://hub.docker.com/r/cascala/igalileo/)|
|Ghc >= 7.6|[IHaskell](https://github.com/gibiansky/IHaskell)||||[Demo](https://begriffs.com/posts/2016-01-20-ihaskell-notebook.html)|
|Gnuplot|[Gnuplot Kernel](https://github.com/has2k1/gnuplot_kernel)|||[Example](https://github.com/has2k1/gnuplot_kernel/tree/master/examples)|MetaKernel|
| Go >= 1.21 |[GoNB](https://github.com/janpfeifer/gonb)| Jupyter >= 5 | | [Tutorial](https://github.com/janpfeifer/gonb/blob/e15ac2e8e3fe/examples/tutorial.ipynb) [Binder Live Demo](https://mybinder.org/v2/gh/janpfeifer/gonb/HEAD?labpath=examples%2Ftutorial.ipynb)| |
|Go >= 1.4|[IGo](https://github.com/takluyver/igo)||||Unmaintained, use gophernotes|
|Go >= 1.6|[gopherlab](https://github.com/fabian-z/gopherlab)|Jupyter 4.1, JupyterLab|ZeroMQ (4.x)|[examples](https://github.com/fabian-z/gopherlab/tree/master/examples)|Deprecated, use gophernotes|
|Go >= 1.8|[lgo](https://github.com/yunabe/lgo)|Jupyter >= 4, JupyterLab|ZeroMQ (4.x)|[Example](http://nbviewer.jupyter.org/github/yunabe/lgo/blob/master/examples/basics.ipynb)|[Docker image](https://hub.docker.com/r/yunabe/lgo/)|
|Go >= 1.9|[Gophernotes](https://github.com/gopherdata/gophernotes)|Jupyter 4, JupyterLab, nteract|ZeroMQ 4.x.x|[examples](https://github.com/gopherdata/gophernotes/tree/master/examples)|[docker image](https://hub.docker.com/r/dwhitena/gophernotes/)|
| GrADS >= 2.0 |[GrADS kernel](https://github.com/ykatsu111/jupyter-grads-kernel)|   |  |  |  |
|Guile 2.0.12|[Guile](https://github.com/jerry40/guile-kernel)|Jupyter 5.2|[guile-json](https://github.com/aconchillo/guile-json), openssl|||
|[HiveQL](https://en.wikipedia.org/wiki/Apache_Hive)|[HiveQL Kernel](https://github.com/EDS-APHP/HiveQLKernel)|Jupyter >= 5| [pyhive](https://github.com/dropbox/PyHive) | | Display HiveQL queries in HTML tables |
|Home Assistant|[PyScript](https://github.com/craigbarratt/hass-pyscript-jupyter/)|Jupyter|Home Assistant|[Tutorial](https://github.com/craigbarratt/hass-pyscript-jupyter/blob/master/pyscript_tutorial.ipynb)||
|Hy|[Hy Kernel](https://github.com/bollwyvl/hy_kernel/)|Jupyter||[Tutorial](http://nbviewer.ipython.org/github/bollwyvl/hy_kernel/blob/master/notebooks/Tutorial.ipynb)|treats Hy as Python pre-processor|
|Hy|[Calysto Hy](https://github.com/Calysto/calysto_hy)|Jupyter||[Tutorial](https://github.com/Calysto/calysto_hy/blob/master/notebooks/Tutorial.ipynb)| based on MetaKernel (magics, shell, parallel, etc.)|
|IDL|[idl_kernel](https://github.com/lstagner/idl_kernel)||||IDL seem to have a [built-in kernel](http://www.exelisvis.com/docs/idl_kernel.html) starting with version 8.5|
| Intel Assembly Language | [Emu86 Kernel](https://github.com/gcallah/Emu86/tree/master/kernels) | Jupyter |  | [Introduction to Intel Assembly Language Tutorial](https://github.com/gcallah/Emu86/blob/master/kernels/Introduction%20to%20Assembly%20Language%20Tutorial.ipynb) | |
|Io.js|[jove](https://www.npmjs.com/package/jove)|||||
|J 805-807 (J901beta)|[J](https://github.com/martin-saurer/jkernel)|Jupyter Notebook/Lab||[Examples](https://github.com/martin-saurer/jkernel)||
| Java & [Rascal](https://rascal-mpl.org) |[Bacatá](https://github.com/cwi-swat/bacata)| Jupyter  | ZeroMQ & Rascal | [Example](https://github.com/maveme/rascal-notebooks-examples) | A Jupyter kernel generator for domain-specific languages. |
|Java 11+, [Groovy](https://groovy-lang.org/), [Javascript](https://www.oracle.com/technical-resources/articles/java/jf14-nashorn.html), [Kotlin](https://kotlinlang.org/), [Scala](https://www.scala-lang.org/), [Apache Spark](http://spark.apache.org/), and more|[Ganymede](https://github.com/allen-ball/ganymede)|Jupyter >= 4.0|[JShell](https://docs.oracle.com/en/java/javase/11/docs/api/jdk.jshell/jdk/jshell/JShell.html?is-external=true), [Apache Maven Resolver](https://maven.apache.org/resolver/index.html)|[Examples](https://github.com/allen-ball/ganymede-notebooks)|
|Java 9|[IJava](https://github.com/SpencerPark/IJava)|Jupyter|Java **JDK** >= 9|[Binder online demo](https://mybinder.org/v2/gh/SpencerPark/ijava-binder/master)|Based on the new JShell tool|
| [JavaScript, Ruby, Python, R, and more](https://www.graalvm.org/latest/reference-manual/polyglot-programming/) |[IPolyglot](https://github.com/hpi-swa/ipolyglot)| Jupyter | [GraalVM](https://www.graalvm.org/) | [Example Polyglot Notebook](https://github.com/hpi-swa/ipolyglot/blob/master/demo/polyglot-notebook.ipynb) | [Dockerfile](https://github.com/hpi-swa/ipolyglot/blob/master/Dockerfile) |
|Julia >= 0.3|[IJulia](https://github.com/JuliaLang/IJulia.jl)|||||
|Jython 2.7|[IJython](https://github.com/suvarchal/IJython)|||||
|Jython>=2.7.0|[Jython](https://github.com/fiber-space/jupyter-kernel-jsr223)|Jupyter>=4.0|Java>=7||Java based JSR223 compliant||
|Kotlin|[kotlin-jupyter](https://github.com/Kotlin/kotlin-jupyter)|Jupyter|Java >= 8|[Samples](https://mybinder.org/v2/gh/kotlin/kotlin-jupyter/master?filepath=samples)||
|Livescript >= 1.5|[jp-LiveScript](https://github.com/p2edwards/jp-livescript)||||Based on IJavascript and jpCoffeescript|
|Lua|[Lua Kernel](https://github.com/neomantra/lua_ipython_kernel)|||||
|Lua|[IPyLua](https://github.com/pakozm/IPyLua)||||Fork of *Lua Kernel*|
|Lua|[ILua](https://github.com/guysv/ilua)|||||
|Lua|[Lua (used in Splash)](https://github.com/scrapinghub/splash/tree/master/splash/kernel)|||||
|Mac Os X|[Pharo Smalltalk](https://github.com/jmari/JupyterTalk)|IPython >= 3||[Binder demo](https://mybinder.org/v2/gh/jmari/JupyterTalk.git/master?filepath=Tutorial1_BasicStatistics.ipynb)|Paro 64 bits native kernel, zeromq|
|Mathics|[IMathics](http://nbviewer.ipython.org/gist/sn6uv/8381447)|||||
|MATLAB >= 2016b|[imatlab](https://github.com/imatlab/imatlab)|ipykernel >= 4.1||||
|Matlab|[MATLAB Kernel](https://github.com/calysto/matlab_kernel)|Jupyter|pymatbridge|[Example](http://nbviewer.ipython.org/github/Calysto/matlab_kernel/blob/master/matlab_kernel.ipynb)|MetaKernel|
|Matlab|[MKernel](https://github.com/allefeld/mkernel)|Jupyter|ipykernel, matlabengine, wurlitzer|[Example](https://github.com/allefeld/mkernel/blob/main/examples/mkernel_test_2.ipynb)|Optimized for both Jupyter and [Quarto](https://quarto.org/)|
|Maxima|[Maxima-Jupyter](https://github.com/robert-dodier/maxima-jupyter)|Jupyter|Quicklisp|||
|MIPS32 Assembly Language|[MIPS Jupyter Kernel](https://github.com/epalmese/MIPS-jupyter-kernel)|Jupyter|Python3, [SPIM](http://spimsimulator.sourceforge.net/)|[Example](https://github.com/epalmese/MIPS-jupyter-kernel/blob/master/kernel/test.ipynb)|Driven by Python3 and Pexpect|
|MIT Scheme 9.2|[mit-scheme-kernel](https://github.com/joeltg/mit-scheme-kernel)|Jupyter 4.0||||
|Mochi|[Mochi Kernel](https://github.com/pya/mochi-kernel)|||||
|MongoDB|[iMongo](https://github.com/gusutabopb/imongo)|||||
|Natural languages|[iTTS](https://github.com/KOLANICH/iTTS)||[speech-dispatcher](https://github.com/brailcom/speechd)|[Example](https://github.com/KOLANICH/iTTS/blob/master/tutorial.ipynb)|Currently cannot output sound into files or blobs because of limitations of speech-dispatcher|
|NodeJS, Babel, Clojurescript|[jupyter-nodejs](https://github.com/notablemind/jupyter-nodejs)|Jupyter, iPython 3.x||[Examples](http://nbviewer.jupyter.org/gist/jaredly/404a36306fdee6a1737a)|
| NodeJs 12 |[nelu-kernelu](https://github.com/3Nigma/nelu-kernelu)| Jupyter  | [NodeJs 12.3+](https://nodejs.org/dist/latest-v12.x/docs/api/) | [Examples](https://github.com/3Nigma/nelu-kernelu/blob/master/nbs/nk-features.ipynb) | An advanced NodeJs Jupyter kernel supporting comms and displays among other things. |
|NodeJs >= 0.10|[IJavascript](https://github.com/n-riesco/ijavascript)|||||
|OCaml >= 4.01|[IOCaml](https://github.com/andrewray/iocaml)|IPython >= 1.1|opam|||
|OCaml >= 4.02|[OCaml-Jupyter](https://github.com/akabe/ocaml-jupyter)|Jupyter >= 4.0|opam|[Example](https://github.com/akabe/ocaml-jupyter/blob/master/notebooks/introduction.ipynb)|[Docker image](https://github.com/akabe/docker-ocaml-jupyter-datascience)|
|Octave|[IOctave](https://github.com/calysto/octave_kernel)|Jupyter||[Example](http://nbviewer.jupyter.org/github/Calysto/octave_kernel/blob/master/octave_kernel.ipynb)|MetaKernel|
|Octave|[xeus-octave](https://github.com/jupyter-xeus/xeus-octave)|Jupyter||[Example](https://mybinder.org/v2/gh/jupyter-xeus/xeus-octave/stable?urlpath=/lab/tree/notebooks/xeus-octave.ipynb)| |
|PARI/GP >= 2.9|[pari_jupyter](https://github.com/jdemeyer/pari_jupyter)|Jupyter 4||||
|PHP >= 5.4|[IPHP](https://github.com/dawehner/ipython-php)|IPython >= 2|composer||DEPRECATED, use Jupyter-PHP|
|PHP >= 7.0.0|[Jupyter-PHP](https://github.com/Litipk/Jupyter-PHP)|Jupyter 4.0|composer, php-zmq|||
|Perl 5|[IPerl](https://metacpan.org/release/Devel-IPerl)|||||
|Perl 6|[IPerl6](https://github.com/timo/iperl6kernel)|||||
|Perl 6.C|[Jupyter-Perl6](https://github.com/bduggan/p6-jupyter-kernel)|Jupyter|[Rakudo Perl 6](http://rakudo.org/how-to-get-rakudo/)|||
|Perl 6.c|[Perl6](https://github.com/gabrielash/p6-net-jupyter)|Jupyter >= 4|zeromq 4|||
|Pike >= 7.8|[Pike](https://github.com/kevinior/jupyter-pike-kernel)|IPython >= 3|||Wrapper, Based on Bash Kernel|
|PostScript|[IPostScript](https://github.com/kts/IPostScript)||`gs` (ghostscript)|||
|Powershell|[PowerShell](https://github.com/vors/jupyter-powershell)|IPython >= 3|||Wrapper, Based on Bash Kernel|
|Processing.js >= 2|[Calysto Processing](https://github.com/Calysto/calysto_processing)||||MetaKernel|
|Prolog|[Prolog](https://github.com/Calysto/calysto_prolog)||||MetaKernel|
|Purescript|[IPurescript](https://github.com/Eoksni/ipurescript)|||||
|Pyspark (Python 2 & 3), Spark (Scala), SparkR (R)|[sparkmagic](https://github.com/jupyter-incubator/sparkmagic)|Jupyter >=4.0|[Livy](https://github.com/cloudera/livy)|[Notebooks](https://github.com/jupyter-incubator/sparkmagic/tree/master/examples), [Docker Images](https://github.com/jupyter-incubator/sparkmagic#docker)|This kernels are implemented via the magics machinery of the ipython kernel to use Spark via Livy|
|Python|[MetaKernel Python](https://github.com/Calysto/metakernel/tree/master/metakernel_python)||||MetaKernel|
|Python 2.7|[AIML chatbot](https://github.com/paulovn/aiml-chatbot-kernel)|Jupyter 4|[pyAIML](https://github.com/creatorrr/pyAIML)|[Examples](http://nbviewer.jupyter.org/github/paulovn/aiml-chatbot-kernel/tree/master/examples/)||
|Python 2.7 or >=3.4|[SPARQL](https://github.com/paulovn/sparql-kernel)|Jupyter 4|[rdflib](https://github.com/RDFLib/rdflib), [SPARQLWrapper](https://rdflib.github.io/sparqlwrapper/)|[Examples](http://nbviewer.jupyter.org/github/paulovn/sparql-kernel/tree/master/examples/)| Optional [GraphViz](http://www.graphviz.org/) dependency|
|Python 2.7, >= 3.3|[IPyKernel](https://github.com/ipython/ipykernel)|Jupyter 4.0|pyzmq|||
|Python >= 3.3|[sas_kernel](https://github.com/sassoftware/sas_kernel)|Jupyter 4.0|SAS 9.4 or higher|||
|Python >= 3.5, scala >= 2.11|[spylon-kernel](https://github.com/maxpoint/spylon-kernel)|ipykernel >=4.5|Apache Spark >=2.0|[Example](https://github.com/maxpoint/spylon-kernel/blob/master/examples/basic_example.ipynb)|MetaKernel|
|Python >=3.4|[SoS](https://github.com/vatlab/SOS)|Jupyter 4|Support kernels for bash, python2/3, matlab/octabe, javascript, julia, R, Stata, SAS, and more|[Examples](http://vatlab.github.io/SOS/#documentation)|Workflow system, Multi-Kernel support|
|Python>=3.7.5, Groovy>3|[Micronaut](https://github.com/stainlessai/micronaut-jupyter)||[Micronaut](https://micronaut.io/)|https://github.com/stainlessai/micronaut-jupyter/blob/master/examples/basic-service/notebooks/use-library.ipynb|Compatible with [BeakerX](http://beakerx.com)|
|Python|[Jupyter on Golem](https://github.com/golemfactory/golem-kernel-python/tree/master)|JupyterLab >= 4.0.2 |[yagna](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development#running-the-yagna-daemon) >=0.12.2, jupyter >= 1.0.0, pandas >=2.0.2, tensorflow-cpu >= 2.12.0, matplotlib >= 3.7.1|[Examples](https://github.com/golemfactory/golem-kernel-python/tree/master/examples)| Python kernel, which enables JupyterLab to run Python Notebooks on decentralized [Golem Network](https://www.golem.network/)|
|Q|[KDB+/Q Kernel (IKdbQ)](https://github.com/jvictorchen/IKdbQ)|IPython >= 3.1|qzmq, qcrypt|||
|Q|[KDB+/Q Kernel (KdbQ Kernel)](https://github.com/newtux/KdbQ_kernel)|Jupyter||||
|Q|[PyQ Kernel](https://pypi.org/project/pyq-kernel)|Jupyter||[Python for kdb+](https://pyq.enlnt.com/pyq-2017)||
|Q#|[IQSharp](https://github.com/microsoft/iqsharp)|Jupyter 4||[QuantumKatas](https://github.com/microsoft/QuantumKatas)|
|R 3.2|[IRKernel](http://irkernel.github.io/)|IPython 3.0|rzmq|||
|R >= 4.0|[RKernel](https://github.com/melff/RKernel)|Jupyter|R packages: tools, utils, pbdZMQ (>= 0.2-1), jsonlite (>= 0.9.6), uuid, digest, R6, svglite, repr, htmltools, htmlwidgets, base64enc; Python package: jupyter-server-proxy | [Example Notebooks](https://tmphub.elff.eu/) | A kernel for R, a language and environment for statistical computing and graphics. This kernel relies on the the more recent R6 class system and fully supports interactive widgets based on [ipywidgets version 8](https://ipywidgets.readthedocs.io/)|
|Racket >= 6.10|[IRacket](https://github.com/rmculpepper/iracket)|IPython >= 3|Racket, ZeroMQ|[Example](https://github.com/rmculpepper/iracket/blob/master/examples/getting-started.ipynb)||
|Raku|[Raku-Jupyter-Kernel](https://github.com/bduggan/raku-jupyter-kernel)|Jupyter|[Raku](http://raku.org)|[examples](https://github.com/bduggan/raku-jupyter-kernel/tree/master/eg)||
|Redis|[Redis Kernel](https://github.com/supercoderz/redis_kernel)|IPython >= 3|||Wrapper|
|Ruby >= 2.3|[IRuby](https://github.com/SciRuby/iruby)|||||
|Rust >= 1.29.2|[EvCxR Jupyter Kernel](https://github.com/google/evcxr/tree/master/evcxr_jupyter)|Jupyter 4, JupyterLab, nteract|ZeroMQ 4.x.x|[Examples](https://github.com/google/evcxr/tree/master/evcxr_jupyter/samples), [Binder online demo](https://mybinder.org/v2/gh/google/evcxr/main?filepath=evcxr_jupyter%2Fsamples%2Fevcxr_jupyter_tour.ipynb)| |
|SQL|[Teradata SQL kernel and extensions](https://teradata.github.io/jupyterextensions/)|JupyterLab >= 3.0|  |[Example Notebooks](https://github.com/Teradata/jupyterextensions/tree/master/notebooks) | | |
|SQL|[mariadb_kernel](https://github.com/MariaDB/mariadb_kernel)|Jupyter Notebook/Lab|[Internal Dependencies](https://github.com/MariaDB/mariadb_kernel/blob/master/requirements.txt), [MariaDB Server](https://mariadb.org/download/)|[Binder notebook](https://mybinder.org/v2/gh/MariaDB/mariadb_kernel.git/master?filepath=binder%2Ftry_it_out.ipynb)|A Jupyter kernel for the MariaDB Open Source database|
|SWI-Prolog|[SWI-Prolog](https://github.com/madmax2012/SWI-Prolog-Kernel)|Jupyter >=4.0 |||https://hub.docker.com/r/jm1337/jupyter-prolog-notebook/|
|Sbt >= 1.0.0|[Isbt](https://github.com/ktr-skmt/Isbt)|Jupyter 4.3.0|sbt|[example](https://github.com/ktr-skmt/Isbt/blob/master/examples/isbt_examples.ipynb)||
|Scala|[IScala](https://github.com/mattpap/IScala)|||||
|Scala, Python, R|[Apache Toree (formerly Spark Kernel)](https://github.com/apache/incubator-toree)|Jupyter|Spark >= 1.5|[Example](https://github.com/apache/incubator-toree/blob/master/etc/examples/notebooks/magic-tutorial.ipynb)||
|Scala>=2.10|[almond (old name: Jupyter-scala)](https://github.com/almond-sh/almond)|IPython>=3.0||[examples](https://github.com/almond-sh/examples)| [Docs](https://almond.sh)|
|Scheme|[Calysto Scheme](https://github.com/Calysto/calysto_scheme)|||[Reference Guide](https://github.com/Calysto/calysto_scheme/blob/master/notebooks/Reference%20Guide%20for%20Calysto%20Scheme.ipynb)|MetaKernel|
|Scilab|[IScilab](https://github.com/calysto/scilab_kernel)|Jupyter||[Example](http://nbviewer.jupyter.org/github/Calysto/scilab_kernel/blob/master/scilab_kernel.ipynb)|MetaKernel|
|SetlX|[ISetlX](https://github.com/1b15/iSetlX)|Jupyter||[Example](https://github.com/1b15/iSetlX/blob/master/example_notebooks/fibonacci.ipynb)||
|Singular 4.1.0|[jupyter_kernel_singular](https://github.com/sebasguts/jupyter_kernel_singular)|Jupyter||[Demo](https://github.com/sebasguts/jupyter-singular/blob/master/Demo.ipynb)|Optional PySingular for better performance, surf for images, [details](https://www.singular.uni-kl.de/index.php/graphical-interface.html)|
|Skulpt Python|[Skulpt Python Kernel](https://github.com/Calysto/skulpt_python)|||[Examples](http://jupyter.cs.brynmawr.edu/hub/dblank/public/Examples/Skulpt%20Python%20Examples.ipynb)|MetaKernel|
|GNU Smalltalk|[GNU Smalltalk Kernel](https://github.com/anlytcs/gst_kernel)|Jupyter|GNU Smalltalk |||
|Stata|[stata_kernel](https://github.com/kylebarron/stata_kernel)|Jupyter >=5|Stata >=14| | Communicates natively with Stata|
|Stata|[iPyStata](https://github.com/TiesdeKok/ipystata)|Jupyter|Stata| [Example Notebook](http://nbviewer.jupyter.org/github/TiesdeKok/ipystata/blob/master/ipystata/Example.ipynb)| Implemented using magics machinery of ipython. |
|Stata >= 17|[pystata-kernel](https://github.com/ticoneva/pystata-kernel)||||Communicates with Stata through the [pystata](https://www.stata.com/python/pystata/) official Python bindings|
|Stata >= 17|[nbstata](https://hugetim.github.io/nbstata/)|Jupyter >= 5.2|[pystata](https://www.stata.com/python/pystata/), [ipydatagrid](https://github.com/bloomberg/ipydatagrid)|[stata_kernel example](https://github.com/hugetim/nbstata/blob/master/manual_test_nbs/stata_kernel%20example.ipynb)||
|[StuPyd](https://github.com/StuPyd/stupyd-lang)|[StuPyd Kernel](https://github.com/StuPyd/demo-kernel)|Jupyter >= 4|Python3, antlr4-python3-runtime >= 4.7.1|[nbviewer demo](https://nbviewer.jupyter.org/github/StuPyd/demo-kernel/blob/master/test.ipynb)||
| [Systemtap](https://sourceware.org/systemtap/) >= 4.9, Python >= 3.10 |[ISystemtap](https://sourceware.org/git/?p=systemtap.git;a=tree;f=interactive-notebook)| ipykernel>=6.15 | NodeJS | [ISystemtap.ipynb](https://sourceware.org/git/?p=systemtap.git;a=blob;f=interactive-notebook/ISystemtap.ipynb) | [Podman image](https://www.quay.io/systemtap/isystemtap) |
| TaQL |[TaQL](https://github.com/tammojan/taql-jupyter) | Jupyter | [python-casacore](https://github.com/casacore/python-casacore) | [TaQL tutorial](http://taql.astron.nl) | |
|Tcl 8.5|[Tcl](https://github.com/rpep/tcl_kernel)|Jupyter|||Based on Bash Kernel|
|Tcl 8.6|[Tcl](https://github.com/mpcjanssen/tcljupyter)|Jupyter||[Binder demo](https://mybinder.org/v2/gh/mpcjanssen/tcljupyter/binder?filepath=examples%2Fexample.ipynb)|Written from scratch with a patched Tcl zmq binding|
|Torch 7 (LuaJIT)|[ITorch](https://github.com/facebook/iTorch)|IPython >= 2.2 and <= 5.x ||||
|Typescript 3.7.2, JavaScript ESNext|[tslab](https://github.com/yunabe/tslab)||Node.js|[Example notebooks](https://github.com/yunabe/tslab/blob/master/README.md#example-notebooks)|[Jupyter kernel for JavaScript and TypeScript](https://github.com/yunabe/tslab) - [npm](https://www.npmjs.com/package/tslab)|
|Typescript >= 2.0|[ITypeScript](https://github.com/nearbydelta/itypescript)||Node.js >= 0.10.0|||
| V1.1 |[Common Workflow Language (CWL) Kernel](https://github.com/giannisdoukas/CWLJNIKernel)|  |  | [examples directory](https://github.com/giannisdoukas/CWLJNIKernel/blob/master/examples/) |  |
|VPython|[IVisual](https://pypi.python.org/pypi/IVisual)|||[Ball-in-Box](http://nbviewer.jupyter.org/url/dl.dropboxusercontent.com/u/5095342/visual/Ball-in-Box.ipynb)||
|[Vim script](https://github.com/vim/vim/)|[A Jupyter kernel for Vim script](https://github.com/mattn/vim_kernel)|Jupyter||||
| Whitespace 0.1 |[Whitenote](https://github.com/makiuchi-d/whitenote)| Jupyter>=5 | Go>=1.19 | [example.ipynb](https://github.com/makiuchi-d/whitenote/blob/main/example.ipynb) | [Docker image](https://hub.docker.com/r/makiuchid/whitenote) |
| Wolfram Mathematica |[Wolfram Language for Jupyter](https://github.com/WolframResearch/WolframLanguageForJupyter)|   | Wolfram Engine, i.e., a Wolfram Desktop or Mathematica installation; `wolframscript` is optional but recommended |  |A Jupyter kernel for [the Wolfram Language](https://www.wolfram.com/language) (Mathematica).|
|Wolfram Mathematica|[IWolfram](https://github.com/mmatera/iwolfram)|| Wolfram Mathematica(R), Metakernel||MetaKernel|
|Xonsh|[Xonsh](https://github.com/calysto/xonsh_kernel)|||[Example](http://nbviewer.ipython.org/github/Calysto/xonsh_kernel/blob/master/xonsh_kernel.ipynb)|MetaKernel|
|YACAS|[Yacas](https://github.com/grzegorzmazur/yacas_kernel)|||||
|Zsh >= 5.3|[Z shell](https://github.com/dan-oak/zsh-jupyter-kernel)|IPython >= 3||[Example](https://github.com/dan-oak/zsh-jupyter-kernel/blob/master/example.ipynb)|

</div>

Many kernels are available for installation on [PyPI](https://pypi.python.org/pypi?:action=browse&c=586).

## Additional Related Projects

<!-- *   [Jove](https://github.com/jove-sh) - notebook interface in Java; provides Spark and Scala kernels  -->
*   [Brython Magics](https://github.com/kikocorreoso/brythonmagic) - A magic trick to allow you to use Brython code (client-side) in other notebooks  
*   [pixiedust_node](https://github.com/ibm-watson-data-lab/pixiedust_node) - PixieDust extension that enable a Jupyter Notebook user to invoke Node.js commands.

## Creating new Jupyter kernels

[Making kernels for Jupyter](http://jupyter-client.readthedocs.org/en/latest/kernels.html) in the documentation.

[Simple example kernel](https://github.com/dsblank/simple_kernel)

[IHaskell creator blog
post](http://andrew.gibiansky.com/blog/ipython/ipython-kernels/)

[Testing kernels against message specification (work in progress)](https://github.com/ipython/ipython/wiki/Dev:-Testing-kernels-against-message-specification)

[Tool to test a kernel against specification (work in progress)](https://github.com/jupyter/jupyter_kernel_test)
