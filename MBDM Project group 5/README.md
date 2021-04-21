# Room for the River, implementation of a new flood risk management for Rijkswaterstaat

## Foreword

This is the directory for the EPA1361 project of flood risk management for the Ijssel river.

The creators are:

Group 5
- Marceau Mertens
- Sybe Andringa
- Kylian Knetemann
- Pepijn van den Berg

Unfortunately, one member of us left the group in an early stadium. However, this did not keep us away from diving into the matter as deep as we should with 5 members.
We are very enthousiast about the results we would like to present. In order to walk you through our set-up, read the next part.

## Structure

To succesfully walk you through our steps the following order is obligated to follow:

1 - Exploration. This notebook explores the space of the flood risk management model and will give you a first insight in how the model behaves if no policy is implemented. 
2 - Comparison. This notebook explores several random policies and compares this to the base case, in order to retrieve if policies even make a difference in the flood risk management model.
3 - MORO. With defined functions, we'll use an optimization algorithm in order to find the most robust policies for Rijkswaterstaat that will help them in mitigating the flood risks. 
4 - Optimal policies. With the found optimal policies, we'll perform an thorough analysis based on multiple scenarios. In this way, we can identify the most robust policies within the optimal set in order to present to Rijkswaterstaat.

## File structure

data/ - Data provided by EPA1361
dike_model/ - The original dike_model, provided by EPA1361
images/ - Some of our visualizations have been saved in this directory
results/ - The csv and pkl files of our runs
1 - Exploration.ipynb
2 - Comparison.ipynb
3 - MORO.ipynb
4 - Optimal policies.ipynb
README.md
requirements.txt