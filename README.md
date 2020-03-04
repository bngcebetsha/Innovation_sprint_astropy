# Innovation sprint: Learning `astropy` package

Innovation sprint where I did as many `astropy` tutorials as I can.

The [Examples](https://docs.astropy.org/en/stable/generated/examples/index.html) are found here linked

## Example1 - [Convert RGB JPEG image into FITS using](https://docs.astropy.org/en/stable/generated/examples/io/split-jpeg-to-fits.html#sphx-glr-generated-examples-io-split-jpeg-to-fits-py)
  - [pillow](https://python-pillow.org)  for reading the image
  - `matplotlib.pyplot` to display
  - `astropy.io.fits` to save FITS files

## Example1 - [Determining and plotting atlaz coordinates of a celestial object](https://docs.astropy.org/en/stable/generated/examples/coordinates/plot_obs-planning.html#sphx-glr-generated-examples-coordinates-plot-obs-planning-py)
  - Use [SkyCoord](https://docs.astropy.org/en/stable/api/astropy.coordinates.SkyCoord.html#astropy.coordinates.SkyCoord) instance of an object to determine alt-az coordinates using `astropy.coordinates.EarthLocation` and `astropy.time.Time` objects.
  - For more convenient observation planning, see [astroplan](https://astroplan.readthedocs.io/en/latest/)
  
  ## Next I learned about convolution
  - Did an exercise on how to convolve a 1-D `sinc` function with 1) a 1-D `delta` function and with 2) a 1-D`gaussian` function.
  - Went to a 2-D case where I convolved 2-D `numpy arrays` to practice and better understand the concept.
  - An application of the above is on imaged data of two different surveys done with the VLA telescope
    - FIRST (high resolution)
    - NVSS (lower resolution)

An image of the same object in the two surveys looks very different, one would swear they are different objects. Even the flux density measurements of the two look look different. To correct for this, we use convolution. The differences are caused mainly by the difference in the resolution. If we make the resolutions the same, we could potentially make the two images close to being the same.

## [Astropy `Quantities` & `Units` for astrophysical calculations](http://learn.astropy.org/rst-tutorials/quantities.html?highlight=filtertutorials%20filterradioastronomy)
  - Here I use another useful package in `astropy` used to do calculations of physical quantities and interprete their physical meaning.
