# LaTeX Templates

This repo contains the following LaTeX templates:

* Academic Journal
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.sty)
  * [Sample bib (citation source) file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/bibliography.bib)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.pdf)
* Presentation
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Presentation/presentation.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Presentation/presentation.sty)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Presentation/presentation.pdf)
* Problem Set
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.sty)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.pdf)
* Cheat Sheet
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.sty)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.pdf)

Files under the [Tips](https://github.com/scaotravis/LaTeX-Templates/tree/master/Tips) folder also contain references to some common math symbols and some helpful tips to LaTeX.

## Notes

1. All TeX styles are defined in a `.sty` file, which needs to be placed in the same folder with the `.tex` file
1. TeX files in this repo will read image references from a subfolder `figures`. If you'd rather not have such setting, remove or comment out the following line in the respective `.sty` file

    ```tex
    \graphicspath{{./figures/}}
    ```

1. `tabular` created by the style files in this repo spreads out vertically a bit for aesthetic reasons (except for `cheat-sheet.sty` and `presentation.sty` to save space). If you want to modify the amount of vertical spread, change the following lines in the respective `.sty` file:

    ```tex
    % More spaced out tabular
    \setlength\extrarowheight{1.2pt}
    \renewcommand{\arraystretch}{1.2}
    ```

## Resources on Getting Started with LaTeX

* [Getting started with TeX, LaTeX, and friends](https://www.tug.org/begin.html)
* [Overleaf tutorials](https://www.overleaf.com/learn/latex/Tutorials)

## Guides on Making Presentation Slides

* [How to give an applied micro talk](https://www.brown.edu/Research/Shapiro/pdfs/applied_micro_slides.pdf)
