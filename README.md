# sane-coq

This is a basic configuration to reduce the pain involved in starting to work with Coq on your computer via Proof General.
It is based on suggestions from [Clément Pit--Claudel](https://github.com/cpitclaudel/company-coq) (developer of company-coq).

Use it to configure:
 * Loading Proof General initialization file on startup
 * Activating company-coq minor mode when opening a Coq development
 * Useful keyboard shortcuts that are less painful than the default ones

## To use it

Copy the contents of `dot-emacs` to your `.emacs` file (typically located in your home directory).

Modify the paths of the `coqtop` executable and Proof General package in the source.

 * To install Proof General in the same directory used by `dot-emacs` use the following commands:
```bash
git clone https://github.com/ProofGeneral/PG ~/.emacs.d/lisp/PG
cd ~/.emacs.d/lisp/PG
make
```

 * To install company-coq, in Emacs, type <kbd>M-x package-refresh-contents RET</kbd> followed by <kbd>M-x package-install RET company-coq RET</kbd>.
