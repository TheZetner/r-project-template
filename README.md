# R Project Analysis Template - Minimal Version
_Replace this with your actual README file_

This template is meant to guide and structure your analysis projects in R whether or not you use version control (github/gitlab). Feel free to delete the contents of this readme and fill it out again with [markdown formatted text](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

The folder structure helps to organize data and scripts according to their purpose and facilitate easy reuse of project workflows on new datasets. Feel free to delete every portion that doesn't fit your needs.

This **minimal version** combines the read and tidy scripts and gets rid of the *ext* and *doc* folders.  

## Project Setup with this Template and RStudio

1. Get the latest version: click on [Releases](https://github.com/TheZetner/r-project-template/releases) above and grab the latest **Source code** zip file to your computer then unzip and rename it accordingly.  

2. Load [RStudio](https://www.rstudio.com/) (are you not using RStudio? You really should be)  

3. Click _File>New Project...>Existing Directory_  

4. Select the unzipped template folder then _Create Project_  

## Project Setup with this Template and the Command Line

1. Clone into your project folder with whatever branch you want to choose: eg. minimal or master  
    ```git clone --single-branch --branch <branchname> git@github.com:TheZetner/r-project-template.git <foldername>```  
2. Modify remotes to your new project's repository: 
    ```
    git remote rename origin old-origin
    git remote add origin https://github.com/TheZetner/<newreponame>
    ```  
3. Commit and push as normal

Start working!

---

## Explanations

Questions? [adrian.zetner@canada.ca](mailto:adrian.zetner@canada.ca)

### Files in the Main Folder

* **.gitignore**: 
    * Only matters for version control.  
    * Tells Git which files it shouldn't monitor (eg. pictures, data).  
    * Secondary `.gitignore` files can be found in data and output folders.      
* **01_read-and-tidy.R**: Script to read in raw data and do data cleaning  
* **02_plot.R**: Visualization etc from cleaned data
* **LICENSE**: MIT open source license, default for all software projects undertaken by Bioinformatics Core  
* **README**: This file. Replace it with an explanation of your project  

### Subfolders  

* **R**: Optionally store support functions in individual R files here  
* **data**: Raw data goes here. Do not modify raw data in place. This isn't Excel.  
* **output**: Script outputs (eg. cleaned data and figures)  

## Resources
An opinionated [repository template](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/)
to begin a simple analytical project with R.  
Read this blog post for more information: https://www.rostrum.blog/2019/06/11/r-repo-template/  
A git tutorial: https://guides.github.com/introduction/git-handbook/  
Project oriented workflows: https://whattheyforgot.org/project-oriented-workflow.html 