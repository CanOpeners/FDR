# FDR
FDR for CanSat 2020/21

# Requirements
You need the following packages (and their dependencies) for compiling the TeX source:
- [amsmath](https://www.ctan.org/pkg/amsmath)
- [babel](https://www.ctan.org/pkg/babel)
- [caption](https://www.ctan.org/pkg/caption)
- [color](https://www.ctan.org/pkg/color)
- [currfile](https://www.ctan.org/pkg/currfile)
- [fancyhdr](https://www.ctan.org/pkg/fancyhdr)
- [geometry](https://www.ctan.org/pkg/geometry)
- [graphicx](https://www.ctan.org/pkg/graphicx)
- [hypcap](https://www.ctan.org/pkg/hypcap)
- [hyperref](https://www.ctan.org/pkg/hyperref)
- [import](https://www.ctan.org/pkg/import)
- [inputenc](https://www.ctan.org/pkg/inputenc)
- [pdfpages](https://www.ctan.org/pkg/pdfpages)
- [standalone](https://www.ctan.org/pkg/standalone)
- [titling](https://www.ctan.org/pkg/titling)




The Makefile uses the [rubber](https://gitlab.com/latex-rubber/rubber/) TeX build system.
Also, the makefile's `all` target automatically compresses the target PDF using `ps2pdf`.
