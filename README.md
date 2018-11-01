The Solar Benchmark: Rotational Modulation of the Sun Reconstructed from Archival Sunspot Records
===================

In this repository you'll find a file called `solar_lc.txt` which contains the solar light curve. To open it in python, try: 

```python
import numpy as np
jd, flux = np.loadtxt('solar_lc.txt', unpack=True)
```

