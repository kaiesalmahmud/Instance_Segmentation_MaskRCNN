# Instance_Segmentation_MaskRCNN

## File Description

#### MaskRCNN_Training.ipynb
Instance segmentation training of MaskRCNN on ATLDSD dataset
#### Transformer_Backbone_Attempt.ipynb
Incomplete attempt of replacing CNN backbone of MaskRCNN (Pytorch Implementation) with Vision Transformer (ViT).

#### Transformer_Backbone_Attempt_DETECTRON2.ipynb
Incomplete attempt of replacing CNN backbone of MaskRCNN (Detectron2 Implementation) with Vision Transformer (ViT).


## Dataset used:

#### Pytorch Implementation of MaskRCNN
[Apple Tree Leaf Disease Segmentation Dataset (ATLDSD)](https://www.scidb.cn/en/detail?dataSetId=0e1f57004db842f99668d82183afd578&dataSetType=personal)

The dataset structure is changed to the following:

    ├── ATLDSD_dataset      
    │   ├── images          # Images of all classes
    │   ├── masks           # Masks of all images

#### DETECTRON2 Implementaion of MaskRCNN
[leaf_segment Image Dataset](https://universe.roboflow.com/fpt-vl85s/leaf_segment/dataset/2)


