# Emacs Major Mode for Mustache

Based on Google's tpl-mode for ctemplates, this major mode adds
support for Mustache's more lenient tag values and includes a few
commands for your editing pleasure.

## Installing

In your shell:

    cd ~/.emacs.d/vendor
    curl --location -O https://github.com/mustache/emacs/raw/master/mustache-mode.el

In your Emacs config:

    (add-to-list 'load-path "~/.emacs.d/vendor/mustache-mode.el")
    (require 'mustache-mode)
