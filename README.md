# TraCon: A novel dataset for real-time traffic cones detection using deep learning

## Dataset Description

The dataset contains RGB data from heterogeneous sources and sensors (e.g., DSLR cameras, smartphones, UAVs). Furthermore, the images vary in terms of illumination conditions (e.g., overexposure, underexposure), environmental landscapes (e.g., highways, bridges, cities, countrysides), and weather conditions (e.g., cold, hot, sunny, windy, cloudy, rainy, and snowy). In parallel, several images include various types of occlusions, thus making the traffic cone detection task more challenging. Each image has a corresponding .txt file with the bounding box information of the traffic cones (YOLO annotation format: <code>object-class, center_x, center_y, width, height</code>).

The total number of RGB images in the dataset is 540 with various resolutions ranging from 114×170 to 2,100×1,400. It is underlined that the total number of traffic cones in the entire dataset is 947. Representative samples of the dataset are demonstrated in the figure below. From the images of the whole dataset, 92.5% were used for training the deep model, and 7.5% for testing its effectiveness. Among the training data, 80% of them were used for training and the remaining 20% for validation.

<img src="docs/TraCon_data_samples.png"/>

## Acknowledgements

This work has received funding from the European Union’s Horizon 2020 Research and Innovation Programme under grant agreement No 955356 (Improved Robotic Platform to perform Maintenance and Upgrading Roadworks: The HERON Approach).

## Citations

If you use or find the TraCon dataset useful, please cite the following:

1. **[TraCon Summary Paper](https://arxiv.org/abs/2205.11830):** Katsamenis, I., Karolou, E. E., Davradou, A., Protopapadakis, E., Doulamis, A., Doulamis, N., & Kalogeras, D. (2022). TraCon: A novel dataset for real-time traffic cones detection using deep learning. arXiv preprint arXiv:2205.11830.
2. **[HERON Summary Paper](https://dl.acm.org/doi/abs/10.1145/3529190.3534746?casa_token=MQ7wMDMZHfoAAAAA:Dr880-nr5X04aeDJiR9hK3GzHXmK_KaYV5gqvLopzeClO9yx7q6tgjKaqXbMo09OjrcsHeyyQuRTsA):** Katsamenis, I., Bimpas, M., Protopapadakis, E., Zafeiropoulos, C., Kalogeras, D., Doulamis, A., Doulamis, N., Martín-Portugués Montoliu, C., Handanos, Y., Schmidt, F., Ott, L., Cantero, M., & Lopez, R. (2022, June). Robotic maintenance of road infrastructures: The HERON project. In Proceedings of the 15th International Conference on PErvasive Technologies Related to Assistive Environments (pp. 628-635)., doi: 10.1145/3529190.3534746.

```csv
@article{katsamenis2022tracon,
  title={TraCon: A novel dataset for real-time traffic cones detection using deep learning},
  author={Katsamenis, Iason and Karolou, Eleni Eirini and Davradou, Agapi and Protopapadakis, Eftychios and Doulamis, Anastasios and Doulamis, Nikolaos and Kalogeras, Dimitris},
  journal={arXiv preprint arXiv:2205.11830},
  year={2022}
}

@inproceedings{katsamenis2022robotic,
  title={Robotic maintenance of road infrastructures: The heron project},
  author={Katsamenis, Iason and Bimpas, Matthaios and Protopapadakis, Eftychios and Zafeiropoulos, Charalampos and Kalogeras, Dimitris and Doulamis, Anastasios and Doulamis, Nikolaos and Mart{\'\i}n-Portugu{\'e}s Montoliu, Carlos and Handanos, Yannis and Schmidt, Franziska and others},
  booktitle={Proceedings of the 15th International Conference on PErvasive Technologies Related to Assistive Environments},
  pages={628--635},
  year={2022}
}
```
