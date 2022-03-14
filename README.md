# README

## Overview
This repository contains a set of tutorials prepared for helping students get started analysing data using tools of the Python ecosystem.

Each tutorial is presented as an independent Python notebook: familiarity with Python is expected to follow them. We recommend to study the tutorials in the following order:


|     |  Notebook             | Google Colab   | Binder   |
| --- |:----------------------| -------------- | -------- |
| **1.**   | [NumPy](https://nbviewer.jupyter.org/github/airnandez/numpandas/blob/master/notebooks/NumPy.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/notebooks/NumPy.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=notebooks%2FNumPy.ipynb) |
| **2.**   | [pandas](https://nbviewer.jupyter.org/github/airnandez/numpandas/blob/master/notebooks/pandas.ipynb) |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/notebooks/pandas.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=notebooks%2Fpandas.ipynb) |
| **3.**   | [visualisation](https://nbviewer.jupyter.org/github/airnandez/numpandas/blob/master/notebooks/visualisation.ipynb)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/notebooks/visualisation.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=notebooks%2Fvisualisation.ipynb) |

You may also want to look at the exercises available in the `exam` directory:

| Notebook             | Google Colab   | Binder   |
|:---------------------| -------------- | -------- |
| [exercise 2019](https://github.com/airnandez/numpandas/blob/master/exam/2019-exam-with-answers.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/exam/2019-exam-with-answers.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=examp%2F2019-exam-with-answers.ipynb) |
| [exercise 2020](https://github.com/airnandez/numpandas/blob/master/exam/2020-exam-with-answers.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/exam/2020-exam-with-answers.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=examp%2F2020-exam-with-answers.ipynb) |
| [exercise 2021](https://github.com/airnandez/numpandas/blob/master/exam/2021-exam-with-answers.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/airnandez/numpandas/blob/master/exam/2021-exam-with-answers.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/airnandez/numpandas/master?filepath=examp%2F2021-exam-with-answers.ipynb) |


## How to run these notebooks in your computer

To run the notebooks of this repository on your own computer, you need a working Python environment which includes:

* [NumPy](https://www.numpy.org) 
* [pandas](https://pandas.pydata.org)
* [matplotlib](https://matplotlib.org)
* [bokeh](https://bokeh.pydata.org/en/latest/)
* [requests](https://requests.readthedocs.io)
* [Jupyter](https://jupyter.readthedocs.io/en/latest/#)

The notebooks were verified to work with Python v3.7 and should work with more recent versions. We **strongly recommend** to use the [Anaconda](https://www.anaconda.com/distribution/) distribution, which already includes all the packages needed to execute these notebooks.

To execute these notebooks in your own environment proceed as shown below:

```
$ git clone https://github.com/airnandez/numpandas.git
$ cd numpandas
$ jupyter lab
```

You will find the notebooks ready to run in the `notebooks` directory.

## Credits

### Author
This material was developed and is maintained by Fabio Hernandez at [IN2P3 / CNRS computing center](http://cc.in2p3.fr) (Lyon, France). 

It was originally intended for students of the [DU Data Scientist](https://www.uca.fr/formation/nos-formations/catalogue-des-formations/du-data-scientist) of the [Université Clermont-Auvergne](https://www.uca.fr) in France, but feel free to use it for other purposes as well.


## License
Copyright 2019-2022 Fabio Hernandez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
