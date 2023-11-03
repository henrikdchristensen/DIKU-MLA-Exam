# README

## Quick guide to run the program

1. Install Python (tested with v.3.11, v.3.12 does not work yet) and a package manager, e.g. conda or pip (conda is recommended)
   1. Update package manager if already installed: `conda update -n base -c defaults conda`
2. Start existing virtual environment or create a new one: `conda create -n mla python=3.11`
3. Install necessary python libraries into the virtual environment: `conda install notebook ipykernel pandas numpy matplotlib seaborn scikit-learn tabulate`. Note can be necessary to update `scikit-learn` afterwards using `conda update scikit-learn`.
4. Run all cells in the notebook using either a IDE (e.g. VS code) or just using the Jupyter notebook server by running `jupyter notebook` in the terminal)

## Versions of libraries tested
| Package       | Version |
|---------------|---------|
| notebook      | 6.5.4   |
| pandas        | 2.1.1   |
| numpy         | 1.24.3  |
| requests      | 2.31.0  |
| matplotlib    | 3.8.0   |
| scikit-learn  | 1.3.0   |
| seaborn       | 0.12.2  |
| tabulate      | 0.8.10  |