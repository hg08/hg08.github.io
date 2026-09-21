# Homepage 

# Installation
To get started, we create a conda environment from this dependency file `src/myenv.yml`.
```bash
conda env create -f ./src/myenv.yml 
```

Then active it with 
```bash
conda activate Homepage
```

## File structure
The recomended file structure
```bash
project_name/
├── README.md             # overview of the project
├── data/                 # data files used in the project
│   ├── README.md         # describes where data came from
│   └── sub-directory/    # may contain subdirectories
├── processed_data/       # intermediate files from the analysis
├── manuscript/           # manuscript describing the results
├── results/              # results of the analysis (data, tables, figures)
├── src/                  # contains all code in the project
│   ├── LICENSE           # license for your code
│   ├── requirements.txt  # software requirements and dependencies
│   └── ...
└── doc/                  # documentation for your project
    ├── index.rst
    └── ...
```

