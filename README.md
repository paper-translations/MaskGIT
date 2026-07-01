# MaskGIT

Chinese translation of [MaskGIT: Masked Generative Image Transformer](https://arxiv.org/abs/2202.04200) (Chang et al., CVPR 2022), typeset in the CVPR 2022 paper format.

**Original authors**: Huiwen Chang, Han Zhang, Lu Jiang, Ce Liu, William T. Freeman (Google Research)

## Build

Requires XeLaTeX and the following fonts:

| Role | Font |
|---|---|
| CJK body | FZShuSong-Z01 |
| CJK bold | FZHei-B01 |
| CJK italic | FZKai-Z03 |
| CJK bold italic | FZFangSong-Z02 |
| Latin body | Times New Roman |

```bash
xelatex main.tex
xelatex main.tex
```

The compiled bibliography (`main.bbl`) is committed directly, so `bibtex` does not need to be run.

## License

This translation is for educational purposes only. All rights belong to the original authors.

## Acknowledgements

This document is typeset using the CVPR 2022 LaTeX template, developed by Ming-Ming Cheng (Nankai University) and further modified by Stefan Roth for CVPR 2022, based on the original CVPR/ICCV template files contributed by Paolo Ienne and Andrew Fitzgibbon.
