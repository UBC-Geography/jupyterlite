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

## Customizations

This deployment has been adapted to include the following:

- A Python kernel running from Pyodide's development release, which provides
  access to the popular geospatial package, rasterio.
- An R kernel running from R for WebAssembly's webR distribution.

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
