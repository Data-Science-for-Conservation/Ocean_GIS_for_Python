# Using GIS in Python with Wreck Data

Code and presentation for the NH Python meetup given December 2021. The project uses an MIT license, which covers everything except the materials in the `data` folder. Items there retain their original use licenses.


## Create a Virtual Environment to Run the Code Locally

To run the Jupyter notebook locally, you'll need to create an environment with all the necessary packages and their dependencies.

To run with [Anaconda](https://www.anaconda.com/):

```shell
conda env create --file environment.yml

# Activate the new environment
conda activate geo

# Launch Jupyter notebooks
jupyter notebook
```

The code was only tested within an Anaconda environment, but there is a `requirements.txt` file if you would prefer to create the environment using PIP. Navigate to the project directory, then run the following commands. The `conda` environment uses Python 3.8.

```shell
# Create a virtual environment named "geo" in the project folder
python3 -m venv geo

# Activate the environment
source geo/bin/activate

# Install the packages via the requirements.txt file
python3 -m pip install -r requirements.txt

# Launch Jupyter notebooks
jupyter notebook
```
