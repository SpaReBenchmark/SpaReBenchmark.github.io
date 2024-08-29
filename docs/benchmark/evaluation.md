---
title: Evaluation
parent: Benchmark
nav_order: 2
---

# Evaluation

The SpaRe Benchmark provides a comprehensive evaluation of the submitted solutions.

## Metrics
Submissions are evaluated based on the following metrics:
- Masked PSNR (PSNR-M) - PSNR calculated with the object mask,
- PSNR - calculated in the whole image, including background reconstruction,
- SSIM-M - SSIM calculated withing the tight bounding box around the object,
- SSIM - calculated in the whole image,
- LPIPS-M - LPIPS calculated withing the tight bounding box around the object, using AlexNet as a backbone,
- LPIPS - calculated in the whole image.

## Data
All submissions are evaluated on SpaRe Dataset (Synthetic), and DTU in agreement with [1].

{: .note }
The benchmark contains data SpaRe Dataset and DTU, Codabench allows submission of solution including either of those datasets or both.

Users are provided with all metrics in the following details:
- separately for SpaRe Dataset and DTU (only one can be submitted to the benchmark),
- on various granularity level: for each image, average for every scene, average for the whole dataset.


[1] Nazarczuk, M., Tanay, T., Catley-Chandar, S., Shaw, R., Timofte, R., Pérez-Pellitero, E.: AIM 2024 Sparse Neural Rendering Challenge: Dataset and Benchmark. In: Proceedings of the European Conference on Computer Vision (ECCV) Workshops (2024)