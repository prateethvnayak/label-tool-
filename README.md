# label-tool-
An opensource Labelling tool given for creating PASCAL-VOC format for imagenet applications
### Labellmg - Tool for creating XML PASCAL VOC format for labels used in ImageNet.

This Repo is just a fork of the original repo - https://github.com/tzutalin/labelImg 

The repo gives the dependencies and the files required for easy launch of the Labelling tool under conda environment

Clone the repo and then create a conda environment with the `labelling-dependencies.txt`. Then we can launch the labelling tool with the following commands

`conda create --name Labelmg --file labelling-dependencies.txt`

The environment is created with the necessary dependencies. The tool is written in Python and uses the Qt-lib for GUI. 

`source activate Labelmg`

`python3 labelImg.py`

The usage of the tool can be seen in this guide video - https://www.youtube.com/watch?v=p0nR2YsCY_U&feature=youtu.be

