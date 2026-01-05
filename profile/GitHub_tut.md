# GitHub Tutorial

## Overview

There are many ways to work with [__GitHub__](https://github.com/home). 
One may do so directly through one's web browser of choice (e.g. edge, firefox, etc.), or via whichever programming IDE one tends to use (e.g. Visual Studio Code, RStudio, etc.).
In this document we will provide links to existing tutorials that outline exactly how to go about using [__GitHub__](https://github.com/home) with whatever workflow one is already using.
The purpose of using [__GitHub__](https://github.com/home) is to make our lives easier, not more complicated, so the aim of this document is to get the reader up to speed on storing their 
programming scripts in this repository as quickly and painlessly as possible, while creating as small of an addition to one's normal routine as possible.

## Installing Git

If one intends to interact with [__GitHub__](https://github.com/home) remotely (i.e. to upload/download things without going to the GitHub website) 
one will need to first ensure that `Git` is installed on one's machine. If not, this step may be skipped.
To check if `Git` is installed, open a `terminal`/`PowerShell` and type:

```
git --version
```

If this commands returns a version number, you're all set! Otherwise, please follow one of these tutorials to `Git` up and running. 
For a more direct and tehcnical approach see the [Git documentation](https://github.com/git-guides/install-git).
For a more user firendly explanation try the [GitHub documentation](https://github.com/git-guides/install-git).

Note however that it is possible to use GitHub directly via a web browser without needing to install anything. 
If this approach is the most desirable please see the following section for details. 
Note however that while this may be easier/faster the first few times we want to use GitHub, in the long run this is a more labour intensive option. 
As the reader prefers.

## GitHub via web browser

As one may have noticed, the [__GitHub__](https://github.com/home) website is very developed and offers a long list of products and services. 
At its base however it rests a free service, with most of its more advanced utilities offered for free in a limited capacity.
If one's primary goal is simply the stocking and version control of programming scripts, this is not a concern.
Either way, one will need to [create an account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) to get started.
Once this has been done, a good starting point is the [Hello World Tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world).
There are a plethora of tutorials online for working with [__GitHub__](https://github.com/home), 
including many [videos on YouTube](https://www.youtube.com/results?search_query=github+tutorial+for+beginners) if one prefers to watch a video rather than read text.

## GitHub via IDE

The preferable way to work with [__GitHub__](https://github.com/home) in the long-run is via an IDE (**I**ntegrated **D**evelopment **E**nvironment). There are many and an exhaustive list is not provided here. 
If your IDE of choice is not listed here please contact Robert Schlegel (robert.schlegel@imev-mer.fr) for support. Note that the resources provided below are good, but not necessarily the only options. An internet search (and YouTube) will provide a long list of options. 
The links here have been vetted and provide a quick starting point for those who do not want to go wading through the deluge of existing content.

- [__Visual Studio Code__ - basic](https://code.visualstudio.com/docs/sourcecontrol/github)
- [__Visual Studio Code__ - student pack](https://code.visualstudio.com/learn/students/github-pack)
- [__PyCharm__ - basic](https://www.jetbrains.com/help/pycharm/github.html)
- [__RStudio__ - e-book](https://happygitwithr.com/rstudio-git-github.html)
- [__RStudio__ - for Biologists](https://r-bio.github.io/intro-git-rstudio/)
- [__Jupyter Notebooks__ - via GitHub](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/01-sharing-github/)
- [__Jupyter Notebooks__ - via terminal](https://saturncloud.io/blog/how-to-add-jupyter-notebook-to-github/)

## Creating repositories

If you are starting a new project, and computer code will represent a significant portion of the effort, it is strongly advised to create a new GitHub repository for it. This can be done via your personal GitHub account by going to the _Repository_ tab in your profile and clicking the green 'New' button. One can then follow the step-by-step instructions provided by GitHub to finish the setup process. If however the new project is contained completely within the cadre of he RiOMar project, one can also create the new repository within the [RiOMar GitHub space](https://github.com/orgs/RiOMar-projet/repositories). Click the green 'New Repository' button to get started. Once created you will want to link your local computer to this repository so pushing and pulling to it will be simple. Please see the tutorials in the __GitHub via IDE__ section for how to get this started.

## Cloning repositories

If a repository already exists, and you are interested in simply downloading the code, not contributing to it, this can be done directly through the GitHub web interface. Go to the home page of the  repository in question (e.g. [RiOMar/sat_access](https://github.com/RiOMar-projet/sat_access)), click the green 'Code' button, then the 'Download ZIP' option at the bottom of the pop-up menu. This will download the contents of the entire repository as a .zip file to your local machine. One can then unzip it and access all of the scripts etc. therein. The files/folders will be structured identical to the repository, meaning that any scripts that make calls to local files should work as anticipated.

## Contributing to repositories

If a colleague has already established a repository, and you would like to contribute to the code they've written, first ask them to grant you access. This can be found in the settings tab, then access (e.g. [RiOMar/sat_access](https://github.com/RiOMar-projet/sat_access/settings/access)). This will generate an invitation e-mail, which one must accept to finish the process. Once access is established, one must then pull the repository to one's local machine for the first time to establish the connection. Instructions for how to do so are given in the __GitHub via IDE__ section.

