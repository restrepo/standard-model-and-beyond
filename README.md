Detailed notes in Quantum Field Theory
======================================

> Diego Restrepo
> Instituto de Física
> Universidad de Antioquia
> diego.restrepo _AT_ fisica.udea.edu.co

The updated PDF generated from this document is at:

http://goo.gl/ozsl3

LICENSE: All materials are licensed under the [Creative Commons Attribution-Share Alike 3.0 United States License.](http://creativecommons.org/licenses/by-sa/3.0/us/)

The master file is:
    $ pdflatex beyond

There is another master file to generate selected parts of the book in
presentation mode:

    $ pdflatex beyond.beamer


the parts are the ones inside the beamer enviorement

    \begin{frame}[fragile,allowframebreaks]
    ...
    \end{frame}

We have used the a trick with the coment package, in order that the
original master file ignores the frame enviroment. beyond.tex includes
the following lines:

    \usepackage{comment}
    ...	
    \includecomment{frame}
    \specialcomment{frame}
    {\begingroup}{\endgroup}
    %\excludecomment{frame}

The figures/ dir contains the figures in pdf with some sources in svg.

This file was written in Markdown wiki format: 

* [Help](http://daringfireball.net/projects/markdown/syntax)
* [Example in GithHub](https://raw.github.com/github/gollum/master/README.md)



