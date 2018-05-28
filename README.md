## Advanced Lane Finding
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

This repo contains the code written to complete the project **Advanced Lane Finding** on Udacity Self-Driving Car Nanodegree. The goal is detect lane lines from images (and video) taken from a camera at the from of a car.

Prerequisites
---
To run this project, you need [Anaconda 4.3.30](https://anaconda.org/conda-canary/conda/files?version=4.3.30) installed.

Installation
---
First, clone the repository:
```
git clone https://github.com/shohne/CarND-Advanced-Lane-Lines.git
```
Change current directory:
```
cd CarND-Advanced-Lane-Lines
```
Create a conda environment with all dependencies:
```
conda env create -f environment.yml
```
The name of created environment is *lane-advanced*.

Running the Notebook
---
Activate the created conda environment:
```
source activate lane-advanced
```
And run Jupyter Notebook:
```
jupyter notebook P4.ipynb
```
Implementation Details
---
Please visit the [report.md](report.md) for more information about the algorithm pipeline and its shortcomings.

Ouput and List of Files
---
As an example of produced video running the iPython Notebook:

[project_video.mp4](output/project_video.mp4)

Some usefull files and folders in this project:

- **P4.ipynb** iPython Notebook with the implementation;
- **environment.yaml** used to create conda environment;
- **report.md** detailed description of pipeline;
