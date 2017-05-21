# Download arxiv publications.
by jaggz.h who is at gmail  
2017-05-12

## Downloads the abstract, pdf, and HTTP headers.
The HTTP headers contain X-Meta-Citation information, including the authors'
names, citation date, etc.

## Installation:
1. Place file arxiv-dl somewhere runnable
2. Edit {HOME}/.config/arxiv-dlrc and set libdir to the folder in which to
   store the downloaded documents.
   * They are currently stored single-level (all in the libdir)
   * An example arxiv-dlrc is included

## Usage/examples:
```
arxiv-dl https://arxiv.org/abs/whatever
arxiv-dl https://arxiv.org/pdf/whatever
```
(The script will automatically substitute pdf with abs as needed).
