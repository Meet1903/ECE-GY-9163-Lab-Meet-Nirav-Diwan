ECE-GY-9163 Lab 3
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

Steps to run code:
-   
1. If you have downloaded data files and stored it in the same file sturcture then you can skip the next step. [It is a recommended step to avoid overwork]
2. Change below variables with your own data path.
    - clean_validation = 'cl/valid.h5'
    - clean_test = 'cl/test.h5'
    - bad_validation = 'bd/bd_valid.h5'
    - bad_test = 'bd/bd_test.h5'
    - clean_test = 'cl/test.h5'
    - bd_test = 'bd/bd_test.h5'
3. Run Lab3.ipynb file.

