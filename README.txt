README
------------------

Python Version: 3.5
I have written the code in Jupyter Notebook. All libraries
are installed with respect to this version using

>>pip install <library-name>

Required Libraries:
-------------------
jupyter notebook
json
matplotlib
plotly (and its dependencies)


How to run:
--------------------
Change the working directory to the directory consisting of the submitted assignment files.

Conserding python 3.5, Jupyter notebook and all the other dependencies are installed.

Start the notebook server by running the following command
>>jupyter notebook

Once the server starts, it will automatically open a webpage. If it doesn't you can access
it by going to localhost:8888

Select the upload menu and select the Design Challenge 3.ipynb file.

Once the notebook opens, you can start by clicking on the cell menu ->run all cells. This
will run with the default 50x15.json dataset.

To change the dataset, click on the toggle code button, and in the immediately next code section
enter the file name of the new dataset in the json_file variable. There are commented code 
examples for your reference. Now click on the cell menu -> run all below. This may take a few seconds
to run depending on the dataset. Remember to click the toggle code button to get a clean 
view of the tool.


Comments on Library:
----------------------
The library plotly provides and api using enables create interactive charts that run on D3.js which
is rendered in our Jupyter notebook. The only issue with using plotly is that, it requires an username
and api key tagged with your poorly account.