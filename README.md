# Digital_Phantom_Prac
Welcome to Digital Phantom Prac! This repository provides a set of tools for calculating intensity-based statistical features from medical images.

![Alt Text](https://lirp.cdn-website.com/69c0b277/dms3rep/multi/opt/dt_150925_kidney_cancer_800x600-960w.jpg)

## Installation

To install the package and its dependencies, follow these steps:

1. Download or clone this repository to your local machine.

2. Navigate to the package directory:

   ```bash
   cd PATH/digital_phantom_package

3. Install the required dependencies using pip:

   ```bash
   !pip install -r requirements.txt

## Usage

Once the package and its dependencies are installed, you can use it in your Python code. Here's an example of how to import and use the package:

 ```python 
  from digital_phantom_package import IntensityBasedStat
  
  # Load your image and mask data using SimpleITK 
  # ...
  
  # Create an instance of the IntensityBasedStat class
  intensity_stat = IntensityBasedStat(image, mask)
  
  # Calculate the features
  mean_intensity = intensity_stat.get_mean_intensity()
  variance_intensity = intensity_stat.get_variance_intensity()
  # ... (other features)
  
  # Print or use the calculated features
  print("Mean Intensity:", mean_intensity)
  print("Variance Intensity:", variance_intensity)
  # ...
