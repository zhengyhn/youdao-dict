youdao-dict
===========

Youdao online dictionary query for Emacs in Linux

## Requirement

* GNU/Emacs or other Emacs
* Linux
* Online

## Installation

Download or clone the repository and drop the directory into your `.emacs.d/`.
Load the files and requre the function like:

```lisp
(add-to-list 'load-path "~/.emacs.d/plugins/youdao-dict")
(require 'youdao-dict-query)
```lisp

## Usage

You can query a word by `M-x youdao-dict-query`. The default keybinding is
`C-c y`, but you can modify it by:

```lisp
(global-set-key (kbd "key-you-like"))
```lisp

## TODO

* Local storage
* Words table

## Author

[Yuanhang Zheng](http://www.zhengyuanhang.com)

## Thanks

* pos-tip.el
