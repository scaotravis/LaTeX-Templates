# LaTeX Templates
This repo contains three types of LaTeX templates: 
* Academic Journal
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.sty)
  * [Sample bib (citation source) file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/bibliography.bib)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Academic-Journal/journal.pdf)
* Problem Set
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.sty)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Problem-Set/problem-set.pdf)
* Cheat Sheet
  * [TeX file](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.tex)
  * [Document style](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.sty)
  * [PDF preview](https://github.com/scaotravis/LaTeX-Templates/blob/master/Cheat-Sheet/cheat-sheet.pdf)

Files under the [Tips](https://github.com/scaotravis/LaTeX-Templates/tree/master/Tips) folder also contain references to some common math symbols and some helpful tips to LaTeX. 

# Notes
1. All TeX styles are defined in a `.sty` file, which needs to be placed in the same folder with the `.tex` file
1. TeX files in this repo will read image references from a subfolder `figures`. If you'd rather not have such setting, remove or comment out the following line in the respective `.sty` file
    ```
    \graphicspath{{./figures/}}
    ```
1. `tabular` created by the style files in this repo spreads out vertically a bit for aesthetic reasons (except for in `cheat-sheet.sty` to save space). If you want to modify the amount of vertical spread, change the following lines in the respective `.sty` file: 
    ```
    % More spaced out tabular
    \setlength\extrarowheight{1.2pt}
    \renewcommand{\arraystretch}{1.2}
    ```

# Resources on Getting Started with LaTeX
* [Getting started with TeX, LaTeX, and friends](https://www.tug.org/begin.html)
* [Overleaf tutorials](https://www.overleaf.com/learn/latex/Tutorials)
