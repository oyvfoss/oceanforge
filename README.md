<img src="misc/graphics/oceanforge_wide.png" alt="drawing" width="550"/>

*A collection of publicly-accessible Earth science datasets and how to access them remotely*
___

Here, we will collect some information about ocean, ice, and atmosphere datasets and how to access 
them remotely. The basic idea is to be able to get started with any of these datasets quickly
and avoid having to locate them every time.

Each entry should contain a short description of the dataset and a **Jupyter notebook** with an example 
of how to access the data remotely using **Python**.

Where possible, data are accessed using `xarray.open_dataset()`, which lazily loads the data without 
acually entering it into memory. In some cases we also use custom APIs such as `copernicusmarine` 
which may require a (free) user sign-up.

## DATASETS

<details>
<summary><strong>OCEAN MODELS AND REANALYSIS</strong></summary>

- **Barents 2.5** ice-ocean model: [ [Notebook](<datasets/ocean_models/barents_2_5/Accessing Barents 2.5 remotely.ipynb>) ] [[Static webpage](<datasets/ocean_models/barents_2_5/Accessing Barents 2.5 remotely.md>) ]

</details>

<details>
<summary><strong>ATMOSPHERE REANALYSIS</strong></summary>
</details>

<details>
<summary><strong>SEA ICE</strong></summary>

<details>
<summary> SEA ICE THICKNESS </summary>

- **SMOS L3 SIT** sea ice thickness: [ [Notebook](<datasets/sea_ice/sea_ice_thickness/SMOS_L3_SIT/SMOS sea ice thickness.ipynb>) ] [[Static webpage](<datasets/sea_ice/sea_ice_thickness/SMOS_L3_SIT/SMOS sea ice thickness.md>) ]
</details>

</details>

<details>
<summary><strong>OTHER</strong></summary>
</details>
