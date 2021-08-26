# STA601  Lab0   8/26/2021

## Overview
 
In this lab 

* we will cover using RStudio on the department server or a laptop
* demonstrate using Sweave to produce pdf files using LaTeX with embedded R 


For why Reproducible Research is important read [Yihui's post](https://yihui.name/en/2012/06/enjoyable-reproducible-research/)  (and watch the video in the blog about what happened at Duke when Reproducible Research was not used!) or review CaseStudies  and materials from the 
[2021 StatSci Computing Bootcamp](https://github.com/DukeStatSci/computing-bootcamp-2021)


## Preliminaries

A couple things to get everyone on the same page,

1. If you don't have one, sign up for a GitHub account (it takes 1 min.)

  * Go to https://github.com/join
  * Enter your information
  

Ready?


## Start R Studio

If you have a StatSci account,   
   1) Open RStudio on knight [http://calc3.stat.duke.edu:8787](http://calc3.stat.duke.edu:8787) and login with your Duke netid and password.   If you are unable to login to the server  and you have connected to the Duke VPN, please see the TA or instructor.  Email clyde@duke.edu and provide your Full Name and netid so that your account can be created.
   2) Next change some RStudio preferences. Go to Rstudio -> Preferences -> Sweave and make the following two changes:
    * Select "Sweave Rnw files using Knitr"
    * Set "Preview PDF" with "System Viewer"
   3) Create a new repo to your account by clicking on the Green Use This Template 
   4) In your github account, click on the code button to copy the url for the repository
   5) Create a new Project.  In RStudio, click on New Project in the file menu.  Select Version Control, then Git. Enter the  the  Repository URL field, provide a name for the project, e.g. 'lab0', and select a directory to save your work, e.g. Lab0    We suggest that you make a folder for STA601 to save your work for the course.
  5) On the lower right panel in RStudio, click on the Files tab. You should see a listing of the files in your directory. Click on `lab1.Rnw` to open it in the RStudio editor and then follow instructions there.  
   
  


  For more on getting started using RStudio and git see the StatSci ComputingBootcamp slides & videos
  
For more info on Sweave in Rstudio see the [RPubs page](https://rpubs.com/YaRrr/SweaveIntro))
