# R Project Analysis Template
_Replace this with your actual README file_

This template is meant to guide and structure your analysis projects in R whether or not you use version control (github/gitlab). Feel free to delete the contents of this readme and fill it out again with [markdown formatted text](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

The folder structure helps to organize data and scripts according to their purpose and facilitate easy reuse of project workflows on new datasets. Feel free to delete every portion that doesn't fit your needs.

## Project Setup with this Template and RStudio

1. Get the latest version one of two ways:  
    * Download a zip file of the template by clicking [![](https://raw.githubusercontent.com/TheZetner/picturehosting/master/clone-or-download.png)](#) - includes git information, be sure to change to your own config
        * Change the remote to your new project:  ```git remote set-url origin git@github.com:<USERNAME>/<PROJECTNAME>.git```
        
    * Click on [Releases](https://github.com/TheZetner/r-project-template/releases) above and grab the latest **Source code** zip file to your computer.  

2. Unzip where you want the project to live on your computer (eg. Documents/R_projects/), rename the folder, update git information if using version control. (eg `rm .git*` will remove the git folder and ignore file)  

3. Load [RStudio](https://www.rstudio.com/) (are you not using RStudio? You really should be)  

4. Click _File>New Project...>Existing Directory_  

5. Select the unzipped template folder then _Create Project_  

Start working!

---

## Explanations

Questions? [adrian.zetner@canada.ca](mailto:adrian.zetner@canada.ca)

### Files in the Main Folder

* **.gitignore**: 
    * Only matters for version control.  
    * Tells Git which files it shouldn't monitor (eg. pictures, data).  
    * Secondary `.gitignore` files can be found in data and output folders.      
* **01_read.R**: Set up script to read in raw data and do basic cleaning  
* **02_tidy.R**: Advanced cleaning and modification of data  
* **03_model.R**: Statistical modelling from cleaned data
* **LICENSE**: MIT open source license, default for all software projects undertaken by Bioinformatics Core  
* **README**: This file. Replace it with an explanation of your project  

### Subfolders  

* **R**: Optionally store support functions in individual R files here  
* **data**: Raw data goes here. Do not modify raw data in place. This isn't Excel.  
* **output**: Script outputs (eg. cleaned data and figures)  
* **ext**: External sources like statistical models  
* **doc**: R markdown documents explaining the analysis

## Resources
An opinionated [repository template](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/)
to begin a simple analytical project with R.  
Read this blog post for more information: https://www.rostrum.blog/2019/06/11/r-repo-template/  
A git tutorial: https://www.learnenough.com/git-tutorial/getting_started
Project oriented workflows: https://whattheyforgot.org/project-oriented-workflow.html 