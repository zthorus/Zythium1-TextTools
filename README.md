# ZTH1-TextTools
Tools to display text on screen with the ZTH1

This repository contains various tools to display texts (ASCII characters) on an
HDMI monitor with the ZTH1 micro-computer (as implemented on a Kamami Maximator
FPGA board). These tools come as files that can be copy-and-pasted into source and
object files of any software developed for the ZTH1. The RAM files contain the
character bitmaps to display ASCII characters, using the font of the Sinclair
ZX-Spectrum (these files have no MIF headers and footers and are intented to be
copied into rom.mif, ram_h.mif and ram_l.mif files).
The source file is in ZTH1 assembly language and contains a routine to display
an ASCII character on the screen (the (x,y) position, as well as the foreground
and background colors, can be selected).
