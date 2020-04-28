## Getting started
1. Create a working directory
```
$ mkdir <work-directory>
$ cd <work-directory>
```
## Create a virtual environment
2. Copy the requirements.txt file and all of the remaining files into the working directory. Then create a virtual environment by running the following commands
```
$ python3 -m venv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

To access the notebooks, run the following command
```
$ jupyter notebook
```
then  the source code LinearSVC.ipynb notebook can be accessed. The model is saved and loaded into the test_classifier.ipynb notebook (contain trained model). The file how_ping_works.pdf contain information about the architecture of the model and other answered questions regarding the model.