# Landmark Detection & Robot Tracking (SLAM)

## Project Overview

A project to implement 2D SLAM (Simultaneous Localization and Mapping).
The starting repo can be fournd [here](https://github.com/udacity/P3_Implement_SLAM).




__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking 



### Local Environment Instructions

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/udacity/P3_Implement_SLAM.git
cd P3_Implement_SLAM
```

2. Create (and activate) a new environment, named `cv-nd` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n cv-nd python=3.6
	source activate cv-nd
	```
	- __Windows__: 
	```
	conda create --name cv-nd python=3.6
	activate cv-nd
	```
	
	At this point your command line should look something like: `(cv-nd) <User>:P3_Implement_SLAM <user>$`. The `(cv-nd)` indicates that your environment has been activated, and you can proceed with further package installations.

6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```


## Notebooks

1. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd
cd P3_Implement_SLAM
```

2. Open the directory of notebooks, using the below command. You'll see all of the project files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

3. Once you open any of the project notebooks, make sure you are in the correct `cv-nd` environment by clicking `Kernel > Change Kernel > cv-nd`.

__NOTE:__ While some code has already been implemented to get you started, you will need to implement additional functionality and answer all of the questions included in the notebook. __Unless requested, it's suggested that you do not modify code that has already been included.__


## Note for further reading
https://robotics.stackexchange.com/questions/9318/understanding-drift-in-simultaneous-localization-and-mapping-slam
https://github.com/devendrachaplot/Neural-Localization




LICENSE: This project is licensed under the terms of the MIT license.
