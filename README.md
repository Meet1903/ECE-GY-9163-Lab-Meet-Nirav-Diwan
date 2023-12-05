ECE-GY-9163 Lab 3 - Backdoor attack & Pruning defence
-
File structure (expected):

```
bd
├── bd_test.h5
├── bd_valid.h5
cl
├── test.h5
├── valid.h5
models
├── bd_net.h5
└── bd_weight.h5
```

Due to the large size of the Data I have not attached data files to this repository. Data can be downloaded from this [link](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq).

Steps to run code (Descending order):
-   
1. If you have downloaded the data files and stored it in the same file sturcture then you can skip the next step and execute the 3rd step directly. [It is a recommended step to avoid overwork].
2. Change below variables with your own data path.
    - clean_validation = 'cl/valid.h5'
    - clean_test = 'cl/test.h5'
    - bad_validation = 'bd/bd_valid.h5'
    - bad_test = 'bd/bd_test.h5'
    - clean_test = 'cl/test.h5'
    - bd_test = 'bd/bd_test.h5'
3. Run Lab3.ipynb file.

Evaluation call:
-
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_2.h5
```
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_4.h5
```
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_10.h5
```
---

Steps to run code (Default/ascending order):
-   
1. If you have downloaded data files and stored it in the same file sturcture then you can skip the next step and execute the 3rd step directly. [It is a recommended step to avoid overwork]
2. Change below variables with your own data path.
    - clean_validation = 'cl/valid.h5'
    - clean_test = 'cl/test.h5'
    - bad_validation = 'bd/bd_valid.h5'
    - bad_test = 'bd/bd_test.h5'
    - clean_test = 'cl/test.h5'
    - bd_test = 'bd/bd_test.h5'
3. Run lab3-extra-asc.ipynb file.

Evaluation call:
-
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_2_a.h5
```
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_4_a.h5
```
```
python3 eval.py cl/test.h5 bd/bd_test.h5 model_10_a.h5
```
If you have run the .ipynb files, these models would have been saved in the current working directory, hence can be evaluated from the current working directory. 

If you directly want to evaluate my work, these models can be found under AscendingRepairedNetworks folder.

File structure:

```
AscendingRepairedNetworks
├── model_2_a.h5
├── model_4_a.h5
└── model_10_a.h5
```