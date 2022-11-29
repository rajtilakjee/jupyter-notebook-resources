![Jupyter Notebook](./assets/jupyter-notebook.png)

![Open-Source](https://img.shields.io/badge/Open%20Source%20Initiative-3DA639.svg?style=for-the-badge&logo=Open-Source-Initiative&logoColor=white)

## Introduction

Jupyter Notebook is a part of [Project Jupyter](https://jupyter.org/). It is a web-based IDE which can be tried from your browser from the Project Jupyter website, and used after being installed locally. It offers an interactive, document-centric development environment, and can be used for creating and sharing computational documents. Jupyter Notebook supports 40+ programming languages including Python, Scala, R, and Julia.

The notebooks created using Jupyter Notebook can be shared via email, Dropbox, GitHub and the Jupyter Notebook Viewer. For producing rich interactive output, it supports HTML, images, videos, LaTeX, and custom MIME types. With the help of Jupyter Notebook you can utilize big data tools like Apache Spark, from Python, R, and Scala. You can also explore that same data with pandas, scikit-learn, ggplot2, and TensorFlow.

## Installation

Jupyter Notebook can be directly installed, or it can be installed as a part of Anaconda.

_Direct installation:_

`pip install notebook`

_Conda installation can be done through `conda-forge`:_

`conda install -c conda-forge jupyter`

## Open Jupyter Notebook

Open an Anaconda prompt and use the following command:

`jupyter notebook`

## Tips & Tricks

__Open from another drive__

`jupyter notebook --notebook-dir=NameOfTheDrive:`

__Open from another drive using a Batch file__

_Create a Batch file, name it `jupyter.bat`, and then insert the below script in the batch file and save it:_

```
@echo ON
title Launch Jupyter notebooks from Drive D
jupyter notebook --notebook-dir=D:
@echo OFF
```

__Embedding images__

`![title](img/picture.png)`

__Checking Python version__

`!python --version`

__Recover deleted cell__

Edit -> Undo Delete Cells

__Show line numbers__

View -> Toggle Line Numbers

__500: Internal Server Error__

_Upgrade Jupyter Hub:_

```
pip install --upgrade jupyterhub
pip install --upgrade --user nbconvert
```

_In case the above commands does not work:_

`pip install --upgrade nbconvert`

_From within `conda` environment:_

`conda install nbconvert==5.4.1`

__Run R and Python from the same Notebook__

`pip install rpy2`

_After rpy2 is installed, run the following code once in a cell:_

`%load_ext rpy2.ipython`

## Important links

- [Documentation](https://jupyter-notebook.readthedocs.io/en/latest/)
- [GitHub repository](https://github.com/jupyter/notebook)
- [Themes](https://github.com/dunovank/jupyter-themes)
- [Built-in Magic Commands](https://ipython.readthedocs.io/en/stable/interactive/magics.html)
- [nbconvert](https://nbconvert.readthedocs.io/) _For converting Notebooks into other formats._
- [Managing Conda Environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
- [Papermill](https://github.com/nteract/papermill) _Tool for parameterizing, executing, and analyzing Jupyter Notebooks._
- [nbparameterise](https://github.com/takluyver/nbparameterise) _Tool to run notebooks with input values._
- [nbclick](https://github.com/ssciwr/nbclick) _Turn Jupyter notebooks into command line applications._
- [Pydroid 3](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3&pli=1) _For installing Jupyter Notebook on Android._
- [Dash](https://github.com/plotly/jupyterlab-dash) _Extension for the Interactive development of Dash apps in JupyterLab._

## Jupyter Notebook Kernels

- [Rust](https://github.com/google/evcxr/blob/main/evcxr_jupyter)
- [Java](https://github.com/SpencerPark/IJava)
- [C++](https://github.com/jupyter-xeus/xeus-cling)
- [R](https://github.com/IRkernel/IRkernel)
- [Scala](https://github.com/almond-sh/almond)
- [Wolfram](https://github.com/WolframResearch/WolframLanguageForJupyter)
- [LFortran](https://github.com/lfortran/lfortran)
- [Elixir](https://github.com/pprzetacznik/IElixir)
- [C#](https://github.com/zabirauf/icsharp)
- [OCaml](https://github.com/akabe/ocaml-jupyter)
- [Stata](https://github.com/kylebarron/stata_kernel)
- [Scala & Spark](https://github.com/vericast/spylon-kernel)
- [Common Lisp](https://github.com/yitzchak/common-lisp-jupyter)
- [nim](https://github.com/stisa/jupyternim)
- [Lua](https://github.com/guysv/ilua)
- [kdb+](https://github.com/KxSystems/jupyterq)
- [Coq](https://github.com/EugeneLoy/coq_jupyter)
- [Elm](https://github.com/abingham/jupyter-elm-kernel)
- [Coarray Fortran](https://github.com/sourceryinstitute/jupyter-CAF-kernel)
- [Dyalog APL](https://github.com/Dyalog/dyalog-jupyter-kernel)
- [MongoDB](https://github.com/gusutabopb/imongo)
- [Swift](https://github.com/McJones/jupyter-swift-kernel)
- [GNU Guile Scheme](https://github.com/jerry40/guile-kernel)
- [ClickHouse](https://github.com/wangfenjin/xeus-clickhouse)
- [Fift & FunC](https://github.com/m-kus/xeus-fift)

## Contribution

This is an open-source project. We invite your participation through issues and pull requests! Please ensure that you follow the [contributing guidelines](CONTRIBUTING.md). Also, do go through out [code of conduct](CODE_OF_CONDUCT.md) guidelines for contributors.

## List of Contributors

![GitHub Contributors Image](https://contrib.rocks/image?repo=rajtilakjee/jupyter-notebook-resources)
