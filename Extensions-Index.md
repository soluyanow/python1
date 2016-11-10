Extensions you can install for IPython are listed here. To create a new extension, please refer to the [extension docs](http://ipython.readthedocs.io/en/stable/config/extensions/index.html).

## ActiveState Code Recipes magics

Allows querying [ActiveState Code Recipes](http://code.activestate.com/recipes/langs/python)

* [Homepage](https://github.com/debjan/ipython-recipes-magic)

Installation:

```
%install_ext https://raw.github.com/debjan/ipython-recipes-magic/master/recipes.py
```


## Asymptote

* [Homepage](https://github.com/jrjohansson/ipython-asymptote)

[Asymptote](http://asymptote.sourceforge.net/) is a powerful vector graphics
language for generating scientific diagrams.

This IPython magic extension makes it easy to create and display Asymptote
diagrams within an IPython notebook.

See the [example notebook](http://nbviewer.ipython.org/github/jrjohansson/ipython-asymptote/blob/master/examples/asymptote_magic_examples.ipynb) for installation instruction and example of how to use this magic extension.

## base16-ipython-matplotlibrc
Enables matplotlib themes that match base16 [notebook themes](https://github.com/nsonnad/base16-ipython-notebook).

[Homepage](https://github.com/benjaminaschultz/base16-ipython-matplotlibrc)

[Example Screenshot](https://raw.githubusercontent.com/benjaminaschultz/base16-ipython-matplotlibrc/master/eighties_dark.png)

## Brythonmagic
Enables the possibility to use Brython in the notebook so you can interact with the notebook or use javascript libraries without having to write [much] javascript.

[Homepage](https://github.com/kikocorreoso/brythonmagic)

Some notebooks:

* [General examples](http://nbviewer.ipython.org/github/kikocorreoso/brythonmagic/blob/master/notebooks/Brython%20usage%20in%20the%20IPython%20notebook.ipynb).
* [A notebook tutorial about the use of Highcharts.js in the notebook](http://nbviewer.ipython.org/github/kikocorreoso/brythonmagic/blob/master/notebooks/Highcharts%20(python)%20tutorial.ipynb).

To install:

```
%install_ext https://raw.github.com/kikocorreoso/brythonmagic/master/brythonmagic.py
```

## Cassandra (CQL3) integration

Query cassandra directly from ipython.

* [Homepage](https://github.com/rustyrazorblade/ipython-cql)

Installation:

```
pip install ipython-cql
```

[Example Screenshot](https://www.dropbox.com/s/vkpjhob4gcbp8ho/ipython-cql.png?dl=0)


## CSV Magic

Tools for quickly importing and exporting data from CSV files.
* [Homepage](https://github.com/FrankSalad/ipython-csvmagic)

Installation:
```
%install_ext https://raw.githubusercontent.com/FrankSalad/ipython-csvmagic/master/csvtools.py
```

## Django ORM magic

Define your django models in a cell and use them on the fly. Let the magic do the boring part.

* [Homepage](https://github.com/mgaitan/django-orm-magic)

Installation:

```
%install_ext https://raw.github.com/mgaitan/django-orm-magic/master/django_orm_magic.py
```

## ipythonPexpect magic

A magic that allows IPython notebooks to interface with other programs via Pexpect (written by Adam Lyon).

* [Example notebook](http://nbviewer.ipython.org/url/home.fnal.gov/~lyon/ipython_ext/ipythonPexpect_example.ipynb) - including interfacing with bash, R, and CERN's ROOT system.

To install :

```
%install_ext https://cdcvs.fnal.gov/redmine/projects/ipython_ext/repository/revisions/master/raw/ipythonPexpect.py
```


## fortran magic

Compile and import everything from a Fortran code cell, using f2py.

* [Homepage](https://github.com/mgaitan/fortran_magic)
* [Documentation](http://nbviewer.ipython.org/github/mgaitan/fortran_magic/blob/master/documentation.ipynb)

To install :

```
%install_ext https://raw.github.com/mgaitan/fortran_magic/master/fortranmagic.py
```

## clrmagic (C# cell magic for IPython kernel)

Compile and import everything from a C# (CLR) code cell, using [pythonnet](https://github.com/pythonnet/pythonnet).

* [Homepage](https://pypi.python.org/pypi/clrmagic/)
* [Tutorial](https://github.com/denfromufa/clrmagic/blob/master/README.md)

To install :

```
pip install clrmagic
%reload_ext clrmagic
```

## ferret

ferret, the Data Visualisation and Analysis software from NOAA/PMEL, can now be integrated into notebooks using the _ipython ferretmagic extension_. Install instructions and examples are included in notebooks on the GitHub page.

[Homepage](https://github.com/PBrockmann/ipython_ferretmagic)

To install:

```text
pip install ferretmagic
```
In ipython notebooks,
```
%load_ext ferretmagic
```

## ipyBibtex

With this extension you can use LATEX style references within IPython (Notebook) while still using markdown for formatting.

[Homepage](https://gist.github.com/z-m-k/6080008)

[Example Notebook](http://nbviewer.ipython.org/6080008/ipyBibtex.ipynb)

To install:

```text
%install_ext https://gist.github.com/z-m-k/6080008/raw/7611cb869b5ff162d00e95856054b887b0b0d095/ipyBibtex.py
```

## physics

Enables calculations involving units, such as `(5 m/s) * (3 s)`. It also defines a range of physical constants, such as the speed of light in a vacuum, and the mass of an electron.

[Homepage](https://bitbucket.org/birkenfeld/ipython-physics)

To install:

```text
    %install_ext https://bitbucket.org/birkenfeld/ipython-physics/raw/default/physics.py
```

Note: In the latest version, quantities with uncertainties are supported if the
`uncertainties` module is installed.

## `%hierarchy` and `%%dot` magics

The `%hierarchy` magic command draws an inheritance diagram of the given class or object.
With the `%%dot` cell magic, you can write graphiz dot language in a cell.

[Homepage](https://github.com/tkf/ipython-hierarchymagic)

To install:

```text
  %install_ext https://raw.github.com/tkf/ipython-hierarchymagic/master/hierarchymagic.py
```

## `%importfile` magic

`%importfile` tries to import Python file in most "natural way". For
example, if you have `spam/egg/module.py`, `spam/egg/__init__.py`
and `spam/__init__.py`, you would want import `module.py` as
`spam.egg.module`, not as `module` or `egg.module`.
`%importfile` tries several heuristics to find the best "module path".

[Homepage](https://github.com/tkf/ipython-importfilemagic)

To install:

```text
  %install_ext https://raw.github.com/tkf/ipython-importfilemagic/master/importfilemagic.py
```

Usage:

```text
  %importfile PATH/TO/SOME/FILE.py
```

## Divers

Interactive plotting in notebook using the [flot library](http://code.google.com/p/flot/),
use the `ipython-flot` package.

[Homepage](https://github.com/crbates/ipython-flot/)

A Notebook example can be found [here](https://gist.github.com/3015819). This is not an extension, so it does not need `%install_ext` nor `%load_ext` to work.

## Bitey

The Bitey extension adds a `%%bitey` cell magic for automatically compiling C (or C++) code into LLVM bitcode and loading the bitcode with [Bitey](https://github.com/dabeaz/bitey).  See also a [sample notebook](http://nbviewer.ipython.org/3458310/Bitey%20Magic.ipynb).

[Homepage](https://gist.githubusercontent.com/bfroehle/3458310/raw/biteymagic.py)

To install:

```text
    %install_ext https://gist.githubusercontent.com/bfroehle/3458310/raw/biteymagic.py
```
## Mathematica

Mathematica can be integrated into notebooks using the `IPython-mathematicamagic-extension`. Install instructions and examples are included in a notebook on the GitHub page. Requires the mathlink python module distributed with Mathematica.

[Homepage](https://github.com/bjedwards/IPython-mathematicamagic-extension)

## Matlab

The [Python MATLAB bridge](https://github.com/arokem/python-matlab-bridge)  enables calling of MATLAB code and functions from an IPython session and adds a `%%matlab` cell magic, which allows embedding matlab code in IPython notebooks.

[Homepage](https://github.com/arokem/python-matlab-bridge)

Examples:

* [pymatbridge](http://nbviewer.ipython.org/github/arokem/python-matlab-bridge/blob/master/pymatbridge.ipynb)
* [matlab magic](http://nbviewer.ipython.org/github/arokem/python-matlab-bridge/blob/master/matlab_magic.ipynb)

## IDL

Provides magics for embedding [IDL](http://www.exelisvis.com/ProductsServices/IDL.aspx) and [GDL](http://gnudatalanguage.sourceforge.net/) code using [pIDLy](https://github.com/anthonyjsmith/pIDLy).

[Homepage](https://github.com/ebellm/ipython-idlmagic)

To install:

```text
%install_ext https://raw.github.com/ebellm/ipython-idlmagic/master/idlmagic.py
```
## pep8

Allows to check for the pep8 styleguide using the cellmagic `%%pep8`.

[Homepage](https://github.com/SiggyF/notebooks)

To install:

```text
    %install_ext https://raw.githubusercontent.com/SiggyF/notebooks/master/pep8_magic.py
```

An example is provided [here](http://nbviewer.ipython.org/github/SiggyF/notebooks/blob/master/styleguide.ipynb).


## px magic

Executes shell command and returns stdout as a file like object (pipe). This will make it easy to e.g. read tabular output from shell commands to pandas DataFrame:s.

To install:

```text
    %install_ext https://gist.github.com/kpalin/ec5264445dbb56616d6e/raw/94fe58912752ca2e4b0b20d38674ee8dea69d003/pxmagic.py
```

An example is provided [here](https://gist.github.com/kpalin/ec5264445dbb56616d6e).


## py2tex

Enables conversion of simple expressions to a nice Tex Representation.

- [Gist](https://gist.github.com/4032651)
- [Repository](https://github.com/BekeJ/py2tex)

To install:

```text
    %install_ext https://raw.githubusercontent.com/BekeJ/py2tex/master/py2tex.py
```

An example is provided [here](http://nbviewer.ipython.org/urls/gist.github.com/raw/4040388/ee224a8e0875fad241cea4492b4408f1f72a1d8d/Example_py2tex.ipynb).

The [Unum class](https://bitbucket.org/kiv/unum/src>) is supported for unit-aware calculation.

## duster

Reset namespace and automatically (re)load several modules immediately thereafter.

[Homepage](https://github.com/lebedov/duster)

To install (from the command line):

```text
    pip install duster
```

## icypher

Query a Neo4J graph database with Cypher and get back the results in Python data structures.

[Homepage](https://github.com/lebedov/icypher)

To install (from the command line):

```text
    pip install icypher
```

## idisplay

Magic function for accessing IPython's rich display system without having to explicitly import and call its various classes.

[Homepage](https://github.com/lebedov/idisplay)

To install (from the command line):

```text
    pip install idisplay
```

## inumpy

A numpy extension for IPython. Autocomplete recarray.

[Homepage](https://github.com/piti118/inumpy)

To install:

```text
    %install_ext https://raw.github.com/piti118/inumpy/master/inumpy.py
```

## iorient

Query OrientDB via IPython using OrientDB SQL or Gremlin.

[Homepage](https://github.com/lebedov/iorient)

To install:

```text
    pip install iorient
```

## PlantUML integration

Generate inline, [PlantUML](http://plantuml.com/)-based SVG UML diagrams. 

* [Homepage](https://github.com/jbn/IPlantUML)

Installation:

```
pip install iplantuml
```

##ipy_magics

Cell magics for generating PostScript 2D graphics (using Ghostscript) and RenderMan 3D graphics (using Aqsis), and also audio via Csound.

[Repo](https://github.com/ldo/ipy_magics)

##ipy_table

Create richly formatted data tables in IPython Notebooks.

[Homepage](http://epmoyer.github.com/ipy_table/)

Examples:

* [Introduction](http://nbviewer.ipython.org/github/epmoyer/ipy_table/blob/master/ipy_table-Introduction.ipynb)
* [Reference Guide](http://nbviewer.ipython.org/github/epmoyer/ipy_table/blob/master/ipy_table-Reference.ipynb)

## ipy2wp
Small tool to convert an IPython notebook to html and upload the result to your wordpress blog using XML-RPC.

[Homepage](https://github.com/Pybonacci/ipy2wp).

[Maybe this is not the appropriate place for this but I couldn't find a better place]

## SQLite magics

IPython magics to run SQL and see the result in table format.

[Homepage](https://github.com/tkf/ipython-sqlitemagic)

```text
%install_ext https://raw.github.com/tkf/ipython-sqlitemagic/master/sqlitemagic.py
```


## Doctest magics

Run and debug doctest in IPython.

[Homepage](https://github.com/tkf/ipython-doctestmagic)

```text
%install_ext https://raw.github.com/tkf/ipython-doctestmagic/master/doctestmagic.py
```


## scd - smart change of directory

[Homepage](https://github.com/pavoljuhas/smart-change-directory#smart-change-directory-scd)

- add `%scd` magic for changing to any directory with a few keystrokes
- modify `%cd`, `%pushd`, `%popd` magics to record visited directories in
  `~/.scdhistory`

This plugin is for IPython terminal session on Linux, Mac or other Unix-like
system only.  Must have [Z shell](http://www.zsh.org) (zsh package) and
[scd](https://github.com/pavoljuhas/smart-change-directory/blob/master/bin/scd)
script installed in the PATH.
For best results activate scd also for the system shell as described on
the Homepage.

[Installation Details](https://github.com/pavoljuhas/smart-change-directory#installation-as-ipython-extension)

```text
%install_ext https://raw.github.com/pavoljuhas/smart-change-directory/master/ipython/ipy_scd.py
```


## Magics for temporary workspace

- `%cdtemp` -- Creates a temporary directory that is magically cleaned up
  when you exit IPython session.

- `%%with_temp_dir` -- Run Python code in a temporary directory and
  clean up it after the execution.

[Homepage](https://github.com/tkf/ipython-tempmagic)

```text
%install_ext https://raw.github.com/tkf/ipython-tempmagic/master/tempmagic.py
```


## Magics for activity, block, network and sequence diagrams

Create activity, block, network and sequence diagrams using text definitions similar to graphwiz.
The extension uses blockdiag modules from http://blockdiag.com

[Homepage](https://bitbucket.org/vladf/ipython-diags)

```text
%install_ext https://bitbucket.org/vladf/ipython-diags/raw/default/diagmagic.py
```

## sql

Passes SQL statements to any database reachable by SQLAlchemy, and renders results as tabular HTML or pretty text tables, where possible.

[Homepage](https://pypi.python.org/pypi/ipython-sql)

[Usage sample](http://nbviewer.ipython.org/5272681)

To install (from command line):

```pip install ipython-sql```

## grasp

A set of python functions to help with interactive object
inspection and discovery.

 * %gist -- object inspection
 * %rtype -- recursive type, deep object inspection
 * %apropos -- deep search for things with a given name, value, etc.

Install: ```pip install grasp```

Use: ```%load_ext grasp```

Source code: http://launchpad.net/grasp

More info: http://pypi.python.org/pypi/grasp/

## breakpoint

Run code cells in an iPython notebook until a breakpoint is encountered.

See:

https://github.com/ipython-contrib/IPython-notebook-extensions

## The AnyBody Modeling System

The AnyBody extension adds an `%%anybody` cell magic to run AnyScript macros directly from the IPython Notebook. The [AnyBody Modeling System](www.anybodytech.com) is a multibody modelling system for musculoskeletal biomechanics.

[Github page](https://github.com/melund/anybodymagic)

Usage: See this [IPython notebook](http://nbviewer.ipython.org/github/melund/anybodymagic/blob/master/demo_anybodymagic.ipynb?create=1)

To install: ``` %install_ext https://raw.github.com/melund/anybodymagic/master/anybodymagic.py ```

## Module version information: `%version_information`

The `%version_information` magic extension displays a table with version information for selected Python modules. Use it in a notebook keep a record of exactly which versions of dependency modules were used to run the notebook.

[Homepage](https://github.com/jrjohansson/version_information)

[Example notebook](http://nbviewer.ipython.org/github/jrjohansson/version_information/blob/master/example.ipynb)

## Section numbering: `%secnum`

Provides automatic section numbering for IPython notebooks.

Currently, level-1 headings are labelled like "1. First" and level-2 headings "1.1. Second".
The section numbers are automatically updated every time any cell changes type (e.g. from a Markdown cell to a heading cell).

[Homepage](https://github.com/dpsanders/ipython_extensions/tree/master/section_numbering)

To install:

    %install_ext https://github.com/dpsanders/ipython_extensions/tree/master/section_numbering

To use:

    %load_ext secnum
    %secnum

(Updates are automatic; `%secnum` only needs to be run once per session.)

## .zip, .tar.gz, .tgz extensions support: `%zip_extensions`

* [Homepage](https://github.com/mksenzov/ipython_zip_extensions)
* [Documentation](https://github.com/mksenzov/ipython_zip_extensions/blob/master/README.md)

To install:

    %install_ext https://raw.github.com/mksenzov/ipython_zip_extensions/master/zip_extensions.py

If for example you want to load/start using extension called `grasp` (described above) without using pip do:

    %load_ext zip_extensions

    %install_zip_ext https://pypi.python.org/packages/source/g/grasp/grasp-0.3.2.tar.gz
    %load_zip_ext grasp


## Graphviz Extensions:

These magic functions just pipe various input formats to `dot` using the standard library `subprocess` module. They were written for simplistic demonstration of binary decision diagrams in [PyEDA](https://github.com/cjdrake/pyeda).

* [Homepage](https://github.com/cjdrake/ipython-magic)

To install:

    %install_ext https://raw.github.com/cjdrake/ipython-magic/master/gvmagic.py

To load:

    %load_ext gvmagic

Magics:

* `%dot` - line/cell magic converts raw input to Graphviz `dot` SVG output.
* `%dotstr` - line magic converts string input to Graphviz `dot` SVG output.
* `%dotobj` - line magic converts object with `to_dot` method to Graphviz `dot` SVG output.
* `%dotobjs` - line magic converts sequence of objects with `to_dot` method to Graphviz `dot` SVG output.

Examples:

    %dot digraph G { a -> b; a -> c }

    %%dot digraph G {
        a -> b;
        b -> c;
    }

    %dotstr "digraph G { a -> b; a -> c }"

    %dotobj dotobj.to_dot()

    %dotobjs dotojb[0].to_dot(), dotobj[1].to_dot(), ...

## BeautifulSoup

Pretty HTML rendering and html display of BeautifulSoup queries in the notebook and the qtconsole.

* [Homepage](https://github.com/Psycojoker/ipython-beautifulsoup)

To install:

    pip install "ipython-beautifulsoup[bs4,notebook]"

To load:

    %load_ext soup

Configure how you want the soup extension to work using configure_ipython_beautifulsoup, for example:

    configure_ipython_beautifulsoup(show_html=True, show_css=True, show_js=False)

Then just use the BeautifulSoup object loading into the current context.

![screenshot](https://raw.github.com/Psycojoker/ipython-beautifulsoup/master/teaser.png)


## Page navigation for IPython Notebook

[A Greasemonkey/Tampermonkey user script](http://userscripts.org/scripts/show/180884) that adds a few functions to help you move up and down easily in an IPython notebook page.

To install:

     Get Tampermonkey for Chrome or Greasemonkey for Firefox
     and install the script from http://userscripts.org/scripts/show/180884

What you can do:

     Turbo-Scrolling : Hold [Shift] key while using your mouse wheel to speed
                       up the scrolling about x6. Or, you could also do it
                       by hovering near the left side of page (within 50 px)

     [Top] : Scroll to the page top
     [Bottom] : Scroll to the bottom of page
     [LastCell] : Scroll back to the selected cell

     [+] : increase font-size of notebook tile
     [–] : decrease font-size of notebook tile

## Min's IPython extensions

MinRK has [published](/minrk/ipython_extensions) various (both Python and Notebook) extensions for IPython.

## `py.test` plugin

Discover and run IPython notebook cells as unit tests

* [Github repository](https://github.com/zonca/pytest-ipynb)
* [Release notes](http://zonca.github.io/2014/09/unit-tests-ipython-notebook.html)

## `db.py` plugin

ipython db.py shell extension

[Homepage](https://github.com/dongweiming/idb)

[Example Notebook](http://nbviewer.ipython.org/github/dongweiming/idb/blob/master/examples/db-example.ipynb)

To install:

```text
%install_ext https://raw.githubusercontent.com/dongweiming/idb/master/idb.py
```

## TikZ

IPython magics for generating figures with TikZ. You can select the output format as svg, png or jpg, define the image size, specify a scale factor, load TikZ packages, and save to external files.

* [Homepage](https://github.com/mkrphys/ipython-tikzmagic)

## trepanmagic

IPython extension for using the [python trepan](https://pypi.python.org/pypi?:action=display&name=trepan) debugger.

* [Homepage](https://github.com/rocky/ipython-trepan)

### Installation

To install execute the the following code snippet in an IPython shell or IPython notebook cell:

```
    %install_ext https://raw.github.com/rocky/ipython-trepan/master/trepanmagic.py
    %load_ext trepanmagic
```

or put *trepanmagic.py* in `$HOME/.python/profile_default/startup`:

```
    cd `$HOME/.python/profile_default/startup`:
    wget https://raw.github.com/rocky/ipython-trepan/master/trepanmagic.py
```

## Module Magic

The %%module cell magic for the IPython Notebook. %%module saves the cell as a file and imports it into the session. This is useful for both creating and managing modules within the Notebook, as well as creating sandboxed code - i.e. executing code cells in a separate environment.

* [Homepage](https://github.com/brazilbean/modulemagic)

## Giphy Magic

An IPython magic to embed random GIFs from giphy.com

* [Homepage](https://github.com/AustinRochford/giphy-ipython-magic)

To install:

```text
%install_ext https://raw.githubusercontent.com/AustinRochford/giphy-ipython-magic/master/giphy_magic.py
```

## S3 Image Magic

A set of magics that will display images stored in Amazon S3 and save matplotlib figures to S3.

* [Homepage](https://github.com/AustinRochford/s3img-ipython-magic)

To install:

```text
%install_ext https://github.com/AustinRochford/s3img-ipython-magic/blob/master/s3img_magic.py
```

## Autotime

Times every command.

* [Homepage](https://github.com/cpcloud/ipython-autotime)

Installation:

```
%install_ext https://raw.github.com/cpcloud/ipython-autotime/master/autotime.py
```

## Py_D3

D3 magic for IPython (targeted at Jupyter).

* [Homepage](https://github.com/ResidentMario/py_d3)

Installation:

```
pip install py_d3
```