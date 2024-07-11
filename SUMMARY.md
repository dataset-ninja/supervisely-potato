**Supervisely Potatoes Dataset for Crops and Weed Segmentation** is a dataset for a weakly supervised learning task. Possible applications of the dataset could be in the agricultural industry. 

The dataset consists of 1055 images with 3971 labeled objects belonging to 2 different classes including *crop* and *weed*.

Images in the Supervisely Potatoes dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There are 82 (8% of the total) unlabeled images (i.e. without annotations). There is 1 split in the dataset: *train* (1055 images). Alternatively, the dataset could be split into 3 field IDs: ***113*** (935 images), ***114*** (60 images), and ***116*** (60 images). The dataset was released in 2023 by the <span style="font-weight: 600; color: grey; border-bottom: 1px dashed #d3d3d3;">Supervisely</span>.

Here is the visualized example grid with animated annotations:

[animated grid](https://github.com/dataset-ninja/supervisely-potatoes/raw/main/visualizations/horizontal_grid.webm)
