# Playing with VLA data for FRB121102

This repository contains computational notebooks with analysis related to the repeating fast radio burst FRB121102.

## Requirements
To view the analysis (warts and all!), you can simply load the Jupyter notebooks or view them on github. The best starting place is [demo_FRB121102.ipynb](https://github.com/caseyjlaw/FRB121102/blob/master/demo_FRB121102.ipynb). The notebooks named "candidate_*.ipynb" are more directly related to analysis presented in publications, but are not as well documented.

To reproduce the analysis presented in the publication, you need [rtpipe](https://github.com/caseyjlaw/rtpipe), a Python library for analyzing millisecond interferometric data (particularly from the [Very Large Array](https://science.nrao.edu/facilities/vla)). Instructions for installation are given on github, but in short you need:

- [Anaconda installer](https://www.continuum.io/downloads)
- rtpipe dependencies via anaconda
- `pip install rtpipe`
