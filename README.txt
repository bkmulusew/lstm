Step 1: connect to "cycle*.csug" machine or "username@gpu-node0*.csug.rochester.edu" if you would like to use gpu. 

The department opu machines are: "gpu-node01.csug.rochester.edu" to "gpu-node06.csug.rochester.edu"

Step 2: upload the project file to your account folder.

Step 3: since the environment for project 1 also includes the required packages for project 2, for simplicity, you will still use the same environment for project 2 development. 

Enter the command "source /u/cs298/anaconda3/bin/activate /u/cs298/anaconda3/envs/project1/" in your terminal and run it to activate the environment.

Step 4: as usual, now you can run jupyter notebook and complete the project 2.


If you'd like to use python file for training, there are two ways: copy-and-paste the code from the notebook into a new python file, or run the command "jupyter nbconvert --to script [YOUR_NOTEBOOK].ipynb". 

The training may take several hours, start it early!
