To make predictions, follow these steps:

1.	Clone the LLPS_regulators_Pred repository using command: git clone https://github.com/bioplusAI/LLPS_regulators_pred.git
2.	Launch a command-line interface (e.g., Command Prompt or Terminal).
3.	Navigate to the cloned repository using the command: cd LLPS_regulators_Pred
4.	Create the conda environment by executing: conda env create -f environment/environment.yml
5.	Activate the newly created environment: conda activate llps_predictor
6.	Start Jupyter Notebook by running: jupyter notebook
7.	Insert your query protein sequences (in FASTA format) into the Input_sequences.txt file located within the repository Input_sequences.
8.	Open the Source_code.ipynb notebook from the Source_code directory in Jupyter Notebook and execute the code.
   
Note: The initial run may require several minutes to complete due to the download of the ESM2_t36 model. After the model is cached locally, subsequent predictions will be executed within seconds.
Alternatively, you may manually download the ESM2_t36 model from the following link:
https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t36_3B_UR50D.pt
Place the downloaded esm2_t36_3B_UR50D.pt file in the checkpoints directory, which is typically located at:
C:\Users\<username>\.cache\torch\hub\checkpoints
If this directory does not exist, please create it.
