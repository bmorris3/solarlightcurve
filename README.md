The Solar Benchmark: Rotational Modulation of the Sun Reconstructed from Archival Sunspot Records
===================

[![DOI](https://zenodo.org/badge/155757742.svg)](https://zenodo.org/badge/latestdoi/155757742) [![](http://img.shields.io/badge/arXiv-1901.04557-red.svg?style=flat)](https://arxiv.org/abs/1901.04557)


In this repository you'll find a file called `solar_lc.txt` which contains the solar light curve. To open it in python, try: 

```python
import numpy as np
jd, flux = np.loadtxt('solar_lc.txt', unpack=True)
```

