[![ADBio][adbio-logo]](https://adbio.pnnl.gov/bioviz)  
[![Visit at https://adbio.pnnl.gov](https://adbio.pnnl.gov/bioviz/services/svg/version?ver=0.02)](https://adbio.pnnl.gov/bioviz/releasenotes.html#0.02)

------

# ADBio

[ADBio](https://adbio.pnnl.gov) is a visual analytic tool built to assist in the collaborative analysis of -omics data (e.g. proteomics, transcriptomics, etc.) and allows data exploration within familiar biological contexts. The tool suite is focused on fluid navigation and easy collaboration with two main tools: Heatmap view, Pathway view<!--, and the Canvas-->. Each tool displays project data in a different way and lets domain experts explore data within a visual context that is familiar and productive. Active Data Biology is designed to be a sharable thought space. All data and analyses are versioned and backed on git.

This repository stores the code/analytics necessary to run the ADBio server. Below is a set of comprehensive tutorials with some concrete examples to help you fork/mirror/host your own version of the server. If you want to contribute code to this repository, awesome! We'd love the help. Please check the [Contribution documentation](./.github/CONTRIBUTING.md).

## How to use
ADBio is a web service that means you can use it through web browsers, supporting HTML5 and CSS3. To run check [program access](https://github.com/ActiveDataBio/Adbio/wiki/Program-Access) on the wiki page. This will explain how to get an Adbio server working on your local machine.
### Tutorial Videos
Although we post the videos below to help you get an understanding of what ADBio can do, this repository is for the webserver itself, and not a data analysis project.
* [Overview tutorial](https://youtu.be/lM12rP0Gl9Y?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Heatmap tutorial](https://youtu.be/uB0eV5jp_vA?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Pathway tutorial](https://youtu.be/9i2ijlmKcIg?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)
* [Canvas tutorial](https://youtu.be/_51_mypq_j0?list=PLdW5J6qhxuwCJIJSUcxRroYEbpOQKEeL3)

### Presentations
* [@SciData15](https://youtu.be/POC2-D3XtgU)

## How to login
After setting up the server the data repository cards should be displayed. If you're not logged in already hovering over them will display a login button. Click it and enter your user name and password for the git host you want to access. This will clone the repositories locally.

## Create an Adbio project
An Adbio project is a git repository that stores files required for Adbio to perform the vizual analytics. We have developed a simple command line tool to allow you to create all the files, refer to [CL_Create_Project](https://github.com/ActiveDataBio/CL_Create_Project) for information on creating a project.

[adbio-logo]:https://adbio.pnnl.gov/bioviz/images/activeData-biglogo.png
