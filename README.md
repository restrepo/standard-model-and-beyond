Detailed lecture notes in Quantum Field Theory
=============================================

[PDF](https://github.com/restrepo/beyond-the-standard-model/releases/latest) generated with [TravisCI](https://github.com/travis-ci). (See [HowTo-Deploy-LaTeX-Documents](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents))

[![Build Status](https://travis-ci.org/restrepo/beyond-the-standard-model.svg?branch=master)](https://travis-ci.org/restrepo/beyond-the-standard-model) 
[![GitHub Release](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://github.com/restrepo/beyond-the-standard-model/releases/latest) 
[![GitHub forks](https://img.shields.io/github/forks/restrepo/beyond-the-standard-model.svg)](https://github.com/restrepo/beyond-the-standard-model/network) 
[![GitHub stars](https://img.shields.io/github/stars/restrepo/beyond-the-standard-model.svg)](https://github.com/restrepo/beyond-the-standard-model/stargazers)



> Diego Restrepo

> Instituto de Física

> Universidad de Antioquia

> restrepo _AT_ .udea.edu.co


LICENSE: All materials are licensed under the
[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/) 

The master file is:
    $ pdflatex beyond.tex

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


### NOT Longer maintained versions:

You can clone/edit/push directly from:

https://git.overleaf.com/2638177mjdkmh


The updated PDF generated from this document is at:

http://goo.gl/ozsl3

or (partially until chapter 4) from the [ShareLaTeX](https://www.sharelatex.com/github): [![PDF Status](https://www.sharelatex.com/github/repos/rescolo/beyond-the-standard-model/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/rescolo/beyond-the-standard-model/builds/latest/output.pdf)

