# README #

A curriculum vitae using a modified version of [moderncv](http://www.ctan.org/pkg/moderncv). Feel free to fork away but be sure to change the information.

The font used is called [Myriad Pro Light](http://store1.adobe.com/cfusion/store/html/index.cfm?store=OLS-US&event=displayFont&code=MYRP10003000) and costs $35.

![Preview](http://i.imgur.com/AVNVRwU.png)

## Building ##

To build the resume as previewed you need

- a working Tex distribution with `xetex` engine
- [Myriad Pro Light](http://store1.adobe.com/cfusion/store/html/index.cfm?store=OLS-US&event=displayFont&code=MYRP10003000) font ($35)

If you don't have (the money for) the font, don't worry. Just pick another font that works for you.

TeXworks and RStudio should pick up the typesetting engine using the directives at the beginning of the file. If you want are familiar with the command line you can just

	$ xelatex cv.tex

or use the Makefile for convenience and

	$ make