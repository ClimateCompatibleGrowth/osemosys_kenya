# OSeMOSYS-Kenya
This repository houses OSeMOSYS-Kenya models, and scripts developed under the Climate Compatible Growth (CCG) Project.

OSeMOSYS-Kenya models:
- Power sector model (PSM)
- Whole energy system model (WESM)

Each model requires two files to run:
- Model file
  - Model files are stored in the models subfolder and the same file is to be used both for the power sector and full energy system models.
    - model_light.txt runs without outputs on single timeslices activity.
    - model_heavy.txt generates outputs on single timeslices activity, issues might arise on building the matrix for the WESM as it might be too big.
- Data file
  - Data files are stored in the datafiles subfolder, but can be generated through MOMANI interface. The osemosys.zip file should be used to load the models in MOMANI: download the osemosys.zip file, add it to your local momani/data folder and run deploy.cmd as administrator.

To run the models on OSeMOSYS cloud: upload the model and data files and run.
