---
title: Download
parent: Dataset
nav_order: 2
---

# Data download

We host datasets using HuggingFace repository available here. We include the following files:

- [Track1_split_development.json](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/Track1_split_development.json) - JSON file listing input and test view indices for the Validation set for Track 1 of the SpaRe Benchmark
- [Track1_split_test.json](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/Track1_split_test.json) - JSON file listing input and test view indices for the Test set for Track 1 of the SpaRe Benchmark
- [Track2_split_development.json](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/Track2_split_development.json) - JSON file listing input and test view indices for the Validation set for Track 2 of the SpaRe Benchmark
- [Track1_split_test.json](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/Track2_split_test.json) - JSON file listing input and test view indices for the Test set for Track 2 of the SpaRe Benchmark
- [dtu_calibration.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_calibration.zip) - ZIP file containing projection matrices for DTU camera calibration
- [synth_calibration.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_calibration.zip) - ZIP file containing projection matrices SpaRe data camera calibration (additional file listing camera intrisics and extrinsics in Blender format is provided as well)
- [dtu_development_3views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_development_3views.zip)- ZIP file containing Track 1 Validation split input views from DTU data
- [dtu_test_3views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_test_3views.zip)- ZIP file containing Track 1 Test split input views from DTU data
- [dtu_development_9views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_development_9views.zip)- ZIP file containing Track 2 Validation split input views from DTU data
- [dtu_test_9views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_test_9views.zip)- ZIP file containing Track 2 Test split input views from DTU data
- [synth_development_3views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_development_3views.zip)- ZIP file containing Track 1 Validation split input views from SpaRe data
- [synth_test_3views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_test_3views.zip)- ZIP file containing Track 1 Test split input views from SpaRe data
- [synth_development_9views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_development_9views.zip)- ZIP file containing Track 2 Validation split input views from SpaRe data
- [synth_test_9views.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_test_9views.zip)- ZIP file containing Track 2 Test split input views from SpaRe data
- [dtu_training_p1.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_training_p1.zip) and [dtu_training_p2.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/dtu_training_p2.zip)- ZIP files containing training data from DTU
- [synth_training_p1.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_training_p1.zip) and [synth_training_p2.zip](https://huggingface.co/datasets/aim2024-sparse-rendering/AIM2024-SparseNeuralRendering/blob/main/synth_training_p2.zip)- ZIP files containing SpaRe training data

{: .note }
You may need to download only a few of the files. E.g. if willing to participate in Track 1 Test of the SpaRe Benchmark and evaluate only on SpaRe dataset, download `Track1_split_test.json`, `synth_calibration.zip`, `synth_test_3views.zip`.
