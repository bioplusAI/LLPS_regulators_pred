To make predictions, follow these steps:

1.	Clone the LLPS_regulators_Pred repository from the source.
2.	Launch a command-line interface (e.g., Command Prompt or Terminal).
3.	Navigate to the cloned repository using the command: cd LLPS_regulators_Pred
4.	Create the conda environment by executing: conda env create -f environment/environment.yml
5.	Activate the newly created environment: conda activate llps_predictor
6.	Start Jupyter Notebook by running: jupyter notebook
7.	Insert your query protein sequences (in FASTA format) into the Input_sequences.txt file located within the repository Input_sequences.
8.	Open the Source_code.ipynb notebook from the Source_code directory in Jupyter Notebook and execute the code.
   
Note: The initial execution may take several minutes as the ESM-2 model is downloaded. Once the model is cached, subsequent predictions will be completed within seconds.

