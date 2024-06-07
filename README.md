# Downloading-of-NASA-PACE-Image-data-using-our-STS-Customized-HyperSpectral-Software
The Science and Technology Society (STS) of Sarasota-Manatee Counties, Florida have created a few Jupyter Notebooks used to download PACE data and then process and display this new PACE hyperspectral data available from NASA. 

Florida faces some stiff challenges in dealing the old problem of Red Tide (Karenia brevis). When this algal bloom drifts toward our shorelines, we have problems. Red Tide gives off a toxic vapor that attacks the lungs, kills the fish and other aquatic wildlife and have a huge negative impact on the economy and tourism. Red Tide has been around for millions of years, but what can we with our latest PACE technology to track and possibly the mitigate the impact now? Is it possible to identify and track these Harmful Algal Blooms (HAB) as an early warning system? STS and our citizen scientists would like to be a part of the solution.    

NASA has just launched a new satellite called PACE (Plankton, Aerosol, Cloud Ocean Ecosystem) with hyperspectral data that focuses on our ocean ecosystem and microscopic algae called phytoplankton including the Red Tide species. PACE is hyperspectral data in that each pixel in a PACE satellite image has 184 channels of spectral wavelength data from 339nm in the UV range to 719nm in the near red edge of the visible spectrum. This is a lot of data and is therefore stored in netCDF4 file format as .nc files downloaded from NASA [EarthData](https://urs.earthdata.nasa.gov/). We use Geospatial Solution's HyperCoast to download the PACE data. After the download, you can view individual channel data in maps or even view the wavelength spectrum for each pixel that you request. In addition, we can then use then use the hyperspectral data structure to calculate our own indices such as Chlorophyll a. Our goal is to be able to detect and track Red Tide algal blooms using PACE data. 

1) We have created a Jupyter Notebook so that you too can download PACE data using HyperCoast and then view and process the data in python.

![image1](chlor_a.png)


![image1](wavelength.png)

We also have included the original PACE Access Data notebook proposed from the Ocean Color Instrument (OCI).

**Authors:** Anna Windle (NASA, SSAI), Ian Carroll (NASA, UMBC), Carina Poulin (NASA, SSAI)

> **PREREQUISITES**
>
> This notebook has the following prerequisites:
> - An **<a href="https://urs.earthdata.nasa.gov/" target="_blank">Earthdata Login</a>**
>   account is required to access data from the NASA Earthdata system, including NASA ocean color data.
> - There are no prerequisite notebooks for this module.
