# 4EU+ seminar 09/2022 
---

This is a repository of code for EU+ seminar on Machine Learning for Geoscientis. 


**1. Software requirements**

  - Python3 (3.6+)
  - Interactive Python and Jupyter Notebook
  - Python packages: iPython, Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, Gdal-Python (optionally) 
  
For more details see: https://github.com/lbrodsky/4eu_seminar/blob/main/requirements.txt 

**2. Installation istructions:**
I suppose most of the users would uses Windows. There is not one universal way. I try to discribe the most straitforward one.

  - Python3 https://www.python.org/download/releases/3.0/
  - Or Python from Anaconda https://www.anaconda.com

install e.g. Python 3.9 application (or higher version if you like): 
```
> python-3.9.2-amd64.exe
```
**Be aware!!!**
set pip yes
set add python to environment variables!!!

Run 'Command line': cmd / run
test pip
```
> pip
```

Run Python (I suppose, Python3 executable  is sym-linked to simple 'python'. It used to be python3 before.)
```
> pyhton
```

Check python version (only information) 
```
>>> import sys
>>> sys.version
```

Install Python package: 
```
>pip install numpy
```
Do the saem for other packages: ipython, numpy, pandas, matplotlib, seaborn, scikit-learn

Test if matplotlib is working: 
```
> python
>>> import matplotlib.pyplot as plt
>>> plt.plot([1,2,3], [3,6,9])
>>>plt.show()
```

Install Jupyter notebook

```
python -m pip install jupyter
```

Run jupyter notebook: 
```
jupyter notebook
```

Hope everything runs smooths and you see Jupyter environment in your web browser. 

![Jupyter notebook](https://github.com/lbrodsky/4eu_seminar/blob/main/figs/jupyter.png?raw=true "Jupyter notebook")

Open New notebook and test it! 

- running cells (Ctrl + Enter / Shift + Enter / menu) 
- adding cell (+) 
- adding rich content (Markdown) 
- code and syntax highlighting: 
```
print('hello') 
# do more on your own
```

Test Matplotlib plotting inline! 
```
import matplotlib.pyplot as plt
% matplotlib inline
```

Ok, so far :-) 



