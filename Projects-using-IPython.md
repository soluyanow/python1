Here is a brief list of other projects using IPython. If you know of
more, feel free to add them, and if IPython contributes to a
publication, please use our [ready-made citation
entry](http://ipython.org/citing.html).


List of available kernels
-------------------------

The list of kernels for other languages has been moved [here](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels).

Scientific computing projects
-----------------------------

-   The
    [Nengo](http://nengo.ca/docs/html/advanced/ipython_notebook.html)
    project for simulating large-scale neural systems is the first (that
    we know of) to integrate with the new IPython notebook.

-   The [SimpleCV](http://www.simplecv.org) computer vision project
    ships with an integrated and customized IPython shell.

-   The [JModelica](http://www.jmodelica.org) system for dynamical
    systems simulation and modeling uses IPython and matplotlib for its
    interactive analysis and visualization.

-   The University of Colorado's Mechanical Engineering Department, as
    part of the Denver Aerosol Sources and Health (DASH) study, [uses
    IPython](http://www.microsoft.com/casestudies/Case_Study_Detail.aspx?CaseStudyID=4000007661)
    to parallelize the data analysis.

-   The python binding of the [igraph library for complex network
    research](http://igraph.sourceforge.net) uses IPython for its
    interactive command-line interface.

-   The [Sardana](http://www.sardana-controls.org) system, part of the
    [ALBA Synchrotron Radiation Facility](http://www.cells.es/) control
    system.

-   [ASCEND](http://ascend.cheme.cmu.edu/) embeds an IPython shell in
    its PyGTK GUI, using code from the Accerciser project. [More
    details](http://ascendwiki.cheme.cmu.edu/Python_console_support).

-   [PyIMSL
    Studio](http://www.vni.com/products/imsl/pyimslstudio/overview.php),
    by Visual Numerics, is a set of tools that expose the classic IMSL
    numerical libraries to Python, and ships with IPython, NumPy, SciPy
    and matplotlib as the core Python environment.

-   The [Trilinos](http://trilinos.sandia.gov) project has Python
    bindings that can be used effectively via IPython, see [these
    slides](http://ipython.scipy.org/talks/Trilinos-IPython.pdf) for
    details.

-   The [PyRAF](http://www.stsci.edu/resources/software_hardware/pyraf)
    environment for astronomical image analysis, from the [Space
    Telescope Science Institute](http://www.stsci.edu/), will include in
    its next official release an IPython-based interface. Currently
    (May'05) this functionality is only available via SVN PyRAF.

-   The [CASA interactive shell](http://casa.nrao.edu/demo1.shtml) from
    the National Radio Astronomy Observatory is built on top of IPython.

-   The [Chandra Interactive Analysis of Observations
    (CIAO)](http://cxc.harvard.edu/ciao) environment from the Chandra
    X-Ray Observatory.

-   The [Ganga](http://ganga.web.cern.ch/ganga) system, developed at
    CERN for Grid job control for the
    [LHCb](http://lhcb.web.cern.ch/lhcb) and
    [ATLAS](http://atlas.web.cern.ch/Atlas/index.html) experiments, uses
    IPython for its [CLIP
    interface](http://ganga.web.cern.ch/ganga/user/v4/CLIP).

-   The [ROOT
    project](http://root.cern.ch/drupal/content/discovering-root): a
    framework for data processing, born at CERN, at the heart of the
    research on high-energy physics. See for example [this
    post](http://root.cern.ch/drupal/content/ipython-notebooks-and-root-0).

-   [SageMath](http://www.sagemath.org/), also known as the Sage mathematics
    software system, uses IPython for its interactive command-line interface
    and offers both the Jupyter notebook and the Sage notebook for its
    notebook interface. Note that the Sage notebook was an inspiration for
    the IPython notebook which became the Jupyter notebook.

-   [Singular](http://www.singular.uni-kl.de/), another computer algebra
    system, also offers an IPython interface (Singular is also
    accessible as a SageMath subsystem).

-   The [Pymerase](http://pymerase.sourceforge.net/) project for
    microarray gene expression databases, exposes an IPython shell in
    its iPymerase mode.

-   The PyMAD project, where IPython is used to control a neutron
    spectrometer at the CEA-Grenoble and the Institut Laue Langevin in
    France. See <Projects-using-IPython:-PyMAD> for details.

-   The [Square Kilometre Array South Africa](http://www.ska.ac.za)
    project uses IPython as an advanced user interface to their radio
    telescopes, including the currently operational KAT-7 precursor
    array and the future MeerKAT telescope. A live demonstration of the
    interface can be seen in [Maciej Fijalkowski's
    talk](http://pycon.blip.tv/file/4881233) at PyCon 2011.

-   [rdkit](http://code.google.com/p/rdkit/wiki/IPythonIntegration), a
    chemistry toolkit, integrates with IPython to display molecular
    structures.

-   The
    [PyGrads](http://opengrads.org/wiki/index.php?title=Python_Interface_to_GrADS)
    Python interface to the OpenGrADS tool for access, manipulation, and
    visualization of earth science data.

-   The [ECOOP](http://tw.rpi.edu/web/project/ECOOP) project is using
    IPython to develop the software library for its
    [use-case](http://tw.rpi.edu/web/doc/ICES_2012) .

-   The [AMPL](http://www.ampl.com/) modeling system for large-scale
    mathematical optimization can integrate with IPython with the help
    of AMPL magics provided by the
    [IAMPL](https://github.com/vitaut/iampl) project.

-   [QIIME](http://www.qiime.org) (canonically pronounced "chime")
    stands for Quantitative Insights Into Microbial Ecology. QIIME is an
    open source software package for comparison and analysis of
    microbial communities, primarily based on high-throughput amplicon
    sequencing data (such as SSU rRNA) generated on a variety of
    platforms, but also supporting analysis of other types of data (such
    as shotgun metagenomic data).

-   [KlustaViewa](https://github.com/klusta-team/klustaviewa) is a
    Python GUI software for the manual step of spike sorting, which aims
    at extracting spiking activity from raw extracellular multielectrode
    recordings. An IPython console can be opened in the program to let
    the user perform his own analyses on the data.

-   [Beaker](http://beakernotebook.com/) ([source code](https://github.com/twosigma/beaker-notebook))
    is a language-agnostic notebook UI that uses IPython kernels to power 
    several of its backend languages and uses code from IPython's notebook
    viewer for the backend of its [sharing service](http://sharing.beakernotebook.com/gist/anonymous/11152408).

-   [QtIPy](http://github.com/mfitzp/qtipy) is a GUI utility to enable
    automated running of IPython notebooks in response to file or folder
    changes and timers. Use it to generate automated reports and analysis
    for experimental data sets, output together with the code that made them.

-   [Spyder](https://www.spyder-ide.org/) is a cross-platform PyQt-based IDE
    combining the editing, analysis, debugging and profiling functionality of
    a software development tool with the data exploration, interactive execution,
    deep inspection and rich visualization capabilities of a scientific
    environment like MATLAB or Rstudio. Spyder is fully integrated with
    IPython and Qtconsole through its built in abilities to launch and work with
    [IPython Consoles](https://docs.spyder-ide.org/ipythonconsole.html),
    and IPdb is linked to its
    [GUI debugger](https://docs.spyder-ide.org/debugging.html).
    Spyder's IPython consoles also supports a number of configurable options,
  , can render plots inline with Matplotlib, and can easily connect to native,
    local or remote external kernels with full feature support,
    including a Variable Explorer for rich inspection and editing of objects
    in the IPython environment, a [Help viewer](https://docs.spyder-ide.org/help.html)
    which can retrieve and rich documentation from objects in the console,
    advanced IPython autocompletion and introspection functionality and a
    connection with Spyder's [Editor](https://docs.spyder-ide.org/editor.html)
    to run lines, selections, code cells or files.

-   [scikit-bio](http://scikit-bio.org) is an open-source, BSD-licensed,
    python package providing data structures, algorithms, and educational
    resources for bioinformatics. 

-   [EMPeror](http://emperor.colorado.edu) is a WebGL tool for visualizing
    high-dimensional spaces typically through techniques like principal
    coordinates analysis. 

-   [qiita](https://github.com/biocore/qiita/) (canonically pronounced cheetah)
    the QIIME databasing effort to enable rapid analysis of microbial ecology
    datasets. The Qiita repository is responsible for defining the data
    model and the Python API for interacting with a Qiita database. Qiita
    relies on IPython for parallel compute support.

-   [WooDEM](http://woodem.eu), environment for Discrete Element Modeling
    and multi-body dynamic,s uses IPython for interactive access to all
    internals of simulations (exposed from c++ via boost::python).

-   [neuropy](http://neuropy.github.io) is a command-line based Python program
    for interactive analysis of sorted neuronal spike data, stimulus data, and
    LFP waveforms. neuropy embeds IPython within its main Qt window.

-   [TheVirtualBrain](http://thevirtualbrain.org) ships IPython as its advanced /
    programmable interface, along with notebooks as documentation, e.g the 
    [tutorial on modeling epilepsy propagation](https://github.com/the-virtual-brain/tvb-documentation/blob/master/tutorials/tutorial_3_ModelingEpilepsy.ipynb).


Projects in economics and finance
---------------------------------

-   [fecon235](https://github.com/rsvp/fecon235) is a project for computational data 
    tools in **financial economics**. As of 2015, we have an easy API to freely access 
    data from the U.S. Treasury, Federal Reserve, SEC, CFTC, stock and futures exchanges. 
    Such data is integrated together using *pandas*, and we have developed tools 
    for time-series analysis. Open development is ongoing in the area of international 
    markets, especially: oil, gold, and foreign exchange. 

In teaching
-----------

-   The Software Carpentry Project, led by Greg Wilson, [uses the
    IPython Notebook as one of its core
    technologies](http://software-carpentry.org/blog/2013/03/using-notebook-as-a-teaching-tool.html).

-   The [BEACON course for computational
    biologists](http://ged.msu.edu/angus/beacon-2012/), taught by [Titus
    Brown at Michigan State University](http://ged.msu.edu/).

-   The NIH-funded course on Next-Generation Sequencing, also taught by
    Titus at MSU, is also [based on IPython
    Notebooks](https://github.com/ngs-docs/ngs-notebooks).

-   Tom Softbaugh's [Software development in
    Python](http://www.softbaugh.com/courses/python1/) course.

-   [QIIME](http://www.qiime.org) Workshops are taught using tutorials
    written to run using IPython Notebooks.

Web frameworks and other systems
--------------------------------

-   [Scrapy](http://readthedocs.org/docs/scrapy/en/latest/topics/shell.html),
    a web-scraping framework, uses IPython for its interactive shell if
    it's installed.

-   The [pitz](http://pitz.tplus1.com/) distributed task/bug tracking
    system.

-   Nicolas Rougier implemented a [pyglet Python
    terminal](http://www.loria.fr/~rougier/pyglet-terminal.html) that
    can optionally use IPython.

-   The [Pylons](http://pylonshq.com/) web framework can optionally use
    IPython if installed.

-   As of Jan'06 ([Changeset
    1930](http://code.djangoproject.com/changeset/1930), to be precise),
    IPython is the admin shell for the
    [Django](http://www.djangoproject.com/) web framework.

-   You can use IPython to debug Zope and Plone, as explained in
    [these](http://michaelthornhill.blogspot.com/2005/08/team-development-with-plone-zope-zeo.html)
    [two](http://michaelthornhill.blogspot.com/2005/09/how-to-debug-zopeplone-with-ide.html)
    pages.

-   The [Schevo](http://schevo.org/) database can be [explored with
    IPython](http://orbtech.com/blog/schevo/got-ipython).

-   The [Axon Shell](http://kamaelia.sourceforge.net/AxonShell.html) in
    the BBC's Kamaelia project is an embedded IPython instance.

-   The [emacs-ipython](https://github.com/burakbayramli/emacs-ipython) is an 
    Emacs extension that uses Pymacs to call an ipython kernel, get results and displays 
    them in the LaTeX buffer. Automatic rendering of images from plot commands, 
    even code completion are supported. 

-   As of revision 53 (Oct 11/05), the new [Turbo
    Gears](http://www.turbogears.org/) framework can optionally use
    IPython as its shell. [This
    post](http://www.twistedrails.org/blog/2005/11/13/editing-modelpy-from-ipython-via-tg-admin-shell/)
    has some details on how it works.

-   [Movable Python](http://www.voidspace.org.uk/python/movpy), by
    Michael Foord and Bruno Thoorens, is a way of building portable
    Python environments which uses IPython for its interactive features.

-   The [Logix](http://livelogix.net/logix) programming system
    integrates with IPython for interactive work.

-   The [iVR toolkit](http://visualisation.tudelft.nl/Projects/iVR)
    provides IPython as its shell in interactive Virtual Reality
    applications.

-   The [PuDB](http://pypi.python.org/pypi/pudb) debugger allows the use
    of IPython for its interactive shell.

-   The [StarCluster](http://web.mit.edu/stardev/cluster) EC2 cluster
    computing tool has a
    [plugin](http://web.mit.edu/star/cluster/docs/latest/plugins/ipython.html)
    for configuring a parallel IPython cluster and notebook server.
    StarCluster also uses IPython for its interactive shell
    (\$starcluster shell).

-   [DrQueueIPython](https://ssl.drqueue.org/redmine/projects/drqueueipython),
    a Python port of DrQueue, the open source distributed render queue,
    which uses IPython for task management and network communication.

-   The [JetBrains PyCharm IDE](http://www.jetbrains.com/pycharm) added
    IPython support in version 2.0.

-   The IdleX extensions to Python's basic IDE [support an IPython
    backend](http://idlex.sourceforge.net/ipython.html) from version
    0.8.

-   The [Windmill testing framework](http://www.getwindmill.com/) uses
    IPython for its shell control.

-   [WSPPDE](https://github.com/cwsoft/WSPPDE#readme) provides a
    portable Python 2.7.9 development environment for MS Windows™
    including IPython 3.0.0, Numpy, Scipy, Matplotlib and Pandas in a
    one click package.

-   [NotebookCloud](https://notebookcloud.appspot.com) is a free and
    open source web service for creating and managing IPython Notebook
    servers on Amazon's EC2.

-   [INotebook](https://github.com/tartavull/INotebook) is a desktop app
    for directly opening .ipynb files

-   [Quantopian](https://www.quantopian.com/) is an online algorithm trading platform, using many things inherited from Ipython Notebook.
