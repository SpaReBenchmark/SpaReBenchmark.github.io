---
title: Overview
parent: Dataset
nav_order: 1
---

# SpaRe Dataset

SpaRe extends the [DTU dataset](https://roboimagedata.compute.dtu.dk/?page_id=36). We believe that a fair evaluation protocol requires a larger sample of objects, including a subset such that test views are not publicly released. To this end, we replicate a DTU-alike setup in a synthetic
Blender environment.

## Scenes

We place all objects on a white platform and place them in a black box. We manually collected $102$ assets from [BlenderKit](https://www.blenderkit.com). All the collected models are high-quality 3D assets belonging to a range of categories, including toys, cars and houses miniatures, home appliances and equipment, technology items, tools, sports equipment, plants, decorations *etc*. A breakdown of categories seen in SpaRe is presented below:
![](../../../assets/cat_chart.png)
The scenes span a large range of objects sized between 8cm and 50cm. We include items varying in texture and specularity (*eg.* a plushy elephant, a glass lamp, or a shiny plastic children's toy).

## Examples

 <video src="/assets/objects.mp4" autoplay loop muted style="max-width: 100%;"></video> 

## Paper

For more detail we refer you to our [dataset paper]() [1].

[1] Nazarczuk, M., Tanay, T., Catley-Chandar, S., Shaw, R., Timofte, R., Pérez-Pellitero, E.: AIM 2024 Sparse Neural Rendering Challenge: Dataset and Benchmark. In: Proceedings of the European Conference on Computer Vision (ECCV) Workshops (2024)