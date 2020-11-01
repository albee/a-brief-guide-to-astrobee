# a-brief-guide-to-astrobee

This is the latest available version of "A Brief Guide to Astrobee's Flight Software," a guide to modifying Astrobee's Flight Software source code to incorporate GNC and autonomy modifications. The Astrobee Flight Software (AFS) is written by NASA Ames and is available [here](https://github.com/nasa/astrobee); this document was originally produced by members of the MIT Space Systems Lab and the Ventura group at Instituto Superior Técnico to complement the AFS documentation.

Feel free to make pull requests with edits to the main TeX document. Let the authors know if you are planning to create new documents based on this material and provide a citation back to this document!


```
@misc{Albee2020,
author = {Albee, Keenan and Ekal, Monica and Oestreich, Charles},
number = {October},
title = {{A Brief Guide to Astrobee's Flight Software}},
year = {2020}
}
```

<p align="center">
<img src="tex/img/astrobee_mascot.png" alt="drawing" width="300" class="center"/>
<p align="center">



## LaTeX

`tex` contains the LaTeX for creating this document. `main.tex` is the sole TeX file for the guide. All images are in `img`, and many are generated from `astrobee_guide_palette.svg`.

Note that the markdown package is used (so that markdown
can be used within LaTeX), see [here](http://mirrors.ibiblio.org/CTAN/macros/generic/markdown/markdown.html).
