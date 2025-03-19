Folder Structure
.
├── histopathological cancer prediction                          # Documentation files (alternatively `doc`)
│   ├── data                                                     # data files (testing and training)
│       ├── test
│           ├── 0a0a1f3867f41e02353afcaf503f63be1bdd35ec.tif
│           ├── 0a0a85db9218e366569c913185cc0740f59f4d9e.tif
│           ├── 0a0c08f8f3a830f5d925027e90a889b9c00cf518.tif
│           ├── ...                                              # etc.
│       ├── train
│           ├── 0a0a2e923bdedb11f270dcd3f11d0f001df98f00.tif
│           ├── 0a0a8bdf1d78af77dcc0b94aef6fb5c2f841a3c0.tif
│           ├── ffeac5c0edd4760291d887678a4d6ec83f56c4d2.tif
│           ├── ...                                               # etc.
│       ├── sample_submission.csv                                 # Labels for test/
│       ├── train_labels.csv                                      # Labels for train/
│   ├── pytorch-cnn-binary-image-classification.ipynb             # Main Script
│   ├── requirements.txt                                          # Packages/Lib 
│   └── ...                                                       # etc.
└── .gitignore
