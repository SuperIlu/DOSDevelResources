# MS-DOS development resources
This is my short list of interesting resources for MS-DOS development. This is neither meant to be unbiased nor exhaustive, it is just a list of software/tools I know and/or use. The focus is on free and open source software. No abandonware!

* (F) indicates a favorite of mine
* (S) is one of my own projects

# Compiler
## DJGPP (F)
DJGPP is a complete 32-bit C/C++ development system for Intel 80386 (and higher) PCs running DOS. It includes ports of many GNU development utilities. The development tools require a 80386 or newer computer to run, as do the programs they produce. In most cases, the programs it produces can be sold commercially without license or royalties. 
### Links
- Project page: https://www.delorie.com/djgpp/
- Creating a cross compiler on Linux: https://github.com/jwt27/build-gcc
- RHIDE integrated enviroment for DJGPP: https://sourceforge.net/projects/rhide/

## OpenWatcom (F)
An open source version of the Watcom C/C++ and FORTRAN 77 compiler able to create EXEs for 16/32bit DOS and Windows.
### Links
- Project page: http://www.openwatcom.org/
- Friendly fork: https://github.com/open-watcom/open-watcom-v2

## FreeBASIC
FreeBASIC is a free/open source (GPL), BASIC compiler for Microsoft Windows, DOS and Linux. 
### Links
https://www.freebasic.net/

## BCC
C compiler that produces 8086 assembler for tiny/small models.
### Links
https://gitlab.com/FreeDOS/devel/bcc

## GCC-IA16
Intel 16-bit x86 port of GNU compilers
### Links
https://gitlab.com/tkchia/build-ia16

## Free Pascal
Free Pascal is a mature, versatile, open source Pascal compiler.
### Links
https://www.freepascal.org/

## JWasm
masm compatible assembler.
### Links
https://github.com/Baron-von-Riedesel/JWasm

## i486-w64-mingw32 (S)
Compile a MSVCRT base mingw64 for i486 architectures on Linux.
### Links
https://gist.github.com/SuperIlu/1f0ed930d907442c0fcb2566f7e63ae9

# Interpreters/Frameworks
## DOjS (S)
A MS-DOS Creative Coding IDE/platform based on JavaScript.
### Links
https://github.com/SuperIlu/DOjS

## LoveDOS (S)
A framework for making 2D DOS games in Lua. LoveDOS provides an API based on a subset of the LÖVE API.
### Links
- Original version: https://github.com/rxi/lovedos
- My version with small fixes/improvements: https://github.com/SuperIlu/lovedos

## QBASIC
QuickBasic is a programming language developed by Microsoft for use in the MS-DOS operating system.
### Links
http://www.petesqbsite.com/sections/introduction/intro.shtml

## GameMaker
Recreational Software Design's GameMaker product, released in 1994 
### Links
https://github.com/gandrewstone/GameMaker

## Adventure Creation Kit
Adventure Creation Kit (ACK) is a game development tool by Chris Hopkins that allows you design and play top-down 2D tile-based RPGs like Ultima IV & V of yore.
### Links
https://mozomedia.com/ack/aboutack/

## ADVGEN
ADVGEN is a text adventure game compiler and interpreter system that I wrote in QuickBASIC in 1991 over the course of a month when I was in middle school. It has been untouched since then.
### Links
https://github.com/RobertSundling/ADVGEN

## DIV Games Studio 2
Complete cross platform games development package, originally for DOS but now available on modern platforms. 
### Links
https://github.com/DIVGAMES/DIV-Games-Studio

# Libraries
Helper libraries for various topics.

## lib16 (S)
Small 16-bit DOS library for use with OpenWatcom.
### Links
https://github.com/SuperIlu/lib16

## AllegroXC (F)
Fork of Allegro 4.2.2 for cross compiling for DOS game development 
### Links
https://github.com/msikma/allegro-4.2.2-xc

## PCTIMER
Millisecond Resolution Timing With DJGPP V2 and DPMI
### Links
https://technology.chtsai.org/pctimer/

## GLIDE3 (F)
This is the source code to 3Dfx Glide for Voodoo graphics accelerators.
### Links
https://github.com/sezero/glide

## Watt-32 (F)
Watt-32 TCP/IP library and samples. 
### Links
https://github.com/gvanem/Watt-32

## mTCP
mTCP is a set of TCP/IP applications for personal computers running PC-DOS, MS-DOS, FreeDOS, and other flavors of DOS.
### Links
https://www.brutman.com/mTCP/

## AllegroPNG
This library servers for displaying PNG images in programs using the Allegro multimedia library. It's completely standalone, it doesn't require libpng nor zlib (however it can use zlib if installed). 
### Links
http://alpng.sourceforge.net/

## DZCOMM
DZCOMM is a API for doing serial I/O under DOS, Linux and SunOS.
### Links
http://dzcomm.sourceforge.net/

## perlin-noise
Various versions of Perlin noise (C and C++) 
### Links
https://github.com/stegu/perlin-noise

## kuba zip
A portable, simple zip library written in C .
### Links
https://github.com/kuba--/zip

## zlib
zlib is designed to be a free, general-purpose, legally unencumbered -- that is, not covered by any patents -- lossless data-compression library for use on virtually any computer hardware and operating system.
### Links
https://zlib.net/

## libjpeg
JPEG (de)compression library.
### Links
http://ijg.org/

## micromod
Music player libraries for MOD, S3M and XM formats.
### Links
https://github.com/martincameron/micromod

