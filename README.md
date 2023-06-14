# A simple LaTeX template for scientific papers and technical reports

This template is based on the [LaTeX template](https://github.com/alexhernandezgarcia/mais-latex) for Montreal AI Symposium [(MAIS)](http://montrealaisymposium.com/).

## Provided files

* `latex-simple.sty`: Style file
* `latex-simple.bst`: Bibliography style file
* `instructions.tex` and `instructions.pdf`: documentation for the `latex-simple` LaTeX package and tips for authors.
* `references.bib`: an example BibTeX file 
* `barebones_template.tex`: a barebones template.
* `dummy_paper.tex` and `dummy_paper.pdf`: a dummy paper to easily see the approximate final appearance.

## Basic usage

The easiest way to start using this template is probably by cloning the repository:

```
git clone git@github.com:alexhernandezgarcia/latex-simple.git
```

Alternatively, you may simply download the files you will use. You may rename `barebones_template.tex` and start writing your abstract there. If choose to use the default bibliography style and format, you can simply add the BibTex entries of your citations to `references.bib`.

Please read [`instructions.pdf`](./instructions.pdf) for a short introduction of the package and the main functionality.

## Questions

For questions and bug reports, please file issues at https://github.com/alexhernandezgarcia/latex-simple/issues

## Acknowledgements

As a child of [mais-latex](https://github.com/alexhernandezgarcia/mais-latex) template, this template heavily builds upon the template for [AutoML-Conf](https://www.automl.cc), developed by Roman Garnett, Frank Hutter and Marius Lindauer, and generously open-sourced in [https://github.com/automl-conf/LatexTemplate](https://github.com/automl-conf/LatexTemplate). The bibliography style file, `mais.bst`, has been slightly adapted from the style file for [ICML 2022](https://icml.cc/).
