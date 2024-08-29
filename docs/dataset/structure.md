---
title: Structure
parent: Dataset
nav_order: 3
---

# Data structure

- JSON file indicating input and test views for every scene (e.g. `Track1_split_test.json` for the Test split, Track 1):
    * keys in the JSON corresponding to scene name (and directory name),
    * for every key, a dictonary containining the following fields
        - `input_views` indicating indices of views used as an input (only those are provided)
        - `test_views` indicating indices used for testing required in the submission
        - `dataset` indicating whether data comes from DTU or Synthetic SpaRe part (remember that index i corresponds to camera name (i + 1) - see [Evaluation](/docs/benchmark/evaluation) section).
- Calibration data for DTU and Synthetic datasets provided as projection matrices, compatible with common data loading codes (e.g.as in [RegNeRF](https://github.com/google-research/google-research/tree/master/regnerf)),
- Directories corresponding to scene name, e.g. `scan63`, or `Amplifier`.
- Within directories, images corresponding to various capture positions in various lighting conditions, named as following:
    * for DTU files: `rect_{idx+1:03d}_{lighting}_r5000.png`
    * for SpaRe files: `cam_{idx+1:03d}_{lighting}_0000.png`
    
    where idx corresponds to view index listed in the JSON file, and lighting corresponds to lighting conditions from 0 to 6, where 3 indicates all light sources on, and 3 is the setup used for evaluation in this competition.