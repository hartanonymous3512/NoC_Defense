# NoC_Defense
1. Import the Python Notebook file in Jupyter.
2. Specify the paths to the dataset files. Cells 2 and 3 feed the base file and mix-2 application file. You may have to specify the sheet name in the same line. 
3. Same applies to the Architecture detection Python notebook. Specify all the file paths and sheet names to include. 
4. Once the file paths are set, you may execute all the cells. The performance metric of the train/test is printed first, followed by the performance of the ANN with the new test file specified under the title "Model predicting probabilites and classes". Note: the performance of the new test files will result in lower performance compared to the earlier performance with the files on which the ANN was trained. Reason being the earlier files are fed by the attacker to the ANN, while the data in the test only dataset ("Model predicting probabilites and classes") is generated with the proposed defense. 
