# Semi-supervised Multitask Attention CNN using Signed Distance Maps for Liver Tumor Segmentation
Liver cancer is one of the cancers which has the highest mortality rate in the world. In order to help physician better diagnose and make personalized treatment schemes, an accurate and automatic liver and tumor segmentation method from abdomen CT images is highly demanded in the clinical practice. We proposed a novel Attention CNN based semi-supervised architecture which utilizes signed distance maps (SDMs) for the accurate boundary extraction of liver. The attention module between liver segmentation decoder and tumor segmentation decoder learns to suppress irrelevant regions in tumor segmentation task while highlighting salient features useful for this task. This eliminates the necessity of localization of liver explicitly. The signed distance maps puts more attention on boundary of liver thus enhancing the model performance to segment the liver boundary. We extensively evaluated our method on the data-set of MICCAI 2017 Liver Tumor Segmentation (LiTS) Challenge and Decathlon hepatic vessel segmentation. Our method outperformed other state-of-the-arts on the segmentation results of tumors and achieved very competitive performance for liver and tumor segmentation.

## Pipeline

<img src="https://github.com/Azkarehman/Liver-Tumor-Segmentation/blob/main/Figures/Liver%20model%20sdm.png" width="700" height="500">

## Dataset
This research was performed on:

 - MICCAI 2017 Liver Tumor Segmentation (LiTS)
 - Decathlon hepatic vessel
   segmentation

## Results:


## Technical Details
**Language:** Python
**Deep learning Framework:** Keras
**Image Processing libraries:** Opencv, Scikit learn

