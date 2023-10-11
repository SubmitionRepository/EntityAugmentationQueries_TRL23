# Generating Data Augmentation Queries Using Large Language Models
Datasets can be found here: https://drive.google.com/drive/folders/18sxf7d_VWSre9nZ2kXk7eDVOf_2hSs4Q?usp=sharing

Save paths must be specified prior to running the code. This is done by creating the "output_path_config" in 
the additionalScripts directory like so,
```
processed_data|F:/data/processed_data/
database_index|F:/data/index/
experiment_results|F:/
```
Local and external data structures are stored at "processed_data" path. The indexed database is stored at "database_index" path.
Experiment results are stored at "experiment_results" path. This makes it easier to run the code on different servers
without manually changing paths every time code is pulled from git.