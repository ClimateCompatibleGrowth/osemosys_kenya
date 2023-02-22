# OSeMOSYS-Kenya
This repository houses OSeMOSYS-Kenya models, and scripts developed under the Climate Compatible Growth (CCG) Project.

OSeMOSYS-Kenya models:
- Power sector model (PSM)
- Whole energy system model (WESM)

Each model requires two files to run:
- Model file
  - The model file is directly stored in this repo and is the same file for both the power sector and full energy system models.
    - model_light.txt runs without outputs on single timeslices activity.
    - model_heavy.txt generates outputs on single timeslices activity, issues might arise on building the matrix for the WESM as it might be too big.
- Data file
  - The data.txt is managed through the user interface MOMANI. This repository stores the MOMANI files for the power sector and full energy system models in the osemosys.zip file. To see the models in MOMANI: download the osemosys.zip file, add it to your local momani/data folder and run deploy.cmd as administrator.

To run the model on OSeMOSYS cloud: use one of the model files here provided and the data.txt generated with MOMANI.
