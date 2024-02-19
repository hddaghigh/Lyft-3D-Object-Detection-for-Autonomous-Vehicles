# Description
A U-Net fully convolutional neural network is trained to predict the presence of a car or other objects for every pixel in a bird's-eye view of the world centered on the car. This probability map can then be thresholded, and boxes can be fitted around each of the detections.




## Installation
To set up the environment for running the code, you need to install the required packages:

```bash
pip install shapely -U
pip install lyft-dataset-sdk
```

## Data Preparation
The following commands create symbolic links to the dataset directories. This is necessary for the code to access the data correctly:

```bash
ln -s /kaggle/input/3d-object-detection-for-autonomous-vehicles/train_images images
ln -s /kaggle/input/3d-object-detection-for-autonomous-vehicles/train_maps maps
ln -s /kaggle/input/3d-object-detection-for-autonomous-vehicles/train_lidar lidar
```

## Visualization and results

![Alt text](images\Animation_1.gif)

![Alt text](images\Animation_2.gif)

![Alt text](images\results_1.png)

![Alt text](images\results_2.png)

![Alt text](images\results_3.png)

![Alt text](images\results_4.png)

![Alt text](images\results_5.png)

![Alt text](images\results_6.png)

