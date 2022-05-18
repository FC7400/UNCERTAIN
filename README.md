# UNCERTAIN
Raw data generation for Uncertainty propagation in pore water chemical composition calculation using surrogate models 
In the zip file each folder is associated to one of the two configurations (Small range case and Large range case) and contains four files:
- Inputs_Training_set.txt of size 10.000 x 19 obtained from a Monte-Carlo sampling of the parametric domain (dimension 19).
- Inputs_Validation_set.txt of size 10.000 x 19 obtained from a Monte-Carlo sampling different from the training set.
- Outputs_Training_set.txt of size 10.000 x 13 obtained from PHREEQC simulations with Inputs_Training_set.txt as inputs (they are 13 quantities of interest).
- Outputs_Validation_set.txt of size 10.000 x 13 obtained from PHREEQC simulations with Inputs_Validation_set.txt as inputs.
