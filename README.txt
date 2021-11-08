Readme:


Library Installation:


Below are the terminal commands used to install each necessary Python library. Python3 and Pip must be installed and up to date as well. Instructions for installing Python and pip can be found on Python.org. The OS library loaded in the program comes pre-installed with python. 


Pandas:


        pip install pandas


Matplotlib: 


python -m pip install -U pip
python -m pip install -U matplotlib


Sklearn:


        pip install -U scikit-learn


Numpy:


pip install numpy




Running the program:


The easiest way to run the Jupyter Notebook would be to install VSCode, the open source IDE, from there you can use the search bar to download the Jupyter notebooks extensions directly. This IDE can be downloaded from: https://code.visualstudio.com/


This is available for Mac Os, Windows or Linux


Once the IDE and Jupyter notebook extension are installed and VSCode is running you may press ctrl + shift + p to open the search menu, type “Jupyter Notebook”, start running a Jupyter Notebook, then load the workspace file included in the program files using the “open workspace in project” control in VSCode’s menu. 


The Jupyter Notebook will be compatible with any Jupyter Notebook app, but you must ensure that the raw data is within the same directory folder as the code file.


From here, simply push the play button to the left of the code. Prompts will appear asking for input values for user age and vaccination rate for their local area. These require the user to type in numerals within the displayed ranges, then push enter. 


The easiest way to find an up to date vaccination rate for your area is to google “Covid-19 vaccination tracker” and the google page itself will show the vaccination rate of your county as long as your location and IP settings allow google to see this, but otherwise you may simply select your county from there, or go to the CDC tracker at https://covid.cdc.gov/covid-data-tracker/#county-view and find your county.


To save images from the program you may right click and copy them, or use the save command on the top right of the image to save on your computer directly as a PNG or PDF. Text results can be selected and copied using the mouse.


Updating and maintenance:


To keep the data up to date you must simply go to the raw data page for the CDC, click “export” and “download as csv”. Do not select “Download as csv for excel” as the program was not formatted for this. Below is the CDC link: 


https://data.cdc.gov/Vaccinations/COVID-19-Vaccination-and-Case-Trends-by-Age-Group-/gxj9-t96f


Make sure you keep the file name the same as it is suggested to download. No cleaning of the data is needed prior to loading it into the program, as the program cleans the data as part of the loading process. To replace the old data, simply delete or move the old file, and move the new one into the same folder as the Notebook Code file and workspace.