# IRUVD Dataset(https://doi.org/10.1007/s11042-023-15365-2)

## Overview

This repository contains the IRUVD (Indian Road User Vehicle Dataset), a comprehensive still-image-based dataset for automatic vehicle detection in urban and rural Indian road conditions. The dataset includes one class of pedestrians and 13 different types of vehicles commonly found on Indian roads. It aims to address the challenges unique to the Indian traffic scenario, providing a valuable resource for researchers working on autonomous vehicle detection (AVD) systems.

## Dataset Details

- **Images:** 4K images captured using a 16-megapixel Sony IMX519 high-resolution camera.
- **Annotations:** 14.3K bounding boxes, meticulously annotated for various vehicles and pedestrians.
- **Scope:** The dataset covers diverse scenarios encountered on Indian roads, facilitating robust model training.

  
## Accessing the Dataset

The IRUVD dataset is available for download [here](https://drive.google.com/drive/folders/1WQzpYrYaqbfmeg7d1fSTWIAZRSK2mqwt?usp=drive_link). Please make sure to adhere to the terms mentioned in the dataset documentation.

## Citation

If you use this dataset in your research or work, please cite the following paper:

```bibtex
@Article{Ali2023,
  author={Ali, Asfak
  and Sarkar, Ram
  and Das, Debesh Kumar},
  title={IRUVD: a new still-image based dataset for automatic vehicle detection},
  journal={Multimedia Tools and Applications},
  year={2023},
  month={Jun},
  day={17},
  abstract={One of the difficult tasks in the field of computer vision is the classification and detection of vehicles. Researchers from all over the world are working to create autonomous vehicle detection (AVD) systems due to their numerous practical applications, including highway management and surveillance systems. Deep learning techniques, which require a lot of data for proper model training, are the current AVD trend. However, a number of vehicles are discovered in India, the second-largest nation in terms of population, that are not included in the vehicle detection datasets that are currently in use. Furthermore, India's overcrowding makes traffic management difficult and unusual. In this research, we present a dataset for still-image-based vehicle detection that includes one class of pedestrians and 13 different types of vehicles that are seen on Indian urban and rural roads. Initially, we provide baseline results using some state-of-the-art deep learning models on this dataset. To improve the accuracy further, we present an ensemble-based object detection and classification model. The dataset consists of 4K images and 14.3K bounding boxes of various vehicles; that is, researchers are provided with appropriately annotated rectangular boxes for use with these vehicles in the future. A 16-megapixel Sony IMX519 high-resolution camera was used to take all images while traveling throughout West Bengal, an Indian state on the eastern side. Dataset can be found at: https://github.com/IRUVD/IRUVD.git.},
  issn={1573-7721},
  doi={10.1007/s11042-023-15365-2},
  url={https://doi.org/10.1007/s11042-023-15365-2}
}
