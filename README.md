# HOUND'S TOOTH
A Postscript gimmick to make images with hound's tooth check. Needs Postscript interpreter to run. In case of [Ghostscript](http://ghostscript.com/download/) exec

```
gs -dBATCH -sNX=32 -sDEVICE=pdfwrite -sOutputFile=houndstooth.pdf houndstooth.ps
```
to create PDF file. Parameter `NX` controls number of tiles in x-direction.
