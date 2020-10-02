# microns_phase3_nda
nda schema for MICrONS phase3

# Installation Instructions
This package requires the em_coregistration package from the Allen Institute:

```bash
pip3 install git+https://github.com/AllenInstitute/em_coregistration.git@phase3
```

Install this package:

```bash
pip3 install git+https://github.com/cajal/microns_phase3_nda.git
```

In a jupyter notebook:

```python
from phase3 import nda, func, utils
```

Import datajoint. Configuration instructions: https://docs.datajoint.io/python/setup/01-Install-and-Connect.html

```python
import datajoint as dj
```

View schema:
```python
dj.ERD(nda)
```

![nda](images/nda_erd.png)