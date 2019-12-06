# Download arxiv publications.
by jaggz.h who is at gmail  
2017-05-12

## Downloads the abstract, pdf, HTTP headers, and author's source .bin
## Extracts the bubbly goodness (usually a LaTeX setup)
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

arxiv-dl https://arxiv.org/abs/whatever -s # Get and extract the source
```
(The script will automatically substitute pdf with abs as needed).
