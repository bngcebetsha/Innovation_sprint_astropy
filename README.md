# Innovation_sprint_astropy

Innovation sprint where I did as many `astropy` tutorials as I can.

The [Examples](https://docs.astropy.org/en/stable/generated/examples/index.html) are found here linked

## Example1 - [Convert RGB JPEG image into FITS using](https://docs.astropy.org/en/stable/generated/examples/io/split-jpeg-to-fits.html#sphx-glr-generated-examples-io-split-jpeg-to-fits-py)
  - [pillow](https://python-pillow.org)  for reading the image
  - `matplotlib.pyplot` to display
  - `astropy.io.fits` to save FITS files

## Example1 - [Determining and plotting atlaz coordinates of a celestial object](https://docs.astropy.org/en/stable/generated/examples/coordinates/plot_obs-planning.html#sphx-glr-generated-examples-coordinates-plot-obs-planning-py)
  - Use [SkyCoord](https://docs.astropy.org/en/stable/api/astropy.coordinates.SkyCoord.html#astropy.coordinates.SkyCoord) instance of an object to determine alt-az coordinates using `astropy.coordinates.EarthLocation` and `astropy.time.Time` objects.
  - For more convenient observation planning, see [astroplan](https://astroplan.readthedocs.io/en/latest/)
  