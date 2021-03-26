# Jupyter notebooks for 'Water Productivity and Water Accounting using WaPOR' open courseware
![](http://www.fao.org/typo3temp/pics/93f49ce381.jpg)
## [See the full course on IHE Delft OpenCourseWare](https://ocw.un-ihe.org/course/view.php?id=92&section=0)

Authors: Bich Tran, Abebe Chukalla, Solomon Seyoum

<html>
  <head>
    <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>
  </head>
</html>

## Contents

### Module 1: Introduction and Usage

- Unit 4 WaPOR spatial data analysis using Python packages
    * Download WaPOR raster data
    * Clip and resample
    * Raster calculation
- Unit 5 WaPOR API
    * Get catalog and available data table
    * Get point and area time-series
    * Get raster and crop raster
    * Get custom Water Productivity raster

### Run notebooks

**Step 1**: Download repository zipfile and unzip 

OR

Clone in Git Bash ([Git](https://git-scm.com/) needs to be installed)

    >>> git clone https://github.com/wateraccounting/WAPOROCW.git


**Step 2**: Open Anaconda prompt, change directory to folder **..\WAPOROCW\notebooks**

    >>> cd ..PATH..\WAPOROCW\notebooks
    
**Step 3**: Create a new environment from environment.yml file

    >>> conda env create
    
![](./create_env.PNG)

**Step 4**: Then activate environment with required packages

    >>> conda activate waporocw
  
**Step 5**: Start jupyter notebook

    >>> jupyter notebook
    
![](./activate_env.PNG)
