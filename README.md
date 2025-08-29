# EINE source code and files, 1975-1981 
This repository contains the source code and related files for the text editor [EINE](https://en.wikipedia.org/wiki/EINE_and_ZWEI) (**E**INE **I**s **N**ot **E**macs) from 1975-1981, created by Daniel Weinreb, with contributions from other MIT AI lab members. It was the first clone of Emacs and created as an editor for the [Lisp machine](https://en.wikipedia.org/wiki/Lisp_machine) at the MIT AI lab. In this set are also the source files for Weinreb's undergraduate thesis, "A Real-Time Display-oriented Editor for the LISP Machine," which describes EINE but mainly focuses on a later version called ZWEI (**Z**WEI **W**as **E**INE **I**nitially). The files available in this repo are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [eine](../main/eine)
The files within this directory are the EINE specific files from [14 different tape image files](../main/tapeimagelist.txt) in the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Files are from ITS backup tapes. Most files are written in the Lisp programming language and were originally created on PDP-10 timeshare computers running the ITS operating system.

Files were extracted from the tape images using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, `LISPM; ED 126`, for example. All files have been placed into this artificial `eine` directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed in the `tapeimagelist.txt` file.

[7 files are ITS archive files](../main/ITSarchivefilelist.txt) within this extracted set. Digital Archivist, Joe Carrano, extracted the contents of these files into directories of the same name, one level up from their location using the [itsarc](https://github.com/larsbrinkhoff/pdp10-its-disassembler/blob/master/itsarc.c) program.
### [codemeta.json](../main/codemeta.json)
This file is metadata about the EINE files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE](../main/LICENSE)
This file describes the details about the rights to these files. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [eine](../main/eine) directory showing the original file timestamps as extracted from the tape images.
### [tapeimagelist.txt](../main/tapeimagelist.txt)
A list of all the tape images and their paths in the ToTS collection that these files came from.
### [ITSarchivefilelist.txt](../main/ITSarchivefilelist.txt)
A list of all the ITS archive files and their paths in this repo.
## Preferred Citation
[filename], EINE source code and files, 1975-1981, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:ebd75608d2ac37affde679d124999044214ea701](https://archive.softwareheritage.org/swh:1:dir:ebd75608d2ac37affde679d124999044214ea701)
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [GNU General Public License version 2](https://opensource.org/license/gpl-2-0). See the `LICENSE` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files.