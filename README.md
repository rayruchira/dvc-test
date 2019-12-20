# standardize-mlops
Test repository to build standard workflow for ML

## todo
- [ ] standardize storage (possibly on the Azure VM)
- [ ] standardize workflow to write better tests
- [ ] auto generate documentation

## Project Overview

Documenting Machine Learning models, datasets, experiments, tests, and scores for an efficient workflow resulting in easy reproducibility and collaboration, reduction in deployment time and decreased redundancy between experiments.​

## Directory Structure

- **Datasets-template**
- **Models-template**
- **Project-template**
- **_config.yml**
- **README.md**


### Datasets-template

- Makefile
- README.md

### Models-template

- Makefile
- README.md

### Project-template

#### Datasets

- Makefile
- README.md
- big.h5

#### Models

- Makefile
- README.md
- model.h5

#### Experiments

- Makefile
- README.md

#### Tests

- README.md

## Git LFS

- Replaces large files with text pointer, while storing the contents on a server​.
- Run Makefile to install dependencies
- Select the file types to be tracked 
	- git lfs track "*.psd"
	- git add .gitattributes
- Continue as normal git
	- git add file.psd
	- git commit -m "Add design file"
	- git push origin master
