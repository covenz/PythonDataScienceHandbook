# Python Data Science Handbook
#Python数据科学手册

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

![cover image](notebooks/figures/PDSH-cover.png)

## How to Use this Book
##如何使用这本书

- Read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/
-这本书可以在这个网址看到所有电子版：https://jakevdp.github.io/PythonDataScienceHandbook/
- Run the code using the Jupyter notebooks available in this repository's [notebooks](notebooks) directory.
-在Jupyter上跑一跑Notebooks库里的所有的代码。
- Launch executable versions of these notebooks using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)
-
- Launch a live notebook server with these notebooks using [binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)

- Buy the printed book through [O'Reilly Media](http://shop.oreilly.com/product/0636920034919.do)
-在[O'Reilly Media](http://shop.oreilly.com/product/0636920034919.do可以买到印刷版本
## About
##关于本书
The book was written and tested with Python 3.5, though other Python versions (including Python 2.7) should work in nearly all cases.
这本书基于Python3.5测试与编写，但其他版本的Python（比如2.7）也可以跑通几乎所有的代码案例。
The book introduces the core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and related packages.

Familiarity with Python as a language is assumed; if you need a quick introduction to the language itself, see the free companion project,
[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): it's a fast-paced introduction to the Python language aimed at researchers and scientists.

See [Index.ipynb](http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb) for an index of the notebooks available to accompany the text.

## Software
##软件
The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.
本书的代码基于Python3.5测试，但其他版本的Python（比如2.7）也可以跑通几乎所有的代码案例。
The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).

To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:
为安装
```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.


## License

### Code
The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text
The text content of the book is released under the [CC-BY-NC-ND license](LICENSE-TEXT). Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).
