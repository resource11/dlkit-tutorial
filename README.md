Basic DLKit tutorial, to run in Jupyter Notebook (formerly iPython Notebook).

The instructions below are for Python 2.7. You may need to modify the
`pip` install instructions for Python 3.

````
$ pip install -r requirements.txt
$ git submodule init
$ git submodule update --init --recursive
````
Then, to open the notebook:

````
$ jupyter notebook
````

Open `DLKit Tutorial` in your browser (http://localhost:8888/tree).

Note that all data generated with this tutorial is saved in JSON files to your harddrive, in a folder called `tutorial-data`, sibling to this `README`. If you ever want to start over, just delete that folder and all its contents.
