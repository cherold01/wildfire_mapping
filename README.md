# Wildfire Mapping from remote sensing data

## Objective
Wildfire mapping from remote sensing data retrieved from the FIRMS API. The project focuses on producing an interactive map allowing custom user-inputs. 
Final project of the UZH course SDS210, spring semester 2026.

---------------------------------------------

## Data sources

Wildfire data: 
https://firms.modaps.eosdis.nasa.gov/api/

Countries dataset:
https://www.geoboundaries.org/globalDownloads.html -> ADM0 geoPackage

-----------------------------------------------

## Setup instructions:

1. Navigate to your desired directory
2. Run ```bash git clone https://github.com/cherold01/wildfire_mapping.git ```
3. Navigate into the newly created folder 'wildfire_mapping' containing the repository.
4. Ensure you have conda installed.
5. Run: `conda env create --name wildfire_env --file=environment.yml`
6. Activate environment: `conda activate wildfire-env`

## Usage

*Normal version of the notebook with intermediate outputs and documentation:*
Execute the notebook `front.ipynb`. Custom user inputs can be defined in the first cell. The output will open in your browser.

*Interactive version featuring a cleaner look and interactive elements for the user inputs:*
Execute the notebook `front_interactive.ipynb`. Custom user inputs can be defined in the first cell. The output will open in your browser.
The script running in the background is saved in the `scripts` folder. 

*Regenerate data/countries_simple.gpkg*
If for any reason you would want to regenerate this file, it can be done using the notebook `countries.ipynb`. Usually, this is not required.



Next steps: 

- fetch API data from https://firms.modaps.eosdis.nasa.gov/api/
