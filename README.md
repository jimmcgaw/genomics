# Genomics Libraries and Tools

I've noticed that people use Github repos to compile resource links around the web and to offer tutorials,
in addition to storing code.

I've been surveying libraries and tools that are used by programmers in the bioinformatics and genomics
disciplines as of late. I'll forget this knowledge unless I compile it someplace. This repo is intended
to document my own findings for myself, but perhaps someone else might find it useful.

I'm working on Mac OS X. When I have the option, I use Python. When I don't have the option, I learn things. :)

## Installation

I'm going to use [Anaconda](https://www.continuum.io/downloads) to manage Python dependencies for a change.
(I almost always use virtualenv, but this isn't as hip in scientific community.) Assuming you have Anaconda 
installed, you can quickly run the following from the project root:

``` $ conda env create -f environment.yml ```

## Libraries

* [ADAM](https://github.com/bigdatagenomics/adam)
* [GenomeAnalysisTK](https://software.broadinstitute.org/gatk/)
* [Picard](https://broadinstitute.github.io/picard/)
* [SAMTools](http://samtools.sourceforge.net/)
