[//]: # (Image References)

[image1]: (data/dataset-cover.jpg) "dataset-cover"

# Project: Honey price prediction using regression methods

![dataset-cover][image1]


## Setup Instructions

### Repository Setup

Clone the course repository and set up the Python environment:

```bash
# Clone the required repositories
git clone https://github.com/Yoshiokha/Predict_Price_of_Honey_Regression/Project2_Continuous_Control.git

# Navigate to the project directory
cd Project2_Continuous_Control

# Create and activate the conda environment
conda create --name Honey python=3.11
conda activate Honey

# Update unityagents in requirements.txt and install dependencies
pip install -r requirements.txt

# Add the environment to Jupyter
python -m ipykernel install --user --name Honey  --display-name "Python 3.11 (Honey)"
```

### [Download](https://www.kaggle.com/datasets/stealthtechnologies/predict-purity-and-price-of-honey?resource=download) the dataset


## Dataset presentation

CS (Color Score):
Represents the color score of the honey sample, ranging from 1.0 to 10.0. Lower values indicate a lighter color, while higher values indicate a darker color.

Density:
Represents the density of the honey sample in grams per cubic centimeter at 25°C, ranging from 1.21 to 1.86.

WC (Water Content):
Represents the water content in the honey sample, ranging from 12.0% to 25.0%.

pH:
Represents the pH level of the honey sample, ranging from 2.50 to 7.50.

EC (Electrical Conductivity):
Represents the electrical conductivity of the honey sample in milliSiemens per centimeter.

F (Fructose Level):
Represents the fructose level of the honey sample, ranging from 20 to 50.

G (Glucose Level):
Represents the glucose level of the honey sample, ranging from 20 to 45.

Pollen_analysis:
Represents the floral source of the honey sample. Possible values include Clover, Wildflower, Orange Blossom, Alfalfa, Acacia, Lavender, Eucalyptus, Buckwheat, Manuka, Sage, Sunflower, Borage, Rosemary, Thyme, Heather, Tupelo, Blueberry, Chestnut, and Avocado.

Viscosity:
Represents the viscosity of the honey sample in centipoise, ranging from 1500 to 10000. Viscosity values between 2500 and 9500 are considered optimal for purity.

Purity:
The target variable represents the purity of the honey sample, ranging from 0.01 to 1.00.

Price:
The calculated price of the honey.
