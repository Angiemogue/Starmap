# Starmap

This repository contains a Jupyter Notebook developed for the Computational Techniques course in the Astrophyisics Master in the University of La Laguna.  It analyzes astronomical data from Hipparcos and Gaia using ADQL, and then uses this data to create a star map centered on a specific location in right ascension and declination.

![Image](https://github.com/user-attachments/assets/25877856-13fa-4389-a2af-1d5a1363e91b)

The code uses several utilities from the Astropy module. When generating the star map, you can optionally highlight the position of constellations and choose which ones to display.  
To do this, check the Astropy documentation on `get_constellation` for valid names you can use:

👉 [Astropy: get_constellation](https://docs.astropy.org/en/stable/api/astropy.coordinates.get_constellation.html)

You can also customize the sky region by modifying the coordinates in the code.

<p align="center">
  <img width="389" height="45" alt="Coordinates Input" src="https://github.com/user-attachments/assets/3247760e-970a-42ab-ac08-c8162a6426c8" />
</p>


> The star maps generated represent the sky in **right ascension and declination coordinates**.  
> For more interactive or alternative maps, you can explore tools like [StarPlot](https://starplot.dev/) — a complete, free, and easy-to-use resource.

> ⚠️ **Execution Warning**  
> It is recommended to run all notebook cells sequentially to avoid runtime issues or errors.

<p align="center">
  <img width="630" height="470" alt="Example 1" src="https://github.com/user-attachments/assets/bc3e02ad-8ddb-4cc2-a997-db58d97d3549" />
</p>

<p align="center">
  <img width="1000" height="709" alt="Example 2" src="https://github.com/user-attachments/assets/c31aeb16-915a-4e77-944e-49f67fb50615" />
</p>






