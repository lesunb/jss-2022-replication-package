# hmrs_analysis

Simple statistical analysis on our multi-robot simulation environment. https://github.com/Gastd/morse_simulation

## Installation

Install jupyter on your environment and install the dependencies through pip:

`pip install -r requirements.txt`

## Results

First copy your logs into the data folder.

Then you may run `jupyter notebook` to access the notebooks in the notebook folder, you can then access all the graphs and information used in the analysis for our paper in the Analysis.ipynb notebook.
You can also view our failure analysis for each skill and task results in their respective notebooks

## Notes

When running the notebook with a different dataset please modify the trial_run_objects variable inside the notebook so it points to your logs folder. By default the notebooks will point to "experiment_2021_07_29_15_33_17_run_2" inside the data folder.

