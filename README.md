# exSpy demos

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hyperspy/exspy-demos/main)
[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](http://nbviewer.ipython.org/github/hyperspy/exspy-demos/tree/main/)
[![Documentation Status](https://readthedocs.org/projects/exspy/badge/?version=latest)](https://exspy.readthedocs.io/en/latest/?badge=latest)

## Introduction

This repository contains [Jupyter Notebooks](https://jupyter.org/) to demo and learn
how to process electron energy loss spectroscopy (EELS) and X-ray energy dispersive spectroscopy (EDS)
with [exSpy](https://hyperspy.org/exspy). For learning purposes, we recommend to use them alongside the 
[exSpy User Guide](https://hyperspy.org/exspy).

*exSpy* uses the HyperSpy framework and to learn about generic functionalities of [HyperSpy](https://hyperspy.org),
see the [HyperSpy user guide](http://hyperspy.org/hyperspy-doc/current/index.html) and the [HyperSpy demos](https://github.com/hyperspy/hyperspy-demos).

## Visualising and running the demos.

### (Interactive) Running the demos online

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hyperspy/exspy-demos/main)

Follow [this link](https://mybinder.org/v2/gh/hyperspy/exspy-demos/main)
or click the "launch binder" banner above to run the the demos on 
[mybinder.org](https://mybinder.org/). The demos will run remotely, 
and one can experiment with HyperSpy in a Jupyter notebook with no need 
to install or configure any software locally.

**Note:** depending on the remote server load, the interactive binder demo may 
take up to several minutes to load. For a quicker (but non-interactive) 
visualization, see below.

### (Non-interactive) Visualizing the demos online

[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](http://nbviewer.ipython.org/github/hyperspy/exspy-demos/tree/main/)

Follow [this link](http://nbviewer.ipython.org/github/hyperspy/exspy-demos/tree/main/) 
or click on the "render nbviewer" banner above
to display the demos with the 
[Jupyter Notebook viewer](http://nbviewer.jupyter.org). 
[nbviewer](http://nbviewer.jupyter.org/) will allow you to view the notebooks online,
but you will not be able to change them or evaluate any code, like is possible with the 
[binder](https://mybinder.org/v2/gh/hyperspy/exspy-demos/main).

### Running and visualizing the demos locally

To run the demo notebooks locally, 
clone or download the [demos repository](https://github.com/hyperspy/exspy-demos) 
to your local
machine, install HyperSpy and
[Jupyter Lab](http://jupyterlab.readthedocs.io/en/latest/) or 
[Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/)
and use either of Jupyter tools to run the notebooks.


#### (For developers) Testing the demos locally

To test the demos, install
[nbval](http://github.com/computationalmodelling/nbval) and
[pytest](https://pytest.org/) and run

```bash
$ pytest
```

To help visualize differences/errors, install
[nbdime](http://github.com/jupyter/nbdime) as well, and run the test with

```bash
$ pytest --nbdime
```

## Contributing

To contribute new demos or improvements to the current ones fork the demos
repository and send us a pull request. See the 
[HyperSpy Developer Guide](http://hyperspy.org/hyperspy-doc/current/dev_guide.html) 
for more details on how to contribute to HyperSpy.

For issues and discussions fill a new
issue in [the demos github repository](https://github.com/hyperspy/exspy-demos)
or discuss it in [HyperSpy's gitter chat](https://gitter.im/hyperspy/hyperspy).



