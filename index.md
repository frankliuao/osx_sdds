# Python API for SDDS

### Python Library for SDDS, written by ANL:
[Official webpage](https://www.aps.anl.gov/Accelerator-Operations-Physics/Software)

<hr>

### Usage
- Locate the **site-packages/** directory for your Python environment.
  * For the anaconda (conda) default environment (base), it would be in **~/anaconda3/lib/python3.7/site-packages/**
  * For an anaconda user-created environment, it would be in **~/.conda/envs/ENVNAME/lib/python3.7/site-packages/**, where **ENVNAME** is the name of the environment you created.
  * For the system Python, such as the version installed by the third-party package manager such as MacPorts, you may find it by importing a module in Python and printing its **\_\_path__** variable:
    ```Python
       >>> import numpy
       >>> print(numpy.__path__)
       '/opt/local/Library/Frameworks/Python.framework/Versions/3.7/lib/python3.7/site-packages/numpy'
    ```
- Next, put this folder in that path. Using the anaconda default environment (base) as an example, it would be: **~/anaconda3/lib/python3.7/site-packages/sdds/**
- Open Python prompt (or a Jupyter Notebook) anywhere, try to import sdds and use the SDDS class:
  ```Python
     >>> import sdds
     >>> sdds.SDDS(0)
  ```
- Success!
