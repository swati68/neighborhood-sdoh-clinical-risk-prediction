# The Role of Neighborhood Social Determinant of Health in Clinical Risk Prediction

## Contents

1. `preprocessing.ipynb`  
   Preprocesses the raw data, combines the claims data with ZIP-level neighborhood SDoH and SDI data, and performs variable encoding and other preprocessing steps.

2. `repeat_utilization_preprocessing.ipynb`  
   Creates the X and Y samples used for the analyses.

3. `train_intensity.ipynb`  
   Trains the Poisson models for healthcare utilization.

4. `intensity_model_performance.ipynb`  
   Evaluates model performance and generates calibration, decile, and interaction analyses and plots.

5. `prepare_intensity_causal_data.ipynb`  
   Prepares the data used for the neighborhood SDoH causal analyses.

6. `causal_fci_intensity.ipynb`  
   Performs the FCI analysis.

7. `mediation_analysis.ipynb`  
   Performs the mediation analysis.
