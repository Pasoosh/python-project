# Python Project

## Prerequisites

### Software

You'll need the following installed in order to make best use of this repository:

- [Task](https://taskfile.dev/#/installation)

## Usage

### Creating a new backend component

1. In the root of the repo, run:

   ```shell
   $ task process_name:init PROCESS_NAME=something_something
   ```

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── README.md 
|
├── dependencies                        <- A text file containing all package dependencies per process step.
|                               
├── orchestration
|
├── src 
|   ├── utils                           <- a folder containing common functions used across multiple processes.
|   |
│   ├── process_name                    <- folder name of the job the scripts within this directory are responsible for.
│   │   │
|   │   ├── docs                        <- Supporting documentation or research.
|   |   |
│   │   ├── data_transformation         <- Jupyter notebooks containing data source and feature engineering methodology.
│   │   │
│   │   ├── ETL                         <- Jupyter notebooks use to explore and test modeling techniques and strategies.
│   │    
├── requirements.txt
|
├── Taskfile.yml
└── 
```