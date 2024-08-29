---
title: Submitting
parent: Benchmark
nav_order: 3
---

# Submitting your results

Submission process is described in respective Codabench pages, we provide an overview below:
1. Firstly, **process** the input images (input views provided in SpaRe and/or DTU dataset) and produce a set of 10 novel test views indicated by corresponding .json file:
- Track1_split_development.json for Track 1 Validation,
- Track1_split_test.json for Track 1 Test,
- Track2_split_development.json for Track 2 Validation,
- Track2_split_test.json for Track 2 Test,

Note that output images should be saved in correct size (1600x1200), in a directory corresponding to the scene (structured same as the input files) and named according to the following convention.

Given a camera index idx in the split file:
- for DTU files: rect_{idx+1:03d}_3_r5000.png
- for SpaRe files: cam_{idx+1:03d}_3_0000.png

E.g. if indicated to provide test_view indexed 13 for scene scan63, render the novel view from camera which pose is described by a projection matrix saved in pos_014.txt and save it in a path myResultsPath/scan63/rect_014_3_r5000.png. This convention follows the majority of released codebases for sparse novel view rendering, increasing the compatibility with other works.
2. **create a ZIP** archive containing all the output image results named as above. Note that the archive should not include upper level folders, all the directories with scene names should be in the root of the archive.