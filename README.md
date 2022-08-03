# D-Lab's R Research Design Workshop

This repository contains the materials for D-Lab's Research Design with R workshop. Prior experience with the material in [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals) and [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang) is preferred.

## Workshop Goals

In this workshop, we provide an introduction to the basics of Research Design using the R programming languaage. 

## Installation Instructions

We will use RStudio to go through the workshop materials, which requires installation of both the R language and the RStudio software. Complete the following steps:

1. [Download R](https://cloud.r-project.org/): Follow the links according to the operating system that you are running. Download the package, and install R onto your compute. You should install the most recent version (at least version 4.0).
2. [Download RStudio](https://rstudio.com/products/rstudio/download/#download): Install RStudio Desktop. This should be free. Do this after you have already installed R. The D-Lab strongly recommends an RStudio edition of 2022.02.0+443 "Prairie Trillium" or higher.
3. [Download these workshop materials](https://github.com/dlab-berkeley/R-Research-Design): 

4. Make sure to install the `tidyverse` and `DeclareDesign` packages. 

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

4. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/R-Research-Design.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Launch the RStudio software.

2. Use the file navigator to find the `R-Research-Design` folder that you downloaded from Github.

3. Double click on the `R-Research-Design.Rproj` file, and click "yes" when RStudio asks you to confirm whether you want to open up the project.

4. Open up the `R-Data-Visualization.Rmd` file, located in the `lessons` folder.

5. If you do not have the `cowplot`, `dplyr`, `ggplot2`, and `here` packages installed, be sure to install them using the `install.packages()` function in the first code block of the `R-Data-Visualization.Rmd` file.

6. Run a chunk of code by clicking the green "play" button in the upper right hand corner of each code chunk. Alternatively, place your cursor on a given line and press "Command + Enter" (Mac) or "Control + Enter" (PC) to run an individual line of code. 

7. The file `R-Research-Design-Challenges.qmd` contains space for you to work on five challenge problems. The file `R-Research-Design-Challenges-Solutions.Rmd` contains the solutions to these challenges. 

## Is R not working on your laptop?

If you do not have R installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. 

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in an RStudio instance on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `R-Research-Design` folder.


# Additional Resources

Check out the following resources to learn more about data visualization and R:

* [Field Experiments: Design, Analysis, and Interpretation](https://wwnorton.com/books/9780393979954)  
* [Research Design: Declare, Diagnose, Redesign](https://book.declaredesign.org/index.html)
* [Evidence in Governing and Policy Methods Guides](https://egap.org/methods-guides/)  
* [Open Science Framework](https://osf.io/) 
* [Impact Evaluation in Practice](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice)  
* [Causal Inference: The Mixtape](https://mixtape.scunning.com/)

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab R Workshops

Here are other R workshops offered by the D-Lab:

## Basic Competency

* [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals)
* [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang)
* [R Functional Programming](https://github.com/dlab-berkeley/R-functional-programming)
* [Geospatial Fundamentals in R with sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)
* [Census Data in R](https://github.com/dlab-berkeley/Census-Data-in-R)

## Intermediate/Advanced Competency

* [Advanced Data Wrangling in R](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R)
* [Unsupervised Learning in R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R)
* [R Machine Learning with tidymodels](https://github.com/dlab-berkeley/Machine-Learning-with-tidymodels)
* [Introduction to Deep Learning in R](https://github.com/dlab-berkeley/Deep-Learning-in-R)
* [R Package Development](https://github.com/dlab-berkeley/R-package-development)

# Contributors
* [Alexander Stephenson](https://dlab.berkeley.edu/people/alex-stephenson)


