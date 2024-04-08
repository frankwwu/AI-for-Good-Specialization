# Explore Phase - Exploring the Karoo Image Data

[__Open Lab__](https://www.coursera.org/learn/ai-and-climate-change/ungradedLab/6nLcc/explore-phase-exploring-the-karoo-image-data/lab?path=%2Fnotebooks%2FC2_W3_Lab_1_Karoo_Image_data_exploration.ipynb)

## Instructions

In this project you will use the Snapshot Karoo dataset, which is part of the 
[Lila BC project](https://lila.science/datasets/snapshot-karoo). This dataset contains 14889 sequences of camera trap images, totaling 38074 images.

The dataset has been annotated thanks to the contributions of volunteers using 
[the zooniverse.org platform](https://www.zooniverse.org/projects/shuebner729/snapshot-karoo/classify).

The full quality Karoo dataset is 42 GB. After filtering out just the images containing animals (having deleted the images that are labelled as empty or having vehicles instead of animals), the size of the dataset is reduced to 6 GB. Furthermore, reducing the quality of each picture to around 100Kb, the dataset size is reduced to around 600 MB, such that it can fit into this lab environment. You will use this mini Karoo dataset in this project, but keep in mind the full dataset is higher resolution and contains more images.

The steps you will complete in this lab are the following:

1. Import python packages

2. Inspect the data

3. Visualize the distribution of images