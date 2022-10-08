# Awesome Image-based Meter Recognition & Reading [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)


A curated list of resources dedicated to image-based meter recognition & reading. Any suggestions and pull requests are welcome.

# Task description

In consideration of safety and cost, smart meters are still not widely installed. Conventional meters are still heavily used in energy consumption (water, electricity and gas etc.) and industrial monitoring. Automating the reading of these meters can significantly reduce labour and time costs. 

As showed in Fig. 1, there are two main categories of conventional meters: analog (with pointers and dial display) and digital (with digital wheel display). 

Given an image of meters, image-based meter recognition & reading aims to output the readings of this image (if the image is not cropped, it usually consists of two steps: detection and recognition). 

![Fig. 1](./imgs/fig1.jpg 'Fig. 1')


# Papers

|Year|Conf.|Title|Repo|
|----|----|-----|----|
|2019|Access|[Fully Convolutional Sequence Recognition Network for Water Meter Number Reading](https://ieeexplore.ieee.org/abstract/document/9526566)||
|2021|TAI|[Vector Detection Network: An Application Study on Robots Reading Analog Meters in the Wild](https://ieeexplore.ieee.org/abstract/document/9526566)|[Code](https://github.com/DrawZeroPoint/VectorDetectionNetwork)|
|2022|TIM|[Real Time Power Equipment Meter Recognition Based on Deep Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Its_About_Time_Analog_Clock_Reading_in_the_Wild_CVPR_2022_paper.pdf)|
|2022|CVPR|[It's About Time: Analog Clock Reading in the Wild]()|[Code](https://github.com/charigyang/itsabouttime)|
|2022|IoTJ|[HRC-mCNNs: A Hybrid Regression and Classification Multi-branch CNNs for Automatic Meter Reading with Smart Shell](https://ieeexplore.ieee.org/abstract/document/9854084/)||


# Public available datasets
|Year|Conf.|Dataset|Num.|Paper|Type|
|----|----|-----|----|----|----|
|2019|Access|[SCUT-WMN](https://github.com/HCIILAB/Water-Meter-Number-DataSet)|5k|[Fully Convolutional Sequence Recognition Network for Water Meter Number Reading](https://ieeexplore.ieee.org/abstract/document/9526566)|Digital|
|2020|IJCNN|[UFPR-ADMR-v1](https://github.com/raysonlaroca/ufpr-admr-v1-dataset)|2k|[Deep Learning for Image-based Automatic Dial Meter Reading: Dataset and Baselines](https://ieeexplore.ieee.org/abstract/document/9207318)|Analog|
|2021|TAI|[Pointer-10K](https://github.com/DrawZeroPoint/VectorDetectionNetwork)|10k|[Vector Detection Network: An Application Study on Robots Reading Analog Meters in the Wild](https://ieeexplore.ieee.org/abstract/document/9526566)|Analog|
|2021|Arxiv|[NRC-GAMMA](https://github.com/nrc-cnrc/NRC-GAMMA)|2.8k|[NRC-GAMMA: Introducing a Novel Large Gas Meter Image Dataset](https://arxiv.org/ftp/arxiv/papers/2111/2111.06827.pdf)|Analog|
|2022|Arxiv|[UFPR-ADMR-v2](https://github.com/guesalomon/ufpr-admr-v2-dataset)|5k|[Image-based Automatic Dial Meter Reading in Unconstrained Scenarios](https://arxiv.org/pdf/2201.02850.pdf)|Analog|
|2022|TIM|[PMIs](https://github.com/zzfan3/electric_meter_detect_recognize)|1.8k|[Real Time Power Equipment Meter Recognition Based on Deep Learning](https://ieeexplore.ieee.org/abstract/document/9839682)|Analog|
|2022|CVPR|[COCO+OpenImage](https://github.com/charigyang/itsabouttime)|1.9k+1.3k|[It's About Time: Analog Clock Reading in the Wild](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Its_About_Time_Analog_Clock_Reading_in_the_Wild_CVPR_2022_paper.pdf)|Analog|

