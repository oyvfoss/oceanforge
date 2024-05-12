<img src="misc/graphics/oceanforge_wide.png" alt="drawing" width="550"/>

*A collection of publicly-accessible Earth science datasets and how to access them remotely*
___

Here, we will collect some information about ocean, ice, and atmosphere datasets and how to access 
them remotely. The basic idea is to be able to get started with any of these datasets quickly
and avoid having to locate them every time.

Each entry should contain a short description of the dataset and a **Jupyter notebook** with an example 
of how to access the data remotely using **Python**.

Where possible, data are accessed using `xarray.open_dataset()`, which lazily loads the data without 
acually entering it into memory. In some cases we also use custom APIs such as `copernicusmarine` / `earthaccess` / `cdsapi` 
which may require a (free) user sign-up.

In addition, I may add some recipies for working with large gridded datasets.

## DATASETS

<details>
<summary><strong>OCEAN MODELS AND REANALYSES</strong></summary>

- **Copernicus global ocean reanalysis**: [ [Notebook](<datasets/ocean_models/copernicus_global_ocean/Copernicus Marine global ocean reanalysis product.ipynb>) ] 

- **TOPAZ 4b Arctic and North Atlantic model** [ [Notebook](<datasets/ocean_models/TOPAZ4b/TOPAZ 4b Arctic model.ipynb>) ]

- ECCO?

- ORA S5?

- **Barents 2.5** ice-ocean model: [ [Notebook](<datasets/ocean_models/barents_2_5/Accessing Barents 2.5 remotely.ipynb>) ] 

</details>

<details>
<summary><strong>ATMOSPHERE REANALYSIS</strong></summary>

- **ERA5** atmospheric reanalysis: [ [Notebook](<datasets/atmo_reanalysis/era5/ERA5.ipynb>) ] 
- CARRA - Not available remotely.  

</details>



<details>
<summary><strong>SEA ICE</strong></summary>

<details>
<summary> SEA ICE CONCENTRATION </summary>

- **Bremen AMSR2** - Not available remotely 
- **NSIDC**
- **Met/Copernicus**

</details>

<details>
<summary> SEA ICE DRIFT </summary>

- **NSIDC** - Not available remotely (monthly available [here](https://icdc.cen.uni-hamburg.de/thredds/dodsC/icedrift_nh.html))
- **Met/Copernicus**

</details>

<details>
<summary> SEA ICE THICKNESS </summary>

- **SMOS L3 SIT** sea ice thickness: [ [Notebook](<datasets/sea_ice/sea_ice_thickness/SMOS_L3_SIT/SMOS sea ice thickness.ipynb>) ] 

</details>

<details>
<summary> SEA ICE AGE </summary>

- **NSIDC**

</details>
</details>


<details>
<summary><strong>OCEAN SURFACE FROM REMOTE SENSING</strong></summary>

<details>
<summary>SEA SURFACE TEMPERATURE</summary>

- **NOAA OI SST V2** sea surface temperature: [ [Notebook](<datasets/ocean_surface_remote_sensing/oi_sst_v2/oiSST v2.ipynb>) ] 

</details>

<details>
<summary>SEA SURFACE HEIGHT</summary>

</details>

<details>
<summary>SEA SURFACE SALINITY</summary>

</details>

<details>
<summary>OCEAN COLOUR</summary>

</details>

</details>

<details>
<summary><strong>OTHER</strong></summary>

- Runoff
- Climatologies
- Waves
- Climate model forecasts
- Bathymetry

</details>


#### APIs

## RECIPIES FOR WORKING WITH GRIDDED GEOSPATIAL DATA *(TBW*)

Want to incude some recipies for common methods  like:

- Extracting spatial and temporal subsets.
- Regridding from one lat/lon grid to another.
- Interpolating onto a single-depth surface from a model grid with variable *z*-coordinates.
- Parallelizing tasks with `dask`.
- Computing gradient and curl.








