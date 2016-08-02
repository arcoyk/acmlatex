# ACM LaTeX Template with MacTex
MacTex installation for ACM SIG Proceedings Templates in LaTeX.

## Install MacTex

```
brew update
brew install caskroom/cask/brew-cask
brew cask install mactex
```

## Edit

```
vim sig-alternate-sample.tex
```

## Compile and See

```
platex sig-alternate-sample.tex
dvipdfm sig-alternate-sample.dvi
open sig-alternate-sample.pdf
```

or

```
source proc
```

## Terms

* TeX: A typesetting language.
* LaTeX: A set of macro for TeX.
* TeX Live: TeX distribution.
* TeXShop: TeX previewer for OSX.
