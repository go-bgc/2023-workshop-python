
## Instructions for setting up w/ Google Colab

**Getting Started**
1. Navigate to one of the notebooks [`BGC_one_float_data.ipynb`](https://github.com/go-bgc/2023-workshop-python/blob/main/BGC_one_float_data.ipynb) or [`BGC_region_data.ipynb`](https://github.com/go-bgc/2023-workshop-python/blob/main/BGC_region_float_data.ipynb) in this repository.
2. Click the "Open in Colab" button at the top of the file that looks like:
![](img/2023-08-18-14-30-43.png)
3. If needed, sign into your Google account. A standard, free, personal Google account is recommended, as not all institutional Google accounts allow Colab access to Google Drive.
4. In Google Colab, near the top menu bar, click on the button that says "Copy To Drive" ![Copy to Drive](img/2023-08-18-14-28-38.png)
5. Switch to the browser tab with the newly created "Copy of GO-BGC Workshop - Python tutorial.ipynb" file. This version is editable and is saved in your Google Drive in a folder called "Colab Notebooks." You are ready to go!

**About Google Colab:**

Colab is a free, cloud-based Jupyter notebook platform.

Cells are either code or text. To run a cell, click the button at the top left of the cell, or type `Shift`-`Enter` or `Shift`-`Return` on your keyboard.

If something isn't working, you can restart your runtime using the command in the \"Runtime\" menu.
        <br>

**Setup:**
 The first time you run the cell below, you'll be asked to navigate to a link. **Click on the link,** then give Colab permission to access Google Drive. Copy the authorization code and paste it into the Colab notebook. If you get the message, \"`Mounted at /content/drive`,\" you are ready to go!"





## Instructions for setting up on your computer

#### Below assumes that you already have git and conda installed and have some familiarity with Jupyter Notebooks

1. Clone the repository https://github.com/go-bgc/2023-workshop-python
2. create a new conda environment with necessary packages: ```conda env create -f environment.yml```
3. activate the environment ```activate gobgc```
4. launch jupyter notebook ```jupyter notebook```

*note - the first code block in each notebook (with pip install commands) is not needed and should be deleted if you have setup the gobgc conda environment*
