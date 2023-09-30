[![License: CC BY-NC 4.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/png/by-nc-sa.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Water Conservancy Segment 3D

![image-20230930152815539](README.assets/image-20230930152815539.png)

[Chinese](./README-zh.md)

## Introduction

This dataset contains large-scale outdoor water conservancy scene laser 3D point cloud scanning data from Zhongshui, collecting 3D point cloud data of corresponding scenes under the Greater Bay Area dike-Foshan, Gaozhou Reservoir, and Dateng Gorge basins. This dataset will be used to train and test environmental detection algorithms for the project to achieve accurate monitoring and analysis of the environment around water conservancy projects.

In terms of dataset production, according to the national standard GBT 20257.1-2017 Basic Scale Map Symbols, combined with the actual engineering practice in the water conservancy field, the terrain feature classes for 3D point cloud segmentation are determined, including a total of 6 major categories and 15 minor categories, specifically as follows:

| Major Category |                 | Minor Category |         |
| -------------- | --------------- | -------------- | ------- |
| Water system   | Waterline       | Ditch          | Dam     |
| Bui. and fac.  | Shed            | Concrete House |         |
| Topography     | Slope           | Scarp          |         |
| Veg. and soil  | Vegetable Field | Grassland      | Dryland |
|                | Bareland        | Woodland       |         |
| Transportation | Cement Road     | Dirt Road      |         |
| Others         | Others          |                |         |

The areas of this dataset are concentrated in reservoir and river network areas with complex terrain features. Since the boundaries between natural objects are not clear, this dataset is also very meaningful for the segmentation tasks of natural objects and can serve as a basic dataset to evaluate the performance of 3D point cloud segmentation algorithms.

## Characteristics

The main characteristics of this dataset are as follows:

1. Diverse categories. As shown in Table 2.1, this dataset contains 15 minor categories, which basically covers the main components of water conservancy facilities, such as buildings, roads, terrain, water bodies, etc. These diverse and comprehensive categories can meet the needs for multi-angle analysis of water conservancy facilities.
2.  Large coverage and data volume. As shown in Table 2.2, the collected 3D point cloud data covers multiple typical water conservancy facility scenes including the Greater Bay Area dike-Foshan, Gaozhou Reservoir, Dateng Gorge and other basins. It has a wide geographical scope and good representativeness. The large sample volume data is conducive to developing more robust algorithm models.The 3D point cloud data is divided into 3 Works according to different geographical locations. Among them, Work_1 is the key construction area of Dateng Gorge Hydropower Hub with 104,654,477 points. Work_2 is Donggankeng-Zhuji Gao with 131,112,786 points. Work_3 is Foshan Greater Bay Area Dike with 28,895,223 points.
3. Real-scene data with high-quality annotations. This data comes from the aerial photography of actual water conservancy facilities and has the characteristics of real scenes, which can be directly used for testing and verification of relevant algorithms and products. At the same time, the dataset has been manually checked for annotation to ensure the accuracy and consistency of the annotations. This lays a solid foundation for subsequent algorithm research based on this dataset.

Most of the currently publicly available 3D point cloud datasets focus on indoor scenes or urban street scenes, with relatively little data on water conservancy facility scenes. This dataset helps fill this gap and provides basic data support for the automation analysis and management of water conservancy facilities. With large data volume, wide coverage, refined annotation, and reliable authenticity, this dataset can provide powerful data support for the digital management of water conservancy facilities. It is a more abundant and valuable public 3D point cloud dataset for water conservancy 

## Download

- Baidu Pan: https://pan.baidu.com/s/1eI5K7dvPymsr_RWY6meIrA?pwd=iisk Extraction code: iisk

- Kaggle: https://www.kaggle.com/datasets/happycv/segment-hydraulic

## Extraction code: iisk

This dataset is authorized for use under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material
- Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
- **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

## Contact

If you use this dataset in your research, please click the `Cite this repository` on the right side of the project page for citation.

Please be sure to comply with all the terms of the `CC BY-NC-SA 4.0 license`.

## Contact

If you have any questions about the dataset, please feel free to contact [zhou_wei@xtu.edu.cn](mailto:zhou_wei@xtu.edu.cn).
