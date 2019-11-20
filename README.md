#Road Damage Dataset Update
This fork has the objective of improving the Road Damage Dataset, and making it easier to train it on YOLO, some images had no labels, and were properly labeled, other images had no damage instances and have been removed on this version, this version has the following changes:
- A total of 529 new instances, specifically on the following classes:
    - C00: 62
    - C01: 98
    - C10: 27 
    - C11: 16
    - C20: 118
    - C40: 95
    - C43: 85
    - C44: 28
- 463 images without damage instances have been removed from the dataset
- The structure of the dataset has been simplified to a single folder:
    - All (Contains all images and labels)

# Road Damage Dataset 2018
## The structure of the original Road Damage Dataset 
Road Damage Dataset contains trained models and Annotated images.
Annotated images are presented as the same format to [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/).
- trainedModels
    - SSD Inception V2
    - SSD MobileNet
- RoadDamageDataset (dataset structure is the same format as PASCAL VOC)
    - Adachi
        - JPEGImages : contains images
        - Annotations : contains xml files of annotation
        - ImageSets : contains text files that show training or evaluation image list
    - Chiba
    - Muroran
    - Ichihara
    - Sumida
    - Nagakute
    - Numazu

# This Dataset
## The structure of this version of Road Damage Dataset
Road Damage Dataset contains trained models and Annotated images.
Annotated images are presented as the same format to [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/).
- trainedModels
    - SSD Resnet50
    - SSD MobileNet
- RoadDamageDataset2019 (dataset structure is the same format as PASCAL VOC)
    - Images: contain images (JPEG)
    - Annotations:
        - train.txt
        - val.txt
        - test.txt
        - xmls: contain xml files of annotation

## Download Road Damage Dataset
Please pay attention to the disk capacity when downloading.
- [trainedModels (70MB)](https://mycityreport.s3-ap-northeast-1.amazonaws.com/old/trainedModels.tar.gz)

- [RoadDamageDataset_v1 (1.7GB)](https://mycityreport.s3-ap-northeast-1.amazonaws.com/02_RoadDamageDataset/RoadDamageDataset.tar.gz)

## Dataset Tutorial
We also created the tutorial of Road Damage Dataset.
In this tutorial, we will show you:
- How to download Road Crack Dataset
- The structure of the Dataset
- The statistical information of the dataset
- How to use trained models.

Please check [RoadDamageDatasetTutorial.ipynb](https://github.com/sekilab/RoadDamageDetector/blob/master/RoadDamageDatasetTutorial.ipynb).

## License
Images on this dataset are available under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). The license and link to the legal document can be found next to every image on the service in the image information panel and contains the CC BY-SA 4.0 mark:
<br><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.en"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />
 
## Download Road Damage Dataset
Please pay attention to the disk capacity when downloading.
- [trainedModels (70MB)](link)

- [RoadDamageDataset_v1 (1.7GB)](link)

## Privacy matters
Our dataset is openly accessible by the public. Therefore, considering issues with privacy, based on visual inspection, when a person's face or a car license plate are clearly reflected in the image, they are blurred out.

## License
Images on this dataset are available under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). The license and link to the legal document can be found next to every image on the service in the image information panel and contains the CC BY-SA 4.0 mark:
<br><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.en"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />


If you have something to ask us about the dataset, please contact :
`maedahi[at]iis.u-tokyo.ac.jp`
