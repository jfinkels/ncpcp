PCPs for NC
===========

Restricted probabilistically checkable proofs for NC.

This file was last updated on 25 October 2012.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/ncpcp.

To download the paper using [Git][1], run

    git clone git://github.com/jfinkels/ncpcp

[1]: http://git-scm.com

A somewhat recent version of this work should be available at
https://github.com/jfinkels/ncpcp/downloads, but I can't guarantee that that
will always be up to date, since I compile and upload it manually.

Compilation dependencies
------------------------

Besides `pdflatex`, compile-time dependencies include the following LaTeX
packages:

* `amsmath`
* `amssymb`
* `amsthm`
* `complexity`
* `hyperref`
* `thmtools`

On Ubuntu 11.04, 11.10, 12.04, or 12.10, the necessary system packages which
contain these LaTeX packages are:

* `texlive-base`
* `texlive-latex-base`
* `texlive-latex-extra`
* `texlive-science`

To install them, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science

Compiling
---------

To compile the document, run

    pdflatex ncpcp
    bibtex ncpcp
    pdflatex ncpcp
    pdflatex ncpcp

The output is `ncpcp.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2012 Jeffrey Finkelstein.

Except where otherwise noted, both the LaTeX markup and the content of both the
article and the poster are made available under the terms of the Creative
Commons Attribution-ShareAlike 3.0 license,
https://creativecommons.org/licenses/by-sa/3.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
