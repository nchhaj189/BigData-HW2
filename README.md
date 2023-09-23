# BigData-HW2
# Problem 2: Representational Learning with Word2Vec

## Required Packages and Frameworks:
* ```python (preferably 3.0+)```
* ```numpy```
* ```pandas```
* ```gensim```
* ```time```
* ```re```
* ```json```
* ```notebook```

## To run my code (jupyter notebook) you can run it either in Google Colab or Locally.

### To run in Google Colab: 
* Upload the notebook (BigData_HW2_Word2Vec.ipynb) file to your Google Drive.
* Then you can either right click on the file in Google Drive and click on "Open in Colaboratory", or you can go to colab.research.google.com and open the notebook from there by navigating to it to where you stored it in GDrive.
* Once you've opened the notebook, click the folder icon at the very left, looks like this:
  * ![image](https://github.com/nchhaj189/BigData-HW2/assets/15990293/8fbff43e-f1b4-4275-94d4-e31761084926)
* Then you click the file icon with an arrow in it:
  * ![image](https://github.com/nchhaj189/BigData-HW2/assets/15990293/23eb0787-7329-48ea-9aec-70079372ecae)
* This will allow you to select a file to upload from your computer. Navigate to the ```recipes.json``` dataset under the ```Dataset/``` folder of this project, and upload it.
* After uploading is complete you should see something like this and you should be able to see ```recipes.json``` in there as well:
  * ![image](https://github.com/nchhaj189/BigData-HW2/assets/15990293/15fb62e1-2194-414d-8675-5fece1cccf90)
* From here you can just run all the cells in the notebook, everything should work fine, if it doesn't you might need to adjust the ```path_to_data``` variable in the third cell, but that path should be correct for colab if you uploaded the data correctly as shown in the previous screenshot.
 
 ### To run locally:
 * Install python (if not already installed) and ensure all the packages listed in the required packages section above are installed. The ones that you would most likely need to install (if you are installing python for the first time) are numpy, pandas and gensim. However, all these packages can be installed with the ```pip install``` command. For example to install numpy you just do: ```pip install numpy```, and then replace numpy with all the other packages to install them all using pip install.
 * Open a terminal and navigate to the this project directory.
 * As long as you installed ```notebook``` you should be able to run the ```jupyter notebook``` command, which will open a browser with jupyter. From there you should be able to see my notebook, open the notebook.
 * All you have to do here is to change the ```path_to_data``` variable, in the third cell of notebook, to be the absolute path to the recipes.json file (so like the path that includes C: if on windows).
 * Once that is done, you can just run the notebook, and as long as everything is installed correctly it should work.
