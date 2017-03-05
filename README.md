# **INSTALL**

Make sure you follow the installation
[instructions](https://github.com/pkoukos/grcarma/blob/master/INSTALL.md).

# **Support**

You can always submit your questions/bug reports etc. and receive mailing list support through [this google group](http://groups.google.com/group/carma-molecular-dynamics "Carma Mailing List").

# **NAME**

grcarma - GUI to molecular dynamics trajectories analysis program carma

# **SYNOPSIS**

grcarma [ PSF FILE ] [ DCD FILE ]

grcarma.exe [ PSF FILE ] [ DCD FILE ]

# **DESCRIPTION**

A paper describing the program in greater detail is available from
[JCC](http://dx.doi.org/10.1002/jcc.23381). 

grcarma is a GUI to molecular dynamics trajectories analysis program 
[carma](http://utopia.duth.gr/~glykos/Carma.html). It is written in 
Perl and makes use of the Tk module for graphics. It is available for 
Linux, MACOSX and Windows, and requires the carma executable in the same folder 
( or in the PATH ). As seen in the synopsis the program can be launched 
with  a .psf / .dcd pair of files as arguments. Alternatively, the 
program can be run without any arguments and the user will be prompted
to specify the files to use for the analyses, through a graphical interface.

Versions >= 0.2 directly interface with the programs [GoodTuringMD](https://github.com/pkoukos/GoodTuringMD) and [cluster5D](https://github.com/athbaltzis/cluster5D).

# **AUTHOR**

grcarma has been developed by Panagiotis Koukos, under the supervision of 
[Prof. Nicholas M. Glykos](http://utopia.duth.gr/~glykos/) at the 
[Department of Molecular Biology and Genetics](http://mbg.duth.gr/index.php/en/)
of [Democritus University of Thrace](http://duth.gr/index.en.shtml).

# **LICENCE**

Copyright (c) 2012 - 2017, Panagiotis I. Koukos

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met: 

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer. 
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
