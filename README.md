# JupyterLab Fasta Viewer

A JupyterLab extension for viewing
[Fasta](https://en.wikipedia.org/wiki/FASTA_format) information. A file renderer
for files with `.fasta` extensions and a mime renderer for the
`application/vnd.fasta.fasta` mimetype is included. This extension uses the
[MSA Fasta viewer](http://msa.biojs.net/).

## Prerequisites

* JupyterLab

## Installation

Clone this repo into a directory (say jupyterlab-fasta), and then do

```bash
jupyter labextension install ./jupyterlab-fasta
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
