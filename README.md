# `pycontrails` Workshop

- **Date**: 2023 April 19 - 20
- **Location**: [Skempton Building, Imperial College London](https://goo.gl/maps/9oBGJ2eUwPj5GyuU7)
- [Agenda](https://drive.google.com/drive/folders/10-4j2nsayJnB5kUCkZkfyKBL7HwnrNIN)

## Presentations

> Add link to presentations

## Notebooks

The [Notebooks](notebooks) directory contain [Jupyter Notebooks](https://jupyter.org/) used in the workshop.

Notebooks reference data staged in [`gs://2023-04-pycontrails-workshop`](https://console.cloud.google.com/storage/browser/2023-04-pycontrails-workshop)

### Background

- [pycontrails Architecture]()
- [Geospatial Data](notebooks/01-Geospatial.ipynb)

### Tutorials

> ** Haven't started yet

- ** [CoCiP Flight](notebooks/03-CoCiP.ipynb): Run CoCiP along a flight trajectory
- [Aircraft performance](notebooks/03-Aircraft-Performance.ipynb): Calculate aircraft performance using [OpenAP](https://openap.dev/)
- ** [ADS-B Processing](03-ADSB-Processing.ipynb): Clean and filter ADS-B data before processing
- [Create GOES Tiles](notebooks/03-GOES-tiles.ipynb): Create map tiles from GOES imagery
- [Compare CoCiP outputs to GOES](notebooks/03-CoCiP-satellite.ipynb): Plot CoCiP contrail outputs on top of GOES imagery
- ** [Persistent contrail regions](notebooks/03-PCR.ipynb): Identify ice super-satured regions and regions that satisfy the Schmidt-Appleman criteria to calculate persistent contrail regions.

### References

> !! We could add individual example notebooks here (e.g. Flight), but I think its better to use something like `pycontrails-intro`) or we could just link out to them

- [`pycontrails` setup](notebooks/02-Setup.ipynb): Learn about pycontrails dependencies, installation, and setup. 
- [`pycontrails` examples](notebooks/02-Examples.ipynb): View examples of the core data classes.
- [`pycontrails` API](https://py.contrails.org/api.html): Python API documentation for `pycontrails`
- [Contrails API](https://apidocs.contrails.org/): REST API documentation for hosted `pycontrails` version


## Setup

The simplest way to get started is to use [Google Colab](https://colab.research.google.com/).
Colab enables notebooks to be run in the cloud without local installation.
