# Peach Cultivars Dataset (PCD)
The **PCD** is the outcome of a collaboration between academics from the University of Beira Interior (Portugal) and the Polytechnic Institute of Castelo Branco (Portugal) to enable peach detection study using data from three different cultivars: catherine, royal time, and sweet dream. The dataset contains field images (.jpg), file annotations (.xml) for each image and files (.csv) with information about the annotations. The images have three channels (RGB) and a dimension of 640x480.
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
        ├── Annotation
        ├── Images
        └── Information

```
The following table describes the division of the dataset into training and test data, the number of images for each variety (cultivar), and the number of fruit labels.  
![Dataset](https://user-images.githubusercontent.com/100839988/168843942-aa632486-ead4-462e-8722-2fb3707d5baf.png)

## Image Sample

The next three images are examples from the test split data. The rectangular boxes are drawn with the information from the annotation files.  

***Catherine cultivar*** (Test_CTR_10.jpg)

![Test_CTR_10](https://user-images.githubusercontent.com/100839988/168625018-3f6edaa8-b7a4-4040-b20b-a9eeeb860c52.jpg)


***Royal time cultivar*** (Test_RT_51.jpg)

![Test_RT_51](https://user-images.githubusercontent.com/100839988/168625137-fe1abbcf-1f65-43ec-9ae0-0c3d617cd82e.jpg)


***Sweet dream cultivar*** (Test_SD_1.jpg)

![Test_SD_1](https://user-images.githubusercontent.com/100839988/168625172-e93f8f81-81a1-44a9-a501-0a47b6b6e387.jpg)


## Citation
Please cite this dataset as:

Assunção, E.; Gaspar, PD; Alibabaei, K.; Simões, MP; Proença, H.; Soares, VNGJ; Caldeira, JMLP Detecção de Imagem em Tempo Real para Dispositivos Edge: Uma Aplicação de Detecção de Frutos de Pêssego. Future Internet 2022 , 14 , 323. https://doi.org/10.3390/fi14110323




