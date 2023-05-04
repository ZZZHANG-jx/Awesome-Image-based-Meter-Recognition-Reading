# Awesome Image-based Meter Recognition & Reading [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)


A curated list of resources dedicated to image-based meter recognition & reading. Any suggestions and pull requests are welcome.

# Task description

In consideration of safety and cost, smart meters are still not widely installed. Conventional meters are still heavily used in energy consumption (water, electricity and gas etc.) and industrial monitoring. Automating the reading of these meters can significantly reduce labour and time costs. 

As showed in Fig. 1, there are two main categories of conventional meters: analog (with pointers and dial display) and digital (with digital wheel display). 

Given an image of meters, image-based meter recognition & reading aims to output the readings of this image. If the image is not cropped, it usually consists of two steps: detection (Det) and recognition (Recog). 

![Fig. 1](./imgs/fig1.jpg 'Fig. 1')


# Papers

|Year|Venue|Title|Repo|Task|
|----|----|-----|----|----|
|2019|Access|[Fully Convolutional Sequence Recognition Network for Water Meter Number Reading](https://ieeexplore.ieee.org/abstract/document/8606091)||Digital Recog.|
|2020|Measurement|[A pointer meter recognition method based on virtual sample generation technology](https://www.sciencedirect.com/science/article/pii/S0263224120305005)||Analog Recog.|
|2020|ISSPM|[Automatic reading algorithm of pointer water meter based on deep learning and double centroid method](https://link.springer.com/chapter/10.1007/978-981-33-4575-1_46)||Analog Det. & Recog.|
|2021|INTETAIN|[A Fast Region Segmentation Algorithm for Water Meter Image Based on Adaptive Seed Point Selection](https://link.springer.com/chapter/10.1007/978-3-030-99188-3_3)||Digital Recog.|
|2021|IAEAC|[Research on the Visual Recognition Method of Pointer Water Meter Reading](https://ieeexplore.ieee.org/abstract/document/9390735)||Analog Det. & Recog.|
|2021|FMI|[Water meter pointer reading recognition method based on target-key point detection](https://www.sciencedirect.com/science/article/pii/S0263224120305005)||Analog Det. & Recog.|
|2021|CVPRW|[Real-time analogue gauge transcription on mobile phone](https://openaccess.thecvf.com/content/CVPR2021W/MAI/html/Howells_Real-ime_Analogue_Gauge_Transcription_on_Mobile_Phone_CVPRW_2021_paper.html)||Analog Det. & Recog.|
|2021|TAI|[Vector Detection Network: An Application Study on Robots Reading Analog Meters in the Wild](https://ieeexplore.ieee.org/abstract/document/9526566)|[Code](https://github.com/DrawZeroPoint/VectorDetectionNetwork)|Analog Det. & Recog.|
|2021|Sensor|[Image-Based Automatic Watermeter Reading under Challenging Environments](https://www.mdpi.com/1424-8220/21/2/434)||Digital & Analog Det. & Recog.|
|2022|ICDSCA|[Research and Application of Pointer Meter Reading Algorithm Based on Attention U2-Net](https://ieeexplore.ieee.org/abstract/document/9987814)||Analog Recog.|
|2022|MST|[Correction and pointer reading recognition of circular pointer meter](https://iopscience.iop.org/article/10.1088/1361-6501/ac9ad4/meta)||Analog Recog.|
|2022|TIM|[Real Time Power Equipment Meter Recognition Based on Deep Learning](https://ieeexplore.ieee.org/abstract/document/9839682)||Analog Det. & Recog.|
|2022|CVPR|[It's About Time: Analog Clock Reading in the Wild](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Its_About_Time_Analog_Clock_Reading_in_the_Wild_CVPR_2022_paper.pdf)|[Code](https://github.com/charigyang/itsabouttime)|Analog Det. & Recog.|
|2022|IoTJ|[HRC-mCNNs: A Hybrid Regression and Classification Multi-branch CNNs for Automatic Meter Reading with Smart Shell](https://ieeexplore.ieee.org/abstract/document/9854084/)||Digital Det. & Recog.|


# Public available datasets
|Year|Venue|Dataset|Num.|Paper|Task|
|----|----|-----|----|----|----|
|2019|-|[WaterMeters](https://ieee-dataport.org/open-access/water-meter-dataset)|1.2K|[Water Meter Dataset](https://ieee-dataport.org/open-access/water-meter-dataset)|Digital Det. & Recog.|
|2019|Access|[SCUT-WMN](https://github.com/HCIILAB/Water-Meter-Number-DataSet)|5k|[Fully Convolutional Sequence Recognition Network for Water Meter Number Reading](https://ieeexplore.ieee.org/abstract/document/8606091)|Digital Recog.|
|2020|CCF BDCI|[BDCI2020](https://www.datafountain.cn/competitions/480/datasets)|1.5K|[真实场景下的水表读数自动识别](https://www.datafountain.cn/competitions/480)|Digital Det. & Recog.|
|2020|IJCNN|[UFPR-ADMR-v1](https://github.com/raysonlaroca/ufpr-admr-v1-dataset)|2k|[Deep Learning for Image-based Automatic Dial Meter Reading: Dataset and Baselines](https://ieeexplore.ieee.org/abstract/document/9207318)|Analog Det. & Recog.|
|2021|CVPRW|[SyntheticGauges+RealGauges](http://jjcvision.com/projects/gauge_reading.html)|11K|[Real-time analogue gauge transcription on mobile phone](https://openaccess.thecvf.com/content/CVPR2021W/MAI/html/Howells_Real-ime_Analogue_Gauge_Transcription_on_Mobile_Phone_CVPRW_2021_paper.html)|Analog Det. & Recog.|
|2021|TAI|[Pointer-10K](https://github.com/DrawZeroPoint/VectorDetectionNetwork)|10k|[Vector Detection Network: An Application Study on Robots Reading Analog Meters in the Wild](https://ieeexplore.ieee.org/abstract/document/9526566)|Analog Det. & Recog.|
|2021|Arxiv|[NRC-GAMMA](https://github.com/nrc-cnrc/NRC-GAMMA)|2.8k|[NRC-GAMMA: Introducing a Novel Large Gas Meter Image Dataset](https://arxiv.org/ftp/arxiv/papers/2111/2111.06827.pdf)|Analog Recog.|
|2022|Arxiv|[UFPR-ADMR-v2](https://github.com/guesalomon/ufpr-admr-v2-dataset)|5k|[Image-based Automatic Dial Meter Reading in Unconstrained Scenarios](https://arxiv.org/pdf/2201.02850.pdf)|Analog Det. & Recog.|
|2022|TIM|[PMIs](https://github.com/zzfan3/electric_meter_detect_recognize)|1.8k|[Real Time Power Equipment Meter Recognition Based on Deep Learning](https://ieeexplore.ieee.org/abstract/document/9839682)|Analog Det. & Recog.|
|2022|CVPR|[COCO+OpenImage](https://github.com/charigyang/itsabouttime)|1.9k+1.3k|[It's About Time: Analog Clock Reading in the Wild](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Its_About_Time_Analog_Clock_Reading_in_the_Wild_CVPR_2022_paper.pdf)|Analog Det. & Recog.|

