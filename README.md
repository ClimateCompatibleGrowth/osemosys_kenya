[![Documentation Status](https://readthedocs.org/projects/osemosyskenya/badge/?version=latest)](https://osemosyskenya.readthedocs.io/en/latest/?badge=latest)

# OSeMOSYS-Kenya
This repository houses OSeMOSYS-Kenya models and scripts developed under the Climate Compatible Growth (CCG) Project.

## Power system model (PSM)
The power system model describes the power sector at a single power plant level. The model includes storage, in a different implementation from the official OSeMSYS version's one.
The data file has been generated through the MOMANI UI, while the model file contains the specific storage implementation.

### Citing OSeMOSYS-Kenya PSM 
If you work on the current version of the PSM, please cite the following paper:

M. Kihara, P. Lubello, A. Millot, M. Akute, J. Kilonzi, M. Kitili, F. Mukuri, B. Kinyanjui, P. Hoseinpoori, A. Hawkes, A. Shivakumar, D. Welsby, S. Pye, Mid- to long-term capacity planning for a reliable power system in Kenya, Energy Strategy Reviews 52 (2024) 101312. https://doi.org/10.1016/j.esr.2024.101312.

BibTeX:

    @article{osemosys_kenya_psm,
      title = {Mid- to long-term capacity planning for a reliable power system in Kenya},
      author = {Mungai Kihara and Pietro Lubello and Ariane Millot and Michelle Akute and Julius Kilonzi and Monicah Kitili and Felister Mukuri and Boniface Kinyanjui and Pooya Hoseinpoori and Adam Hawkes and Abhishek Shivakumar and Dan Welsby and Steve Pye},
      journal = {Energy Strategy Reviews},
      volume = {52},
      pages = {101312},
      year = {2024},
      issn = {2211-467X},
      doi = {https://doi.org/10.1016/j.esr.2024.101312},
      url = {https://www.sciencedirect.com/science/article/pii/S2211467X24000191}
      }

## Whole energy system model (WESM)
The whole energy system model includes the power system one, but is expanded to consider all energy sectors. In the current version, no storage technologies are included.
The data file has been generated through the UNDESA UI, and the model file is the same as the one used by the UI.

<br/><br/>

### Acknowledgements
This material has been produced with support from the Climate Compatible Growth (CCG) programme. CCG is funded by UK AID from the UK Government. Views expressed herein do not necessarily reflect the UK government's official policies.

### Licenses
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/ClimateCompatibleGrowth/osemosys_kenya?tab=Apache-2.0-1-ov-file#readme)

The model files located at ```psm/model_psm.txt``` and ```wesm/model_wesm.txt``` are released under the [Apache 2.0](https://github.com/ClimateCompatibleGrowth/osemosys_kenya?tab=Apache-2.0-1-ov-file#readme) license, and the copyright holders are listed in the author's list. Both models have been developed starting from the original [OSeMOSYS modelling framework](https://github.com/OSeMOSYS/OSeMOSYS_GNU_MathProg?tab=readme-ov-file)<sup>1</sup>.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The data files located at ```psm/data_psm.txt``` and ```wesm/data_wesm.txt``` are released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0) license, and the copyright holders are listed in the author's list.

### References
[1] Howells, Mark, et al. "OSeMOSYS: the open source energy modeling system: an introduction to its ethos, structure and development." Energy Policy 39.10 (2011): 5850-5870. https://doi.org/10.1016/j.enpol.2011.06.033
