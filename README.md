# Peach Cultivars Dataset
This dataset contains field images (.jpg) of three peach cultivars: catherine, royal time, and sweet drea. File annotations (.xml) for each image and files (.csv) with information about the annotations.
The files are organized like the folder tree below: 

```
.
├── Test
│   ├── Catherine
│   │   ├── Annotation
│   │   ├── Images
│   │   └── Information
│   ├── Royal Time
│   │   ├── Annotation
│   │   ├── Images
│   │   └── Information
│   └── Sweet Dream
│       ├── Annotation
│       ├── Images
│       └── Information
└── Train
    ├── Catherine
    │   ├── Annotation
    │   ├── Images
    │   └── Information
    ├── Royal Time
    │   ├── Annotation
    │   ├── Images
    │   └── Information
    └── Sweet Dream

```
__________________________________________________________________________________________________________________________________________________________
Example of ***Catherine cultivar*** test image (Test_CTR_10.jpg) and its box annotations.
![Test_CTR_10](https://user-images.githubusercontent.com/100839988/168625018-3f6edaa8-b7a4-4040-b20b-a9eeeb860c52.jpg)

Example of ***Royal time cultivar*** test image (Test_RT_51.jpg) and its box annotations.
![Test_RT_51](https://user-images.githubusercontent.com/100839988/168625137-fe1abbcf-1f65-43ec-9ae0-0c3d617cd82e.jpg)

Example of ***Sweet dream cultivar*** test image (Test_SD_1.jpg) and its box annotations.
![Test_SD_1](https://user-images.githubusercontent.com/100839988/168625172-e93f8f81-81a1-44a9-a501-0a47b6b6e387.jpg)

-----------------------------------------------------------------------------------------------------------------------------------------------------------
|Split|Cultivar| |Images|Labels|
|:----|:----|:----|:----|:----|
|Train|Sweet Dream| |270|2015|
| |Royal Time| |248|1066|
| |Catherine| |305|4564|
|Test|Sweet Dream| |66|453|
| |Royal Time| |63|270|
| |Catherine| |76|1480|
|Total of train| | |823|7645|
|Total of test| | |205|2203|




