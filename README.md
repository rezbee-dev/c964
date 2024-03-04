# C964 Project

## Dataset source
- [Kaggle](https://www.kaggle.com/datasets/xiaomengsun/car-insurance-claim-data)

## How to Run

### Using the notebook
- Click on `Run > Run all cells`
  - ![image](https://github.com/rezbee-dev/c964/assets/131298724/2db1f9aa-81f3-4e3f-b27b-99b922c7d813)
- Wait for cells to run (it may take a few seconds)
- Scroll to the bottom of the page
- Interact with the application by entering in data, or pressing "Simulate" to prepopulate data
- Click "Predict" to run machine learning model on the data
  - ![image](https://github.com/rezbee-dev/c964/assets/131298724/a4175e48-4d74-4ce7-96b5-1227881472f4)

### Running in Binder
- Navigate to https://mybinder.org/v2/gh/rezbee-dev/c964/HEAD
- Wait for build process to finish (it may take a few minutes)
- Open `part_c.ipynb` file
  - ![image](https://github.com/rezbee-dev/c964/assets/131298724/572d59ae-cd29-4a56-aa80-f5615741a872)

### Running in local environment
- Install latest version of python
- Download the following files from this repository
  -  `requirements.txt`
  -  `data/dataset.csv`
  -  `data/dataset_not_encoded.csv`
  -  `part_c.ipynb`
-  Create virtual env folder: `python -m venv .venv`
-  Activate virtual env
   - Linux:  `source .venv/bin/activate`
   - Windows: `.venv\Scripts\activate`
- Install packages: `pip install -r requirements.txt`
  - Alternatively (if on Windows), run the following
    - `pip install notebook`
    - `pip install ipywidgets`
    - `pip install seaborn`
    - `pip install scikit-learn`
- Start jupyter notebook: `jupyter notebook`
- Navigate to URL notebook is running on
