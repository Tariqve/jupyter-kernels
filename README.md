
## A curated list of Jupyter kernels 

Kernel Zero is [IPython](https://ipython.org), which you can get through [ipykernel](https://pypi.python.org/pypi/ipykernel), and is still a dependency of [jupyter](https://jupyter.org). The IPython kernel can be thought of as a reference implementation, as CPython is for Python.

Here is a list of available Jupyter kernels. If you are writing your own kernel, feel free to add it to the table!

<!-- div style="display: block; min-width: 100%; overflow: visible; font-size: 7pt" -->

| Language(s) | Name | Jupyter Version | Supports | Examples | Notes |
|---|---|---|---|---|---|
|  | [LFortran](https://lfortran.org/) |  |  |  | Main repository at [GitHub](https://github.com/lfortran/lfortran) |
|  | [JupyterQ (KX Official Kernel)](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) | Jupyter |  | [Notebook Examples](https://github.com/KxSystems/jupyterq/blob/master/examples/q_widgets.ipynb) |  |
| Dockerfile | [dockerfile-kernel](https://github.com/ssciwr/dockerfile-kernel) | JupyterLab |  |  | User should be in the docker group. |
| Dot/graphviz | [jupyter-dot-kernel](https://github.com/laixintao/jupyter-dot-kernel) | Jupyter >= 4.0 |  |  |  |
| Elixir | [IElixir](https://github.com/pprzetacznik/IElixir) | Jupyter >= 4.0 |  | [example](https://github.com/pprzetacznik/IElixir/blob/master/resources/example.ipynb) <br>[Boyle example](https://github.com/pprzetacznik/IElixir/blob/master/resources/boyle%20example.ipynb) <br>[example usage with Matrex library](https://github.com/pprzetacznik/IElixir/blob/master/resources/boyle%20example%20-%20matrex%20installation%20and%20usage.ipynb) | [IElixir Docker image](https://hub.docker.com/r/pprzetacznik/ielixir/), [IElixir Notebook in Docker](https://mattvonrocketstein.github.io/heredoc/ielixir-notebook-in-docker.html#sf-ielixir-notebook-in-docker-2-back) |
| Emacs Lisp | [ielisp](https://github.com/shwina/ielisp) | Jupyter |  |  |  |
| Erlang | [IErlang](https://github.com/robbielynch/ierlang) | IPython 2.3 |  |  |  |
| Erlang<br>Elixir<br>LFE | [ierl](https://github.com/filmor/ierl) | Jupyter >= 4.0 |  |  |  |
| ESP8266/ESP32 | [MicroPython](https://github.com/goatchurchprime/jupyter_micropython_kernel/) | Jupyter |  | [developer notebooks](https://github.com/goatchurchprime/jupyter_micropython_developer_notebooks) | relies on the micro-controller's paste-mode |
| F# | [IFSharp](https://github.com/fsprojects/IfSharp) | Jupyter 4 |  | [Features](https://github.com/fsprojects/IfSharp/blob/master/FSharp_Jupyter_Notebooks.ipynb) |  |
| Forth | [IForth](https://github.com/jdfreder/iforth) | IPython >= 3 |  |  |  |
| Forth | [peforth](https://github.com/hcchengithub/peforth) | IPython 6/Jupyter 5 |  | [Example](https://github.com/hcchengithub/peforth/wiki) | python debugger in FORTH syntax |
| Fortran | [Coarray-Fortran](https://github.com/sourceryinstitute/jupyter-CAF-kernel) | Jupyter 4.0 |  | [Demo](https://nbviewer.jupyter.org/github/sourceryinstitute/jupyter-CAF-kernel/blob/master/index.ipynb), [Binder demo](https://beta.mybinder.org/v2/gh/sourceryinstitute/jupyter-CAF-kernel/master?filepath=index.ipynb) | [Docker image](https://hub.docker.com/r/sourceryinstitute/jupyter-caf-kernel/) |
| Galileo | [iGalileo](https://github.com/cascala/igalileo) | Jupyter >= 4, JupyterLab |  |  | [Docker image](https://hub.docker.com/r/cascala/igalileo/) |
| GAP | [GAP Kernel](https://gap-packages.github.io/JupyterKernel/) | Jupyter |  | [Binder demo](https://github.com/gap-system/try-gap-in-jupyter) | A Jupyter kernel for the computational algebra system [GAP](https://www.gap-system.org/). |
| Ghc | [IHaskell](https://github.com/gibiansky/IHaskell) |  |  |  | [Demo](https://begriffs.com/posts/2016-01-20-ihaskell-notebook.html) |
| GNU Smalltalk | [GNU Smalltalk Kernel](https://github.com/anlytcs/gst_kernel) | Jupyter |  |  |  |
| Gnuplot | [Gnuplot Kernel](https://github.com/has2k1/gnuplot_kernel) |  | Linux | [Example](https://github.com/has2k1/gnuplot_kernel/tree/master/examples) | MetaKernel |
| Go | [IGo](https://github.com/takluyver/igo) |  |  |  | Unmaintained, use gophernotes |
| Go | [gopherlab](https://github.com/fabian-z/gopherlab) | Jupyter 4.1, JupyterLab |  | [examples](https://github.com/fabian-z/gopherlab/tree/master/examples) | Deprecated, use gophernotes |
| Go | [lgo](https://github.com/yunabe/lgo) | Jupyter >= 4, JupyterLab |  | [Example](http://nbviewer.jupyter.org/github/yunabe/lgo/blob/master/examples/basics.ipynb) | [Docker image](https://hub.docker.com/r/yunabe/lgo/) |
| Go | [Gophernotes](https://github.com/gopherdata/gophernotes) | Jupyter 4, JupyterLab, nteract |  | [examples](https://github.com/gopherdata/gophernotes/tree/master/examples) | [docker image](https://hub.docker.com/r/dwhitena/gophernotes/) |
| Go | [GoNB](https://github.com/janpfeifer/gonb) | Jupyter >= 5 |  | [Tutorial](https://github.com/janpfeifer/gonb/blob/e15ac2e8e3fe/examples/tutorial.ipynb) <br>[Binder Live Demo](https://mybinder.org/v2/gh/janpfeifer/gonb/HEAD?labpath=examples%2Ftutorial.ipynb) |  |
| GrADS | [GrADS kernel](https://github.com/ykatsu111/jupyter-grads-kernel) |  |  |  |  |
| Guile | [Guile](https://github.com/jerry40/guile-kernel) | Jupyter 5.2 |  |  |  |
| HiveQL | [HiveQL Kernel](https://github.com/EDS-APHP/HiveQLKernel) | Jupyter >= 5 |  |  | Display HiveQL queries in HTML tables |
| Home Assistant | [PyScript](https://github.com/craigbarratt/hass-pyscript-jupyter/) | Jupyter |  | [Tutorial](https://github.com/craigbarratt/hass-pyscript-jupyter/blob/master/pyscript_tutorial.ipynb) |  |
| Hy | [Hy Kernel](https://github.com/bollwyvl/hy_kernel/) | Jupyter |  | [Tutorial](http://nbviewer.ipython.org/github/bollwyvl/hy_kernel/blob/master/notebooks/Tutorial.ipynb) | treats Hy as Python pre-processor |
| Hy | [Calysto Hy](https://github.com/Calysto/calysto_hy) | Jupyter |  | [Tutorial](https://github.com/Calysto/calysto_hy/blob/master/notebooks/Tutorial.ipynb) | based on MetaKernel (magics, shell, parallel, etc.) |
| IDL | [idl_kernel](https://github.com/lstagner/idl_kernel) |  |  |  | IDL seem to have a [built-in kernel](http://www.exelisvis.com/docs/idl_kernel.html) starting with version 8.5 |
| Intel Assembly Language | [Emu86 Kernel](https://github.com/gcallah/Emu86/tree/master/kernels) | Jupyter |  | [Tutorial](https://github.com/gcallah/Emu86/blob/master/kernels/Introduction%20to%20Assembly%20Language%20Tutorial.ipynb) |  |
| Io.js | [jove](https://www.npmjs.com/package/jove) |  |  |  |  |
| J | [J](https://github.com/martin-saurer/jkernel) | Jupyter Notebook/Lab |  | [Examples](https://github.com/martin-saurer/jkernel) |  |
| Java & Rascal | [Bacatá](https://github.com/cwi-swat/bacata) | Jupyter |  | [Example](https://github.com/maveme/rascal-notebooks-examples) | A Jupyter kernel generator for domain-specific languages. |
| Java | [IJava](https://github.com/SpencerPark/IJava) | Jupyter |  | [Binder online demo](https://mybinder.org/v2/gh/SpencerPark/ijava-binder/master) | Based on the new JShell tool |
| Java<br>Groovy<br>Javascript<br>Kotlin<br>Scala<br>Apache Spark<br>and more | [Ganymede](https://github.com/allen-ball/ganymede) | Jupyter >= 4.0 |  | [Examples](https://github.com/allen-ball/ganymede-notebooks) |  |
| JavaScript, Ruby, Python, R, and more | [IPolyglot](https://github.com/hpi-swa/ipolyglot) | Jupyter |  | [Example Polyglot Notebook](https://github.com/hpi-swa/ipolyglot/blob/master/demo/polyglot-notebook.ipynb) | [Dockerfile](https://github.com/hpi-swa/ipolyglot/blob/master/Dockerfile) |
| Julia | [IJulia](https://github.com/JuliaLang/IJulia.jl) |  |  |  |  |
| Jython | [IJython](https://github.com/suvarchal/IJython) |  |  |  |  |
| Jython | [Jython](https://github.com/fiber-space/jupyter-kernel-jsr223) | Jupyter>=4.0 |  |  | Java based JSR223 compliant |
| Kotlin | [kotlin-jupyter](https://github.com/Kotlin/kotlin-jupyter) | Jupyter |  | [Samples](https://mybinder.org/v2/gh/kotlin/kotlin-jupyter/master?filepath=samples) |  |
| Livescript | [jp-LiveScript](https://github.com/p2edwards/jp-livescript) |  |  |  | Based on IJavascript and jpCoffeescript |
| Lua | [Lua Kernel](https://github.com/neomantra/lua_ipython_kernel) |  |  |  |  |
| Lua | [IPyLua](https://github.com/pakozm/IPyLua) |  |  |  | Fork of *Lua Kernel* |
| Lua | [ILua](https://github.com/guysv/ilua) |  |  |  |  |
| Lua | [Lua (used in Splash)](https://github.com/scrapinghub/splash/tree/master/splash/kernel) |  |  |  |  |
| Mac Os X | [Pharo Smalltalk](https://github.com/jmari/JupyterTalk) | IPython >= 3 |  | [Binder demo](https://mybinder.org/v2/gh/jmari/JupyterTalk.git/master?filepath=Tutorial1_BasicStatistics.ipynb) | Paro 64 bits native kernel, zeromq |
| Mathics | [IMathics](http://nbviewer.ipython.org/gist/sn6uv/8381447) |  |  |  |  |
| Matlab | [MATLAB Kernel](https://github.com/calysto/matlab_kernel) | Jupyter |  | [Example](http://nbviewer.ipython.org/github/Calysto/matlab_kernel/blob/master/matlab_kernel.ipynb) | MetaKernel |
| Matlab | [MKernel](https://github.com/allefeld/mkernel) | Jupyter |  | [Example](https://github.com/allefeld/mkernel/blob/main/examples/mkernel_test_2.ipynb) | Optimized for both Jupyter and [Quarto](https://quarto.org/) |
| MATLAB | [imatlab](https://github.com/imatlab/imatlab) | ipykernel >= 4.1 |  |  |  |
| Maxima | [Maxima-Jupyter](https://github.com/robert-dodier/maxima-jupyter) | Jupyter |  |  |  |
| MIPS32 Assembly Language | [MIPS Jupyter Kernel](https://github.com/epalmese/MIPS-jupyter-kernel) | Jupyter |  | [Example](https://github.com/epalmese/MIPS-jupyter-kernel/blob/master/kernel/test.ipynb) | Driven by Python3 and Pexpect |
| MIT Scheme | [mit-scheme-kernel](https://github.com/joeltg/mit-scheme-kernel) | Jupyter 4.0 |  |  |  |
| Mochi | [Mochi Kernel](https://github.com/pya/mochi-kernel) |  |  |  |  |
| MongoDB | [iMongo](https://github.com/gusutabopb/imongo) |  |  |  |  |
| Natural languages | [iTTS](https://github.com/KOLANICH/iTTS) |  |  | [Example](https://github.com/KOLANICH/iTTS/blob/master/tutorial.ipynb) | Currently cannot output sound into files or blobs because of limitations of speech-dispatcher |
| NodeJS<br>Babel<br>Clojurescript | [jupyter-nodejs](https://github.com/notablemind/jupyter-nodejs) | Jupyter, iPython 3.x |  | [Examples](http://nbviewer.jupyter.org/gist/jaredly/404a36306fdee6a1737a) |  |
| NodeJs | [IJavascript](https://github.com/n-riesco/ijavascript) |  |  |  |  |
| NodeJs | [nelu-kernelu](https://github.com/3Nigma/nelu-kernelu) | Jupyter |  | [Examples](https://github.com/3Nigma/nelu-kernelu/blob/master/nbs/nk-features.ipynb) | An advanced NodeJs Jupyter kernel supporting comms and displays among other things. |
| OCaml | [IOCaml](https://github.com/andrewray/iocaml) | IPython >= 1.1 |  |  |  |
| OCaml | [OCaml-Jupyter](https://github.com/akabe/ocaml-jupyter) | Jupyter >= 4.0 |  | [Example](https://github.com/akabe/ocaml-jupyter/blob/master/notebooks/introduction.ipynb) | [Docker image](https://github.com/akabe/docker-ocaml-jupyter-datascience) |
| Octave | [IOctave](https://github.com/calysto/octave_kernel) | Jupyter |  | [Example](http://nbviewer.ipython.org/github/Calysto/octave_kernel/blob/master/octave_kernel.ipynb) | MetaKernel |
| Octave | [xeus-octave](https://github.com/jupyter-xeus/xeus-octave) | Jupyter |  | [Example](https://mybinder.org/v2/gh/jupyter-xeus/xeus-octave/stable?urlpath=/lab/tree/notebooks/xeus-octave.ipynb) |  |
| PARI/GP | [pari_jupyter](https://github.com/jdemeyer/pari_jupyter) | Jupyter 4 |  |  |  |
| Perl | [IPerl](https://metacpan.org/release/Devel-IPerl) |  |  |  |  |
| Perl | [IPerl6](https://github.com/timo/iperl6kernel) |  |  |  |  |
| Perl | [Jupyter-Perl6](https://github.com/bduggan/p6-jupyter-kernel) | Jupyter |  |  |  |
| Perl | [Perl6](https://github.com/gabrielash/p6-net-jupyter) | Jupyter >= 4 |  |  |  |
| PHP | [IPHP](https://github.com/dawehner/ipython-php) | IPython >= 2 |  |  | DEPRECATED, use Jupyter-PHP |
| PHP | [Jupyter-PHP](https://github.com/Litipk/Jupyter-PHP) | Jupyter 4.0 |  |  |  |
| Pike | [Pike](https://github.com/kevinior/jupyter-pike-kernel) | IPython >= 3 |  |  | Wrapper, Based on Bash Kernel |
| PostScript | [IPostScript](https://github.com/kts/IPostScript) |  |  |  |  |
| Powershell | [PowerShell](https://github.com/vors/jupyter-powershell) | IPython >= 3 |  |  | Wrapper, Based on Bash Kernel |
| Processing.js | [Calysto Processing](https://github.com/Calysto/calysto_processing) |  |  |  | MetaKernel |
| Prolog | [Prolog](https://github.com/Calysto/calysto_prolog) |  |  |  | MetaKernel |
| Purescript | [IPurescript](https://github.com/Eoksni/ipurescript) |  |  |  |  |
| Pyspark (Python 2 & 3)<br>Spark (Scala)<br>SparkR (R) | [sparkmagic](https://github.com/jupyter-incubator/sparkmagic) | Jupyter >=4.0 |  | [Notebooks](https://github.com/jupyter-incubator/sparkmagic/tree/master/examples), [Docker Images](https://github.com/jupyter-incubator/sparkmagic#docker) | This kernels are implemented via the magics machinery of the ipython kernel to use Spark via Livy |
| Python | [MetaKernel Python](https://github.com/Calysto/metakernel/tree/master/metakernel_python) |  |  |  | MetaKernel |
| Python | [Jupyter on Golem](https://github.com/golemfactory/golem-kernel-python/tree/master) | JupyterLab >= 4.0.2 |  | [Examples](https://github.com/golemfactory/golem-kernel-python/tree/master/examples) | Python kernel, which enables JupyterLab to run Python Notebooks on decentralized [Golem Network](https://www.golem.network/) |
| Python | [sas_kernel](https://github.com/sassoftware/sas_kernel) | Jupyter 4.0 |  |  |  |
| Python, scala | [spylon-kernel](https://github.com/maxpoint/spylon-kernel) | ipykernel >=4.5 |  | [Example](https://github.com/maxpoint/spylon-kernel/blob/master/examples/basic_example.ipynb) | MetaKernel |
| Python | [SoS](https://github.com/vatlab/SOS) | Jupyter 4 |  | [Examples](http://vatlab.github.io/SOS/#documentation) | Workflow system, Multi-Kernel support |
| Python | [AIML chatbot](https://github.com/paulovn/aiml-chatbot-kernel) | Jupyter 4 |  | [Examples](http://nbviewer.jupyter.org/github/paulovn/aiml-chatbot-kernel/tree/master/examples/) |  |
| Python | [SPARQL](https://github.com/paulovn/sparql-kernel) | Jupyter 4 |  | [Examples](http://nbviewer.jupyter.org/github/paulovn/sparql-kernel/tree/master/examples/) | Optional [GraphViz](http://www.graphviz.org/) dependency |
| Python | [IPyKernel](https://github.com/ipython/ipykernel) | Jupyter 4.0 |  |  |  |
| Python, Groovy | [Micronaut](https://github.com/stainlessai/micronaut-jupyter) |  |  | [Examples](https://github.com/stainlessai/micronaut-jupyter/blob/master/examples/basic-service/notebooks/use-library.ipynb) | Compatible with [BeakerX](http://beakerx.com) |
| Q | [KDB+/Q Kernel (IKdbQ)](https://github.com/jvictorchen/IKdbQ) | IPython >= 3.1 |  |  |  |
| Q | [KDB+/Q Kernel (KdbQ Kernel)](https://github.com/newtux/KdbQ_kernel) | Jupyter |  |  |  |
| Q | [PyQ Kernel](https://pypi.org/project/pyq-kernel) | Jupyter |  | [Python for kdb+](https://pyq.enlnt.com/pyq-2017) |  |
| Q# | [IQSharp](https://github.com/microsoft/iqsharp) | Jupyter 4 |  | [QuantumKatas](https://github.com/microsoft/QuantumKatas) |  |
| R | [RKernel](https://github.com/melff/RKernel) | Jupyter |  | [Example Notebooks](https://tmphub.elff.eu/) | A kernel for R, a language and environment for statistical computing and graphics. This kernel relies on the the more recent R6 class system and fully supports interactive widgets based on [ipywidgets version 8](https://ipywidgets.readthedocs.io/) |
| R | [IRKernel](http://irkernel.github.io/) | IPython 3.0 |  |  |  |
| Racket | [IRacket](https://github.com/rmculpepper/iracket) | IPython >= 3 |  | [Example](https://github.com/rmculpepper/iracket/blob/master/examples/getting-started.ipynb) |  |
| Raku | [Raku-Jupyter-Kernel](https://github.com/bduggan/raku-jupyter-kernel) | Jupyter |  | [examples](https://github.com/bduggan/raku-jupyter-kernel/tree/master/eg) |  |
| Redis | [Redis Kernel](https://github.com/supercoderz/redis_kernel) | IPython >= 3 |  |  | Wrapper |
| Ruby | [IRuby](https://github.com/SciRuby/iruby) |  |  |  |  |
| Rust | [EvCxR Jupyter Kernel](https://github.com/google/evcxr/tree/master/evcxr_jupyter) | Jupyter 4, JupyterLab, nteract |  | [Examples](https://github.com/google/evcxr/tree/master/evcxr_jupyter/samples), [Binder online demo](https://mybinder.org/v2/gh/google/evcxr/main?filepath=evcxr_jupyter%2Fsamples%2Fevcxr_jupyter_tour.ipynb) |  |
| Sbt | [Isbt](https://github.com/ktr-skmt/Isbt) | Jupyter 4.3.0 |  | [example](https://github.com/ktr-skmt/Isbt/blob/master/examples/isbt_examples.ipynb) |  |
| Scala | [IScala](https://github.com/mattpap/IScala) |  |  |  |  |
| Scala<br>Python<br>R | [Apache Toree (Spark Kernel)](https://github.com/apache/incubator-toree) | Jupyter |  | [Example](https://github.com/apache/incubator-toree/blob/master/etc/examples/notebooks/magic-tutorial.ipynb) |  |
| Scala | [almond (Jupyter-scala)](https://github.com/almond-sh/almond) | IPython>=3.0 |  | [examples](https://github.com/almond-sh/examples) | [Docs](https://almond.sh) |
| Scheme | [Calysto Scheme](https://github.com/Calysto/calysto_scheme) |  |  | [Reference Guide](https://github.com/Calysto/calysto_scheme/blob/master/notebooks/Reference%20Guide%20for%20Calysto%20Scheme.ipynb) | MetaKernel |
| Scilab | [IScilab](https://github.com/calysto/scilab_kernel) | Jupyter |  | [Example](http://nbviewer.jupyter.org/github/Calysto/scilab_kernel/blob/master/scilab_kernel.ipynb) | MetaKernel |
| SetlX | [ISetlX](https://github.com/1b15/iSetlX) | Jupyter |  | [Example](https://github.com/1b15/iSetlX/blob/master/example_notebooks/fibonacci.ipynb) |  |
| Singular | [jupyter_kernel_singular](https://github.com/sebasguts/jupyter_kernel_singular) | Jupyter |  | [Demo](https://github.com/sebasguts/jupyter-singular/blob/master/Demo.ipynb) | Optional PySingular for better performance, surf for images, [details](https://www.singular.uni-kl.de/index.php/graphical-interface.html) |
| Skulpt Python | [Skulpt Python Kernel](https://github.com/Calysto/skulpt_python) |  |  | [Examples](http://jupyter.cs.brynmawr.edu/hub/dblank/public/Examples/Skulpt%20Python%20Examples.ipynb) | MetaKernel |
| SQL | [Teradata SQL kernel and extensions](https://teradata.github.io/jupyterextensions/) | JupyterLab >= 3.0 |  | [Example Notebooks](https://github.com/Teradata/jupyterextensions/tree/master/notebooks) |  |
| SQL | [mariadb_kernel](https://github.com/MariaDB/mariadb_kernel) | Jupyter Notebook/Lab |  | [Binder notebook](https://mybinder.org/v2/gh/MariaDB/mariadb_kernel.git/master?filepath=binder%2Ftry_it_out.ipynb) | A Jupyter kernel for the MariaDB Open Source database |
| Stata | [stata_kernel](https://github.com/kylebarron/stata_kernel) | Jupyter >=5 |  |  | Communicates natively with Stata |
| Stata | [iPyStata](https://github.com/TiesdeKok/ipystata) | Jupyter |  | [Example Notebook](http://nbviewer.jupyter.org/github/TiesdeKok/ipystata/blob/master/ipystata/Example.ipynb) | Implemented using magics machinery of ipython. |
| Stata | [pystata-kernel](https://github.com/ticoneva/pystata-kernel) |  |  |  | Communicates with Stata through the [pystata](https://www.stata.com/python/pystata/) official Python bindings |
| Stata | [nbstata](https://hugetim.github.io/nbstata/) | Jupyter >= 5.2 |  | [stata example](https://github.com/hugetim/nbstata/blob/master/manual_test_nbs/stata_kernel%20example.ipynb) |  |
| [StuPyd](https://github.com/StuPyd/stupyd-lang) | [StuPyd Kernel](https://github.com/StuPyd/demo-kernel) | Jupyter >= 4 |  | [nbviewer demo](https://nbviewer.jupyter.org/github/StuPyd/demo-kernel/blob/master/test.ipynb) |  |
| SWI-Prolog | [SWI-Prolog](https://github.com/madmax2012/SWI-Prolog-Kernel) | Jupyter >=4.0 |  |  | https://hub.docker.com/r/jm1337/jupyter-prolog-notebook/ |
| Systemtap | [ISystemtap](https://sourceware.org/git/?p=systemtap.git;a=tree;f=interactive-notebook) | ipykernel>=6.15 |  | [ISystemtap.ipynb](https://sourceware.org/git/?p=systemtap.git;a=blob;f=interactive-notebook/ISystemtap.ipynb) | [Podman image](https://www.quay.io/systemtap/isystemtap) |
| TaQL | [TaQL](https://github.com/tammojan/taql-jupyter) | Jupyter |  | [TaQL tutorial](http://taql.astron.nl) |  |
| Tcl | [Tcl](https://github.com/rpep/tcl_kernel) | Jupyter |  |  | Based on Bash Kernel |
| Tcl | [Tcl](https://github.com/mpcjanssen/tcljupyter) | Jupyter |  | [Binder demo](https://mybinder.org/v2/gh/mpcjanssen/tcljupyter/binder?filepath=examples%2Fexample.ipynb) | Written from scratch with a patched Tcl zmq binding |
| Torch | [ITorch](https://github.com/facebook/iTorch) | IPython >= 2.2 and <= 5.x |  |  |  |
| TypeScript (Deno) | [Deno](https://docs.deno.com/runtime/reference/cli/jupyter) |  | All | [Examples](https://github.com/rgbkrk/denotebooks) |  |
| Typescript | [ITypeScript](https://github.com/nearbydelta/itypescript) |  |  |  |  |
| Typescript, JavaScript | [tslab](https://github.com/yunabe/tslab) |  |  | [Example notebooks](https://github.com/yunabe/tslab/blob/master/README.md#example-notebooks) | [Jupyter kernel for JavaScript and TypeScript](https://github.com/yunabe/tslab) - [npm](https://www.npmjs.com/package/tslab) |
|  | [Common Workflow Language (CWL) Kernel](https://github.com/giannisdoukas/CWLJNIKernel) |  |  | [examples directory](https://github.com/giannisdoukas/CWLJNIKernel/blob/master/examples/) |  |
| [Vim script](https://github.com/vim/vim/) | [A Jupyter kernel for Vim script](https://github.com/mattn/vim_kernel) | Jupyter |  |  |  |
| VPython | [IVisual](https://pypi.python.org/pypi/IVisual) |  |  | [Ball-in-Box](http://nbviewer.jupyter.org/url/dl.dropboxusercontent.com/u/5095342/visual/Ball-in-Box.ipynb) |  |
| Whitespace | [Whitenote](https://github.com/makiuchi-d/whitenote) | Jupyter>=5 |  | [example.ipynb](https://github.com/makiuchi-d/whitenote/blob/main/example.ipynb) | [Docker image](https://hub.docker.com/r/makiuchid/whitenote) |
| Wolfram Mathematica | [Wolfram Language for Jupyter](https://github.com/WolframResearch/WolframLanguageForJupyter) |  |  |  | A Jupyter kernel for [the Wolfram Language](https://www.wolfram.com/language) (Mathematica). |
| Wolfram Mathematica | [IWolfram](https://github.com/mmatera/iwolfram) |  |  |  | MetaKernel |
| Xonsh | [Xonsh](https://github.com/calysto/xonsh_kernel) |  |  | [Example](http://nbviewer.ipython.org/github/Calysto/xonsh_kernel/blob/master/xonsh_kernel.ipynb) | MetaKernel |
| YACAS | [Yacas](https://github.com/grzegorzmazur/yacas_kernel) |  |  |  |  |
| Zsh | [Z shell](https://github.com/dan-oak/zsh-jupyter-kernel) | IPython >= 3 |  | [Example](https://github.com/dan-oak/zsh-jupyter-kernel/blob/master/example.ipynb) |  |

<!-- /div -->

Many kernels are available for installation on [PyPI](https://pypi.python.org/pypi?:action=browse&c=586).

## Additional Related Projects

<!-- *   [Jove](https://github.com/jove-sh) - notebook interface in Java; provides Spark and Scala kernels  -->
*   [Brython Magics](https://github.com/kikocorreoso/brythonmagic) - A magic trick to allow you to use Brython code (client-side) in other notebooks  
*   [pixiedust_node](https://github.com/ibm-watson-data-lab/pixiedust_node) - PixieDust extension that enable a Jupyter Notebook user to invoke Node.js commands.

## Creating new Jupyter kernels

[Making kernels for Jupyter](http://jupyter-client.readthedocs.org/en/latest/kernels.html) in the documentation.

[Simple example kernel](https://github.com/dsblank/simple_kernel)

[IHaskell creator blog post](http://andrew.gibiansky.com/blog/ipython/ipython-kernels/)

[Testing kernels against message specification (work in progress)](https://github.com/ipython/ipython/wiki/Dev:-Testing-kernels-against-message-specification)

[Tool to test a kernel against specification (work in progress)](https://github.com/jupyter/jupyter_kernel_test)
