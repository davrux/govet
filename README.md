govet for Emacs
===============

Simple wrapper for go vet command

Simply rewritten from golint.el

Usage:

To install govet, add the following lines to your .emacs file:

```lisp
(add-to-list 'load-path "PATH CONTAINING govet.el" t)
(require 'govet)
```

After this, type M-x govet on Go source code.
