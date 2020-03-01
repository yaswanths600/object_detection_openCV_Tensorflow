
#made by: p yashwant sai, venkat ramiya
#contact details: yashwamnts600@gmail.com
#note: kindly dont send me any pull request as i have already closed this project and looking to improve it further

# object_detection_openCV_Tensorflow
object detection (real-time) using openCV


#Overview:

This repository contains the code for real time object detection.

There is two approach given here. 
1. Base line or basic approach
2. revised approach

## Dependencies and installation
For base line approach there are following libraries which are needed.

* imutils: `$ sudo pip install imutils`
* Install computervision or CV2 from [here](https://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/)
* time - default library of python
* numpy - `$ sudo pip install numpy`

For revised approach there are following libraries which are needed.

* os - default library of python
* Install computervision or CV2 from [here](https://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/) 
* time - default library of python
* argparse - default library of python
* multiprocessing - default library of python
* numpy `$ sudo pip install numpy`
* tensorflow - You can refer [this link](https://www.tensorflow.org/install/install_linux)


## Usage

#### Run base line approach using following execution steps.
```
1. Go to the base_line_model folder.
    $ cd ./base_line_model
2. To run the script execute following command.
    $ python object_detection_app.py

```

#### Run revised approach using following execution steps.

```
1. Go to the revised_approach folder.
    $ cd ./revised_approach
2. To run the script execute following command.
    $ python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel 

```


