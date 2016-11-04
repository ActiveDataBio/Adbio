![ADBio][adbio-logo]

[![Visit at https://adbio.pnnl.gov](https://adbio.pnnl.gov/bioviz/services/svg/version?ver=0.02)](https://adbio.pnnl.gov/bioviz/releasenotes.html#0.02)

------

# ADBio Tutorials

[ADBio](https://adbio.pnnl.gov) is a visual analytic tool that allows data exploration within familiar biological contexts. The tool suite is focused on fluid navigation and easy collaboration with three main tools: Heatmap view, Pathway view, and the Canvas. Each tool displays project data in a different way and lets domain experts explore data within a visual context that is familiar and productive. The Active Data Biology is designed to be a sharable thought space. All data and analyses are versioned and backed at Github.

This repository aims to provide a set of comprehensive tutorials with some concrete examples.

## How to use
ADBio is a web service that means you can use it through web browsers, supporting HTML5 and CSS3. For each tool, please refer to [this link](https://adbio.pnnl.gov/bioviz/FAQ.html) for the detail. Also you can find more information from the following videos. The videos have been recorded in the old version of ADBio. Nevertheless, it still provides fairly good lessons to get each tool started. We'll update these soon.

### Tutorial Videos
* [Overview tutorial](https://youtu.be/lM12rP0Gl9Y?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Heatmap tutorial](https://youtu.be/uB0eV5jp_vA?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Pathway tutorial](https://youtu.be/9i2ijlmKcIg?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Canvas tutorial](https://youtu.be/_51_mypq_j0?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)

### Presentations
* [@SciData15](https://youtu.be/POC2-D3XtgU)

## How to login
All accounts on ADBio are mirrored from Github, meaning that you use your GitHub account to work on ADBio. To log-in using your GitHub account, click the LOG-IN button which redirects you to Github.com where you can enter your user name and password, or create an account. ADBio doesn't keep your private information at all.

## How to prepare for my data
In order to create a new ADBio project using your own data, you need to prepare these two files.

* RData file: it contains the data matrix and clustering information
* Tab-delimited text file: it contains the meta data for each experiment (or each sample)  (See '[example_metadata.tsv](https://github.com/ActiveDataBio/adbio_tutorial/blob/master/example_metadata.tsv)')

### How to generate RData from my data file.
You need to install [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/) first. If you have R, please clone or download this repository in your local computer. Then, please open '[generate_rdata_hc.R](https://github.com/ActiveDataBio/adbio_tutorial/blob/master/generate_rdata_hc.R)' and run it with '[example_dataset.csv](https://github.com/ActiveDataBio/adbio_tutorial/blob/master/example_dataset.csv)'. Or please go to [here](https://github.com/ActiveDataBio/adbio_tutorial/blob/master/tutorial_1_generate_rdata.ipynb) and follow the guidelines.

### How to use a meta data file.
please go to [here](https://github.com/ActiveDataBio/adbio_tutorial/blob/master/tutorial_2_metadata.ipynb) and refer to the tutorial.

<!--
## How to upload my data
with some pictures
* Go to 'myproject' page
* Click the 'Create' tab
How to fill in the forms
How to assign tests
Bug reports
-->

[adbio-logo]:https://adbio.pnnl.gov/bioviz/images/activeData-biglogo.png
