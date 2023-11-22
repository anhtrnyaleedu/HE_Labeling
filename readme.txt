Background and Purpose: 
- When running a model for HE prediction, the input is only the baseline CT. When training the model, training data is needed including input data (CT baseline) as well as the desired output data (label computing from baseline+follow-up segmentation)
- We aim to reduce the number of patients (baseline + follow-up) that doctors need to check to label the data when setting up a dataset for training HE prediction model from admission non-contrast head CT.
Methods: Using medical imaging from a multicentric clinical trial, a single-center longitudinal study, and external validation data, we proposed a model for HE labeling with multiple inputs, outputs, and loss fuction to detect the patients with no HE expansion in high certainty. We then compared the model with state of art methods.
Conclusion: We trained, and independently validated a deep learning model for the label of HE in supratentorial ICH, with improved labeling compared to other methods. Such a model can reduce the number of patients that doctors need to check to nearly 40%-80% of the dataset.

https://drive.google.com/drive/folders/1zJ1IQ5zOBg2cUSzeOM6sQuSnG_Pk4NzX?usp=sharing