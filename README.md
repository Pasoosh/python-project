# Python Project

## Prerequisites

### Software

You'll need the following installed in order to make best use of this repository:

- [Task](https://taskfile.dev/#/installation)

## Usage

### Creating a new backend component

1. In the root of the repo, run:

   ```shell
   $ task project:init PROJECT_NAME=something_something
   ```

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
   
├── PROJECT_NAME                           
│   ├── notebooks                       <- Jupyter notebooks. Naming convention is a number (for ordering),
│   │   │                                  the creator's initials, and a short `-` delimited description, 
│   │   │                                  e.g. '1.0-jqp-initial-data-exploration`.
│   │   │
│   │   ├── feature_engineering         <- Jupyter notebooks containing data source and feature engineering methodology.
│   │   │
│   │   ├── models                      <- Jupyter notebooks use to explore and test modeling techniques and strategies.
│   │   │
│   │   ├── data_analysis               <- Jupyter notebooks to explore and analyse data.
│   │   
│   ├── docs                            <- Supporting documentation or research. 
│   │
│   │
│   ├── project_requirements.txt        <- A text file containing links to supporting documentation, the owner of the project 
│   │                                      notion boards, and package requirements.
└── 
```