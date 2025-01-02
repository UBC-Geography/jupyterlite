# UBC Geography JupyterLite

This is a customized deployment of the
[JupyterLite Demo](https://jupyterlite.github.io/demo) with a specific focus
around the diverse computing needs of geographers.

You can learn more about JupyterLite and running JupyterLab entirely within a
browser [here](https://jupyterlite.readthedocs.io/en/stable/index.html).

This method for running JupyterLab is still experimental and many features
aren't available. For UBC researchers seeking a stable method for running
Jupyter on remote resources, review
[UBC Open Jupyter](https://open.jupyter.ubc.ca/jupyter/hub),
[UBC Syzygy](https://ubc.syzygy.ca/), or
[Alliance JupyterHub](https://docs.alliancecan.ca/wiki/JupyterHub).

## Supported Software

### Python

A Python kernel that's built on Pyodide 0.27.0, which includes:

- Python 3.12.7
- GDAL 3.8.3
- PROJ 9.3.1
- GEOS 3.12.1
- numpy 2.0.2
- geopandas 1.0.1
- matplotlib 3.8.4
- pandas 2.2.3
- pyproj 3.6.1
- rasterio 1.4.2
- scipy 1.14.1
- shapely 2.0.6
- xarray 2024.11.0
- and [more](https://pyodide.org/en/stable/usage/packages-in-pyodide.html)
- note: many pure Python packages can also be installed using
  [piplite.install()](https://jupyterlite.readthedocs.io/en/latest/howto/pyodide/packages.html)

### R

An R kernel that's built on webR 0.4.1, which includes:

- R 4.4.1
- note: R packages that are compatible with WebAssembly, many of which have
  already been compiled and hosted [here](https://repo.r-wasm.org/), can be
  installed using
  [webr::install()](https://docs.r-wasm.org/webr/latest/packages.html)

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
