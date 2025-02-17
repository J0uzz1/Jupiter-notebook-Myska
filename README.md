# FLOW ACCUMULATION - Water flow analysis in digital terrain model 
## **WARNING!**
**To make this Jupiter notebook work, you need to import the included conda environment enviroment_m.yml**
### How to import the Conda environment into your device:
1. **Download the environment file**
   Make sure you have received the `environment_m.yml` file.
2. **Open the command prompt**.
   Open the command prompt (console) on your device. If you have Anaconda Promt on your device use it.
3. **Go to the correct folder**
   Use the `cd` command to navigate to the folder where you saved the `environment.yml` file.
4. **Create a Conda environment**
   Run the following command to create a Conda environment from the saved file:
    ```
    conda env create -f environment.yml
    ```
    This command will install all necessary packages into the new Conda environment according to the specifications in the `environment.yml` file.
5. **Activate the new Conda environment**
   Activate the newly created Conda environment using the command:
    ```
    conda activate environment_name
    ```
    Where `environment name` is the name of the newly created Conda environment.
6. **Join the new environment**
   When creating a new laptop, select the newly created Conda environment from the kernel environment menu. If you installed the environment correctly, it should be available in your menu.

## Description: 
This project involves a script written in Python to analyze water flow in a digital elevation model (DEM) using the pysheds library. The project consists of several parts that include loading and processing the DEM, defining flow directions, calculating flow accumulation, visualizing the results, and other analyses. 
## Contents: 
- **FLOW_ACCUMULATION.ipynb**: Jupyter notebook containing the complete code for analyzing water flow in a digital terrain model.
- **dem1-3.tif**: Sample digital elevation model (DEM) files in GeoTIFF format used in the analysis.
- **enviroment_m.yml**: Conda environment required for proper functioning of the notebook.
## Libraries: 
numpy - pysheds.grid - matplotlib.pyplot - matplotlib.colors - matplotlib.patches - seaborn - rasterio 
## Running: 
To run the script, you must first have all the libraries used installed. Then you can run each cell in the Jupyter notebook in turn from the beginning, or selected parts of the code as needed. 
## Author: 
Josef Myška
## Contact: 
For any questions or comments you can contact myska-josef@seznam.cz.
## Notes: 
This project was created as součást předmětu PRODA a to jako semestrální práce. 
