# Playing with VLA data for the Fast Radio Burst FRB 121102
## Fast radio interferometric imaging with rtpipe

This repository contains computational (Jupyter) notebooks with reproduction analysis for the manuscript "The direct localization of a fast radio burst and its host" (http://dx.doi.org/10.1038/nature20797). The data consist of visibilities and calibration files from the Very Large Array for nine radio bursts from the repeating Fast Radio Burst FRB 121102.

The notebooks here present the latest snapshot of the analysis presented in and in support of our publications. They can be viewed with the Jupyter notebook viewer or directly on github. To reproduce (and improve!) the analysis, follow the steps below.

## Requirements
...

The best starting place is [demo_FRB121102.ipynb](https://github.com/caseyjlaw/FRB121102/blob/master/demo_FRB121102.ipynb). The notebooks named "candidate_*.ipynb" are more directly related to analysis presented in publications, but are not as well documented.

To reproduce the analysis presented in the publication, you need [rtpipe](https://github.com/caseyjlaw/rtpipe), a Python library for analyzing millisecond interferometric data (particularly from the [Very Large Array](https://science.nrao.edu/facilities/vla)). Instructions for installation are given on github, but in short you need:

... data via the Harvard Dataverse at http://dx.doi.org/10.7910/DVN/TLDKXG.

- [Anaconda installer](https://www.continuum.io/downloads)
- rtpipe dependencies via anaconda
- `pip install rtpipe`
