# Convert TPCM data to CARA supported format Jupyter Notebook

`Version 1.0`

This is a Jupyter Notebook created by the TPCM team that will convert a TPCM dataset (.xls) to a [CARA](https://apps.fs.usda.gov/pals/) supported dataset (.csv). 

## Getting Started

These instructions will get you a copy of the Jupyter Notebook up and running on your machine.

### Prerequisites

- `ArcGIS Online Account with ArcGIS Pro License`
- `ArcGIS Pro 2.4.1 or above`
- `usaddress python module`
- `TPCM project comments in .xls format`
- `CARA access`

### Installing python modules to a new ArcGIS Pro Python environment

If you have not created a new python environment or have not installed `usaddress` read these instructions before going to deployment.

1. Open ArcGIS Pro.

2. Open a new project.

3. Create a new environment for installing packages. Click Project > Python > Manage Environments. Inside manage environments click the image of two dashed boxes below clone next to arcgispro-py3 to clone the default environment. Name the environment `tpcmpro-env`.

5. Open your Windows Start Menu and type `python command prompt`. Open the Python Command Prompt.

6. Inside of the Python Command Prompt type `activate tpcmpro-env` and hit enter. *Note in later versions of Conda you may need to type `conda activate`.*

7. Once the environment is activated type `pip install usaddress` and hit enter.

You now have an environment with usaddress installed and are ready to run the Jupyter Notebook.

### Deployment

1. Download repository as a zip file.

2. Unzip the repository. Move your TPCM dataset to the unzipped repository. Rename your comment file to `TPCM_Comments.xls`.

3. Open your Windows Start Menu and type `python command prompt`. Open the Python Command Prompt.

4. Make sure you are inside of the environment that has usaddress installed; the environment name will be before the current working directory path. If you are not in the python environment type `activate tpcmpro-env` (or the name of your environment). *Note in later versions of Conda you may need to type `conda activate`.*

5. Change working directories, type `cd \` and hit enter.

6. Open Jupyter Notebook, type `Jupyter-Notebook` and hit enter.

7. Inside of Jupyter Notebook browse to the location of the repository and open `TPCM-to-Cara.ipynb`

8. Run each cell in the Jupyter Notebook. When each cell has completed you will have a CSV inside of your repository ready to be uploaded to CARA.

## Built with

- Jupyter-Notebook
- usaddress

## Authors

- Zachary Neumann

## Disclaimer

The USDA Forest Service makes no warranty, expressed or implied, including the warranties of merchantability and fitness for a particular purpose, and assumes no legal liability or responsibility for the accuracy, reliability, completeness or utility of these geospatial data, or for the improper or incorrect use of these geospatial data. These geospatial data and related maps or graphics are not legal documents and are not intended to be used as such. The data and maps may not be used to determine title, ownership, legal descriptions or boundaries, legal jurisdiction, or restrictions that may be in place on either public or private land. Natural hazards may or may not be depicted on the data and maps, and land users should exercise due caution. The data are dynamic and may change over time. The user is responsible to verify the limitations of the geospatial data and to use the data accordingly.
