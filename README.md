[![arXiv](http://img.shields.io/badge/cs.LG-arXiv%3A1902.11122-B31B1B.svg)](https://arxiv.org/abs/1902.11122)
[![citation](http://img.shields.io/badge/citation-0091FF.svg)](https://scholar.google.com/scholar?q=Deep%20Learning%20in%20Cardiology.%20arXiv%202019)
[![template](http://img.shields.io/badge/template-EEE0B1.svg)](https://github.com/pbizopoulos/a-makefile-for-developing-containerized-latex-technical-documents-template)
[![test-document](https://github.com/pbizopoulos/deep-learning-in-cardiology/workflows/test-document/badge.svg)](https://github.com/pbizopoulos/deep-learning-in-cardiology/actions?query=workflow%3Atest-document)

# Deep Learning in Cardiology
This repository contains the code that generates **Deep Learning in Cardiology**.

## Requirements
- [POSIX-oriented operating system](https://en.wikipedia.org/wiki/POSIX#POSIX-oriented_operating_systems)
- [Docker](https://docs.docker.com/get-docker/)
- [Make](https://www.gnu.org/software/make/)

## Instructions
1. `git clone https://github.com/pbizopoulos/deep-learning-in-cardiology`
2. `cd deep-learning-in-cardiology/`
3. `sudo systemctl start docker`
4. make options
    * `make`             # Generate the document.
    * `make clean`       # Remove the tmp/ directory.