## ini
A tiny ANSI C library for loading .ini config files 
### Links
https://github.com/rxi/ini

# Emulation
If you don't have real hardware available you can run your DOS programs using the following emulators.

## DOSBox-staging (F)
DOSBox Staging is a modern continuation of DOSBox— your existing configurations will continue to work, and you will have access to many advanced features. 
### Links
https://www.dosbox-staging.org/

## DOSBox-X
DOSBox-X is an open-source DOS emulator for running DOS applications and games.
### Links
https://dosbox-x.com/

## 86Box (F)
86Box is a low level x86 emulator that runs older operating systems and software designed for IBM PC systems and compatibles from 1981 through fairly recent system designs based on the PCI bus.
### Links
https://86box.net/

## PCEm
PC hardware emulator
### Links
https://pcem-emulator.co.uk/

## MartyPC
An IBM PC/XT emulator written in Rust. 
### Links
https://github.com/dbalsom/martypc

# Operating systems
Here you can find DOS compatible operating systems.

## FreeDOS (F)
FreeDOS is an open source DOS-compatible operating system that you can use to play classic DOS games, run legacy business software, or write new DOS programs. Any program that works on MS-DOS should also run on FreeDOS.
### Links
https://www.freedos.org/

## Win98 Quick install (F)
A framework + installer to (very) quickly install Windows 98 on anything from a 486 up to a modern system 
### Links
https://github.com/oerg866/win98-quickinstall

## SvarDOS
an open-source DOS distribution.
### Links
http://svardos.org/

# Other tools
## Fontána
Fontána is tool for developers. It is a bitmap font editor (with ability to import from some vector formats) which allows you to create, convert and edit fonts stored in many file formats. 
### Links
https://www.laaca.borec.cz/blocek/

## Doszip (F)
The Doszip Commander is an LFN-aware TUI file manager (NC clone) with built-in Zip and UnZip for DOS and Windows.
### Links
https://sourceforge.net/projects/doszip/

## Smart Boot Manager (F)
Smart Boot Manager or briefly SmartBtmgr (SBM), is an OS independent Boot Manager - a program that is loaded by the bios before any operating system and allows you to choose which operating system to boot. 
### Links
https://btmgr.sourceforge.net/download.html

## FreeDOS repo
A repository of FreeDOS-compatible freeware and OSS software. No "abandonware".
### Links
https://clasqm.github.io/freedos-repo/

## VSBHDA
Sound blaster emulation for HDA (and AC97/SBLive); a fork of crazii's SBEMU
### Links
https://github.com/Baron-von-Riedesel/VSBHDA

# Documentation
## ctyme (F)
HTML version of the famous Ralf Brown Interrupt List with over 9000 linked pages and 350 indexes making the process of searching much easier. This list contains every documented and undocumented interrupt call known. Ralf Brown is a Postdoctoral Fellow at Carnegie Mellon University 's Center for Machine Translation in Pittsburgh, Pennsylvania. He is well-known in cyberspace for maintaining the Interrupt List. We all appreciate his continued support.
### Links
https://www.ctyme.com/rbrown.htm

## HelpPC Reference Library
This site is a HTML version of HelpPC Reference Library, a DOS-based hypertext program by David Jurgens.
### Links
https://www.stanislavs.org/helppc/

## FreeVGA
Hardware Level VGA and SVGA Video Programming Information Page
### Links
http://www.osdever.net/FreeVGA/home.htm

## SoundBlaster guide
Sound Blaster Series Hardware Programming Guide
### Links
https://pdos.csail.mit.edu/6.828/2005/readings/hardware/SoundBlaster.pdf

## Basic Gravis UltraSound Programming (F)
The Gravis Ultrasound is by far the best & easiest sound card to program. Why? Because the card does all the hard stuff for you, leaving you and the CPU to do other things! This reference will document some (but not all) of the Gravis Ultrasound's hardware functions, allowing you to play music & sound effects on your GUS.
### Links
https://archive.gamedev.net/archive/reference/articles/article448.html

## Glide 3.0 Programming Guide (F)
Programming the 3Dfx Interactive Glide™ Rasterization Library 3.0
### Links
http://www.bitsavers.org/components/3dfx/Glide_Programming_Guide_3.0_199806.pdf

## PC Game Programmer's Encyclopedia
The PC Game Programmer's Encyclopedia (PCGPE or PC-GPE) is a collection of text files that cover numerous aspects of game development for DOS.
### Links
https://www.phatcode.net/articles.php?id=247

## Building Win16 applications in C
This article explains how to write a fully featured Win16 GUI application in C.
### Links
https://www.transmissionzero.co.uk/computing/win16-apps-in-c/

## Programming the AdLib/Sound Blaster FM Music Chips
Two of the most popular sound cards for the IBM-PC, the AdLib and the Sound Blaster, suffer from a real dearth of clear documentation for programmers. AdLib Inc. and Creative Labs, Inc. both sell developers' kits for their sound cards, but these are expensive, and (in the case of the Sound Blaster developers' kit) can be extremely cryptic. This document is intended to provide programmers with a FREE source of information about the programming of these sound cards. 
### Links
http://www.shipbrook.net/jeff/sb.html

## The Graphics File Formats Page
This site contains specifications for various graphics file formats; along with a number of relevant graphics utilities, information, and URLs. The site was originally created in 1994 to help serve the growing community of web developers. 
### Links
https://www.martinreddy.net/gfx/
