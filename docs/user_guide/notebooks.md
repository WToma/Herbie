# 📝 Jupyter Notebooks

These notebooks show practical use case of the `hrrrb` package:

- [Main Package Examples](https://github.com/blaylockbk/Herbie/blob/master/notebooks/examples.ipynb)
- [Make Cartopy maps with HRRR data](https://github.com/blaylockbk/Herbie/blob/master/notebooks/demo_plot-on-map-with-common-features.ipynb)

**Zarr:** Select parts of the HRRR archive are available in [Zarr](https://zarr.readthedocs.io/en/stable/) format in the `s3://hrrrzarr` bucket on AWS developed by [Taylor Gowan](https://twitter.com/tayloragowan) and managed by the MesoWest group at the University of Utah. To get started check out these notebooks:

- [Taylor Gowan: HRRR-Zarr examples](https://github.com/taylorgowan/zarr)
- [Kevin Tyle: HRRR-Zarr AMS Short Course](https://github.com/ktyle/python_pangeo_ams2021/blob/main/notebooks/03_Pangeo_HRRR.ipynb)

I haven't added Zarr functionality into `hrrrb`, but I started to explore the capability. Here is my sandbox notebook...
- [Brian Blaylock: HRRR-Zarr sandbox](https://github.com/blaylockbk/Herbie/blob/master/notebooks/zarr_HRRR.ipynb)

---

The following notebooks offer a deeper discussion on how the GRIB2 download process works. These are not intended for practical use, but should help illustrate my thought process when I created the `hrrrb` package.

- [Part 1: How to download a bunch of HRRR grib2 files (full file)](https://github.com/blaylockbk/Herbie/blob/master/notebooks/demo_download_hrrr_archive_part1.ipynb)
- [Part 2: How to download a subset of variables from a HRRR file](https://github.com/blaylockbk/Herbie/blob/master/notebooks/demo_download_hrrr_archive_part2.ipynb)
- [Part 3: A function that can download many full files, or subset of files](https://github.com/blaylockbk/Herbie/blob/master/notebooks/demo_download_hrrr_archive_part3.ipynb)
- [Part 4: Opening GRIB2 files in Python with xarray and cfgrib](https://github.com/blaylockbk/Herbie/blob/master/notebooks/demo_download_hrrr_archive_part4.ipynb)



[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/blaylockbk/Herbie/master)