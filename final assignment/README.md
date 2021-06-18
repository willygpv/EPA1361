# Room for the River, implementation of a new flood risk management for the Environmental Interest Group

Created by:
```
Group Number   10

│Irene van den Bent         │4603249│
│Hidde Bijlard              │5418631│
│Mels van Gameren           │4490282│
│Guillermo Prieto Viertel   │5366909│
│Kerem Tunca                │4601386│
```
## Introduction
For the final assignment of __EPA1361 Model-based Decision-making__ robust policies for water management on the IJssel River are identified. The specific focus is on mitigating flood risks by implementing Room for the River (RfR) projects relative to using alternative measures of protection such as dike heightening. Using a simulation model, it is analyzed how the client - the environmental interest group - can design a water management policy for the IJssel river that maximizes the environmental potential of RfR while being robust and effective under different uncertain future scenarios. The robust policy optimization process focuses on the computation of policies which are maximally effective against the worst manifestation of possible futures. Policies were evaluated based on five key performance indicators: 'Expected annual damage', 'Expected number of deaths', 'RfR costs', 'Dike heightening costs', and 'Evacuation costs'.

## Folder structure

```
final assignment
│
└───dike_model <-- contains the model files and the analysis notebooks.
│   │ 
│   └───data <-- contains the preprocessed datafiles on which the model runs.
│   
└───images <-- contains the plots generated in the data analysis.
│
└───results <-- contains the outcome files of the simulations and the data analysis. The analysis notebooks in EPA1361/dike_model rely on these files.
│  
└───reports <-- contains the final report and the political reflection.

```
## Usage

To follow the steps of the analysis the notebooks have to be executed in the following order. Please bear in mind that the cells that peform experiments or optimize have been commented out and instead the notebooks read the results from the save files. 

0. final assignment\dike_model\0 - Random_policy_generation.ipynb.
1. final assignment\dike_model\1 - Basecase_analysis.ipynb. 
2. final assignment\dike_model\2 - Policy_exploration.ipynb. 
3. final assignment\dike_model\3 - MORDM_Optimization.ipynb. 
4. final assignment\dike_model\4 - Policy_Reevaluation.ipynb. 


## Built with

Python 3.7.9
