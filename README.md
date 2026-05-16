# The ZPIC educational code suite

## Student Codespaces launch

Use this Microsoft/GitHub Codespaces link for the class notebook environment:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/terryp532/zpic?quickstart=1)

After the Codespace opens, start with `python/notebooks/README.ipynb`.

Particle-in-Cell (PIC) codes are used in almost all areas of plasma physics, such as fusion energy research, plasma accelerators, space physics, ion propulsion, and plasma processing, and many other areas. Leveraging on our expertise and experience from the development and use of the OSIRIS PIC code, we have developed a suite of 1D/2D fully relativistic electromagnetic PIC codes, as well as 1D electrostatic. These codes are self-contained and require only a standard laptop/desktop computer with a C compiler to be run. The output files are written in a new file format called ZDF that can be easily read using the supplied routines in a number of languages, such as Python, and IDL. The code suite also includes a number of example problems that can be used to illustrate several textbook and advanced plasma mechanisms, including instructions for parameter space exploration. We also invite contributions to this repository of test problems that will be made freely available to the community provided the input files comply with the format defined by the ZPIC team.

The directory structure is organized as follows:
* [**em1d**](https://github.com/zambzamb/zpic/tree/master/em1d) - 1D electromagnetic (finite difference)
* [**em1ds**](https://github.com/zambzamb/zpic/tree/master/em1ds) - 1D electromagnetic (spectral)
* [**em2d**](https://github.com/zambzamb/zpic/tree/master/em2d)  - 2D electromagnetic (finite difference)
* [**em2ds**](https://github.com/zambzamb/zpic/tree/master/em2ds) - 2D electromagnetic (spectral)
* [**es1d**](https://github.com/zambzamb/zpic/tree/master/es1d)  - 1D electrostatic
* [**python**](https://github.com/zambzamb/zpic/tree/master/python)  - Python interface to ZPIC codes

## Documentation

The project now has its own dedicated website on GitHub pages. You can find all the documentation at [https://zpic-plasma.github.io](https://zpic-plasma.github.io)

## Try ZPIC now

For a Microsoft-hosted classroom environment, use GitHub Codespaces:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/terryp532/zpic?quickstart=1)

Binder may also work when public capacity is available:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/terryp532/zpic/HEAD?labpath=python%2Fnotebooks%2FREADME.ipynb)

