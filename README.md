light-soap-theme
================

emacs 24 theme with light background, created with [emacs-theme-creator](http://emacs-theme-creator.appspot.com/).

Screenshot:
-----------

![Screenshot](https://github.com/mswift42/light-soap-theme/raw/master/screenlight-soap.png)

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** light-soap-theme


To use the light-soap theme when starting emacs, add this to your init.el:

    (load-theme 'light-soap)
