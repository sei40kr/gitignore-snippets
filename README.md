# gitignore-snippets

## Description

gitignore.io templates for [yasnippet](https://github.com/joaotavora/yasnippet).

## Install

### Doom Emacs

Add in your `$DOOMDIR/packages.el`:

```emacs-lisp
(package! gitignore-snippets
  :recipe (:host github
           :repo "sei40kr/gitignore-snippets"
           :files ("*.el" "snippets")))
```

and then, add your `$DOOMDIR/config.el`:

```emacs-lisp
(after! yasnippet
    (gitignore-snippets-init))
```
